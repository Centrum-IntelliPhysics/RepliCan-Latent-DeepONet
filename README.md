# RepliCan-Latent-DeepONet

## 1. General info:

This repository contains python codes for reproducing the results of Brittle material fracture example in the paper of "Learning nonlinear operators in latent spaces for real-time predictions of complex dynamics in physical systems".


## 2. Methodology:

<img width="3999" height="1833" alt="image" src="https://github.com/user-attachments/assets/ce04a6ad-d5ca-4d0b-aae4-58edd238902b" />


## 3. Data availability:


## 4. Quick start:

1. Create an Anaconda Python 3.8 virtual environment.
2. Downdoad shear failure dataset from .
3. Install dependencies in the requirements.txt via pip.
4. Run the shearFailure.ipynb.


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

latent_dim= 9 | Final Test MSE: 0.000139

latent_dim=25 | Final Test MSE: 0.000145

latent_dim=49 | Final Test MSE: 0.000125

latent_dim=64 | Final Test MSE: 0.000225
