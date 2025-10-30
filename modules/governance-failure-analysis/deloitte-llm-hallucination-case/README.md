# Deloitte Australia – LLM-Generated Report Failure (2024)
**Case Study: Missing Governance Controls in LLM-Assisted Content Production**

## Overview
Deloitte delivered a long-form report containing fabricated non-traceable citations and misattributed quotes.  
This was **not** a predictive “black box” failure; it was **LLM text generation without evidence grounding** and **weak verification**.

## Root Cause
- No enforced source grounding (no RAG  whitelist corpus)
- No automated citation quote validators
- Inadequate human fact-check and sign-off
- Missing provenance audit trail of prompts and sources

## Controls That Prevent This
- Retrieval-Augmented Generation (**RAG**) from a verified corpus only
- Citation binding (doc ID  and page section required)
- DOI/URL/quote-string validators in CI
- Human-in-the-loop sign-off with ownership
- Prompt output/provenance logging for audit
  
## Where the LLM Failed
This failure was not due to the model being unpredictable, it was due to the absence of governance around it.
- **No Source Verification** → The model generated confident statements and citations that were not grounded in traceable data.
- **No Human-in-the-Loop Assurance** → Output was accepted without structured review or validation before use.
- **Weak Accountability Mapping** → Ownership for checking and approving generated content was unclear.
- **No Provenance Logging** → There was no auditable record of prompts, sources, or reasoning steps leading to the final output.

This was **not** a “model hallucination” issue.  
It was a **governance failure** arising from missing controls and oversight.

This failure was *structurally predictable* based on known LLM behavior. Therefore, accountability rests with the governance design, not the model.
> **What is foreseeable must be governed.**

### Put Simply
| Technology        | Nature of Risk                                      | Predictability                               | Accountability Requirement                                   |
|-------------------|-----------------------------------------------------|-----------------------------------------------|--------------------------------------------------------------|
| **LLM**           | Confident but incorrect output (hallucination)      | **Foreseeable** (built into architecture)     | **Human oversight + source verification is mandatory**       |
| **Traditional ML**| Performance degradation due to data/environment change | **Unforeseen until monitored**              | **Drift monitoring + bias checks are mandatory**             |

> **LLM risk is inherent. ML risk is emergent. Governance must match the failure mode.**

## AI Policy – Introduction (Public Overview)

This policy defines the principles and operating standards for the responsible development, deployment, and oversight of AI systems.
It establishes how AI must be managed to ensure:
- Compliance with regulatory and ethical requirements
- Traceability and accountability for system outcomes
- Fair, transparent, and explainable decision-making
- Safe, secure, and monitored deployment, including post-production oversight

This introduction is provided to demonstrate the governance approach and structural intent.
The full operational policy (including workflows, controls, escalation, assurance testing, and audit mechanisms) is available by request for organisations building or maturing their Responsible AI programs.

## Visuals
- `lion_swimlane.png`  Governance failure swimlane  
- `lion_rag_pipeline.png`  Where hallucination occurs vs RAG grounding

## Artifacts
- `AI_Governance_Evidence_Checklist.pdf`
- `one_page_responsible_ai_lead_summary.pdf`
- `Responsible_AI_Leadership_Carousel_White.pptx`

> **Key Lesson:** Responsible AI is not model accuracy  it’s **runtime governance**.  
> If an output cannot be verified, it cannot be released.
