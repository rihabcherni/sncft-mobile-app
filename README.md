# 🚆 SNCFT Freight Management App

> **Digital transformation for Tunisian railway freight transport**  
> 📅 **Duration:** July 8 - August 8, 2024 | 🏢 **Company:** SNCFT Railway Freight Sector

[![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white)](https://flutter.dev/) [![Node.js](https://img.shields.io/badge/Node.js-43853D?style=flat&logo=node.js&logoColor=white)](https://nodejs.org/) [![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat&logo=mongodb&logoColor=white)](https://www.mongodb.com/) [![Express.js](https://img.shields.io/badge/Express.js-404D59?style=flat)](https://expressjs.com/)

## 📖 Overview

Flutter mobile app with Node.js/Express backend and MongoDB for **SNCFT railway freight management and optimization**.

### 🎯 Problem & Solution

| **Current Challenges** | **Our Solution** |
|------------------------|------------------|
| ❌ Lack of shipment traceability | ✅ Real-time tracking system |
| ❌ Manual processes & delays | ✅ Automated workflow management |
| ❌ Poor resource optimization | ✅ Smart resource allocation |
| ❌ Limited mobile accessibility | ✅ Cross-platform mobile app |
| ❌ High operational costs | ✅ Cost optimization tools |

## 🛠️ Technology Stack

| **Category** | **Technologies** |
|--------------|------------------|
| **Frontend** | Flutter, Dart, MVC Architecture |
| **Backend** | Node.js, Express.js, JWT Authentication |
| **Database** | MongoDB, Mongoose ODM |
| **Testing** | Mocha, Chai |
| **Tools** | Android Studio, VS Code, Postman, MongoDB Compass |

## ⚙️ Architecture

```
📱 Flutter App (MVC) ↔️ 🌐 Express.js API ↔️ 🗄️ MongoDB
```

## 🚀 Key Features

### User Roles & Features

| **Role** | **Core Features** |
|----------|-------------------|
| **👤 Client** | Order management, shipment tracking, schedule consultation, complaints, reviews |
| **👨‍💼 Admin** | User/train/wagon management, order supervision, analytics dashboard |
| **🚛 Driver** | Route consultation, schedule management, mission notifications |
| **⚙️ Operator** | Operational monitoring, shipment management, customer support |

### Common Features
- 🔐 Secure authentication & registration
- 🔔 Real-time notifications
- 💬 Internal messaging system
- 📊 Transaction history
- ⚙️ Profile & settings management

## 📂 Project Structure

```
sncft-freight-app/
├── 📱 frontend/           # Flutter app (MVC pattern)
│   ├── lib/{models,views,controllers,services,config}/
│   └── test/
├── 🖥️ backend/            # Node.js API
│   ├── {models,routes,controllers,middleware,config}/
│   └── tests/
└── 📄 docs/
```

## 📦 Quick Start

### Prerequisites
- Flutter SDK ≥3.0.0, Node.js ≥16.0.0, MongoDB ≥5.0.0

### Setup

| **Backend** | **Frontend** |
|-------------|--------------|
| `git clone [repo-url]` | `cd frontend/` |
| `cd backend/ && npm install` | `flutter pub get` |
| `cp .env.example .env` | `flutter run` |
| `npm start` | |

## 📱 Application Interfaces

### 🌟 Authentication & Welcome

| **Screen** | **Description** |
|------------|-----------------|
| ![Loading](screenshots/landing.png) | **Loading Screen** - SNCFT welcome interface |
| ![Welcome](screenshots/acceuil.png) | **Welcome Screens** - Feature introduction for stakeholders |
| ![Register](screenshots/register.png) ![Company](screenshots/company.png) | **Registration** - User signup with company details |
| ![OTP](screenshots/otp.png) ![Login](screenshots/login.PNG) | **Authentication** - OTP recovery & secure login |

### 🔧 Common Interfaces

| **Feature** | **Interface** | **Description** |
|-------------|---------------|-----------------|
| **Settings** | ![Settings](screenshots/setting.png) | Theme toggle, language selection, contact info |
| **Profile** | ![Profile](screenshots/profile.png) | Personal information & profile picture management |
| **Messaging** | ![Chat](screenshots/chat.png) | Real-time communication between users |
| **Notifications** | ![Notifications](screenshots/notifications.png) | Important updates & alerts system |

### 👤 Client Features

| **Function** | **Interface** | **Capabilities** |
|--------------|---------------|------------------|
| **Dashboard** | ![Client Dash](screenshots/dashclient.png) | Activity overview, order statistics, delivery summaries |
| **Schedules** | ![Train Times](screenshots/timeTrain.png) | Train schedule search by station & date |
| **Orders** | ![Order Mgmt](screenshots/gererorder.png) | Order tracking, management, history, CRUD operations |
| **Support** | ![Complaints](screenshots/reclam.png) ![Reviews](screenshots/avis.png) | Complaint submission & service rating system |

### ⚙️ Admin Features

| **Management Area** | **Interface** | **Functions** |
|--------------------|---------------|---------------|
| **Dashboard** | ![Admin Dash](screenshots/dashadmin.png) | Global overview of operations, orders, trains, incidents |
| **Users** | ![User Mgmt](screenshots/user.png) | User account creation, modification, role assignment |
| **Trains** | ![Train Mgmt](screenshots/gestiontrain.png) | Route supervision, schedule & capacity management |

### 📋 Public Access

| **Service** | **Interface** | **Access** |
|-------------|---------------|------------|
| **Train Schedules** | ![Public Schedule](screenshots/horairestrains.png) | Public transport timetable consultation |
| **General Info** | ![General Info](screenshots/inforGen.png) | SNCFT services, materials, transport conditions |

## 🌟 SNCFT Mission & Values

| **Component** | **Description** |
|---------------|-----------------|
| **🎯 Mission** | Secure, punctual railway transport with infrastructure development |
| **💎 Values** | 🛡️ Security, ⚡ Efficiency, 💡 Innovation, 🌱 Sustainability |
| **📋 Services** | Passenger transport, freight transport, maintenance, infrastructure, tech innovation |

## 🚀 Future Roadmap

| **Phase** | **Planned Features** |
|-----------|---------------------|
| **Phase 1** | 🤖 AI optimization, 🗺️ real-time geolocation |
| **Phase 2** | 📊 Advanced analytics, 🌐 web version |
| **Phase 3** | 🌍 Multi-language support, 📈 performance monitoring |
| **Phase 4** | 🔐 Enhanced security, additional integrations |

---

**🇹🇳 Developed with ❤️ for Tunisian railway transport modernization**

*Transforming freight management through digital innovation and efficient stakeholder collaboration.*