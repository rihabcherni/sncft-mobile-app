# 🚆 SNCFT Freight Management App

[![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)](https://flutter.dev/)
[![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)
[![Express.js](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)](https://expressjs.com/)
[![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![Mocha](https://img.shields.io/badge/mocha.js-323330?style=for-the-badge&logo=mocha&logoColor=Brown)](https://mochajs.org/)

**Project carried out as part of a summer internship**  
📅 **Duration:** 08/07/2024 → 08/08/2024  
🏢 **Company:** SNCFT – Railway Freight Sector

---

## 📋 Table of Contents

- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Architecture](#architecture)
- [Repository Structure](#repository-structure)
- [Installation](#installation)
- [Configuration](#configuration)
- [Testing](#testing)
- [Screenshots](#screenshots)
- [Contributors](#contributors)
- [About SNCFT](#about-sncft)
- [License](#license)

## 📖 Project Overview

This project is a **Flutter mobile application** connected to a **Node.js/Express backend with MongoDB**, designed for the **management and optimization of railway freight** for the **SNCFT** (Société Nationale des Chemins de Fer Tunisiens).

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

## ⚙️ Configuration

### Environment Variables (.env)
```env
# Database
MONGODB_URI=mongodb://localhost:27017/sncft_freight_db

# Server
PORT=3000
NODE_ENV=development

# JWT Authentication
JWT_SECRET=your_jwt_secret_key
JWT_EXPIRES_IN=24h

# Email Configuration (optional)
EMAIL_SERVICE=gmail
EMAIL_USER=your_email@gmail.com
EMAIL_PASS=your_app_password
```

### Flutter Configuration
Modify the `lib/config/api_config.dart` file:
```dart
class ApiConfig {
  static const String baseUrl = 'http://localhost:3000/api';
  static const String wsUrl = 'ws://localhost:3000';
}
```

## 🧪 Testing

### Backend Tests
```bash
cd backend

# Run all tests
npm test

# Run tests with coverage
npm run test:coverage

# Run tests in watch mode
npm run test:watch
```

### Frontend Tests
```bash
cd frontend

# Unit tests
flutter test

# Integration tests
flutter test integration_test/
```

## 📱 Screenshots

### Authentication Screens
- Registration and login interface
- User profile management

### Admin Dashboard
- Comprehensive dashboard
- User and train management

### Client Interface
- Schedule consultation
- Order and complaint management

### Common Features
- Integrated messaging
- Notification system
- Application settings

## 🚀 Future Perspectives

- 🤖 **Artificial Intelligence** for process and resource optimization
- 🗺️ **Real-time Geolocation** of trains
- 📊 **Advanced Analytics** and reporting
- 🌐 **Web Version** of the application
- 🔄 **Offline Synchronization**
- 🌍 **Multi-language Support**
- 📈 **Performance Monitoring**
- 🔐 **Enhanced Security Features**

## 👥 Contributors

- **Cherni Rihab** - Lead Developer & Intern
- **Monsieur Mabrouk Ben Nour Cherif** - Project Supervisor

## 🏢 About SNCFT

**Société Nationale des Chemins de Fer Tunisiens (SNCFT)**
- 📍 67 Avenue Farhat Hached, BP 693, 1001 Tunis, Tunisia
- ☎️ (+216) 71 33 44 44
- 📧 sncft@sncft.com.tn
- 🌐 https://www.sncft.com.tn/

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

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 📞 Support

For questions or support regarding this project, please contact:
- 📧 Email: support@sncft-app.com
- 🐛 Issues: [GitHub Issues](https://github.com/your-username/sncft-freight-app/issues)

---

**Developed with ❤️ to modernize railway transport in Tunisia** 🇹🇳

*This project represents a significant step towards digital transformation in the railway freight industry, providing stakeholders with modern tools for efficient and transparent freight management.*