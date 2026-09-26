# ⚡ Awesome Event Streaming Platforms 🚀

<p rain-align="center">
  <img src="assets/banner.svg" alt="Awesome Event Streaming Platforms Banner" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Event-Streaming-Platform"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Event-Streaming-Platform?style=flat-square&color=gold" alt="GitHub Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Event-Streaming-Platform/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Event-Streaming-Platform?style=flat-square&color=blue" alt="GitHub Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Event-Streaming-Platform/stargazers"><img src="https://img.shields.io/github/last-commit/ishandutta2007/Awesome-Event-Streaming-Platform?style=flat-square" alt="Last Commit"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 🌟 Ecosystem Overview & Industry Landscape

Welcome to the ultimate curated list of **Event Streaming Platforms**, **Kafka-compatible brokers**, **Pub/Sub engines**, and **real-time stream processing tools**. Designed for data platform engineers, enterprise software architects, and event-driven systems developers.

> 📈 **Market Size & Industry Dynamics:**  
> The global event streaming and real-time data infrastructure market is estimated at **~$12.5 Billion (2026)** and is projected to exceed **$28 Billion by 2030** (CAGR ~22%). The market is **moderately fragmented**: hyper-scalers (AWS MSK, Google Cloud Pub/Sub, Azure Event Hubs) and pioneer leaders (Confluent) hold major enterprise market shares, while high-performance next-gen engines (Redpanda, WarpStream, Apache Pulsar/StreamNative) rapidly capture modern cloud-native workloads.

---

## 📋 Table of Contents

- [☁️ SaaS & Hosted Platforms](#️-saas--hosted-platforms)
- [🔥 Open-Source GitHub Projects](#-open-source-github-projects)
- [🤝 How to Contribute](#-how-to-contribute)
- [💖 Support & Community](#-support--community)
- [📈 Star History](#-star-history)
- [⚠️ Disclaimer](#️-disclaimer)

---

## ☁️ SaaS & Hosted Platforms

Below is a comparison of top managed event streaming cloud platforms sorted by **Company Size / Valuation / Revenue** (descending):

| SaaS Product | Size / Valuation / Revenue | Starting Pricing Tier | Free Tier & Free Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- |
| **[Google Pub/Sub](https://cloud.google.com/pubsub)** | **~$2.0 Trillion** (Parent: Alphabet Inc.) | $40 per TB of data volume ingested/delivered | **Free Forever:** 10 GB of message ingestion per month | Global, fully managed serverless pub/sub messaging engine with automatic scaling and zero cluster management. |
| **[Amazon MSK (AWS)](https://aws.amazon.com/msk/)** | **~$2.0 Trillion** (Parent: Amazon Inc.) | ~$0.021 per broker-hour + storage charges | **Free Trial:** 750 broker-hours/month of MSK Serverless for 2 months | Fully managed Apache Kafka engine natively integrated with AWS IAM, CloudWatch, and analytics tools. |
| **[Azure Event Hubs](https://azure.microsoft.com/)** | **~$3.0 Trillion** (Parent: Microsoft Corp.) | $0.015 per hour per Throughput Unit | **Free Trial:** $200 Azure cloud credit valid for 30 days | High-throughput data ingestion service on Azure offering native Apache Kafka protocol compatibility. |
| **[Confluent Cloud](https://www.confluent.io/)** | **~$6.5 Billion** (Public: NASDAQ: CFLT) | $0.00/hr base + pay-as-you-go throughput | **Free Trial:** $400 free credit valid for 30 days | Enterprise-grade managed Apache Kafka platform featuring Schema Registry, 120+ connectors, and Flink stream processing. |
| **[Aiven for Apache Kafka](https://aiven.io/)** | **~$3.0 Billion** (Series C valuation) | $0.07/hr (~$50/month) for Startup-4 plan | **Free Trial:** $300 credit valid for 30 days | Multi-cloud managed data infrastructure offering open-source Apache Kafka, Kafka Connect, and MirrorMaker 2. |
| **[Redpanda Cloud](https://www.redpanda.com/)** | **~$500 Million** (Series C valuation) | $0.08/hr for Serverless tier | **Free Trial:** $300 credit valid for 14 days | C++ based Kafka-compatible streaming engine delivering zero JVM overhead, low latency, and simplified BYOC deployments. |
| **[StreamNative](https://streamnative.io/)** | **~$150 Million** (Series A valuation) | $0.10/hr for Serverless Pulsar instances | **Free Trial:** $300 credit valid for 30 days | Cloud-native event streaming platform powered by Apache Pulsar with multi-tenancy and tier storage. |
| **[Ably Realtime](https://ably.com/)** | **~$120 Million** (Series B valuation) | $29/month for Pay-As-You-Go plan | **Free Forever:** 6 Million messages & 200 concurrent connections / month | Serverless pub/sub messaging platform engineered for edge delivery, real-time web applications, and webhooks. |
| **[WarpStream](https://www.warpstream.com/)** | **~$50 Million** (Venture-backed) | $0.01 per GB written to object storage | **Free Forever:** 1 TB of data ingested per month | BYOC Kafka-compatible broker that streams directly to S3/cloud object storage without disk state management. |
| **[Upstash Kafka](https://upstash.com/)** | **~$30 Million** (Series A valuation) | $0.20 per 100K messages | **Free Forever:** 10,000 messages / day (max 256MB bandwidth) | Serverless Kafka database with per-request pricing, REST API access, and instant edge deployment. |

---

## 🔥 Open-Source GitHub Projects

The leading open-source event streaming engines and frameworks, sorted by **GitHub Star Count** (descending):

- **[Apache Kafka](https://github.com/apache/kafka)** [<img src="https://img.shields.io/github/stars/apache/kafka?style=social&color=white" alt="Kafka Stars"/>](https://github.com/apache/kafka/stargazers)  
  ⚡ The industry standard distributed event streaming platform for high-throughput, fault-tolerant log storage and pub/sub pipelines.

- **[Apache Flink](https://github.com/apache/flink)** [<img src="https://img.shields.io/github/stars/apache/flink?style=social&color=white" alt="Flink Stars"/>](https://github.com/apache/flink/stargazers)  
  ⚡ High-performance stream processing engine providing stateful computations over data streams with exact-once semantics.

- **[RabbitMQ](https://github.com/rabbitmq/rabbitmq-server)** [<img src="https://img.shields.io/github/stars/rabbitmq/rabbitmq-server?style=social&color=white" alt="RabbitMQ Stars"/>](https://github.com/rabbitmq/rabbitmq-server/stargazers)  
  ⚡ Reliable and flexible message broker supporting AMQP, MQTT, and STOMP protocols for traditional & real-time messaging.

- **[NATS Server](https://github.com/nats-io/nats-server)** [<img src="https://img.shields.io/github/stars/nats-io/nats-server?style=social&color=white" alt="NATS Stars"/>](https://github.com/nats-io/nats-server/stargazers)  
  ⚡ Cloud-native, ultra-lightweight messaging system equipped with JetStream for durable streaming and key-value storage.

- **[Apache Pulsar](https://github.com/apache/pulsar)** [<img src="https://img.shields.io/github/stars/apache/pulsar?style=social&color=white" alt="Pulsar Stars"/>](https://github.com/apache/pulsar/stargazers)  
  ⚡ Next-gen distributed pub/sub messaging system with separated compute and storage (BookKeeper) for multi-tenancy.

- **[Redpanda](https://github.com/redpanda-data/redpanda)** [<img src="https://img.shields.io/github/stars/redpanda-data/redpanda?style=social&color=white" alt="Redpanda Stars"/>](https://github.com/redpanda-data/redpanda/stargazers)  
  ⚡ C++ Kafka API-compatible event streaming platform engineered for 10x lower tail latencies and no ZooKeeper dependency.

- **[Bytewax](https://github.com/bytewax/bytewax)** [<img src="https://img.shields.io/github/stars/bytewax/bytewax?style=social&color=white" alt="Bytewax Stars"/>](https://github.com/bytewax/bytewax/stargazers)  
  ⚡ Python-centric stream processing framework powered by a Timely Dataflow Rust execution engine.

- **[Memphis.dev](https://github.com/memphisdev/memphis)** [<img src="https://img.shields.io/github/stars/memphisdev/memphis?style=social&color=white" alt="Memphis Stars"/>](https://github.com/memphisdev/memphis/stargazers)  
  ⚡ Developer-first alternative to complex message brokers with embedded data governance and schema enforcement.

- **[Fluvio](https://github.com/infinyon/fluvio)** [<img src="https://img.shields.io/github/stars/infinyon/fluvio?style=social&color=white" alt="Fluvio Stars"/>](https://github.com/infinyon/fluvio/stargazers)  
  ⚡ Lean real-time data streaming engine written in Rust with inline WebAssembly (Wasm) stream transformations.

- **[Apacke Spark Streaming](https://github.com/apache/spark)** [<img src="https://img.shields.io/github/stars/apache/spark?style=social&color=white" alt="Spark Stars"/>](https://github.com/apache/spark/stargazers)  
  ⚡ Scalable micro-batch and continuous stream processing engine integrating seamlessly with Spark SQL and MLlib.

---

## 🤝 How to Contribute

Contributions are welcome! Please follow these simple guidelines:

1. 🍴 **Fork** this repository.
2. 📝 Add or update entries in `README.md` keeping formatting consistent.
3. 🔗 Ensure all SaaS & Open-Source project links point directly to official resources.
4. 🚀 Submit a **Pull Request** with a detailed summary of additions.

---

## 💖 Support & Community

If you find this repository helpful, please consider supporting the project:

- 🌟 **Star** this repository on GitHub to show your appreciation!
- 🔀 **Fork** it to keep your own curated reference.
- 📢 **Share** it with fellow data engineers and software architects.
- ☕ **Sponsor:** Support open-source curation via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).

Thank you for being part of the open-source community! ❤️

---

## 📈 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Event-Streaming-Platform&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Event-Streaming-Platform&type=date&legend=top-left)

---

## ⚠️ Disclaimer

- This repository is a **community-curated list** for informational and educational purposes.
- System pricing, limits, and market valuations change over time; refer to official platforms for live SLAs and enterprise pricing.

---

<p align="center">
  <b>Made with ❤️ for Data Engineers &amp; Streaming Architects worldwide.</b>
</p>
