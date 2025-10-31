# SOP-01 (Preview) — Human Verification Before Benefit Suspension
**Status:** Partial Release (More steps to follow)  
**Purpose:** Ensure no family’s benefits are suspended due to automated misclassification without **mandatory human review**, context assessment, and hardship checks.

---

## 1. Objective
Automated classification systems must **not** trigger benefit suspension on their own.  
A trained Case Review Officer must validate the case details and confirm that the classification is correct **and not likely to create unnecessary or disproportionate harm**.

This prevents:
- Wrongful suspension of payments
- Financial and emotional harm to families
- Loss of trust in government services

---

## 2. When This SOP Applies
This SOP must be followed **whenever**:
- A system flags a person as **“non-resident”**, **“abroad”**, or **“ineligible”** due to travel or address pattern detection.
- The classification will result in **stopping, suspending, or reducing** Child Benefit or similar entitlements.

---

## 3. Required Inputs Before Review
The Case Review Officer must have the following available:

| Input | Source | Purpose |
|------|--------|---------|
| Travel event history | System log | To verify travel pattern reasoning |
| Claimant family status | Benefits system | To assess dependency and hardship impact |
| Explanation trace (why the system flagged the case) | System-generated | To ensure transparency and auditability |
| Contact history | CRM / Case notes | To determine if clarification was already requested |

> **If the explanation trace is not available → the case cannot proceed.**  
This is a governance requirement, not a suggestion.

---

## 4. Human Verification Step (High-Level)
The Case Review Officer must determine:

| Verification Question | Pass Condition | Fail Condition |
|---|---|---|
| Was the travel classification correct? | Evidence supports flag | Evidence unclear or insufficient |
| Would suspension cause avoidable harm? | No foreseeable harm | Risk of hardship or distress |
| Has the family been contacted first? | Yes | No |

If **any** item fails →  
**SUSPENSION MUST NOT PROCEED.**  
The case is escalated to **Manual Review Queue**.

---

> **This is a preview release.**
> Detailed review sequences, data checks, written justification templates,  
> and escalation routing will be added in **SOP-01 (Full Version)**.

---

**Next Release:**  
**Swimlane View — Where the Human Review Sits in the Flow**  
(Will be added to `/visuals/` and linked here.)

---
