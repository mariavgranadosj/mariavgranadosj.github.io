---
layout: post
title: Churn Prediction ML System
subtitle: The bank's first internal churn models and reusable MLOps foundations
tags: [churn, ML, banking]
author: Maria Granados
date: 2026-08-10
comments: false
mathjax: false
social-share: false
---

## The challenge

Churn management relied on retrospective reporting. Product teams needed earlier signals they could use to shape pricing and retention decisions across home loans and term deposits.

## The response

I led the bank's first internal churn modelling system from problem framing through experimentation and production design. The work combined customer lifecycle signals, business-aligned evaluation, modular pipelines, and decision tools for product teams.

### Sanitised architecture

<div class="abstract-diagram" aria-label="Abstract churn prediction flow">
  <div><span>01</span><strong>Signals</strong><small>customer behaviour</small></div>
  <div><span>02</span><strong>Features</strong><small>lifecycle patterns</small></div>
  <div><span>03</span><strong>Model</strong><small>risk and drivers</small></div>
  <div><span>04</span><strong>Act</strong><small>retention decisions</small></div>
</div>

## Selected outcomes

- Identified a **30% churn reduction opportunity** that influenced pricing strategy.
- Improved F1-score and PR-AUC by **20%** on imbalanced datasets.
- Established reusable MLOps foundations for versioning, CI/CD, and production monitoring.
- Made model predictions and drivers accessible to business users.

## Technology

`Python` · `Snowflake` · `scikit-learn` · `Design of Experiments` · `CI/CD` · `Power BI`

> Recreated from scratch as sanitised architecture. Customer data, feature definitions, decision thresholds, and workflow details are omitted.
