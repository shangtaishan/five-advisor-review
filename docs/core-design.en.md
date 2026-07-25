# Core Design and Research Boundaries

**Languages:** [中文](core-design.md) · [English](core-design.en.md) · [日本語](core-design.ja.md)

## Design problems

Common failure modes in multi-agent or multi-role review include:

1. **False independence:** one model adopts five tones while retaining one reasoning path.
2. **False consensus:** five repetitions of a guess are treated as five pieces of evidence.
3. **False precision:** unsupported conversion rates, sample sizes, or success probabilities are used to sound professional.
4. **Role drift:** the opportunity finder starts executing, or the executor starts making the user's value judgment.
5. **Chair overreach:** the synthesizer introduces facts not present earlier or silently drops strong dissent.
6. **No landing:** the review is insightful but has no validation action or stop condition that can be completed today.

## Guardrails

| Failure mode | Mechanism |
|---|---|
| False independence | One review brief, isolated first round, and no claim of multi-model independence |
| False consensus | Anonymous cross-review, shared-source check, and devil's advocate |
| False precision | Evidence labels, `[Experiment threshold]`, and “unknown” when a source is absent |
| Role drift | One reasoning method and explicit responsibility boundary per advisor |
| Chair overreach | The chair may synthesize only established premises; added validation actions must trace back to identified unknowns |
| No landing | Ruthless executor's dependency graph plus chair validation criteria, checkpoint, and stop condition |

## Why advisors do not self-report confidence

An advisor's high/medium/low confidence often measures tone rather than reliability. The framework records instead:

- the critical evidence;
- the largest unknown; and
- the new evidence that would reverse the conclusion.

The chair's confidence can only be based on evidence quality, independence of reasoning paths, critical unknowns, and decision reversibility.

## Why a minority view is conditional

Minority views matter, but requiring one when no genuine minority exists encourages fabricated opposition. The correct approach is:

- when an evidence-backed minority view exists, preserve it explicitly;
- when it does not, record whether the strongest counterargument survived testing;
- do not treat opposition written merely for balance as genuine disagreement.

## Limits

- This is a cognitive and process tool; it does not replace legal, medical, financial, security, or other qualified professional advice.
- It cannot obtain real-world evidence automatically. Research, interviews, experiments, and data checks still need to happen.
- Procedural isolation reduces anchoring but cannot remove systematic bias from one model or one source set.
- Output quality is bounded by the review brief. When the target, constraints, or goals are unclear, lower confidence rather than invent assumptions.

## Research directions

1. Compare isolated first rounds with sequential discussion for diversity of assumptions.
2. Measure whether the shared-source check reduces repeated reasons being counted as multiple pieces of evidence.
3. Test whether `[Experiment threshold]` reduces fabricated industry benchmarks.
4. Back-test chair decisions against real decisions for calibration, reversibility, and validation cost.
5. Compare cost/benefit across single-model isolation, real multi-agent review, and human-AI hybrid review.
