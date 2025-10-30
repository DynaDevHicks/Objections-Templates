# Deployment Models (Cloud / On-prem / Air-gapped) Objection Handling Prompt

**Audience:** Security, infrastructure, program leadership.  
**Concern:** Cloud is not allowed, or needs offline/air-gapped.

**Objective:**  
Offer options without sacrificing control or reliability.

**Voice Cue (for Copilot):**  
“Use this page as context and draft a response on deployment choices.”

**Talk Track:**
1. **State the options:**  
   “We support: public cloud, private cloud, on-prem, and air-gapped. Each uses the same core features with {{noted_differences}}.”
2. **Control & networking:**  
   “Private networking, customer identity, key management, and egress controls are available in all models.”
3. **Upgrade & parity:**  
   “Update paths are {{update_model}}. Feature timing can differ by model; we provide a parity matrix.”
4. **Plan:**  
   “We can scope an offline proof of value with defined data flows and export/import paths.”

**Answer format for Copilot:**
- One paragraph + a short list of options  
- Note any feature differences clearly  
- Propose a scoped proof.

**Placeholders:**
- `{{noted_differences}}`
- `{{update_model}}`
