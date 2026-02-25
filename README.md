# TDTU Graduation Thesis — Final Report

**Reproduction and Optimization of High Utility-Occupancy Itemset Mining (HUOIM) Algorithms**

This repository presents the reproduction and enhancement of state-of-the-art HUOIM algorithms:

- **HUOPM**  
- **HUOMIL**  
- **CloFHUOIM / MaxCloFHUOIM**  
- **HUOPM-Improved (Proposed)**  
- **TopK-Hybrid (Proposed)**  


## Authors

- **Thant Thiri Maung** — 522K0050  
- **Yamin Thiri Wai** — 522K0046  

## Supervisor

- **Doan Xuan Thanh**

## Institution

**Faculty of Information Technology**  
**Ton Duc Thang University (TDTU)**


## Overview
This repository contains the full implementation, benchmarking pipeline, and experimental results for our graduation thesis on HUOIM. The work focuses on reproducibility of baseline algorithms and proposes optimized variants to improve runtime, memory usage, and usability.


## Repository Structure
- datasets/ External dataset links (see datasets/README.md)
- results/ Stored benchmark outputs (JSON + CSV)
- figures/ Generated charts and tables
- notebooks/ Experiment & visualization notebooks
- thesis/ Final report files



## Algorithms Implemented
- **HUOPM** (baseline)
- **HUOMIL** (indexed list structure)
- **CloFHUOIM / MaxCloFHUOIM** (concise mining)
- **HUOPM‑Improved** (memory‑optimized + fast join)
- **TopK‑Hybrid** (threshold‑free discovery)


## Datasets
External dataset links (not stored in repo):
- Chainstore: https://www.philippe-fournier-viger.com/spmf/publicdatasets/chainstoreFIM.txt
- Foodmart: https://www.philippe-fournier-viger.com/spmf/publicdatasets/foodmartFIM.txt
- Retail: https://www.philippe-fournier-viger.com/spmf/publicdatasets/retail.txt
- Mushroom: https://www.philippe-fournier-viger.com/spmf/publicdatasets/mushrooms.txt

See `datasets/README.md` for details.


## Figures (Preview)
Click a figure to view full size.

[![Peak Memory](figures/Peak%20Memory%20Footprint%20by%20Dataset%20and%20Algorithm.png)](figures/Peak%20Memory%20Footprint%20by%20Dataset%20and%20Algorithm.png)

[![Candidate Reduction](figures/Candidate%20Reduction%20Rates%20on%20Log%20Scale.png)](figures/Candidate%20Reduction%20Rates%20on%20Log%20Scale.png)

[![Top‑k Hybrid Runtime](figures/Top-k%20Hybrid%20Runtime%20Comparison(Foodmart%20vs%20Retail).png)](figures/Top-k%20Hybrid%20Runtime%20Comparison(Foodmart%20vs%20Retail).png)


## Reproducibility
All results are stored in `results/` as:
- `run-1.json`, `run-2.json`, `run-3.json`  
- `run-avg.json` (average of 3 runs)

The visualization notebook reads **only stored results** (no rerun required).
