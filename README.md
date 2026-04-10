# ☁️ Project 4: Data Engineering Pipeline on GCP

**From Local Scripts to Cloud-Automated Data Pipeline**
![Screenshot 2026-01-24 094317](https://github.com/user-attachments/assets/2e820b87-0ebf-4758-8f9c-2b4d16d482f5)

---

## 📌 Overview

This project documents my journey from building **local data scripts** to developing a fully **automated, cloud-based data pipeline** using **Google Cloud Platform (GCP)**.

The pipeline collects **weather and flight arrival data** from multiple sources, processes it, and stores it in a cloud-hosted database with full automation and monitoring.

---

## 🎯 Project Objective

To design and implement an **end-to-end data pipeline** that:

* Extracts data from APIs and web sources
* Cleans and transforms raw data into structured formats
* Stores data in a cloud database
* Automates the entire workflow using GCP services

---

## 🚀 Key Features

* Automated data ingestion from multiple sources
* Cloud-based storage and processing
* Scheduled pipeline execution
* Robust error handling and logging

---

## 🧠 About the Project

As part of my data science journey, I explored **data engineering concepts**, focusing on building scalable and automated pipelines.

The project involved:

* Collecting data from different sources (web scraping and APIs)
* Transitioning from local scripts to a cloud-based architecture
* Leveraging GCP tools to automate workflows and improve reliability

---

## 🔗 Article

📖 Read more about the full journey here:
[My Data Engineering Journey on Medium] https://medium.com/@haji.eng/from-local-scripts-to-cloud-automated-data-pipeline-my-gcp-data-engineering-journey-2c4248229643

---

## 🛠️ Tools & Technologies

* **Python**
* **APIs & Web Scraping**
* **Google Cloud Platform (GCP)**

  * Cloud Functions
  * Cloud Scheduler
  * Cloud SQL (MySQL)

---

## 📊 Data Sources

* Weather data (OpenWeather API)
* Flight arrival data (AeroDataBox API)
* Supplementary data (Wikipedia scraping)

---

## 🏗️ Pipeline Architecture

1. **Data Extraction**

   * APIs (weather, flight data)
   * Web scraping (Wikipedia)

2. **Data Transformation**

   * JSON normalization into structured DataFrames
   * Datetime standardization
   * Handling missing or inconsistent data

3. **Data Storage**

   * Cloud-hosted MySQL database (GCP)

4. **Automation**

   * Cloud Functions for execution
   * Cloud Scheduler for periodic runs

5. **Monitoring & Logging**

   * Logging for API failures and missing fields
   * Error tracking for database operations

---

## 🏆 Accomplishments

* Extracted data from multiple sources using APIs and web scraping
* Cleaned and transformed raw JSON data into structured formats
* Built reusable helper functions for data processing
* Implemented robust handling of missing data and datetime inconsistencies
* Deployed a MySQL database on GCP for secure storage
* Developed cloud functions to automate data ingestion
* Scheduled automated pipeline runs using Cloud Scheduler
* Added comprehensive logging for debugging and reliability

---

## 📂 Repository Structure

| File / Folder | Description                                |
| ------------- | ------------------------------------------ |
| `/scripts`    | Data extraction and transformation scripts |
| `/functions`  | Cloud Functions for automation             |
| `/data`       | Processed datasets (if included)           |
| `/logs`       | Logging outputs (optional)                 |
| `README.md`   | Project documentation                      |

---

## ✨ Key Takeaway

This project demonstrates the transition from **local data processing** to a **scalable, automated cloud pipeline**, showcasing foundational skills in **data engineering, cloud computing, and workflow automation**.

---

🚀 *Feel free to explore the repository and share your feedback!*

