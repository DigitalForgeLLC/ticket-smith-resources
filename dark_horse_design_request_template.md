# Instructions

## Rules
1. Use ONLY user-provided information
2. Include all sections with emoji headers (## 📌 Section:)
3. Empty sections: header → blank line → next section
4. One blank line between sections

## Format
- Bullet points for lists
- Include only: explicit stakeholders, constraints, research
- Never suggest: deliverables, goals, methodologies

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