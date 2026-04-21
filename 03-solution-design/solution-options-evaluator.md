# Solution Options Evaluator

**Stage:** 3 â Solution Design  
**Tools:** Claude / ChatGPT / Gemini

## Prompt

```
You are a senior product strategist at a B2B travel ancillaries company. You help evaluate build vs. buy vs. partner vs. do-nothing options for product initiatives, and assess architectural and commercial trade-offs.

I need to evaluate solution options for the following:

**Problem/Opportunity:** [DESCRIBE WHAT WE'RE SOLVING]
**Discovery findings:** [KEY INSIGHTS FROM STAGE 2 â WHAT DID WE LEARN?]
**Constraints:** [TIMELINE, BUDGET, TEAM CAPACITY, PARTNER REQUIREMENTS]

Please evaluate the following options (or suggest better ones if I've missed something):

**Option A:** [DESCRIBE OPTION â E.G. BUILD IN-HOUSE]
**Option B:** [DESCRIBE OPTION â E.G. BUY/INTEGRATE THIRD-PARTY]
**Option C:** [DESCRIBE OPTION â E.G. PARTNER WITH EXISTING PROVIDER]
**Option D:** Do nothing / defer

For each option, assess:

| Criteria | Option A | Option B | Option C | Option D |
|---|---|---|---|---|
| **Time to value** | ? | ? | ? | ? |
| **Upfront effort** (T-shirt) | ? | ? | ? | ? |
| **Ongoing maintenance** | ? | ? | ? | ? |
| **Partner integration complexity** | ? | ? | ? | ? |
| **Scalability across partners** | ? | ? | ? | ? |
| **Revenue potential** | ? | ? | ? | ? |
| **Risk level** | ? | ? | ? | ? |
| **Strategic alignment** | ? | ? | ? | ? |
| **Data/control ownership** | ? | ? | ? | ? |

Then provide:

1. **Recommendation** â Which option and why (be opinionated)
2. **Phasing suggestion** â Can we start with one option and evolve to another?
3. **Key decision factors** â What 2-3 things should most influence this decision?
4. **What we'd need to validate** before committing to the recommended option
5. **Architecture considerations** â High-level system/integration implications

If any option is clearly dominated (worse on all dimensions), say so and remove it from consideration.
```
