#  Governance Assurance Framework — Module Index

This repository provides **evidence-centered, audit-ready AI governance controls**, aligned with ISO/IEC 42001, NIST AI RMF, and the EU AI Act.

Select a module below to explore artifacts, SOPs, diagrams, and governance controls.

---

##  Case Study Modules

| Module | Description | Link |
|-------|-------------|------|
| **LLM Governance Failure Case Study (Deloitte Australia)** | Demonstrates how missing provenance controls and oversight led to hallucinated report content. Includes swimlane, RAG pipeline, SOPs, evidence checklist, and leadership summary. | [`Open`](modules/governance-failure-analysis/deloitte-llm-hallucination-case/) |

---

##  Upcoming Modules (In Progress)

| Module | Focus Area | Status |
|------|------------|--------|
| **Fairness, Bias & Harm Exposure Testing Suite** | Aequitas, Fairlearn, disparity scorecards, harm modeling. | Draft |
| **Model Release Risk Governance Framework** | Tier classification → controls → sign-off workflow. | Design |
| **Continuously Monitored AI Deployment Strategy** | Drift monitoring, risk score triggers, incident escalation. | Planned |

---

##  Purpose of This Portfolio

This framework demonstrates **leadership-grade AI assurance**:
- Systems must be **traceable**, **explainable**, and **defensible**
- AI decisions must be **reviewable and accountable**
- Automation must **serve humans, not harm them**

---
modules/
  governance-failure-analysis/
    deloitte-llm-hallucination-case/
      SOPs/
        SOP-01_Prompt_Provenance_and_Logging.md
        SOP-02_Citation_and_Evidence_Verification.md
        SOP-03_RAG_Corpus_and_Retrieval_Control.md
        SOP-04_Human_in_the_Loop_and_Final_Approval.md
