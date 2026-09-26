# Awesome-Event-Streaming-Platform

# Top Event Streaming Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Real-Time Event Streaming, Kafka-Compatible Brokers, Pub/Sub, Durable Logs, Stream Processing & Multi-Cloud Streaming*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Event Streaming**. These systems provide durable, scalable publish/subscribe messaging, event logs, and the foundation for real-time data pipelines, event-driven architectures, and stream processing.

**Examples** include Confluent, Redpanda, StreamNative, Aiven, Apache Pulsar Cloud, Amazon MSK, Azure Event Hubs, Google Pub/Sub, WarpStream, Ably, Confluent Cloud, Redpanda Cloud, Aiven for Kafka, Pulsar Cloud, and Upstash Kafka (the category leaders).

**Open-source emphasis**: Event streaming has one of the strongest open-source foundations in infrastructure. **Apache Kafka**, **Apache Pulsar**, **Redpanda** (Kafka-compatible), and **NATS JetStream** power most of the ecosystem. Commercial offerings mainly add managed operations, governance, connectors, and multi-cloud convenience. This section heavily expands the open options.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Confluent / Confluent Cloud](https://www.confluent.io/)**  
  Full-scale event streaming platform built by the original creators of Apache Kafka—managed Kafka, Schema Registry, connectors, ksqlDB, stream processing, and enterprise governance.

- **[Redpanda / Redpanda Cloud](https://www.redpanda.com/)**  
  Kafka-compatible streaming platform written in C++—simpler operations (no ZooKeeper/JVM), high performance, and a fully managed cloud offering.

- **[StreamNative](https://streamnative.io/)**  
  Managed Apache Pulsar and streaming platform focused on Pulsar’s multi-tenancy, geo-replication, and unified messaging + streaming model.

- **[Aiven / Aiven for Apache Kafka](https://aiven.io/)**  
  Multi-cloud managed data platform offering Apache Kafka (and related services) with a free tier, connectors, and operational simplicity.

- **[Apache Pulsar Cloud / managed Pulsar offerings](https://pulsar.apache.org/)**  
  Hosted Pulsar services that provide the open Pulsar architecture as a managed cloud product.

- **[Amazon MSK (Managed Streaming for Apache Kafka)](https://aws.amazon.com/msk/)**  
  Fully managed Apache Kafka service on AWS with integration into the broader AWS data and analytics ecosystem.

- **[Azure Event Hubs](https://azure.microsoft.com/)**  
  Fully managed, real-time data ingestion service on Azure with Kafka protocol compatibility and deep Azure integration.

- **[Google Pub/Sub](https://cloud.google.com/pubsub)**  
  Global, managed messaging and event ingestion service on Google Cloud for high-throughput pub/sub workloads.

- **[WarpStream](https://www.warpstream.com/)**  
  Kafka-compatible streaming platform designed for cost-efficient, agent-based or BYOC-style deployments.

- **[Ably, Upstash Kafka and additional managed streaming services](https://ably.com/)**  
  Other managed event and Kafka-compatible services focused on developer experience, serverless, or specialized real-time use cases.

## Open-Source GitHub Projects
- **[Apache Kafka](https://github.com/apache/kafka)**  
  The foundational open-source distributed event streaming platform—durable logs, high throughput, massive ecosystem of clients, connectors, and stream processors.

- **[Apache Pulsar](https://github.com/apache/pulsar)**  
  Open-source distributed messaging and streaming platform with separated compute/storage, multi-tenancy, geo-replication, and unified queue + stream semantics.

- **[Redpanda](https://github.com/redpanda-data/redpanda)**  
  Open-source, Kafka API-compatible streaming engine written in C++—designed for simplicity, performance, and lower operational overhead.

- **[NATS / NATS JetStream](https://github.com/nats-io/nats-server)**  
  Lightweight, high-performance open-source messaging system with JetStream for persistence, streaming, and at-least-once delivery.

- **[Apache Flink](https://github.com/apache/flink)**  
  Open-source stream processing framework commonly paired with Kafka or Pulsar for real-time analytics and stateful event processing.

- **[Kafka Connect and open connector ecosystem](https://github.com/)**  
  Open framework and community connectors for integrating databases, files, cloud services, and applications with Kafka.

- **[Schema Registry open implementations](https://github.com/)**  
  Open schema management options (Avro, Protobuf, JSON Schema) used with Kafka-compatible clusters.

- **[ksqlDB / stream SQL open projects](https://github.com/)**  
  Open approaches to SQL-based stream processing on top of Kafka.

- **[RabbitMQ and classic messaging open brokers](https://github.com/rabbitmq/rabbitmq-server)**  
  Mature open message broker still widely used for traditional messaging alongside or instead of pure event streaming.

- **[Documentation and event-streaming open playbooks](https://kafka.apache.org/)**  
  Official and community guides for operating Kafka, Pulsar, Redpanda, and NATS in production.

### Additional Strong Open-Source Options
- Self-hosting **Apache Kafka** or **Redpanda** when you want full control and Kafka ecosystem compatibility.
- Choosing **Apache Pulsar** for multi-tenant, geo-replicated, or unified messaging + streaming architectures.
- Using **NATS JetStream** for lightweight, cloud-native messaging and streaming with lower operational complexity.
- Accepting that fully managed operations, enterprise governance, large connector catalogs, multi-cloud SLAs, and 24/7 support still drive many teams to Confluent Cloud, Redpanda Cloud, Aiven, MSK, Event Hubs, Pub/Sub, and similar services.
- Focusing open-source efforts on cost control, data ownership, and deep customization of the streaming backbone.

**Frameworks for building custom systems**: Deploy Kafka or Redpanda (or Pulsar/NATS) → define topics and schemas → produce/consume with official clients → add Kafka Connect or custom connectors → process with Flink or ksql-style tools → observe with open metrics and lag monitoring. Suitable for platform engineering teams. Many organizations still prefer managed streaming platforms for operational simplicity at scale.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Event streaming systems are critical data infrastructure. Misconfiguration can cause data loss, duplication, or outages. Open-source brokers require skilled operations, monitoring, and capacity planning. This list is not operational or architectural advice.

---
**Made for data platform engineers, event-driven architects, and open-source streaming advocates.**
Let's keep events flowing, durable, and as open as practical.
