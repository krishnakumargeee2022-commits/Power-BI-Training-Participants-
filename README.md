


📊 Training Dashboard – Power BI Project

📌 Project Overview

This project is an interactive Training Dashboard built using Microsoft Power BI.
It provides clear insights into training attendance, participation, team performance, gender distribution  and job levels.
The dashboard helps management track training effectiveness and attendance patterns in a simple, visual way.



🎯 Objectives

* Monitor total enrolled, present, and absent participants
* Analyze attendance team-wise and manager-wise
* Understand gender distribution
* Track participation across job levels
* Enable easy filtering for better decision-making



 🛠 Tools & Technologies Used

* Microsoft Power BI
* Power Query (Data Cleaning & Transformation)
* DAX (Calculated Measures)
* Excel (Data Source)

📂 Dataset Details

The dataset includes:

* Participant Name
* Gender
* Job Level
* Team
* Manager
* Training Type (Basic / Intermediate)
* Attendance Status (Present / Absent)



# 📊 Dashboard Features
 🔢 KPI Cards

* Total Enrolled
* Present Count
* Absent Count
* Average Attendance (%)

# 📈 Visualizations

* Gender-wise Distribution (Pie Chart)
* Team-wise Attendance(Clustered Column Chart)
* Job Level Distribution(Tree Map)
* Manager-wise Summary (Waterfall Chart)

# 🎛 Filters / Slicers

* Training Level (Basic / Intermediate)
* Senior Manager
* Team
* Job Level

---


## 📐 Key DAX Measures Used

DAX
Total Enrolled = COUNT('TrainingData'[Name])

Present Count = CALCULATE(COUNT('TrainingData'[Name]), 'TrainingData'[Status] = "Present")

Absent Count = CALCULATE(COUNT('TrainingData'[Name]), 'TrainingData'[Status] = "Absent")

Attendance % = DIVIDE([Present Count], [Total Enrolled]) * 100

## 🚀 How to Use This Project

1. Download the `.pbix` file
2. Open it using **Power BI Desktop**
3. Load the Excel dataset if required
4. Interact with slicers to explore insights



## 💡 Insights Gained

* Attendance rate is high across most teams
* Certain teams show higher absenteeism
* Balanced gender participation in training
* Senior and mid-level employees actively attend sessions



## 📌 Future Enhancements

* Add trend analysis over multiple training sessions
* Include performance scores
* Automate data refresh using Power BI Service
* Role-based dashboards for managers



## 👤 Author

**Krishna Kumar**
Full Stack Developer | Power BI Enthusiast
📍 SNS College of Technology, Coimbatore


## ⭐ If you like this project

Give it a ⭐ on GitHub and feel free to fork or contribute!




