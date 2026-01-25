# Project_4_data_engineering
# From Local Scripts to Cloud-Automated Data Pipeline: My GCP Data Engineering Journey
![Screenshot 2026-01-24 094317](https://github.com/user-attachments/assets/2e820b87-0ebf-4758-8f9c-2b4d16d482f5)

Automating Web Scraping and API Ingestion to Cloud-Hosted Storage


During my journey into data science, I also explored data engineering, particularly the process of building data pipelines. This was a completely new topic for me and provided valuable learning experiences and fresh perspectives.
For this project, I needed to collect data from multiple websites using various methods. Along the way, I learned about web scraping, APIs, and several tools offered by the Google Cloud Platform (GCP). The primary goal of the project was to collect weather and flight arrival data from different cities, then transfer, automate, and store it in GCP.
In this short article, I share my journey from a local setup to a cloud-based solution, along with the challenges faced.

# Accomplishments

- Extracted data from websites using web scraping and APIs (Wikipedia, OpenWeatherMap, and AeroDataBox).
- Normalized and cleaned raw API JSON into structured DataFrames.
- Created reusable helper functions for datetime normalization and API ingestion.
- Ensured robust handling of missing fields and datetime issues.
- Stored processed data securely in a MySQL database on GCP.
- Development of cloud functions for automatically retrieving and updating data.
- Automated the entire pipeline using Cloud Scheduler for regular execution.
- Implemented comprehensive logging for API failures, missing fields, and database errors to enable quick troubleshooting.
