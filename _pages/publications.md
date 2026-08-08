---
layout: archive
title: " "
permalink: /publications/
author_profile: true
redirect_from:
  - /publications
---

{% include base_path %}

## Research Projects

### Vibration-Assisted Rope-Climbing Robot
**Role:** Project Leader &nbsp;|&nbsp; **Period:** May 2022 -- June 2024

- **Overview:** Independently designed and prototyped a compact rope-climbing robot with a novel dual-wheel winding rope-gripping mechanism, enabling efficient locomotion in unstructured environments.
- **Theoretical Analysis:** Established the parametric obstacle-negotiation model, revealed the vibration-assisted obstacle negotiation mechanism based on the time-domain averaging equivalent friction reduction.
- **Hardware:** Built a hierarchical control architecture consisting of host computer and on-board MCU, integrated FOC motor with encoder, IMU and main motor current sensor for full-state feedback.
- **Algorithm:** Implemented EKF state estimation, a lightweight FSM for multi-feature condition classification, and online system identification enhanced ESC vibration amplitude control, forming a perception-decision-execution closed loop that significantly boosts obstacle negotiation performance.
- **Master Degree Thesis:** Design and Obstacle-crossing Method of Rope-climbing Mobile Robot. Zhejiang University, 2024.
- **Manuscript in Preparation:** Minghao Li, Xin Li\*. "ROVIN: A Rope-Climbing Robot With Vibration-Assisted Obstacle Negotiation," targeted for *IEEE/ASME Transactions on Mechatronics*, 2026.

---

### Rope-Aided Single-Arm Robot for Mesh Structures
**Role:** Manipulator Control &nbsp;|&nbsp; **Period:** July 2021 -- June 2024

- **Overview:** Designed and prototyped a rope-aided truss-climbing robot with 6-DOF lightweight manipulator and anti-winding winch for stable locomotion on mesh structures with high payload capacity.
- **Theoretical Analysis:** Established D-H kinematics (closed-form inverse solution), rigid-body dynamics and dual-rope two-link swing dynamics models.
- **Hardware:** Built hierarchical control architecture on STM32 + FreeRTOS, integrating FOC drives, SSI encoders and IMU for 200 Hz full-state closed-loop control.
- **Algorithm:** Implemented RLS-based adaptive speed controller with KF state observer for encoder noise suppression, improving accuracy.

---

### Small-Size Soccer Robot Design for RoboCup
**Role:** Hardware Leader &nbsp;|&nbsp; **Period:** Sep 2019 -- Mar 2021

- **Hardware:** Innovatively designed ball suction and kicking actuator mechanisms to improve ball control stability and dynamic response; completed component selection and PCB redesign for boost power board.
- **Motion Control:** Participated in overall control architecture design, developed a custom protocol to receive and parse host-side packets, implemented closed-loop control for all wheel-motors and actuator motors.

---

## Industrial Projects

### Embedded Computing Platform Based on RK3568/RK3588
**Role:** Embedded Engineer &nbsp;|&nbsp; **Period:** Oct 2024 -- Present

- **Overview:** Built a domestically sourced heterogeneous platform based on RK3568/RK3588 SoCs and Unigroup FPGAs. Led board hardware design, RT-Thread/Linux driver & BSP development, and system verification, focusing on high-speed bus integrity, multi-core real-time performance, and driver reliability.
- **Hardware:** Designed schematics and selected components for ADC sampling, FLASH storage, I2C/I3C/SPI buses, and CPU minimum system. Participated in PCB review, EMC testing and hardware bring-up.
- **Driver & BSP:** Developed RT-Thread peripheral drivers (GPIO, SPI, CAN, GMAC, timers, interrupts), shared memory and IPC drivers for AMP architecture, and encapsulated standardized APIs for upper layers.
- **Interconnection:** Defined CPU-FPGA GMAC/SPI connection, developed corresponding bus drivers and packet protocols, and implemented DMA zero-copy data transmission to satisfy strict real-time requirements.

---

### Smart NIC Validation for Cluster Computing Servers
**Role:** Embedded Intern &nbsp;|&nbsp; **Period:** June 2023 -- Oct 2023

- **Overview:** Participated in testing and validation of HiSilicon-based smart NICs on Kunpeng Taishan servers, covering PCIe interface, driver adaptation and openEuler compatibility for cluster computing.
- **Test Hardware Design:** Designed an MCU+CPLD-based test carrier board to emulate chip thermal load and implement automated temperature data acquisition, supporting pre-evaluation of chip thermal design.
- **System Validation:** Built openEuler Linux test environments, conducted NIC driver adaptation and RoCE RDMA benchmark tests, collaborated with cross-functional teams to root-cause hardware and driver defects.

---

## Patents

1. **Chip Thermal Simulation System and Pre-evaluation Method for Chip Thermal Design**  
   Minghao Li et al. [CN] 202610661567.6 (Under Substantive Examination), 2026.

2. **A Remote Control Method for Multi-peripheral Relay Protection Devices Based on I3C Bus**  
   Minghao Li et al. [CN] 202610589343.9 (Patent Pending), 2026.

3. **A Construction Method for Data Preprocessing and Cooperative Control System of Relay Protection Devices**  
   Minghao Li et al. [CN] 202610730554.X (Patent Pending), 2026.

4. **A Multimodal Diffusion-Based Semantic Perception Method for Agricultural 3D Radar**  
   基于多模态扩散模型的农业三维雷达语义感知方法  
   Ruibin Zhang#, Fei Gao\* [CN] 202510123456.7 (Under Substantive Examination), 2025.

5. **Model Predictive Planning and Control Device for Air-Ground Bimodal Vehicles with Passive Wheels**  
   空地双模态无源轮载车辆模型预测规划控制装置  
   Ruibin Zhang, Junxiao Lin, Yuze Wu, Fei Gao\* [CN] 202510789012.3 (Under Preliminary Examination), 2025.

---

## Publications

***Sem-RaDiff: Diffusion-Based 3D Radar Semantic Perception in Cluttered Agricultural Environments***  
**<u>Ruibin Zhang</u>**, Fei Gao*  
IEEE Transactions on Automation Science and Engineering (**T-ASE**), 2026.  
<img src="/images/2025-background.png" style="width:auto;height:200px" />

***Towards Dense and Accurate Radar Perception Via Efficient Cross-Modal Diffusion Model***  
**<u>Ruibin Zhang</u>**<sup>#</sup>, Donglai Xue<sup>#</sup>, Yuhan Wang, Ruixu Geng, Fei Gao*  
IEEE Robotics and Automation Letters (**RA-L**), 2024.  
[[paper](https://ieeexplore.ieee.org/document/10592769)] [[code](https://github.com/ZJU-FAST-Lab/Radar-Diffusion)] [[video](https://www.youtube.com/watch?v=Q3S-9w3dGV4)]  
<img src="/images/RAL2024-cover.png" style="width:auto;height:200px" />  <img src="/images/RAL2024-architecture.png" style="width:auto;height:200px" />

***Model-based planning and control for terrestrial-aerial bimodal vehicles with passive wheels***  
**<u>Ruibin Zhang</u>**, Junxiao Lin, Yuze Wu, Yuman Gao, Chi Wang, Chao Xu, Yanjun Cao, Fei Gao*  
IEEE/RSJ International Conference on Intelligent Robots and Systems (**IROS**), 2023.  
[[paper](https://ieeexplore.ieee.org/document/10342188)] [[video](https://www.youtube.com/watch?v=_KhqTl2Vlqc)]  [[Media Report](https://www.youtube.com/watch?v=kaijXxgYyRY)]  
<img src="/images/IROS2023-exp.gif" style="width:auto;height:200px" />  <img src="/images/IROS2023-topgraph.png" style="width:auto;height:200px" />
