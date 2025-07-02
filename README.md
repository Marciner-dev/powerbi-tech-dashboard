#  Tech Metrics & Reporting Dashboard – Power BI Project (in progress)

This project presents a simulated **Tech Metrics & Reporting Dashboard** built in **Power BI**, inspired by real-world use cases.

## Project Overview

I built a personal interactive Power BI dashboard using dummy XML data that mimics Jira exports.

The dashboard simulates sprint reporting and includes:
- Sprint velocity based on Release spent in hours 
- Jira Issue resolution time with total hours spent
- Status by assignee and issue type 
- Burn down indicators

I'm using Power BI, DAX and a star schema data model to calculate custom KPIs and create dynamic visuals.

This is a learning-focused project, currently in development.

I'm planning to dive deep into Power BI features, from data transformations and DAX measures to creating interactive charts that showcase the platform's capabilities.

Exited to see where it goes!

---

The goal is to demonstrate the ability to:
- Analyze and transform complex datasets
- Create clear KPI visualizations for different stakeholders
- Build scalable, automated reporting structures in Power BI

> ⚠️ Note: All data in this project is synthetic and created for portfolio/demo purposes.

---

## Dashboard Features

| Section | Description |
|--------|-------------|
| **Performance Metrics** | Average resolution time, tickets by status, team velocity |
| **CI/CD Metrics** | Deployment frequency, success rate |
| **Code Quality Snapshot** | Number of bugs, security hotspots, technical debt |
| **Time Filtering** | Custom filters for date ranges and project teams |
| **KPIs Cards** | High-level metrics for quick decision-making |

---

## Files in this Repo

- `Marcin Power BI project.pbix` – Main Power BI dashboard file  
- `dim_sprints.xml`
- `dim_users.xml`
- `fact_issue_activity.xml`
- `jira_issues__100.xml`

---

## Skills Demonstrated

- Power BI report design & DAX
- Data modeling & relationships
- Dashboard layout & UX
- Synthetic data creation
- Understanding of tech KPIs (Agile, DevOps, Code Quality)

---

## Future Improvements

- Add data refresh via Power Query from online JSON/XML
- Simulate real-time metrics integration
- Build GitHub Actions-style CI/CD data stream

---

## About Me

I'm currently transitioning into a data/BI-focused role and developing my skills in Power BI and analytics for tech teams.  
This project is part of my **learning journey** and **portfolio for job applications** in data & analytics.

Connect with me on [LinkedIn](https://www.linkedin.com/in/marcin-rusiecki-67a46b102/) or check out more of my work on [GitHub](https://github.com/Marciner-dev/powerbi-tech-dashboard).
