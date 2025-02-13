# 🌍 Build a 360-Degree Customer View in AWS with Powerful Analytics Tools

This repository demonstrates how to integrate data from multiple systems into a **360-degree customer view**, creating a robust foundation for customer analytics initiatives.

---

## 📊 Key Dimensions of a 360-Degree Customer View

We explore a **hypothetical financial services company**, showcasing industry-relevant customer dimensions, including:
- **Marketing & Communications**
- **Customer History**
- **Demographic Information**

These dimensions are applicable across various service industries.

---

## 🏗 Solution Overview

### 🔹 **Data Storage & Processing**
We utilize three **Amazon S3 buckets** for different data purposes:
- **Raw Data Bucket**
- **Stage Data Bucket**
- **Analytics Data Bucket**

### 🔹 **Data Generation & Integration**
- **Synthetic Data**: Generated via AWS Lambda functions with random values.
- **Google Analytics Data**: Uses Amazon **AppFlow** for real-world data extraction.
- **Bank Transactions**: Stored in **Amazon RDS PostgreSQL**.
- **CRM API Simulation**: Lambda functions simulate a CRM API, with the option to extract data from **Salesforce via AppFlow**.
- **Mainframe Simulation**: Lambdas generate flat files stored in **Amazon S3**.

### 🔹 **Automation & Monitoring**
- **Amazon CloudWatch** schedules and triggers **Lambda functions** for automated data processing.

---

## 🚀 Deployment

To deploy this example in your AWS account, follow the detailed **[Deployment Guide](deployment/README.md)**.

---

## 📜 License

This project is licensed under the **MIT-0 License**. See the **[LICENSE](LICENSE)** file for more details.

---

🔗 **Explore, deploy, and enhance customer insights with AWS!**

