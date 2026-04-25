# EnvTory: Hardwood Lumber Grading & ERP Optimizer
**Bridging the gap between the sawmill floor and the front office.**

> **Note:** The source code for EnvTory is maintained in a private repository. This showcase is intended to demonstrate the technical architecture and real-world utility of the platform.

### My Goal with EnvTory
I built EnvTory to solve a specific problem I've seen throughout my 15 years in the lumber industry: the "Data Gap." Most mills rely on paper tallies or slow, outdated software that doesn't help the operator make better decisions. 

As a student at Penn State World Campus, I wanted to combine my industry experience with modern tech like React Native and PowerSync to create an app that works as hard as the people using it—even when there’s no Wi-Fi in the yard.

### 🎥 System Overview & Live Demo
<video src="https://github.com/user-attachments/assets/c6709cfe-72cd-4f0b-b4a4-2cee9cf4abe3" width="100%" controls>
  Your browser does not support the video tag.
</video>

---

## 💡 How the App Works

### 1. Operations Management & Log Intake
This is where everything starts. Instead of writing log dimensions on a clipboard, the intake module lets you scale logs (Doyle or International 1/4) right on your phone. I also built in a "Quality Audit" section so you can track defects like heartwood ratio or stain, which directly affects what that load is worth.

| Mission Control | Log Intake | Quality Audit |
| :---: | :---: | :---: |
| <img src="./assets/HomeScreen.jpg" width="250" /> | <img src="./assets/Log_Intake_Scale_Mode.jpg" width="250" /> | <img src="./assets/Log_Intake_Load_Quality_Audit.jpg" width="250" /> |
| **Mission Control:** The main menu that keeps the different parts of the mill organized. | **Scaling:** A simple interface to record log diameter and length without manual math. | **Auditing:** Tracking the "hidden" details of a load that usually get lost on paper. |

### 2. Real-Time Grading Optimization
This is the heart of the project. In the grading booth, you have to decide in seconds whether to "clip" a board to get a better grade. I designed this UI to look like the physical Lufkin sticks we use. It calculates "Profitability Guardrails" that tell you the "Max Drop"—exactly how much wood you can cut off before you start losing money on the upgrade.

| Grading Interface | Pricing Engine | Mill Configuration |
| :---: | :---: | :---: |
| <img src="./assets/Lumber_Grading_Highlight.jpg" width="250" /> | <img src="./assets/Mill_Management_Prices_Tab.jpg" width="250" /> | <img src="./assets/Mill_Management_Config_Tab.jpg" width="250" /> |
| **The Optimizer:** Tells you if an upgrade is worth it based on current market prices. | **Pricing:** A simple spot to update what the mill is paying for different species and grades. | **Mill Settings:** Where you toggle species on/off depending on what's running that day. |

### 3. Inventory & Live Analytics
Sawmills are rarely in areas with good cell service. I used an "Offline-First" architecture so that as you tally boards or build packs, the data is saved locally on the device first. The second you get back to the office Wi-Fi, everything syncs to the cloud so management can see exactly what was produced that day.

| Yard Inventory | Packet Tally | Production Manager |
| :---: | :---: | :---: |
| <img src="./assets/Packet_Builder_Yard_Tab.jpg" width="250" /> | <img src="./assets/Packet_Builder_Tally_Tab.jpg" width="250" /> | <img src="./assets/Production_Analytics_Screen.jpg" width="250" /> |
| **Tracking:** Knowing exactly where a pack of lumber is in the yard. | **Auto-Tally:** No more manual board-foot math. The app handles it as you tap. | **Analytics:** A birds-eye view of the mill's performance for the day. |

---

## ⚙️ The Technical Stack
I chose these tools because they allow for a professional, fast, and reliable app that works without an internet connection:

* **React Native (Expo) & TypeScript:** Allows for a smooth mobile experience on both Android and iOS.
* **OP-SQLite & PowerSync:** This is the "secret sauce" that allows for 100% offline functionality. It stores data locally and syncs to the backend automatically.
* **Supabase:** Handles my database and user logins securely.
* **EAS:** Used for building the app and sending out "Over-the-Air" updates so I can fix bugs instantly.

---

## 📬 Contact & Collaboration
I'm currently pursuing my B.S. in Information Sciences and Technology at **Penn State** and looking to transition into a technical role where I can use my industry background to build better tools.

**Brandon Sickler** [LinkedIn](https://www.linkedin.com/in/brandonsickler) | BrandonMSickler@gmail.com

---
<div align="center">
  <sub>Built with experience from the yard. Powered by Penn State IST. 🌲</sub>
</div>
