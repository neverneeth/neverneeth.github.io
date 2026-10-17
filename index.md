---
layout: default
title: Navaneeth V Sankar
---

[Resume (PDF)](resume.pdf)

# Navaneeth V Sankar

Trivandrum, Kerala | tve24cs110@cet.ac.in | [linkedin.com/in/navaneeth-v-sankar](https://linkedin.com/in/navaneeth-v-sankar) | [github.com/neverneeth](https://github.com/neverneeth)

## Education

**College of Engineering, Trivandrum (CET)** — Trivandrum, Kerala

B.Tech in Computer Science and Engineering | **CGPA: 9.29/10** — Expected Grad: April 2028

## Technical Skills

**Languages:** C/C++, Python, Java, JavaScript/TypeScript, CUDA, SQL

**Backend & Cloud:** AWS (Lambda, DynamoDB, S3, CloudFront, API Gateway, Cognito, WAF), AWS CDK, NestJS, PostgreSQL, TypeORM, REST APIs

**Systems & Hardware:** Microcontrollers (Arduino/STM32), GPIO/I2C Interfacing, Edge Profiling, DAG Scheduling

**Tools:** Linux, Git, Docker, NetworkX, Matplotlib

## Experience

**Research Intern** | *IIT Kharagpur* — June 2026 – July 2026

- Profiled edge-deployed LLMs on resource-constrained embedded hardware, characterizing end-to-end inference latency, memory bandwidth, and power consumption under Dr. Arnab Sarkar.
- Designed and executed adversarial evaluation pipelines against quantized models, establishing robustness baselines and maintaining sub-10% Attack Success Rate across attack variants.

**Undergraduate Research Assistant** | *CET* — August 2025 – May 2026

- Designed a novel RL-based DAG task scheduler for concurrent workload distribution across heterogeneous multi-processor compute systems, under Dr. Piyoosh P.
- Benchmarked against QL-HEFT and CC-TMS scheduling baselines, achieving up to a **28% reduction in average makespan** across diverse task-graph topologies.

**Backend Software Engineer** | *CET Enterprise Client Project* — July 2025 – Present

- Architecting scalable REST API infrastructure for a client Enterprise Resource Planning platform using NestJS, PostgreSQL, and TypeORM.
- Engineered decoupled endpoints with strict input validation and query optimization, reducing data-access abstraction overhead.

**Summer Research Intern** | *IIIT Kottayam (Network Science Group)* — May 2025 – June 2025

- Formulated non-linear time series analysis algorithms using complex network theory under Dr. Divya Sindhu Lekha.
- Leveraged `pyunicorn` for recurrence network construction, mapping large climate datasets to isolate critical temporal anomalies.

## Projects

**CET LIVE VOTES** | *AWS Serverless, AWS CDK, JavaScript* — [live.cetlivevotes.me](https://live.cetlivevotes.me)

- Built and operated a live results and exit-poll platform for a ~4,000-student college union election, with infrastructure as code in AWS CDK and security via Cognito MFA, WAF rate limits, and a strict CSP.
- Served **797K requests** at a peak of ~400 concurrent viewers with a single backend error by publishing results as CDN-cached static JSON (S3 + CloudFront), keeping **99.6%** of traffic off Lambda.
- Designed a privacy-preserving exit poll using client-side SHA-256 ID hashing, expiring HMAC-keyed deduplication, aggregate-only storage via atomic DynamoDB transactions, and suppression of groups under 5; it called 14 of 16 contested seats from 191 responses.

**Processor DAG Scheduling Framework** | *Python, NetworkX, Matplotlib*

- Built an extensible simulation framework to model and analyze concurrent DAG task execution across multi-processor architectures with pluggable scheduling strategies.
- Used to run the experiments for the paper listed under Publications.

**EEPROM Programmer** | *Bare-Metal C, Hardware Interfacing*

- Engineered an EEPROM programmer in C, interfacing an Arduino Nano with 74HC595 Shift Registers to flash 28C16 memory units.
- Implemented serial-to-parallel bit-shifting to overcome microcontroller GPIO limitations, utilizing the registers as a 16-bit memory address buffer.
- Integrated programmed EEPROMs as combinational logic decoders (7-segment displays) and as a microcode control ROM for a prototype 8-bit CPU architecture.

## Publications

- Rahim S., Sankar N. V., Devaraj R., & Nair P. P. (2026). A Reinforcement Learning Approach to Contention-Aware Co-Scheduling in Heterogeneous Cyber-Physical Systems. *Computer Communications. Article: 108616. Volume 257*.

## Relevant Coursework & Leadership

**Core Coursework:** Computer Architecture, Operating Systems, Data Structures & Algorithms, Database Systems, Theory of Computation, Graph Theory.

**Leadership:** **Vice President**, Build Club CET (Organized technical builds and upskilled student cohorts).
