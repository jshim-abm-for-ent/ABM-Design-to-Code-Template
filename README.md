# 🧩 ABM Design-to-Code Template

> **Natural-language ABM design → executable NetLogo code framework**  
> A lightweight, open-source template for transforming conceptual agent-based models (ABMs) into runnable NetLogo simulations.

---

## 📘 Overview
This repository provides a unified workflow that helps researchers and students:
- Design ABM logic in **natural language** (structured through an ABM Canvas),
- Automatically transform it into **NetLogo code**, and
- Conduct **simulation experiments (BehaviorSpace)**.

---

## 🧱 Repository Structure

| Folder / File | Description |
|----------------|-------------|
| `/templates/ABM_Canvas_Template_EN.md` | Blank ABM Canvas template (10 sections) |
| `/templates/Example_Canvas_Filled_EN.md` | Example canvas (Entrepreneurship Network) |
| `/versions/v0.1-alpha/Example_Output_Code.nls` | Generated NetLogo source code (NLS format) |
| `/versions/v0.1-alpha/Example_Shell_Model.nlogo` | NetLogo model file that includes the `.nls` source |
| `/RELEASE_NOTES.md` | Release details for each version |
| `/LICENSE` | MIT License |

---

## 🚀 Quick Start

### Option 1: Run the Example Model
1. Open **NetLogo**.  
2. Load `/versions/v0.1-alpha/Example_Shell_Model.nlogo`.  
3. The model automatically includes `Example_Output_Code.nls`.  
4. Click `setup` → `go` to start simulation.

### Option 2: Create Your Own Model
1. Copy `/templates/ABM_Canvas_Template_EN.md`.  
2. Fill out sections (1–10) in natural language.  
3. Use ChatGPT or the provided Python scripts to transform your canvas into NetLogo code.  
4. Save as `.nls` and include it from a `.nlogo` shell model.

---

## 🧩 Release Versions

| Version | Description | Link |
|----------|--------------|------|
| `v0.1-alpha` | Initial NLS include-based implementation | [README_NLS.md](versions/v0.1-alpha/README_NLS.md) |
| `v0.2-beta` *(planned)* | Auto-generation workflow with prompt templates | _TBA_ |

---

## 🧠 Research & Educational Use
The project aims to:
- Lower technical barriers to ABM development,  
- Enable reproducible simulation design through structured documentation, and  
- Support entrepreneurship and social-science ABM research.

---

## 🧩 Authors & Contributors
This project is co-developed by:

- **Jaehu Shim**, KAIST School of Business and Technology Management (K-School)  
- **Jiyoung Kimjeon**, Jönköping International Business School  

Please cite the repository in publications as:

> [https://github.com/jshim-abm-for-ent/ABM-Design-to-Code-Template](https://github.com/YourUserName/ABM-Design-to-Code-Template)

## 📄 License
MIT License — free for academic, educational, and commercial use.  

---

## 🧰 Acknowledgements
Inspired by ABM Canvas and ODD+D.
