---
layout: page
title: "Project Overview"
nav_order: 1
---

# Project Overview

## 🎯 Problem Statement

Digital payment fraud is a growing epidemic with staggering financial impacts:

- **Global losses** exceeding $30 billion annually
- **False positive rates** of 5-10% in traditional systems
- **Evolving tactics** that outpace rule-based detection
- **Customer frustration** from legitimate transaction declines

## 💡 Our Solution

We're developing a **real-time AI-powered fraud detection system** that:

- Processes transactions in **under 500 milliseconds**
- Achieves **>90% fraud detection rate** (recall)
- Maintains **>85% precision** to minimize false positives
- **Adapts automatically** to new fraud patterns
- Provides **explainable decisions** for fraud analysts

## 🎯 Project Objectives

### Primary Objective
To design, implement, and evaluate a prototype real-time fraud detection system using machine learning and stream processing technologies.

### Specific Objectives
1. **Data Management**
   - Acquire and preprocess the IEEE-CIS fraud detection dataset
   - Perform comprehensive exploratory data analysis (EDA)
   - Engineer predictive features for transaction analysis

2. **Model Development**
   - Implement and compare multiple ML algorithms
   - Handle extreme class imbalance (99.8% legitimate vs 0.2% fraud)
   - Optimize model performance for precision-recall balance

3. **Real-Time System**
   - Build stream processing pipeline with Apache Kafka
   - Develop low-latency model serving API
   - Implement real-time feature calculation and caching

4. **Evaluation & Documentation**
   - Comprehensive performance benchmarking
   - System latency and throughput testing
   - Complete technical documentation

## 🔧 Technology Stack

<div class="tech-stack">
  <div class="tech-category">
    <h4>Machine Learning & Data Science</h4>
    <ul>
      <li><strong>Python</strong> - Primary programming language</li>
      <li><strong>Pandas, NumPy</strong> - Data manipulation</li>
      <li><strong>Scikit-learn</strong> - Machine learning algorithms</li>
      <li><strong>XGBoost</strong> - Gradient boosting for classification</li>
      <li><strong>Imbalanced-learn</strong> - Handling class imbalance</li>
    </ul>
  </div>
  
  <div class="tech-category">
    <h4>Real-Time Processing</h4>
    <ul>
      <li><strong>Apache Kafka</strong> - Stream processing platform</li>
      <li><strong>Flask/FastAPI</strong> - Model serving API</li>
      <li><strong>Redis</strong> - Real-time feature store and caching</li>
    </ul>
  </div>
  
  <div class="tech-category">
    <h4>Infrastructure & Tools</h4>
    <ul>
      <li><strong>Docker</strong> - Containerization</li>
      <li><strong>Git</strong> - Version control</li>
      <li><strong>Jupyter Notebook</strong> - Data analysis and experimentation</li>
      <li><strong>GitHub Pages</strong> - Project website hosting</li>
    </ul>
  </div>
</div>

## 📋 Project Scope

### ✅ In Scope
- Real-time transaction processing pipeline
- Multiple machine learning model implementation
- Performance benchmarking and evaluation
- Web-based monitoring dashboard
- Comprehensive documentation

### ❌ Out of Scope
- Production payment gateway integration
- Regulatory compliance implementation (PCI-DSS)
- Mobile application development
- Multi-currency and cross-border transaction handling
- Production-grade security implementation

## 📊 Success Metrics

| Metric | Target | Current | Status |
|--------|--------|---------|--------|
| Fraud Detection Rate (Recall) | >90% | TBD | 🟡 Pending |
| Precision | >85% | TBD | 🟡 Pending |
| End-to-End Latency | <500ms | TBD | 🟡 Pending |
| Throughput | >100 TPS | TBD | 🟡 Pending |
| False Positive Rate | <15% | TBD | 🟡 Pending |

## 🗓️ Project Timeline

```mermaid
gantt
    title Project Timeline 2025-2026
    dateFormat  YYYY-MM-DD
    section Phase 1: Foundation
    Literature Review     :done, 2025-09-01, 2w
    Environment Setup     :done, 2025-09-15, 1w
    Data Acquisition & EDA :active, 2025-09-22, 3w
    section Phase 2: Elaboration
    Model Development     :2025-10-13, 4w
    System Architecture   :2025-11-10, 3w
    Interim Report        :2026-01-25, 2w
    section Phase 3: Construction
    Implementation       :2026-02-01, 6w
    Testing & Evaluation :2026-03-15, 4w
    Final Documentation  :2026-04-19, 2w
