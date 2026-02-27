**Enterprise Log Analytics using PySpark – AI Proof of Concept
Project Overview**

This project demonstrates a scalable enterprise log analytics pipeline built using PySpark, simulating large-scale production transaction logs (100K+ records).

The objective of this Proof of Concept (POC) is to showcase how distributed data processing and machine learning can be leveraged to detect anomalies and generate actionable business insights in enterprise environments.

**Business Problem**

Large enterprises generate millions of transaction logs daily across multiple geographies and devices. Monitoring these logs for failures, anomalies, and unusual behavior is critical for:

Fraud detection

System reliability monitoring

Operational intelligence

Risk management

This project simulates such an enterprise environment and applies AI-driven analytics using Spark MLlib.

**Tech Stack**

Python

PySpark

Spark MLlib

Pandas

Distributed Data Processing

**Key Features**

Synthetic generation of 100,000+ enterprise transaction records
Distributed data ingestion using PySpark
Business-level aggregations (failure rate, device usage insights)
Feature engineering using VectorAssembler
ML-based clustering (KMeans) for anomaly detection
Enterprise-ready scalable pipeline structure

**Insights Generated**

Failure rate by country

Average transaction value by device type

Cluster-based anomaly detection on transaction patterns

**Enterprise Impact**

This POC demonstrates how AI-driven log analytics systems can be designed for:

Scalable big data environments

Real-time anomaly detection

Enterprise monitoring systems

Production-grade AI architecture foundations
