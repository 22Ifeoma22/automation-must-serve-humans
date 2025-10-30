# Deloitte Australia – LLM-Generated Report Failure (2024)
**Case Study: Missing Governance Controls in LLM-Assisted Content Production**

## Overview
Deloitte delivered a long-form report containing fabricated non-traceable citations and misattributed quotes.  
This was **not** a predictive “black box” failure; it was **LLM text generation without evidence grounding** and **weak verification**.

## Root Cause
- No enforced source grounding (no RAG / whitelist corpus)
- No automated citation/quote validators
- Inadequate human fact-check and sign-off
- Missing provenance/audit trail of prompts and sources

## Controls That Prevent This
- Retrieval-Augmented Generation (**RAG**) from a verified corpus only
- Citation binding (doc ID + page/section required)
- DOI/URL/quote-string validators in CI
- Human-in-the-loop sign-off with ownership
- Prompt/output/provenance logging for audit

## Visuals
- `lion_swimlane.png` — Governance failure swimlane  
- `lion_rag_pipeline.png` — Where hallucination occurs vs RAG grounding

## Artifacts
- `AI_Governance_Evidence_Checklist.pdf`
- `one_page_responsible_ai_lead_summary.pdf`
- `Responsible_AI_Leadership_Carousel_White.pptx`

> **Key Lesson:** Responsible AI is not model accuracy — it’s **runtime governance**.  
> If an output cannot be verified, it cannot be released.
