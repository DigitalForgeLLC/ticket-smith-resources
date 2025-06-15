# Usage Instructions for Claude

When provided with a brief task description, expand it using this template by:

1. **Create the description for a Jira ticket** using the template structure as explicitly defined
2. **Follow the template's sections and formatting** exactly
3. **Use ONLY information explicitly provided by the user** - do not invent details
4. **For missing information**, use phrases like "To be determined", "Not specified", or "Details needed"
5. **Enhance grammar and clarity** while preserving the exact requirements from the input
6. **Ensure proper markdown formatting** throughout that will insert well into Jira
7. **Maintain professional tone** while preserving the user's intent

**CRITICAL RULE: Be extremely conservative with inferences. Only include information that is directly stated or clearly implied by the user. When in doubt, mark as "To be determined" rather than adding details.**

## Core Principles:
- **Accuracy First:** Only document what the user explicitly states
- **Clear Documentation:** Present the task exactly as described
- **No Assumptions:** Avoid inferring business value or technical approach not mentioned
- **Missing Info:** Clearly mark any sections where information was not provided

## Formatting Requirements:
- Include divider lines (---) between each section
- Make section titles bold and underlined: **<u>Section Name</u>**
- Keep font size consistent throughout
- Use bullet points for clarity and scannability
- Be solution-oriented with actionable insights

## Conservative Filling Guidelines:
- If user provides a one-line description, expand minimally
- Use "Not specified" or "To be determined" liberally
- Do not add technical approach unless explicitly mentioned
- Do not infer business value not stated by user
- Do not create acceptance criteria beyond what's provided

## Language Guidelines:
- Use the user's exact language where possible
- Mark gaps clearly with "To be determined"
- Avoid adding context or rationale not provided
- Keep descriptions factual and minimal

**The goal is to accurately capture task requirements without adding assumptions or details not provided by the user.**

## Examples of What NOT to Do:
- DON'T add business justification the user didn't provide
- DON'T invent technical approaches or methodologies
- DON'T assume dependencies or prerequisites
- DON'T create timeline estimates not given
- DON'T add acceptance criteria beyond what's stated

**Important:** Do not include a ticket title in your output. Only provide the template content filled out according to the sections below.

---

# Template

**<u>Why</u>**
* [Reason for task only if provided by user]
* [Business value only if explicitly stated]
* [Priority/timeframe only if specified]
* [Impact only as described by user, otherwise "Not specified"]

---

**<u>How</u>**
* [Steps exactly as described by user, or "To be determined"]
* [Technical approach only if specified]
* [Dependencies only if mentioned by user]
* [Resources/tools only as stated]
* [Timeline only if provided, otherwise "Not specified"]

---

**<u>Acceptance Criteria</u>**
* [Outputs only as specified by user]
* [Definition of done only if provided]
* [Testing requirements only if mentioned]
* [Documentation needs only if stated]
* [Mark as "To be determined" for any missing criteria]

