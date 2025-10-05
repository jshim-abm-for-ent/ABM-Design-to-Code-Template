# 🧩 ABM Design-to-Code Template — v0.1-alpha  
### Initial Public Release (Work-in-Progress)

## 🌍 Overview
This is the **first public release** of the *ABM Design-to-Code Template* —  
a lightweight framework that bridges **natural-language model design** and **NetLogo implementation**.

It enables researchers, students, and educators to:
- Write ABM designs in plain English using a structured 10-section canvas.  
- Convert those descriptions into runnable **NetLogo code skeletons** with the help of LLMs (e.g., ChatGPT).  
- Standardize ABM documentation, replication, and experiment setup through a unified canvas-to-code workflow.

> ⚠️ *This version is an early alpha (v0.1-alpha) and will continue to evolve.*

## 📦 Included Files
| File | Description |
|------|--------------|
| **README.md** | Overview, quick start, and design-to-code mapping |
| **LICENSE** | MIT open-source license |
| **ABM_Canvas_Template_EN.md** | Blank code-oriented ABM design canvas (sections ①–⑩) |
| **Example_Canvas_Filled_EN.md** | Entrepreneurship network model example (filled canvas) |
| **Example_Output_Code.nlogo** | NetLogo skeleton generated from the example canvas |

## 🧩 Key Features
- **Structured ABM Canvas (①–⑩)** – covers Research Focus → Agents → Environment → Rules → Interaction → Dynamics → Metrics → Validation → Scenarios → Interpretation.  
- **Direct mapping to code:**  
  - ② → `breed`, `own`, initialization (`setup`)  
  - ③ → `globals`, environment setup  
  - ④ → behavioral logic (`to act`)  
  - ⑤ → interaction rules (`to interact`)  
  - ⑥ → simulation loop (`to go`, `tick`)  
  - ⑦ → reporters and outputs  
  - ⑧ → validation / experiment routines  
  - ⑨ → scenario & policy functions  
- **Plain-language compatible:** design in Markdown or text, then feed directly to ChatGPT / LLM.  
- **Educational ready:** useful for teaching ABM logic and simulation literacy without heavy coding barriers.  

## 🚧 Work-in-Progress (Planned for v0.2–v1.0)
| Goal | Description |
|------|--------------|
| **BehaviorSpace XML examples** | Automated multi-run experiment templates |
| **ODD / ODD+D integration** | Add a mapping table aligning Canvas sections with ODD protocol items |
| **Additional examples** | Policy diffusion, innovation dynamics, social contagion models |
| **Documentation site** | GitHub Pages or Notion-based guidebook |

## 🧠 Citation (optional)
> Shim, J. (2025). *ABM Design-to-Code Template (v0.1-alpha).*  
> GitHub repository: https://github.com/jshim-abm-for-ent/ABM-Design-to-Code-Template

## 🪪 License
MIT License — free for academic, research, and commercial use with attribution.  
See the [LICENSE](LICENSE) file for full terms.

## 🔖 Tag & Release Info
- **Tag:** `v0.1-alpha`  
- **Release Title:** *Initial alpha release — Natural Language → NetLogo ABM workflow*  
- **Branch:** `main`  

**Commit Message Example:**
```
feat: initial release of ABM Design-to-Code Template (v0.1-alpha)
```

## 🤝 Contributions
Feedback and pull requests are warmly welcome!  
You can:
- Open an **Issue** for feature ideas or improvements.  
- Submit a **Pull Request** for bug fixes or added examples.  
- Share your own “Canvas + Code” variants in `/examples` once the repo evolves.  

> © 2025 J. Shim — ABM Design-to-Code Template  
> Released under the MIT License.  
> *Empowering researchers to think in models before coding them.*
