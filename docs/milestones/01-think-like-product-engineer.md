# Milestone 1 — Think Like a Product Engineer

## Objective

Learn to analyze a feature from the perspective of user problems, hypotheses, metrics, MVPs, and trade-offs.

This milestone should be self-contained. If you come back to this document after forgetting the conversation, it should tell you exactly what to read, what to watch, what to practice, what to produce, and when to move on.

---

## Competencies Trained

Primary:

- Product Thinking

Secondary:

- Business Thinking

---

## Why This Matters

A Product Engineer does not only ask how to build a feature. They also ask why it exists, who it serves, how success will be measured, and what trade-offs are involved.

The goal of this milestone is to build the basic mental model required to look at any feature and reason about it as a product decision.

---

## Tools Needed

- ChatGPT
- GitHub repository
- Real product features
- One book or article source at a time
- 20-30 minute focused sessions

No extra tools are required.

Do not add Notion, dashboards, courses, or automation during this milestone.

---

## Learning Resources

Use these resources in order. Do not consume everything before practicing.

### Required Resource 1 — Book

**Inspired — Marty Cagan**

Read only the parts needed for this milestone.

Focus on:

- empowered product teams;
- product discovery;
- outcomes over output;
- solving customer problems;
- product manager, designer, and engineer collaboration.

How to use it:

- Read one small section or chapter.
- Write 3 bullet points.
- Apply one idea to a real feature.

Do not read passively.

### Required Resource 2 — Article / Reference

**Continuous Discovery Habits — Teresa Torres / Product Talk**

Focus on these ideas:

- start with a clear outcome;
- discover opportunities;
- test assumptions;
- keep product, design, and engineering aligned.

How to use it:

- Read enough to understand the discovery loop.
- Apply it to one feature analysis.

Reference:

- https://www.producttalk.org/continuous-discovery-habits/

### Required Resource 3 — Metrics Reference

**Amplitude — How to Set Metrics for Product Launches**

Focus on these ideas:

- define metrics before building;
- avoid vanity or “fun fact” metrics;
- distinguish primary and secondary metrics;
- use metrics to align product, design, and engineering.

Reference:

- https://amplitude.com/blog/product-metrics

---

## Optional Resources

Use only if you want more context. They are not required to complete this milestone.

- Lenny's Newsletter: product case studies and growth/product thinking.
- Product School articles: introductory product management concepts.
- Reforge essays: growth, product strategy, retention, and activation.
- Talks or interviews with Marty Cagan, Teresa Torres, Melissa Perri, or Shreyas Doshi.

Rule:

> Optional resources should support an exercise. They should not delay practice.

---

## Concepts to Learn

By the end of this milestone, you should understand these concepts well enough to use them in writing:

### User Problem

The real friction, need, or job the user has.

Example:

> The user finds a plan they like but is not ready to buy now and may struggle to find it later.

### Hypothesis

A testable belief about how a feature may change user behavior.

Example:

> If users can save plans, they will return to them later and some will purchase from Favorites.

### Success Metric

A signal that tells us whether the feature is working.

Example:

> purchase_success with source favorites.

### Simplest Useful Version

The smallest version that can validate the hypothesis.

Example:

> Users can add/remove favorites and access a Favorites list.

### Trade-off

A cost, risk, or compromise created by the feature.

Example:

> Favorites adds UI state, empty states, sync logic, analytics, and expectations around unavailable plans.

### Questions for PM / Design

Questions that reduce ambiguity before implementation.

Example:

> What behavior are we trying to change?
> Where should the feature live so users can find it later?

---

## Working Method

For each feature analysis, follow this order:

1. Spend 5-10 minutes thinking alone.
2. Answer the analysis template in rough form.
3. Send the rough version to ChatGPT for feedback.
4. Improve the analysis.
5. Save the final version in the repository.
6. Move to the next feature.

Do not try to write a perfect first version.

The first version is for thinking. The second version is for evidence.

---

## Analysis Template

Use this template for every feature:

```markdown
# Product Analysis: <Feature Name>

## Product

## Feature

## 1. User Problem

## 2. User

## 3. Product Hypothesis

## 4. Success Metric

## 5. Simplest Useful Version

## 6. Trade-offs

## 7. Questions for PM / Design

## 8. Final Insight
```

---

## Exercises

Complete 3 product analyses.

### Exercise 1 — Fever Favorites

Status: started.

Goal:

Understand how a saving feature can reduce rediscovery friction and support delayed purchase intent.

Deliverable:

- `journal/product-analyses/01-fever-favorites.md`

### Exercise 2 — Fever Search

Status: next.

Goal:

Understand how search helps users move from vague intent or specific intent to plan discovery.

Questions to consider:

- Is search mainly for users who know what they want?
- Is search also a discovery tool?
- What happens when search returns no results?
- Should success be measured by search usage, plan views, or purchases?
- What is the difference between a good search result and a useful search experience?

Deliverable:

- `journal/product-analyses/02-fever-search.md`

### Exercise 3 — PickOne Watchlist

Status: not started.

Goal:

Apply the same product reasoning to a personal project, where no PM gives you the answer.

Questions to consider:

- Why would users save movies or shows?
- Is Watchlist about remembering, deciding, sharing, or reducing choice overload?
- What metric would show that Watchlist creates value?
- What is the simplest useful version for an MVP?

Deliverable:

- `journal/product-analyses/03-pickone-watchlist.md`

---

## Minimum Learning Before Each Exercise

Before Exercise 1:

- Read this milestone document.
- Understand the analysis template.

Before Exercise 2:

- Read one small section from Inspired about product discovery or outcomes.
- Read the Amplitude article sections about primary and secondary metrics.
- Then analyze Fever Search.

Before Exercise 3:

- Read the Product Talk article enough to understand outcomes, opportunities, and assumptions.
- Then analyze PickOne Watchlist.

---

## Feedback Loop

Each analysis receives feedback in three parts:

1. What is well reasoned.
2. What needs more depth.
3. Improved version.

The feedback should be immediate and practical.

Do not wait until all three analyses are complete.

---

## Completion Criteria

This milestone is complete when:

- 3 product analyses exist;
- each analysis uses the template;
- each analysis includes problem, user, hypothesis, metric, MVP, trade-offs, and questions;
- the player can explain a feature without starting from implementation details;
- the player can distinguish feature usage from feature value.

---

## What Not To Do

Do not:

- read an entire book before practicing;
- collect many articles;
- watch many videos without producing output;
- create a dashboard;
- add new tools;
- turn this milestone into research.

The purpose is not to know more about product.

The purpose is to think better about real features.

---

## Status

In progress.

Current next action:

> Complete Exercise 2 — Fever Search.
