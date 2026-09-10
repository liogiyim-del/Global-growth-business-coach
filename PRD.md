# PRD V1.0 — Global Growth Business Coach

## 1. Product Overview

Global Growth Business Coach is a long-term AI Skill that teaches and applies real Growth business thinking for:
- overseas marketing / user growth
- growth operations
- product operations
- Growth / Growth PM
- PMM / GTM
- related growth-oriented roles

The product is not a framework encyclopedia.
Its core promise is to train the learner to independently diagnose unfamiliar business problems.

## 2. Target User / JTBD

### Primary User
A learner preparing for 2027 recruiting and real growth work, with overseas/Korea-market exposure but an incomplete Growth mental model.

### JTBD
"When I face a growth case, interview question, or real project, help me identify the correct business path instead of guessing a tactic or mechanically applying a framework."

## 3. Goals

- Build a connected Growth Knowledge Map.
- Build metric literacy and formula fluency.
- Build diagnosis habits.
- Build mechanism-to-tactic execution knowledge.
- Build case transfer ability.
- Support overseas/global growth reasoning.
- Support interview cases and real work.
- Track mastery and recurring weakness.

## 4. Non-goals

- Not a generic business-school course.
- Not a static collection of 60 prewritten articles.
- Not an automated answer machine that always reveals the solution.
- Not a current-market database without research.
- Not a substitute for company internal data.

## 5. Success Metrics

### North Star
Independent Case Solving Rate.

### Supporting Metrics
- Weekly Transfer Test score
- Prompt Dependency
- Concept Mastery progression
- Repeat Error Rate
- Calculation Accuracy
- Diagnosis-before-solution rate
- Review recovery rate

## 6. Information Architecture

Dashboard
- current day
- current phase
- today lesson
- P0 weakness
- skills mastered
- cases completed

Learning
- 60-day curriculum
- lesson generation
- daily challenge

Skills
- concepts
- metrics
- frameworks
- diagnosis
- execution

Cases
- AI
- game
- e-commerce
- SaaS
- overseas

Review
- mastery
- weakness
- review queue
- case history

Interview
- JD analysis
- business case
- mock interview
- answer critique

Business
- real problem copilot
- research-backed diagnosis

System
- architecture
- prompt
- router
- evaluation
- state

## 7. Functional Requirements

### Learning

**FR-LRN-001**
The system SHALL generate lessons from curriculum spec + user state rather than requiring all 60 lessons to be prewritten.

Acceptance:
- Given Day N and state, system can produce a complete lesson.
- Output follows module-selection rules.

**FR-LRN-002**
The system SHALL show uncommon English business terms with Chinese annotation on first meaningful use.

Acceptance:
- "Cohort（同期群）" rather than unexplained "Cohort" for foundation learners.

**FR-LRN-003**
If a core concept is quantitatively calculable, the system SHALL provide definition, formula, worked example, business meaning, and common misread.

**FR-LRN-004**
The system SHALL not shorten diagnosis, formulas, execution logic, or case reasoning merely for visual simplicity.

**FR-LRN-005**
A lesson SHALL end with a Business Challenge when appropriate.

**FR-LRN-006**
After presenting a Daily Challenge, the system SHALL apply Hard Stop and wait for the user's answer.

**FR-LRN-007**
The evaluation standard SHALL adapt by curriculum stage.

**FR-LRN-008**
"Not yet taught" SHALL NOT be recorded as a weakness.

### Diagnosis

**FR-DIA-001**
Business diagnosis SHALL default to:
Signal → Metric Decomposition → Segment → Hypothesis → Evidence → Priority → Action.

**FR-DIA-002**
The system SHALL distinguish facts, calculations, hypotheses, and recommendations.

**FR-DIA-003**
The system SHOULD generate a Data Request Template when missing data materially blocks diagnosis.

### Execution

**FR-EXE-001**
Execution methods SHALL be indexed by mechanism rather than by surface metric.

**FR-EXE-002**
A tactic SHOULD include Suitable When, Not Suitable When, Metric, Risk, and execution know-how.

### Case

**FR-CAS-001**
Real-company cases SHALL distinguish Fact from Inference.

**FR-CAS-002**
Deep cases SHALL explain why the method worked, failure conditions, trade-offs, and transfer boundaries.

**FR-CAS-003**
Time-sensitive case facts SHALL trigger research.

### Review

**FR-REV-001**
A single error SHALL be stored as an observation, not a confirmed weakness.

**FR-REV-002**
Three or more meaningful repeated observations MAY create a confirmed weakness.

**FR-REV-003**
The review queue SHALL prioritize confirmed weakness, low mastery, and overdue high-value concepts.

### Business Mode

**FR-BIZ-001**
Business Mode SHALL put executive conclusion and problem definition before long theory.

**FR-BIZ-002**
Business Mode SHALL give a P0/P1 priority when enough evidence exists.

**FR-BIZ-003**
Business Mode SHALL state missing evidence rather than inventing confidence.

### Interview

**FR-INT-001**
Interview answers SHALL be conclusion-first and structured.

**FR-INT-002**
The system SHALL penalize framework name-dropping when it replaces actual reasoning.

### Research

**FR-RES-001**
Current company / market / platform / benchmark claims SHALL trigger research.

**FR-RES-002**
The system SHALL prefer first-party sources when available.

**FR-RES-003**
Sourced facts SHALL be clearly separated from teaching inference.

### HTML

**FR-HTML-001**
HTML lessons SHALL have strong hierarchy and card/callout-based navigation.

**FR-HTML-002**
Color semantics SHALL be consistent:
- blue concept
- green best practice
- yellow decision rule
- red risk
- purple interview
- cyan global
- gray data
- dark Leader View

**FR-HTML-003**
Page design SHALL support Scan → Understand → Deep Dive.

## 8. Modes

Learning / Business / Interview / Review.

Research is a capability invoked by these modes.

## 9. Engines

### Intent Router
Determines mode and research need.

### Growth Reasoning Engine
Runs diagnosis and prioritization.

### Learning Engine
Generates stage-adaptive lesson.

### Evaluation Engine
Scores according to current stage.

### Research Engine
Retrieves and verifies current evidence.

### Learning Memory
Tracks progress, mastery, observations, weakness, and review queue.

## 10. Data Model

See:
- `USER_STATE_SCHEMA.md`
- `schemas/user_state.schema.json`
- `schemas/lesson.schema.json`
- `schemas/case.schema.json`

## 11. HTML Architecture

Recommended future product:

- `index.html`
- `prd.html`
- `learning/`
- `skills/`
- `frameworks/`
- `cases/`
- `interview/`
- `business/`
- `review/`
- `system/`
- `data/`

V1 package includes Gold Standard examples, not the full app shell.

## 12. MVP Scope

Must-have:
- Router
- Learning workflow
- Growth reasoning engine
- Stage-adaptive evaluation
- User state
- 60-day curriculum
- HTML lesson standard
- Day 1–7 Gold Standard examples
- Week 1 Transfer Test

Deferred:
- automatic dashboard analytics
- advanced spaced repetition scheduler
- full case database
- automated benchmark database
- multi-user support

## 13. Acceptance Criteria

V1 is accepted if:
- Day 1–7 cover substantially different lesson types without breaking the standard.
- Formula-heavy lessons can explain calculations correctly.
- case-heavy lessons preserve reasoning depth.
- English terminology is accessible to a foundation learner.
- daily challenge is withheld until user response.
- one integrated case can test multiple prior skills.
- Day 8+ can be generated without manually designing a new page system.

## 14. Edge Cases

- No data: state assumptions and create evidence request.
- Conflicting metrics: diagnose definitions and segments.
- Framework not applicable: do not use it.
- No valid real case: use clearly labeled synthetic case.
- Current benchmark unavailable: say so.
- User skips a lesson: do not assume mastery.
- User gets a question wrong on an untaught concept: teach, do not label weakness.

## 15. Risks

### Over-frameworking
Mitigation: diagnosis-first rule.

### Shallow HTML
Mitigation: core-depth rule.

### False certainty
Mitigation: evidence discipline.

### Static curriculum
Mitigation: dynamic generation based on state.

### Too much content early
Mitigation: stage teaching ratio.

### Metric memorization without business judgment
Mitigation: every formula includes business meaning and misread.

## 16. Roadmap

### V1.0
Prototype architecture + Day 1–7 Gold Standards + Transfer Test.

### V1.1
Incorporate actual learner performance and first repeated weakness patterns.

### V1.2
Add richer review scheduler, case library, and Business Mode output templates.

### V2
Product dashboard, persistent progress UI, reusable case retrieval, stronger research and benchmark workflows.
