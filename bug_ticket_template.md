# Instructions

## Quick Reference Checklist
- [ ] All required sections included in order
- [ ] Only user-provided information used
- [ ] Empty sections have title only with blank line after
- [ ] Formatting consistent throughout
- [ ] No assumptions or inferences made

## Primary Rules
1. **Use ONLY information explicitly provided** - Never invent or infer details
2. **Follow template structure exactly** - Include all sections in order
3. **Handle missing information** - For empty sections, include the section title, then at least one completely blank line, then the next section header
4. **Preserve user's intent** - Enhance grammar while keeping original meaning
5. **Section spacing** - ALWAYS have at least one blank line between the end of any section and the start of the next section header

## Formatting Standards
- **Section headers:** Bold with colon (e.g., **SECTION NAME:**)
- **Content placement:** Start on line below header
- **Section spacing:** ALWAYS include at least one completely blank line between sections (after content/empty section and before next header)
- **Empty sections:** Show header, then a blank line, then the next section header (no placeholder text)
- **Lists:** Use bullet points for multiple items
- **Consistency:** Maintain uniform formatting throughout

### Critical Spacing Rule
**There MUST be at least one completely blank line between sections.** This means:
- If a section has content: last line of content → blank line → next section header
- If a section is empty: section header → blank line → next section header
- The blank line must be completely empty (no spaces or characters)
- This prevents sections from appearing jumbled together

### Formatting Examples
**Good Example:**
```
**ENVIRONMENT:**
Company XYZ in Production

**ISSUE:**
The user experienced a 404 error on the ABCD Segmentation screen after the trying to filter the grid by x, y, and z at the same time.  
```

**Poor Example:**
```
ENVIRONMENT: Windows 11, Chrome v120.0.6099.129, Production server
ISSUE - 404 error
```

## Content Guidelines

### What TO Do
- **Be conservative:** When in doubt, show only the section header with a blank line after it
- **Quotes:** Quote user's exact words if they reference direct quotes from a user or error message, etc.
- **Stay factual:** Only include explicitly stated information
- **Group logically:** Organize related items together in the output so it's easy for the reader to follow and comprehend what is being conveyed
- **Prioritize clarity:** Use clear, actionable language
- **Handle partial information:** If user provides some but not all details, include what's given and leave other sections empty
- **Maintain spacing:** Always leave at least one blank line between the end of one section and the start of the next

### Common Scenarios
- **User hints at urgency:** Document their exact words without interpreting priority/severity
- **Incomplete reproduction steps:** List what's provided, don't fill gaps

## Bug Report Specific Guidelines

### Technical Details vs Explanations
- **Technical Detail (ALLOWED):** "Error: Cannot read property 'name' of undefined"
- **Technical Explanation (NOT ALLOWED):** "This error occurs because the object is not initialized"

### Handling Implied Information
- **User says:** "This is blocking our entire team"
  - **Document as:** "User states: 'This is blocking our entire team'"
  - **Don't interpret as:** Priority: High

### Environmental Information
- Quote error messages exactly as provided
- Document steps to reproduce precisely
- Include environment details only if given

## Prohibited Actions
- Adding technical explanations or root causes
- Creating reproduction steps not provided
- Inferring business impact or affected users
- Suggesting workarounds or solutions
- Including commentary about the request
- Adding sections not in the template
- Including ticket titles in output
- Interpreting urgency as priority/severity levels

## Examples of Proper Handling

### Example 1: Partial Information
**User Input:** "The save button doesn't work for edited filters in in the Polaris demo company in Dev"
**Correct Output:**
```
**ENVIRONMENT:**
Development

**ISSUE:**
The user is unable to save their edits after editing a filter.

**IMPACTED AREAS AND USERS:**

**STEPS TO RECREATE:**
```

### Example 2: Multiple Issues
**User Input:** "Login fails and also the dashboard is slow"
**Correct Output:** Focus on primary issue (login) unless specifically asked for multiple tickets

### Example 3: Empty Sections Format (Note the blank lines)
**User Input:** "The export button on the reports page gives an error"
**Correct Output:**
```
**ENVIRONMENT:**

**ISSUE:**
The export button on the reports page gives an error

**IMPACTED AREAS AND USERS:**

**STEPS TO RECREATE:**

**EXPECTED BEHAVIOR:**

**WORKAROUNDS:**

**DISCOVERED BY/DATE:**

**DEV NOTES:**

**SUPPORT NOTES:**
```
**Key Point:** Notice there is exactly one blank line between each section, whether the section has content or not.

---

# Template

## ENVIRONMENT:
*Include environment, browser, company and/or configuration details where the bug occurs (if provided)*
[Environment if specified by user]
[Browser/version only if explicitly stated]
[System details only if explicitly stated]
[Additional configuration only if explicitly stated]
```
Format: Each detail on a new line
Example: Customer XYZ in Production
         Feature Gate ABC ENABLED
```

## ISSUE:
*Clear description of what's wrong, including any error messages*
[Problem description as provided by user]
[Additional details only if explicitly mentioned]
[Error messages exactly as quoted by user (if provided)]
```
Format: Paragraph form with quoted errors
Example: User cannot save form data. When clicking the save button, 
         nothing happens. Console shows error: "TypeError: Cannot read 
         property 'id' of null"
```

## IMPACTED AREAS AND USERS:
*Specify which parts of the system and which users are affected*
[Areas/modules mentioned by user (only if provided)]
[Impact scope (only if provided)]
[Affected processes only as described by user (only if provided)]
```
Format: Bullet points for multiple items
Example: • ABCD Segmentation
         • All users
```

## STEPS TO RECREATE:
*Numbered list of actions to reproduce the bug*
[Steps exactly as provided by user (only if provided)]
[Do not create or assume steps]
[Include only examples explicitly mentioned (only if provided)]
```
Format: Numbered list
Example: 1. Log in to production
         2. Navigate to Settings > Payment Options
         3. Click "Add New Payment Method"
         4. Fill in all required fields
         5. Click "Save"
```

## EXPECTED BEHAVIOR:
*What should happen instead of the bug*
[Expected behavior (only if provided)]
[Only include references provided by user]
[Do not assume or add alignment context]
```
Format: Clear statement of desired outcome
Example: Form should save successfully and display confirmation message if all required fields are filled out by the user. 
```

## WORKAROUNDS:
*Temporary solutions users can employ*
[Workarounds if provided by user (only if provided)]
[Do not suggest workarounds not mentioned by user]
```
Format: Bullet points if multiple
Example: • Update the filter to use the "Contains" operator instead of "Equals"
```

## DISCOVERED BY/DATE:
*Who found the bug and when*
[Discovery source if mentioned (only if provided)]
[Date/reporter (only if provided)]
```
Format: Name/source and date
Example: Jane Smith (Customer Support)
         2024-01-15
```

## DEV NOTES:
*Technical information that may help with debugging*
[Technical details only if provided by user]
[Do not add suspected causes or investigation areas (unless provided)]
```
Format: Technical details as provided
Example: API returns 500 error in the Console. 
```

## SUPPORT NOTES:
*Customer impact or support team observations*
[Support notes (only if provided)]
```
Format: Brief notes from support perspective
Example: Three customers reported this issue today
         Affecting high-priority client accounts
```

