### 1. What is Amazon DynamoDB?
Amazon DynamoDB is a fully managed NoSQL database service that provides fast and predictable performance with seamless scalability. It's designed to handle massive amounts of structured data across various use cases.

### 2. How does Amazon DynamoDB work?
DynamoDB stores data in tables, each with a primary key and optional secondary indexes. It automatically replicates data across multiple Availability Zones for high availability and durability.

### 3. What types of data models does Amazon DynamoDB support?
DynamoDB supports both document data model (key-value pairs) and columnar data model (tables with items and attributes). It's well-suited for a variety of applications, from simple key-value stores to complex data models.

### 4. What are the key features of Amazon DynamoDB?
Key features of DynamoDB include automatic scaling, multi-master replication, global tables for global distribution, support for ACID transactions, and seamless integration with AWS services.

### 5. What is the primary key in Amazon DynamoDB?
The primary key is used to uniquely identify items within a table. It consists of a partition key (and optional sort key), which determines how data is distributed and stored.

### 6. How does partitioning work in Amazon DynamoDB?
DynamoDB divides a table's data into partitions based on the partition key. Each partition can store up to 10 GB of data and handle a certain amount of read and write capacity.