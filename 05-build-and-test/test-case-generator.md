# Test Case Generator

**Stage:** 5 â Build & Test  
**Tools:** Claude / ChatGPT / Gemini

## Prompt

```
You are a QA specialist working with an Experience Product Owner at a B2B travel ancillaries company. The platform delivers travel extras (parking, lounges, insurance, hotels, transfers) through white-label integrations with airline and OTA partners.

I need comprehensive test cases for the following feature:

**Feature:** [DESCRIBE THE FEATURE]
**User stories / Acceptance criteria:** [PASTE RELEVANT STORIES AND AC]
**Integration context:** [HOW PARTNERS INTERACT WITH THIS â API, WIDGET, WHITE-LABEL]

Generate test cases organised by category:

## Functional Tests â Happy Path
| ID | Test Case | Steps | Expected Result | Priority |
|---|---|---|---|---|
| TC-001 | ... | 1. ... 2. ... | ... | P1 |

## Functional Tests â Negative / Error
| ID | Test Case | Steps | Expected Result | Priority |
|---|---|---|---|---|
| TC-100 | ... | 1. ... 2. ... | ... | P1 |

## Edge Cases
| ID | Test Case | Steps | Expected Result | Priority |
|---|---|---|---|---|
| TC-200 | ... | 1. ... 2. ... | ... | P2 |

## Partner Integration Tests
| ID | Test Case | Steps | Expected Result | Priority |
|---|---|---|---|---|
| TC-300 | ... | 1. ... 2. ... | ... | P1 |

(Test across different partner configurations, API versions, branding setups)

## Cross-Browser / Device Tests
| ID | Test Case | Steps | Expected Result | Priority |
|---|---|---|---|---|
| TC-400 | ... | 1. ... 2. ... | ... | P2 |

## Accessibility Tests
| ID | Test Case | Steps | Expected Result | Priority |
|---|---|---|---|---|
| TC-500 | ... | 1. ... 2. ... | ... | P2 |

## Performance Tests
| ID | Test Case | Steps | Expected Result | Priority |
|---|---|---|---|---|
| TC-600 | ... | 1. ... 2. ... | ... | P3 |

## Data & Analytics Tests
| ID | Test Case | Steps | Expected Result | Priority |
|---|---|---|---|---|
| TC-700 | ... | 1. ... 2. ... | ... | P2 |

---

Guidelines:
- P1 = Must pass before release (blockers)
- P2 = Should pass, but can ship with known issues if documented
- P3 = Nice to verify, lower risk
- Include regression tests for existing functionality that might be affected
- Flag any tests that require specific partner sandbox environments
- Note any test data setup requirements
```
