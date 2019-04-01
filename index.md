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

The *CDA* project is currently composed out of 1) *Arc*: an Intermediate Representation (*IR*) for batch and stream data computation, 2) *Arcon*: A distributed execution runtime for Arc programs and 3) Kompact: a component- and actor-based middleware for programming distributed systems that written entirely in *Rust*.

![Architecture of CDA](/assets/images/overview.png)

Publications
==========

PhD Dissertations
------
* Paris Carbone - [Scalable and Reliable Data Stream Processing](http://urn.kb.se/resolve?urn=urn:nbn:se:kth:diva-233527) (Sept 2018)

* Salman Niazi - [Scaling Distributed Hierarchical File Systems Using NewSQL Databases](http://urn.kb.se/resolve?urn=urn:nbn:se:kth:diva-238605) (Dec 2018)

MSc Theses
------
* Klas Segeljakt - [A Scala DSL for Rust code generation](http://urn.kb.se/resolve?urn=urn:nbn:se:kth:diva-235358)

* Oscar Bjuhr - [Relocatable Driver and Code Generator for Continuous Deep Analytics](http://urn.kb.se/resolve?urn=urn:nbn:se:kth:diva-232079)

* Johan Mickos - [Design of a Network Library for Continuous Deep Analytics](http://urn.kb.se/resolve?urn=urn:nbn:se:kth:diva-232129)

* Tobias Lindener - [Enabling Arbitrary Memory Constraint Standing Queries on Distributed Stream Processors using Approximate Algorithms](http://urn.kb.se/resolve?urn=urn:nbn:se:kth:diva-237459)

Conference and Workshop Papers
------


*  Salman Niazi, Mikael Ronström. Seif Haridi, Jim Dowling - Size Matters: Improving the Performance of Small Files in Hadoop - ACM Middleware 2018


* Z Abbas, V Kalavri, P Carbone, V Vlassov - Streaming graph partitioning: an experimental study - VLDB 2018

* Vasiliki Kalavri, Vladimir Vlassov, Seif Haridi - High-level programming abstractions for distributed graph processing-IEEE Transactions in Knowledge Data Engineering (TKDE Journal) 2018

* Paris Carbone - Asynchronous Epoch Commits for Fast and Consistent Stateful Streaming with Apache Flink . LADIS 2018, part of ACM PODC 18.

Talks
------

* Paris Carbone - [Stream Loops on Flink: Reinventing the wheel for the streaming era](https://www.ververica.com/flink-forward-berlin/resources/stream-loops-on-flink-reinventing-the-wheel-for-the-streaming-era) - Flink Forward 2018 Berlin



	