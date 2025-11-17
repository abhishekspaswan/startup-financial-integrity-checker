Startup Financial Integrity Checker
AI-driven anomaly detection for validating accounting and financial integrity.
This repository implements an AI-powered tool to detect anomalies in startup financial data, preventing fraud and ensuring reliable reporting.
Built with Python, Pandas, SQL, and scikit-learn's Isolation Forest for ML-based anomaly detection.

What It Is: A smart tool that spots weird stuff in startup money books. Like fake numbers or hidden tricks that fool checks.
The Problem: Bad money entries hide from hand-checks. They trick investors.
The Fix: AI tool finds odd books, funny payments, and cash mix-ups.

How It Works:
Uses machine learning to scan money data.
Tools: Python, Pandas, SQL.
What You Get: Stops money cheats. Makes reports safe for funders.

Mock Financial Integrity Dataset
Company	Sales (₹ Cr)	Costs (₹ Cr)	Cash Fit %	Score (0-100)	Grade	Note
FinServe AI	120	96	97%	92	Great	Steady cash, no funny business.
EcoBuild	75	70	89%	77	Okay	Check Q2 bills—they look off.
HealthNova	150	140	72%	48	Bad	Weird cash adds and round tricks.
AgroTech	60	55	95%	88	Good	Books match bank fine.

Score Breakdown
Check	Weight	FinServe	EcoBuild	HealthNova	AgroTech	Why
Deal Match	35%	95	80	50	90	Books vs bank.
Cost Link	25%	90	75	55	88	Costs fit business?
Cash Steady	25%	94	78	40	89	In vs out flow.
Debt Fit	15%	85	74	47	91	Loans vs sales steady.

Final Scores
Company	Score	Risk
FinServe AI	92	Low
EcoBuild	77	Medium
HealthNova	48	High
AgroTech	88	Low

Why It Helps
Finds cheats early.
Smart checks ahead of time.
Builds trust with funders.
Cuts money loss from tricks.

Made by Abhishek Paswan. Run it easy: Clone, pip install, python run.
