# Satellite NDVI Processing Pipeline

**Skills:** `s3`, `lambda`, `batch`, `earth-observation`

## Description

NDVI measures plant health from satellite imagery — high NDVI means healthy vegetation and more carbon sequestered.

Architecture: Sentinel-2 images land in S3 → Lambda queues jobs → AWS Batch runs NDVI compute (Python + rasterio) → results in S3 + metadata in DynamoDB → API Gateway exposes per-plot scores. Same NDVI data as the BleepxQuery farming domain — now you build the cloud that produces it.

