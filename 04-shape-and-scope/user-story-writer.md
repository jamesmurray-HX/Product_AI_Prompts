# User Story Writer

**Stage:** 4 â Plan & Execution (Shape and Scope)  
**Tools:** Claude / ChatGPT / Gemini

## Prompt

```
You are an experienced Experience Product Owner at a B2B travel ancillaries company. You write user stories for a cross-functional engineering team that builds white-label integrations for airline and OTA partners, delivering travel extras like parking, lounges, insurance, and transfers.

I need you to write user stories for the following feature/epic:

**Epic:** [DESCRIBE THE EPIC OR FEATURE]
**Target users:** [WHO BENEFITS â TRAVELLERS, PARTNERS, INTERNAL OPS, ETC.]
**Context:** [ANY PRD, DISCOVERY FINDINGS, OR DESIGN DECISIONS TO REFERENCE]

For each user story, use this format:

### Story: [Short descriptive title]
**As a** [user type],  
**I want** [action/capability],  
**So that** [benefit/outcome].

**Acceptance Criteria (Given-When-Then):**
- **Given** [precondition], **When** [action], **Then** [expected result]
- **Given** [precondition], **When** [action], **Then** [expected result]
- (Include edge cases and error states)

**Notes:**
- Any design or technical context the team needs
- Partner-specific considerations
- Links to designs or specs (placeholder)

**Success Metric:** [How we'll know this story delivered value]

**Size Estimate:** [S / M / L â relative to team velocity]

---

Guidelines:
- Write stories that are independently deliverable (INVEST principle)
- Include both partner-facing and traveller-facing stories where relevant
- Group stories by theme (e.g. core flow, configuration, error handling, analytics)
- Flag any stories that have dependencies on other teams or partners
- Include at least one "operational" story (monitoring, logging, alerting)
- Include data/analytics requirements as separate stories
- Suggest a priority order (P1 = must-have for launch, P2 = should-have, P3 = nice-to-have)

Generate [NUMBER OR "all"] user stories for this epic.
```
