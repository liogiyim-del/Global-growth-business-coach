# Global Growth Business Coach

> **Growth Knowledge Base + Diagnosis Manual + Execution Playbook + Learning Coach**

[English](./README.md) | [中文](./README.zh-CN.md)

一套面向真实业务问题、海外增长、求职面试与长期 Growth 学习的 AI Skill。

它不是单纯的 Growth 理论课，也不是 Framework 百科，而是希望训练一套可以迁移到陌生业务问题上的分析路径：

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

最终目标：

> **面对一个陌生业务问题，也能先形成合理的分析路径，而不是直接跳到执行方案。**

---

## 在线体验

- **Website:** https://liogiyim-del.github.io/Global-growth-business-coach/
- **PRD:** https://liogiyim-del.github.io/Global-growth-business-coach/prd.html
- **Day 1–7 Gold Standards:** https://liogiyim-del.github.io/Global-growth-business-coach/examples/
- **Week 1 Transfer Test:** https://liogiyim-del.github.io/Global-growth-business-coach/examples/week1_transfer_test.html

---

## 为什么做这个项目

很多 Growth 学习资料的问题是：

- 只讲 Framework，不讲什么时候该用
- 只讲指标定义，不讲指标关系
- 只给答案，不讲 Diagnosis
- 只讲成功案例，不讲失败条件
- 只讲 Tactic，不讲背后的 Mechanism

最后容易变成：

> “看的时候都懂，遇到真实业务问题还是不会拆。”

这个项目就是为了补上这部分。

---

## 4 个核心模式

### Learning Mode

用于系统学习 Growth：

- 60-Day Curriculum
- Knowledge Map
- Metrics & Formulas
- Diagnosis SOP
- Execution Playbook
- Deep Case
- Daily Challenge
- Stage-adaptive Evaluation

### Business Mode

用于真实业务问题。

默认结构：

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

用于 Growth、Marketing、产品运营、PMM、GTM 等岗位：

- JD Analysis
- Growth Case
- Metrics Case
- 海外市场 Case
- Mock Interview
- Answer Evaluation

### Review Mode

用于长期复习：

- Mastery
- Weakness
- Review Queue
- Case History
- Prompt Dependency

---

## 核心原则

### Diagnosis before Solution

系统不会把：

```text
DAU ↓ → Push
Retention ↓ → Streak
CAC ↑ → Cut Budget
```

当成完整 Growth 方法。

默认逻辑是：

```text
Signal
→ Mechanism
→ Evidence
→ Tactic
```

### Metrics must be usable

涉及可计算核心指标时，优先采用：

```text
Definition
→ Formula
→ Worked Example
→ Business Meaning
→ Common Misread
→ Related Metrics
```

### Frameworks are tools, not answers

AARRR、Funnel、Metric Tree、North Star Metric、Growth Loop 等 Framework 只在能够降低问题不确定性时使用。

不是：

> Case → 套 AARRR

而是：

> Business Problem → 选择最有帮助的 Framework

---

## 60-Day Curriculum

### Phase 1 — Growth Mental Model
Day 1–8

### Phase 2 — User
Day 9–14

### Phase 3 — Acquisition
Day 15–22

### Phase 4 — Activation
Day 23–27

### Phase 5 — Retention
Day 28–33

### Phase 6 — Monetization
Day 34–38

### Phase 7 — Experiment
Day 39–44

### Phase 8 — Overseas Growth & GTM
Day 45–51

### Phase 9 — Channels
Day 52–55

### Phase 10 — Integrated Cases
Day 56–60

完整课程：

[`curriculum/60_day_curriculum.json`](./curriculum/60_day_curriculum.json)

---

## Day 1–7 Gold Standard

前 7 天作为人工验证过的 Gold Standard：

| Day | Topic | Core Capability |
|---|---|---|
| Day 1 | Growth Fundamentals | Knowledge Map + Diagnosis |
| Day 2 | Role Boundary | Ownership + Cross-functional |
| Day 3 | Growth Funnel | Conversion + Bottleneck |
| Day 4 | AARRR | Lifecycle Stage Thinking |
| Day 5 | North Star Metric | Value Metric + Guardrails |
| Day 6 | Metric Tree | Driver Decomposition |
| Day 7 | Growth Loop | Compounding Growth |

课程入口：

[`examples/`](./examples/)

---

## Week 1 Transfer Test

Week 1 结束后用一个完整海外 AI App Case 测试：

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

入口：

[`examples/week1_transfer_test.html`](./examples/week1_transfer_test.html)

---

## Skill Architecture

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

---

## 动态生成课程

本项目不会提前写完 60 篇静态课程。

Day 8–60 会根据：

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

动态生成。

Day 1–7 作为 Few-shot Gold Standard，用于约束后续生成质量。

---

## Evaluation System

评分标准会随学习阶段变化。

其中一条核心规则是：

> **“没有学过”不能被记录为 Weakness。**

Weakness 需要在多个 Case 中反复出现，才会被确认。

---

## Research Standard

真实公司案例优先使用：

1. First-party company / product / regulatory sources
2. Financial filings / reputable research
3. Strong secondary analysis
4. Community discussion for sentiment only

案例必须区分：

- **Fact**
- **Inference**
- **Transfer**
- **Boundary / Risk**

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
