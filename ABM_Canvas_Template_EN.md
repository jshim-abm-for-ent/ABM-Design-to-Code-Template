# ABM Design‑to‑Code Canvas (English, Blank)

Fill in plain English. The goal is to convert this canvas into NetLogo code.

—

## 1. Research Question & Purpose  
[Your input]

## 2. Agents & Variables  
2‑1. Agent Types  
[Your input]

2‑2. Attributes / State Variables (per type)  
[Your input]

## 3. Behavioral Rules (individual decision logic)  
3‑1. Decision / Action per tick  
[Your input] 

3‑2. Conditions & Probabilities (explicit formulas if any)  
[Your input]

3‑3. Internal Updates (state changes on success/failure)  
[Your input]

## 4. Interaction Mechanisms (between agents)  
4‑1. Target Selection  
[Your input]

4‑2. Interaction Type (exchange, trust update, link ops)  
[Your input]

4‑3. Interaction Effects (on both sides/system)  
[Your input]

## 5. Environment & Structure  
5‑1. Space / Network / Context  
[Your input]

5‑2. Initial Structure / Conditions  
[Your input]  
 
## 6. Initialization & Temporal Process  
6‑1. Initialization (counts, distributions, placement)  
[Your input]

6‑2. Iteration Pattern / Update Order  
[Your input]

6‑3. Time Step meaning  
[Your input]

6‑4 Time‑based Updates (decay, replenishment)  
[Your input]

6‑5. Stop Condition  
[Your input]

## 7. Parameters  
[Your input]

## 8. Metrics & Evaluation  
8‑1. Key Outcome Variables  
[Your input]

8‑2. Measurement Level (agent vs system)  
[Your input]

8‑3. Output Mode (plots, CSV, final snapshot)  
[Your input]

## 9. Scenarios & Experiments  
[Your input]

## 10. Interpretation & Insights  
[Your input]

Instruction for the LLM when generating code:  
- Include runnable structure: setup, go, reporter(s).  
- Map: (2→breed, -own, 3→to go, ask agents, formulas, 4→link creation, resource exchange, influence update, 5→patches, links, topology setup, 6→setup, go, tick logic, 7→globals, BehaviorSpace parameters, 8→to-report, monitor, export, 9→BehaviorSpace or scenario setup).  
- Use my variable names verbatim.  
- Add comments indicating canvas sections.  
- Prefer concise, readable code; complex UI elements are optional.
