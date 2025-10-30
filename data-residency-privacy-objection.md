# Data Residency & Privacy Objection Handling Prompt

**Audience:** Privacy officer, legal, security.  
**Concern:** Where is data stored and processed? How is personal data handled?

**Objective:**  
State location controls, retention, and privacy by design.

**Voice Cue (for Copilot):**  
“Use this page as context and draft a response on data residency and privacy.”

**Talk Track:**
1. **Residency choice:**  
   “Data can reside in {{regions}}. You choose the region and can restrict cross-region transfer.”
2. **Processing paths:**  
   “Processing occurs in {{processing_paths}}. Optional private networking and customer-managed keys.”
3. **Privacy controls:**  
   “Data minimization, masking for sensitive fields, configurable retention: {{retention_policy}}.”
4. **Requests & audit:**  
   “Support for subject access requests, audit logs, and export.”
5. **Next step:**  
   “We can share a data flow diagram and a residency statement for legal review.”

**Answer format for Copilot:**
- 2 short paragraphs + bullets  
- Avoid legal jargon; stick to facts  
- Offer documents and a review call.

**Placeholders:**
- `{{regions}}`
- `{{processing_paths}}`
- `{{retention_policy}}`
