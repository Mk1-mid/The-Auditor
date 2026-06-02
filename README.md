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

The Auditor is distributed as a standalone `.skill` file.

Because skill systems differ across platforms, installation depends on the environment being used.

---

## Web-Based LLM Interfaces

For platforms that support custom instructions, system prompts, skills, agents, or projects:

1. Open the platform's customization or configuration settings.
2. Create a new custom skill, agent, project, or instruction set.
3. Copy the contents of `auditor.skill`.
4. Save the configuration.
5. Start a new conversation.

Examples may include:

* ChatGPT Projects
* Claude Projects
* Gemini Gems
* Custom AI workspaces
* Other instruction-enabled interfaces

Refer to the platform documentation for exact steps.

---

## IDE Integrations

For AI assistants integrated into development environments:

1. Locate the custom instructions, agent, rules, or skills configuration area.
2. Import or paste the contents of `auditor.skill`.
3. Save the configuration.
4. Restart the assistant if required.

Examples may include:

* Cursor
* Windsurf
* Cline
* Roo Code
* Continue
* Other AI-powered IDE extensions

---

## CLI-Based Assistants

For command-line AI environments:

1. Create a custom skill, system prompt, or instruction file according to the platform's documentation.
2. Copy the contents of `auditor.skill`.
3. Load the file through the CLI's configuration system.
4. Verify the assistant recognizes the skill.

Examples may include:

* Claude Code
* OpenAI Codex CLI
* OpenCode
* Aider
* Other terminal-based AI tools

---

## Manual Usage

If your platform does not support skills directly:

1. Open `auditor.skill`.
2. Copy its contents.
3. Paste it into the system prompt, project instructions, or custom instructions section.

The framework is self-contained and does not require external dependencies.

---

# Compatibility

The Auditor is platform-agnostic.

It is designed around behavioral instructions rather than platform-specific features.

Any LLM environment capable of accepting structured instructions, custom prompts, skills, agents, rules, or project-level guidance should be able to use The Auditor.

---

# Verification

After installation, test with:

* "Audit this startup idea."
* "What are the flaws in this architecture?"
* "Give me a Level 2 audit of this roadmap."
* "What could go wrong with this decision?"

If the assistant responds using structured critical analysis rather than simple validation, the installation was successful.

---

# Guiding Principle

> The purpose of an audit is not to find problems.
>
> The purpose of an audit is to improve decisions.

---

# License

This project is released under the MIT License.
