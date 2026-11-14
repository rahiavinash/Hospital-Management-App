# 🏥 Hospital Management System (MediCare)

A robust, production-ready healthcare management platform engineered to streamline patient care, appointment scheduling, electronic medical records (EMR), and role-based administration for modern clinics and hospitals.

---

## 📱 Key Features

*   **Role-Based Access Control (RBAC):** Secure authentication workflows tailored for Patients, Doctors, and Administrators with distinct dashboard interfaces.
*   **Appointment Booking & Management:** Real-time scheduling, rescheduling, and status tracking for consultations.
*   **Electronic Health Records (EHR):** Secure storage and retrieval of patient medical history, prescriptions, lab reports, and diagnostic notes.
*   **Real-Time Notifications:** Instant alerts for appointment confirmations, medication reminders, and emergency notifications using Firebase Cloud Messaging (FCM).
*   **Secure Authentication & Data Sync:** Token-based authentication paired with cloud-synced offline capabilities to ensure uninterrupted clinical workflows.

---

## 🛠 Tech Stack & Architecture

*   **Frontend / Mobile:** Flutter / Native Android (Kotlin) / iOS (Swift)
*   **Architecture:** MVVM (Model-View-ViewModel) for clean separation of concerns, maintainability, and reactive UI state management.
*   **Backend & Database:** Firebase Authentication, Cloud Firestore / RESTful API integration.
*   **State Management:** Provider / BLoC / ViewModel
*   **Additional Tools:** Retrofit, Google Maps SDK (for facility locator), secure token storage.

---

## 📂 Project Structure

```text
lib/
│
├── data/                 # Models, repositories, and remote/local data sources
├── domain/               # Use cases and business logic abstractions
├── presentation/         # UI layers (screens, widgets, viewmodels)
│   ├── admin/            # Admin dashboard and management portal
│   ├── doctor/           # Doctor consultation and prescription views
│   └── patient/          # Patient booking and medical record views
│
├── core/                 # Constants, themes, network clients, and utilities
└── main.dart             # Application entry point
