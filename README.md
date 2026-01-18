# RepliCan-Latent-DeepONet

## 1. General info:

This repository contains python codes for reproducing the results of Brittle material fracture example in the paper of "Learning nonlinear operators in latent spaces for real-time predictions of complex dynamics in physical systems".
<img width="685" height="530" alt="image" src="https://github.com/user-attachments/assets/26d9c664-6e78-447d-986f-2b4793de99bc" />

<img width="685" height="688" alt="image" src="https://github.com/user-attachments/assets/1ac79c4e-c128-4cf2-8db9-3b87be22d745" />


## 2. Methodology:

<img width="3999" height="1833" alt="image" src="https://github.com/user-attachments/assets/ce04a6ad-d5ca-4d0b-aae4-58edd238902b" />


## 3. Data availability:
https://livejohnshopkins-my.sharepoint.com/:u:/g/personal/zliu274_jh_edu/IQDdOvQWtR2wQ7ZDVo-bhNIbAay4nUpPLR_3FIkXV24w4Ws?e=sPZtp2


## 4. Quick start:

1. Create an Anaconda Python 3.8 virtual environment.
2. Downdoad shear failure dataset from “https://livejohnshopkins-my.sharepoint.com/:u:/g/personal/zliu274_jh_edu/IQDdOvQWtR2wQ7ZDVo-bhNIbAay4nUpPLR_3FIkXV24w4Ws?e=sPZtp2”.
3. Install dependencies in the requirements.txt via pip.
4. Run the shearFailure randomseed2/12/22/32/42.ipynb.


## 5. Results:

d=9
<img width="2784" height="820" alt="image" src="https://github.com/user-attachments/assets/3dc68e50-0566-4f4d-8cb9-4c9aa1c76edf" />

d=25
<img width="2774" height="820" alt="image" src="https://github.com/user-attachments/assets/f6309544-ff93-44a0-a783-bc3bfa69a41b" />

d=49
<img width="2774" height="820" alt="image" src="https://github.com/user-attachments/assets/c20d6e96-75ae-4cc9-8d78-ae0b48480212" />

d=64
<img width="2775" height="820" alt="image" src="https://github.com/user-attachments/assets/61606bea-27f2-42f1-a831-345d7dbf597a" />

Final MSE Comparison:

Latent Dimension|       MLAE        |  Latent DeepONet

latent_dim= 9   |   MSE: 0.000035   |   MSE: 0.000139

latent_dim=25   |   MSE: 0.000039   |   MSE: 0.000145

latent_dim=49   |   MSE: 0.000032   |   MSE: 0.000125

latent_dim=64   |   MSE: 0.000034   |   MSE: 0.000225
