# Aviyon SQL

**Role**: Truth database (BigQuery + Postgres)
**Syntax**: SQL + ULE + nimbus.ai
**Execution**: Distributed, versioned
**Integration**: Grid, Drive
**Use Case**: Vagabond inventory truth


``` laviysql
SELECT stock FROM Vagabond
WHERE ULE.auth AND nimbus.predict(low<10)
AUTO RESTOCK;
```
