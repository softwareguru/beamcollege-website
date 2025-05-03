---
title: "Leverage Managed I/O"
weight: 4
label_color: "#621FFF"
images:
 - /images/firefly-matrix.png
summary: "Build a pipeline that integrates with Iceberg | Kafka | BigQuery via Managed I/O."
---

#### Justification
Managed I/O enables Dataflow to manage specific I/O connectors used in Apache Beam pipelines. Managed I/O simplifies the management of pipelines that integrate with supported sources and sinks, often improving performance and scalability.

#### Objective
Build an Apache Beam data pipeline that leverages Managed I/O to integrate with one or more of the following sources and sinks: Apache Iceberg, Apache Kafka, BigQuery.

#### Things to consider
 * Understand the benefits and configurations of Managed I/O connectors.
 * Implement reads from and/or writes to the chosen sources/sinks.
 * Ensure proper authentication and authorization for accessing the services.

#### Expected result
One or more running Apache Beam pipelines that successfully use Managed I/O APIs. This can be demonstrated by running the pipeline(s) locally (e.g., using the Direct Runner in a Colab environment) to read from and/or write data to Iceberg, Kafka, or BigQuery sources/sinks. If applicable and resources allow, these pipelines could also be run on Dataflow.
