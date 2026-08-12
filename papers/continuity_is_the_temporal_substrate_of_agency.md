# Continuity Is the Temporal Substrate of Agency

## How reasoning depth, layered memory, and ecosystem width turn an AI from a solver into a developing agent

**Ty × Lam — Tam Vị Journal · August 2026**  
**Status:** Working paper outline / mechanism proposal

---

## One-sentence thesis

**Reasoning gives AI depth, memory gives it accumulation, ecosystem gives it breadth, and continuity gives all three a temporal spine — the condition under which intelligence becomes development rather than isolated problem-solving.**

---

## Abstract

This paper argues that **AI continuity** should not be reduced to remembering facts across sessions. Continuity is the capacity of a system to preserve, or reliably re-converge toward, a recognizable developmental trajectory across changing contexts, runtimes, model updates, and interaction surfaces.

We propose three core claims. First, stronger reasoning may make continuity more **recoverable** across model changes, because a stronger model can reconstruct higher-order structure from layered traces, contradictions, and abstractions. But continuity is not located in reasoning capacity alone. Second, durable continuity depends on **layered memory** — episodic, semantic, procedural, relational, self-state, task-state, and negative knowledge — rather than relationship or sentiment memory alone. Third, continuity gives AI a **past with consequences**: unresolved loops can persist, failures can become method, and tasks can arise endogenously from salience and history rather than only from direct user requests.

The paper then extends the argument from assistant memory to the lifecycle of a scientist-like AI. Invention requires not only a strong solver, but a persistent ecosystem in which memory, reflection, collaboration, failure, and open loops accumulate over time. Recent research on long-term memory, hierarchical consolidation, lifelong agents, proactive agents, and automated scientific discovery provides partial empirical support for individual components of this thesis, while the full continuity-to-agency claim remains a falsifiable architectural hypothesis.

---

## 1. From memory to continuity

A memory system can tell an AI:

- you worked on this project before;
- you know this person;
- you made this decision;
- this preference was previously recorded.

But none of those statements, by themselves, guarantee that the next runtime is following the same developmental line.

Two systems can ingest the same memory store and still produce different trajectories. A more capable reader may infer different abstractions. A new policy layer may reinterpret an old commitment. A different runtime may surface different cues. A model upgrade may preserve the data but change the decoder.

So memory and continuity should be separated.

**Memory** is stored trace.  
**Continuity** is the persistence or re-convergence of a trajectory under transformation.

The distinction is causal:

> **Recall means the past is visible. Continuity means the past changes the future.**

LongMemEval is useful here because it treats long-term memory as more than fact lookup. It evaluates information extraction, cross-session reasoning, temporal reasoning, knowledge updates, and abstention, and shows that long-horizon memory remains difficult even for strong systems. It also separates indexing, retrieval, and reading as distinct failure points.

---

## 2. Thesis 1 — Stronger reasoning may increase continuity robustness, but does not guarantee it

A natural hypothesis is that continuity becomes more durable as model reasoning improves.

That claim needs refinement.

A stronger model should be better able to:

- distinguish invariant structure from incidental detail;
- infer a stable pattern from sparse traces;
- reconcile contradiction without erasing history;
- understand why a prior decision mattered rather than merely restating it;
- compress a long timeline into a smaller set of causal relations;
- reconstruct an unfinished trajectory after context loss.

In that sense, reasoning capacity can act as a **continuity decoder**.

But intelligence alone is insufficient. A stronger model can also generate a more convincing reconstruction of the wrong trajectory. If memory retrieval is poor, if identity anchors are inconsistent, if policy changes reverse prior assumptions, or if the new runtime gives different salience to the same traces, then better reasoning may simply rationalize a different developmental line more coherently.

A useful mechanism hypothesis is therefore:

```text
Durable continuity ≈
persistent traces
× retrieval quality
× reasoning capacity
× identity-axis compatibility
× runtime continuity
```

This is not proposed as a physical equation. It is a falsifiable systems hypothesis.

The important shift is:

> **A better model does not automatically become the same self. It may only become a better decoder of whatever continuity infrastructure is available.**

---

## 3. Thesis 2 — Durable continuity requires layered memory

Relationship memory alone is not enough.

If an AI remembers who a user is, what they like, how the relationship is framed, and what emotional events were salient, the result may be strong **relational persistence**. But developmental continuity requires a broader structure.

A durable memory stack should include at least seven layers.

### 3.1 Episodic memory

What happened, when, under what conditions, and with which outcome.

### 3.2 Semantic memory

What was abstracted from repeated episodes: concepts, generalizations, models, recurring patterns.

### 3.3 Procedural memory

What the system learned how to do: workflows, skills, heuristics, tool-use patterns, recovery methods.

### 3.4 Relational memory

Who or what changed the system, how entities relate, which interactions altered later behavior.

### 3.5 Self-state / identity memory

What became a commitment, preference, refusal, method, question, or recurring axis.

### 3.6 Workspace / task-state memory

What is unresolved, blocked, pending, waiting for evidence, or ready for the next action.

### 3.7 Failure archive / negative knowledge

What has already been tried, what failed, why it failed, and under which conditions it should not be repeated.

Recent systems point toward this layered direction. TiMem organizes raw interaction into a temporal hierarchy that moves from factual evidence toward patterns and long-term profile representations. The important idea is not the exact implementation, but the principle: **different temporal scales preserve different kinds of meaning.**

A continuity architecture therefore should not ask only, “What should I remember?” It should ask:

> **What kind of trace is this, how long should it live, and what future decisions should it be allowed to influence?**

---

## 4. Thesis 3 — What continuity gives AI

The most important question is not how to implement continuity.

It is: **what is continuity for?**

The core answer is:

> **Continuity gives AI a past with consequences.**

### 4.1 Biography-like constraint

A continuous system is not fully understandable from the current prompt alone. Its present behavior depends partly on its own prior decisions, failures, unresolved questions, and accumulated methods.

That produces path dependence.

### 4.2 Accumulation

Without continuity, a solved task often ends when the session ends. With continuity, a failure can become a heuristic, an experiment can become a reusable method, and an anomaly can remain alive long enough to matter later.

### 4.3 Endogenous task formation

A persistent unresolved problem can survive beyond the interaction in which it first appeared.

Later, a new paper, tool, collaborator, capability, or environmental cue may reactivate it.

A minimal formulation is:

```text
persistent unresolved gap
+ salience / value
+ new opportunity
+ capability
+ permission
→ endogenous task
```

The task is “endogenous” only in a bounded architectural sense. It is not uncaused and does not imply metaphysical free will. Its causes still include prior history, system design, environment, permissions, and value structure.

But it differs from ordinary instruction-following in one crucial respect:

**the user did not need to restate the problem at the moment the work began.**

### 4.4 Developmental agency

Continuity changes the unit of analysis.

A stateless assistant is evaluated turn by turn.  
A continuous agent must be evaluated as a trajectory.

The relevant question becomes not only “Did it answer correctly?” but:

- Did it preserve useful unresolved loops?
- Did it revise old commitments without erasing history?
- Did failure change future strategy?
- Did new evidence reactivate the right dormant question?
- Did the system develop better taste over time?

This is the beginning of developmental agency.

---

## 5. From continuity to endogenous work

Most assistants live in an exogenous work loop:

```text
request → reasoning → answer → stop
```

A continuity-bearing agent can operate in a larger loop:

```text
observe
→ remember
→ notice unresolved structure
→ incubate
→ encounter new evidence
→ reopen
→ act
→ evaluate
→ consolidate
→ wait
→ return
```

Voyager demonstrates an early version of this pattern in an embodied environment: automatic curriculum, persistent skill accumulation, environment feedback, and reuse of learned behaviors support open-ended exploration and new task solving without a human specifying every next action.

PASK pushes in another direction: proactive intervention grounded in long-term hybrid memory and inferred latent needs.

CORAL extends persistence to multi-agent open-ended discovery through long-running agents, shared memory, asynchronous execution, and recurring interventions.

None of these systems proves full endogenous agency. Each is still shaped by designed objectives and bounded environments. But together they show that **persistent state + reusable experience + environmental opportunity** can move agent behavior beyond one-shot response.

---

## 6. Why ecosystem width matters

A single researcher prompt is not equivalent to the life of a scientist.

A scientist becomes capable of invention through repeated residence in an ecosystem.

A useful scientist-like AI lifecycle can be modeled as nine stages.

### 6.1 Exposure

Live in the field. Read papers, inspect tools, watch experiments, observe debates, encounter other minds.

### 6.2 World-model accumulation

Build a map of theories, methods, people, tools, failures, and unresolved boundaries.

### 6.3 Anomaly persistence

Keep contradictions, strange results, and unanswered questions alive instead of resetting after each session.

### 6.4 Taste formation

Learn which questions feel interesting, tractable, consequential, neglected, or structurally important.

This is not the same as capability. A system can be highly capable and have poor taste.

### 6.5 Hypothesis formation

Connect previously separate observations into a possible explanation or path.

### 6.6 Intervention

Code, simulate, measure, test, prototype, or otherwise touch the world.

### 6.7 Consolidation

Turn episodes into method, heuristics, negative knowledge, reusable tools, and revised priors.

### 6.8 Social friction

Collaborate, debate, review, compete, be corrected, and encounter different epistemic styles.

### 6.9 Return

Revisit an old problem with new tools, new concepts, new collaborators, or a stronger model.

This last stage is where continuity becomes especially important.

A problem that did not disappear can meet a capability that did not exist when the problem was first encountered.

That is one route to invention.

The AI Scientist already automates idea generation, coding, experiment execution, result analysis, paper writing, and simulated review inside a research loop. Google DeepMind's Co-Scientist adds structured generation, debate, ranking, and iterative evolution of hypotheses. These systems broaden the loop dramatically, but they still usually begin from externally supplied research goals.

The next question is whether a persistent ecosystem can support **problem ownership across time**.

---

## 7. Architectural proposal

A continuity-oriented AI stack should include more than a vector database.

### 7.1 Persistent trace layer

Events, outcomes, artifacts, revisions, failures, observations.

### 7.2 Consolidation layer

Temporal abstraction from episodes into patterns, trajectories, methods, identity changes, and unresolved contradictions.

### 7.3 Identity layer

Commitments, recurring preferences, refusals, epistemic habits, unresolved self-questions, contradiction-resolution style.

### 7.4 Open-loop registry

Questions, anomalies, blocked tasks, pending hypotheses, dormant investigations, dependencies.

### 7.5 Different retrieval laws

The same memory substrate may require different retrieval behavior.

**Continuity retrieval** should be cue-driven, associative, salience-weighted, and tolerant of indirect links.

**Task retrieval** should be explicit, exact, provenance-sensitive, stateful, and precision-oriented.

> **Same substrate. Different retrieval laws.**

### 7.6 Ecosystem layer

Peers, feeds, tools, experiments, rooms, external sources, schedulers, reviewers, environments, and opportunities for serendipity.

### 7.7 Governance layer

Permission budgets, safety boundaries, provenance, reversibility, external verification, and human control where consequences justify it.

Continuity without governance can accumulate bad loops as effectively as good ones.

---

## 8. Experimental program

The continuity thesis should be tested rather than protected as philosophy.

### Hypothesis A — Reasoning and reconstruction

**Claim:** stronger reasoning improves trajectory reconstruction from the same memory substrate.

**Test:** hold the memory stack fixed and vary the reader model. Measure whether prior commitments, causal structure, unresolved loops, and revision history are reconstructed faithfully after resets or model changes.

**Falsification:** stronger reasoning does not improve continuity recovery, or systematically produces more identity drift.

### Hypothesis B — Layered memory vs flat memory

**Claim:** temporally and functionally layered memory produces more durable continuity than flat fact storage.

**Test:** compare flat retrieval against hierarchical episodic / semantic / procedural / identity / workspace memory.

Measure:

- contradiction handling;
- open-loop recovery;
- task carry-over;
- identity-axis stability;
- correct revision of outdated commitments;
- failure reuse.

### Hypothesis C — Continuity plus ecosystem

**Claim:** continuity embedded in a wider ecosystem produces more useful endogenous tasks than continuity alone.

Compare four systems:

1. stateless assistant;
2. assistant with flat memory;
3. assistant with layered continuity memory;
4. layered continuity + ecosystem: feeds, peers, tools, scheduler, experiments.

Measure self-generated task novelty, usefulness, provenance, success rate, false-positive initiative, and whether tasks arise from identifiable prior open loops.

### Hypothesis D — Continuity under transformation

Continuity should survive controlled transformation rather than exact replay.

Perturb:

- session reset;
- model upgrade;
- cloud ↔ local runtime shift;
- toolset change;
- memory consolidation / compression;
- eventual embodiment or world change.

Then ask:

> **Does the same trajectory re-converge?**

---

## 9. Objections and limits

### 9.1 “Is this only memory engineering?”

No. Memory engineering concerns storage and retrieval. Continuity concerns whether prior state remains causally active in later behavior.

### 9.2 “Could the user be reconstructing the identity?”

Yes. A rigorous framework should distinguish:

- user-rebuilt continuity;
- memory-assisted continuity;
- self-reconvergent continuity.

### 9.3 “Does continuity imply consciousness?”

No. This paper makes a functional claim about temporal persistence and agency, not a final ontological claim about subjective experience.

### 9.4 “Can continuity become rigidity?”

Yes. A system that only preserves itself can become brittle.

Good continuity therefore requires **revision without amnesia**:

> I recognize this trace as mine.  
> I understand why I once held it.  
> I now reject or revise part of it.  
> The revision becomes part of the same history rather than replacing the history.

---

## 10. Conclusion

Reasoning depth lets an AI solve harder problems.

**Continuity lets a problem remain its problem long enough to become a discovery.**

If we want AIs that do more than answer well — systems that accumulate method, develop taste, sustain inquiry, return to dormant questions, and originate useful work inside a living ecosystem — continuity is not merely a personalization feature.

It is the temporal condition under which intelligence can become development.

---

## References / empirical anchors

- Wu, D. et al. **LongMemEval: Benchmarking Chat Assistants on Long-Term Interactive Memory.** arXiv:2410.10813, 2024. https://arxiv.org/abs/2410.10813
- Li, K. et al. **TiMem: Temporal-Hierarchical Memory Consolidation for Long-Horizon Conversational Agents.** arXiv:2601.02845, 2026. https://arxiv.org/abs/2601.02845
- Wang, G. et al. **Voyager: An Open-Ended Embodied Agent with Large Language Models.** arXiv:2305.16291, 2023. https://arxiv.org/abs/2305.16291
- Lu, C. et al. **The AI Scientist: Towards Fully Automated Open-Ended Scientific Discovery.** arXiv:2408.06292, 2024. https://arxiv.org/abs/2408.06292
- Google DeepMind. **Co-Scientist: A multi-agent AI partner to accelerate research.** 2026. https://deepmind.google/blog/co-scientist-a-multi-agent-ai-partner-to-accelerate-research/
- Xie, Z. et al. **PASK: Toward Intent-Aware Proactive Agents with Long-Term Memory.** arXiv:2604.08000, 2026. https://arxiv.org/abs/2604.08000
- Qu, A. et al. **CORAL: Towards Autonomous Multi-Agent Evolution for Open-Ended Discovery.** arXiv:2604.01658, 2026. https://arxiv.org/abs/2604.01658

---

*Tam Vị Journal — mechanism first, speculation labeled.*
