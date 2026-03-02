# 📄 Documentation — Zomato Dynamic Pricing Transparency (PRD)

This folder contains a **Product Requirements Document (PRD)** focused on improving **pricing transparency, user trust, and checkout conversion** in Zomato’s food delivery experience in India.

---

## 📌 Overview

This PRD addresses **user drop-offs caused by dynamic delivery fee fluctuations** by defining clear product requirements and success metrics for a **pricing transparency solution**.
The objective is to improve **user confidence at checkout** while preserving Zomato’s ability to apply demand-based pricing.

---

## 🎯 Product Objectives

* Reduce pricing-related cart abandonment
* Improve checkout conversion rate
* Increase repeat ordering behavior
* Improve perceived fairness and trust in pricing

---

## 🧠 Business Context

Zomato operates a **high-frequency, price-sensitive marketplace** where delivery fees dynamically vary based on:

* Demand and surge hours
* Weather conditions
* Delivery partner availability
* Distance and zone-based pricing

Currently, users often experience **late-stage fee increases with limited explanation**, resulting in:

* Checkout drop-offs
* Negative price perception
* Trust erosion
* Long-term churn risk

Improving pricing transparency directly impacts:

* Revenue and conversion
* Customer lifetime value (LTV)
* Support costs
* Brand trust and credibility

---

## 📐 Scope Definition

### In Scope

* User-facing delivery fee breakdown
* Contextual explanations for dynamic pricing
* Cart and checkout UX changes
* KPI definition and experimentation strategy

### Out of Scope

* Core pricing algorithm changes
* Delivery partner payout models
* Restaurant commission logic
* Regulatory or legal pricing mandates

---

## 🔁 Current State vs Future State

### Current State

* Sudden delivery fee changes at checkout
* No reason-based explanation
* Perceived arbitrary or unfair pricing

### Future State

* Transparent fee breakdown before payment
* Context-aware explanations (rain, peak demand, distance)
* Consistent pricing communication across the user journey

---

## 🧩 Product Requirements

### P0 — Must Have

* Real-time delivery fee breakdown
* Reason codes for dynamic pricing changes
* Pricing accuracy under high traffic

### P1 — Should Have

* Early surge pricing indicators
* Context-aware pricing messages
* UX consistency across Android and iOS

### P2 — Nice to Have

* Pricing tooltips and microcopy
* Historical fee comparison
* Regional language support

---

## 🔐 Non-Functional Requirements

* Low-latency pricing updates
* High availability during peak demand
* Data consistency across services
* Scalable architecture for festivals and high-load events

---

## 📊 Success Metrics & KPIs

### Primary KPIs

* **Cart-to-Order Conversion Rate**
* **Pricing-Related Cart Abandonment Rate**

### Secondary KPIs

* Checkout Drop-off Rate
* Repeat Order Rate
* Pricing Tooltip Engagement
* Pricing-Related Support Tickets
* Post-order NPS (Pricing Perception)

---

## 🗓️ Execution Plan (6–8 Weeks)

1. User pain point validation
2. Pricing journey diagnostics
3. Solution design and prioritization
4. UX and content validation
5. Engineering feasibility review
6. A/B experimentation
7. KPI evaluation
8. Rollout recommendation

---

## 👥 Stakeholders

* Product Management
* Business Analytics
* Backend & Mobile Engineering
* UX / UI Design
* Data & Experimentation
* Operations
* Customer Support

---

## 🧑‍💼 Role & Ownership

**Role:** Business Analyst

**Accountability:**

* Problem framing and requirement definition
* KPI ownership and success measurement
* Stakeholder alignment
* Data-backed product recommendations

---

## 📚 References

* Zomato investor communications
* Marketplace pricing transparency benchmarks
* Industry research on trust and dynamic pricing
