Customer Inactivity & Churn Analysis (PaySim)
Overview

Customer inactivity is often an early warning signal of churn.
This project analyzes transaction behavior patterns to identify behavioral signals associated with customer churn using the PaySim dataset.

The focus is on framing churn through real-world business logic rather than relying on a pre-existing churn label.

Business Problem

Financial institutions lose revenue when customers gradually disengage before fully churning.

This project explores:

Whether long inactivity predicts churn

Whether transaction frequency impacts retention

Whether certain transaction behaviors correlate with higher churn risk

The objective is to identify early warning signals that can support retention strategies.

Dataset

PaySim – Simulated mobile money transaction dataset containing transaction types, amounts, and behavioral patterns.

Churn Definition

Since no explicit churn label exists, churn is defined behaviorally using:

Extended inactivity gaps

Low transaction frequency
Engagement decline signals
This mirrors how churn is often inferred in real-world financial analytics.

Key Analysis
Churn vs. Inactivity Gap
Churn vs. Transaction Frequency
Churn by Dominant Transaction Type

Key Insights
Long inactivity is the strongest churn signal
Lower transaction frequency is associated with higher churn
Behavioral features provide strong early detection signals

Tools Used
Python (Pandas, NumPy, Matplotlib, Seaborn)
Jupyter Notebook.
