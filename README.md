# Topology Optimization – Monitor Wall Mount (Altair Inspire)

![License](https://img.shields.io/badge/License-MIT-blue)
![Domain](https://img.shields.io/badge/Domain-Mechanical%20Design-brightgreen)
![Method](https://img.shields.io/badge/Method-Topology%20Optimization-orange)
![Tool](https://img.shields.io/badge/Tool-Altair%20Inspire-lightgrey)

## 📌 Overview
Lightweight redesign of a **monitor wall mount** using **FEM-based topology optimization** in **Altair Inspire**.  
Goal: cut mass significantly while maintaining structural integrity under defined loads and constraints.

---

## ⭐ STAR Summary

**Situation**  
Conventional wall-mount brackets are often over-designed, driving up weight and cost.

**Task**  
Deliver a **lightweight**, manufacturable wall-mount that **meets stiffness/strength limits** with clear, quantified savings.

**Action**  
- Built baseline assembly; defined **loads & boundary conditions** at assembly and part level.  
- Ran **topology optimization** (objective: mass minimization; constraints: displacement & stress).  
- Interpreted iso-topology into manufacturable geometry; verified with **FEA** (stress/displacement).  
- Benchmarked pre/post mass at assembly and component level.

**Result**  
- **Assembly:** mass reduced **82.58%** (**8123.92 g → 1415.18 g**).  
- **Arm:** mass reduced **65.16%** (Al 2024).  
- **Link:** mass reduced **48.92%** (Al 2024-T3).  
Design meets functional targets with a much better **mass-to-stiffness** ratio.

---

## 📊 Key Figures

### 1) Assembly – Optimized
![Assembly](docs/figures/01_Assembly.png)  
*Final optimized wall-mount assembly — total mass reduction **82.58%**.*

### 2) ARM – Topology Optimization
![Arm](docs/figures/02_Arm_Optimized.png)  
*Optimized **ARM**; mass −**65.16%** with stiffness maintained.*

### 3) LINK – Topology Optimization
![Link](docs/figures/03_Link_Optimized.png)  
*Optimized **LINK**; mass −**48.92%** with required load-path continuity.*

---

## 📂 Reports

- 📑 **Final Report (PDF):** [`TopologyOptimization_Report.pdf`](docs/reports/TopologyOptimization_Report.pdf)  
- 🖥️ **Final Presentation (PDF):** [`TopologyOptimization_Presentation.pdf`](docs/reports/TopologyOptimization_Presentation.pdf)


---

## 🧰 Method & Tooling
- **Altair Inspire**: topology optimization (mass minimization with displacement/stress bounds).  
- **FEA validation** on optimized geometry (stress & displacement).  
- **Design interpretation** from iso-surface to manufacturable CAD.

---

## 🗂️ CAD Models
To keep the repo lean, CAD is published as a release asset:

👉 **Download CAD (STEP/IGES, ZIP):**  
[`cad_models.zip`](../../releases/latest/download/cad_models.zip)

**Includes:** `Link.iges`, `Model.step`, `Monitor_Bracket.iges`, `Wall_Mount.iges`

---

## 🔑 Takeaways
- Demonstrated **lightweight engineering** with large, verified savings.  
- End-to-end **CAE workflow**: baseline → optimization → FEA → interpreted design.  
- Approach is transferable to **automotive/aerospace** components.

---

## ⚖️ License
Distributed under the [MIT License](LICENSE).
