
![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Power Automate](https://img.shields.io/badge/Power_Automate-3A96DD?style=for-the-badge&logo=power-automate&logoColor=white)
![Microsoft Lists](https://img.shields.io/badge/Microsoft_Lists-57A4FF?style=for-the-badge&logo=microsoft-lists&logoColor=white)
![SharePoint](https://img.shields.io/badge/SharePoint-0078D4?style=for-the-badge&logo=microsoft-sharepoint&logoColor=white)

💡 Collaborative Hub Project: Innovation Management & Continuous Improvement

📌 Overview

This project emerged from the need to centralize, manage, and measure improvement ideas proposed by employees. I designed an Internal Open Innovation Platform integrated within the Microsoft 365 ecosystem, where suggestions are captured, voted on, prioritized, and implemented with total transparency.

🎯 The Problem

Information Silos: Valuable ideas were often lost in emails or informal conversations.

Disengagement: Lack of feedback loops for those suggesting improvements caused team disengagement.

Unmeasured Impact: Difficulty in measuring the actual ROI (Return on Investment) of innovation within the company.

🛠️ The Solution: Gamification & Visual Management

1. Collection & Engagement (Microsoft Lists)

Created a user-friendly interface for submitting suggestions.

Implemented a "Crowd-Voting" System (Likes), empowering the team to prioritize the most relevant ideas themselves.

2. Intelligence & Governance (Power BI) The dashboard acts as the "Innovation Scoreboard", monitoring the entire lifecycle of an idea, from brainstorming to deployment.

3. Advanced DAX Metrics:

Innovation Funnel: Status monitoring (Backlog -> Under Analysis -> In Progress -> Implemented).

Engagement KPIs: Total Suggestions by Department and Average Votes per Suggestion to identify high-interest topics.

Innovation SLA (Service Level Agreement): Precise measurement of the time the company takes to turn an idea into reality:

Backlog Duration: Waiting time before analysis.

Analysis Lead Time: Feasibility assessment duration.

Implementation Cycle Time: Technical execution.

End-to-End Journey: Total Lead Time.

4. Data Engineering:

SharePoint data treatment to normalize dates and statuses.

Application of COALESCE Logic in DAX to handle null values, ensuring time metrics don't break when stages are empty or still in progress.

🚀 Results & Impact

Innovation Culture: The dashboard's visibility (showing who suggested and who voted) stimulated healthy competition and a surge in new ideas.

Radical Transparency: Employees can track exactly where their suggestion sits in the pipeline, eliminating the frustration of the "forgotten suggestion box."

Process Improvement: The implemented suggestions (tracked by the dashboard) resulted in direct optimizations of the company's workflows.
