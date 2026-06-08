# Hi 👋 I'm Karol

I build **practical backend tools and automation** using Python, AWS, and serverless technologies.

I enjoy turning real-world problems into **simple, reliable systems** — from event-driven data pipelines to cloud-native automation and API integrations.
Most of my work starts with a concrete need and grows into something reusable, well-structured, and ready for the cloud.

---

## 🧰 Tech I work with

- **AWS** — Lambda, S3, EC2, IAM, VPC, CloudWatch — including serverless, event-driven architectures
- **Python** — automation, API integration, data processing, backend utilities, AWS Lambda functions
- **Docker, Git, GitHub Actions** — containerization, CI/CD, reproducible environments
- **Linux & networking** — deployment, debugging, troubleshooting

---

## 🚀 Selected Projects

### AWS Serverless CSV Data Profiler
Repo: https://github.com/k-borowiak/csv-s3-lambda-profiler

A lightweight **event-driven data pipeline on AWS** that automatically processes CSV files uploaded to S3.

Designed as a complete cloud-native flow — storage → compute → processed output — fully decoupled and scalable with no persistent infrastructure.

It:
- triggers automatically via S3 event notifications → AWS Lambda
- processes CSV files using Python and extracts structured metadata
- writes JSON output back to S3 (`uploads/` → `output/` folder)
- uses IAM roles with scoped permissions for secure execution
- logs execution details via CloudWatch for observability

This was also a first step into **serverless PoC prototyping** — building a working, deployable solution fast and iterating from there.

---

### Flight Deals Tracker
Repo: https://github.com/k-borowiak/flight_deals

A tool that **automatically tracks flight prices** and sends a weekly email report with current and historical data.

It:
- queries Google Travel Explore API for the cheapest flights across multiple destinations
- caches API responses locally to avoid unnecessary calls
- compares current prices against historical minimums
- updates a Google Sheets spreadsheet via REST API
- sends a formatted weekly report via Gmail SMTP
- runs automatically every Monday via **GitHub Actions** (zero-maintenance CI/CD)

---

### ZwiftPower Rider Data Tool
Repo: https://github.com/k-borowiak/zwiftpower-excel-updater

A Python tool that **automates collecting rider performance data from ZwiftPower** and turns it into a structured dataset for team management.

It:
- logs in via Zwift SSO and extracts data from dynamic web pages
- cleans and normalizes results
- exports ready-to-use data to Excel

---

## 🔍 What these projects show

- designing and deploying **serverless, event-driven architectures on AWS**
- fast prototyping — building working solutions quickly, then improving structure and reliability
- working with external APIs and dynamic web data
- separating responsibilities cleanly: data intake, processing logic, output
- setting up CI with GitHub Actions
- thinking about **IAM, observability, and cloud-native design** from the start

---

## 🧩 How I work

I start with the **simplest working solution**, then improve structure, reliability, and deployment step by step.

I care about:
- simple and understandable solutions
- tools that are easy to run, debug, and maintain
- reproducible setups (Docker, configuration, scripts)
- building software designed for **real use**, not just demos

---

## 📫 Contact

- GitHub: https://github.com/k-borowiak
- LinkedIn: https://www.linkedin.com/in/karol-borowiak-810425236/
