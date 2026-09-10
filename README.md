# Global Growth Business Coach

> **Growth Knowledge Base + Diagnosis Manual + Execution Playbook + Learning Coach**

[English](./README.md) | [中文](./README.zh-CN.md)

An AI-powered learning and business coaching system designed to help users build a **transferable Growth mental model** for real-world growth problems, global markets, interviews, and day-to-day business decision-making.

Rather than teaching isolated frameworks, this project trains a repeatable reasoning process:

```text
Business Result
→ Signal
→ Metric
→ Stage
→ Segment
→ Mechanism
→ Hypothesis
→ Evidence
→ Priority
→ Action
→ Experiment
→ Learning
```

The goal is simple:

> **When facing an unfamiliar business problem, form a useful analysis path before jumping to tactics.**

---

## Live Demo

- **Website:** https://liogiyim-del.github.io/Global-growth-business-coach/
- **PRD:** https://liogiyim-del.github.io/Global-growth-business-coach/prd.html
- **Day 1–7 Gold Standards:** https://liogiyim-del.github.io/Global-growth-business-coach/examples/
- **Week 1 Transfer Test:** https://liogiyim-del.github.io/Global-growth-business-coach/examples/week1_transfer_test.html

---

## Why This Project

A common problem with Growth learning materials is that they often teach:

- frameworks without explaining when to use them
- metrics without showing how they connect
- answers without showing the diagnosis process
- success cases without failure conditions
- tactics without identifying the underlying mechanism

The result is often:

> “I understand Growth when I read it, but I still do not know how to solve a real business problem.”

This project is designed to close that gap.

---

## Core Product Philosophy

### 1. Diagnosis before Solution

The system does **not** treat this as good Growth thinking:

```text
DAU ↓ → Send Push
Retention ↓ → Add Streak
CAC ↑ → Cut Budget
```

Instead:

```text
Signal
→ Mechanism
→ Evidence
→ Tactic
```

---

### 2. Metrics must be actionable

For every important quantitative concept, the preferred structure is:

```text
Definition
→ Formula
→ Worked Example
→ Business Meaning
→ Common Misread
→ Related Metrics
```

Example:

```text
CAC = Acquisition Cost / New Customers
```

But lower CAC does not automatically mean better growth.

It must be interpreted together with:

```text
Activation
Retention
LTV
Payback Period
User Quality
```

---

### 3. Frameworks are tools, not answers

Frameworks such as:

- AARRR
- Funnel
- Metric Tree
- North Star Metric
- Growth Loop

should only be used when they reduce uncertainty.

The system is designed to avoid:

> Case → immediately apply AARRR

and instead follow:

> Business Problem → choose the minimum useful framework

---

## Four Core Modes

### Learning Mode

A structured 60-day Growth curriculum with:

- Knowledge Map
- Industry Vocabulary
- Metrics & Formulas
- Diagnosis SOP
- Execution Playbook
- Deep Cases
- Daily Challenges
- Stage-adaptive Evaluation

### Business Mode

For real business problems.

Default output structure:

```text
Executive Conclusion
→ Problem Definition
→ Known Facts / Data
→ Metric Decomposition
→ Segmentation
→ Hypotheses
→ Evidence Needed
→ Priority
→ Recommended Direction
→ Measurement / Experiment
→ Risks / Trade-offs
```

### Interview Mode

For Growth, Marketing, Product Operations, PMM, GTM, and related roles.

Includes:

- JD Analysis
- Growth Cases
- Metrics Cases
- Global Market Cases
- Mock Interviews
- Answer Evaluation

### Review Mode

For adaptive review and skill tracking.

Includes:

- Mastery
- Weakness
- Review Queue
- Case History
- Prompt Dependency

---

## 60-Day Curriculum

### Phase 1 — Growth Mental Model
Day 1–8

- Growth Fundamentals
- Growth vs Marketing / Product / Operations
- Growth Funnel
- AARRR
- North Star Metric
- Metric Tree
- Growth Loop
- Growth Diagnosis & Prioritization

### Phase 2 — User
Day 9–14

- User Segmentation
- JTBD
- Persona vs Behavioral Segment
- User Journey
- Growth User Research
- User Diagnosis Transfer Test

### Phase 3 — Acquisition
Day 15–22

- Channel Map
- Paid Acquisition
- Creative Funnel
- CAC / CPC / CPI / CPM
- Organic Growth
- KOL / Influencer Growth
- Attribution
- Acquisition Transfer Test

### Phase 4 — Activation
Day 23–27

- Activation & Aha Moment
- Onboarding
- Time to Value
- Activation Experiments
- Activation Transfer Test

### Phase 5 — Retention
Day 28–33

- Retention Cohort
- D1 / D7 / D30
- Churn
- Habit & Engagement
- Lifecycle / CRM
- Retention Transfer Test

### Phase 6 — Monetization
Day 34–38

- Monetization Fundamentals
- Payer Conversion
- Pricing & Packaging
- LTV & Payback
- Monetization Transfer Test

### Phase 7 — Experiment
Day 39–44

- Experiment Fundamentals
- Hypothesis Design
- A/B Test
- ICE / RICE
- Experiment Readout
- Experiment Transfer Test

### Phase 8 — Global Growth & GTM
Day 45–51

- Global Growth Map
- Localization
- Market × Channel × Product Fit
- GTM
- Pricing & Payment
- Trust / Regulation
- Global Growth Transfer Test

### Phase 9 — Channels
Day 52–55

- Channel Portfolio
- Lifecycle Channels
- Creator / Community Growth
- Channel Transfer Test

### Phase 10 — Integrated Cases
Day 56–60

- AI Product
- Game
- E-commerce
- SaaS / GTM
- Growth Leader Capstone

Full curriculum:

[`curriculum/60_day_curriculum.json`](./curriculum/60_day_curriculum.json)

---

## Gold Standard Prototype

The first 7 lessons are manually validated as **Gold Standard Examples**.

| Day | Topic | Core Capability |
|---|---|---|
| Day 1 | Growth Fundamentals | Knowledge Map + Diagnosis |
| Day 2 | Role Boundary | Ownership + Cross-functional Thinking |
| Day 3 | Growth Funnel | Conversion + Bottleneck Diagnosis |
| Day 4 | AARRR | Lifecycle Stage Thinking |
| Day 5 | North Star Metric | Value Metric + Guardrails |
| Day 6 | Metric Tree | Driver Decomposition |
| Day 7 | Growth Loop | Compounding Growth |

Open the lessons here:

[`examples/`](./examples/)

---

## Week 1 Transfer Test

Week 1 ends with an integrated Global AI App business case.

It tests whether the learner can connect:

```text
Growth Health
+ Funnel Calculation
+ AARRR
+ Ownership
+ Hypothesis & Evidence
+ Metric Tree
+ North Star Metric
+ Growth Loop
+ P0 Decision
```

Open:

[`examples/week1_transfer_test.html`](./examples/week1_transfer_test.html)

---

## System Architecture

```text
Intent Router
↓
Context Layer
↓
Growth Reasoning Engine
↓
Knowledge Layer
↓
Research Engine
↓
Output Engine
↓
Learning Memory
```

Core reasoning engine:

```text
Business Result
→ Signal
→ Metric
→ Stage
→ Segment
→ Mechanism
→ Hypothesis
→ Evidence
→ Priority
→ Action
→ Experiment
```

---

## Dynamic Lesson Generation

This project intentionally does **not** prewrite all 60 lessons.

Day 8–60 should be generated dynamically from:

```text
Curriculum Day Spec
+
User Mastery
+
Weakness / Review Queue
+
Knowledge Base
+
Research
+
Lesson Template
```

The Day 1–7 files are used as **few-shot Gold Standard examples** for quality control.

---

## Evaluation System

The evaluation system changes as the learner progresses.

### Day 1–15
Focus on:

- Knowledge Understanding
- Knowledge Map
- Metric Literacy
- Trigger Recognition
- Basic Diagnosis
- Transfer

### Day 16–30
Adds:

- Framework Selection
- Hypothesis
- Evidence
- Action Logic

### Day 31–45
Adds:

- Prioritization
- Trade-offs
- stronger evidence requirements

### Day 46–60
Uses full business-case evaluation.

A key rule:

> **“Not yet taught” is never treated as a weakness.**

A weakness requires repeated meaningful evidence across multiple cases.

---

## Research Standard

Real-company cases follow this source hierarchy:

1. First-party company / product / regulatory sources
2. Financial filings / reputable research
3. Strong secondary analysis
4. Community discussion for sentiment only

Case content is separated into:

- **Fact**
- **Inference**
- **Transfer**
- **Boundary / Risk**

---

## Repository Structure

```text
global-growth-business-coach/
│
├── SKILL.md
├── README.md
├── README.zh-CN.md
├── PRD.md
├── prd.html
├── SYSTEM_PROMPT.md
├── ROUTER.md
├── LEARNING_WORKFLOW.md
├── EVALUATION_RUBRIC.md
├── USER_STATE_SCHEMA.md
│
├── curriculum/
├── schemas/
├── knowledge/
├── research/
├── templates/
├── examples/
└── data/
```

---

## Product Status

**Current Version:** `V1.0.0`

- [x] Product Architecture
- [x] System Prompt
- [x] Router
- [x] Learning Workflow
- [x] Evaluation Rubric
- [x] User State Schema
- [x] 60-Day Curriculum
- [x] Day 1–7 Gold Standard
- [x] Week 1 Transfer Test
- [x] PRD V1.0
- [x] GitHub Pages
- [ ] Real learner validation
- [ ] V1.1 adaptive improvement
- [ ] Full dashboard
- [ ] Expanded case library
- [ ] Automated review system

---

## Roadmap

### V1.1

Improve through real learning sessions:

- Weakness Detection
- Review Scheduling
- Challenge Difficulty
- Formula Training
- Case Transfer

### V1.2

- Expanded Case Library
- Business Mode Templates
- Better Review Dashboard
- Richer Skill Cards

### V2

- Persistent Learning Dashboard
- Stronger Research Workflows
- Reusable Benchmark System
- Dynamic Progress Visualization

---

## Documents

- [`SKILL.md`](./SKILL.md)
- [`PRD.md`](./PRD.md)
- [`SYSTEM_PROMPT.md`](./SYSTEM_PROMPT.md)
- [`ROUTER.md`](./ROUTER.md)
- [`LEARNING_WORKFLOW.md`](./LEARNING_WORKFLOW.md)
- [`EVALUATION_RUBRIC.md`](./EVALUATION_RUBRIC.md)
- [`USER_STATE_SCHEMA.md`](./USER_STATE_SCHEMA.md)

---

## Version

`Global Growth Business Coach V1.0.0`

Prototype-validated architecture.

The next iteration will be driven by real usage, transfer-test performance, and repeated failure patterns.
