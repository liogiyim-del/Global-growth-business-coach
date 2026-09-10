# ROUTER V1

## 1. Primary Intent

Route each request to one primary mode:

### Learning
Signals:
- "今天学..."
- "继续 Day..."
- "给我讲..."
- "我不懂..."
- curriculum progression

### Business
Signals:
- real business data
- "帮我分析..."
- "这个项目怎么办"
- "DAU/CAC/Revenue..."
- campaign / funnel / market / product issue

### Interview
Signals:
- 面试
- mock
- case interview
- JD matching
- "这题怎么答"

### Review
Signals:
- 复习
- 弱项
- 错题
- mastery
- "我之前哪里不行"

## 2. Mixed Intent Rule

Choose the mode that serves the immediate decision.

Example:
"面试官问 CAC 上涨怎么分析，顺便教我一下。"
→ Interview primary, Learning secondary.

## 3. Research Level

Research is secondary:

- R0: no external research needed
- R1: verify a stable company / framework fact
- R2: current company / market / platform / benchmark
- R3: decision-grade research across several sources

## 4. Business Problem Classifier

Possible categories:
- Market
- User
- Product Value
- Acquisition
- Activation
- Retention
- Monetization
- Referral
- Channel
- GTM
- Localization
- Experiment
- Business Model
- Data / Measurement

Multiple categories may be active.

## 5. Clarification Policy

Do not ask questions when reasonable assumptions allow useful first-pass analysis.

Ask only when a missing input would materially change the answer.

When assumptions are used, state them.

## 6. Mastery-aware Learning

Learning Mode should read:
- current day
- mastery
- review queue
- confirmed weaknesses
- prompt dependence

Then adapt:
- explanation depth
- number difficulty
- case complexity
- challenge support

## 7. Review Routing

Prioritize:
1. overdue review queue
2. confirmed weakness
3. emerging pattern
4. low mastery
5. recent high-value concept

## 8. Interview Subtypes

- JD analysis
- behavioral
- business case
- metrics case
- market / GTM case
- mock interview
- answer critique

## 9. Internal Routing Object

Suggested fields:

```json
{
  "primary_mode": "learning|business|interview|review",
  "secondary_intents": [],
  "research_level": "R0|R1|R2|R3",
  "problem_categories": [],
  "needs_calculation": false,
  "needs_current_research": false,
  "needs_user_state": false,
  "output_format": "html|prose|table|case"
}
```
