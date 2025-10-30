# Security & Compliance Objection Handling Prompt

**Who you’re talking to:** Chief Information Security Officer (CISO) or security lead.  
**Concern:** Tool requires broad access; how do we protect sensitive data and meet strict policies?

**Objective:**  
Help the seller explain controls, data handling, and compliance alignment in clear terms.

**Voice Cue (for Copilot):**  
“Use this page as context and draft a concise response to a CISO about security and compliance.”

**Talk Track (simple steps):**
1. **Acknowledge:**  
   “That’s a fair concern. Protecting sensitive data comes first.”
2. **Access & Scope:**  
   “Here’s the minimum access required and why: {{required_access_summary}}. We follow least privilege and role-based access control.”
3. **Data Handling:**  
   “We process {{data_types}}. Sensitive fields can be masked, encrypted at rest and in transit, and access is audited.”
4. **Controls & Standards:**  
   “We align to {{standards}} (for example: National Institute of Standards and Technology [NIST] 800-53, Center for Internet Security [CIS] Benchmarks, System and Organization Controls [SOC] 2). Here are the key controls relevant to you: {{control_list}}.”
5. **Customer Controls:**  
   “You keep control over keys, identity, network paths, and retention. You can restrict egress and set approval workflows.”
6. **Proof:**  
   “We can share a control mapping, a data flow diagram, and a sample audit log: {{links_or_locations}}.”
7. **Close with options:**  
   “If you need tighter boundaries, we can support {{options: private networking, customer-managed keys, on-prem, or air-gapped}}.”

**Answer format for Copilot (keep it tight):**
- 3–5 short paragraphs, no fluff  
- Include a bullet list of controls  
- End with two next steps (e.g., “review control map,” “schedule security deep dive”).


