---
title: "Assembling the Puzzle: High-Performance Entity Building streaming Beam pipeline using a Two-Tiered State Architecture"
date: 2026-02-09T16:43:32-06:00
instructors:
 - Israel Herraiz
day: 20263
time_start: 2026-04-23T16:00:00.000Z
time_end:   2026-04-23T16:25:00.000Z
track: Tips & Tricks
video: 
weight: 13

---

When source systems emit only partial updates to conserve network bandwidth, Data Engineers face the complex task of reconstructing complete entities in real-time. In this session, we will deep dive into a high-performance, SCD-like streaming pipeline that dynamically reconstructs full entities from partial data before sinking them to the data warehouse.

The core of our solution is a custom two-tiered state backend architecture. By intelligently combining Apache Beam’s native, low-latency state API (Tier 1) with an external third-party data store (Tier 2), we overcome standard memory and throughput limitations. Join us to explore how this two-tiered design, alongside Beam timers, drastically reduces external database lookups, minimizes network latency, and unlocks unparalleled performance for stateful streaming pipelines.
 
