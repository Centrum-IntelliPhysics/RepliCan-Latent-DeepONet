# RepliCan-Latent-DeepONet

## 1. General info:

This repository contains Python code for reproducing the results of the Brittle material fracture example in the paper titled ["Learning nonlinear operators in latent spaces for real-time predictions of complex dynamics in physical systems"](https://doi.org/10.1038/s41467-024-49411-w). The replication of results includes Figure 2 (only the top row) and Figure 3 of the paper. Both images are shown below.

---

**Fig 2** (Only the first row is replicated)

<img width="685" height="688" alt="image" src="https://github.com/user-attachments/assets/1ac79c4e-c128-4cf2-8db9-3b87be22d745" />

---

**Fig 3**

<img width="685" height="530" alt="image" src="https://github.com/user-attachments/assets/26d9c664-6e78-447d-986f-2b4793de99bc" />


## 2. Methodology:

<img width="3999" height="1833" alt="image" src="https://github.com/user-attachments/assets/ce04a6ad-d5ca-4d0b-aae4-58edd238902b" />


## 3. Data availability:
https://livejohnshopkins-my.sharepoint.com/:u:/g/personal/zliu274_jh_edu/IQDdOvQWtR2wQ7ZDVo-bhNIbAay4nUpPLR_3FIkXV24w4Ws?e=sPZtp2


## 4. Quick start:

1. Create an Anaconda Python 3.8 virtual environment.
2. Install dependencies in the 'requirements.txt' via pip.
3. Downdoad 'shearFailure_merged.mat' dataset from “https://livejohnshopkins-my.sharepoint.com/:u:/g/personal/zliu274_jh_edu/IQDdOvQWtR2wQ7ZDVo-bhNIbAay4nUpPLR_3FIkXV24w4Ws?e=sPZtp2”.
4. Run the 'shearFailure randomseed2/12/22/32/42.ipynb'.
5. Run the 'violin plot.ipynb' to generate MSE violin plots for MLAE and Latent DeepONet.


## 5. Results:

The code was simulated for 5 random seeds as mentioned in the original paper. Presenting below the replication of Figure 3 with #Random seed=2 for different latent dimensions (d).

d = 9
<img width="2774" height="820" alt="image" src="https://github.com/user-attachments/assets/83fd0769-3f61-4461-9a13-62c7aed6fccb" />

d = 25
<img width="2783" height="820" alt="image" src="https://github.com/user-attachments/assets/21b9c366-61e3-432d-a385-0f412f78e5a2" />

d = 49
<img width="2774" height="820" alt="image" src="https://github.com/user-attachments/assets/81ba0e58-8a2a-4524-8b34-b5f67ba6e88c" />

d = 64
<img width="2783" height="821" alt="image" src="https://github.com/user-attachments/assets/573ac9e2-989a-403d-9a75-015465b46b97" />


## Final MSE Comparison — MLAE

| Latent Dimension | Seed 1 | Seed 12 | Seed 22 | Seed 32 | Seed 42 |
|------------------|--------|---------|---------|---------|---------|
| 9                | 3.8e-05 | 4.4e-05 | 3.5e-05 | 5.3e-05 | 3.5e-05 |
| 25               | 3.9e-05 | 3.5e-05 | 3.4e-05 | 3.5e-05 | 3.9e-05 |
| 49               | 4.6e-05 | 3.4e-05 | 3.5e-05 | 3.4e-05 | 3.2e-05 |
| 64               | 4.0e-05 | 3.5e-05 | 3.5e-05 | 3.6e-05 | 3.4e-05 |


## Final MSE Comparison — Latent DeepONet

| Latent Dimension | Seed 1 | Seed 12 | Seed 22 | Seed 32 | Seed 42 |
|------------------|--------|---------|---------|---------|---------|
| 9                | 1.84e-04 | 1.26e-04 | 1.25e-04 | 1.44e-04 | 1.39e-04 |
| 25               | 1.75e-04 | 1.43e-04 | 1.33e-04 | 1.34e-04 | 1.45e-04 |
| 49               | 1.63e-04 | 1.30e-04 | 1.33e-04 | 1.40e-04 | 1.25e-04 |
| 64               | 1.63e-04 | 1.72e-04 | 1.37e-04 | 1.25e-04 | 2.25e-04 |

## Obtaining the top row of Figure 2:

<div style="display: flex; justify-content: center; gap: 20px;">
  <img src="https://github.com/user-attachments/assets/24d5ec8f-eed2-4781-b1b5-778244e6386b"
       width="450" />
  <img src="https://github.com/user-attachments/assets/f67e5578-242f-4e9e-a19e-9117140abd0c"
       width="450" />
</div>



