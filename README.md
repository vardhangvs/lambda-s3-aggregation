# 💼 Real-Time Salary Aggregation with AWS Lambda and S3

This project demonstrates how to build a **serverless pipeline** using AWS Lambda and S3 that automatically processes employee data files and generates salary totals by country.

Whenever a new file is uploaded to an S3 bucket, a Lambda function is triggered. It reads the file, calculates the total salary for each country, and saves the result into another S3 bucket.

---

## 📌 Features

- Auto-trigger on file upload using S3 event
- Reads CSV data containing employee info
- Aggregates salaries based on country
- Writes output to a target S3 bucket
- Logs processing steps to CloudWatch

---



