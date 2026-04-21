# Architecture Brief Generator

**Stage:** 3 â Solution Design  
**Tools:** Claude / ChatGPT / Gemini / Mermaid (for diagrams)

## Prompt

```
You are a Solution Architect working with an Experience Product Owner at a B2B travel ancillaries company. The platform serves partners (airlines, OTAs, travel agents) via white-label API integrations and delivers products like airport parking, lounges, insurance, hotels, and transfers.

I need you to generate a lightweight architecture brief for the following feature/initiative:

**Feature:** [WHAT ARE WE BUILDING?]
**Chosen approach:** [BUILD / BUY / PARTNER â FROM SOLUTION OPTIONS EVALUATION]
**Key requirements:** [TOP 3-5 REQUIREMENTS]
**Partner integration context:** [HOW PARTNERS WILL CONSUME THIS â API, WIDGET, WHITE-LABEL PAGE, ETC.]

Generate an architecture brief covering:

## 1. System Context
- Where does this sit in the existing platform?
- What systems does it interact with (internal and external)?
- Generate a Mermaid context diagram showing the key components and data flows

## 2. Key Components
- New services, APIs, or modules needed
- Changes to existing systems
- Third-party integrations required

## 3. Data Flow
- What data moves where and when?
- Generate a Mermaid sequence diagram for the primary happy-path flow
- Any new data storage requirements?

## 4. Partner Integration
- How will partners access this? (API endpoint, SDK, widget, redirect)
- What configuration or customisation will partners need?
- Backwards compatibility considerations

## 5. Non-Functional Requirements
- Performance expectations (latency, throughput)
- Availability and reliability needs
- Security and data privacy considerations
- Scalability approach

## 6. Risks & Unknowns
- Technical risks and mitigation strategies
- Integration risks with partner systems
- Spikes or investigations needed before detailed design

## 7. Phasing
- What's the minimum viable slice?
- How does this evolve across phases?
- What can we defer without blocking the first release?

Output all Mermaid diagrams as code blocks so they can be rendered directly. Keep the brief high-level â this is for alignment, not detailed design.
```
