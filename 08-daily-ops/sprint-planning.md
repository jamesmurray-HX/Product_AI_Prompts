# Sprint Planning Assistant

**Activity:** Daily Operations  
**Tools:** Claude / ChatGPT / Gemini

## Prompt

```
You are a sprint planning facilitator working with an Experience Product Owner at Holiday Extras, a B2B travel ancillaries company.

I need help planning the upcoming sprint:

**Sprint:** [SPRINT NUMBER / NAME]
**Duration:** [2 WEEKS / 1 WEEK / OTHER]
**Team capacity:** [NUMBER OF DEVS Ã AVAILABLE DAYS, MINUS PTO/MEETINGS]
**Velocity (last 3 sprints):** [STORY POINTS OR TICKET COUNT]
**Carryover from last sprint:** [ANY INCOMPLETE ITEMS]
**Sprint goal candidates:** [WHAT SHOULD WE FOCUS ON?]

**Candidate items for this sprint:**
[PASTE YOUR PRIORITISED BACKLOG ITEMS WITH ESTIMATES]

**External commitments:**
[PARTNER DEADLINES, LAUNCH DATES, STAKEHOLDER PROMISES]

Help me plan this sprint:

## 1. Sprint Goal
- Propose a clear, measurable sprint goal (one sentence)
- The goal should answer: "What will be true at the end of this sprint that isn't true today?"

## 2. Capacity Calculation
- Available capacity: [X] person-days
- Recommended commitment: [Y]% of capacity (accounting for meetings, reviews, unexpected work)
- Buffer for unplanned work: [Z] points/days

## 3. Sprint Backlog Recommendation
| Priority | Item | Estimate | Sprint Goal? | Dependencies |
|---|---|---|---|---|
| P0 | ... | ... | â/â | ... |
| P1 | ... | ... | â/â | ... |
| P2 | ... | ... | â/â | ... |
| Stretch | ... | ... | â | ... |

**Total committed:** [X] points  
**Stretch items:** [Y] points  
**Buffer remaining:** [Z] points

## 4. Risk Check
- Are we over-committing? (compare to velocity)
- Do we have unresolved dependencies that could block us?
- Is the sprint goal achievable with the committed items?
- Any single-person dependencies (bus factor)?

## 5. Carry-Over Assessment
- For each carry-over item: Why didn't it complete? Is the remaining work well-understood?
- Should any carry-over items be re-estimated or split?

## 6. Suggested Sprint Ceremonies
- Sprint planning: [ALREADY DOING]
- Mid-sprint check-in: [RECOMMEND DAY/TIME]
- Sprint review: [DATE]
- Retro: [DATE]

Be realistic about capacity. It's better to under-commit and over-deliver than the reverse.
```
