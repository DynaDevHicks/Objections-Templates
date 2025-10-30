# Support Model (24×7 / Geography / SLAs) Objection Handling Prompt

**Audience:** Operations leadership, program manager.  
**Concern:** Need confirmed 24×7 support, response times, and geographic restrictions (for example, United States–only).

**Objective:**  
Clarify coverage, response targets, and geo restrictions.

**Voice Cue (for Copilot):**  
“Use this page as context and draft a response on support coverage.”

**Talk Track:**
1. **Coverage:**  
   “We offer {{support_hours}} with {{channels}}. Severity definitions and escalation paths are documented.”
2. **Response Targets:**  
   “Initial response: Sev1 {{sev1_target}}, Sev2 {{sev2_target}}; updates every {{update_cadence}} until resolved.”
3. **Geography:**  
   “We can restrict support staff to {{geo_scope}} if required. Confirm via contract addendum.”
4. **Evidence:**  
   “Sample SLAs, runbooks, and on-call calendar available for review.”
5. **Next step:**  
   “Let’s align on severity matrix and confirm the geo scope in writing.”

**Answer format for Copilot:**
- Short paragraph + bullet list of targets  
- Clear numbers; no marketing fluff  
- End with two concrete next steps.

**Placeholders:**
- `{{support_hours}}`
- `{{channels}}`
- `{{sev1_target}}`
- `{{sev2_target}}`
- `{{update_cadence}}`
- `{{geo_scope}}`
