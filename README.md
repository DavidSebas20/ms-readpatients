# 🏥 **Patient Management Domain**

## 📖 Description
The **Patient Management** domain is responsible for managing all patient-related information within the hospital system. Each CRUD action is designed as an independent microservice to ensure **modularity, scalability, and maintainability**.

---

## 🔹 Microservices

### 🔍 **2. Read Patient**
- **📌 Description:** Retrieves information about a specific patient.
- **🔹 Method:** `GET`
- **🔗 Dependencies:** Patient database 🗂️
- **📥 Inputs:** `Patient ID`
- **📤 Outputs:** Patient data 📄

- ---

## 🛠️ **Technologies Used**
- **⚙️ Backend:** Java, Spring Boot 💻
- **🗄️ Database:** PostgreSQL 🐘

---

## 🔗 **Integrations**
- **🩺 Medical Care Domain:** Patient data is used for scheduling medical appointments.
- **🩹 Clinical History Domain:** Patient data is used for recording their clinical history.

---

🚀 **This README provides a clear overview of the microservices within the Patient Management domain.** It is recommended to update it as changes are made to the architecture or system functionalities. 📢
