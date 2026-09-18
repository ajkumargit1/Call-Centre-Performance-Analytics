# 📞 Call Centre Performance Analytics

A Power BI-driven analytics project that turns raw call center logs into a decision-ready performance dashboard — covering response times, customer satisfaction, call resolution, and topic-level trends. Built as part of the **Forage × PwC Job Simulation**.

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Data-Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white)
![PowerPoint](https://img.shields.io/badge/Report-PPTX-B7472A?style=flat-square&logo=microsoftpowerpoint&logoColor=white)

---

## 📁 Repository Contents

| File | Description |
|---|---|
| `Call-Center-Dataset.xlsx` | Raw source dataset used to build the dashboard |
| `Callcentre_dashboard.pbix` | Interactive Power BI dashboard file |
| `CallCentre Analysis.pptx` | Stakeholder-ready presentation summarizing findings and recommendations |
| `README.md` | Project documentation (this file) |

---

## 🎯 Project Overview

This project was completed as part of the **Forage PwC Job Simulation**, which asks participants to analyze call center data and derive actionable insights from it. Power BI was used for visualization, with new measures built using **DAX expressions** across a range of chart types.

The workflow involved cleaning the raw data and calculating: total calls per agent, average satisfaction score, average response time, number of topics, most-called topic, calls resolved by topic, and speed of response — all visualized in an interactive dashboard.

![Dashboard KPI Summary](images/dashboard-kpi-summary.png)

---

## 🛠️ Data Preparation

The dataset was sourced as an Excel file and loaded into Power BI. The date column was split into three separate fields — **date**, **time**, and **month name** — with the month name derived by reformatting the date column.

---

## 📊 Key Performance Indicators (KPIs)

- **Average Response Time: 55 seconds** — reflects how efficiently and responsively the call center handles incoming calls, calculated via a DAX average formula
- **Average Satisfaction Score: 3 / 5** — customer satisfaction rating on a scale of 1 to 5, also derived via DAX
- **Call Answered / Not Answered Ratio** — a critical measure of the center's availability and reliability
- **Agent & Month Slicers** — advanced slicers let you filter every visual by individual agent or by month
- **Topic Distribution** — a doughnut chart breaking down call volume by reason for contact

![Call Distribution by Topic](images/topic-distribution.png)

Call topics break down as: **Streaming (25.11%)**, **Payment Related (23.79%)**, **Technical Support (21.15%)**, **Contract Related (16.74%)**, and **Admin Support (13.22%)**.

---

## 🔍 Insights

Detailed insights and supporting visuals are walked through slide-by-slide in `CallCentre Analysis.pptx`. Key findings include:

- **Streaming and Contract-related calls dominate volume** — the majority of calls fall into these two categories, making them the highest-leverage areas for process improvement
- **Contract and Admin Support have the longest resolution times** — these topics are the clearest targets for targeted training and additional resources
- **Peak call volume was observed during Week 5** (for the example agent, "Dan"), which also saw the highest number of calls resolved — useful for spotting efficiency patterns and staffing bottlenecks
- **Call answered/not-answered breakdown (sample view — Agent "Dan," January):** 190 calls answered vs. 37 not answered, illustrating how the dashboard's slicers let you isolate performance at the agent and month level

![Call Answered vs Not Answered](images/call-answered-ratio.png)

> \* Figures shown for the Answered/Not Answered chart reflect one filtered view (Agent: Dan, Month: January) used as a working example in the presentation — the dashboard itself supports slicing this ratio across any agent or month.

---

## ✅ Recommendations

- **Maintain/Improve Response Times** — continue to monitor and optimize response times to enhance customer satisfaction
- **Enhance Customer Satisfaction Scores** — implement strategies such as agent training and improved problem-solving capabilities
- **Optimize Agent Availability and Performance** — adjust staffing levels based on call volume trends to reduce missed calls
- **Focus on High-Volume Topics** — develop specialized resources and training for common issues like Streaming and Contract problems
- **Reduce Resolution Times** — target improvements in slower categories such as Contract and Admin Support
- **Implement Regular Training Programs** — as a recurring next step to sustain gains across all of the above

---

## 🚀 How to Use This Project

1. **Explore the data** — open `Call-Center-Dataset.xlsx` to review the raw fields and structure
2. **Interact with the dashboard** — open `Callcentre_dashboard.pbix` in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) to filter by agent or month using the built-in slicers and explore the visuals yourself
3. **Review the findings** — walk through `CallCentre Analysis.pptx` for the full narrative, slide-by-slide insights, and recommendations — ideal for presenting to stakeholders or a hiring manager

> 💡 **Requirement:** Power BI Desktop (free) is needed to open and edit the `.pbix` file.

---

## 🧩 Conclusion

This project turns call center operations data into a clear, visual story — surfacing where performance is strong, where it's slipping, and what to do about it. The combination of an interactive Power BI dashboard and a stakeholder-ready presentation makes it easy to both explore the data independently and communicate findings to decision-makers.

---

## 📬 Contact

**Ajay Kumar**
📧 kumarajay150303@gmail.com

---

⭐ If you found this project useful, consider starring the repo!
