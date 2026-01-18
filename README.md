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
2. Install dependencies in the requirements.txt via pip.
3. Downdoad 'shearFailure_merged.mat' dataset from “https://livejohnshopkins-my.sharepoint.com/:u:/g/personal/zliu274_jh_edu/IQDdOvQWtR2wQ7ZDVo-bhNIbAay4nUpPLR_3FIkXV24w4Ws?e=sPZtp2”.
4. Run the shearFailure randomseed2/12/22/32/42.ipynb.


## 5. Results:

#Random seed=2

d=9
<img width="2774" height="820" alt="image" src="https://github.com/user-attachments/assets/83fd0769-3f61-4461-9a13-62c7aed6fccb" />

d=25
<img width="2783" height="820" alt="image" src="https://github.com/user-attachments/assets/21b9c366-61e3-432d-a385-0f412f78e5a2" />

d=49
<img width="2774" height="820" alt="image" src="https://github.com/user-attachments/assets/81ba0e58-8a2a-4524-8b34-b5f67ba6e88c" />

d=64
<img width="2783" height="821" alt="image" src="https://github.com/user-attachments/assets/573ac9e2-989a-403d-9a75-015465b46b97" />

Final MSE Comparison:

Latent Dimension|       MLAE        |  Latent DeepONet

latent_dim= 9   |   MSE: 0.000038   |   MSE: 0.000184

latent_dim=25   |   MSE: 0.000039   |   MSE: 0.000175

latent_dim=49   |   MSE: 0.000046   |   MSE: 0.000163

latent_dim=64   |   MSE: 0.000040   |   MSE: 0.000163

---
#Random seed=12

d=9
<img width="2772" height="821" alt="image" src="https://github.com/user-attachments/assets/1aa13fdc-c8ca-4151-8fdb-79ace1ad0079" />

d=25
<img width="2774" height="820" alt="image" src="https://github.com/user-attachments/assets/93667b0e-cb4f-46ee-acf0-ff2c35157aeb" />

d=49
<img width="2773" height="820" alt="image" src="https://github.com/user-attachments/assets/4233f40c-bab5-4b92-8b50-24d2b67650bb" />

d=64
<img width="2773" height="820" alt="image" src="https://github.com/user-attachments/assets/bd8864b3-2721-48bb-98e0-5eee3aa6fcc1" />

Final MSE Comparison:

Latent Dimension|       MLAE        |  Latent DeepONet

latent_dim= 9   |   MSE: 0.000044   |   MSE: 0.000126

latent_dim=25   |   MSE: 0.000035   |   MSE: 0.000143

latent_dim=49   |   MSE: 0.000034   |   MSE: 0.000130

latent_dim=64   |   MSE: 0.000035   |   MSE: 0.000172

---
#Random seed=22

d=9
<img width="2773" height="820" alt="image" src="https://github.com/user-attachments/assets/4153aefa-54e3-4d07-af37-e98bd64ec1ef" />

d=25
<img width="2774" height="820" alt="image" src="https://github.com/user-attachments/assets/fb6bfff2-e8a6-49eb-8a47-6f3878647398" />

d=49
<img width="2774" height="820" alt="image" src="https://github.com/user-attachments/assets/f7bf5f2c-8a47-4b15-ba94-2f9f0a437a40" />

d=64
<img width="2774" height="821" alt="image" src="https://github.com/user-attachments/assets/f9eeee73-2392-4352-ad5d-746a309f52e3" />

Final MSE Comparison:

Latent Dimension|       MLAE        |  Latent DeepONet

latent_dim= 9   |   MSE: 0.000035   |   MSE: 0.000125

latent_dim=25   |   MSE: 0.000034   |   MSE: 0.000133

latent_dim=49   |   MSE: 0.000035   |   MSE: 0.000133

latent_dim=64   |   MSE: 0.000035   |   MSE: 0.000137

---
#Random seed=32

d=9
<img width="2775" height="820" alt="image" src="https://github.com/user-attachments/assets/7b90a458-b8a1-46cd-b14a-dde23162dea4" />

d=25
<img width="2783" height="820" alt="image" src="https://github.com/user-attachments/assets/495bd84e-4f51-4e39-a514-d8c77f196ebe" />

d=49
<img width="2775" height="820" alt="image" src="https://github.com/user-attachments/assets/ed485bc3-d4e8-4e45-9fde-397f183f8a4e" />

d=64
<img width="2783" height="820" alt="image" src="https://github.com/user-attachments/assets/f1511596-6e82-487d-8584-43a579be19c0" />

Final MSE Comparison:

Latent Dimension|       MLAE        |  Latent DeepONet

latent_dim= 9   |   MSE: 0.000053   |   MSE: 0.000144

latent_dim=25   |   MSE: 0.000035   |   MSE: 0.000134

latent_dim=49   |   MSE: 0.000034   |   MSE: 0.000140

latent_dim=64   |   MSE: 0.000036   |   MSE: 0.000125

---
#Random seed=42

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

<img width="1772" height="1469" alt="image" src="https://github.com/user-attachments/assets/24d5ec8f-eed2-4781-b1b5-778244e6386b" />

<img width="1772" height="1469" alt="image" src="https://github.com/user-attachments/assets/f67e5578-242f-4e9e-a19e-9117140abd0c" />



