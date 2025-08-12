# 🚆 SNCFT Freight Management App
**Project carried out as part of a summer internship**  
📅 **Duration:** 08/07/2024 → 08/08/2024  
🏢 **Company:** SNCFT – Railway Freight Sector

## 📖 Project Overview

This project is a **Flutter mobile application** connected to a **Node.js/Express backend with MongoDB**, designed for the **management and optimization of railway freight** for the **SNCFT** (Société Nationale des Chemins de Fer Tunisiens).

[![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)](https://flutter.dev/)
[![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)
[![Express.js](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)](https://expressjs.com/)
[![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![Mocha](https://img.shields.io/badge/mocha.js-323330?style=for-the-badge&logo=mocha&logoColor=Brown)](https://mochajs.org/)

---

### Problem Statement
The current freight management system faces several challenges:
- **Lack of traceability** and visibility of goods
- **Delivery delays**
- **Insufficient optimization** of routes and underutilization of resources  
- **Manual tracking** of shipments and lack of communication between stakeholders
- **High logistics costs** and operational complexity
- **Difficult management** of customer complaints
- **Non-optimized train maintenance**
- **Inaccessibility** of data on mobile devices

### Solution
The aim is to provide a digital solution that:
- ✅ Improves shipment traceability and visibility
- ✅ Reduces logistics costs
- ✅ Optimizes resource usage
- ✅ Facilitates communication between stakeholders in the railway transport process
- ✅ Enhances customer satisfaction
- ✅ Provides real-time monitoring and notifications

## 🎯 Objectives

- 📊 **Manage clients** and track orders
- 🚂 **Manage train routes** and schedules
- 🚛 **Manage wagons** and drivers
- 📞 **Track complaints** and customer reviews
- 📋 **Maintain transaction** and shipment history
- 🔔 **Provide real-time notifications**
- 💬 **Enable internal messaging** between stakeholders
- ⏰ **Allow customers** to consult train schedules

### Mission
To ensure secure and punctual railway transport while developing infrastructure to meet customer demands.

### Core Values
- 🛡️ **Security** - Ensuring safe operations
- ⚡ **Efficiency** - Optimizing performance
- 💡 **Innovation** - Embracing new technologies
- 🌱 **Sustainability** - Environmental responsibility

### Services
- 🚂 **Passenger Transport**
- 📦 **Freight Transport**
- 🔧 **Railway Maintenance**
- 🏗️ **Infrastructure Development**
- 💡 **Technological Innovation**

## 🚀 Features

### For Clients
- 📱 **Secure Registration & Authentication**
- 📦 **Order Management** for freight services
- 🚛 **Real-time Shipment Tracking**
- 📅 **Train Schedule Consultation**
- 💬 **Integrated Complaint System**
- 📊 **Transaction History**
- 🔔 **Push Notifications**
- 💬 **Messaging** with operators

### For Administrators
- 👥 **User Management** (clients, drivers, operators)
- 🚂 **Train & Wagon Management**
- 👨‍✈️ **Driver Management**
- 📋 **Order Supervision**
- 🎯 **Shipment Management**
- 📞 **Complaint Processing**
- 📈 **Analytics Dashboard**

### For Drivers
- 🗺️ **Assigned Route Consultation**
- ⏰ **Schedule Management**
- 📱 **Optimized Mobile Interface**
- 🔔 **Mission Notifications**

### For Operators
- 📊 **Operational Monitoring**
- 🚛 **Shipment Management**
- 📞 **Customer Support**
- 📋 **Activity Coordination**

## 🛠️ Technologies Used

### **Frontend**
- **[Flutter](https://flutter.dev/)** - Cross-platform mobile development framework
- **Dart** - Programming language
- **MVC Architecture** - Model-View-Controller pattern
- Responsive and user-friendly interfaces

### **Backend**
- **[Node.js](https://nodejs.org/)** - JavaScript runtime environment
- **[Express.js](https://expressjs.com/)** - Web framework for Node.js
- **[MongoDB](https://www.mongodb.com/)** - NoSQL database
- **Mongoose** - MongoDB ODM
- **JWT** - JSON Web Tokens for authentication

### **Testing**
- **[Mocha](https://mochajs.org/)** - JavaScript testing framework
- **[Chai](https://www.chaijs.com/)** - Assertion library for testing

### **Development Tools**
- **Android Studio** - Flutter development IDE
- **Visual Studio Code** - Code editor
- **Postman** - API testing
- **MongoDB Compass** - MongoDB GUI

## ⚙️ Architecture

The application follows the **MVC (Model-View-Controller)** architecture for clear separation of concerns:

```
📱 Frontend (Flutter)
    ↕️ REST API
🌐 Backend (Express.js)
    ↕️ Mongoose ODM
🗄️ Database (MongoDB)
```

- **MVC Architecture** (Model - View - Controller)
- **Secure REST API** with JWT authentication
- **Communication** between frontend and backend via HTTP/JSON
- **Hosted MongoDB** database

## 📂 Repository Structure

```
sncft-freight-app/
├── 📱 frontend/              # Flutter Application
│   ├── lib/
│   │   ├── models/          # Data models
│   │   ├── views/           # User interfaces
│   │   ├── controllers/     # Business logic
│   │   ├── services/        # API services
│   │   └── config/          # App configuration
│   ├── test/                # Flutter tests
│   └── pubspec.yaml
├── 🖥️ backend/               # Node.js API
│   ├── models/              # MongoDB models
│   ├── routes/              # API routes
│   ├── controllers/         # Controllers
│   ├── middleware/          # Middleware functions
│   ├── config/              # Database config
│   ├── tests/               # Unit tests (Mocha/Chai)
│   └── package.json
├── 📄 docs/                 # Documentation
└── 📝 README.md
```

## 📦 Installation

### Prerequisites
- Flutter SDK (≥ 3.0.0)
- Node.js (≥ 16.0.0)
- MongoDB (≥ 5.0.0)
- Android Studio / Xcode (for emulators)

### Backend Setup
```bash
# Clone the repository
git clone https://github.com/your-username/sncft-freight-app.git
cd sncft-freight-app/backend

# Install dependencies
npm install

# Configure environment variables
cp .env.example .env
# Edit the .env file with your configurations

# Start the server
npm start
```

### Frontend Setup
```bash
cd ../frontend

# Install Flutter dependencies
flutter pub get

# Run the application
flutter run
```

## 📱 Application Screenshots

### 🌟 Welcome & Authentication Interfaces

#### **Loading Interface**
![Loading Screen](screenshots/landing.png)
*Welcome screen displaying the SNCFT logo, greeting visitors before they access the application.*

#### **Welcome Interfaces**
![Welcome Screens](screenshots/acceuil.png)
*Introduction to application features, highlighting the role of each stakeholder involved in railway freight management.*

#### **Authentication Interfaces**

##### Registration Process
![Registration](screenshots/register.png)
*User-friendly registration form where users can enter personal information to create an account.*

![Company Details](screenshots/company.png)
*Interface allowing users to enter company details after registration, including business name, address, and contact information.*

##### Password Recovery & Login
![OTP Interface](screenshots/otp.png)
*Password reset interface offering OTP code delivery via email for forgotten passwords.*

![Login Interface](screenshots/login.PNG)
*Login interface enabling users to access the application with email and password credentials.*

#### **Public Information Access**

##### Train Schedule Consultation
![Train Schedules](screenshots/horairestrains.png)
*Interface for visitors to access train schedules and available routes for raw material transportation.*

##### General Information Access
![General Information](screenshots/inforGen.png)
*Interface providing information about SNCFT services, including transported materials, transport conditions, and available options.*

---

### 🔧 Common Interfaces (All User Types)

#### **Settings Interface**
![Settings](screenshots/setting.png)
*Settings interface allowing users to customize their experience with dark/light mode toggle and language selection (Arabic, French, English). Also provides SNCFT contact information and social media links.*

#### **Profile Management**
![Profile Management](screenshots/profile.png)
*User-friendly profile management interface enabling users to customize and update personal information, including profile picture modification.*

#### **Communication Features**

##### Real-time Messaging
![Chat Interface](screenshots/chat.png)
*Real-time messaging interface facilitating instant communication between administrators and operators.*

##### Notification System
![Notifications](screenshots/notifications.png)
*Notification interface ensuring all stakeholders receive important updates for efficient communication and optimal responsiveness.*

---

### 👤 Client Interface

#### **Dashboard**
![Client Dashboard](screenshots/dashclient.png)
*Client dashboard providing overview of activities, including order statistics and recent delivery summaries.*

#### **Train Schedule Consultation**
![Train Times](screenshots/timeTrain.png)
*Interface allowing clients to easily search schedules by selecting departure/arrival stations and departure date.*

#### **Order Management**
![Order Management](screenshots/gererorder.png)
*Comprehensive order management interface enabling clients to track order progress, access delivery details, view estimated timelines, and add/modify/delete unprocessed orders. Also provides order history consultation.*

#### **Complaint Management**
![Complaints](screenshots/reclam.png)
*Complaint management interfaces allowing clients to submit complaints for order-related issues.*

#### **Review System**
![Reviews](screenshots/avis.png)
*Review interface enabling clients to evaluate service quality with star rating system to gather constructive feedback for service improvement.*

---

### ⚙️ Administrator Interface

#### **Administrator Dashboard**
![Admin Dashboard](screenshots/dashadmin.png)
*Comprehensive administrator dashboard providing global overview of order management activities, trains, incidents, and transported materials.*

#### **User Management**
![User Management](screenshots/user.png)
*User management interface allowing administrators to create, modify, or delete user accounts and assign roles (driver, operator, client, etc.).*

#### **Train Management**
![Train Management](screenshots/gestiontrain.png)
*Train management interface enabling administrators to supervise routes, schedules, and capacities of trains used for raw material transportation.*

---

## 🚀 Future Perspectives

- 🤖 **Artificial Intelligence** for process and resource optimization
- 🗺️ **Real-time Geolocation** of trains
- 📊 **Advanced Analytics** and reporting
- 🌐 **Web Version** of the application
- 🌍 **Multi-language Support**
- 📈 **Performance Monitoring**
- 🔐 **Enhanced Security Features**

---

**Developed with ❤️ to modernize railway transport in Tunisia** 🇹🇳

*This project represents a significant step towards digital transformation in the railway freight industry, providing stakeholders with modern tools for efficient and transparent freight management.*