# 🛡️ CarePulse: Autonomous Ring & AWS Bedrock Triage
*Amazon Developer Hackathon Submission (Ring Track + AWS Builder Challenge)*

## 🚀 Overview
**CarePulse** is an intelligent, agentic caretaking assistant built to bridge the gap between smart home hardware telemetry and proactive emergency response. Designed for the **Ring Track**, CarePulse listens to real-time IoT telemetry from Ring devices, uses **AWS Bedrock** to perform semantic risk assessment and event triage, and instantly triggers autonomous workflows to protect vulnerable residents.

---

## 🏗️ Architecture & Tech Stack
* **Frontend Dashboard:** Built with **Streamlit** for real-time monitoring, live audit logs, and instant payload simulations.
* **Backend API:** Built with **FastAPI** and **Uvicorn** to handle incoming webhook events asynchronously.
* **AI & Logic Triage:** Powered by **AWS Bedrock** generative AI models to analyze event notes, categorize risk levels (`LOW`, `MEDIUM`, `HIGH`), and recommend contextual safety actions.
* **Environment:** Developed in Python with secure configuration management via `python-dotenv`.

---

## ⚙️ Core Features
1. **Multi-Sensor Telemetry Support:** Handles triggers from motion sensors, doorbell presses, and contact sensors.
2. **Autonomous Risk Triage:** Dynamically parses event context (differentiating routine pet movement from high-risk anomalies).
3. **Real-Time Audit Timeline:** Maintains an immutable, color-coded stream of triage events for caregivers.

---

## 🚀 How to Run Locally

1. **Clone the Repository:**
   ```cmd
   git clone [https://github.com/muhammadshahzaibhaider97-lab/carepulse-hackathon.git](https://github.com/muhammadshahzaibhaider97-lab/carepulse-hackathon.git)
   cd carepulse-hackathon
