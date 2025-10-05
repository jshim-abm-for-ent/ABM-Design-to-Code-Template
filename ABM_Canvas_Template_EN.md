# ABM Design‑to‑Code Canvas (English, Blank)

Fill in plain English. The goal is to convert this canvas into NetLogo code.

—

① Research Focus (problem & purpose)
[Your input]

② Agents Definition
2‑1. Agent Types
[Your input]
2‑2. Attributes / State Variables (per type)
[Your input]
2‑3. Initialization (counts, distributions, placement)
[Your input]

③ Environment & Structure
3‑1. Space / Network / Context
[Your input]
3‑2. Global Parameters (symbols & intended effects)
[Your input]
3‑3. Initial Structure / Conditions
[Your input]

④ Behavioral Rules (individual decision logic)
4‑1. Decision / Action per tick
[Your input]
4‑2. Conditions & Probabilities (explicit formulas if any)
[Your input]
4‑3. Internal Updates (state changes on success/failure)
[Your input]

⑤ Interaction Mechanisms (between agents)
5‑1. Target Selection
[Your input]
5‑2. Interaction Type (exchange, trust update, link ops)
[Your input]
5‑3. Interaction Effects (on both sides/system)
[Your input]

⑥ Dynamics & Temporal Process
6‑1. Time Step meaning
[Your input]
6‑2. Iteration Pattern / Update Order
[Your input]
6‑3. Time‑based Updates (decay, replenishment)
[Your input]
6‑4. Stop Condition
[Your input]

⑦ Metrics & Outputs
7‑1. Key Outcome Variables
[Your input]
7‑2. Measurement Level (agent vs system)
[Your input]
7‑3. Output Mode (plots, CSV, final snapshot)
[Your input]

⑧ Validation & Calibration
[Your input]

⑨ Scenarios / What‑if Experiments
[Your input]

⑩ Interpretation & Contribution
[Your input]

Instruction for the LLM when generating code:
- Include runnable structure: setup, go, reporter(s).
- Map: (2→breed/own/init, 3→globals/env, 4→act, 5→interact, 6→go/tick, 7→report/plots, 8→runs, 9→policy).
- Use my variable names verbatim.
- Add comments indicating canvas sections (e.g., “; [4] Behavioral Rules”).
- Prefer concise, readable code; complex UI elements are optional.
