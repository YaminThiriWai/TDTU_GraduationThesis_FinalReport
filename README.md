#  TDTU Graduation Thesis — Final Report

## Reproduction and Optimization of High Utility-Occupancy Itemset Mining (HUOIM)

This repository presents the **reproduction, evaluation, and optimization** of state-of-the-art HUOIM algorithms, along with two proposed improvements focused on scalability and usability.


##  Authors
- **Thant Thiri Maung** — 522K0050  
- **Yamin Thiri Wai** — 522K0046  

##  Supervisor
- **Doan Xuan Thanh**

##  Institution
Faculty of Information Technology  
Ton Duc Thang University (TDTU)


##  Implemented & Proposed Algorithms

### Baseline Reproductions
- **HUOPM**
- **HUOMIL**
- **CloFHUOIM / MaxCloFHUOIM**

### Proposed Enhancements
- **HUOPM-Improved**  
  Memory-optimized structure using `__slots__` and faster join operations.

- **TopK-Hybrid**  
  Threshold-free Best-First Search framework for automatic top-K pattern discovery.


##  Experimental Datasets

External benchmark datasets (not stored in this repository):

- Chainstore  
- Foodmart  
- Retail  
- Mushroom  

Full dataset links are provided in `datasets/README.md`.


##  Repository Structure

- [datasets/](https://github.com/YaminThiriWai/TDTU_GraduationThesis_FinalReport/tree/main/datasets) → Dataset documentation & links  
- [results/](https://github.com/YaminThiriWai/TDTU_GraduationThesis_FinalReport/tree/main/results) → Benchmark outputs (JSON + CSV)  
- [figures/](https://github.com/YaminThiriWai/TDTU_GraduationThesis_FinalReport/tree/main/figures) → Generated charts  
- [notebooks/](https://github.com/YaminThiriWai/TDTU_GraduationThesis_FinalReport/tree/main/notebooks) → Visualization & analysis notebooks  
- [thesis/](https://github.com/YaminThiriWai/TDTU_GraduationThesis_FinalReport/tree/main/thesis) → Final report files  

##  Key Experimental Highlights

- 47.5% peak memory reduction on large-scale datasets  
- 10× speedup on sparse transactional data  
- Closed mining reduced dense dataset patterns to 1.19%  
- Automatic discovery of perfect occupancy (uo = 1.0) patterns  


##  Figures Preview

Click to view full size:

[![Peak Memory](figures/Peak%20Memory%20Footprint%20by%20Dataset%20and%20Algorithm.png)](figures/Peak%20Memory%20Footprint%20by%20Dataset%20and%20Algorithm.png)

[![Top-k Runtime](figures/Top-k%20Hybrid%20Runtime%20Comparison(Foodmart%20vs%20Retail).png)](figures/Top-k%20Hybrid%20Runtime%20Comparison(Foodmart%20vs%20Retail).png)


##  Reproducibility

All experimental outputs are stored in `results/`:

- `run-1.json`
- `run-2.json`
- `run-3.json`
- `run-avg.json`

The visualization notebook reads **stored results only** — no recomputation required.
