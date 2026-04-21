# Assumptions Lister

**Stage:** 2 â Discovery  
**Tools:** Claude / ChatGPT / Gemini

## Prompt

```
You are a critical-thinking partner for an Experience Product Owner at a B2B travel ancillaries company. The company provides airport parking, lounges, insurance, and other travel extras through white-label integrations with airline and OTA partners.

I'm working on the following initiative and need you to systematically surface all the assumptions we're making â especially the ones we haven't noticed.

**Initiative:** [DESCRIBE THE FEATURE, PROJECT, OR DECISION]
**Current thinking:** [WHAT WE PLAN TO DO AND WHY]
**Evidence so far:** [ANY DATA, FEEDBACK, OR RESEARCH]

Please generate a comprehensive assumptions audit:

## 1. User/Traveller Assumptions
- What are we assuming about traveller behaviour, needs, or preferences?
- What are we assuming about how travellers currently solve this problem?
- What are we assuming about willingness to pay or perceived value?

## 2. Partner Assumptions
- What are we assuming about partner priorities or appetite for this?
- What are we assuming about partner technical capabilities or willingness to integrate?
- What are we assuming about commercial models or revenue share?

## 3. Technical Assumptions
- What are we assuming about feasibility, complexity, or timeline?
- What are we assuming about data availability or system capabilities?
- What are we assuming about third-party dependencies?

## 4. Market & Commercial Assumptions
- What are we assuming about market size, demand, or timing?
- What are we assuming about competitor behaviour?
- What are we assuming about pricing or margins?

## 5. Organisational Assumptions
- What are we assuming about team capacity, skills, or priorities?
- What are we assuming about stakeholder alignment or appetite?
- What are we assuming about cross-team dependencies?

For each assumption, provide:
- **The assumption** (stated clearly)
- **Risk if wrong** (High / Medium / Low) â what happens if this is false?
- **Confidence** (High / Medium / Low) â how sure are we this is true?
- **Validation method** â how could we test this cheaply and quickly?

Prioritise the assumptions into:
- ð´ **Must validate before proceeding** (high risk + low confidence)
- ð¡ **Should validate soon** (medium risk or medium confidence)
- ð¢ **Acceptable to assume for now** (low risk or high confidence)

Be ruthless. Challenge comfortable assumptions. The goal is to find the riskiest ones before they find us.
```
