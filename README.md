# 🚀 Smart Feedback & Student Performance Management System

<p align="center">
  <b>An End-to-End Automated Academic Analytics & Issue Resolution Platform</b><br>
  Designed to streamline student performance tracking and institutional support systems.
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

<a href="Project_Documentation.pdf">
  <img src="https://img.shields.io/badge/📄_View_Documentation-000000?style=for-the-badge&logo=adobeacrobatreader&logoColor=white"/>
</a>

<a href="architecture.png">
  <img src="https://img.shields.io/badge/🏗️_View_Architecture-2E8B57?style=for-the-badge"/>
</a>

</p>

---

# 📌 Problem Statement

Educational institutions often face challenges such as:

- Manual student performance tracking
- No automated communication system
- Lack of structured issue resolution
- No transparency in ticket handling
- Delayed intervention for at-risk students

These inefficiencies reduce academic visibility and delay problem resolution.

---

# 💡 Project Overview

The **Smart Feedback & Student Performance Management System** is a fully automated workflow platform that transforms raw academic data into actionable insights and structured support management.

It integrates:

- 📊 Performance Analytics  
- 📩 Automated Email Reporting  
- 🎫 Smart Ticket Generation  
- 🌐 Live Ticket Tracking Portal  
- 📈 Risk Prediction Engine  

This system bridges academic monitoring with structured issue resolution in a single automated pipeline.

---

# 🏗️ System Architecture

## 🔄 End-to-End Workflow

```
Student Data (Excel / SQL)
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
- Average score computation
- Performance classification:
  - Excellent
  - Very Good
  - Good
  - Average
  - Poor
- Risk detection based on attendance & marks

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
- Status tracking capability

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

This architecture can scale beyond educational institutions into:

- Corporate employee performance tracking
- HR grievance management systems
- Customer support helpdesk platforms
- SaaS ticketing systems
- Enterprise workflow automation tools

---

# 🚀 Why This Project Stands Out

This project demonstrates:

- End-to-End System Design
- Automation Workflow Engineering
- Backend Logic Development
- Product-Oriented Thinking
- Real-World Problem Solving
- Scalable Architecture Planning

---

# 🔒 Data Privacy Notice

All data included in this repository is sample/demo data for academic purposes only.  
No real student data is publicly shared.

---

# 🔮 Future Enhancements (Version 2.0)

- Admin analytics dashboard with ticket statistics
- Firebase / Supabase database integration
- Role-based authentication system
- AI-based risk scoring model
- Deployment on Vercel / Netlify
- Advanced analytics dashboards using BI tools

---

# 👨‍💻 Author

**Siddu V**  
Computer Science Engineer  
Focused on Automation, System Design & Data Analytics  

---

⭐ If you found this project interesting, consider giving it a star!
