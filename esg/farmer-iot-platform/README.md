# Farmer IoT Platform: Soil Sensor to Carbon Credit

**Skills:** `iot-core`, `timestream`, `lambda`, `s3`

## Description

End-to-end architecture for smallholder farmers:
1. ESP32 + LoRa sensor sends soil data over LoRaWAN.
2. AWS IoT Core receives messages.
3. Lambda validates + transforms readings.
4. Timestream stores the time series.
5. Lambda computes monthly carbon sequestration estimates.
6. Results become carbon-credit candidates (QLDB).
7. SNS notifies a verification agent for field audit.

