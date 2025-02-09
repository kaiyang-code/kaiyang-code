## About
My name is Kaiyang, and I am a master's student at Carnegie Mellon University. I have always been fascinated by the world of programming, and I consider myself lucky to have found a career that aligns with my passions.
Throughout my career, I have had the opportunity to work with a variety of programming languages and technologies, which has allowed me to grow and develop as a programmer. While I have gained a considerable amount of knowledge and experience from working for an early-stage startup, a big tech company, and multiple academic researches, I am always eager to continue learning and improving.
I'm currently looking for full-time software engineering opportunities with a particular interest in distributed systems, cloud computing, and operating systems. Thank you for viewing my profile, and I hope you will find what you are looking for :)

## Experiences

### Databricks | Full-Time | 02/2025 - 🚀
- Part of the IAM Infra team designing and developing highly scalable next-generation systems to serve millions of requests per second

### Amazon Web Services | Full-Time | 07/2024 - 01/2025
- Part of DynamoDB Core Services team building hyper-scale distributed system with sub-10ms response time for workloads of all sizes
- Designed and implemented a high-impact tooling for dynamic config overrides on storage nodes in Java, using RPC to efficiently publish overrides without full AZ redeployments, cutting operational overhead by nearly 100% and greatly boosting system uptime
- Initiated and implemented a production-ready log trimming process in Java based on an investigation on race conditions caused by table partition splits during nodes redeployment downtime, resulting in a $1.5 million cost reduction for log storage annually
- Led design and fix to the low-level Paxos algorithm, resolving a long-standing issue with leader replica removal that caused recurring elections and system lag, resulting in over 100ms reduction in P100 latency and greatly enhancing system responsiveness

### Analytics 4 Everyone LLC | Internship | 05/2023 - 08/2023
- Implemented and migrated a large-scale ML-native service on GCP using Python for an early-stage startup, resulting in a highly scalable and fault-tolerant model that analyzed over 60 million podcast episodes on the fly for 10,000+ users
- Designed the entire backend workflow and streamlined the backend build to an IaC environment using Terraform and Shell Script from scratch, utilizing GKE, Dataproc, PostgreSQL, HBase, Kafka, and Cloud VPC/Firewalls/DNS as the backend infrastructures
- Developed an archiving process that periodically deletes MP3 files on HBase using Pydoop, reducing disk usage by around 55%; containerized the program using Docker and deployed it on GKE as a CronJob
- Built an advanced HPA algorithm that scales Kubernetes Pods based on Kafka messaging load using KEDA, reducing the processing time by around 88% (from 800+ hours to within 72 hours) while ensuring pods resiliency on GKE
- Created a secure CI/CD pipeline using Maven as a build tool in Jenkins; integrated the pipeline with Cloud Shell, GKE, and SonarQube, automatically pushing new codes to the staging environment while detecting and alerting vulnerabilities

### Google | Internship | 05/2022 - 08/2022
- Implemented three multi-cloud data analytics workflow DAG scripts using Python and SQL, providing sample codes for data transferring and processing jobs between GCP, AWS, and Azure in Cloud Composer (managed Apache Airflow)
- Authored and published three tutorials that showcased the implementations, configurations, dependencies, and entire schedulings of multi-cloud DAGs in Cloud Composer, utilizing GCS, BigQuery, Dataproc, S3, and Blob Storage
- Elevated the original data analytics workflow using PySpark and DAG scripts, providing a more advanced usage of Cloud Composer that incorporated a Dataproc Serverless batch job for the developers; my pipeline has been merged with the GCP sample code base
- My work provided the first-ever usage of Cloud Composer in a multi-cloud environment, which fulfilled a highly demanded request and received a 95%+ positive feedback rate from Google’s developer community

### Multidisciplinary Design Program | Part-time | 01/2021 - 01/2022
- Built an accessible driving simulator platform using modeling software OpenDS and Roadrunner to support research on driver distraction, driver workload, and interfaces for partially automated vehicles
- Developed a car-following task consistent with the federal driver distraction protocol independently using Pygame and CARLA in Python; my simulation system will be used for research purposes shortly
- Created a realistic map of the UMich campus with landscapes, such as roads, constructions, etc., by utilizing three types of data (Aerial data, LiDAR data, and elevation data) in Roadrunner, providing a virtual environment for the dynamic/static motion of automobiles operated by test subjects

### University of Michigan | Internship | 05/2021 - 08/2021
- Developed Trace Collector, a Python library that recorded both manual and automated web browser actions into JSON files, providing inputs for the backend programming synthesis algorithm
- Implemented and categorized more than 180 benchmarks to imitate actual actions of users using Trace Collector and Selenium API, which helped the development of our Domain-Specific Language (DSL) and testing of frontend codes (JavaScript, CSS, HTML)
- Implemented a programming synthesis technique that transformed unstructured expressions into looping programs using E-graph, Equality Saturation, and Inverse Transformation in Rust

