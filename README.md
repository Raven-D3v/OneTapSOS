<p align="center"> <img src="https://github.com/Raven-D3v/OneTapSOS/blob/b335f266417fe3104f9bd4d9aea1fc93cb112055/Logo/OneTapSOS-Logo.png" alt="OneTapSOS Banner" width="100%"> </p>

# 🆘 OneTapSOS

### **An AI-Powered SMS Emergency Alert System for Reporting Robbery and Assault**

OneTapSOS is a mobile safety application designed to help students report emergencies **quickly, discreetly, and even without internet access**. With just **one tap**, users can send an SMS alert containing their **location, emergency details, and incident type**—all processed through an **AI-powered classification system** to assist responders in prioritizing cases.

Built for real-world safety needs, OneTapSOS ensures that help is only one tap away during robbery, assault, harassment, or other emergencies.

---

## 🚨 Why OneTapSOS?

Traditional emergency apps require internet. **OneTapSOS works offline** and sends alerts via **SMS**, ensuring students can still call for help during:

* Low-signal or no-internet situations
* Late-night commutes
* Sudden emergencies where speed matters

The system supports:

* Fast one-tap SOS
* Voice-to-text emergency reporting
* Automatic GPS capture
* AI-based emergency classification
* Real-time monitoring via a responder dashboard

---

## 📱 Key Features

### ⭐ **One Tap SOS Alert**

Send an emergency alert instantly through SMS with all required information.

### 🎤 **Voice-to-Text Input**

Users can speak naturally, and the app converts it into an emergency message.

### 📍 **Automatic Location Tracking**

Accurate GPS coordinates are captured and included in the SMS alert.

### 🧠 **AI-Powered Classification**

On the responder side, the emergency message is automatically analyzed using a custom AI classifier to determine if the incident is:

* Robbery
* Assault
* Harassment
* Or Others

### 🖥️ **Responder Dashboard**

A Django-based web dashboard allows authorities to:

* View real-time emergency alerts
* Access incident history
* Analyze emergency trends
* Manage responder accounts

---

# 🖼️ App Screenshots

(Add your images here)

| Home Screen   | SOS Alert    | Voice Input    |
| ------------- | ------------ | -------------- |
| ![Home](link) | ![SOS](link) | ![Voice](link) |

| GPS Location | Login/Register | Settings          |
| ------------ | -------------- | ----------------- |
| ![GPS](link) | ![Login](link) | ![Settings](link) |

---

# 🖥️ System Demo & Dashboard

(Add system demo GIFs or images here)

### **Responder Dashboard**

* Incident List
* Emergency Details
* Map View
* Analytics Charts

| Dashboard          | Analytics          |
| ------------------ | ------------------ |
| ![Dashboard](link) | ![Analytics](link) |

---

# 🏗️ How OneTapSOS Works

1. User triggers SOS (tap or voice).
2. The app collects:

   * Message
   * Timestamp
   * GPS location
   * User details
3. The app converts everything into a structured SMS.
4. SMS is sent to the responder device (no internet needed).
5. The responder system runs AI classification to categorize the emergency.
6. The dashboard displays the alert in real-time for authorities to respond.

---

# 🧠 AI Technology Inside OneTapSOS

OneTapSOS uses a **lightweight, optimized emergency classifier**, designed to run on low-resource systems.
The model is built using:

* Custom keyword datasets (level 1–5 severity)
* CSV → JSON conversion tools
* A Python-based keyword-boosting engine
* Local, offline processing for privacy and speed

This ensures that emergency categories are detected accurately—even with short user messages.

---

# 👥 Target Users

OneTapSOS is built for:

* University students
* Working students commuting late
* At-risk individuals around campus
* Safety officers and security responders

---

# 🛠️ Technology Stack

* **Android (Kotlin/Java)** – Mobile app
* **Django** – Admin dashboard
* **Python** – AI classifier
* **SQLite/MySQL** – Data storage
* **SMS** – Offline emergency transmission

---

# 🎯 Project Purpose

OneTapSOS aims to provide a reliable, accessible, and internet-independent emergency reporting tool for students, empowering them to feel safer on and off campus.

---

# 📄 License

This project is developed for academic and research purposes under **City of Malabon University**.

---

If you'd like, I can also create:

✅ A shorter, minimal version for GitHub
✅ A dark-themed version
✅ A version with badge icons (e.g., Android, Django, Python badges)
✅ A README banner/header design
Just tell me your preferred style!
