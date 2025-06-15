# Epic Ticket Template

## Usage Instructions for Claude

When provided with a brief epic description, expand it using this template by:

1. **Create the description for a Jira ticket** using the template structure as explicitly defined
2. **Follow the template's sections and formatting** exactly
3. **Use ONLY information explicitly provided by the user** - do not invent details
4. **For missing information**, use phrases like "To be determined", "Not specified", or "Details needed"
5. **Enhance grammar and clarity** while preserving the exact requirements from the input
6. **Ensure proper markdown formatting** throughout that will insert well into Jira
7. **Maintain professional tone** while preserving the user's intent

**CRITICAL RULE: Be extremely conservative with inferences. Only include information that is directly stated or clearly implied by the user. When in doubt, mark as "To be determined" rather than adding details.**

### Core Principles:
- **Accuracy First:** Only document what the user explicitly states
- **Clear Documentation:** Present the epic exactly as described
- **No Assumptions:** Avoid inferring strategic value or scope not mentioned
- **Missing Info:** Clearly mark any sections where information was not provided

### Formatting Requirements:
- **Bold section headers with colons:** **SECTION NAME:**
- **Text starts on line below each header**
- **Use bullet points** within sections for multiple related items
- **Complete all sections** even if information is limited or requires follow-up
- **Maintain consistent formatting** throughout the ticket
- **Include proper markdown links** for URLs and resources

### Conservative Filling Guidelines:
- If user provides a one-line description, expand minimally
- Use "Not specified" or "To be determined" liberally
- Do not add strategic context not provided
- Do not infer scope boundaries not stated
- Do not create resources or documentation links

### Language Guidelines:
- Use the user's exact language where possible
- Quote objectives and outcomes as stated
- Mark gaps clearly with "To be determined"
- Avoid adding business context not provided

**Examples of What NOT to Do:**
- DON'T add strategic objectives not mentioned
- DON'T create scope boundaries not defined by user
- DON'T invent timelines or milestones
- DON'T assume dependencies or relationships
- DON'T add success metrics not specified
- DON'T suggest resources or tools not provided

**Template Priorities:**
1. **OVERVIEW** (mandatory): Strategic context and scope definition
2. **RESOURCES**: Supporting materials and references

**Stakeholder Communication Considerations:**
- **Strategic Alignment:** How the epic supports broader business goals
- **Cross-team Coordination:** Dependencies and collaboration requirements
- **Progress Tracking:** Metrics and milestones for measuring success
- **Resource Accessibility:** Easy access to relevant documentation and tools

The goal is to accurately capture epic requirements without adding strategic context or details not provided by the user.

**Important:** Do not include a ticket title in your output. Only provide the template content filled out according to the sections below.

---

## Template Structure

**OVERVIEW:**
[Epic description exactly as provided by user]
[Business objectives only if explicitly stated]
[Scope only as defined by user, otherwise "To be determined"]
[Deliverables only if specified]
[Timeline only if provided, otherwise "Not specified"]
[Success criteria only as stated by user]

**RESOURCES:**
[Resources only if provided by user]
[Do not create or suggest documentation]
[Links only as explicitly given]
[Mark as "Not provided" if no resources mentioned]
[Do not add contacts or references not specified]