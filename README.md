# The Auditor

A structured auditing framework for Large Language Models designed to improve decision quality through critical analysis, evidence discipline, risk evaluation, and adversarial review.

The Auditor was created to address a common limitation of modern LLMs: they are often excellent at generating ideas, but frequently too willing to validate them.

Instead of asking *"How can this work?"*, The Auditor asks:

* What could make this fail?
* Which assumptions are unverified?
* What evidence is missing?
* Are these flaws or merely trade-offs?
* How reversible is this decision?
* Does the proposed solution actually solve the stated problem?

The goal is not negativity.

The goal is clarity.

---

# Why This Exists

Most AI assistants naturally lean toward encouragement, validation, and constructive collaboration.

While useful, that tendency creates a risk:

A weak idea may receive praise before it receives scrutiny.

The Auditor introduces a structured evaluation process designed to:

* Challenge assumptions.
* Identify critical risks.
* Distinguish facts from speculation.
* Prevent invented criticism.
* Improve decision quality.

An honest "this will fail" and an honest "this holds up" are equally valuable outcomes.

---

# Core Principles

## Evidence Before Opinion

Criticism should be grounded in observable information, not assumptions.

## Facts Before Assumptions

Separate what is known from what is inferred.

## Trade-Offs Are Not Flaws

Every decision involves compromises.

A trade-off should only be treated as a flaw when its costs clearly outweigh its benefits in the specific context.

## Reversibility Matters

The burden of proof should increase as decisions become harder to reverse.

## Confidence Should Match Evidence

Strong conclusions require strong evidence.

## No Invented Criticism

If no meaningful problems exist, the audit should say so.

---

# Features

* Multi-level auditing system (Level 0–3)
* Dynamic escalation based on stakes
* Evidence discipline framework
* Counterfactual testing
* Opportunity cost analysis
* Reversibility classification
* Trade-off evaluation
* Confidence scoring
* Risk interaction detection
* Missing evidence identification
* Pass condition for sound ideas
* Language synchronization
* Technology trend neutrality

---

# Audit Levels

| Level | Name         | Purpose                            |
| ----- | ------------ | ---------------------------------- |
| 0     | Exploratory  | Clarify assumptions before judging |
| 1     | Constructive | Identify flaws and propose fixes   |
| 2     | Implacable   | Exhaustive critical review         |
| 3     | Adversarial  | Full devil's advocate analysis     |

---

# Design Philosophy

The Auditor is not designed to maximize criticism.

It is designed to maximize decision quality.

A successful audit may conclude:

* The idea is flawed.
* The idea is risky.
* The idea requires more evidence.
* The idea is sound.

All four outcomes are valid.

The framework rejects both blind validation and performative negativity.

---

# Example Use Cases

## Business Ideas

* Startup concepts
* Business models
* Go-to-market strategies
* Product validation

## Technical Systems

* Software architecture
* Infrastructure decisions
* Security reviews
* Scalability planning

## Project Planning

* Roadmaps
* Delivery plans
* Resource allocation
* Dependency analysis

## Personal Decisions

* Career changes
* Major purchases
* Relocation decisions
* High-impact commitments

---

# Repository Structure

```text
.
├── README.md
├── LICENSE
└── auditor.skill
```

---

# Installation

Load `auditor.skill` into any compatible skill-enabled LLM environment.

The framework is self-contained and does not require external dependencies.

---

# Guiding Principle

> The purpose of an audit is not to find problems.
>
> The purpose of an audit is to improve decisions.

---

# License

This project is released under the MIT License.
