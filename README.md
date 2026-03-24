# EnvTory-Showcase
EnvTory Showcase: An enterprise-grade mobile app translating complex manufacturing workflows and strict NHLA grading rules into an intuitive digital tool that protects mill profitability.
# EnvTory: Hardwood Lumber Grading & ERP Optimizer

**EnvTory** is an enterprise-grade mobile application designed to optimize hardwood lumber grading, preserve manufacturing yield, and connect the shop floor to the front office. 

Architected by a 15-year industry veteran, EnvTory translates complex manufacturing workflows and strict NHLA grading rules into an intuitive digital tool that protects mill profitability.

### 🎥 Video Demonstration

https://github.com/user-attachments/assets/c098cf7a-ef8f-48c7-ac43-e811fa2cd97d

---

## 🛑 The Manufacturing Challenge
In the hardwood lumber industry, mills lose thousands of dollars daily due to inefficient grading decisions and delayed inventory data. 
1. **Yield Loss:** Standard grading software often pushes for the "Highest Value" grade, instructing operators to cut off too much good wood, resulting in net financial loss.
2. **Delayed Visibility:** Management typically discovers production bottlenecks or yield drops days after the fact.
3. **Workflow Disruption:** Digital tools that don't mimic physical workflows slow down operators on a fast-paced line, leading to poor software adoption.

---

## 💡 System Modules & Core Features

### 1. Mission Control (The Enterprise Hub)
EnvTory functions as a full suite, breaking operations down into dedicated, modular workflows. This ensures facilities can scale the software to match their specific footprint, from Log Yard Intake to Pack Building and Supply Chain logistics.

<div align="center">
  ![Home Screen](https://github.com/user-attachments/assets/da9b4ba3-3f24-4aff-97f2-42047d614b99)

</div>

### 2. "The Judge": Smart Tape & Optimizer Engine
This is the core financial safety net of the application. To ensure high user adoption, the UI was designed to mirror the physical Lufkin grading stick operators already trust. 

Instead of just recording data, **The Optimizer** actively calculates real-time profitability thresholds based on the exact width measured on the Smart Tape. It tells the inspector the **"Max Cut"** and **"Max Drop"** allowed before an upgrade loses money. This empowers the operator to make the final physical cut while guaranteeing financial safety.

<div align="center">
  ![Button Optimizer](https://github.com/user-attachments/assets/401eee5d-4ca4-4159-a988-4c13d60f63fb)

</div>

### 3. "The Landing": Log Yard Intake & Scaling
Lumber optimization starts before the wood hits the saw. The Landing module allows for rapid log scaling (e.g., Doyle scale), vendor ticket tracking, and granular defect deductions (Rot, Sweep, Crook) right in the yard.

<div align="center">
  ![Landing Screen Scale Mode](https://github.com/user-attachments/assets/35c921ce-63dc-40e7-8be9-c04b5deaa8ca)

</div>

### 4. Real-Time Operations & Inventory
Connecting the shop floor to the top floor. As operators tally wood, plant managers can instantly monitor production flow, track active kiln charges, view live grade percentages, and make proactive operational decisions in real time.

<div align="center">
  ![Architect Yard Inventory](https://github.com/user-attachments/assets/5d3a9da7-4b98-4f91-b0ae-db6d60ccc4c0)

</div>

### 5. "The Stockpile": Vendor Auditing & SQLite Edge Data
A built-in supply chain accountability module powered by a local OP-SQLite database. EnvTory tracks the expected grade versus the actual graded yield per vendor. This provides purchasing departments with actionable business intelligence to negotiate contracts and manage supplier performance, all while remaining fully functional offline.

<div align="center">
  ![Inventory](https://github.com/user-attachments/assets/dc86fa94-3818-4743-8026-7d17424e449c)

</div>

---

## 🧠 Product Management & AI Architecture

**The approach:** I approached this project acting as the Product Manager and Domain Expert. I defined the problem statements, mapped the business logic, gathered UI/UX requirements, and established success metrics. 

Leveraging AI as my engineering team, I strictly managed the logic output, iterated on the application state, and dialed in the UI physics to rapidly prototype and deliver a complex, offline-resilient enterprise application independently. Building EnvTory is an exercise in taking a massive real-world supply chain problem and translating it into a digital product that immediately impacts the bottom line.
