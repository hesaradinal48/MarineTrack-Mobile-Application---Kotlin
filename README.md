# 🚤 Marinetrack – Mobile Application

**Marinetrack** is a mobile application developed as part of the **Marinetrack Harbour Management System**.

The application is designed for **boat owners and fishermen** to access important harbour-related services directly from their mobile devices. It provides a convenient way to manage boats, fishermen information, departure details, and other related activities.

The application is connected to the system's cloud-based backend, allowing information to be synchronized with the harbour management platform.

## 📱 Features

### 🔐 Authentication

* User registration
* Secure login
* User authentication
* User session management

### 🚤 Boat Management

* Register boats
* View registered boats
* View boat details
* Manage boat information

### 👨‍✈️ Fishermen Management

* Register fishermen
* View fishermen information
* Manage fisherman details
* Access fisherman-related information

### ⚓ Departure Management

* Register boat departures
* View departure details
* Track departure information
* Access departure records

### 🌦️ Weather Information

* View current weather information
* Access weather data through an API
* Display weather information within the mobile application

### 📊 Dashboard

The mobile dashboard provides quick access to important features such as:

* Registered boats
* Boat details
* Fishermen registration
* Departure information
* Weather information

## 🛠️ Technologies Used

| Technology                  | Purpose                         |
| --------------------------- | ------------------------------- |
| **Kotlin**                  | Android application development |
| **Android Studio**          | Development environment         |
| **Firebase Authentication** | User authentication             |
| **Firebase Firestore**      | Cloud database                  |
| **Firebase Storage**        | File/document storage           |
| **Weather API**             | Weather information             |
| **Git**                     | Version control                 |

## 🏗️ Application Architecture

```text
┌──────────────────────────────┐
│       Marinetrack App        │
│                              │
│          Kotlin              │
│      Android Application     │
└───────────────┬──────────────┘
                │
                ▼
┌──────────────────────────────┐
│          Firebase            │
│                              │
│  Authentication              │
│  Firestore Database          │
│  Cloud Storage               │
└───────────────┬──────────────┘
                │
                ▼
┌──────────────────────────────┐
│    Harbour Management        │
│          System              │
│                              │
│  Boat / Fishermen /          │
│  Departure Information       │
└──────────────────────────────┘
```

## 📲 Main Screens

The application includes the following major screens:

1. **Home Screen**
2. **Registration Screen**
3. **Login Screen**
4. **Dashboard**
5. **Weather Data**
6. **Boat Registration**
7. **Registered Boats**
8. **Boat Details**
9. **Fishermen Registration**
10. **Fishermen Details**
11. **Departure Details**

## ☁️ Firebase Integration

The application uses Firebase as the cloud backend.

### Firebase Authentication

Used for:

* User registration
* Login
* Authentication
* Secure user access

### Firebase Firestore

Used to store and retrieve:

* User information
* Boat information
* Fishermen information
* Departure information
* Other application data

### Firebase Storage

Used for storing application-related files and documents where required.

## 🌦️ Weather API

The application integrates a weather API to provide users with weather-related information.

Weather data can help users access current conditions before carrying out marine activities.

## 🔄 Data Synchronization

The mobile application communicates with the cloud backend to keep application data synchronized.

```text
Mobile Application
        │
        ▼
     Firebase
        │
        ▼
 Cloud Database
        │
        ▼
Harbour Management System
```

Changes made through the supported system interfaces can be reflected through the shared backend.

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/marinetrack-mobile.git
```

### 2. Open in Android Studio

Open the cloned project using **Android Studio**.

### 3. Configure Firebase

Add the Firebase configuration file:

```text
google-services.json
```

to the appropriate Android application directory.

> Do not upload your private Firebase configuration or API keys if they contain credentials or other sensitive information.

### 4. Sync the Project

Allow Android Studio to download and synchronize the required Gradle dependencies.

### 5. Run the Application

Connect an Android device or start an Android Emulator and run the application from Android Studio.

## 📁 Project Structure

A typical project structure is organized around:

```text
Marinetrack/
│
├── app/
│   ├── src/
│   │   └── main/
│   │       ├── java/
│   │       ├── res/
│   │       └── AndroidManifest.xml
│   │
│   └── build.gradle
│
├── gradle/
├── build.gradle
└── settings.gradle
```

## 🔒 Security

The application uses authentication and cloud-based access controls to help protect user information.

Security considerations include:

* Firebase Authentication
* Authenticated user access
* Firebase security rules
* Restricted database access
* Secure API configuration

## 🎯 Purpose

The main purpose of the Marinetrack mobile application is to provide boat owners and fishermen with a convenient mobile interface for accessing harbour-related services.

Instead of depending entirely on physical visits or manual processes, users can access important information and perform supported activities directly through their mobile devices.

## 🚀 Future Improvements

Possible future improvements include:

* Push notifications
* GPS-based boat tracking
* Digital permits
* Online berth reservations
* Digital document management
* Offline data support
* Emergency/SOS functionality
* Real-time boat location
* Improved weather and marine-condition information
* Online communication with harbour officers

## 📄 License

This project is developed for educational and demonstration purposes.
