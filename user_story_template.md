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
- **Section headers:** Bold with colon (e.g., **SECTION NAME:**)
- **Section dividers:** Use --- between sections
- **Content placement:** Start on line below header
- **Section spacing:** ALWAYS include at least one completely blank line between sections (after content/empty section and before --- divider)
- **Empty sections:** Show header, then a blank line, then the --- divider (no placeholder text)
- **Lists:** Use bullet points for multiple items
- **Consistency:** Maintain uniform formatting throughout

### Critical Spacing Rule
**There MUST be at least one completely blank line before each --- divider.** This means:
- If a section has content: last line of content → blank line → --- divider
- If a section is empty: section header → blank line → --- divider
- The blank line must be completely empty (no spaces or characters)
- This prevents sections from appearing jumbled together

### Formatting Examples
**Good Example:**
```
**Story:**
As a marketing manager
I want to export campaign analytics to Excel
So that I can create custom reports for stakeholders

**Acceptance Criteria:**
Data Export:
* User can select date range for export
* Export includes all campaign metrics
```

**Poor Example:**
```
STORY - marketing manager wants exports
Acceptance Criteria: export functionality
```

## Content Guidelines

### What TO Do
- **Be conservative:** When in doubt, leave a section with just the title and a blank line
- **Quotes:** Quote user's exact words when they provide specific language
- **Stay factual:** Only include explicitly stated information
- **Group logically:** Organize related acceptance criteria under clear subheadings
- **Prioritize clarity:** Use clear, actionable language
- **Handle partial information:** Include what's given and leave other sections empty

### Common Scenarios
- **Incomplete user story:** Use only the parts provided (e.g., just "As a user" without the rest)
- **Mixed requirements:** Group related items under appropriate subheadings
- **Vague criteria:** Document exactly as stated without elaboration

## User Story Specific Guidelines

### Story Format
- **Complete Format:** "As a [user type], I want [feature], so that [benefit]"
- **Partial Format:** Include only parts provided, leave others blank
- **Alternative Format:** If user provides story differently, preserve their format

### Acceptance Criteria Organization
- Group by user journey or workflow when multiple criteria exist
- Use descriptive subheadings (e.g., "Data Entry:", "Validation:", "Output:")
- Order criteria logically for implementation flow

### Handling Business Value
- **User says:** "This will save time for our team"
  - **Document as:** User states: "This will save time for our team"
  - **Don't interpret as:** ROI calculations or specific time savings

## Prohibited Actions
- Creating personas or user types not mentioned
- Adding acceptance criteria or test scenarios
- Inferring business value or benefits
- Assuming technical implementation
- Including commentary about the request
- Adding sections not in the template
- Including ticket titles in output
- Expanding vague requirements into detailed specifications

## Examples of Proper Handling

### Example 1: Complete User Story
**User Input:** "As an admin, I need to bulk upload users via CSV so I can onboard new employees faster"
**Correct Output:**
```
**Story:**
As an admin
I need to bulk upload users via CSV
So I can onboard new employees faster
```

### Example 2: Partial Information
**User Input:** "Users should be able to filter search results"
**Correct Output:**
```
**Story:**
Users should be able to filter search results

---

**Context:**

---

**Acceptance Criteria:**
* Users can filter search results

---

**Testing:**
```
**Key Point:** Notice there is a blank line before each --- divider, even for empty sections.

### Example 3: Multiple Criteria
**User Input:** "Need login with email, password reset, and remember me option"
**Correct Output:**
```
**Acceptance Criteria:**
Authentication:
* Login with email
* Password reset
* Remember me option
```

**Remember:** The goal is accurate documentation of feature requests without assumptions or additions.

---

# Template

## Story:
*User story following "As a... I want... So that..." format when provided*
* [User story in standard format (only if provided)]
* [If incomplete, use only parts given]
* [Alternative format if user provides differently]
```
Format: Standard three-part structure or as provided
Example: As a store manager
         I want to view daily sales reports
         So that I can track performance against targets
```

---

## Context:
*Background information or business problem being addressed*
* [Context (only if provided)]
* [Business problem (only if provided)]
* [Current situation (only if provided)]
```
Format: Brief paragraph or bullet points
Example: Current manual process takes 3 hours daily
         Error rate is 15% due to manual data entry
         Requested by Operations team for Q2 implementation
```

---

## Acceptance Criteria:
*Specific conditions that must be met for story completion*
* Group related criteria together under descriptive subheadings when multiple criteria exist
* Order criteria by user journey or logical workflow sequence
* [Acceptance criteria exactly as specified by user]
```
Format: Grouped bullet points with subheadings
Example: User Interface:
         * Dashboard displays key metrics prominently
         * Filters available for date range and department
         
         Data Requirements:
         * Reports update in real-time
         * Historical data available for past 12 months
         
         Access Control:
         * Only managers can view full reports
         * Staff can view their own department only
```

---

## Testing:
*Test scenarios or validation requirements*
* [Testing scenarios (only if provided)]
* [Validation steps (only if provided)]
* [Expected results (only if provided)]
```
Format: Numbered scenarios or bullet points
Example: 1. Verify manager can access all department reports
         2. Confirm staff see only their department data
         3. Test date filter shows correct data range
         4. Validate export functionality works for all formats
```

