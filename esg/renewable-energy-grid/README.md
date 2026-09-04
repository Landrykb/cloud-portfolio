# Renewable Energy Grid Monitoring on AWS

**Skills:** `kinesis`, `timestream`, `grafana`, `iot`

## Description

A solar + wind operator needs real-time monitoring. Power sensors → Kinesis Data Streams → Lambda aggregates into 5-min windows → Timestream → Managed Grafana dashboards, with EventBridge alarms on SLA breaches. Bonus: compute CO2-equivalent avoided per kWh and feed the carbon pipeline.

