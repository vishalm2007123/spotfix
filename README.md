

# 🚀 SpotFix — Smart Civic Issue Reporting Platform





## 📌 Problem Statement

Civic issues such as potholes, garbage overflow, streetlight failures, and drainage problems often remain unresolved due to slow reporting systems and lack of transparency between citizens and authorities.



## 💡 Solution — SpotFix

**SpotFix** is a smart civic engagement platform that allows citizens to report issues easily, track their resolution status transparently, and visualize complaint hotspots using an **interactive heatmap**.

The platform bridges the gap between **citizens and government authorities** through dedicated dashboards, analytics, and a reward-based engagement system.



## ✨ Features

### 👤 Citizen Module

* 🔐 OTP-based Registration (No backend required)
* 📝 Report civic issues with category & location
* 📦 **Complaint Tracking System**
  *(Pending → Verified → In-Progress → Solved)*
* 🪙 **Coins & Rewards System** for participation
* 🗺️ **Live Heatmap** showing complaint density
* 🤖 **Rule-Based Chatbot Assistant**
* 📊 Personal dashboard with complaint statistics
* 📝 **Anonymous Survey Page** (No login required)



### 🧑‍💼 Government / Staff Module

* 📊 Staff dashboard with complaint analytics
* 🗂️ Issue management & status updates
* ⏳ Deadline-based tracking (simulated)
* 💰 Budget allocation overview (demo)
* 📍 Location-based issue visualization



### 🗺️ Heatmap System

* Built using **Leaflet + Leaflet Heatmap**
* Status-based intensity:

  * 🔴 **Pending** — High intensity
  * 🟠 **In-Progress / Verified** — Medium intensity
  * 🟢 **Solved** — Low intensity
* Interactive markers with detailed popups


## 🛠️ Tech Stack

| Layer    | Technology                |
| -------- | ------------------------- |
| Frontend | HTML, CSS, JavaScript     |
| Maps     | Leaflet.js, OpenStreetMap |
| Heatmap  | Leaflet.heat              |
| Storage  | Browser LocalStorage      |
| Chatbot  | Rule-based JavaScript Bot |
| UI       | Custom Modern UI (CSS)    |


## 📂 Project Structure

```
SpotFix/
│
├── index.html            # Landing page
├── register.html         # User registration (OTP-based)
├── home.html             # Citizen dashboard
├── report.html           # Issue reporting page
├── user_complaints.html  # Complaint tracking
├── staff_login.html      # Staff login
├── staff_dashboard.html  # Government dashboard
├── rewards.html          # Coins & rewards
├── survey.html           # Anonymous survey
└── README.md             # Documentation
```








## 🚀 Future Enhancements

* Backend integration (Node.js / Firebase)
* Real-time notifications
* AI-powered chatbot
* Mobile application
* Role-based authentication
* Government API integration






