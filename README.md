

# 🤖  Business Intelligence Assistant

A **Streamlit-powered, AI-driven BI Assistant** that enables users to query **cloud and on-premises datasets** like **Snowflake**, **Amazon S3**, **Google Cloud Storage**, **MySQL**, **PostgreSQL**, and **SQLite** using **natural language**. The assistant generates **safe SQL queries** and returns **dynamic tables** or **responsive charts**, with the ability to **download session summaries** in **PDF/HTML** formats.

---
## Overview
This BI Assistant provides a chat-like interface for data exploration and visualization. It interprets natural-language queries and securely executes SQL statements (or fetches data from storage services like S3/GCS). 
The application addresses multiple cloud data services and ensures data safety through read-only modes and destructive-statement blocking.


## 🌟 Features

- 🔌 **Multi-Cloud Connectivity**
  - Supports **Snowflake**, **S3**, **GCS**, **PostgreSQL**, **MySQL**, **SQLite**, and more
  - Modular **database manager** for secure, dynamic connection handling

- 💬 **Natural Language Querying**
  - Powered by **LangChain** and **LangGraph**
  - Seamlessly turns user queries into **safe SQL statements**

- 🔐 **Query Safety**
  - Detects and blocks **destructive queries** like `DROP`, `DELETE`, `ALTER`
  - Optional **read-only mode** ensures data integrity

- 📊 **Smart Visualization**
  - Generates **Matplotlib** or **Plotly** charts automatically
  - Plotly charts are **interactive** (hover, zoom, tooltips)

- 🧠 **Session Memory + Export**
  - Saves chat interactions in memory
  - Allows exporting session summaries to **PDF** or **HTML**

---

## 📐 Architecture
![image](https://github.com/user-attachments/assets/5b54cb9a-6327-4f45-9377-e880b44c0b74)
![image](https://github.com/user-attachments/assets/58071713-a8a0-46df-b3a9-6b1d2e9bcf77)

## 🛠️ Tech Stack
![image](https://github.com/user-attachments/assets/87edf1b2-36a7-4805-b97f-f4e164e5b153)

## 💾 Supported Databases
SQLite

MySQL

PostgreSQL

Microsoft SQL Server

Oracle

Snowflake ❄️

Google BigQuery 🌐

DuckDB

## ✨ Example Use Cases
"Total number of customers per country"

"Visualize rental revenue by month"

"Compare inventory levels across categories"

"Show the distribution of payments (as a histogram)"

## 🛡️ Planned Safety Features
✅ DDL prevention (e.g., DROP, DELETE)

✅ SQL validation & explain plans (coming soon)

✅ Feedback loop for SQL correctness



## 👨‍💻 Author
Developed by Mukesh Chandra Yarlagadda.

MS in Business Analytics | Data Scientist | LLM Engineer




