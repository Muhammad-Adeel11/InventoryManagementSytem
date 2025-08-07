# InventoryManagementSytem
A simple and effective Inventory Management System built using Flutter, Dart, and Firebase. This project features a clean UI, smooth navigation, and full CRUD operations to manage inventory data seamlessly.

# Features
🔹 Firebase Integration for real-time database support

🔹 CRUD Functionality: Add, read, update, and delete inventory items

🔹 User-Friendly UI built with Flutter widgets

🔹 Smooth Navigation between screens

🔹 State Management using basic Flutter state tools

# Tech Stack
Flutter (for cross-platform app development)
Dart (Flutter’s core language)
Firebase (for backend services like Firestore)

# Firebase Setup Commands
To integrate Firebase into your Flutter project, run the following commands:

# Install Firebase CLI (if not already)
npm install -g firebase-tools

# Initialize Firebase in your project directory
firebase login
firebase init

# Add Firebase to your Flutter project
flutter pub add firebase_core

flutter pub add cloud_firestore

flutter pub add firebase_auth

flutter pub add firebase_storage

flutter pub add firebase_analytics

Also, don’t forget to configure firebase_options.dart using the FlutterFire CLI:

flutterfire configure

# How to Run the Project

## Get all the dependencies
flutter pub get

## Run the app on your connected device or emulator
flutter run
