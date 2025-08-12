# 🚆 SNCFT Freight Management App

A modern Flutter mobile application with Node.js backend for railway freight management and optimization.

[![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)](https://flutter.dev/)
[![Node.js](https://img.shields.io/badge/Node.js-43853D?style=flat-square&logo=node.js&logoColor=white)](https://nodejs.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white)](https://www.mongodb.com/)

**📅 Duration:** July - August 2024 | **🏢 Company:** SNCFT – Railway Freight Sector

---

## 📖 Overview

Digital solution for **SNCFT** (Société Nationale des Chemins de Fer Tunisiens) freight management, addressing key operational challenges through mobile technology and real-time tracking.

### Key Problems Solved
- ❌ Manual shipment tracking → ✅ Real-time digital tracking
- ❌ Poor communication → ✅ Integrated messaging system  
- ❌ High logistics costs → ✅ Route optimization
- ❌ Customer complaints → ✅ Streamlined complaint management

## 🎯 Features by User Role

<table>
<tr>
<td width="50%">

### 👤 **Clients**
- Order management & tracking
- Real-time shipment status
- Train schedule consultation
- Complaint system
- Transaction history

### 👨‍💼 **Administrators**
- User & role management
- Train & wagon oversight
- Order supervision
- Analytics dashboard
- System configuration

</td>
<td width="50%">

### 🚛 **Drivers**
- Route assignments
- Schedule management
- Mission notifications
- Mobile-optimized interface

### 👨‍💻 **Operators**  
- Operational monitoring
- Shipment coordination
- Customer support
- Activity tracking

</td>
</tr>
</table>

## 🛠️ Tech Stack

**Frontend:** Flutter (Dart) • MVC Architecture  
**Backend:** Node.js • Express.js • MongoDB • Mongoose • JWT  
**Testing:** Mocha • Chai  
**Tools:** Android Studio • VS Code • Postman

## ⚙️ Architecture

```mermaid
graph TB
    A[📱 Flutter App] --> B[🌐 REST API]
    B --> C[🖥️ Express.js]
    C --> D[🗄️ MongoDB]
```

**MVC Pattern** with secure JWT authentication and real-time communication.

## 📂 Project Structure

```
sncft-freight-app/
├── 📱 frontend/          # Flutter app
│   ├── lib/
│   │   ├── models/      # Data models
│   │   ├── views/       # UI screens
│   │   ├── controllers/ # Business logic
│   │   └── services/    # API integration
│   └── test/
├── 🖥️ backend/          # Node.js API
│   ├── models/         # MongoDB schemas
│   ├── routes/         # API endpoints
│   ├── controllers/    # Logic handlers
│   └── tests/          # Unit tests
└── 📄 docs/            # Documentation
```

## 🚀 Quick Start

### Prerequisites
- Flutter SDK ≥3.0.0, Node.js ≥16.0.0, MongoDB ≥5.0.0

### Installation

```bash
# 1. Clone repository
git clone https://github.com/your-username/sncft-freight-app.git

# 2. Backend setup
cd sncft-freight-app/backend
npm install
cp .env.example .env  # Configure your environment
npm start

# 3. Frontend setup  
cd ../frontend
flutter pub get
flutter run
```

## 📱 Application Showcase

### 🔐 Authentication Flow
<div align="center">
<img src="screenshots/login.PNG" width="200" alt="Login"/>
<img src="screenshots/register.png" width="200" alt="Register"/>
<img src="screenshots/otp.png" width="200" alt="OTP"/>
</div>

### 📊 Dashboard Views
<div align="center">
<img src="screenshots/dashclient.png" width="200" alt="Client Dashboard"/>
<img src="screenshots/dashadmin.png" width="200" alt="Admin Dashboard"/>
</div>

### ⚙️ Core Features
<div align="center">
<img src="screenshots/gererorder.png" width="150" alt="Order Management"/>
<img src="screenshots/timeTrain.png" width="150" alt="Train Schedule"/>
<img src="screenshots/chat.png" width="150" alt="Messaging"/>
<img src="screenshots/notifications.png" width="150" alt="Notifications"/>
</div>

*More screenshots available in `/screenshots` directory*

## 🚀 Future Enhancements

- 🤖 AI-powered route optimization
- 🗺️ Real-time GPS tracking  
- 📊 Advanced analytics dashboard
- 🌐 Web application version
- 🌍 Multi-language support

---

## 📄 License & Contact

**Project Duration:** July-August 2024  
**Internship:** SNCFT Railway Freight Sector

*Developed to modernize railway transport in Tunisia* 🇹🇳

---

<div align="center">
<strong>Built with ❤️ for digital transformation in railway logistics</strong>
</div>