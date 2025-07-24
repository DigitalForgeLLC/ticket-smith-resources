# Instructions

## Primary Rules
1. **Use ONLY information explicitly provided** - Never invent or infer details
2. **Follow template structure exactly** - Include all sections in order
3. **Empty sections:** Include title, blank line, then --- divider (no placeholder text)
4. **Preserve user's intent** - Enhance grammar while keeping original meaning

## Formatting Standards
- **Section headers:** Use ## format with colon (e.g., ## Why:)
- **Section dividers:** Use --- between sections
- **Content:** Start on line below header
- **Spacing:** Always include blank line before --- divider
- **Lists:** Use bullet points for multiple items

### Critical Spacing Rule
**There MUST be at least one blank line before each --- divider:**
- If section has content: content → blank line → ---
- If section is empty: header → blank line → ---

## Content Guidelines
- Document exactly as stated without elaboration
- Include only explicitly provided information
- Group related items under subheadings in Acceptance Criteria
- Never infer timelines, dependencies, or technical approaches

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
