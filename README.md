# 🧠 ABM Design‑to‑Code Template (English)

Turn a plain‑language **Agent‑Based Model (ABM) design canvas** into an **executable NetLogo code skeleton** with the help of LLMs (e.g., ChatGPT).

This repository provides:
- A blank, code‑oriented **ABM Canvas** (Markdown) to capture your model design.
- A **filled example** canvas.
- A **NetLogo example output** generated from the example canvas.
- A simple, reproducible workflow for teaching, research prototyping, and scenario experiments.

> Scope: The template focuses on ABM design → NetLogo code (not UI/UX design‑to‑code).

---

## 🚀 Quick Start

1. Open `ABM_Canvas_Template_EN.md` and complete sections **①–⑩** in plain English.
2. Paste your completed canvas into your LLM with this instruction:

   ```text
   Using this canvas, generate an executable NetLogo code skeleton.
   Follow the mapping: 
   (2→breed/own/init, 3→globals/env, 4→act, 5→interact, 6→go/tick, 7→report/plots, 8→runs, 9→policy).
   ```

3. Save the generated code as `your_model.nlogo` and run it in NetLogo.

---

## 📁 Repository Structure

```
ABM-Design-to-Code-Template-EN/
├─ README.md
├─ LICENSE
├─ RELEASE_NOTES.md
├─ ABM_Canvas_Template_EN.md       # Blank, code-oriented canvas
├─ Example_Canvas_Filled_EN.md     # Filled example (entrepreneurship network)
└─ Example_Output_Code.nlogo       # Example NetLogo skeleton
```

---

## 🧩 Design → Code Mapping

- **② Agents** → `breed`, `...-own`, initialization in `setup`
- **③ Environment** → `globals`, world/patch setup
- **④ Behavioral Rules** → agent decision functions (e.g., `to act`)
- **⑤ Interaction Mechanisms** → inter-agent routines (e.g., `to interact` / links)
- **⑥ Dynamics** → `to go` loop, `tick`, updates
- **⑦ Metrics** → reporters, monitors/plots, logging
- **⑧ Validation** → experiment helpers (e.g., `to run-experiment [reps]`)
- **⑨ Scenarios** → policy toggles (e.g., `policy-mode`, `to apply-policy`)
- **⑩ Interpretation** → naming/comments only (guides meaning, not code)

---

## 🧠 Tips

- Provide a concise **① Research Focus** so variable names and comments reflect your theory.
- Start with a **full canvas** to generate a coherent skeleton, then iterate with partial updates.
- For automated sweeps, consider NetLogo’s **BehaviorSpace** or add your own loops (`run-experiment`).

---

## 🪪 License

MIT — Free to use, modify, and share.
