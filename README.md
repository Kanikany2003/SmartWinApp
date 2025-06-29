# SmartWin App 🚀

This project is a **web application** 🖥️ for displaying motorcycle taxi driver information and collecting customer feedback. It fetches driver data **securely** from a Firebase Cloud Function, which proxies requests to a Google Apps Script connected to a Google Sheet backend.

## 🎯 Objective
To provide an **easy-to-use**, **friendly**, and **trustworthy** system for passengers to view motorcycle taxi driver details and submit feedback or complaints through QR code scanning. The goal is to improve service quality and build community trust.

## 🌟 What it does
- ✅ When a user scans a QR code (containing driver ID), the app shows driver details
- 📝 Provides buttons linking to Google Forms for satisfaction surveys and complaints with driver info pre-filled
- 📊 Data is saved into Google Sheets for later analysis
- 💬 Friendly interface with styled HTML, smooth animations, and responsive design

## ✨ Features
- Show driver details (ID, location, shirt number, name, license plate)
- Buttons for satisfaction & complaint feedback via Google Forms
- Emergency contact buttons
- Smooth fade-in animations & modern styling using HTML + CSS
- Secure backend with Cloud Function (API URL hidden from frontend)

## 🛠️ Tech Stack
- Frontend: HTML, CSS (animated effects, friendly UI), JavaScript
- Backend: Firebase Cloud Functions (Node.js)
- Data storage: Google Sheets via Google Apps Script

## 🔒 Security
- Backend Cloud Function hides sensitive endpoints
- Firebase project protected with IAM, firewall, and access control rules
- No sensitive data in frontend code


