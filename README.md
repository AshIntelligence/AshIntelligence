# Ash Baskaran

**Product & Technology Leader · AI Systems · Platforms · Fintech · Trust**

I use these repos to work through product decisions in code: where autonomy belongs, what should stay deterministic, how controls fit into the flow, how quality is measured, and how risk turns into action.

The systems are deliberately compact. Each one is built far enough to make the product logic visible — inputs, state, policy, decision paths, failure modes and output.

## Ash Intelligence

**21 runnable systems organized around four recurring product decisions.**

| Area | What I am working through |
|---|---|
| **ORCHESTRATE** | Cross-domain context, prioritization, autonomy policy, approvals and follow-up |
| **CONTROL** | Autonomy, permissions, approval, orchestration and rollout boundaries |
| **EVALUATE** | Quality, grounding, adoption, reliability, experiments and product health |
| **DECIDE** | Risk, fintech, ranking, incident response and policy tradeoffs |

**[Open the live systems lab →](https://ash-intelligence-lab.streamlit.app/)**  
**[Open Ash OS →](https://ash-intelligence-lab.streamlit.app/Ash_OS)**  
[Browse the source →](https://github.com/AshIntelligence/agenticmine)

## Start here

### ORCHESTRATE · Ash OS — Personal Control Plane
A persistent-assistant product concept above inbox, calendar, money, career and travel. It asks four practical questions: **what changed, what matters, what can the system handle, and what still needs Ash?**

The demo routes synthetic signals to **HANDLE / DRAFT / ASK ASH / WATCH** through explicit policy for confidence, sensitivity, reversibility, spend and external commitments. High model confidence never automatically grants execution authority.

[▶ Try Ash OS live](https://ash-intelligence-lab.streamlit.app/Ash_OS) · [Source](https://github.com/AshIntelligence/agenticmine/blob/main/pages/1_Ash_OS.py)

### CONTROL · [Agent Control Plane](https://github.com/AshIntelligence/agent-control-plane)
Brings agent registration, tool authorization, approval gates, eval thresholds, cost limits, incident signals and rollout state into one control surface.

[▶ Try it live](https://ash-intelligence-lab.streamlit.app/?product=agentic-product-control-plane)

### EVALUATE · [MAUTAM — AI Product Evaluation](https://github.com/AshIntelligence/AI-Observability)
Evaluates an AI capability across model quality, adoption, workflow success, trust, availability and measurable impact, then maps the result to **SHIP / TUNE / SIMPLIFY / STOP**.

[▶ Try it live](https://ash-intelligence-lab.streamlit.app/?product=mautam-evaluation)

### DECIDE · [Risk Decision System](https://github.com/AshIntelligence/risk-decision-system)
Turns behavioral, payment and identity signals into explainable **ALLOW / REVIEW / BLOCK** decisions while keeping review load and good-user harm visible.

[▶ Try it live](https://ash-intelligence-lab.streamlit.app/?product=fraud-signal-decision-engine)

## The rest of the lab

The remaining systems extend the same four areas rather than acting as separate portfolio pieces.

- **ORCHESTRATE:** Ash OS · Personal Control Plane
- **CONTROL:** Agent vs Workflow Router · Human-in-the-Loop Router · Tool Permission Policy · Finance Close Orchestrator
- **EVALUATE:** RAG Quality Gate · Retrieval Benchmark · Support Knowledge OS · Telemetry → Product Action · Experiment Analysis · Voice of Customer Synthesis · Evidence-Weighted Prioritization · PRFAQ Product Spec
- **DECIDE:** Payment Provider Onboarding · Billing Reconciliation · Incident Triage · Career Discovery Ranking · Intentional Discovery Ranking

## How I use code as a product manager

I build enough to test the part that is easy to hand-wave in a document: state, permissions, thresholds, review paths, metrics, failure behavior and the tradeoff behind the decision.

The lab spans discovery, experimentation, prioritization, evaluation, decisioning, orchestration and platform control; code is the medium for testing the product mechanics.

- Use an agent only when the work earns the added autonomy.
- Keep deterministic work deterministic.
- Put permissions, approval and rollout rules outside model behavior.
- Treat escalation and human review as normal product states.
- Measure the product around the model, not only the model itself.
- Trace the path from input to decision to output.

Code is useful when it exposes a weak assumption faster than a deck.

## Elsewhere

**[LinkedIn](https://www.linkedin.com/in/ashb27)** · **[Live Systems Lab](https://ash-intelligence-lab.streamlit.app/)**