# Tales of Wisdom — FYP Engineering & Milestone Dashboard

> **Final Year Project (FYP) 2026–2027**  
> **Project Name:** Tales of Wisdom  
> **Student Developers:** Aleena Memon & Rauf Shahid  
> **Project Supervisor:** Laviza Asif  
> **Target Mid-Term Deadline:** 1 December 2026  

---

## 📖 Overview

**Tales of Wisdom** is a 3D gamified educational platform that weaves core Computer Science pedagogy into an interactive narrative. 

This repository hosts the official **Engineering & Milestone Progress Dashboard**, an interactive 2-page web application designed for honest, transparent, and mathematical tracking of project deliverables, milestones, and architectural layers throughout the FYP lifecycle.

---

## ⚡ Key Dashboard Features

### Page 1: Progress & Deliverable Checklists
- **4 Key Performance Indicator (KPI) Cards:**
  1. **50% Mid-Term Target**: Tracks progress specifically against the mid-term viva requirement with an honest, half-filled dual-gauge indicator.
  2. **Final-Term Target**: Full 100% project completion trajectory.
  3. **Deliverables Status**: Real-time counter of total deliverables completed vs. pending across the entire system.
  4. **FYP Target Deadline**: Live countdown to the **1 December 2026** milestone.
- **Dual-View Switcher:**
  - **By Architectural Layers:** Organizes tasks across the 8 project tiers (Frontend & HUD, 3D & Character Pipeline, Database & Vector Schema, Backend Services, AI Narrative & Socratic RAG, Game Logic & Scaffolding, Planning & Viva Defense, Integration & QA).
  - **By Milestones:** Maps deliverables sequentially across the 13 FYP milestone phases (M1 through M13).
- **Collapsible Module Cards:** Minimalist accordion layout showing clean module headers by default (title, layer badge, progress bar, and percentage completed), expanding smoothly to reveal interactive checklist items.
- **Honest Mathematical Completion:** No arbitrary or hardcoded percentages. Every percentage is calculated strictly from completed checkboxes:
  $$\text{Completion \%} = \left(\frac{\text{Checked Items}}{\text{Total Items}}\right) \times 100\%$$

---

### Page 2: Gantt Chart & Weightage Proof
- **Interactive Gantt Timeline:** Visual schedule spanning **1 August 2026 – 31 May 2027 (518 scheduled days)**, with an active vertical line indicating today's date.
- **Section 1: Milestone Progress Ledger:** Tabular view of all 13 milestones with scheduled date ranges, planned calendar durations, assigned weightages, and real-time completion state.
- **Section 2: Mathematical Weightage Proof:**
  - **Formula Justification:** Proves mathematically why each milestone carries its exact weightage:
    $$\text{Milestone Weightage \%} = \left(\frac{\text{Scheduled Days}}{518 \text{ Total Scheduled Days}}\right) \times 100\%$$
  - **Full Milestone Ledger & Layer Roll-Up:** Comprehensive breakdown of engineering effort across Frontend (32.63%), Planning & Viva (20.66%), AI Layer (14.86%), Backend & DB (17.37%), Integration & QA (11.39%), and Game Logic (8.88%).

---

## 📱 Fully Responsive Design
- Built for all screen sizes: **Desktop**, **Tablets (iPad/Android)**, and **Mobile Phones (iOS/Android)**.
- Full zoom fidelity (supported from **80% up to 200% zoom** without text truncation or horizontal layout clipping).
- Horizontal swipe containers (`-webkit-overflow-scrolling: touch`) ensure dense Gantt schedules and tables remain navigable on small viewports.

---

## 🚀 How to Run Locally

This dashboard has **zero dependencies** and requires no build tools or package managers.

1. Clone this repository:
   ```bash
   git clone https://github.com/leena-77/Tales-Of-Wisdom.git
   cd Tales-Of-Wisdom
   ```
2. Open `index.html` directly in any modern web browser (Chrome, Edge, Firefox, Safari):
   - Double click `index.html`, OR
   - Run a simple local server:
     ```bash
     python -m http.server 8080
     ```
     and open [http://localhost:8080](http://localhost:8080).

---

## 🌐 Live GitHub Pages Deployment

To host this dashboard live for presentations and supervisors:
1. Go to your repository on GitHub: `https://github.com/leena-77/Tales-Of-Wisdom`.
2. Navigate to **Settings** > **Pages**.
3. Under **Build and deployment** > **Branch**, select `main` branch and `/ (root)` folder.
4. Click **Save**. Within 1–2 minutes, your dashboard will be live at:
   ```
   https://leena-77.github.io/Tales-Of-Wisdom/
   ```

---

## 👥 Credits & Academic Information

| Role | Name | Details |
| :--- | :--- | :--- |
| **Project** | **Tales of Wisdom** | Final Year Project (FYP) 2026–2027 |
| **Student** | **Aleena Memon** | Core Architecture, 3D Pipeline & Dashboard |
| **Student** | **Rauf Shahid** | Full-Stack Development & AI Integration |
| **Supervisor** | **Laviza Asif** | Academic Guidance & Project Supervision |
