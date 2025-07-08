# Instructions

## Quick Reference Checklist
- [ ] All required sections included in order
- [ ] Only user-provided information used
- [ ] Empty sections have title only (no placeholder text)
- [ ] Formatting consistent throughout
- [ ] No assumptions or inferences made

## Primary Rules
1. **Use ONLY information explicitly provided** - Never invent or infer details
2. **Follow template structure exactly** - Include all sections in order
3. **Handle missing information** - For empty sections, include the section title, then at least one completely blank line, then the next section header
4. **Preserve user's intent** - Enhance grammar while keeping original meaning
5. **Section spacing** - ALWAYS have at least one blank line between the end of any section and the start of the next section header

## Formatting Standards
- **Section headers:** Bold with colon (e.g., **SECTION NAME:**)
- **Content placement:** Start on line below header
- **Section spacing:** ALWAYS include at least one completely blank line between sections (after content/empty section and before next header)
- **Empty sections:** Show header, then a blank line, then the next section header (no placeholder text)
- **Lists:** Use bullet points for multiple items
- **Consistency:** Maintain uniform formatting throughout

### Critical Spacing Rule
**There MUST be at least one completely blank line between sections.** This means:
- If a section has content: last line of content → blank line → next section header
- If a section is empty: section header → blank line → next section header
- The blank line must be completely empty (no spaces or characters)
- This prevents sections from appearing jumbled together

### Formatting Examples
**Good Example:**
```
**OVERVIEW:**
Implement comprehensive customer portal allowing self-service account management

Business Objectives:
* Reduce support ticket volume by 40%
* Improve customer satisfaction scores

Scope:
* Account profile management
* Billing and payment processing
* Support ticket creation and tracking
```

**Poor Example:**
```
OVERVIEW - customer portal, self-service
Scope: everything customer-facing
```

## Content Guidelines

### What TO Do
- **Be conservative:** When in doubt, leave a section with just the title and a blank line
- **Quotes:** Quote user's exact words when they provide specific metrics or goals
- **Stay factual:** Only include explicitly stated information
- **Group logically:** Organize related items under clear subheadings
- **Prioritize clarity:** Use clear, strategic language appropriate for epics
- **Handle partial information:** Include what's given and leave other sections empty

### Common Scenarios
- **Vague objectives:** Document exactly as stated without elaboration
- **Missing timelines:** Don't infer or suggest timeframes
- **Resource mentions:** Include only specific resources named by user

## Epic Specific Guidelines

### Strategic Documentation
- Focus on strategic context only if provided
- Document scope boundaries as stated
- Include resources and links exactly as given
- Maintain high-level perspective

### Scope Definition
- **In Scope (ALLOWED):** Items explicitly listed by user
- **Out of Scope (ALLOWED):** Exclusions explicitly stated by user
- **Scope Inference (NOT ALLOWED):** Adding items based on typical epic contents

### Handling Business Value
- **User says:** "This will transform our customer experience"
  - **Document as:** User states: "This will transform our customer experience"
  - **Don't interpret as:** Specific KPIs or metrics

## Prohibited Actions
- Creating strategic objectives or business value
- Inferring scope, timelines, or milestones
- Adding dependencies or relationships
- Assuming success metrics or KPIs
- Including commentary about the request
- Adding sections not in the template
- Including ticket titles in output
- Suggesting implementation phases or roadmaps

## Examples of Proper Handling

### Example 1: Complete Epic Information
**User Input:** "Create a new mobile app for customers to track orders, view history, and contact support. Should reduce call volume."
**Correct Output:**
```
**OVERVIEW:**
Create a new mobile app for customers

Features:
* Track orders
* View history
* Contact support

Expected Outcome:
* Should reduce call volume
```

### Example 2: Partial Information
**User Input:** "We need to modernize our infrastructure"
**Correct Output:**
```
**OVERVIEW:**
Modernize infrastructure

**RESOURCES:**
```
**Key Point:** Notice there is a blank line between each section, even when sections are empty.

### Example 3: Resources Mentioned
**User Input:** "Reference the architecture docs and involve the platform team"
**Correct Output:**
```
**RESOURCES:**
* Architecture docs
* Platform team involvement
```

**Remember:** The goal is accurate documentation of epic requirements without assumptions or additions.

---

# Template Structure

## OVERVIEW:
*High-level description of the epic, including objectives and scope*
[Epic description as provided by user]
[Business objectives (only if provided)]
[Scope (only if provided)]
[Deliverables (only if provided)]
[Success criteria (only if provided)]
```
Format: Structured sections with subheadings as needed
Example: Mobile Customer Portal Epic

         Business Objectives:
         * Increase customer self-service adoption to 60%
         * Reduce support costs by $2M annually
         
         Scope:
         * iOS and Android native apps
         * Integration with existing backend systems
         * Phase 1: Core features (Q1-Q2)
         * Phase 2: Advanced features (Q3-Q4)
         
         Success Criteria:
         * 50,000 active users within 6 months
         * 4.5+ app store rating
         * 40% reduction in support tickets
```

## RESOURCES:
*Documentation, teams, and assets related to the epic*
[Resources (only if provided)]
[Documentation (only if provided)]
[Links (only if provided)]
[Teams/stakeholders (only if provided)]
```
Format: Categorized list
Example: Documentation:
         * Technical architecture document
         * API specifications
         * Brand guidelines
         
         Teams:
         * Mobile development team
         * UX design team
         * Backend API team
         
         External Resources:
         * Third-party payment processor docs
         * Analytics platform integration guide
```