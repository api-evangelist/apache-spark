# Apache Spark (apache-spark)
Apache Spark is a unified analytics engine for large-scale data processing. It provides high-level APIs in Java, Scala, Python, and R, and an optimized engine that supports general execution graphs. Spark offers a comprehensive suite of APIs for batch processing, SQL queries, streaming analytics, machine learning, and graph computation, governed by the Apache Software Foundation.

**URL:** [https://spark.apache.org/](https://spark.apache.org/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Analytics, Big Data, Distributed Computing, Machine Learning, Open Source, Streaming

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-19

## APIs

### Apache Spark REST API
REST API for monitoring Spark applications, accessing cluster information, and managing Spark jobs through the Spark UI backend. Exposes endpoints for applications, jobs, stages, tasks, storage, environment, and executors.

**Human URL:** [https://spark.apache.org/docs/latest/monitoring.html#rest-api](https://spark.apache.org/docs/latest/monitoring.html#rest-api)

#### Tags:

 - Jobs, Metrics, Monitoring, Stages

#### Properties

- [Documentation](https://spark.apache.org/docs/latest/monitoring.html#rest-api)

### Apache Spark SQL API
Spark module for structured data processing with DataFrame and Dataset APIs. Provides a SQL interface and supports various data sources including Parquet, ORC, JSON, CSV, JDBC, Hive, and Delta Lake.

**Human URL:** [https://spark.apache.org/docs/latest/sql-programming-guide.html](https://spark.apache.org/docs/latest/sql-programming-guide.html)

#### Tags:

 - DataFrames, SQL, Structured Data

#### Properties

- [Documentation](https://spark.apache.org/docs/latest/sql-programming-guide.html)
- [Scala API Reference](https://spark.apache.org/docs/latest/api/scala/org/apache/spark/sql/index.html)
- [Python API Reference](https://spark.apache.org/docs/latest/api/python/reference/pyspark.sql/index.html)
- [Java API Reference](https://spark.apache.org/docs/latest/api/java/index.html?org/apache/spark/sql/package-summary.html)

### Apache Spark Streaming API
Scalable, high-throughput, fault-tolerant stream processing with Structured Streaming, exactly-once semantics, and integration with Kafka, Kinesis, HDFS, and other sources.

**Human URL:** [https://spark.apache.org/docs/latest/structured-streaming-programming-guide.html](https://spark.apache.org/docs/latest/structured-streaming-programming-guide.html)

#### Tags:

 - Data Processing, Real-Time, Streaming

#### Properties

- [Documentation](https://spark.apache.org/docs/latest/structured-streaming-programming-guide.html)
- [Scala Streaming API](https://spark.apache.org/docs/latest/api/scala/org/apache/spark/streaming/index.html)
- [Python Streaming API](https://spark.apache.org/docs/latest/api/python/reference/pyspark.streaming/index.html)

### Apache Spark MLlib API
Spark's scalable machine learning library with classification, regression, clustering, collaborative filtering, and pipeline-based ML workflows.

**Human URL:** [https://spark.apache.org/docs/latest/ml-guide.html](https://spark.apache.org/docs/latest/ml-guide.html)

#### Tags:

 - Algorithms, Data Science, Machine Learning, ML

#### Properties

- [Documentation](https://spark.apache.org/docs/latest/ml-guide.html)
- [Scala MLlib API](https://spark.apache.org/docs/latest/api/scala/org/apache/spark/ml/index.html)
- [Python MLlib API](https://spark.apache.org/docs/latest/api/python/reference/pyspark.ml.html)

### Apache Spark GraphX API
Spark API for graphs and graph-parallel computation with PageRank, Connected Components, Triangle Counting, and shortest path algorithms.

**Human URL:** [https://spark.apache.org/docs/latest/graphx-programming-guide.html](https://spark.apache.org/docs/latest/graphx-programming-guide.html)

#### Tags:

 - Analytics, Graph Processing, Graphs

#### Properties

- [Documentation](https://spark.apache.org/docs/latest/graphx-programming-guide.html)
- [Scala GraphX API](https://spark.apache.org/docs/latest/api/scala/org/apache/spark/graphx/index.html)

## Common Properties

- [GitHubRepository](https://github.com/apache/spark)
- [Portal](https://spark.apache.org/)
- [Documentation](https://spark.apache.org/docs/latest/)
- [GettingStarted](https://spark.apache.org/docs/latest/quick-start.html)
- [Blog](https://spark.apache.org/news/)
- [Support](https://spark.apache.org/community.html)
- [TermsOfService](https://www.apache.org/licenses/LICENSE-2.0)
- [StackOverflow](https://stackoverflow.com/questions/tagged/apache-spark)
- [PySpark (Python)](https://pypi.org/project/pyspark/)
- [Maven (Scala/Java)](https://search.maven.org/search?q=g:org.apache.spark)

## Features

| Name | Description |
|------|-------------|
| Unified Analytics Engine | Single engine for batch, streaming, SQL, ML, and graph processing workloads. |
| Lazy Evaluation and DAG Execution | Optimized execution plans with Catalyst optimizer and DAG scheduling. |
| In-Memory Processing | Up to 100x faster than Hadoop MapReduce for iterative algorithms via in-memory caching. |
| Structured Streaming | Unified streaming and batch processing with exactly-once semantics and Kafka integration. |
| Multi-Language Support | High-level APIs in Scala, Java, Python (PySpark), and R (SparkR). |
| Delta Lake Integration | ACID transactions, schema evolution, and time travel for data lakes. |
| Kubernetes Native | Native Kubernetes scheduling for cloud-native deployment of Spark workloads. |

## Use Cases

| Name | Description |
|------|-------------|
| Large-Scale ETL | Extract, transform, and load petabytes of data across distributed clusters. |
| Real-Time Analytics | Streaming analytics on live event data with sub-second latency. |
| Machine Learning Pipelines | Distributed ML training and feature engineering at scale with MLlib. |
| Data Lake Processing | Query and transform data stored in cloud object stores and HDFS. |
| Interactive SQL Analytics | Interactive SQL queries on structured and semi-structured data at scale. |

## Integrations

| Name | Description |
|------|-------------|
| Apache Hadoop | HDFS storage, YARN cluster manager, and Hadoop ecosystem integration. |
| Apache Kafka | Structured Streaming source and sink for real-time event processing. |
| Delta Lake | Open-source storage layer with ACID transactions for data lakes. |
| Apache Iceberg | Open table format for huge analytic datasets on cloud storage. |
| Apache Hive | Hive metastore integration for table catalog and metadata management. |
| Kubernetes | Native Kubernetes scheduling for cloud-native Spark deployments. |
| Apache Airflow | Workflow orchestration for scheduling and managing Spark jobs. |

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
