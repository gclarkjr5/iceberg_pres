# Database vs Data Lake

What does a database have that a data lake didn't?

- Schema of the dataset
    - columns present
    - varieties of data types present
- Coordination of changes to the dataset
    - DDL (data definition)
        ```sql
        ALTER TABLE table_a ADD COLUMN b int;
        ```
    - DML (data modification) -> inserts, updates, deletes, etc.
        ```sql
        UPDATE table_a SET b = b + 1;
        ```