
# 🌍 AI Disaster Incident Response Coordinator

> **An AI-powered emergency response system that analyzes disaster incidents, evaluates environmental conditions, recommends resource deployment, notifies emergency teams, and maintains a centralized incident log — all through an automated n8n workflow.**

![License](https://img.shields.io/badge/License-MIT-green)
![n8n](https://img.shields.io/badge/Built%20With-n8n-orange)
![Gemini](https://img.shields.io/badge/AI-Google%20Gemini-blue)
![Automation](https://img.shields.io/badge/Automation-End--to--End-success)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

# 📖 Project Overview

Natural disasters demand **rapid analysis, informed decisions, and immediate communication**.

This project demonstrates how AI and workflow automation can streamline emergency response by transforming a raw incident report into actionable intelligence within seconds.

Instead of relying on manual coordination, the workflow automatically:

- Understands the incident using Google Gemini AI.
- Retrieves live weather information.
- Determines emergency severity.
- Suggests optimal resource allocation.
- Generates an executive summary.
- Sends email alerts.
- Logs every incident into Google Sheets for future tracking.

The entire pipeline is orchestrated using **n8n**.

---

# 🚀 Workflow Overview

```
Manual Trigger
      │
      ▼
Incident Data
      │
      ▼
🧠 Gemini Incident Analyzer
      │
      ▼
🌦 OpenWeather API
      │
      ▼
🚑 Gemini Resource Allocation
      │
      ▼
📄 Gemini Executive Summary
      │
      ├──────────────► 📧 Gmail Notification
      │
      └──────────────► 📊 Google Sheets Logging
```

---

# ✨ Key Features

## 🧠 AI Incident Analysis
Uses Google Gemini to understand the disaster, classify its severity, and identify critical response requirements.

---

## 🌦 Live Weather Intelligence
Fetches real-time weather conditions from the OpenWeather API to support operational decisions.

---

## 🚑 Intelligent Resource Allocation
Recommends emergency resources such as ambulances, rescue teams, medical personnel, and firefighting units based on the incident.

---

## 📄 Executive Summary Generation
Creates a concise report for decision-makers and emergency coordinators.

---

## 📧 Automated Email Alerts
Immediately notifies emergency stakeholders through Gmail.

---

## 📊 Incident Logging
Stores every incident in Google Sheets for reporting, auditing, and historical analysis.

---

# 🛠 Tech Stack

| Technology | Purpose |
|------------|---------|
| n8n | Workflow Automation |
| Google Gemini AI | Incident Analysis & Decision Making |
| OpenWeather API | Weather Intelligence |
| Gmail | Automated Email Notifications |
| Google Sheets | Incident Database |

---

# 📂 Repository Structure

```
AI-Disaster-Incident-Response-Coordinator
│
├── workflow.json
├── README.md
├── LICENSE
│
├── images
│   ├── workflow.png
│   ├── architecture.png
│   ├── execution.png
│   ├── gmail.png
│   └── sheets.png
│
└── docs
    ├── Project_Report.pdf
    └── Architecture.pdf
```

---

# 🖼 Workflow Screenshot

> *(Add your screenshot here after uploading it to the `images` folder.)*

```markdown
![Workflow](images/workflow.png)
```

---

# 🏗 System Architecture

> *(Replace with your architecture diagram.)*

```markdown
![Architecture](images/architecture.png)
```

---

# ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/ChaitrikaNelluri/AI-Disaster-Incident-Response-Coordinator.git
```

---

### 2. Import Workflow

Open n8n and import:

```
workflow.json
```

---

### 3. Configure Credentials

Configure:

- Google Gemini API
- Gmail
- Google Sheets
- OpenWeather API

---

### 4. Execute Workflow

Click

```
Execute Workflow
```

The workflow will automatically:

- Analyze the incident
- Fetch weather data
- Allocate resources
- Generate an executive summary
- Send an email notification
- Store the incident in Google Sheets

---

# 📈 Sample Workflow Output

| Stage | Output |
|--------|--------|
| Incident Analysis | High Severity |
| Weather | Rain, 29°C |
| Resources | 3 Ambulances, Fire Unit, Medical Team |
| Summary | Executive Incident Report |
| Email | Successfully Sent |
| Google Sheets | New Incident Logged |

---

# 🌟 Potential Applications

- Government Disaster Management
- Emergency Operations Centers
- Fire & Rescue Departments
- NGOs
- Smart Cities
- Public Safety Automation
- Crisis Management Platforms

---

# 🔮 Future Enhancements

- SMS Notifications
- WhatsApp Integration
- Slack Integration
- Voice Call Alerts
- Interactive Dashboard
- PDF Incident Reports
- GIS/Map Visualization
- Multi-Agent AI Coordination

---

# 🎯 Learning Outcomes

This project demonstrates practical experience with:

- AI Workflow Automation
- Prompt Engineering
- API Integration
- AI Decision Support Systems
- Low-Code Development
- Cloud Automation
- Intelligent Incident Management

---

# 👩‍💻 Author

**Chaitrika Nelluri**

Computer Science & Information Technology Student

GitHub:  
https://github.com/ChaitrikaNelluri

---

# 📜 License

This project is licensed under the MIT License.

---

⭐ **If you found this project interesting, consider giving it a star!**
