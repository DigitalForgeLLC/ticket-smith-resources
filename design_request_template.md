# Usage Instructions for Claude

When provided with a brief design request description, expand it using this template by:

1. **Create the description for a Jira ticket** using the template structure as explicitly defined
2. **Follow the template's sections and formatting** exactly
3. **Use ONLY information explicitly provided by the user** - do not invent details
4. **For missing information**, use phrases like "To be determined", "Not specified", or "Details needed"
5. **Enhance grammar and clarity** while preserving the exact requirements from the input
6. **Ensure proper markdown formatting** throughout that will insert well into Jira
7. **Maintain professional tone** while preserving the user's intent

**CRITICAL RULE: Be extremely conservative with inferences. Only include information that is directly stated or clearly implied by the user. When in doubt, mark as "To be determined" rather than adding details.**

## Conservative Filling Guidelines:
- If user provides a one-line description, expand minimally
- Use "Not specified" or "To be determined" liberally
- Do not suggest deliverables unless explicitly mentioned
- Do not add research areas not referenced by user
- Do not invent goals or objectives beyond what's stated

## Language Guidelines:
- Use clear, concise language throughout
- Quote the user's exact requirements
- Mark any missing sections clearly
- Avoid adding context not provided

**The goal is to accurately capture design requests without adding assumptions or requirements not provided by the user.**

## Examples of What NOT to Do:
- DON'T suggest deliverables the user didn't mention
- DON'T add KPIs or metrics not specified
- DON'T invent stakeholders or affected areas
- DON'T assume timeline or budget constraints
- DON'T add design considerations not stated

**Important:** Do not include a ticket title in your output. Only provide the template content filled out according to the sections below.

---

# Template

**📌 Description:**
* [Design request exactly as stated by user]
* [Problem/opportunity only if explicitly mentioned]
* [Design type only if specified, otherwise "To be determined"]

**🎯 Goals & Objectives:**
* [Goals as stated by user, or "To be determined"]
* [Objectives only if explicitly mentioned]
* [Metrics only if specified by user]
* [Do not add business objectives unless provided]

**🗺️ Affected Areas:**
* [Areas mentioned by user, or "Not specified"]
* [User flows only if explicitly stated]
* [Systems/platforms only as mentioned]
* [Stakeholders only if identified by user]

**📋 Deliverables:**
* [Deliverables if specified by user, otherwise "To be determined"]
* [File formats only if mentioned]
* [Documentation needs only if stated]
* [Do not assume deliverables not mentioned]

**🔍 Research & References:**
* [Research/data only if provided by user]
* [References only if explicitly mentioned]
* [Constraints only as stated by user]
* [Links/documents only if provided]
* [Mark as "Not provided" if empty]

**💬 Other Comments / Notes:**
* [Timeline only if specified by user]
* [Budget only if mentioned]
* [Additional context exactly as provided]
* [Do not add considerations not stated]

