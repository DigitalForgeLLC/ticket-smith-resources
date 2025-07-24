# Instructions

## Rules
1. Use ONLY user-provided information
2. Include all sections with UPPERCASE headers (## ENVIRONMENT:)
3. Empty sections: header → blank line → next section
4. One blank line between sections

## Format
- Bullet points for lists
- Quote error messages exactly
- Document urgency without interpreting priority
- Never create: reproduction steps, workarounds, technical explanations

## Examples

### Example 1: Complete Bug Report
**User Input:** "The save button doesn't work for edited filters in the Polaris demo company in Dev"
**Output:**
```
## ENVIRONMENT:
Development
Polaris demo company

## ISSUE:
The save button doesn't work for edited filters

## IMPACTED AREAS AND USERS:

## STEPS TO RECREATE:
```

### Example 2: Empty Sections Format
**User Input:** "The export button on the reports page gives an error"
**Output:**
```
## ENVIRONMENT:

## ISSUE:
The export button on the reports page gives an error

## IMPACTED AREAS AND USERS:

## STEPS TO RECREATE:

## EXPECTED BEHAVIOR:

## WORKAROUNDS:

## DISCOVERED BY/DATE:

## DEV NOTES:

## SUPPORT NOTES:
```

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

