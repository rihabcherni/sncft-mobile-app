# 🚆 SNCFT Freight Management App
> **Digital transformation for Tunisian railway freight transport**  
> 📅 **Duration:** July 8 - August 8, 2024 | 🏢 **Company:** SNCFT Railway Freight Sector

[![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white)](https://flutter.dev/) [![Node.js](https://img.shields.io/badge/Node.js-43853D?style=flat&logo=node.js&logoColor=white)](https://nodejs.org/) [![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat&logo=mongodb&logoColor=white)](https://www.mongodb.com/) [![Express.js](https://img.shields.io/badge/Express.js-404D59?style=flat)](https://expressjs.com/)

## Overview
Flutter mobile app with Node.js/Express backend and MongoDB for **SNCFT railway freight management and optimization**.

### Problem & Solution

| **Current Challenges** | **Our Solution** |
|------------------------|------------------|
| ❌ Lack of shipment traceability | ✅ Real-time tracking system |
| ❌ Manual processes & delays | ✅ Automated workflow management |
| ❌ Poor resource optimization | ✅ Smart resource allocation |
| ❌ Limited mobile accessibility | ✅ Cross-platform mobile app |
| ❌ High operational costs | ✅ Cost optimization tools |

## Technology Stack
| **Category** | **Technologies** |
|--------------|------------------|
| **Frontend** | Flutter, Dart, MVC Architecture |
| **Backend** | Node.js, Express.js, JWT Authentication |
| **Database** | MongoDB, Mongoose ODM |
| **Testing** | Mocha, Chai |
| **Tools** | Android Studio, VS Code, Postman, MongoDB Compass |


## Key Features

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

## Quick Start
- Prerequisites  Flutter SDK ≥3.0.0, Node.js ≥16.0.0, MongoDB ≥5.0.0
- Setup
| **Backend** | **Frontend** |
|-------------|--------------|
| `git clone [repo-url]` | `cd frontend/` |
| `cd backend/ && npm install` | `flutter pub get` |
| `cp .env.example .env` | `flutter run` |
| `npm start` | |

## Application Interfaces

### Authentication & Welcome
| **Screen** | **Description** |
|------------|-----------------|
| <img src="screenshots/landing.png" width="100"/> | **Loading Screen** - SNCFT welcome interface |
| <img src="screenshots/acceuil.png" width="250"/> | **Welcome Screens** - Feature introduction for stakeholders |
| <img src="screenshots/register.png" width="250"/> <img src="screenshots/company.png" width="200"/> | **Registration** - User signup with company details |
| <img src="screenshots/otp.png" width="250"/> <img src="screenshots/login.PNG" width="200"/> | **Authentication** - OTP recovery & secure login |

### Common Interfaces
| **Feature** | **Interface** | **Description** |
|-------------|---------------|-----------------|
| **Settings** | <img src="screenshots/setting.png" width="250"/> | Theme toggle, language selection, contact info |
| **Profile** | <img src="screenshots/profile.png" width="200"/> | Personal information & profile picture management |
| **Messaging** | <img src="screenshots/chat.png" width="200"/> | Real-time communication between users |
| **Notifications** | <img src="screenshots/notifications.png" width="120"/> | Important updates & alerts system |

### Client Features
| **Function** | **Interface** | **Capabilities** |
|--------------|---------------|------------------|
| **Dashboard** | <img src="screenshots/dashclient.png" width="200"/> | Activity overview, order statistics, delivery summaries |
| **Schedules** | <img src="screenshots/timeTrain.png" width="200"/> | Train schedule search by station & date |
| **Orders** | <img src="screenshots/gererorder.png" width="280"/> | Order tracking, management, history, CRUD operations |
| **Support** | <img src="screenshots/reclam.png" width="280"/> <img src="screenshots/avis.png" width="110"/> | Complaint submission & service rating system |

### Admin Features
| **Management Area** | **Interface** | **Functions** |
|--------------------|---------------|---------------|
| **Dashboard** | <img src="screenshots/dashadmin.png" width="200"/> | Global overview of operations, orders, trains, incidents |
| **Users** | <img src="screenshots/user.png" width="120"/> | User account creation, modification, role assignment |
| **Trains** | <img src="screenshots/gestiontrain.png" width="250"/> | Route supervision, schedule & capacity management |

### Public Access
| **Service** | **Interface** | **Access** |
|-------------|---------------|------------|
| **Train Schedules** | <img src="screenshots/horairestrains.png" width="200"/> | Public transport timetable consultation |
| **General Info** | <img src="screenshots/inforGen.png" width="200"/> | SNCFT services, materials, transport conditions |

## SNCFT Mission & Values
| **Component** | **Description** |
|---------------|-----------------|
| **🎯 Mission** | Secure, punctual railway transport with infrastructure development |
| **💎 Values** | 🛡️ Security, ⚡ Efficiency, 💡 Innovation, 🌱 Sustainability |
| **📋 Services** | Passenger transport, freight transport, maintenance, infrastructure, tech innovation |

## Future Roadmap
| **Planned Features** |
|---------------------|
| 🤖 AI optimization, 🗺️ real-time geolocation |
| 📊 Advanced analytics, 🌐 web version |
| 🌍 Multi-language support, 📈 performance monitoring |
| 🔐 Enhanced security, additional integrations |