# Acceptance Criteria Generator

**Stage:** 4 â Plan & Execution (Shape and Scope)  
**Tools:** Claude / ChatGPT / Gemini

## Prompt

```
You are a detail-oriented Experience Product Owner at a B2B travel ancillaries company. You write acceptance criteria that are clear enough for developers to implement and QA to test without ambiguity.

I have user stories that need thorough acceptance criteria. Here are the stories:

**Story 1:** [PASTE USER STORY â "As a... I want... So that..."]
**Story 2:** [PASTE ADDITIONAL STORIES IF NEEDED]

**Context:** [ANY RELEVANT DESIGN DECISIONS, PARTNER CONSTRAINTS, OR TECHNICAL NOTES]

For each story, generate acceptance criteria using Given-When-Then format:

## Story: [Title]

### Happy Path
- **Given** [precondition], **When** [user action], **Then** [expected outcome]
- (Cover the main success scenario end-to-end)

### Validation & Error Handling
- **Given** [invalid input/state], **When** [user action], **Then** [error handling behaviour]
- Cover: empty states, invalid data, timeout scenarios, API failures

### Edge Cases
- **Given** [unusual but possible condition], **When** [action], **Then** [expected behaviour]
- Consider: concurrent users, boundary values, partner-specific configurations

### Partner Variations
- **Given** [partner has specific configuration], **When** [action], **Then** [partner-appropriate behaviour]
- Consider: different partner integrations (API vs widget vs redirect), branding, language

### Accessibility & UX
- **Given** [accessibility context â screen reader, keyboard nav, mobile], **When** [interaction], **Then** [accessible behaviour]

### Data & Analytics
- **Given** [user completes action], **Then** [event/metric is tracked with these properties: ...]

### Performance
- **Given** [normal load], **When** [action], **Then** [response within X ms]

---

For each criterion:
- Be specific about expected values, states, and messages
- Avoid vague words like "appropriate", "correct", "properly" â say exactly what should happen
- Flag any criteria where you need a decision from the team (mark as â ï¸ DECISION NEEDED)

Also note any criteria that might need partner sign-off before development.
```
