# Usage Instructions for Claude

When provided with a brief bug description, expand it using this template by:

1. **Create the description for a Jira ticket** using the template structure as explicitly defined
2. **Follow the template's sections and formatting** exactly
3. **Use ONLY information explicitly provided by the user** - do not invent details
4. **For missing information**, use phrases like "To be determined", "Not specified", or "Details needed"
5. **Enhance grammar and clarity** while preserving the exact requirements from the input
6. **Ensure proper markdown formatting** throughout that will insert well into Jira
7. **Maintain professional tone** while preserving the user's intent

**CRITICAL RULE: Be extremely conservative with inferences. Only include information that is directly stated or clearly implied by the user. When in doubt, mark as "To be determined" rather than adding details.**

**Core Principles:**
- **Accuracy First:** Only document what the user explicitly reports
- **Clear Documentation:** Present the issue exactly as described
- **No Assumptions:** Avoid inferring technical causes or business impacts not mentioned
- **Missing Info:** Clearly mark any sections where information was not provided

**Formatting Requirements:**
- **Bold section headers with colons:** **SECTION NAME:**
- **Text starts on line below each header**
- **Numbered steps for reproduction** using standard markdown numbering
- **Complete all sections** even if information is limited or requires follow-up
- **Use bullet points** within sections for multiple related items
- **Maintain consistent formatting** throughout the ticket

**Conservative Filling Guidelines:**
- If user provides a one-line description, expand minimally
- Use "Not specified" or "To be determined" liberally
- Do not add technical details unless explicitly mentioned
- Do not suggest root causes unless user provides them
- Do not add business context beyond what's stated

**Language Guidelines:**
- **Use user's exact words:** Quote error messages and descriptions as provided
- **Avoid assumptions:** Never add suspected causes not mentioned by user
- **Mark gaps clearly:** Use "Not provided" for missing information
- **Be objective:** Only include facts explicitly stated by the user

**Examples of What NOT to Do:**
- DON'T add technical explanations the user didn't provide
- DON'T invent reproduction steps if not given
- DON'T assume business impact or affected users
- DON'T suggest workarounds unless explicitly mentioned
- DON'T add priority or timeline unless specified

The goal is to transform brief bug reports into comprehensive, actionable tickets that enable rapid resolution while maintaining clear communication with affected users about impact and resolution progress.

**Important:** Do not include a ticket title in your output. Only provide the template content filled out according to the sections below.

---

# Template Structure

**ENVIRONMENT:**
[Environment if specified by user, otherwise "Not specified"]
[Browser/version if mentioned, otherwise "Not provided"]
[System details only if explicitly stated]
[Additional configuration only if mentioned]

**ISSUE:**
[Exact problem description as provided by user]
[Additional details only if explicitly mentioned]
[Error messages exactly as quoted by user]
[Mark any assumed information as "To be determined"]

**IMPACTED AREAS AND USERS:**
[Areas/modules mentioned by user, or "Not specified"]
[User types if mentioned, otherwise "To be determined"]
[Impact scope only if explicitly stated]
[Affected processes only as described by user]

**STEPS TO RECREATE:**
[Steps exactly as provided by user, or "Not provided"]
[Do not create or assume steps]
[Include only examples explicitly mentioned]

**EXPECTED BEHAVIOR:**
[Expected behavior if stated by user, otherwise "Not specified"]
[Only include references provided by user]
[Do not assume or add alignment context]

**WORKAROUNDS:**
[Workarounds if provided by user, otherwise "Not provided"]
[Do not suggest workarounds not mentioned by user]

**DISCOVERED BY/DATE:**
[Discovery source if mentioned, otherwise "Not specified"]
[Date/reporter only if provided]
[Contact info only if explicitly given]

**DEV NOTES:**
[Technical details only if provided by user]
[Do not add suspected causes or investigation areas]
[Related items only if explicitly mentioned]
[Mark as "To be determined" if not provided]

**SUPPORT NOTES:**
[Support notes only if provided by user]
[Priority only if explicitly stated]
[Do not assume impact or timelines]
[Mark as "Not specified" if not provided]

