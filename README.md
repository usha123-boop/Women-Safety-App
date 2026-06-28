# Women Safety Application

## 🛡️ Feel Safe Everywhere

> A user-friendly Android application designed to enhance personal safety through real-time emergency alert features and location sharing.

---

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Screenshots](#screenshots)
- [Prerequisites](#prerequisites)
- [Installation & Setup](#installation--setup)
- [How to Use](#how-to-use)
- [Technology Stack](#technology-stack)
- [Project Structure](#project-structure)
- [Demo & Resources](#demo--resources)
- [Author Details](#author-details)
- [License](#license)

---

## Overview

The **Women Safety Application** is a lightweight yet powerful Android application built with Android Studio to provide users with a quick and efficient way to send emergency alerts to trusted contacts. The app is designed with simplicity in mind, making it easy to implement and understand.

In critical situations, users can simply shake their device to trigger an SOS alert that sends their last known location to pre-registered emergency contacts, ensuring help reaches them quickly.

### Key Characteristics
- ✅ User-friendly interface
- ✅ Simple to implement and understand
- ✅ Real-time emergency notifications
- ✅ Automated location sharing
- ✅ Cloud-based data management

---

## Features

### 🚨 Core Emergency Features
- **Shake Detector** - Detects device shake gestures to trigger emergency mode
- **SOS Alert System** - Sends emergency alerts to registered mobile numbers instantly
- **Location Sharing** - Automatically sends the last known GPS location to emergency contacts
- **Registered Contacts** - Easy management of trusted emergency contact numbers

### 📱 User Experience
- Intuitive and clean UI design
- Quick access to emergency features
- Real-time notification delivery
- Secure Firebase integration for data protection

### 🔐 Security & Reliability
- Firebase Authentication for secure access
- Real-time Database for instant notifications
- Encrypted data transmission
- Contact information protection

---

## Screenshots

[Add app screenshots here]

```
┌─────────────────────────────────┐
│  Women Safety Application       │
│                                 │
│  [Emergency Contact List]       │
│  [Settings]                     │
│  [Help & Support]               │
└─────────────────────────────────┘
```

Demo Screenshots: [Link to app demo on blogger](https://diplomagraduate.blogspot.com/2021/08/women-safety-applicatino-in-android.html)

---

## Prerequisites

### System Requirements
- **Android Studio** - Latest stable version recommended
- **Android SDK** - API Level 26 (Android Oreo) or higher
- **Gradle** - Required for build automation
- **Java Development Kit (JDK)** - JDK 8 or higher

### Knowledge Requirements
- Basic Android development knowledge
- Understanding of Firebase Authentication
- Understanding of Firebase Realtime Database
- Familiarity with Android manifest and app permissions

### Firebase Setup
- Firebase project created in Firebase Console
- Firebase Authentication enabled
- Realtime Database configured
- Necessary Firebase dependencies added to project

---

## Installation & Setup

### Step 1: Clone or Download Repository
```bash
# Clone the repository
git clone https://github.com/vinayak09/women-safety-android.git

# OR download and extract the ZIP file
# Extract: women-safety-android-main.zip
```

### Step 2: Open in Android Studio
1. Launch Android Studio
2. Select **File** → **Open**
3. Navigate to the extracted project folder
4. Select the `women-safety-android-main` folder and click **OK**

### Step 3: Wait for Gradle Sync
- Android Studio will automatically download required Gradle files
- Allow the build system to complete the sync process
- This may take a few minutes on first load

### Step 4: Configure Firebase (Important!)
1. Go to [Firebase Console](https://console.firebase.google.com/)
2. Create a new project or use an existing one
3. Add Android app to your Firebase project
4. Download `google-services.json`
5. Place the file in `app/` directory
6. Enable **Authentication** and **Realtime Database** in Firebase Console

### Step 5: Build and Run
1. Click the **Run** button (or press `Shift + F10`)
2. Select your Android device or emulator
3. Wait for the app to compile and install
4. Launch the app on your device

---

## How to Use

### Initial Setup
1. **Launch the app** on your Android device
2. **Register/Login** using Firebase Authentication
3. **Add Emergency Contacts** - Enter phone numbers of trusted people

### Emergency Alert
1. **Detect Shake** - When in danger, vigorously shake your phone
2. **Automatic SOS** - App triggers emergency mode
3. **Location Sharing** - Last known location is captured
4. **Alert Sent** - SOS alert with location is sent to all registered contacts
5. **Confirmation** - App displays confirmation that alert was sent

### Settings
- Update your contact information
- Add/Edit emergency contact numbers
- Configure app preferences
- Enable/disable notifications

---

## Technology Stack

### Frontend
- **Language**: Java / Kotlin
- **Framework**: Android SDK
- **IDE**: Android Studio
- **UI**: XML Layouts, Material Design

### Backend & Database
- **Backend Service**: Firebase
- **Authentication**: Firebase Authentication
- **Database**: Firebase Realtime Database
- **Cloud Messaging**: Firebase Cloud Messaging (FCM)

### Libraries & Dependencies
- Firebase SDK
- Google Play Services (for Location Services)
- Android Support Libraries
- Gson (for JSON serialization)

### Hardware Features
- GPS/Location Services
- Accelerometer (for shake detection)
- Mobile Network/WiFi connectivity

---

## Project Structure

```
women-safety-android-main/
├── .github/
│   └── FUNDING.yml
├── .idea/
│   ├── compiler.xml
│   ├── gradle.xml
│   ├── jarRepositories.xml
│   └── misc.xml
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/vinayak09/wsafety/
│   │   │   │   └── [Activity and Service classes]
│   │   │   ├── res/
│   │   │   │   ├── layout/
│   │   │   │   ├── drawable/
│   │   │   │   └── values/
│   │   │   └── AndroidManifest.xml
│   │   └── androidTest/
│   ├── build.gradle
│   └── proguard-rules.pro
├── build.gradle
├── settings.gradle
├── README.md
└── .gitignore
```

---

## Demo & Resources

### Video Demonstration
- **Full Project Demo**: [YouTube Video](https://youtu.be/E0WLnlkPDJY)
- Complete walkthrough of features and functionality
- Live demonstration of emergency alert system

### Download Demo App
- **Live APK Download**: [Available on Blog](https://diplomagraduate.blogspot.com/2021/08/women-safety-applicatino-in-android.html)
- Try the app directly on your device
- No build setup required

### Additional Resources
- [Android Developer Documentation](https://developer.android.com/)
- [Firebase Documentation](https://firebase.google.com/docs)
- [Android Studio Documentation](https://developer.android.com/studio)

---

## Author Details

**Developer**: Vinayak  
**GitHub**: [vinayak09](https://github.com/vinayak09)  
**Telegram**: [@vinayak_09](https://t.me/vinayak_09)  
**Package Name**: `com.vinayak09.wsafety`

### About the Developer
This project was created with a focus on making personal safety accessible and easy to use for everyone. The application demonstrates practical implementation of Android development combined with cloud services.

---

## License

This project is provided as **Free Software**.

Feel free to use, modify, and distribute this project for personal and educational purposes.

---

## Contributing

Contributions are welcome! If you have suggestions or improvements:
1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

---

## Support & Issues

If you encounter any issues or have questions:
- Check the [YouTube demo](https://youtu.be/E0WLnlkPDJY) for guidance
- Review Firebase documentation for setup issues
- Open an issue on GitHub for bug reports

---

## Acknowledgments

- Android Studio and Google for development tools
- Firebase for backend services
- Google Play Services for location and device features
- All users and contributors who have supported this project

---

**Last Updated**: June 2026  
**Minimum Android Version**: Android 8.0 (Oreo) - API Level 26  
**Status**: Active ✅

---

**Stay Safe! 🛡️**
