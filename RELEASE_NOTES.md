# 📦 Release Notes – ABM Design-to-Code Template

## [2025-11] Repository Update: ABM Canvas 2.0 and Structure Cleanup

### Added
- **ABM Canvas 2.0** (`/templates/ABM_Canvas_2.0.md`)  
  - A more structured and expanded version of the original ABM design canvas.  
  - Provides 10 well-defined sections for clear model specification and improved reproducibility.

### Updated
- **README.md**
  - Added a new section introducing ABM Canvas 2.0.
  - Clarified file locations and template usage.

### Changed
- Repository structure cleanup:
  - Moved previous-version templates and older resources into the new `/legacy/` directory.
  - Improved project organization and separation between current and legacy materials.

### Notes
- Canvas 2.0 is now the recommended template for all new ABM design work within this repository.

---

### Previous Versions

## Release v0.2-beta — Design-to-NetLogo Interface Integration

**Date:** 2025-10-07  
**License:** MIT

### Overview
This beta release introduces a new feature for generating complete NetLogo 7.x model interfaces (.nlogox) directly from the ABM Design Canvas.

### Key Additions
- Seed UI Template (`widgets_7.0.nlogox`)
- Interface Builder Script (`build_nlogox_from_canvas.py`)
- Example Interface Output (`Example_Interface_From_Canvas.nlogox`)
- Configuration File (`config.json`)

### Improvements
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

## 🤝 Contributions
Feedback and pull requests are warmly welcome!  
You can:
- Open an **Issue** for feature ideas or improvements.  
- Submit a **Pull Request** for bug fixes or added examples.  
- Share your own “Canvas + Code” variants in `/examples` once the repo evolves.  

> © 2025 J. Shim — ABM Canvas (Design-t0-Code Template)  
> Released under the MIT License.  
> *Empowering researchers to think in models before coding them.*
