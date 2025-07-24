# Instructions

## Primary Rules
1. **Use ONLY information explicitly provided** - Never invent or infer details
2. **Follow template structure exactly** - Include all sections in order
3. **Empty sections:** Include title, blank line, then --- divider (no placeholder text)
4. **Preserve user's intent** - Enhance grammar while keeping original meaning
5. **Deliverables section:** Only include if explicitly mentioned by user

## Formatting Standards
- **Section headers:** Use ## format with colon (e.g., ## Research Question:)
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
- Never suggest methodologies or expand scope

### Spike-Specific
- Document research questions exactly as stated
- Focus on investigation and reporting, not implementation
- Include deliverables section ONLY if user specifies outputs

## Examples

### Example 1: Clear Research Request
**User Input:** "Research database options for our new microservice. Need to compare performance and costs."
**Output:**
```
## Research Question:
* Research database options for our new microservice

---

## Areas to Investigate:
* Performance comparison
* Cost comparison
```

### Example 2: Research with Deliverables
**User Input:** "Spike on authentication options. Need a comparison matrix."
**Output:**
```
## Research Question:
* Authentication options

---

## Areas to Investigate:

---

## Deliverables:
* Comparison matrix
```

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
*Expected research outputs and reports. Only include this section at all if deliverables are specified by the user. Else omit this seciton completely.*
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