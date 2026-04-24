# 🏥 Nexus Healthcare: Digital HMS Solution

Nexus Healthcare is a professional **Hospital Management System** designed with **Python 3.13**, **Streamlit**, and **SQLite3**. It automates the workflow of a modern clinic, from patient intake to financial reporting.

## 🌟 Key Features
- **Relational SQL Database**: Advanced database schema with `JOIN` queries to link patients, doctors, and appointments seamlessly.
- **Dynamic Scheduling**: Real-time appointment booking with a pre-configured database of specialists (Cardiology, Neurology, etc.).
- **Smart Session Management**: Persistent UI states using `st.session_state` for a smooth registration experience.
- **Digital Billing & Records**: Instant patient history retrieval and revenue calculation based on consultation fees.
- **Enterprise UI**: Custom CSS-injected "Patient Profile Cards" and high-contrast labels for medical staff usability.

## 📊 Database Architecture
The system utilizes a relational model to ensure data integrity:
* **Patients Table**: Stores demographic and medical data (Blood group, ID, etc.).
* **Doctors Table**: Manages specialist profiles and consultation pricing.
* **Appointments Table**: Connects patients and doctors with a timestamped status for audit trails.

## 🚀 Installation & Setup
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/nexus-healthcare-management-system.git](https://github.com/your-username/nexus-healthcare-management-system.git)
