---
title: "Build a data pipeline without coding"
weight: 2
label_color: "#621FFF"
images:
 - /images/firefly-highspeed.png
summary: "Prototype common data processing tasks using Apache Beam YAML within a Google Colab environment."
---

#### Justification
Tools that allow for building data pipelines without extensive coding can significantly lower the barrier to entry for data processing and empower a wider range of users. Apache Beam YAML provides a way to define pipelines declaratively, and when combined with interactive environments like Google Colab, it allows for rapid prototyping. For more robust deployments, visual tools like Dataflow Job Builder can be utilized.

### Objective
Prototype common data processing tasks (e.g., Google-provided Templates) using Apache Beam YAML within a Google Colab environment. If Dataflow access is available, participants can explore using the Dataflow Job Builder to construct and run their pipelines.

#### Things to consider
 * Use different types of data (e.g., CSV, JSON)
 * Implement common data transformations (e.g., filter, map, group)
 * Explore the syntax and capabilities of Beam YAML
 * Understand how Beam YAML translates to a Beam pipeline
 * (If applicable) Familiarize with Dataflow Job Builder interface

#### Expected result
A data pipeline defined using Beam YAML, successfully prototyped and executed in Google Collab to perform a specific data processing task. If Dataflow Job Builder is used, a running data pipeline on Dataflow.
