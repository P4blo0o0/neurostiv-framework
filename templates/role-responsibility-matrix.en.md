# Role Responsibility Matrix for Human-AI Teams

> **Language:** **🇺🇸 English Version** | [🇷🇺 Russian Version](role-responsibility-matrix.md)  
> **Library:** [Neurostiv Practical Templates](README.md)  
> **Version:** 1.0 | **Usage Time:** 30-45 minutes

**Clear role distribution between humans and AI in teams**

---

## The Problem

Teams with AI integration often face confusion:
- Who makes final decisions — humans or AI?
- Who's responsible for collaborative work quality?
- How do we distribute responsibility when errors occur?
- What happens when humans and AI give conflicting recommendations?

**Result of ambiguity:** Work delays, conflicts, decreased trust in AI systems.

## Neurostiv Approach

The RACI-AI role matrix — an adaptation of the classic RACI matrix for teams with AI agents, based on **Neurostiv Framework principles** and **Implementation Protocol v1.1**.

**Neurostiv Protocol foundation:**
- **Connectivity Principle** — clear information pathways between agents
- **Plasticity Principle** — ability to quickly restructure roles
- **Operational Specifications** — formalized human-AI system interaction

### Why This Matters: A Practical Example

**Situation:** A 4-person team + ChatGPT working on a new product. Client requests urgent technical requirement changes.

**Without role matrix:**
- 15 minutes spent figuring out "who will analyze the changes"
- ChatGPT gives recommendations, but no one knows how much to rely on them
- Decision gets postponed until tomorrow's call
- **Result:** 24-hour delay, team stress

**With role matrix:**
- Change analysis: Anna (**A**ccountable), ChatGPT (**AI**-support)
- Technical assessment: Sergey (**R**esponsible), Anna (**C**onsulted)
- Acceptance decision: Anna (**A**ccountable) considering recommendations
- **Result:** 2 hours for complete cycle, clear work distribution

### Economic Rationale

**Cost of role ambiguity:**
- Average team spends **18% of work time** figuring out "who does what"
- **1 hour of coordination discussions** = $200-400 lost for 5-person team
- **Project delays** of 15-25% due to decision-making unclear processes

**Role matrix ROI:**
- **45 minutes investment** in matrix creation
- **2-4 hours saved weekly** on coordination
- **Monthly savings:** $1,600-3,200 for 5-person team
- **Payback period:** Less than 1 week

The matrix defines five responsibility types for each task:

- **R** (Responsible) — **Executor** (who does the work)
- **A** (Accountable) — **Accountable** (who answers for results) 
- **C** (Consulted) — **Consultant** (who gets asked before decisions)
- **I** (Informed) — **Informed** (who gets notified about decisions)
- **AI** (AI-Supported) — **AI Support** (where AI helps but doesn't decide)

---

## How to Use It

### Step 1: Preparation (10 minutes)

**Participants:** Entire team (optimal 5-8 people)  
**Materials:** Template table, list of key team processes

**Prepare process list** — select 8-12 typical work processes:
```
Process examples:
☐ Client requirements analysis
☐ Solution option generation  
☐ Technical planning
☐ Code review
☐ Solution testing
☐ Results presentation
☐ Strategic decision making
☐ Risk management
```

### Step 2: Fill the Matrix (20 minutes)

For each process, define each team member's role:

| Process / Participant | Anna (PM) | Sergey (Dev) | Claude (AI) | QA Team |
|----------------------|-----------|--------------|-------------|---------|
| Requirements analysis | **A** | **C** | **AI** | **I** |
| Solution generation | **C** | **R** | **AI** | **I** |
| Code review | **I** | **A** | **AI** | **C** |
| Decision making | **A** | **C** | **C** | **I** |

**Filling rules:**
- Each row should have only one **A** (Accountable)
- **AI** means AI supports the process, but final decision stays with humans
- If AI got **R** or **A** — reconsider: who's really responsible for results?

### Step 3: Validation (10 minutes)

**Check matrix for contradictions:**

✅ **Correct patterns:**
- `Anna: A, Claude: AI` — human accountable, AI supports
- `Sergey: R, Claude: C` — human executes, AI consults
- `Anna: A, Sergey: R, Claude: I` — classic division with AI notification

❌ **Problem patterns:**
- `Claude: A` — AI cannot bear responsibility
- `Anna: A, Sergey: A` — two accountable parties for one process
- `Claude: R, no A among humans` — AI execution without human oversight

### Step 4: Agreement (5 minutes)

Ensure each participant understands their roles and agrees with the distribution.

---

## Template for Completion

```markdown
## Team Role Matrix: [Project Name]

**Creation Date:** ___________  
**Participants:** ___________  
**Next Review:** ___________

| Process | [Name 1] | [Name 2] | [AI System] | [Team N] |
|---------|----------|----------|-------------|----------|
| 1. _________________ | __ | __ | __ | __ |
| 2. _________________ | __ | __ | __ | __ |
| 3. _________________ | __ | __ | __ | __ |
| 4. _________________ | __ | __ | __ | __ |
| 5. _________________ | __ | __ | __ | __ |
| 6. _________________ | __ | __ | __ | __ |
| 7. _________________ | __ | __ | __ | __ |
| 8. _________________ | __ | __ | __ | __ |

**Legend:**
- **R** — Responsible (does the work)
- **A** — Accountable (answers for results)
- **C** — Consulted (asked before decisions)
- **I** — Informed (notified about decisions)
- **AI** — AI Support (helps but doesn't decide)
```

---

## Examples for Different Team Types

### Development Team (5 people + 2 AI)

| Process | Product Manager | Tech Lead | Developer | QA | ChatGPT | Copilot |
|---------|-----------------|-----------|-----------|----|---------|---------| 
| Sprint planning | **A** | **C** | **C** | **I** | **AI** | - |
| Code writing | **I** | **C** | **R** | **I** | **I** | **AI** |
| Code review | **I** | **A** | **C** | **I** | **AI** | **AI** |
| Testing | **I** | **C** | **I** | **A** | **AI** | - |
| Deployment | **C** | **A** | **R** | **C** | - | - |

### Content Marketing Team (3 people + 1 AI)

| Process | Copywriter | Editor | Designer | Claude |
|---------|------------|--------|----------|--------|
| Idea generation | **R** | **I** | **I** | **AI** |
| Text creation | **R** | **C** | - | **AI** |
| Editing | **C** | **A** | - | **AI** |
| Visual creation | **I** | **C** | **R** | **AI** |
| Final review | **C** | **A** | **C** | **I** |

---

## Scientific Foundation

The approach is based on organizational behavior research and neuroscience principles:

**Connectivity Principle:** Clear roles create predictable "connections" between team participants, reducing cognitive load on interaction planning.

**Plasticity Principle:** The matrix can quickly adapt when team composition changes or new tasks emerge.

**Research shows:** Teams with clear role distribution spend 23% less time on coordination and face 31% fewer responsibility conflicts¹.

*¹ Belbin, R.M. (2010). Management Teams: Why They Succeed or Fail. Butterworth-Heinemann.*

---

## Common Mistakes

### Mistake 1: AI as Accountable
❌ **Wrong:** `Claude: A` (AI responsible for results)  
✅ **Right:** `Anna: A, Claude: AI` (human accountable, AI supports)

### Mistake 2: Blurred Responsibility  
❌ **Wrong:** `Anna: A, Sergey: A` (two accountable parties)  
✅ **Right:** `Anna: A, Sergey: R` (one accountable, one responsible)

### Mistake 3: Ignoring AI in Processes
❌ **Wrong:** AI not included in matrix but actively used  
✅ **Right:** All significant AI systems included with **AI** or **I** role

### Mistake 4: Over-Detailed Decomposition
❌ **Wrong:** 25+ granular processes in matrix  
✅ **Right:** 8-12 key processes covering core work

---

## Effectiveness Measurement

### Short-term Indicators (1-2 weeks)
- **Reduced questions** "Who should do this?" in team chats
- **Faster decision-making** when non-standard situations arise
- **Less work duplication** between participants

### Medium-term Results (1-2 months)
- **Improved coordination** between humans and AI systems
- **Increased AI trust** through clear understanding of its role
- **Reduced time** in weekly planning meetings

### Connection to Other Templates
- **[Decision Latency Tracker](decision-latency-tracker.md)** — measure how role matrix affects decision speed
- **[Weekly Retrospectives](weekly-retrospective-guide.md)** — regularly update matrix based on feedback
- **[RAG Assessment](rag-assessment-card.md)** — use when working with AI consultants from matrix

---

## Context Adaptations

### For Large Teams (10+ people)
- Group participants by functional roles
- Use sub-matrices for sub-teams
- Assign one person responsible for maintaining matrix currency

### For Distributed Teams
- Add "Time Zone" column for participants
- Include asynchronous processes (notifications, documentation)
- Define roles for cases when key participants are unavailable

### for Project Teams
- Create matrix for each major project
- Include external stakeholders in **I** (Informed) role
- Plan matrix review at each project milestone

---

## Next Steps

1. **Fill the matrix** for your team using the template above
2. **Test for 1-2 weeks** — track how role distribution works in practice
3. **Conduct retrospective** — what works well, what needs adjustment
4. **Integrate with other templates** — start measuring decision latency and AI interaction quality

### Feedback
How does the role matrix work in your team? Share your experience:
- **[GitHub Discussions - Templates](https://github.com/designhumanai/neurostiv-framework/discussions/categories/templates)** — practical application discussion
- **[Issues](https://github.com/designhumanai/neurostiv-framework/issues)** — template improvement suggestions

---

**Author:** [Viktor Savitsky](https://github.com/designhumanai) | **Project:** [DesignHumanAI](https://designhumanai.com)  
**Version:** 1.0 | **Last updated:** 2025-01-24  
**License:** Apache 2.0

---

*Clear roles are the foundation of adaptive teams. Start with a responsibility matrix.*
