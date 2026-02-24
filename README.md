# TDTU_GraduationThesis_FinalReport

Reproduction and optimization of High Utility‑Occupancy Itemset Mining (HUOIM) algorithms:
**HUOPM**, **HUOMIL**, **CloFHUOIM/MaxCloFHUOIM**, **HUOPM‑Improved**, and **TopK‑Hybrid**.

**Authors**  
- Thant Thiri Maung (522K0050)  
- Yamin Thiri Wai (522K0046)  

**Institution**  
Faculty of Information Technology, Ton Duc Thang University

---

## Overview
This repository contains the full implementation, benchmarking pipeline, and experimental results for our graduation thesis on HUOIM. The work focuses on reproducibility of baseline algorithms and proposes optimized variants to improve runtime, memory usage, and usability.

---

## Repository Structure
datasets/ Raw benchmark datasets
results/ Stored benchmark outputs (JSON + CSV)
notebooks/ Experiment & visualization notebooks
src/ Core algorithm implementations 
figures/ Generated charts and tables
thesis/ Final report files


---

## Algorithms Implemented
- **HUOPM** (baseline)
- **HUOMIL** (indexed list structure)
- **CloFHUOIM / MaxCloFHUOIM** (concise mining)
- **HUOPM‑Improved** (memory‑optimized + fast join)
- **TopK‑Hybrid** (threshold‑free discovery)

---

## Datasets
- Retail  
- Foodmart  
- Mushroom  
- Chainstore  

---

## Reproducibility
All results are stored in `results/` as:
- `run-1.json`, `run-2.json`, `run-3.json`  
- `run-avg.json` (average of 3 runs)

Visualization notebook reads only from saved results (no rerun required).

---

## License
This project is for academic research use only.  
For reuse, please contact the authors.
