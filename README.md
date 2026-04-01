📊 Vanguard UX Optimization & A/B Testing Project

This project evaluates the impact of a redesigned digital interface on user experience and process completion within a financial services platform. By combining customer journey analysis, exploratory data analysis (EDA), and hypothesis testing, the project assesses whether the new UI improves usability, reduces friction, and drives higher completion rates.

🛠️ Tech Stack & Tools

Python · Pandas · NumPy · Matplotlib · Seaborn · Statistical Testing (Z-test, T-test, Chi-square) · Jupyter Notebook · Tableau

📚 Project Background & Overview

The Friction: UX Inefficiencies in Digital Journeys
Users navigating Vanguard’s online process experienced drop-offs, confusion, and inefficiencies across multiple steps. High bounce rates, backward navigation, and long completion times indicated friction in the customer journey.
The Fix: Data-Driven UX Redesign
An A/B test was conducted to evaluate a redesigned interface aimed at improving usability. The new experience introduced a simplified, more intuitive flow, with the goal of increasing completion rates and optimizing the overall user journey.

📊 Data Architecture

Pillar	Source	Key Features / Data Points
Client Profiles	Internal Dataset	Age, gender, tenure, demographics
Digital Footprints	Web Interaction Logs	Session activity, timestamps, process steps
Experiment Roster	A/B Test Assignment	Control vs Test group

📈 Executive Summary

UX Impact: Improved Completion, Reduced Friction
The redesigned interface increased completion rate from 65% to 69%, exceeding the business threshold of +5% uplift and confirming improved usability .
Trade-Off Insight: Simplicity vs Engagement
While the new UI reduced friction and improved efficiency (lower time per step), it also led to lower engagement and retention, suggesting a more streamlined but less “sticky” experience .

💡 Insight Deepdive

Customer Journey Analysis (EDA)
EDA revealed how users interact with each step of the process:
Friction Points: High time spent and drop-offs between Step 3 and Confirmation highlight a critical bottleneck
Error Behavior: Increased backward navigation (error rate) signals confusion, particularly at the start step and among older users
Bounce Rate Improvement: The new design reduced early-stage abandonment (14% → 9%), indicating a smoother entry experience
Behavioral Insights
Middle-aged users (40–64) represent the largest user segment
Male users show slightly higher interaction frequency
New UI reduces the need for repeated actions, suggesting improved clarity

🧪 Hypothesis Testing

Core Hypothesis: Completion Rate
H₀: No difference between old and new UI
H₁: New UI improves completion rate
✔ Result: Statistically significant improvement (p < 0.05) → Reject H₀
Business Hypothesis: Cost-Effectiveness
Required uplift: +5%
Observed uplift: +5.41%
✔ Result: The redesign meets the business viability threshold and supports rollout
Additional UX Hypotheses
Bounce Rate ↓ → Improved entry experience
Retention ↓ → Potential friction at early stages
Engagement ↓ → Simpler UX reduces repeated interactions

🎯 Key Learnings

UX simplification improves conversion but may reduce engagement
Customer journey analysis is critical to identify hidden friction points
Data-driven UI decisions must balance efficiency and long-term user retention

🚀 Future Roadmap

[Product & UX Improvements]
Optimize start step experience to reduce error rates
Improve transition from Step 3 → Confirmation (major bottleneck)
Introduce adaptive UX for older users

[Advanced Analytics]
Incorporate behavioral segmentation models
Add real-time user journey tracking
Extend A/B testing duration for long-term impact analysis

[Business Impact]
Improve completion → higher conversion & revenue potential
Reduce friction → better customer satisfaction
Enable data-driven UX → scalable optimization strategy

