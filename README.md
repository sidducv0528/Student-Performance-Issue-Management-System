# 🚀 Smart Feedback & Student Performance Management System

<p align="center">
  <b>An End-to-End Automated Academic Analytics & Issue Resolution Platform</b><br>
  Designed to streamline student performance tracking and institutional support workflows.
</p>

---

## 🔗 Quick Access

<p align="center">

<a href="https://youtu.be/24SNZvqx7Ls?si=R4Nc2qOIgip75MEm" target="_blank">
  <img src="https://img.shields.io/badge/🎬_Watch_Demo-FF0000?style=for-the-badge&logo=youtube&logoColor=white"/>
</a>

<a href="https://script.google.com/macros/s/AKfycbylG7dAZqwKu9vtdN43snP2M2GK4mvBrDja6zpKpMB0qW_7BXWtq25zfI4qNkgcwFSq/exec" target="_blank">
  <img src="https://img.shields.io/badge/🌐_Live_Web_App-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white"/>
</a>

<a href="https://docs.google.com/spreadsheets/d/1pfKE8nWOIghgew9lF2CqLoidj8pdKDlWQvvNUwZz5wM/edit?usp=sharing" target="_blank">
  <img src="https://img.shields.io/badge/📊_View_Google_Sheet-34A853?style=for-the-badge&logo=googlesheets&logoColor=white"/>
</a>

<a href="Project_Documentation.pdf">
  <img src="https://img.shields.io/badge/📄_View_Documentation-000000?style=for-the-badge&logo=adobeacrobatreader&logoColor=white"/>
</a>

<a href="architecture.png">
  <img src="https://img.shields.io/badge/🏗️_View_Architecture-2E8B57?style=for-the-badge"/>
</a>

</p>

---

# 📌 Problem Statement

Educational institutions often struggle with:

- Manual student performance tracking  
- No automated reporting system  
- Unstructured issue resolution  
- No transparent ticket tracking  
- Delayed academic risk detection  

These inefficiencies result in poor visibility and slower administrative action.

---

# 💡 Project Overview

The **Smart Feedback & Student Performance Management System** is a fully automated workflow platform that transforms raw student data into structured insights and actionable support mechanisms.

It integrates:

- 📊 Performance Analytics  
- 📩 Automated Email Reporting  
- 🎫 Smart Ticket Generation  
- 🌐 Live Ticket Tracking Portal  
- 📈 Academic Risk Prediction  

This system connects performance monitoring with structured issue management in one seamless automation pipeline.

---

# 🏗️ System Architecture

## 🔄 End-to-End Workflow

```
Student Data (Google Sheets / Excel)
        ↓
Performance & Risk Engine
        ↓
Dashboard Generation
        ↓
PDF Auto Creation
        ↓
Weekly Automated Email
        ↓
Smart Feedback Form
        ↓
Auto Ticket Generation
        ↓
Admin Monitoring
        ↓
Web-Based Ticket Tracker
```

---

## 📊 Architecture Preview

![System Architecture](architecture.png)

---

# ⚙️ Core Features

## 📊 1. Performance Analytics Engine
- Attendance percentage calculation  
- Semester-wise marks analysis  
- Automated average computation  
- Performance classification:
  - Excellent
  - Very Good
  - Good
  - Average
  - Poor  
- Risk detection based on attendance and performance  

---

## 📩 2. Automated Weekly Email Reports
- Personalized academic summary  
- Attendance & risk alerts  
- Fee status updates  
- Direct dashboard link  
- Fully automated using Google Apps Script  

---

## 🎫 3. Smart Ticket Management System
- Conditional issue submission form  
- Unique Ticket ID generation  
- Automatic database logging  
- Confirmation email sent to student  
- Ticket status tracking system  

---

## 🌐 4. Web-Based Ticket Tracker
Students can:
- Enter their Ticket ID  
- Check live status  
- View resolution updates  

---

# 🧠 Risk Prediction Logic (Sample)

```javascript
const performance =
  avgVal >= 75 ? "Excellent" :
  avgVal >= 50 ? "Good" :
  "Needs Improvement";

const riskPredictor =
  attVal < 75 ? "High Risk (Attendance below 75%)" :
  "Safe";
```

---

# 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| Data Storage | Google Sheets |
| Backend | Google Apps Script |
| Logic | JavaScript |
| UI | HTML / CSS |
| Reporting | Excel Dashboards |
| Email Automation | MailApp Service |

---

# 📂 Project Structure

```
📁 Student-Performance-Issue-Management-System
 ├── README.md
 ├── architecture.png
 ├── Project_Documentation.pdf
 ├── google_apps_script.gs
 ├── screenshots/
```

---

# 📈 Real-World Applications

This architecture can scale into:

- Corporate performance monitoring systems  
- HR grievance management platforms  
- Customer support helpdesk solutions  
- SaaS-based ticketing tools  
- Enterprise workflow automation systems  

---

# 🚀 Why This Project Stands Out

This project demonstrates:

- End-to-End System Design  
- Automation Workflow Engineering  
- Backend Logic Development  
- Product-Level Thinking  
- Scalable Architecture Planning  
- Real-World Problem Solving  

---

# 🔒 Data Privacy Notice

All data used in this repository is sample/demo data for academic purposes only.  
Sensitive information should not be publicly exposed in production environments.

---

# 🔮 Future Enhancements (Version 2.0)

- Admin analytics dashboard with ticket statistics  
- Firebase / Supabase database integration  
- Role-based authentication system  
- AI-based risk scoring model  
- Deployment on Vercel / Netlify  
- Advanced BI reporting dashboards  

---

# 👨‍💻 Author

**Siddu V**  
Computer Science Engineer  
Focused on Automation, System Design & Data Analytics  

---

⭐ If you found this project valuable, consider giving it a star!
