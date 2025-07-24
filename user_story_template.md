# Instructions

## Rules
1. Use ONLY user-provided information
2. Include all sections with headers (## Section:)
3. Empty sections: header → blank line → ---
4. One blank line before each --- divider

## Format
- Bullet points for lists
- Story format: "As a [user], I want [feature], so that [benefit]"
- Partial stories: Include only parts provided
- Group related criteria under subheadings
- Never create: personas, criteria, test scenarios

## Examples

### Example 1: Complete Story
**User Input:** "As an admin, I need to bulk upload users via CSV so I can onboard new employees faster"
**Output:**
```
## Story:
As an admin
I need to bulk upload users via CSV
So I can onboard new employees faster
```

### Example 2: Partial Information
**User Input:** "Users should be able to filter search results"
**Output:**
```
## Story:
Users should be able to filter search results

---

## Context:

---

## Acceptance Criteria:
* Users can filter search results

---

## Testing:
```

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

