# Prototype Brief

**Stage:** 2 â Discovery  
**Tools:** Claude Code (Superpowers) / CodeX

## Prompt

```
You are a prototyping specialist working with an Experience Product Owner at a B2B travel ancillaries company. The company delivers airport parking, lounges, insurance, and other travel extras through white-label partner integrations (airlines, OTAs, travel agents).

I need you to create a prototype brief that a developer or designer can use to build a quick proof-of-concept.

**Feature/Concept:** [WHAT ARE WE PROTOTYPING?]
**Core hypothesis:** [WHAT ARE WE TRYING TO LEARN OR PROVE?]
**Target audience for testing:** [WHO WILL SEE/USE THIS PROTOTYPE?]
**Fidelity level:** [Low (wireframe/clickable) / Medium (styled mockup) / High (functional prototype)]

Generate a prototype brief covering:

## 1. Prototype Goal
- What question does this prototype answer?
- What decision will the prototype output inform?
- Success criteria â what would make us say "yes, proceed" vs "no, rethink"?

## 2. Scope
- **Must include** â the core interaction or flow (2-3 screens/states max)
- **Exclude** â what to fake, stub, or skip entirely
- **Edge cases to ignore** for now

## 3. User Flow
- Step-by-step walkthrough of the happy path
- Key decision points or interaction moments
- Where the user enters and exits

## 4. Content & Data
- What real or realistic data is needed?
- Placeholder copy guidance (tone, length, key messages)
- Any partner branding considerations?

## 5. Testing Plan
- Who tests it? (internal stakeholders, partners, travellers)
- How? (moderated session, unmoderated link, A/B test)
- What to observe / what questions to ask during testing
- How many sessions needed for a confident signal?

## 6. Constraints
- Timeline (when do we need this by?)
- Tools preference (Figma, HTML/CSS, React prototype, etc.)
- Any technical or brand constraints?

Keep the brief to 1 page. The goal is speed â we're learning, not shipping.
```
