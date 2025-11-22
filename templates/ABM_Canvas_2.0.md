# ABM Specification Canvas 2.0

---

### 1. Research Question & Purpose
* **Description:** What is the primary question this simulation seeks to answer? What is the context?
* **Input:** > 

---

### 2. Agents & Attributes
* **Description:** List the agent breeds and their specific variables (attributes). (e.g., `wolves` have `energy`, `sheep` have `speed`)
* **Input:** > 

---

### 3. Environment & Constraints
* **Description:** Define the world topology (Torus/Box), Grid/Patch size, and specific Patch variables.
* **Input:** > 

---

### 4. Process Overview & Scheduling
* **Description:** **[CRITICAL]** detailed execution order within the `to go` procedure. (e.g., 1. Move -> 2. Eat -> 3. Reproduce -> 4. Die)
* **Input:** > 

---

### 5. Behavioral Rules
* **Description:** How do individual agents move? Under what conditions do they make decisions? (Movement logic, state changes, etc.)
* **Input:** > 

---

### 6. Interaction Rules
* **Description:** What happens when agents meet (or are within a certain radius)? (e.g., Combat, Trade, Infection, Mating)
* **Input:** > 

---

### 7. Initialization (Setup)
* **Description:** The initial state when `to setup` is clicked. How many agents are created? Where are they placed? What are their starting states?
* **Input:** > 

---

### 8. Parameters (Sliders/Switches)
* **Description:** List global variables adjustable via the interface (GUI) and their default ranges. (e.g., `infection-rate` 0 ~ 100%)
* **Input:** > 

---

### 9. Evaluation Metrics (Plots/Monitors)
* **Description:** What data needs to be measured? What will be displayed on Plots or Monitors?
* **Input:** > 

---

### 10. Experiment Design
* **Description:** Scenarios for model verification and data collection.

**A. Manual Presets (Buttons)**
* **Description:** Buttons for quick testing scenarios. (e.g., "Setup Simple", "Setup High Density")
* **Input:** > 

**B. Automated Experiment (BehaviorSpace)**
* **Description:** Design for XML generation. Which variables will you sweep (range/step)? What specific metrics will you measure at the end?
* **Input:** >