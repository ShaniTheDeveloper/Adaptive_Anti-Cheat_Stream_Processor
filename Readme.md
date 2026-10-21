# Adaptive Anti-Cheat Stream Processor

**A real-time gameplay telemetry analysis system built with C++ and Qt, applying advanced Data Structures and Algorithms to identify potentially suspicious behavior in competitive gaming.**

## Overview

The Adaptive Anti-Cheat Stream Processor is an academic software project developed for the Data Structures and Algorithms (DSA) course. It explores how efficient algorithms and memory-conscious data structures can be applied to the challenge of monitoring gameplay events and identifying suspicious activity in real time.

The project combines a high-performance C++ processing engine with a Qt-based desktop dashboard. The system is designed to process simulated gameplay telemetry continuously, analyze player behavior, generate anomaly alerts, and present processing statistics through an interactive graphical interface.

## Core Technologies and Concepts

- **C++:** Core telemetry-processing engine and application logic.
- **Qt:** Interactive desktop dashboard and graphical user interface.
- **Bloom Filters:** Memory-efficient membership checks for known suspicious signatures.
- **Count-Min Sketches:** Approximate frequency estimation of gameplay events.
- **Sliding Windows:** Analysis of recent player actions and temporal behavior.
- **Queues and Circular Buffers:** Organized event ingestion and bounded-memory processing.
- **Hash Functions:** Efficient indexing and probabilistic data structure operations.

## Key Features

- Continuous processing of simulated gameplay telemetry.
- Detection of predefined suspicious signatures and unusually frequent actions.
- Analysis of rapid repeated inputs and potentially automated behavior.
- Monitoring of movement velocity and aim-vector changes over configurable time windows.
- Anomaly scoring and configurable detection thresholds.
- Telemetry logs, suspicious-activity alerts, and processing statistics.
- Performance evaluation using throughput, latency, and memory consumption.

## Project Goal

The primary goal is to demonstrate how intermediate and advanced DSA concepts can support real-time stream processing, efficient memory management, and anomaly detection in a practical gaming-security scenario.

**Note:** This project identifies potentially suspicious gameplay patterns; its alerts are indicators for further investigation, not definitive proof of cheating.