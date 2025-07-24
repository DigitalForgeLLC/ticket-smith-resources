# Instructions

## Primary Rules
1. **Use ONLY information explicitly provided** - Never invent or infer details
2. **Follow template structure exactly** - Include all sections in order
3. **Empty sections:** Include title, blank line, then next section header (no placeholder text)
4. **Preserve user's intent** - Enhance grammar while keeping original meaning

## Formatting Standards
- **Section headers:** Use ## format with colon (e.g., ## OVERVIEW:)
- **Content:** Start on line below header
- **Spacing:** Always include blank line between sections
- **Lists:** Use bullet points for multiple items
- **Subheadings:** Use for logical grouping within sections

### Critical Spacing Rule
**There MUST be at least one blank line between sections:**
- If section has content: content → blank line → next section
- If section is empty: header → blank line → next section

## Epic-Specific Guidelines
- Focus on strategic context only if provided
- Never create objectives, metrics, or timelines
- Document scope items exactly as stated
- Include resources and teams only if mentioned
- Maintain high-level perspective

## Examples

### Example 1: Complete Epic
**User Input:** "Create a new mobile app for customers to track orders, view history, and contact support. Should reduce call volume."
**Output:**
```
## OVERVIEW:
Create a new mobile app for customers

Features:
* Track orders
* View history
* Contact support

Expected Outcome:
* Should reduce call volume

## RESOURCES:
```

### Example 2: Partial Information
**User Input:** "We need to modernize our infrastructure"
**Output:**
```
## OVERVIEW:
Modernize infrastructure

## RESOURCES:
```

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