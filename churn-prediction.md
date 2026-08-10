---
layout: post
title: Internal Churn Prediction ML System
subtitle: Modular, production-grade churn prediction system integrated with strategic decision-making
cover-img: /assets/img/churn-background-header.png
thumbnail-img: /assets/img/churn-header.png
share-img: /assets/img/churn-header.png
tags: [churn, ML, banking]
author: Maria Granados
gh-repo: mariavgranadosj/mariavgranadosj.github.io
comments: false
mathjax: false
social-share: false
---

**Role:** Lead Data Scientist and ML Engineer  
**Organisation:** P&N Bank  

Designed and delivered the bank’s first internal machine learning system to predict and reduce customer churn across Home Loans and Term Deposits. The project established a scalable ML foundation, integrated with key business processes, and supported strategic decision-making for proactive retention.

## The challenge

Shifted the bank's churn management approach from reactive reporting to a proactive, model-driven system for identifying and targeting at-risk customers early in the lifecycle.

## The response

### Problem framing and strategic alignment
- Collaborated with product, retail, and data stakeholders to scope the use case and define measurable success metrics.
- Reframed the business problem to align with retention priorities and move beyond retrospective churn tracking.

### Feature engineering and domain collaboration
- Mapped customer journeys and extracted churn signals from behavioral, transactional, and engagement data.
- Engineered features aligned to lifecycle stages and time windows (e.g., recent vs. long-term trends) to surface early signs of disengagement.

### Model development and experimentation
- Conducted EDA and addressed class imbalance in the churn target.
- Selected business-aligned metrics (F1, PR-AUC) for evaluation.
- Applied Design of Experiments to compare model types and feature groups, balancing performance and interpretability.
- Improved F1-score and PR-AUC by 20% through factorial experimentation and targeted hyperparameter tuning.

### MLOps and pipeline design
- Built modular ML pipelines with Python, Snowflake, and produced interactive visuals in Power BI.
- Integrated CI/CD for reproducibility and scalability.
- Leveraged Snowflake model registry for versioning and automated scoring.

### Stakeholder tools and enablement
- Delivered interactive Streamlit apps to expose churn insights to business users.
- Reduced analyst load by enabling direct access to model predictions and drivers.
- Produced documentation and reusable code templates to support team enablement.

### Operational integration and governance
- Worked with Product and Salesforce teams to explore CRM workflow integration.
- Facilitated discussions around model governance, oversight, and data quality as part of broader enablement strategy.

## Selected outcomes

- Identified a **30% churn reduction opportunity** that directly shaped pricing and retention strategies.
- Delivered estimated annual cost savings of **$110K** by reducing manual reporting effort.
- Established a **reusable ML architecture** now being extended to credit risk and product lifecycle projects.

---

## Technology

`Python`, `Snowflake`, `scikit-learn`, `CI/CD`, `Design of Experiments`, `Power BI`, `GitHub Actions`
