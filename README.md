<a id="top"></a>

## 📑 Table of Contents
- [Regular Scenarios](#regular-scenario-demonstrations)
  - [Regular Scenario 1](#regular-scenario-1)
    - [Navigation Task: L1](#navigation-task-l1)
    - [Navigation Task: L2](#navigation-task-l2)
    - [Navigation Task: S1](#navigation-task-s1)
  - [Regular Scenario 2](#regular-scenario-2)
    - [Navigation Task: R1](#navigation-task-r1)
    - [Navigation Task: R2](#navigation-task-r2)
    - [Navigation Task: S2](#navigation-task-s2)
- [Out-of-Distribution Scenarios](#video-demonstrations)
  - [OOD Scenario 1](#ood-scenario-1)
    - [STUD (Full)](#ood1-stud-full)
    - [STUD w/o UA](#ood1-stud-wo-ua)
    - [STUD w/o SF](#ood1-stud-wo-sf)
  - [OOD Scenario 2](#ood-scenario-2)
    - [STUD (Full)](#ood2-stud-full)
    - [STUD w/o UA](#ood2-stud-wo-ua)
    - [STUD w/o SF](#ood2-stud-wo-sf)

<a id="regular-scenario-demonstrations"></a>
## 🎬 Regular Scenario Demonstrations
Evaluation videos of the proposed **STUD** framework in two regular driving scenarios for unsignalized intersection navigation.

<a id="regular-scenario-1"></a>
### Regular Scenario 1

<a id="navigation-task-l1"></a>
#### Navigation Task: L1

| case1 | case2 | case3 |
|---|---|---|
| <img src="https://github.com/user-attachments/assets/a3ff662f-bcae-4d1c-82e4-6beadf6442fe" alt="scenario1-seed27_L1" width="250"> | <img src="https://github.com/user-attachments/assets/196f44b3-5c0f-41c8-afcb-426889ba561c" alt="scenario1-seed5_L1" width="250"> | <img src="https://github.com/user-attachments/assets/311bd9dd-23f5-4181-a90f-713e01e20768" alt="scenario1-seed8_L1" width="250"> |

<a id="navigation-task-l2"></a>
#### Navigation Task: L2

| case1 | case2 | case3 |
|---|---|---|
| <img src="https://github.com/user-attachments/assets/2627f579-b14a-49d9-bbf0-b7fe8c93de0b" alt="scenario1-seed0_L2" width="250"> | <img src="https://github.com/user-attachments/assets/8a005087-ceeb-485b-b7bd-9534ec6641a6" alt="scenario1-seed2_L2" width="250"> | <img src="https://github.com/user-attachments/assets/7d64414c-ee16-4195-aa7b-ac6346c5c0f6" alt="scenario1-seed28_L2" width="250"> |

<a id="navigation-task-s1"></a>
#### Navigation Task: S1

| case1 | case2 | case3 |
|---|---|---|
| <img src="https://github.com/user-attachments/assets/b6530fb6-714e-4132-9121-53140f53d9c5" alt="scenario1-seed4_S1" width="250"> | <img src="https://github.com/user-attachments/assets/7a465490-9494-44a2-8dad-aa9482ac9d62" alt="scenario1-seed6_S1" width="250"> | <img src="https://github.com/user-attachments/assets/baffb054-1120-4580-82dd-23dc96b92226" alt="scenario1-seed24_S1" width="250"> |

<a id="regular-scenario-2"></a>
### Regular Scenario 2

<a id="navigation-task-r1"></a>
#### Navigation Task: R1

| case1 | case2 | case3 |
|---|---|---|
| <img src="https://github.com/user-attachments/assets/3ab20a33-3bcc-4827-9c92-0dc9a967ab7b" alt="scenario2-seed5_R1" width="250"> | <img src="https://github.com/user-attachments/assets/0bbb0ec3-6f69-4301-80c5-071ef417642b" alt="scenario2-seed7_R1" width="250"> | <img src="https://github.com/user-attachments/assets/30750cb0-a609-44da-9ca5-2d9e549b5e3e" alt="scenario2-seed9_R1" width="250"> |

<a id="navigation-task-r2"></a>
#### Navigation Task: R2

| case1 | case2 | case3 |
|---|---|---|
| <img src="https://github.com/user-attachments/assets/ae067579-c792-447d-a79e-af5db639399d" alt="scenario2-seed0_R2" width="250"> | <img src="https://github.com/user-attachments/assets/696d0a47-9975-471e-9517-1e72b3903d28" alt="scenario2-seed11_R2" width="250"> | <img src="https://github.com/user-attachments/assets/b813dea0-8225-4db9-a200-74451422c5fc" alt="scenario2-seed15_R2" width="250"> |

<a id="navigation-task-s2"></a>
#### Navigation Task: S2

| case1 | case2 | case3 |
|---|---|---|
| <img src="https://github.com/user-attachments/assets/f5bafcf0-3e4b-4fa6-9ca1-0abb7b5d90b8" alt="scenario2-seed4_S2" width="250"> | <img src="https://github.com/user-attachments/assets/06bff9b6-bb0c-4431-b286-9d793fe9c503" alt="scenario2-seed6_S2" width="250"> | <img src="https://github.com/user-attachments/assets/e5363347-b1eb-4921-95e3-8b0f13665124" alt="scenario2-seed12_S2" width="250"> |

<a id="video-demonstrations"></a>
## 🎥 Video Demonstrations
Video results of the proposed **STUD** framework and its ablated variants in two Out-of-Distribution (OOD) driving scenarios for unsignalized intersection navigation.
- **STUD**: STUD with UA-HOCBF-based safety filter
- **STUD w/o UA**: STUD with HOCBF-based safety filter
- **STUD w/o SF**: STUD without safety filtering

<a id="ood-scenario-1"></a>
### OOD Scenario 1

<a id="ood1-stud-full"></a>
#### STUD (Full)
<video src="https://github.com/user-attachments/assets/426a6307-eb7f-4dd1-b1da-c7e1221e7f24" width="800" controls></video>

<a id="ood1-gaussian-distributions"></a>
##### Gaussian Distributions of the Probabilistic Ensemble Cost Critic
![OOD1-Probabilistic_Ensemble_Cost_Critic](https://github.com/user-attachments/assets/8ac73aed-87e2-4229-8abc-fdb8b887f28e)

<a id="ood1-stud-wo-ua"></a>
#### STUD w/o UA
<video src="https://github.com/user-attachments/assets/990aa28a-925b-4a7c-a447-ce32ace24adc" width="800" controls></video>

<a id="ood1-stud-wo-sf"></a>
#### STUD w/o SF
<video src="https://github.com/user-attachments/assets/b39809f9-4d8b-4e12-8257-692a2b934a41" width="800" controls></video>

<a id="ood-scenario-2"></a>
### OOD Scenario 2

<a id="ood2-stud-full"></a>
#### STUD (Full)
<video src="https://github.com/user-attachments/assets/a597a86b-8977-4b13-9f6b-3893ca840e2c" width="800" controls></video>

<a id="ood2-gaussian-distributions"></a>
##### Gaussian Distributions of the Probabilistic Ensemble Cost Critic
![OOD2-Probabilistic_Ensemble_Cost_Critic](https://github.com/user-attachments/assets/b15a0c90-c131-4a56-8c16-7e7f48d9bb65)

<a id="ood2-stud-wo-ua"></a>
#### STUD w/o UA
<video src="https://github.com/user-attachments/assets/ec8178aa-306f-40ef-8911-1bf51dd8a111" width="800" controls></video>

<a id="ood2-stud-wo-sf"></a>
#### STUD w/o SF
<video src="https://github.com/user-attachments/assets/ec027781-e57a-405f-904d-05ab1691ef5b" width="800" controls></video>
