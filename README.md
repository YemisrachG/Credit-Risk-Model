# Credit Risk Model

Credit Risk Model for Bati Bank's buy-now-pay-later service.
Credit Scoring Business Understanding (GitHub README) – Summary 
1.	How Basel II affects our modeling:
Basel II emphasizes transparency and the use of internal risk models. Therefore, interpretable models with strong documentation (e.g., logistic regression with WoE) are critical for regulatory approval.
2.	Need for Proxy Default Variable:
Since the dataset lacks a labeled “default” outcome, a proxy (e.g., non-top-up for 90 days) must be created. Risk: this proxy may misclassify good borrowers, introduce bias and affecting fairness or compliance.
3.	Model Trade-offs in Financial Context:
o	Logistic Regression with WoE is interpretable and satisfies compliance.
o	XGBoost offers better performance but is complex.
Trade-off: we must balance performance vs. explainability, especially when facing audits or legal challenges.

