ClearVue NoSQL BI System

A lightweight NoSQL Business Intelligence project built for CMPG321. The system processes ClearVue’s sales, payments, and purchase data using Python, Apache Kafka, and MongoDB, and visualizes insights through Metabase dashboards.

🚀 Features

Real-time data streaming with Apache Kafka

NoSQL database design using MongoDB Atlas

Data cleaning & JSON transformation using Python (Pandas)

BI dashboards built in Metabase

Mapping of all data to ClearVue’s custom fiscal calendar

🧩 Tech Stack

Python

Apache Kafka

MongoDB Atlas + Compass

Docker

Metabase

🔌 Streaming Overview

Python producers publish cleaned JSON data to Kafka topics.

Kafka consumers read events and insert them into MongoDB.

Metabase connects to MongoDB for up-to-date BI reporting.

📁 Project Structure
/etl            → Python data cleaning & JSON converters
/kafka          → Producers, consumers, docker setup
/mongodb        → Schemas & example documents
/dashboards     → Metabase screenshots

📊 What the System Provides

Sales trends

Customer behaviour

Payment tracking

Product performance

Supplier spending

Aging analysis
