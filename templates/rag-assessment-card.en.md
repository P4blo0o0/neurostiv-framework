# RAG AI Response Assessment Card

> **Language:** **🇺🇸 English Version** | [🇷🇺 Russian Version](rag-assessment-card.md)  
> **Library:** [Neurostiv Practical Templates](README.md)  
> **Version:** 1.0 | **Usage Time:** 2-3 minutes

**Structured quality assessment of AI responses for Human-AI teams**

---

## The Problem

Most teams evaluate AI responses intuitively: "good answer" or "bad answer." This leads to:

- **Subjectivity** — the same response gets different ratings from different people
- **Incomplete analysis** — critical quality aspects get overlooked
- **No learning feedback** — teams don't understand how to improve their AI interactions
- **Trust erosion** — one bad AI experience gets generalized to the entire system

**Result:** Underutilized AI potential and growing distrust of the technology.

## Neurostiv Approach

### Standard Method
Typical AI response evaluation: "Rate this from 1 to 10"

**Problems:**
- One-dimensional scoring misses quality nuances
- No insight into what specifically needs improvement
- Subjectivity without structure
- No connection to AI operational principles

### Neurostiv Approach: RAG Assessment
**RAG** = **R**elevance + **A**ccuracy + **G**roundedness

**Based on Neurostiv Protocol v1.1:**
- **Connectivity Principle** — evaluation through multiple interconnected criteria
- **Emergence Principle** — composite assessment provides more insights than individual parts
- **Operational Specifications** — formalized approach to human-AI interaction quality

### Practical Difference Example

**Team query:** "How should we organize remote work for our development team?"

**AI response:** "Use Scrum methodology. Hold daily standups on Zoom. Set clear KPIs. Use Jira for task tracking."

**Standard assessment:**
```
"Decent answer, 7 out of 10"
```
*What to do with this information? Unclear.*

**RAG Assessment:**
```
Relevance (R): 0.9 — Directly addresses remote development team organization
Accuracy (A): 0.7 — Scrum isn't right for every team, KPIs can be demotivating
Groundedness (G): 0.4 — No source references, doesn't account for team specifics

Composite RAG: 0.67 — Good starting point, needs context-specific details
```
*Clear next steps: request justification and specify team context.*

---

## How to Use the RAG Card

### Three-Dimensional Assessment

#### R — Relevance
**Key question:** How well does the response match the asked question?

**Rating scale:**
- **0.9-1.0:** Fully addresses the question, covers all aspects
- **0.7-0.8:** Answers the main question but misses details
- **0.5-0.6:** Partially relevant, requires follow-up questions
- **0.3-0.4:** Touches on the topic but doesn't answer the specific question
- **0.0-0.2:** Unrelated to the asked question

#### A — Accuracy
**Key question:** How factually correct is the information in the response?

**Rating scale:**
- **0.9-1.0:** All information verified and correct
- **0.7-0.8:** Core information is sound, minor inaccuracies present
- **0.5-0.6:** Mix of correct and questionable information
- **0.3-0.4:** Significant factual errors
- **0.0-0.2:** Most claims are incorrect

#### G — Groundedness
**Key question:** How well is the response backed by evidence and sources?

**Rating scale:**
- **0.9-1.0:** Clear references to verifiable sources
- **0.7-0.8:** Mentions authoritative sources without direct links
- **0.5-0.6:** General claims without specific sources
- **0.3-0.4:** Personal opinions presented as facts
- **0.0-0.2:** Unfounded claims or speculation

### Calculating the Composite Score

**Basic formula:**
```
RAG Score = (R × 0.4) + (A × 0.35) + (G × 0.25)
```

**Context-specific weight adjustments:**
- **Research tasks:** R=0.3, A=0.25, G=0.45 (groundedness matters most)
- **Operational decisions:** R=0.5, A=0.4, G=0.1 (speed over sources)
- **Strategic planning:** R=0.35, A=0.4, G=0.25 (balanced approach)

---

## RAG Assessment Template

```markdown
## RAG Assessment: [Project/Task Name]

**Date:** ___________  
**Evaluator:** ___________  
**AI System:** ___________

### Original Query
___________________________________________________________________________
___________________________________________________________________________

### AI Response (key excerpts)
___________________________________________________________________________
___________________________________________________________________________

### RAG Assessment

**R — Relevance:** ___ / 1.0
*Justification:* __________________________________________________________

**A — Accuracy:** ___ / 1.0  
*Justification:* __________________________________________________________

**G — Groundedness:** ___ / 1.0
*Justification:* __________________________________________________________

**Composite RAG:** ___ / 1.0

### Improvement Recommendations
☐ Rephrase query for better relevance
☐ Fact-check the response information  
☐ Request sources and justification
☐ Clarify context for more precise answers
☐ Other: _______________________________________________________________

### Next Actions
☐ Accept response as-is
☐ Ask AI follow-up questions
☐ Verify information with independent sources
☐ Consult human expert
☐ Other: _______________________________________________________________
```

---

## Assessment Examples for Different Scenarios

### Scenario 1: Technical Consultation

**Query:** "Which database should we choose for an e-commerce project with 10,000 users?"

**AI Response:** "I recommend PostgreSQL. It supports ACID transactions, has good performance, and an active community. Data integrity is crucial for e-commerce."

**RAG Assessment:**
- **R (Relevance): 0.9** — Clear recommendation for the specified scenario
- **A (Accuracy): 0.8** — PostgreSQL is indeed good for e-commerce, but alternatives exist
- **G (Groundedness): 0.6** — Mentions principles (ACID) but no benchmarks referenced

**Composite RAG: 0.79** — Solid response, worth requesting comparison with alternatives

### Scenario 2: Marketing Strategy

**Query:** "How should we promote our SaaS product in the B2B segment?"

**AI Response:** "Use content marketing, LinkedIn ads, and cold email campaigns. These are the most effective channels for B2B."

**RAG Assessment:**
- **R (Relevance): 0.8** — Addresses the question but superficially
- **A (Accuracy): 0.6** — Generic recommendations without SaaS-specific considerations
- **G (Groundedness): 0.3** — No effectiveness data or sources provided

**Composite RAG: 0.59** — Needs significant refinement and specificity

### Scenario 3: Research Query

**Query:** "What research confirms the effectiveness of remote work?"

**AI Response:** "Stanford research (Bloom et al., 2015) showed 13% productivity increase with remote work. Gallup (2020) found higher engagement among remote employees."

**RAG Assessment:**
- **R (Relevance): 1.0** — Directly answers the research request
- **A (Accuracy): 0.9** — References to real studies are correct
- **G (Groundedness): 0.9** — Specific studies with authors and years

**Composite RAG: 0.94** — Excellent response, ready to use directly

---

## Neurostiv Ecosystem Integration

### Role Matrix Connection
If AI has an **AI** (AI Support) or **C** (Consultant) role in your [role responsibility matrix](role-responsibility-matrix.md), use RAG assessment for all its recommendations.

### Input for Other Templates
- **[NTSR Innovation Tracker](ntsr-innovation-tracker.md)** — high RAG scores correlate with solution novelty
- **[Decision Latency Tracker](decision-latency-tracker.md)** — quality AI responses accelerate decision-making
- **[Weekly Retrospectives](weekly-retrospective-guide.md)** — analyze RAG score dynamics over time

### Team Metrics
- **Average project RAG** — indicator of AI integration effectiveness
- **RAG improvement trend** — is AI interaction quality growing?
- **Component distribution** — where are the issues: R, A, or G?

---

## Scientific Foundation

The RAG approach is based on cognitive psychology and information theory research:

**Multi-dimensional quality perception:** Research shows human information quality perception includes at least three independent dimensions: need alignment (relevance), factual correctness (accuracy), and source trust (groundedness)¹.

**Composite metrics:** Weighted combinations of criteria provide more stable and predictive assessments than any single criterion².

**Neural verification principle:** The brain verifies information through multiple cognitive pathways — RAG Assessment replicates this mechanism³.

*¹ Wang, R.Y. & Strong, D.M. (1996). Beyond Accuracy: What Data Quality Means to Data Consumers. Journal of Management Information Systems.*  
*² Batini, C. & Scannapieco, M. (2016). Data and Information Quality: Dimensions, Principles and Techniques. Springer.*  
*³ Kahneman, D. (2011). Thinking, Fast and Slow. Farrar, Straus and Giroux.*

---

## Common Mistakes

### Mistake 1: Mixing Criteria
❌ **Wrong:** Lowering relevance due to missing sources  
✅ **Right:** Relevance = question match, groundedness = source quality

### Mistake 2: Perfectionism in G Assessment
❌ **Wrong:** G=0.1 because AI didn't provide direct article links  
✅ **Right:** G=0.6 if response is logically sound and mentions authoritative sources

### Mistake 3: Ignoring Task Context
❌ **Wrong:** Same RAG weights for all task types  
✅ **Right:** Adapt weights to specifics (research vs operational decisions)

### Mistake 4: No Team Calibration
❌ **Wrong:** Everyone rates by their own scale interpretation  
✅ **Right:** Team calibration on several examples at start

### Mistake 5: RAG Perfectionism
❌ **Wrong:** "This AI response got RAG 0.73, not 0.75 — I demand a recount!"  
✅ **Right:** RAG is a tool for understanding, not forensic analysis

*Remember: RAG Assessment's goal is improving AI interaction, not driving colleagues to precision-induced breakdowns.*

---

## Team Implementation

### Week 1: Calibration
1. **Select 5-7 typical AI responses** from your practice
2. **Evaluate collectively** — reach consensus on each criterion
3. **Document team standards** — what 0.8 accuracy means in your context

### Weeks 2-3: Individual Practice
1. **Each team member** assesses their AI interactions
2. **Track problem patterns** — where do low scores occur most?
3. **Experiment with queries** — how to improve RAG through phrasing

### Week 4+: Systematic Use
1. **Integrate into workflow** — RAG assessment for all significant AI consultations
2. **Analyze trends** — is interaction quality improving?
3. **Optimize prompts** — build library of high-RAG queries

---

## Context-Specific Adaptations

### Development Teams
- **R** = technical query alignment
- **A** = code/architectural solution correctness  
- **G** = references to documentation, best practices

### Marketing Teams
- **R** = target audience and channel alignment
- **A** = factual correctness of market data
- **G** = references to research, cases, data

### Research Teams
- **R** = research question alignment
- **A** = scientific correctness of claims
- **G** = source quality and relevance (increased weight)

---

## Effectiveness Measurement

### Individual Metrics
- **Average RAG score** — is your AI interaction quality growing?
- **Assessment time** — decreasing with practice (target: under 2 minutes)
- **Prediction accuracy** — do your RAG scores match actual usefulness?

### Team Metrics
- **Assessment consensus** — is score variance between participants decreasing?
- **Decision quality** — do high RAG scores correlate with successful outcomes?
- **AI usage efficiency** — is the proportion of "useful" AI consultations growing?

---

## Next Steps

1. **Try RAG assessment** on 3-5 recent AI responses from your practice
2. **Calibrate with colleagues** — discuss evaluation criteria for your context
3. **Integrate into workflow** — make RAG assessment a habit, not an event
4. **Track trends** — maintain simple statistics for improvement analysis

### Feedback
How does RAG Assessment work in your team?
- **[GitHub Discussions - Templates](https://github.com/designhumanai/neurostiv-framework/discussions/categories/templates)** — share your implementation experience
- **[Issues](https://github.com/designhumanai/neurostiv-framework/issues)** — suggestions for improving assessment criteria

---

**Author:** [Viktor Savitsky](https://github.com/designhumanai) | **Project:** [DesignHumanAI](https://designhumanai.com)  
**Version:** 1.0 | **Last updated:** 2025-01-24  
**License:** Apache 2.0

---

*Quality AI response assessment is the foundation of effective Human-AI collaboration.*
