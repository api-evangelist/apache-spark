# Apache Spark (apache-spark)

Apache Spark is a unified analytics engine for large-scale data processing. It provides high-level APIs in Java, Scala, Python, and R, and an optimized engine that supports general execution graphs. Spark offers a comprehensive suite of APIs for batch processing, SQL queries, streaming analytics, machine learning, and graph computation, governed by the Apache Software Foundation.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/apache-spark/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apache-spark/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Analytics
- Big Data
- Distributed Computing
- Machine Learning
- Open Source
- Streaming

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Apache Spark REST API

REST API for monitoring Spark applications, accessing cluster information, and managing Spark jobs through the Spark UI backend. Exposes endpoints for applications, jobs, stages, tasks, storage, environment, executors, and streaming statistics on port 4040 (or 18080 for Spark History Server).

- **Human URL:** [https://spark.apache.org/docs/latest/monitoring.html#rest-api](https://spark.apache.org/docs/latest/monitoring.html#rest-api)

#### Tags

- Jobs
- Metrics
- Monitoring
- Stages

#### Properties

- [Documentation](https://spark.apache.org/docs/latest/monitoring.html#rest-api)
- [OpenAPI](openapi/apache-spark-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/apache-spark.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-spark.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Apache Spark SQL API

Spark module for structured data processing with DataFrame and Dataset APIs. Provides a SQL interface and supports various data sources including Parquet, ORC, JSON, CSV, JDBC, Hive, and Delta Lake. The Spark SQL API supports Scala, Python, Java, and R bindings.

- **Human URL:** [https://spark.apache.org/docs/latest/sql-programming-guide.html](https://spark.apache.org/docs/latest/sql-programming-guide.html)

#### Tags

- DataFrames
- SQL
- Structured Data

#### Properties

- [Documentation](https://spark.apache.org/docs/latest/sql-programming-guide.html)
- [SDK](https://spark.apache.org/docs/latest/api/scala/org/apache/spark/sql/index.html)
- [SDK](https://spark.apache.org/docs/latest/api/python/reference/pyspark.sql/index.html)
- [SDK](https://spark.apache.org/docs/latest/api/java/index.html?org/apache/spark/sql/package-summary.html)
- [Postman Collection](collections/apache-spark.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-spark.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Apache Spark Streaming API

Scalable, high-throughput, fault-tolerant stream processing of live data streams. Supports Structured Streaming (the newer DStream-based API) with exactly-once semantics, continuous processing mode, and integration with Kafka, Kinesis, HDFS, and other sources.

- **Human URL:** [https://spark.apache.org/docs/latest/structured-streaming-programming-guide.html](https://spark.apache.org/docs/latest/structured-streaming-programming-guide.html)

#### Tags

- Data Processing
- Real-Time
- Streaming

#### Properties

- [Documentation](https://spark.apache.org/docs/latest/structured-streaming-programming-guide.html)
- [SDK](https://spark.apache.org/docs/latest/api/scala/org/apache/spark/streaming/index.html)
- [SDK](https://spark.apache.org/docs/latest/api/python/reference/pyspark.streaming/index.html)
- [Postman Collection](collections/apache-spark.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-spark.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Apache Spark MLlib API

Spark's scalable machine learning library consisting of common learning algorithms and utilities, including classification, regression, clustering, collaborative filtering, dimensionality reduction, and feature engineering. Supports pipeline-based ML workflows through the spark.ml package.

- **Human URL:** [https://spark.apache.org/docs/latest/ml-guide.html](https://spark.apache.org/docs/latest/ml-guide.html)

#### Tags

- Algorithms
- Data Science
- Machine Learning
- ML

#### Properties

- [Documentation](https://spark.apache.org/docs/latest/ml-guide.html)
- [SDK](https://spark.apache.org/docs/latest/api/scala/org/apache/spark/ml/index.html)
- [SDK](https://spark.apache.org/docs/latest/api/python/reference/pyspark.ml.html)
- [Postman Collection](collections/apache-spark.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-spark.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Apache Spark GraphX API

Spark API for graphs and graph-parallel computation with a collection of graph algorithms and builders, including PageRank, Connected Components, Triangle Counting, and shortest paths.

- **Human URL:** [https://spark.apache.org/docs/latest/graphx-programming-guide.html](https://spark.apache.org/docs/latest/graphx-programming-guide.html)

#### Tags

- Analytics
- Graph Processing
- Graphs

#### Properties

- [Documentation](https://spark.apache.org/docs/latest/graphx-programming-guide.html)
- [SDK](https://spark.apache.org/docs/latest/api/scala/org/apache/spark/graphx/index.html)
- [Postman Collection](collections/apache-spark.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/apache-spark.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/apachespark)
- [GitHub Repository](https://github.com/apache/spark)
- [Portal](https://spark.apache.org/)
- [Documentation](https://spark.apache.org/docs/latest/)
- [Getting Started](https://spark.apache.org/docs/latest/quick-start.html)
- [Blog](https://spark.apache.org/news/)
- [Support](https://spark.apache.org/community.html)
- [Terms of Service](https://www.apache.org/licenses/LICENSE-2.0)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/apache-spark)
- [SDK](https://pypi.org/project/pyspark/)
- [SDK](https://search.maven.org/search?q=g:org.apache.spark)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
