# ADF Incremental Pipeline

## Description
Metadata-driven Azure Data Factory pipeline to load data incrementally from Azure SQL to Blob storage using watermark logic.

## Features
- ForEach loop for multiple tables
- High watermark pattern (safe incremental load)
- Supports ID and DateTime watermark
- Late-arriving handling using overlap
- Dynamic file naming
- Audit logging

## Technologies
- Azure Data Factory
- Azure SQL Database
- Azure Blob Storage

## Author
Sidd1z
``
