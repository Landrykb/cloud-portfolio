# ESG Data Pipeline on AWS

**Skills:** `s3`, `glue`, `athena`, `quicksight`

## Description

Architecture: farm IoT sensors → S3 raw zone → Glue ETL → Athena query → QuickSight dashboard.

*Scenario:* a cooperative of 200 smallholder farmers in Benin, each with a soil-moisture + CO2 sensor. Data lands hourly in S3; Glue transforms it; Athena queries it; QuickSight visualizes carbon sequestration per hectare per month.

