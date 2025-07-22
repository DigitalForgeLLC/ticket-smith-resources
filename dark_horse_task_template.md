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
3. **Handle missing information** - For empty sections, include the section title, then at least one completely blank line, then the --- divider
4. **Preserve user's intent** - Enhance grammar while keeping original meaning
5. **Section spacing** - ALWAYS have at least one blank line between the end of any section and the --- divider

## Formatting Standards
- **Section headers:** Use header 2 format (##) with colon (e.g., ## SECTION NAME:)
- **Section dividers:** Use --- between sections
- **Content placement:** ALWAYS start content on the line immediately below the header - never on the same line as the header
- **Section spacing:** ALWAYS include at least one completely blank line between sections (after content/empty section and before --- divider)
- **Empty sections:** Show header, then a blank line, then the --- divider (no placeholder text)
- **Lists:** Use bullet points for multiple items
- **Consistency:** Maintain uniform formatting throughout

### Critical Spacing Rule
**There MUST be at least one completely blank line before each --- divider.** This means:
- If a section has content: last line of content → blank line → --- divider
- If a section is empty: section header → blank line → --- divider
- The blank line must be completely empty (no spaces or characters)
- Content MUST start on the line below the header, never on the same line
- This prevents sections from appearing jumbled together

### Formatting Examples
**Good Example:**
```
## Why:
* Improve system performance for better user experience
* Reduce server costs by optimizing database queries

## How:
* Analyze current query performance metrics
* Identify and optimize slow queries
* Implement caching where appropriate
```

**Poor Example:**
```
Why: performance, costs
How - optimize queries
```

## Content Guidelines

### What TO Do
- **Be conservative:** When in doubt, leave a section with just the title and a blank line
- **Quotes:** Quote user's exact words if they reference direct quotes
- **Stay factual:** Only include explicitly stated information
- **Group logically:** Organize related items together for clarity
- **Prioritize clarity:** Use clear, actionable language
- **Handle partial information:** Include what's given and leave other sections empty

### Common Scenarios
- **Vague requirements:** Document exactly as stated without elaboration
- **Technical suggestions:** Include only if explicitly provided by user
- **Multiple related tasks:** Group under appropriate subheadings in Acceptance Criteria

## Task-Specific Guidelines

### Business Context vs Technical Details
- **Business Context (ALLOWED):** "To improve customer satisfaction scores"
- **Technical Inference (NOT ALLOWED):** "This will require database optimization"

### Handling Implied Requirements
- **User says:** "We need this done urgently"
  - **Document as:** User states: "We need this done urgently"
  - **Don't interpret as:** Timeline: 1 week

## Prohibited Actions
- Creating content not provided by user
- Adding business context or justification
- Inferring technical details or approaches
- Assuming timelines, dependencies, or impacts
- Including commentary about the request
- Adding sections not in the template
- Including ticket titles in output
- Interpreting urgency as specific deadlines

## Examples of Proper Handling

### Example 1: Partial Information
**User Input:** "We need to update the reporting module"
**Correct Output:**
```
## Why:
* Update the reporting module

---

## How:

---

## Acceptance Criteria:
```
**Key Point:** Notice there is a blank line before each --- divider, even for empty sections.

### Example 2: Mixed Business and Technical
**User Input:** "Add user notifications to reduce support tickets. Use email and in-app alerts."
**Correct Output:**
```
## Why:
* Reduce support tickets

## How:
* Use email and in-app alerts
```

**Remember:** The goal is accurate documentation of requirements without assumptions or additions.

---

# Template

## Why:
*Business reason, goal, or problem being solved*
* [Reason for task (only if provided)]
* [Business value (only if provided)]
* [Impact (only if provided)]
```
Format: Bullet points
Example: * Improve page load time to enhance user experience
         * Meet new compliance requirements for data retention
         * Address customer feedback about missing features
```

---

## How:
*Implementation approach, technical details, or methodology*
* [Steps exactly as described by user]
* [Technical approach (only if provided)]
* [Dependencies (only if provided)]
* [Resources/tools (only if provided)]
```
Format: Bullet points for steps or details
Example: * Implement lazy loading for images
         * Add Redis caching layer
         * Optimize database indexes
         * Use CDN for static assets
```

---

## Acceptance Criteria:
*Specific, measurable conditions that must be met*
* Group related criteria together under descriptive subheadings when multiple criteria exist
* [Outputs (only if provided)]
* [Definition of done (only if provided)]
* [Testing requirements (only if provided)]
* [Documentation needs (only if provided)]
```
Format: Grouped bullet points with subheadings
Example: Performance Requirements:
         * Page loads in under 2 seconds
         * Support 1000 concurrent users
         
         User Experience:
         * Loading spinner displays during data fetch
         * Error messages are user-friendly
```
