## Hybrid TSP Meta-Heuristics (Greedy + ES)

---

### Project Layout

```
tsp/
├─ README.md
├─ requirements.txt
├─ data/                # place the .npy TSP instances here
├─ results/             # optional folder for saving CSV outputs
└─ tsp_hybrid.ipynb     # main notebook with ES 
```

all `.npy` instances in `/data/`. The notebook reads from there automatically.

---

### Quickstart

1. (Optional) Create and activate a virtual environment.
2. `pip install -r requirements.txt`
3. Open `tsp_hybrid.ipynb` in JupyterLab or VS Code.
4. Run the cells from top to bottom. Change `INSTANCE_NAME` when you want to test a different problem file.

---
### Algorithm Highlights

- **ES(μ+λ)**: tournament selection, order crossover, adaptive swap mutation, and embedded 2-opt refinement.
---

### Notebook Exploration

Open `tsp_hybrid.ipynb` to:

- Discover available instances in `data/`.
- run my pipeline on data


### result 
last section of Notebook contains the final result 
---





