---
layout: article
title: Unified Compilation and Execution for Data Pipelines
article_header:
  type: overlay
  theme: dark
  background_color: '#20639B'
  cover_size: md
  background_image:
        gradient: 'linear-gradient(135deg, rgba(34, 90, 87 , .7), rgba(139, 34, 139, .7))'
        src: /assets/images/unified.png

---

Our Mission
========

Modern end-to-end data pipelines are highly complex and unoptimized. They combine code from different frontends (e.g., SQL, Beam, Keras), declared in different programming languages (e.g., Python, Scala) and execute across many backend runtimes (e.g., Spark, Flink, Tensorflow). Data and intermediate results take a long and slow path through excessive materialization, conversions down to different partially supported hardware accelerators. End-to-End guarantees are typically complex to reason due to the mismatch of processing semantics across runtimes.

The Continuous Deep Analytics (*CDA*) project aims to shape the next-generation software for scalable, data-driven applications and pipelines. Our work binds state of the art mechanisms in compiler and database technology together with 
hardware-accelerated machine learning and distributed stream processing. 


Architecture
==========

The *CDA* project is currently composed out of 1) *Arc*: an Intermediate Representation (*IR*) for batch and stream data computation, 2) *Arcon*: A distributed execution runtime for Arc programs and 3) Kompact: a component- and actor-based middleware for programming distributed systems that is written entirely in *Rust*.

![Architecture of CDA](/assets/images/overview.png)


	
