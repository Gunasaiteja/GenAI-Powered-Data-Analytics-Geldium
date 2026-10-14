# GenAI-Powered Data Analytics — Geldium Collections Strategy

**Job simulation:** Tata × Forage — GenAI Powered Data Analytics  
**Author:** Guna Sai Teja K  
**Completed:** October 14, 2026

## Project overview

This project documents a business-focused AI solution concept for helping Geldium's Collections team identify customers who may miss upcoming credit-card payments and provide timely, appropriate support.

The work focuses on translating data-analysis and predictive-analytics concepts into stakeholder recommendations, while considering fairness, explainability, human oversight, and responsible AI.

> **Important scope note:** This repository contains the reports and strategy deck produced during the simulation. The candidate risk factors are hypotheses to validate against the source dataset. It does not claim that a predictive model was trained or validated unless actual dataset analysis and model evaluation are added.

## Problem statement

How can a financial-services collections team use predictive insights to prioritize helpful customer outreach while managing risk, fairness, transparency, and regulatory responsibilities?

## Work completed

1. **Exploratory Data Analysis (EDA) planning** — identified data-quality checks and candidate delinquency indicators to investigate.
2. **Predictive model evaluation framework** — outlined appropriate evaluation measures such as precision, recall, F1, ROC-AUC/PR-AUC, calibration, and fairness checks.
3. **Stakeholder recommendations** — drafted a concise report with a SMART pilot recommendation.
4. **Responsible AI considerations** — covered bias risks, explainability, human review, privacy, and monitoring.
5. **Agentic AI concept** — described bounded autonomous tasks and decisions that should remain under human oversight.
6. **Executive presentation** — created a five-slide strategy deck covering workflow, learning loop, governance, and impact measurement.

## Proposed high-level workflow

**Customer/account data → Risk estimate and explanation → Policy-based action → Outcome measurement → Reviewed learning loop**

- **Inputs:** payment history, utilization, balances, and other validated fields available in the approved dataset.
- **Decision logic:** use a validated risk estimate plus eligibility rules, customer preferences, and confidence checks.
- **Actions:** select an approved reminder or support option; route exceptions for human review.
- **Learning loop:** measure repayment outcomes, complaints, opt-outs, errors, and fairness indicators; validate changes before release.

## SMART pilot proposal

Run a six-week controlled SMS outreach pilot for an appropriately defined at-risk segment. A proposed target is a **10% relative reduction in 30-day delinquency compared with a control group**. This is a target for evaluation, not a guaranteed or observed result. The segment definition, baseline, sample size, and success criteria must be finalized using actual data and business approval.

## Responsible AI guardrails

- Measure model performance and error rates across relevant customer groups.
- Explain risk flags in plain language and provide a route to correct inaccurate data.
- Keep human review for disputed, sensitive, or high-impact decisions.
- Limit data use and access; maintain audit logs and review applicable compliance requirements.
- Monitor drift and customer-harm indicators; version, test, approve, and roll back changes when needed.

## Success metrics

- 30-day delinquency rate and repayment/cure rate
- Outreach success and cost per successful resolution
- Precision, recall, calibration, and false-alert rates
- Complaint rate, opt-outs, and contact errors
- Fairness gaps and human-review outcomes

## Repository contents

- `reports/Geldium_EDA_Report.docx` — preliminary EDA report and candidate checks
- `reports/Geldium_Model_Evaluation_Plan.docx` — proposed model evaluation framework
- `reports/Geldium_Stakeholder_Predictive_Insights_Report.docx` — stakeholder report and SMART pilot proposal
- `presentation/Geldium_AI_Collections_Strategy_Deck.pptx` — five-slide executive briefing

Some files may be omitted if they were not available when this package was assembled.

## Skills demonstrated

- Generative AI (GenAI) and prompt engineering
- Exploratory data analysis (EDA) concepts
- Predictive analytics and model evaluation planning
- Business analysis and data-driven recommendations
- Responsible AI, fairness, and explainability
- Agentic AI concepts and human-in-the-loop design
- KPI definition, stakeholder reporting, and presentation design

## How to use

Open the Word reports in Microsoft Word or Google Docs and the presentation in PowerPoint or Google Slides. Review all candidate insights against the actual simulation dataset before presenting them as measured findings.

## Disclaimer

This is an educational job-simulation project, not a production credit-risk system or financial advice. Any real deployment would require validated data and models, appropriate governance, security, legal/compliance review, and ongoing monitoring.
