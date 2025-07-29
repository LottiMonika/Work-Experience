# Project Charter – WFM Software Rollout

## Project Purpose

The current workforce management (WFM) software used by the Customer Service (CS) department was built for a team of 50–100 agents. The CS team has since grown to 150–200 agents, which has led to serious system performance issues. Lag in the software has caused agents to stop checking schedules regularly, increasing the risk of missed shifts and scheduling conflicts. Short-notice changes are avoided by WFM due to poor visibility and agent disengagement.

Absences are currently 100% manually approved by WFM against defined capacity thresholds. The goal is to approve 75% of absences automatically with the new tool, saving WFM up to **8 hours of manual work per week**. Legal exceptions will still require manual review.

There are no real-time monitoring dashboards in place. The new system will enable queue-level tracking (phone, chat, email), allowing the organization to hire a **real-time monitor**, with the goal of improving SLA performance to **95%**.

Manual processing for channel assignments will be replaced by automated scheduling logic, again saving WFM up to **8 hours per week**. The software introduces clearer access controls to reduce scheduling errors by team leads and managers.

Although forecasting will continue to be done externally, the new tool will assess forecast accuracy and output performance metrics to support improved future forecasting.

The new software is compliant with company security policies and will use two-factor authentication, ensuring **GDPR-compliant access** and protection of personal data.

---

## 👥 Key Stakeholders

- **Project Lead:** Lotti (responsible for planning, execution, and stakeholder alignment)
- **Vendor:** Provides platform, training for admins, daily support, and weekly check-ins
- **WFM Team:** Supports setup, configuration, and process design
- **IT & Security:** Ensures system compatibility, performs security reviews and whitelisting
- **Data Team:** Integrates WFM data into the data warehouse and ensures analytics continuity
- **CS Management & Leadership:** Receives regular updates and communicates rollout details to team leads, coaches, and agents
- **End Users:** All customer service employees, including agents, seniors, leads, coaches, and managers, will be trained and onboarded to the new system

---

## 📦 Scope

**Included:**
- System configuration and integration
- Training for all CS employees
- Automation of absence approval and scheduling
- Rollout in multiple stages (by teams)
- Embedding of data connectors into the data warehouse
- Post-rollout monitoring, KPIs tracking, and improvements
- Creation of dashboards, training material, and documentation

**Out of Scope:**
- Forecasting logic (still handled externally)
- Custom integrations not provided by vendor out-of-the-box
- Changes to contractual scheduling frameworks or work agreements

---

## ⚠️ Constraints & Assumptions

- **Phone shifts will change** from 2 daily blocks to 1–3 flexible blocks, improving scheduling flexibility but requiring adjustment by agents
- **Absence policy enforcement** will become stricter; fewer manual exceptions will be allowed
- A **temporary productivity dip (~10%)** is expected during the first two weeks post-rollout due to change adaptation
- Coaches and managers will lose some direct scheduling access, requiring stricter process adherence and reminders to use official WFM channels
- The rollout will be planned during a **low contact volume period** to minimize impact
- Some integration testing and validation will rely on availability of external systems (CRM, telephony, etc.)

---

## 📈 Success Metrics

| Goal | Target |
|------|--------|
| Schedule accuracy improvement | +15% |
| SLA performance (chat, phone, email) | 95% |
| Absences auto-approved | 75% |
| WFM manual effort reduction | -8 hours/week |
| Scheduling errors caused by unauthorized edits | 0 |
| Forecast accuracy tracking | Enabled and reviewed monthly |
| Productivity impact post-rollout | Recovery to baseline within 2 weeks |
| Agent engagement with schedules (views per week) | +30% from baseline |
