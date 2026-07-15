# Food Ordering Behavior & Logistics Analysis (Tableau)

This repository contains the complete Business Intelligence project analyzing **Food Ordering Behavior & Operational Logistics Performance** using **Tableau** and **Web Integration technologies**. The project is based on a transactional dataset of over **50,000 orders** spanning multiple cities, cuisines, and demographics.

## 🚀 Interactive Workspace & Web Hub
The project features a central, interactive HTML5 web hub that embeds the live Tableau dashboards, links all project documentation (Ideation, Design, Planning, Requirements, Testing, and Final Reports), and includes a local observations notebook.
* **Launch Interface**: Open [index.html](file:///C:/Users/karan/OneDrive/Desktop/Food_Ordering_Project_Repo/index.html) in any modern browser.

---

## 📂 Repository Structure
```directory
Food_Ordering_Project_Repo/
├── 0_datasets/
│   └── food_ordering_behavior_dataset.csv     # The core transactional dataset (50,000 records)
├── 1_Ideation_Phase/
│   ├── Brainstorming- Idea Generation- Prioritizaation Template.docx
│   ├── BrainstormingTemplate.pdf              # Idea selection and weighting matrix
│   ├── Define Problem Statements Template.docx
│   └── Empathy Map Canvas.docx                # Stakeholder feels, thhinks, says, does canvas
├── 2_Requirement_Analysis/
│   ├── Customer Journey Map - Example.pdf     # User experience touchpoint flow
│   ├── Data Flow Diagrams and User Stories.docx
│   ├── Solution Requirements.docx             # Hardware/software functional requirements
│   └── Technology Stack - Template.docx
├── 3_Project_Design_Phase/
│   ├── Problem - Solution Fit Template.docx
│   ├── Proposed Solution Template.docx
│   └── Solution Architecture.docx             # 5-Layer BI architecture overview
├── 4_Project_Planning_Phase/
│   └── Project Planning Template.docx         # Sprints scheduling and risk assessment
├── 5_Project_Development_Phase/
│   ├── 1st PDF - Preprocessing Steps and Business Questions.pdf
│   └── 2nd PDF - Dashboard Screenshot and Story.pdf
├── 6_Performance_Testing/
│   └── Tableau .docx                          # Latency, loading times, and filter pass reports
├── 7_Doc_and_Demo/
│   └── Final Report.pdf                       # Comprehensive 7-page analytical publication
├── handouts/                                  # Business Intelligence curriculum documents
│   ├── 1. Business Intelligence & Data Analytics.docx
│   ├── 2. Introduction to Tableau.docx
│   ├── 3. Tableau Prep Builder Introduction.docx
│   ├── Data Visualization-1.docx
│   └── Sets and Filters.docx
├── presentation vedio/
│   └── Recording 2026-07-15 230648.mp4        # Presentation video walkthrough (local only)
├── index.html                                 # Central web workspace container
└── .gitignore                                 # Git exclusions file
```

---

## 🛠️ Step-by-Step Analytical Approach

### 1. Ideation & Project Selection
* Brainstormed five different BI dashboard concepts (Sales, Hospital, Student, E-Commerce, Food Delivery).
* Prioritized the **Food Ordering Behavior Analysis** project due to its high commercial value, data availability, and operational learning potential.
* Conducted empathy mapping to align dashboard outcomes with business managers (monitoring revenue) and operations managers (reducing delivery bottlenecks).

### 2. Requirement Analysis
* Mapped customer action flows from initial platform exploration through delivery and rating feedback.
* Outlined four core User Stories defining specific dashboard views needed by Business Managers, Operations Managers, Marketing Managers, and CX Analysts.
* Set performance targets (2-5 second dashboard load times) and defined the system tech stack.

### 3. Solution Design
* Structured a 5-layer BI architecture: **Data Source** ➔ **Data Processing** ➔ **Visualization** ➔ **Dashboard Story** ➔ **Web Integration**.
* Mapped specific problems to visual components (e.g., city workload spikes mapped to geographical heatmaps).

### 4. Project Planning
* Set up a 10-phase schedule timeline.
* Documented risk mitigation strategies (e.g., handling missing fields, managing calculation latency).

### 5. Development & Dashboard Building
* Connected Tableau to the dataset, performed type casting, and created **10 calculated fields** (such as `Repeat Order Flag`, `Rating Tier`, `Delivery Speed Bucket`).
* Designed **21 worksheets** and grouped them into **4 interactive dashboards**:
  1. *Business Performance*: Revenue KPIs, city-level ordering volumes, and cuisine demand.
  2. *Operational Efficiency*: Order preparation time distribution, peak hour logistics, and city workload heatmaps.
  3. *Customer Experience*: Feedback trends, repeat order metrics, and discount-to-rating impact.
  4. *Executive Summary*: Platform KPI overview and dashboard navigation controls.
* Published the unified workspace containing **6 story points** to Tableau Public.

### 6. Performance Testing
* Evaluated filter response speeds under global constraints (City, Day Type, Mood, etc.).
* Verified that dashboard loading times consistently remained under 5 seconds under normal test parameters.

### 7. Documentation & Video Demo
* Produced a detailed cover-page analytical **Final Report.pdf** outlining executive takeaways, operational time slots, and marketing recommendations.
* Recorded a comprehensive 10-minute HD walkthrough video demonstrating interactive features.

---

## 🎥 Presentation Video Demo
Due to GitHub's file size restriction of 100 MB per single file, the **1.44 GB high-definition video walkthrough** (`presentation vedio/Recording 2026-07-15 230648.mp4`) has been excluded from git tracking. 

* **To Access Locally**: Play the file directly from [presentation vedio/Recording 2026-07-15 230648.mp4](file:///C:/Users/karan/OneDrive/Desktop/Food_Ordering_Project_Repo/presentation%20vedio/Recording%202026-07-15%20230648.mp4).
* **To Access via Web Hub**: Click the "🎥 Play Video Recording" link in the "Demo Video Outline" tab inside `index.html`.

---

## 💻 Getting Started

### Local Setup
1. Clone this repository to your local system:
   ```bash
   git clone <your-repository-url>
   ```
2. Navigate to the project root and launch `index.html` in your browser:
   * Double-click `index.html` or open it from your browser (e.g., Chrome, Edge).
3. The interactive side panel will allow you to read all Microsoft Word (`.docx`) and PDF templates locally from your desktop.

### Git Version Control
A local git repository has been initialized in this folder with the `.gitignore` pre-configured to ignore the heavy video recording:
```bash
# Add your GitHub repository remote url
git remote add origin <your-github-repo-url>

# Push the project files to main
git branch -M main
git push -u origin main
```
