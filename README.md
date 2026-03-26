## Regular Scenario 1
<p align="center">
  <strong>Navigation Tasks: L1 | L2 | S1</strong>
</p>

<div style="display: flex; gap: 10px; width: 100%; justify-content: center;">

  <!-- L1 列 -->
  <div style="flex: 1; text-align: center;">
    <h4>🚗 L1 Navigation</h4>
    <img src="https://github.com/user-attachments/assets/89923832-ed15-4bbb-bb89-480997e02143" 
         style="width:100%; height:120px; object-fit:cover; border-radius:4px; margin-bottom:4px;">
    <img src="https://github.com/user-attachments/assets/e79ef976-9ac5-4c70-89e2-f6ed03cc2440" 
         style="width:100%; height:120px; object-fit:cover; border-radius:4px; margin-bottom:4px;">
    <img src="https://github.com/user-attachments/assets/2c6f579c-35bf-4661-8fa7-d498bbf3910d" 
         style="width:100%; height:120px; object-fit:cover; border-radius:4px; margin-bottom:4px;">
    <img src="https://github.com/user-attachments/assets/bae1a418-db48-4a7a-ae13-3f89044ec3d7" 
         style="width:100%; height:120px; object-fit:cover; border-radius:4px;">
  </div>

  <!-- L2 列 -->
  <div style="flex: 1; text-align: center;">
    <h4>🚙 L2 Navigation</h4>
    <img src="https://github.com/user-attachments/assets/9c4c3ec1-7c69-4dc8-be37-fb946df3ab0a" 
         style="width:100%; height:248px; object-fit:cover; border-radius:4px; margin-bottom:4px;">
    <img src="https://github.com/user-attachments/assets/5f9eb42d-ec11-4103-b5d1-8643042ce78c" 
         style="width:100%; height:248px; object-fit:cover; border-radius:4px;">
  </div>

  <!-- S1 列 -->
  <div style="flex: 1; text-align: center;">
    <h4>🚛 S1 Navigation</h4>
    <img src="https://github.com/user-attachments/assets/f3fad9cf-bffc-48ea-83a5-e2a91fb3fd5d" 
         style="width:100%; height:248px; object-fit:cover; border-radius:4px; margin-bottom:4px;">
    <img src="https://github.com/user-attachments/assets/496ad4a6-2d47-4a25-9859-a123ca539487" 
         style="width:100%; height:248px; object-fit:cover; border-radius:4px;">
  </div>

</div>


## 🎥 Video Demonstrations
Video results of the proposed **STUD** framework and its ablated variants in two Out-of-Distribution (OOD) driving scenarios for unsignalized intersection navigation.
- **STUD**: Full framework (Safe Trajectory Optimization with Uncertainty-aware CBF)
- **STUD w/o SF**: STUD without Safety Filter
- **STUD w/o UA**: STUD without Uncertainty Awareness

### OOD Scenario 1
#### STUD (Full)
<video src="https://github.com/user-attachments/assets/d9745f34-b865-4a46-bce5-f2874bff3f85" width="800" controls></video>

##### Gaussian Distributions of the Probabilistic Ensemble Cost Critic
![OOD1-Probabilistic_Ensemble_Cost_Critic](https://github.com/user-attachments/assets/8ac73aed-87e2-4229-8abc-fdb8b887f28e)



#### STUD w/o SF
<video src="https://github.com/user-attachments/assets/96c17068-efcf-484b-bba2-b1f2f18b61ee" width="800" controls></video>

#### STUD w/o UA
<video src="https://github.com/user-attachments/assets/5f1c6004-154a-4be1-8228-3620e3c80ce5" width="800" controls></video>

### OOD Scenario 2
#### STUD (Full)
<video src="https://github.com/user-attachments/assets/4356ac5a-eaa0-477f-bd46-0c3b4303323a" width="800" controls></video>


##### Gaussian Distributions of the Probabilistic Ensemble Cost Critic
![OOD2-Probabilistic_Ensemble_Cost_Critic](https://github.com/user-attachments/assets/b15a0c90-c131-4a56-8c16-7e7f48d9bb65)



#### STUD w/o SF
<video src="https://github.com/user-attachments/assets/9f9b96cb-5d55-4fe8-b475-7f532127237b" width="800" controls></video>

#### STUD w/o UA
<video src="https://github.com/user-attachments/assets/1a41d9b1-eaaf-4472-9392-b81d8397440f" width="800" controls></video>
