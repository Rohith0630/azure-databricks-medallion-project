## 🟤 Bronze Layer – Raw Ingestion

This layer is responsible for ingesting raw Formula 1 dataset files into Delta tables.

### Responsibilities
- Read raw CSV files from source
- Apply minimal transformations
- Store data in Delta format
- Preserve original structure for traceability

### Output
Raw Delta tables used as input for Silver layer processing.
