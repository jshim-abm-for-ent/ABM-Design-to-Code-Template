# 📦 Release Notes – ABM Design-to-Code Template

---

# Release v0.2-beta — Canvas-to-NetLogo Interface Integration

**Date:** 2025-10-07  
**License:** MIT

## Overview
This beta release introduces a new feature for generating complete NetLogo 7.x model interfaces (.nlogox) directly from the ABM Design Canvas.

## Key Additions
- Seed UI Template (`widgets_7.0.nlogox`)
- Interface Builder Script (`build_nlogox_from_canvas.py`)
- Example Interface Output (`Example_Interface_From_Canvas.nlogox`)
- Configuration File (`config.json`)

## Improvements
- Enhanced reproducibility and ease of deployment for ABM prototypes.
- Unified workflow: Canvas → NLS (model code) + Canvas → NLOGOX (interface layout)

---

## [v0.1.1] – 2025-10-05
### Changed
- Refactored repository structure:
  - Introduced modular NetLogo system (`Example_Shell_Model.nlogo` + `Example_Output_Code.nls`)
  - Added `/docs/` directory for documentation and checklists
  - Revised main `README.md` for full project overview and version index
- Improved clarity in `Authors & Contributors` and `Acknowledgements` sections

### Added
- Included new `ABMS_Application_Checklist_EN.md` (in `/docs/`)
- Added explanation for future version plan: *Auto-generation workflow with prompt templates*

### Removed
- Deprecated single-file model `Example_Output_Code.nlogo` removed

---

## [v0.1-alpha] – 2025-10-05
### Initial Public Release

### 🌍 Overview
This is the **first public release** of the *ABM Design-to-Code Template* —  
a lightweight framework that bridges **natural-language model design** and **NetLogo implementation**.

It enables researchers, students, and educators to:
- Write ABM designs in plain English using a structured 10-section canvas.  
- Convert those descriptions into runnable **NetLogo code skeletons** with the help of LLMs (e.g., ChatGPT).  
- Standardize ABM documentation, replication, and experiment setup through a unified canvas-to-code workflow.

> ⚠️ *This version is an early alpha (v0.1-alpha) and will continue to evolve.*

### 📦 Included Files
| File | Description |
|------|--------------|
| **README.md** | Overview, quick start, and design-to-code mapping |
| **LICENSE** | MIT open-source license |
| **ABM_Canvas_Template_EN.md** | Blank code-oriented ABM design canvas (sections ①–⑩) |
| **Example_Canvas_Filled_EN.md** | Entrepreneurship network model example (filled canvas) |
| **Example_Output_Code.nlogo** | NetLogo skeleton generated from the example canvas |

### 🧩 Key Features
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

### 🚧 Work-in-Progress (Planned for v0.2–v1.0)
| Goal | Description |
|------|--------------|
| **BehaviorSpace XML examples** | Automated multi-run experiment templates |
| **ODD / ODD+D integration** | Add a mapping table aligning Canvas sections with ODD protocol items |
| **Additional examples** | Policy diffusion, innovation dynamics, social contagion models |
| **Documentation site** | GitHub Pages or Notion-based guidebook |

## 🤝 Contributions
Feedback and pull requests are warmly welcome!  
You can:
- Open an **Issue** for feature ideas or improvements.  
- Submit a **Pull Request** for bug fixes or added examples.  
- Share your own “Canvas + Code” variants in `/examples` once the repo evolves.  

> © 2025 J. Shim — ABM Design-to-Code Template  
> Released under the MIT License.  
> *Empowering researchers to think in models before coding them.*
