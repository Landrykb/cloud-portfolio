# EV Charging Network: Multi-Region Architecture

**Skills:** `global-accelerator`, `dynamodb-global`, `lambda`, `ocpp`

## Description

EV charging backends need low-latency global availability. OCPP chargers → API Gateway → Lambda → DynamoDB Global Tables for multi-region session state, with Global Accelerator routing, CloudWatch charger health, and weekly carbon-avoided reports via Athena.

