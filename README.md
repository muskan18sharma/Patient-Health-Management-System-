# Patient-Health-Management-System-
A comprehensive database-driven solution designed to modernize hospital data management. This project integrates MySQL and MongoDB to manage structured and unstructured patient records efficiently. Key features include EER and UML-based data modeling, Python-powered analytics, secure record handling, and future scalability for IoT and telemedicine.
# Patient Health Management System (PHMS)

A hybrid, scalable, and data-driven health information system designed to improve hospital efficiency, ensure accurate record-keeping, and support analytics-driven decision-making. This project was developed as part of the IE 6700 course – *Data Management for Analytics*, by Team Data Dynamos (Muskan Sharma, Hemalikaa Thirumavalavan, and Mohit Deshpande).

## 🩺 Project Overview

The Patient Health Management System (PHMS) aims to centralize and modernize how patient data is managed in healthcare settings. It combines the power of **relational (MySQL)** and **non-relational (MongoDB)** databases to handle both structured and semi-structured medical records. The project supports complex queries, real-time data access, and insights into trends like diagnoses and billing—enhancing operational decision-making and patient outcomes.

---

## 🔧 Features and Highlights

### ✅ Data Modeling
- **Enhanced Entity-Relationship (EER) Diagrams** for logical design
- **UML Class Diagrams** for object-oriented representation
- Generalization/Specialization (e.g., Doctor and Nurse from HealthcareProvider)

### 🗃️ Dual Database Implementation
- **MySQL**:
  - Normalized schema ensuring data consistency
  - Foreign key constraints and cascade rules
  - Sample queries for real-world use (diagnoses, billing, encounters)
- **MongoDB**:
  - Flexible schema with embedded documents
  - Quick access to nested patient data (e.g., vaccinations, contacts)
  - Efficient querying using regular expressions and filters

### 📊 Data Analytics with Python
- Pandas and matplotlib/seaborn visualizations
- Visual Insights:
  - Patient birth year distribution
  - Top 10 most frequent diagnoses
  - Claim amount analysis by status

### 🔐 Security & Usability
- Recommendations for:
  - Role-based access control
  - Secure credential management
  - Soft deletion instead of hard cascade deletions
- Modular methods for record updates and reporting

---

## 📈 Sample Queries & Use Cases

- Retrieve all patient encounters with reasons and timestamps
- Analyze most common diagnoses by frequency
- Track billing and claim statuses across patient groups
- Identify patients with specific conditions (e.g., Hypertension, Covid-19)
- Filter patients from specific states or insurance providers in MongoDB

---

## 🚀 Future Scope

- **Patient Portal Integration** for engagement and self-service
- **IoT and Telemedicine Readiness** for real-time monitoring
- **Machine Learning Integration** for predictive diagnosis and treatment suggestions
- **Real-time Dashboards** for hospital administrators

---

## 📂 Project Structure

📁 MySQL_Scripts/
├── schema.sql
├── sample_data.sql
└── queries.sql

📁 MongoDB_Scripts/
├── documents_insert.js
└── queries.js

📁 Python_Analytics/
├── analysis.ipynb
└── visualizations/

📁 Docs/
├── EER_Diagram.pdf
├── UML_Diagram.pdf
└── Final_Report.pdf

## 📘 License

This project was completed for academic purposes. Please contact the authors for any intended reuse or collaboration.

---
