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

## Spike-Specific Guidelines

### Research Focus
- Document research questions exactly as stated
- List specific areas to investigate as provided
- Include only explicitly mentioned deliverables
- Emphasize findings and reporting requirements

### Research vs Implementation
- **Research (ALLOWED):** "Investigate performance bottlenecks in the system"
- **Implementation (NOT ALLOWED):** "Fix the performance issues"

### Handling Research Scope
- **User says:** "Look into why the system is slow"
  - **Document as:** "Look into why the system is slow"
  - **Don't interpret as:** Specific areas to investigate or methodologies

## Prohibited Actions
- Suggesting research methodologies not provided
- Adding implementation details
- Inferring specific deliverables or reports
- Assuming timelines or deadlines
- Including commentary about the research
- Adding sections not in the template
- Expanding research scope beyond what's stated

## Examples of Proper Handling

### Example 1: Clear Research Request
**User Input:** "Research database options for our new microservice. Need to compare performance and costs."
**Correct Output:**
```
## Research Question:
* Research database options for our new microservice

---

## Areas to Investigate:
* Performance comparison
* Cost comparison

---

## Deliverables:
```
**Key Point:** Notice the simplified structure focused on research.

### Example 2: Vague Research Request
**User Input:** "Spike on authentication options"
**Correct Output:**
```
## Research Question:
* Authentication options

---

## Areas to Investigate:

---

## Deliverables:
```

**Remember:** The goal is accurate documentation of research requirements without assumptions or additions.

---

# Template

## Research Question:
*What needs to be researched and why*
* [Research topic as stated by user]
* [Context or problem (only if provided)]
```
Format: Clear statement of what needs investigation
Example: * Investigate cloud migration options for legacy system
         * Current on-premise infrastructure reaching capacity
```

---

## Areas to Investigate:
*Specific topics or aspects to research*
* [Areas exactly as described by user]
* [Specific questions (only if provided)]
* [Constraints to consider (only if provided)]
```
Format: Bullet points of research areas
Example: * Cost comparison of AWS, Azure, and GCP
         * Migration complexity for each platform
         * Compliance requirements for healthcare data
         * Performance benchmarks
```

---

## Deliverables:
*Expected research outputs and reports*
* [Reports or findings (only if specified)]
* [Format requirements (only if provided)]
* [Presentation needs (only if provided)]
```
Format: Specific deliverables
Example: * Comparison matrix of options
         * Executive summary with recommendations
         * Technical deep-dive document
         * Presentation for stakeholders
```