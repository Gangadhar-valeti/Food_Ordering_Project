# 🍔 Food Ordering Behavior & Operations Analysis

📊 **An Interactive Business Intelligence & Logistics Dashboard Workspace**

---

## 🔗 Live Web Integration
Explore the fully integrated web workspace, featuring interactive Tableau dashboards, structured project phase documents, and a local observations notepad:
👉 **[Food Ordering Behavior Web Hub](https://food-ordering-project-60nl.onrender.com)** *(Live Dashboard)*

---

## 📖 Executive Summary
In the highly competitive food delivery sector, data-driven decisions are key to sustaining growth and operational efficiency. This project implements a comprehensive **Business Intelligence (BI) pipeline** using **Tableau** and **Web Integration technologies** to analyze a dataset of **50,000 orders** across major cities in India. 

Through this analysis, we identify critical insights such as top-performing cities, high-demand cuisines, delivery time distributions, and customer satisfaction factors. The ultimate goal is to equip business analysts and operations managers with actionable insights.

---

## 📂 Repository Structure
```directory
Food_Ordering_Project_Repo/
├── 0_datasets/
│   └── food_ordering_behavior_dataset.csv     # Ingested order log dataset (50,000 records)
├── 1_Ideation_Phase/
│   ├── Brainstorming- Idea Generation- Prioritizaation Template.docx
│   ├── BrainstormingTemplate.pdf              # Idea prioritization matrix
│   ├── Define Problem Statements Template.docx
│   └── Empathy Map Canvas.docx                # Stakeholder requirement mapping
├── 2_Requirement_Analysis/
│   ├── Customer Journey Map - Example.pdf     # Customer touchpoint flow & touchpoint chart
│   ├── Data Flow Diagrams and User Stories.docx
│   ├── Solution Requirements.docx             # Hardware/software functional specs
│   └── Technology Stack - Template.docx
├── 3_Project_Design_Phase/
│   ├── Problem - Solution Fit Template.docx
│   ├── Proposed Solution Template.docx
│   └── Solution Architecture.docx             # 5-Layer BI architecture definition
├── 4_Project_Planning_Phase/
│   └── Project Planning Template.docx         # Sprint schedules & risk assessment matrix
├── 5_Project_Development_Phase/
│   ├── 1st PDF - Preprocessing Steps and Business Questions.pdf
│   └── 2nd PDF - Dashboard Screenshot and Story.pdf
├── 6_Performance_Testing/
│   └── Tableau .docx                          # Loading times, global filters, and calculated fields logs
├── 7_Doc_and_Demo/
│   └── Final Report.pdf                       # Rebuilt publication-ready report with visual appendices
├── handouts/                                  # Business Intelligence curriculum materials
│   ├── 1. Business Intelligence & Data Analytics.docx
│   ├── 2. Introduction to Tableau.docx
│   ├── 3. Tableau Prep Builder Introduction.docx
│   ├── Data Visualization-1.docx
│   └── Sets and Filters.docx
├── presentation vedio/
│   └── README.md                              # Google Drive download link for the walkthrough video
├── index.html                                 # Central interactive web workspace container
└── .gitignore                                 # Git exclusions
```

---

## 🛠️ Step-by-Step Analytical Approach

| Phase | Core Objective | Key Deliverables & Artifacts |
| :--- | :--- | :--- |
| **1. Ideation** | Select and validate the BI project idea. | Priority matrix, stakeholder empathy map, and problem definition. |
| **2. Requirements** | Establish technical and business specifications. | User stories, customer journey maps, and DFD Level-0/1 diagrams. |
| **3. Design** | Map architectural components and flows. | 5-Layer BI architecture specification, problem-solution fit mapping. |
| **4. Planning** | Schedule development and assess project risks. | Sprint allocation model (10 phases) and mitigation matrix. |
| **5. Development** | Preprocess data, build worksheets, and dashboards. | 10 calculated fields, 21 worksheets, 4 dashboards, and 6 story points. |
| **6. Testing** | Verify rendering latency and calculation accuracy. | Performance logs showing filter latency under 5 seconds. |
| **7. Final Report** | Publish consolidated findings and demo video. | cover-page final report PDF, presentation video walkthrough. |

---

## 📈 Dashboard Highlights & Business Insights

### 📊 Business Performance Dashboard
* **KPI Metrics**: Instant summaries of Total Revenue, Total Orders, Average Order Value (AOV), and Customer Satisfaction.
* **Top Performance**: Mumbai leads platforms in volume (18,500 orders) and AOV (INR 520).
* **Cuisine Demand**: Fast Food represents the platform's highest demand share (32%), followed by Desserts (24%).

### ⚙️ Operational Efficiency Dashboard
* **Logistics Time Slots**: 82% of orders are completed within the 4-10 minute hyper-local delivery time slot.
* **Workload Spikes**: Identified bottleneck intervals (1:00 PM and 8:00 PM) during peak meal hour transitions in Bangalore and Pune.

### 👥 Customer Experience Dashboard
* **Snack Hours Affinity**: Gen Z and Millennials represent 74% of the snack hour ordering volume.
* **Discount Impact**: Analyzed rating changes and repeat order conversions across discounted checkouts.

---

## 🎬 Presentation Walkthrough Video
Due to GitHub's file size limit of 100 MB per file, the **1.44 GB high-definition video walkthrough** (`presentation vedio/Recording 2026-07-15 230648.mp4`) has been excluded from git tracking.

📺 **[Watch the Project walkthrough video on Google Drive](https://drive.google.com/file/d/1dXFtuMq-Kz7Dvq6ITuLpbi66FyYf_9ws/view?usp=drive_link)**

---

## ⚙️ How to Run Locally

### 1. Web Hub Workspace
To explore the interactive dashboards and documentation on your system:
1. Clone this repository:
   ```bash
   git clone https://github.com/Gangadhar-valeti/Food_Ordering_Project.git
   ```
2. Double-click [index.html](file:///C:/Users/karan/OneDrive/Desktop/Food_Ordering_Project_Repo/index.html) to launch the workspace interface in your browser.
3. Switch between tabs to view design documents, worksheets summaries, and test cases.

### 2. Pushing Local Commits to GitHub
If you are linking this workspace to your GitHub repository:
```bash
# 1. Update remote repository URL (forces login as Gangadhar-valeti)
git remote set-url origin https://Gangadhar-valeti@github.com/Gangadhar-valeti/Food_Ordering_Project.git

# 2. Push commits to GitHub
git push -u origin main
```