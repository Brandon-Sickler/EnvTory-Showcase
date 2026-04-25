# EnvTory: Hardwood Lumber Grading & ERP Optimizer
**Bridging the gap between the sawmill floor and the front office.**

> **Note:** The source code for EnvTory is maintained in a private repository to protect proprietary business logic and enterprise security configurations. This repository serves as a technical showcase of the application's architecture, UI/UX design, and integrated manufacturing workflows.

EnvTory is an enterprise-grade, offline-first mobile application designed to optimize hardwood lumber grading, preserve manufacturing yield, and digitize the timber supply chain. 

Architected by a 15-year industry veteran and Pennsylvania State University IST student, EnvTory translates complex NHLA rules into a high-performance digital tool that protects mill profitability in real-time.

### 🎥 System Overview & Live Demo
<video src="PASTE_YOUR_VIDEO_LINK_HERE" width="100%" controls>
  Your browser does not support the video tag.
</video>

---

## 💡 System Modules & Core Features

### 1. Operations Management & Log Intake
The foundational layer of the supply chain, handling everything from initial intake to global mill configuration.

| Mission Control | Log Intake | Quality Audit |
| :---: | :---: | :---: |
| <img src="./assets/HomeScreen.jpg" width="250" /> | <img src="./assets/Log_Intake_Scale_Mode.jpg" width="250" /> | <img src="./assets/Log_Intake_Load_Quality_Audit.jpg" width="250" /> |
| **Central Hub:** Modular dashboard for facility-wide scaling. | **Intake Scaling:** Supports Doyle and International 1/4 rules. | **Quality Audit:** Digital defect tracking (Stain, Heartwood, Wane). |

### 2. Lumber Grading & Yield Optimization
The core engine designed to protect mill margins. This module mirrors physical workflows while providing real-time financial guardrails.

| Grading Interface | Pricing Engine | Mill Configuration |
| :---: | :---: | :---: |
| <img src="./assets/Lumber_Grading_Highlight.jpg" width="250" /> | <img src="./assets/Mill_Management_Prices_Tab.jpg" width="250" /> | <img src="./assets/Mill_Management_Config_Tab.jpg" width="250" /> |
| **Yield Optimizer:** Real-time "Max Drop" calculations to protect ROI. | **Market Pricing:** Granular price management by species and grade. | **Global Config:** Dynamic toggles for species and thickness tracking. |

### 3. Inventory Control & Production Analytics
Connecting real-time shop floor data to administrative oversight, ensuring 100% traceability.

| Yard Inventory | Packet Tally | Production Manager |
| :---: | :---: | :---: |
| <img src="./assets/Packet_Builder_Yard_Tab.jpg" width="250" /> | <img src="./assets/Packet_Builder_Tally_Tab.jpg" width="250" /> | <img src="./assets/Production_Analytics_Screen.jpg" width="250" /> |
| **Traceability:** Live tracking of staged vs. active production runs. | **Auto-Tally:** Instant board-foot and efficiency calculations. | **Executive Oversight:** Real-time monitoring of facility throughput. |

---

## ⚙️ Technical Stack & Architecture
EnvTory is architected for the "No-Service" environments of a sawmill using a professional-grade, offline-first sync engine.

* **Frontend:** React Native (Expo) & TypeScript for a native, type-safe mobile experience.
* **Local Database:** OP-SQLite for instantaneous, edge-based grading calculations.
* **Sync Engine:** PowerSync to ensure zero data loss and seamless background cloud synchronization.
* **Backend:** Supabase (PostgreSQL) for secure authentication and relational data storage.
* **DevOps:** EAS (Expo Application Services) for automated native builds and OTA (Over-the-Air) updates.

---

## 📬 Contact & Collaboration
**Brandon Sickler** *B.S. Information Sciences and Technology | Pennsylvania State University* * **LinkedIn:** [linkedin.com/in/brandonsickler](https://www.linkedin.com/in/brandonsickler)
* **Email:** BrandonMSickler@gmail.com

---
<div align="center">
  <sub>Built for the Lumber Industry. Powered by Penn State IST. 🌲</sub>
</div>
