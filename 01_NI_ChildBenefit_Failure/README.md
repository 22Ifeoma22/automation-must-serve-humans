
# Case Study 01 - Northern Ireland Child Benefit Suspension Failure
 Published |  Real-World Harm |  Human Rights Violation

346 parents in Northern Ireland had their child benefit payments **suspended automatically** after returning home from a holiday through Dublin airport.
The AI-driven fraud detection system misclassified these trips as signs of **permanent emigration**.

This resulted in sudden withdrawal of essential income for families with children  
**without warning, investigation, or a human review path to correct the error.**

##  Root Governance Failures
| Issue | What Went Wrong | Required Control |
|------|----------------|----------------|
| Misinterpreted travel signals | Model assumed travel via Ireland = emigration | Context & scope validation |
| No exception handling | Cross-border travel common in NI | Scenario & edge-case testing |
| Absence of human oversight | Full automation deployed on high-risk decisions | Human-in-the-loop escalation |
| Late incident response | Harm detected only after public complaints | Continuous monitoring + KPIs |

 **Key Governance Insight:**  
 In the NI case, individuals did not lose their rights, the system was designed so those rights could not be exercised.  

**Human Contestability Breakdown:**  
Although rights under GDPR Article 22 technically existed, individuals had **no practical way** to challenge the automated decision.  
Because the system did not provide transparency, notification, or a human review path, the right to contest became **unenforceable in practice** — making the automation **unlawful by default** under GDPR Article 22.

Once transparency and human-in-the-loop pathways failed, protection shifted from the individual to the regulator, making the automation unlawful by default under **GDPR Article 22**.

##  Impact on Human Rights
- Financial hardship for vulnerable families  
- Risk of hunger and housing instability  
- Damage to public trust in government systems

##  Coming Next
- Case Study 02 DWP - Fraud AI False Positives  
- Governance Remediation Plans  
- Responsible AI Oversight Controls (ISO 42001 alignment)

 **Follow this repository** to be the first to access updates.
