# 🌍 Dunes of Arabia – Tourism Mobile App

## 📌 Overview

**Dunes of Arabia** is a full-featured tourism mobile application developed for Saudi Arabia.
The app provides users with tools for **destination discovery, trip planning, booking management, and interactive maps**, all integrated into a single platform.

This project was developed as part of a **Mobile Computing course**.

---

## 🚀 Features

### 🔐 User Authentication

* Firebase email/password login
* Secure session handling
* User profile management

### 🏝️ Destination Discovery

* Browse destinations in grid layout
* Search and filter by categories
* Detailed pages with travel insights

### 🗺️ Interactive Maps

* Google Maps integration
* Custom markers for tourist locations
* Real-time navigation and filtering

### 📅 Trip Planning

* Itinerary planner
* Packing checklist
* Budget estimation
* Travel guidance

### 📖 Booking System

* Book trips with user details
* Upload passport/ID
* Booking confirmation system

### 🎯 Activities & Tours

* Featured tours and activities
* Categorized listings
* Detailed descriptions

---

## 🛠️ Tech Stack

* **Frontend:** Flutter (Dart)
* **Backend:** Firebase

  * Authentication
  * Cloud Firestore
  * Storage
* **Maps:** Google Maps Flutter
* **Tools:** Android Studio / VS Code, Git

---

## 🏗️ Architecture

### UI Layer

* Home
* Destinations
* Maps
* Profile
* Booking
* Settings

### Backend Layer

* Firebase Authentication
* Firestore Database
* Cloud Storage
* Security Rules

---

## 📂 Database Structure

### Users Collection

* userId
* email
* displayName
* phone
* passport
* createdAt

Subcollections:

* bookings
* favorites
* itineraries

### Bookings Collection

* bookingId
* userId
* destination
* travelDate
* status
* totalPrice

---

## 🔄 State Management

* `setState` (UI state)
* `ValueNotifier` (global state)
* Firebase streams (real-time updates)

---

## 🔐 Security

* Firestore rules for user-based access
* Secure authentication system
* Data validation for forms

---

## ▶️ How to Run the Project

1. Clone the repository

```id="x7p9k1"
git clone https://github.com/your-username/dunes-of-arabia.git
```

2. Navigate to project folder

```id="l3k8d2"
cd dunes-of-arabia
```

3. Install dependencies

```id="n4z2q9"
flutter pub get
```

4. Run the app

```id="v8m1c5"
flutter run
```

---


## Screenshots
<img width="720" height="1600" alt="WhatsApp Image 22026-04-25 at 8 28 47 PM" src="https://github.com/user-attachments/assets/663e6e78-c772-4b4b-b3ca-3bf7ac8ce43d" />
<img width="720" height="1600" alt="WhatsApp Image 2026-04-25 at 8 28 46 PM" src="https://github.com/user-attachments/assets/04786fff-03ba-4ab2-b66a-e38734634a70" />
<img width="720" height="1600" alt="WhatsApp Image 2026-04-25 at 8 28 47 PM" src="https://github.com/user-attachments/assets/4bc7db63-6745-4416-b0bb-fb236e8d0d41" />
<img width="720" height="1600" alt="WhatsApp Image5 2026-04-25 at 8 28 49 PM" src="https://github.com/user-attachments/assets/7d0a1e94-bfc7-4704-9c3e-4ba27b3c65b4" />
<img width="720" height="1600" alt="WhatsApp Image1 2026-04-25 at 8 28 47 PM" src="https://github.com/user-attachments/assets/b060f0b9-e557-4e45-bc20-9bc19d674714" />
<img width="720" height="1600" alt="WhatsApp Image 42026-04-25 at 8 28 49 PM" src="https://github.com/user-attachments/assets/b62f809a-b78c-4fc8-b2d0-1bdbf2473504" />
<img width="720" height="1600" alt="WhatsApp Image 32026-04-25 at 8 28 48 PM" src="https://github.com/user-attachments/assets/04329d3b-2569-4b21-993d-ed44cf72160b" />
<img width="720" height="1600" alt="WhatsApp Image 82026-04-25 at 8 28 50 PM" src="https://github.com/user-attachments/assets/eb3ff51d-a768-43fa-9500-3bf92a8f1674" />
<img width="720" height="1600" alt="WhatsApp Image6 2026-04-25 at 8 28 50 PM" src="https://github.com/user-attachments/assets/91fc0e37-e93b-48ad-9b49-f69876742122" />
<img width="720" height="1600" alt="WhatsApp Image 92026-04-25 at 8 28 51 PM" src="https://github.com/user-attachments/assets/ec4702f2-5989-4139-9053-ba83abf9547b" />
<img width="720" height="1600" alt="WhatsApp Image7 2026-04-25 at 8 28 50 PM" src="https://github.com/user-attachments/assets/06e066e3-faf9-4a94-8cd7-b7d783af7d8a" />


### Technical Skills

* Flutter app development
* Firebase integration
* Google Maps API usage
* UI/UX design principles

### Professional Skills

* Team collaboration
* Project planning
* Documentation

---

## 📄 License

This project is for academic and learning purposes.
