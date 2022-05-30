# Apache Iceberg

- a table format
    - abstraction between physical data files and how they are structured to form a table
- created by Netflix & Apple
- 100% open-source
- supports common standard file formats (parquet, avro, orc)
- supported by common data lake engines (spark, hive, presto/trino, dremio)
- transactional consistency
    - data modification can occur concurrently with isolation
- tracks the evolution of the data and its schema