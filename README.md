# Apache Spark (apache-spark)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
