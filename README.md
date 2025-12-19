# FlowSight — Predictive Sprint Analytics MVP

FlowSight is a predictive sprint analytics system designed to detect delivery risk early and recommend corrective actions for engineering teams.

---

## 🚩 Problem Statement
Engineering teams often realize sprint delays too late, leading to spillovers, missed commitments, and reactive firefighting. Existing tools like Jira provide descriptive reports but lack predictive insights and decision support.

---

## 🎯 Solution Overview
FlowSight transforms sprint data into actionable intelligence by:
- Detecting early sprint risk
- Predicting delay probability
- Highlighting at-risk work
- Recommending corrective actions

---
## MVP Focus

FlowSight was intentionally built as an MVP to validate one core question:

Can sprint delivery risk be detected early using signals already available in Jira?

The project focuses on early risk detection and decision support, 
not on building a full production-grade analytics platform.


## 📦 MVP Scope
**Data Source:** Jira only  
**Target Users:** Product Managers, Engineering Managers  

### Included
- Sprint health analytics
- Feature engineering
- Delay risk estimation
- Actionable recommendations
- Analytics dashboard

### Not Included
- GitHub / Slack integrations
- Real-time streaming
- Automated actions
- Advanced ML models

---

## 🧠 Core Capabilities

### Sprint Health Features
- Velocity deviation
- Burndown deviation
- Blocker impact score
- Workload imbalance
- Story churn indicators
- Sprint progress ratio

### Predictive Outputs
- Delay probability
- At-risk story points
- Sprint risk level (Low / Medium / High)

### AI Recommendations
- Resolve high-impact blockers
- Reassign work from overloaded developers
- Freeze scope additions mid-sprint

---

## 🏗 Architecture Overview
FlowSight follows a clean, modular architecture:

Jira  
→ Feature Engineering  
→ Risk & Prediction Logic  
→ AI Recommendation Engine  
→ Analytics Dashboard  

(Architecture visuals available in architecture/Architecture.png

---

## 📊 Dashboard
The dashboard provides:
- Sprint summary & context
- KPI cards for risk and health
- Trend visualizations
- Root cause analysis
- Actionable recommendations

(Dashboard visuals available in `/dashboard`)

---

## 📈 Business Impact (Estimated)
- Early sprint risk detection (Day 2–4)
- 20–30% reduction in sprint spillover
- Improved sprint predictability
- Faster decision-making for PMs & EMs

*Estimates based on industry benchmarks*

---

## ⚠ Limitations
- Prediction accuracy depends on historical sprint data quality
- Assumes consistent Jira usage
- MVP focuses on sprint-level signals only

---

## 🔮 Future Enhancements
- GitHub & Slack signal integration
- Personalized dashboards by role
- Feedback-driven recommendation tuning
- Advanced velocity forecasting

---

## 👤 Author
Built as a product & analytics case study for internship applications.
