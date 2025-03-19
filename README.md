# Real-Time-Data-Streaming-DataEngineering-Project.
This End-to-End Data Engineering Project demonstrates a scalable and efficient real-time data streaming pipeline using modern tools and technologies. You can extend this pipeline to handle various data sources, processing, and storage solutions, and use it for different use cases like IoT data collection, real-time analytics, and monitoring.

The project is designed with the following components:

Data Source: We use randomuser.me API to generate random user data for our pipeline.

Apache Airflow: Responsible for orchestrating the pipeline and storing fetched data in a PostgreSQL database.

Apache Kafka and Zookeeper: Used for streaming data from PostgreSQL to the processing engine.

Control Center and Schema Registry: Helps in monitoring and schema management of our Kafka streams.

Apache Spark: For data processing with its master and worker nodes.

Cassandra: Where the processed data will be stored.
