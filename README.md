<div align="center">

# 🏥 Healthcare Buddy

### Your AI-Powered Personal Health Records Manager

**The ONLY health app that scans prescriptions with AI, detects drug interactions, and keeps your data 100% private**

[![Android](https://img.shields.io/badge/Platform-Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://android.com)
[![Kotlin](https://img.shields.io/badge/Kotlin-100%25-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)](https://kotlinlang.org)
[![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-Modern%20UI-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white)](https://developer.android.com/jetpack/compose)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=for-the-badge)](http://makeapullrequest.com)

[✨ Features](#-ai--smart-features) • [📸 Screenshots](#-screenshots) • [🗺️ Roadmap](#-roadmap)

---

### 🎯 Why Healthcare Buddy?

| 🤖 **AI-Powered** | 🔒 **Private & Secure** | 📴 **Offline-First** | 🎨 **Beautiful UI** |
|:---:|:---:|:---:|:---:|
| ML Kit OCR scans prescriptions instantly | 256-bit AES encryption | Works 100% offline | Modern Material 3 design |
| Smart drug interaction detection | Biometric authentication | No cloud, no tracking | Doctor Mode theme |
| Personalized preventive care reminders | Your data never leaves your device | Zero internet required | Intuitive UX |

</div>
---

## 📱 Screenshots

<div align="center">

### 🤖 AI Features in Action

| 📸 Prescription Scanner | ⚠️ Drug Interaction Alert | 🎯 Preventive Care |
|:---:|:---:|:---:|
| *Snap photo → AI extracts data* | *Real-time safety warnings* | *Personalized reminders* |
| ![Scanner](../screenshots/prescription_scanner.png) | ![Interactions](../screenshots/drug_interactions.png) | ![Preventive](../screenshots/preventive_care.png) |

### 📊 Core Functionality

| 🏠 Dashboard | 💊 Medications | 🚨 Allergies |
|:---:|:---:|:---:|
| *Unified health overview* | *Complete med history* | *Severity-based sorting* |
| ![Dashboard](../screenshots/dashboard.png) | ![Medications](../screenshots/medications.png) | ![Allergies](../screenshots/allergies.png) |

| 💉 Immunizations | 🩺 Blood Pressure | 👤 Profile |
|:---:|:---:|:---:|
| *Vaccine records & lot numbers* | *OCR scanning + charts* | *Personal health info* |
| ![Immunizations](../screenshots/immunizations.png) | ![BP](../screenshots/blood_pressure.png) | ![Profile](../screenshots/profile.png) |

</div>

---
## 🚀 NEW: AI-Powered Features

<div align="center">

### 📸 **Prescription Scanner**
*Powered by Google ML Kit Text Recognition*

**Just snap a photo of your prescription bottle — AI does the rest!**

</div>

```
📷 Take Photo → 🤖 AI Extracts Text → ✅ Auto-fills Medication Details
```

**What it extracts:**
- 💊 **Medication Name** - Detects brand and generic names
- 📏 **Dosage** - Recognizes mg, ml, units, tablets
- 👨‍⚕️ **Prescriber** - Finds doctor names and credentials
- 🎯 **90% Accuracy** - Smart parsing with confidence scoring

<div align="center">

### ⚠️ **Drug Interaction Detector**
*Real-time safety checking with hundreds of medications*

**Prevent dangerous medication combinations before it's too late**

</div>

```kotlin
🆕 Adding new medication...
→ 🔍 Checking drug interactions...
→ ⚠️  ALERT: Severe interaction detected!
```

**Protection levels:**
- 🔴 **SEVERE** - Life-threatening interactions (immediate warning)
- 🟠 **MODERATE** - Significant effects (caution advised)
- 🟡 **MINOR** - Monitor for side effects

Real-world example:
```
Adding: Warfarin (blood thinner)
⚠️ SEVERE: Do NOT combine with Aspirin
⚠️ Risk: Increased bleeding, hemorrhage
```

<div align="center">

### 🎯 **Intelligent Preventive Care**
*Personalized health reminders based on age, gender & history*

**Never miss important health screenings again**

</div>

**Smart recommendations:**
- 🩺 **Cancer Screenings** - Mammogram, Colonoscopy, Prostate (age-based)
- 💉 **Vaccinations** - Flu, COVID, Shingles, Pneumonia (seasonal alerts)
- ❤️ **Cardiovascular** - Blood pressure, cholesterol, diabetes screening
- 📊 **Custom Scheduling** - Tracks last visit, calculates next due date

---

## ✨ Core Features

### 💊 Complete Medication Management
- ✅ **Prescription Scanner** - AI-powered OCR (NEW!)
- ✅ **Drug Interactions** - Real-time safety alerts (NEW!)
- ✅ **Medication Tracker** - Dosage, frequency, start dates
- ✅ **Smart Sorting** - By name or date, ascending/descending

### 🚨 Allergy Management (NEW!)
- ✅ **Comprehensive Tracking** - Food, medication, environmental allergies
- ✅ **Severity Indicators** - Visual color-coding (Red/Orange/Green)
- ✅ **Reaction History** - Document symptoms and triggers
- ✅ **Smart Sorting** - Severe allergies always shown first

### 🩺 Self-Monitoring
- ✅ **Blood Pressure Tracking** - Manual entry or OCR scan
- ✅ **Trend Visualization** - Charts and graphs
- ✅ **Historical Data** - Complete timeline

### 💉 Immunization Vault
- ✅ **Vaccination Records** - COVID, Flu, childhood vaccines
- ✅ **Lot Numbers** - FDA tracking compliance
- ✅ **Next Dose Alerts** - Booster shot reminders
- ✅ **Proof of Vaccination** - Always accessible offline

### 🏥 Health Visits & Conditions
- ✅ **Doctor Visit Logs** - Date, provider, diagnosis, notes
- ✅ **Health Screenings** - Mammograms, colonoscopies, etc.
- ✅ **Upcoming Appointments** - Never miss a checkup
- ✅ **Complete History** - Lifetime health journey

### 🔐 Bank-Level Security
- ✅ **SQLCipher Encryption** - 256-bit AES (same as banking apps)
- ✅ **Encrypted Backups** - Local .hbb backup files with AES-256
- ✅ **Zero Cloud Storage** - Your data stays on YOUR device
- ✅ **No Tracking** - Zero analytics, zero telemetry

### 📄 Export & Backup
- ✅ **PDF Health Reports** - Password Protected comprehensive health summary with all records
- ✅ **Customizable Export** - Select which sections to include in PDF (NEW!)
- ✅ **Blood Pressure History** - Last 20 readings included in PDF
- ✅ **Glucose Log** - Weekly glucose tracking in PDF exports
- ✅ **Encrypted Backups** - Save to Downloads/HealthcareBuddy folder
- ✅ **One-Click Restore** - Easy data recovery from backup files

---

## 🛠️ Technology Stack

### 🤖 AI & Machine Learning
- **Google ML Kit** - Text Recognition (OCR)
- **Custom Parsers** - Medication name/dosage extraction
- **Drug Database** - Hundreds of medication interaction rules
- **Smart Algorithms** - Preventive care recommendation engine

### 💾 Data & Storage
- **Room Database** - Local SQLite with type safety
- **SQLCipher** - Military-grade encryption (256-bit AES)
- **Repository Pattern** - Single source of truth
- **Offline-First** - Works without internet

---

## 🗺️ Roadmap (Partial)

### ✅ Completed (v1.0)
- [x] Core health record management
- [x] AI prescription scanner (ML Kit)
- [x] Drug interaction detection
- [x] Preventive care reminders (age/gender based)
- [x] Allergy management with severity tracking
- [x] Blood pressure monitoring with OCR
- [x] SQLCipher encryption
- [x] Offline-first architecture

### ✅ Completed (v1.2 - January 2026)
- [x] Customizable, password-protected PDF export with section selection
- [x] Developer tools for testing (43+ sample records)
- [x] Fixed profile edit persistence bug
- [x] Enhanced settings navigation
- [x] Select All/Clear All toggles for export options
- [x] Glucose log tracking in PDF exports
---

## 🌟 Why Healthcare Buddy is Special

### 🆚 Comparison with Other Health Apps

| Feature                            | Healthcare Buddy | MyChart | Apple Health | Google Fit |
|------------------------------------|:----------------:|:-------:|:------------:|:----------:|
| 🤖 AI Prescription Scanner         |        ✅         | ❌ | ❌ | ❌ |
| ⚠️ Drug Interaction Alerts         |        ✅         | ❌ | ❌ | ❌ |
| 🎯 Preventive Care AI              |        ✅         | Limited | ❌ | ❌ |
| 📄 PDF Export (Password Protected) |        ✅         | ✅ | ⚠️ | ❌ |
| 💾 Encrypted Backup                |        ✅         | Cloud | Cloud | Cloud |
| 🔒 Full Encryption                 |        ✅         | ✅ | ✅ | ⚠️ |
| 📴 100% Offline                    |        ✅         | ❌ | ⚠️ | ❌ |
| 🔍 Zero Tracking                   |        ✅         | ❌ | ⚠️ | ❌ |
| 💊 Medication Management           |        ✅         | ✅ | ⚠️ | ❌ |
| 🚨 Allergy Tracking                |        ✅         | ✅ | ⚠️ | ❌ |
| 🩺 Blood Pressure History          |        ✅         | ✅ | ✅ | Limited |

### 💡 What Makes Us Different

1. **🤖 AI-First Approach** - We leverage ML Kit for prescription scanning and smart health recommendations
2. **🔒 Privacy-First Design** - Your data NEVER leaves your device. No cloud, no tracking, period. Password-Protected.
3. **🎨 Beautiful & Intuitive** - Modern Material 3 UI that healthcare professionals love

---

<div align="center">

### 🏥 Built with ❤️ for Healthcare

**Privacy First • Security Always • Your Data, Your Control**

---

Designed and Coded by Shawn R. Harden - (Harden Business Consulting LLC.)

[⬆ Back to Top](#-health-buddy)

</div>

<!-- Last synced: 2026-01-12 v3 -->
