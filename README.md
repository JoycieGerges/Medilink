# 🏥 MediLink – Graduation Project

**MediLink** is a secure mobile & web system that digitizes prescription handling between doctors, pharmacies, and patients. The system aims to prevent drug misuse and streamline the healthcare process.

---

## 📱 Features

### 👨‍⚕️ Doctor App (Flutter Mobile)
- Secure login with fingerprint
- Add new prescriptions for patients
- View, edit, or delete previous prescriptions
- Upload Syndicate ID during registration
- Prescription data stored by patient national ID

### 💊 Pharmacist Web Dashboard (Flutter Web)
- View prescriptions after verifying patient name & ID
- OTP verification before dispensing medicine
- Track dispensing status (Pending / Processed)
- Monthly analytics dashboard

### 🤖 AI Integration
- Analyze patient survey responses
- Fuzzy logic scoring to detect possible misuse or dependency
- Disable medication dispensing if score is high (e.g., ≥ 8)

---

## 🛠 Tech Stack

- **Flutter** (Web & Mobile)
- **Firebase** (Auth, Firestore, Realtime DB, Storage)
- **Python** (AI backend for scoring + Flask)
- **HL7** Messaging (for medical system interoperability)
- **Apps Script** (Google Forms survey processing)

---

## 📊 Sample Dashboards

| Doctor App | Pharmacy Web | Admin AI |
|------------|---------------|----------|
| ![](screenshots/doctor.png) | ![](screenshots/pharmacy.png) | ![](screenshots/ai.png) |

> *(Add real screenshots in folder `screenshots/` if available)*

---

## 🚀 Getting Started

```bash
git clone https://github.com/JoycieGerges/Medilink.git
cd Medilink
