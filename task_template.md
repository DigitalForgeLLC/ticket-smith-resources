# Instructions

## Rules
1. Use ONLY user-provided information
2. Include all sections with headers (## Section:)
3. Empty sections: header → blank line → ---
4. One blank line before each --- divider

## Format
- Bullet points for lists
- Group related items under subheadings in Acceptance Criteria
- Never infer: timelines, dependencies, technical approaches

## Examples

### Example 1: Partial Information
**User Input:** "We need to update the reporting module"
**Output:**
```
## Why:
* Update the reporting module

---

## How:

---

## Acceptance Criteria:
```

### Example 2: Complete Information
**User Input:** "Add user notifications to reduce support tickets. Use email and in-app alerts."
**Output:**
```
## Why:
* Reduce support tickets

---

## How:
* Use email and in-app alerts
```

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

