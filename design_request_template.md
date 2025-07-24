# Instructions

## Primary Rules
1. **Use ONLY information explicitly provided** - Never invent or infer details
2. **Follow template structure exactly** - Include all sections in order
3. **Empty sections:** Include title, blank line, then next section header (no placeholder text)
4. **Preserve user's intent** - Enhance grammar while keeping original meaning
5. **Keep emoji icons** - Maintain emojis in section headers

## Formatting Standards
- **Section headers:** Use ## format with emoji and colon (e.g., ## 📌 Description:)
- **Content:** Start on line below header
- **Spacing:** Always include blank line between sections
- **Lists:** Use bullet points for multiple items

### Critical Spacing Rule
**There MUST be at least one blank line between sections:**
- If section has content: content → blank line → next section
- If section is empty: header → blank line → next section

## Content Guidelines
- Document exactly as stated without elaboration
- Include only explicitly provided information
- Never suggest deliverables, goals, or methodologies

### Design-Specific
- Document design needs exactly as stated
- Include only explicitly mentioned stakeholders or areas
- List constraints and research only if provided

## Examples

### Example 1: Complete Request
**User Input:** "Redesign checkout flow to reduce cart abandonment. Need mobile and desktop versions. Research shows users confused by shipping options."
**Output:**
```
## 📌 Description:
* Redesign checkout flow to reduce cart abandonment

## 📋 Deliverables:
* Mobile versions
* Desktop versions

## 🔍 Research & References:
* Research shows users confused by shipping options
```

### Example 2: Partial Information
**User Input:** "Update the color scheme to match new branding"
**Output:**
```
## 📌 Description:
* Update the color scheme to match new branding

## 🎯 Goals & Objectives:

## 🗺️ Affected Areas:

## 📋 Deliverables:

## 🔍 Research & References:

## 💬 Other Comments / Notes:
```

---

# Template

## 📌 Description:
*What needs to be designed and why*
* [Design request as stated by user]
* [Problem/opportunity (only if provided)]
```
Format: Clear description of the design need
Example: * Redesign onboarding flow to reduce drop-off rate
         * Current flow has 60% abandonment at step 3
         * Users report confusion with account setup process
```

## 🎯 Goals & Objectives:
*What the design should achieve*
* [Goals as stated by user]
* [Objectives (only if provided)]
* [Metrics (only if provided)]
```
Format: Bullet points with measurable outcomes where provided
Example: * Reduce onboarding drop-off to under 30%
         * Decrease time to complete setup by 50%
         * Achieve 80% user satisfaction score
```

## 🗺️ Affected Areas:
*Parts of the system, user groups, or workflows impacted*
* [Areas mentioned by user]
* [User flows (only if provided)]
* [Systems/platforms (only if provided)]
* [Stakeholders (only if provided)]
```
Format: Categorized list
Example: User Flows:
         * New user registration
         * Account verification
         * Initial profile setup
         
         Platforms:
         * Web application
         * iOS app
         * Android app
```

## 📋 Deliverables:
*Expected design outputs*
* [Deliverables (only if provided)]
* [File formats (only if provided)]
* [Documentation needs (only if provided)]
```
Format: Specific deliverables with details
Example: * High-fidelity mockups for all screens
         * Interactive prototype in Figma
         * Design system documentation
         * Accessibility compliance report
```

## 🔍 Research & References:
*Background information and constraints*
* [Research/data (only if provided)]
* [References (only if provided)]
* [Constraints (only if provided)]
* [Links/documents (only if provided)]
```
Format: Organized by type
Example: User Research:
         * Usability test results (link provided)
         * Customer feedback survey data
         
         Constraints:
         * Must work with existing backend API
         * Follow WCAG 2.1 AA standards
         * Use current design system components
```

## 💬 Other Comments / Notes:
*Additional context or considerations*
* [Additional context exactly as provided]
```
Format: Any other relevant information
Example: * CEO specifically requested a "clean, minimal look"
         * Similar to competitor X but with our brand personality
         * Previous design attempts attached for reference
```

