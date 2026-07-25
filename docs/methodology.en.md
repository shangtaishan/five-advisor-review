# Methodology: From Role-Based Answers to a Decision Stress-Test

**Languages:** [中文](methodology.md) · [English](methodology.en.md) · [日本語](methodology.ja.md) · [Français](methodology.fr.md) · [Español](methodology.es.md)

## Purpose

Five-Advisor Review is not five roles taking turns to speak. It uses different reasoning methods to expose one proposal's vulnerabilities, overlooked opportunities, and execution blockers. The output must help a user decide whether to proceed, proceed conditionally, pause, or abandon—and what to validate next.

## Flow

```text
Review brief
  → Five isolated first-round views
  → Anonymous cross-review
  → Consensus stress-test
  → (For high risk with material disagreement) adversarial re-review
  → Chair decision and validation action
```

### 1. Review brief

First fix the proposal, goal, audience, constraints, decision at hand, and critical unknowns. Every advisor then reviews the same object instead of discussing incompatible slices such as vision versus execution.

### 2. Five isolated first-round views

Each advisor reads only the review brief and does not respond to earlier views. Isolation does not create false model independence; it reduces the chance that the first opinion anchors the rest.

| Advisor | Reasoning method | Primary output |
|---|---|---|
| Contrarian | Inversion | Likely failure mechanisms, counterexamples, long-term side effects |
| First-principles questioner | Decomposition | Causal assumptions and “why should we believe this?” questions that could change the decision |
| Opportunity finder | Analogy | Overlooked alternatives and their ordering |
| Layperson | Naive questioning | Ordinary-user questions about understanding, trust, price, and hassle |
| Ruthless executor | Dependency graph | First blocker, today's action, deliverable, and stop condition |

In full mode, every advisor also states its critical evidence, largest unknown, and reversal evidence. This is more auditable than self-reporting high, medium, or low confidence.

### 3. Anonymous cross-review

Reorder first-round views as candidates A through E without showing role identities. Review the reasoning only: which view most changes the decision, which is weakest, whether a disagreement is a value tradeoff or a factual correction, and what all five views missed together.

### 4. Consensus stress-test

Apply two checks to consensus:

- **Shared-source check:** Are most views dependent on one assumption or one reasoning path? If so, they are one opinion expressed repeatedly.
- **Devil's advocate:** What is the strongest single argument that overturns the emerging consensus? If it has a non-negligible chance of being right, carry it into the chair's decision.

### 5. Chair decision

The chair is not a sixth advisor. The chair edits, adjudicates, and integrates action: preserves evidence-backed dissent, separates value tradeoffs from factual errors, identifies blockers, and converts critical unknowns into validation actions.

The decision appears only once, after independent views and cross-review.

## Risk and output modes

| Risk | Typical case | Output |
|---|---|---|
| Low | Low cost, reversible, quickly testable | Quick mode: one sentence per advisor and one low-cost validation action |
| Medium | Moderate investment, architecture, or performance tradeoff | Full mode: isolated views, cross-review, stress-test, and validation criteria |
| High | Compliance, safety, reputation, data loss, irreversibility, or missing critical facts | Full mode plus strong validation; adversarial re-review when needed |

Users may request shorter output, but quick mode cannot disable high-risk safeguards.

## Evidence labels

| Label | Meaning |
|---|---|
| `[Verified fact]` | Verified through a reliable source or actual material |
| `[User-provided]` | From user input and not independently verified |
| `[Logical inference]` | Reasoned from known material |
| `[Critical unknown]` | Missing information that could change the conclusion |
| `[Experiment threshold]` | A temporary risk-control threshold, not an industry benchmark |

## High-risk adversarial re-review

Use a third round only for high-risk cases where material disagreement remains after the stress-test. Its purpose is not convergence; it makes each position confront the strongest counterargument and update its evidence, unknowns, and reversal evidence.
