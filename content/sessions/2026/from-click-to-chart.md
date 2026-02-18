---
title: "From Click to Chart: Building a Real-Time Analytics Engine"
date: 2026-02-09T16:43:32-06:00
instructors:
 - Meghana Ganu
time_start: 2026-04-21T15:30:00.000Z
time_end:   2026-04-21T15:50:00.000Z
track: Overview & Fundamentals
video: 
weight: 1

---

This session, "From Click to Chart," demystifies the engineering behind real-time analytics. We will trace the lifecycle of a data point as it travels through a modern Google Cloud Platform (GCP) architecture, moving from ingestion to visualization in seconds. Using Apache Beam, we will explore how to build a unified pipeline that handles massive streams of data without the need to manage servers.

Key Points Addressed:
 * The "Why" of Streaming: Understanding the shift from traditional Batch processing to Real-Time Streaming.
 * The Architecture: A deep dive into the "Golden Path" stack: Cloud Pub/Sub (Ingest) $\rightarrow$ Dataflow (Process) $\rightarrow$ BigQuery (Store).
 * Apache Beam Fundamentals: Introduction to the unified programming model, including Windowing (how to group infinite data) and Watermarks (handling late data).

 