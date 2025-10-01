<p align="center">
<img width="222" height="199" alt="logoPharm" src="https://github.com/user-attachments/assets/51e4c130-dec2-4d90-9489-8f5b9e7b4aab" />
</p>

# 📍 Pharmacy Location Finder

> Easily locate nearby pharmacies with real-time availability and services.


<p align="center">
  <img src="https://img.shields.io/badge/React-18.2.0-20232A?logo=react&logoColor=61DAFB" alt="React"/>
  <img src="https://img.shields.io/badge/React%20Native-0.72.0-20232A?logo=react&logoColor=61DAFB" alt="React Native"/>
  <img src="https://img.shields.io/badge/Node.js-18.16.0-339933?logo=nodedotjs&logoColor=white" alt="Node.js"/>
  <img src="https://img.shields.io/badge/Express.js-4.18.2-000000?logo=express&logoColor=white" alt="Express.js"/>
  <img src="https://img.shields.io/badge/MongoDB-6.0-47A248?logo=mongodb&logoColor=white" alt="MongoDB"/>
</p>

## 📑 Table of Contents

- [✨ Features](#-features)  
- [🛠️ Installation Guide](#️-installation-guide)  
  - [Prerequisites](#prerequisites)  
  - [1. Clone the Repository](#1-clone-the-repository)  
  - [2. Backend Setup (`Backend-Pharmacy`)](#2-backend-setup-backend-pharmacy)  
  - [3. Web Application Setup (`Web-Pharmacy`)](#3-web-application-setup-web-pharmacy)  
  - [4. Mobile Application Setup (`Mobile-Pharmacy`)](#4-mobile-application-setup-mobile-pharmacy)  
- [🚀 Demo](#-demo)  
- [🛣️ Project Roadmap](#️-project-roadmap)  
- [🤝 Contribution Guidelines](#-contribution-guidelines)  
  - [Pull Request Process](#pull-request-process)  
  - [Testing Requirements](#testing-requirements)  
- [📝 License Information](#-license-information)  


## ✨ Features

*   🌍 **Real-time Location Services:** Quickly find the nearest pharmacies based on your current location.
*   🔎 **Advanced Filtering:** Filter pharmacies by services offered, opening hours, or specific medication availability.
*   📱 **Cross-Platform Access:** Seamlessly access the application on both web browsers and mobile devices.
*   🚀 **Robust Backend:** A dedicated backend system ensures reliable data management and API services for all clients.
*   🗺️ **Interactive Maps:** Visualize pharmacy locations and get directions with integrated mapping solutions.


## 🛠️ Installation Guide

To get a local copy up and running, follow these simple steps. The project is divided into three main components: `Backend-Pharmacy`, `Web-Pharmacy`, and `Mobile-Pharmacy`.

### Prerequisites

Ensure you have the following installed:

*   Node.js (LTS version recommended)
*   npm or Yarn package manager
*   Git

### 1. Clone the Repository

```bash
git clone https://github.com/pharmacy-location/pharmacy-location.git
cd pharmacy-location
```

### 2. Backend Setup (`Backend-Pharmacy`)

This directory contains the server-side logic and API.

```bash
cd Backend-Pharmacy
npm install # or yarn install
```

**Environment Configuration:**
Create a `.env` file in the `Backend-Pharmacy` directory and add necessary environment variables (e.g., database connection strings, API keys).

```
# Example .env content
DB_HOST=localhost
DB_PORT=5432
DB_USER=pharmacyuser
DB_PASSWORD=your_password
DB_NAME=pharmacy_db
PORT=3000
```

**Run the Backend:**

```bash
npm start # or yarn start
```

The backend server will typically run on `http://localhost:3000` (or your configured port).

### 3. Web Application Setup (`Web-Pharmacy`)

This directory contains the web-based user interface.

```bash
cd ../Web-Pharmacy
npm install # or yarn install
```

**Run the Web Application:**

```bash
npm start # or yarn start
```

The web application will usually open in your browser at `http://localhost:3001` (or a similar port).

### 4. Mobile Application Setup (`Mobile-Pharmacy`)

This directory contains the mobile application (e.g., React Native).

```bash
cd ../Mobile-Pharmacy
npm install # or yarn install
```

**Run the Mobile Application:**

For Android:

```bash
npm run android # or yarn android
```

For iOS (requires macOS and Xcode):

```bash
npm run ios # or yarn ios
```

Ensure you have an emulator running or a physical device connected.


## 🚀 Demo



https://github.com/user-attachments/assets/cf655ec6-d1b8-4416-a230-eeb4b4ded441



## 🛣️ Project Roadmap

We are continuously working to improve the Pharmacy Location Finder. Here's a glimpse of what's planned:

*   **Version 1.1 - Enhanced Search & Filtering:**
    *   Implement keyword search for specific medications or brands.
    *   Add user reviews and ratings for pharmacies.
    *   "Favorite" pharmacies feature for quick access.
*   **Version 1.2 - User Accounts & Notifications:**
    *   User registration and login for personalized experiences.
    *   Push notifications for prescription refill reminders or pharmacy updates.
    *   Integration with third-party health services.
*   **Future Improvements:**
    *   Performance optimizations for faster loading and smoother interactions.
    *   UI/UX redesigns based on user feedback.
    *   Expansion to include other health-related services.


## 🤝 Contribution Guidelines

We welcome contributions to the Pharmacy Location Finder project! Please follow these guidelines to ensure a smooth collaboration.


### Pull Request Process

1.  Fork the repository and create your feature branch.
2.  Commit your changes with clear, concise commit messages.
3.  Ensure your code passes all tests and linting checks.
4.  Open a Pull Request (PR) to the `main` branch.
5.  Provide a clear description of your changes and link any relevant issues.
6.  Your PR will be reviewed by a maintainer. Address any feedback promptly.

### Testing Requirements

*   All new features and bug fixes should be accompanied by appropriate unit and/or integration tests.
*   Ensure existing tests pass before submitting a PR.


## 📝 License Information

This project is currently released without a specific license.  
All rights are reserved by the copyright holders. You may not use, copy, distribute, or modify this software without explicit permission from the authors.

© 2023 - Present **Salma191, ZinebTaghia, Safiyadaoudi01**. All rights reserved.

