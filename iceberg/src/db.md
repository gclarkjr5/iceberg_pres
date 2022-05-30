# Why not just use a database?

Pros:
- great optimizations on the data they contain
- often times fit very well as the source of the BI layer

Cons:
- closed proprietary systems
    - everything must go through the database for processing
- vendor lock-in
    - limited flexibility
    - increased cost w/ all access routing through a single system
        - w/ iceberg, the data is operated on in place, no need to send data to another separate system