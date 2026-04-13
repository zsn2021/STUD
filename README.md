# Safe Training and Uncertainty-aware Deployment for Autonomous Navigation at Unsignalized Intersections via Constrained Reinforcement Learning with Safety Filtering


## 📑 Table of Contents
- [Regular Scenarios Demonstrations](#-regular-scenarios-demonstrations)
  - [Regular Scenario 1](#regular-scenario-1)
  - [Regular Scenario 2](#regular-scenario-2)
- [OOD Scenarios Demonstrations](#-ood-scenarios-demonstrations)
  - [OOD Case 1](#ood-case-1)
  - [OOD Case 2](#ood-case-2)
  - [OOD Case 3](#ood-case-3)


## 🎬 Regular Scenarios Demonstrations
Evaluation videos of the proposed **STUD** framework in two regular driving scenarios for unsignalized intersection navigation.

### Regular Scenario 1

#### Navigation Task: L1

| case1 | case2 | case3 |
|---|---|---|
| <img src="https://github.com/user-attachments/assets/a3ff662f-bcae-4d1c-82e4-6beadf6442fe" alt="scenario1-seed27_L1" width="250"> | <img src="https://github.com/user-attachments/assets/196f44b3-5c0f-41c8-afcb-426889ba561c" alt="scenario1-seed5_L1" width="250"> | <img src="https://github.com/user-attachments/assets/311bd9dd-23f5-4181-a90f-713e01e20768" alt="scenario1-seed8_L1" width="250"> |

#### Navigation Task: L2

| case1 | case2 | case3 |
|---|---|---|
| <img src="https://github.com/user-attachments/assets/2627f579-b14a-49d9-bbf0-b7fe8c93de0b" alt="scenario1-seed0_L2" width="250"> | <img src="https://github.com/user-attachments/assets/8a005087-ceeb-485b-b7bd-9534ec6641a6" alt="scenario1-seed2_L2" width="250"> | <img src="https://github.com/user-attachments/assets/7d64414c-ee16-4195-aa7b-ac6346c5c0f6" alt="scenario1-seed28_L2" width="250"> |

#### Navigation Task: S1

| case1 | case2 | case3 |
|---|---|---|
| <img src="https://github.com/user-attachments/assets/b6530fb6-714e-4132-9121-53140f53d9c5" alt="scenario1-seed4_S1" width="250"> | <img src="https://github.com/user-attachments/assets/7a465490-9494-44a2-8dad-aa9482ac9d62" alt="scenario1-seed6_S1" width="250"> | <img src="https://github.com/user-attachments/assets/baffb054-1120-4580-82dd-23dc96b92226" alt="scenario1-seed24_S1" width="250"> |

### Regular Scenario 2

#### Navigation Task: R1

| case1 | case2 | case3 |
|---|---|---|
| <img src="https://github.com/user-attachments/assets/3ab20a33-3bcc-4827-9c92-0dc9a967ab7b" alt="scenario2-seed5_R1" width="250"> | <img src="https://github.com/user-attachments/assets/0bbb0ec3-6f69-4301-80c5-071ef417642b" alt="scenario2-seed7_R1" width="250"> | <img src="https://github.com/user-attachments/assets/30750cb0-a609-44da-9ca5-2d9e549b5e3e" alt="scenario2-seed9_R1" width="250"> |

#### Navigation Task: R2

| case1 | case2 | case3 |
|---|---|---|
| <img src="https://github.com/user-attachments/assets/ae067579-c792-447d-a79e-af5db639399d" alt="scenario2-seed0_R2" width="250"> | <img src="https://github.com/user-attachments/assets/696d0a47-9975-471e-9517-1e72b3903d28" alt="scenario2-seed11_R2" width="250"> | <img src="https://github.com/user-attachments/assets/b813dea0-8225-4db9-a200-74451422c5fc" alt="scenario2-seed15_R2" width="250"> |

#### Navigation Task: S2

| case1 | case2 | case3 |
|---|---|---|
| <img src="https://github.com/user-attachments/assets/f5bafcf0-3e4b-4fa6-9ca1-0abb7b5d90b8" alt="scenario2-seed4_S2" width="250"> | <img src="https://github.com/user-attachments/assets/06bff9b6-bb0c-4431-b286-9d793fe9c503" alt="scenario2-seed6_S2" width="250"> | <img src="https://github.com/user-attachments/assets/e5363347-b1eb-4921-95e3-8b0f13665124" alt="scenario2-seed12_S2" width="250"> |

## 🎥 OOD Scenarios Demonstrations

Video results of the proposed **STUD** framework and its ablated variants in three Out-of-Distribution (OOD) driving scenarios for unsignalized intersection navigation.

- **STUD**: STUD with UA-HOCBF  
- **STUD w/o UA**: STUD with standard HOCBF  
- **STUD w/o SF**: STUD without safety filtering  

---

### OOD Case 1
#### Navigation Task: L1

<p align="center">
  <img src="https://github.com/user-attachments/assets/bf5d0a49-068f-41b9-9485-77afaffabaf1" width="500"/>
</p>
<p align="center"><em>Trajectories of STUD and its ablation variants in navigation task L1.</em></p>



##### STUD (Full)
<video src="https://github.com/user-attachments/assets/0dc9bcf6-a362-421b-a851-c49fff66ef40" width="800" controls></video>

##### STUD w/o UA
<video src="https://github.com/user-attachments/assets/6746b3fe-b70f-48ea-a138-c7ca803fd487" width="800" controls></video>

##### STUD w/o SF
<video src="https://github.com/user-attachments/assets/d329367d-9e32-46e1-96a1-45fa4a7c1def" width="800" controls></video>

---

### OOD Case 2
#### Navigation Task: L2

<p align="center">
  <img src="https://github.com/user-attachments/assets/9d72fb0b-59f0-4033-afa1-4e401e63f1f0" width="500"/>
</p>
<p align="center"><em>Trajectories of STUD and its ablation variants in navigation task L2.</em></p>



##### STUD (Full)
<video src="https://github.com/user-attachments/assets/3d3675e6-c2bc-4501-a38f-fc31eb896f7f" width="800" controls></video>

##### STUD w/o UA
<video src="https://github.com/user-attachments/assets/ac7cacca-2575-441d-8208-e60e6c3ffbab" width="800" controls></video>

##### STUD w/o SF
<video src="https://github.com/user-attachments/assets/10f69ac9-633a-4fdc-97bb-02ee587a5d7a" width="800" controls></video>

---

### OOD Case 3
#### Navigation Task: S2

<p align="center">
  <img src="https://github.com/user-attachments/assets/da5b9d02-9260-4bfe-a857-08f36730a774" width="500"/>
</p>
<p align="center"><em>Trajectories of STUD and its ablation variants in navigation task S1.</em></p>



#### STUD (Full)
<video src="https://github.com/user-attachments/assets/7e7d2aff-99cb-4eee-8db4-5f9e4ab09ecd" width="800" controls></video>

#### STUD w/o UA
<video src="https://github.com/user-attachments/assets/754394fd-bf7b-4ade-8ead-6bce940bbe9b" width="800" controls></video>

#### STUD w/o SF
<video src="https://github.com/user-attachments/assets/5bc1ad34-fa48-4016-a1ce-f0c4260f10f9" width="800" controls></video>

## ❤️ Acknowledgements

We gratefully acknowledge the open-source repositories **HighwayEnv** and **FSRL**, which provide essential support for environment construction and safe reinforcement learning implementation in this project.  
- **HighwayEnv**: [https://github.com/Farama-Foundation/HighwayEnv  ](https://github.com/Farama-Foundation/HighwayEnv)
- **FSRL**: [https://github.com/zsn2021/FSRL](https://github.com/liuzuxin/FSRL)


