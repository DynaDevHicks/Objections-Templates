# Pricing & Cost Objection Handling Prompt

**Who you’re talking to:** Procurement lead, finance, or budget owner.  
**Concern:** Cost is too high or unclear.

**Objective:**  
Frame value, clarify scope, and offer cost control levers.

**Voice Cue (for Copilot):**  
“Use this page as context and draft a value-focused response to a cost concern.”

**Talk Track:**
1. **Acknowledge:**  
   “Budget pressure is real. Let’s match scope to outcomes.”
2. **Tie to outcomes:**  
   “Primary goals: {{customer_outcomes}}. The cost model aligns to these outcomes, not just raw usage.”
3. **Cost Controls:**  
   “Levers include tiering, usage caps, alerting, and phased rollout. Example: {{cost_control_example}}.”
4. **ROI Proof:**  
   “Teams reduce {{time_saved}}, avoid {{risk_or_outage_cost}}, and improve {{kpi}}. Case example: {{reference_or_benchmark}}.”
5. **Right-size the plan:**  
   “We can start with {{minimal_viable_scope}} and expand with proof.”

**Answer format for Copilot:**
- 2 short paragraphs + a bullet list of cost controls  
- Include one quantified ROI anchor  
- Offer a phased plan with a checkpoint.

**Placeholders:**
- `{{customer_outcomes}}`
- `{{cost_control_example}}`
- `{{time_saved}}`
- `{{risk_or_outage_cost}}`
- `{{kpi}}`
- `{{reference_or_benchmark}}`
- `{{minimal_viable_scope}}`
