# BSE 2210 — Software Design
## Assignment 1: Foundations of Modern Software Design
### Unified Student Experience Platform (USEP) — Documented Artifacts

**Team:** BSE2210_Design_GroupXX  
**Date:** September 18, 2025  

---

## 1. Software Design in 2025 — Process and Artifact  

### Design as a Process  
In 2025, software design is iterative and adaptive. It balances user needs, business goals, and sustainability.  
The process includes discovery, modeling, decision-making, validation, and continuous evolution.  

### Design as an Artifact  
Artifacts are tangible outputs such as UML diagrams, ADRs, and CI/CD pipeline diagrams.  
They ensure communication, traceability, and maintainability.  

---

## 2. Modern Design Trends  

- **Microservices & API-First:** Services for Academic, Support, Community modules allow independent scaling.  
- **Serverless:** Used for notifications (exam alerts, reminders) to reduce cost.  
- **AI Integration & MLOps:** Advising chatbot with fairness checks and CI/CD-like pipelines.  
- **Sustainable Architecture:** Cloud with renewable energy, caching, and optimized workloads.  

---

## 3. Business Case  

**Problem:** Student services are fragmented, inefficient, and frustrating.  
**Solution:** Unified Student Experience Platform (USEP) integrating LMS, HR, and financial systems.  
**Value:** Improves retention, reduces costs, enhances scalability.  

**KPIs:**  
- +15% student satisfaction  
- –30% ticket resolution time  
- 3+ legacy systems integrated in 18 months  

---

## 4. Outsourcing Options  

- **Onshore:** Same country, high cost, best compliance.  
- **Nearshore:** Neighboring regions, balanced cost and collaboration.  
- **Offshore:** Lowest cost, time-zone/cultural challenges.  

**Recommendation:** Nearshore for most tasks, onshore for sensitive data, selective offshore for UI/testing.  

---

## 5. Cultural Intelligence  

**Inclusivity requirements:**  
1. Multilingual interface with RTL support.  
2. Accessibility (WCAG 2.2 AA).  
3. Time-zone awareness in calendars.  
4. Privacy and consent transparency.  

---

## 6. DevOps & DevSecOps  

**Pipeline includes:**  
Code commit → Build & Unit Tests → Security Scans → Registry → Integration Tests →  
Staging Deploy → AI Model Validation → End-to-End Tests → Production → Monitoring.  

**Principles:**  
- Shift-left security  
- Infrastructure as Code  
- Observability  

```mermaid
flowchart TD
  A[Code Commit] --> B[Build & Unit Tests]
  B --> C[Static Security Scan]
  C --> D[Container Registry]
  D --> E[Integration Tests]
  E --> F[Staging Deploy]
  F --> G[Model Validation (AI Services)]
  G --> H[End-to-End Tests]
  H --> I[Production Deployment]
  I --> J[Monitoring & Alerts]
```

---

## 7. AI Opportunities & Ethics  

**Opportunity:** AI advising assistant for courses and deadlines.  
**Concern:** Bias in recommendations. Mitigation includes fairness audits, transparency, and human oversight.  

---

## 8. Sample ADR  

**ADR 001 — Adopt Microservices Architecture**  
- **Context:** Need modular integration.  
- **Decision:** Microservices with API Gateway.  
- **Consequences:** Scalability gains but requires advanced DevOps.  

---

## 9. Conclusion  

USEP reflects modern practices in 2025: modular microservices, AI integration, sustainability, inclusivity,  
and DevSecOps. Balanced outsourcing and cultural intelligence will ensure longevity and effectiveness.  
