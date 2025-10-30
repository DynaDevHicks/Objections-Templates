# Performance & Scale Objection Handling Prompt

**Audience:** Platform owner, Site Reliability Engineering (SRE), or operations lead.  
**Concern:** Will this scale? What’s the overhead?

**Objective:**  
Explain scale limits, overhead expectations, and test paths.

**Voice Cue (for Copilot):**  
“Use this page as context and draft a response on performance and scale.”

**Talk Track:**
1. **Set the baseline:**  
   “Target footprint is {{overhead_range}} CPU / {{memory_range}} RAM per host/service under typical load.”
2. **Scale pattern:**  
   “We support {{scale_units}} with shard/cluster options and horizontal growth. Control plane and data plane can separate.”
3. **Resilience:**  
   “High availability across {{zones_regions}} with backpressure, retries, and queueing.”
4. **Benchmark/Proof:**  
   “In tests, we handled {{events_per_sec}} / {{hosts_services}}. Here’s a public load profile: {{benchmark_link}}.”
5. **Plan a pilot:**  
   “Let’s run a sizing workshop and a capped pilot with telemetry to validate overhead.”

**Answer format for Copilot:**
- One paragraph + a short bullet list  
- Include concrete numbers where possible  
- End with a pilot proposal.

**Placeholders:**
- `{{overhead_range}}`
- `{{memory_range}}`
- `{{scale_units}}`
- `{{zones_regions}}`
- `{{events_per_sec}}`
- `{{hosts_services}}`
- `{{benchmark_link}}`
