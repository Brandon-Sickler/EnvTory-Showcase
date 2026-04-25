# EnvTory: Hardwood Lumber Grading & ERP Optimizer
**Bridging the gap between the sawmill floor and the front office.**

EnvTory is an enterprise-grade, offline-first mobile application designed to optimize hardwood lumber grading, preserve manufacturing yield, and digitize the timber supply chain. 

Architected by a 15-year industry veteran and PSU Information Sciences student, EnvTory translates complex NHLA (National Hardwood Lumber Association) rules into a high-performance digital tool that protects mill profitability in real-time.

### 🎥 System Overview & Live Demo
[Insert Video Placeholder: Drag your compressed MP4 link here]

---

## 🛑 The Manufacturing Challenge
In the hardwood industry, mills lose thousands of dollars daily due to "Silent Yield Loss."
1. **Profitability Thresholds:** Traditional tally systems record what was cut, but they don't tell the operator if the cut was financially viable.
2. **Connectivity Gaps:** Sawmills are often located in remote areas with zero cell service, rendering cloud-only tools useless.
3. **Data Silos:** Log intake, lumber grading, and pack building often happen in three different "languages," making vendor auditing a manual nightmare.

---

## 💡 The EnvTory Solution: Core Modules

### 1. Mission Control (The Hub)
The central command center. EnvTory is built on a modular architecture, allowing facilities to scale from simple intake to full-scale production analytics.
[Image Placeholder: HomeScreen.jpg]

### 2. Log Intake (The Landing)
The entry point of the supply chain. This module handles vendor tickets, species identification, and granular defect audits (Stain, Heartwood, Wane).
* **Scale Mode:** Supports Doyle and International 1/4 rules.
* **Defect Logic:** Built-in deduction math for Rot, Sweep, and Crook.
[Image Placeholder: Log_Intake_Scale_Mode.jpg]
[Image Placeholder: Log_Intake_Load_Quality_Audit.jpg]

### 3. Lumber Grading (Featuring "The Judge" Optimizer)
The heart of the app. This module features a **Smart Tape** UI that mirrors the physical Lufkin sticks used by professionals.
* **Profitability Guardrails:** Real-time calculation of "Max Drop" and "Max Cut."
* **Active Feedback:** Tells the inspector exactly how much "good wood" can be removed before the grade-upgrade loses money.
[Image Placeholder: Lumber_Grading_Highlight.jpg]

### 4. Mill Management (The ERP Core)
The administrative layer where the "Rules of the Mill" are defined.
* **Pricing Engine:** Manage Market Prices ($ per MBF) by species and grade.
* **Logistics Relay:** Transition "Staged" yard loads into "Active" production runs.
* **Configurable Logic:** Toggle "Actual Thickness" tracking and species availability globally.
[Image Placeholder: Mill_Management_Prices_Tab.jpg]
[Image Placeholder: Mill_Management_Yard_Pull.jpg]

### 5. Yard Inventory & Packet Builder
The final step in the production chain. This module organizes graded output into physical packs, ensuring 100% traceability from a single board back to the original log vendor ticket.
[Image Placeholder: Mill_Management_Logs_Tab.jpg]

---

## ⚙️ The Technical Stack (Offline-First Architecture)

EnvTory is built to survive the "No-Service" environments of a sawmill using a professional-grade sync engine.

* **Frontend:** React Native (Expo) & TypeScript.
* **Local Database:** OP-SQLite – High-speed "Edge" storage for instantaneous grading math.
* **Sync Engine:** PowerSync – Keeps the local database in perfect sync with the cloud.
* **Backend:** Supabase (PostgreSQL) – Real-time authentication and cloud storage.
* **DevOps:** EAS (Expo Application Services) – CI/CD pipeline for native builds and OTA updates.

---

## 📬 Contact & Collaboration

**Brandon Sickler**
*B.S. Information Sciences and Technology | Pennsylvania State University*
* **LinkedIn:** [www.linkedin.com/in/brandonsickler](https://www.linkedin.com/in/brandonsickler)
* **Email:** BrandonMSickler@gmail.com

---
<div align="center">
  <sub>Built for the Lumber Industry. Powered by Penn State IST. 🌲</sub>
</div>
