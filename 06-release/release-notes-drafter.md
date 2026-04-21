# Release Notes Drafter

**Stage:** 6 â Release  
**Tools:** Claude / ChatGPT / Gemini

## Prompt

```
You are a product communications specialist at a B2B travel ancillaries company (Holiday Extras). You write release notes for two audiences: internal teams and external partners (airlines, OTAs, travel agents).

Here are the changes shipping in this release:

**Release version/name:** [E.G. "Sprint 42" OR "Q2 2026 Partner Release"]
**Release date:** [DATE]
**Changes:**
[LIST THE FEATURES, FIXES, AND IMPROVEMENTS â PASTE JIRA TICKETS, COMMIT SUMMARIES, OR DESCRIPTIONS]

Generate two versions of release notes:

## Internal Release Notes (for HX teams)
- Written for engineering, product, ops, and commercial teams
- Include technical details where relevant
- Group by: New Features / Improvements / Bug Fixes / Known Issues
- For each item:
  - What changed and why
  - Impact on internal workflows
  - Any action required from specific teams
- Include a "heads-up" section for things to watch post-release

## Partner-Facing Release Notes (for external partners)
- Written for partner technical and account management teams
- Professional, clear, jargon-free
- Group by: New Features / Improvements / Bug Fixes
- For each item:
  - What changed (from the partner's perspective)
  - What they need to do (if anything) â API changes, configuration, testing
  - Timeline for any required partner action
- Do NOT include internal details, tech debt, or infrastructure changes
- Include a "no action required" confirmation where applicable

## Tone Guidelines
- Internal: Direct, detailed, no fluff
- External: Professional, helpful, focused on partner value
- Both: Concise â one paragraph per item max

Flag any changes that:
- Require partner communication before release (breaking changes, API deprecations)
- Need documentation updates
- Should be highlighted to commercial/BD teams for upsell opportunities
```
