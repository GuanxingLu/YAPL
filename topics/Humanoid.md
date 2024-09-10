# Humanoid

## Teleoperation

History:
In the 1950s, remote control was used to complete tasks in dangerous environments such as nuclear power plants. [source]
Institute:
CMU, Stanford, UCSD
Hardware:
- Bimanual
- Whole-body
System:
- Passive vision
- Glove-based
- Passive + haptic feedback
- Active vision
- Passive vision + Exoskeletons
MOdel:
- Joint-matching (ALOHA series)
- Vision + retargeting
- Vision + IK + lower-body controller
- Vision + learning-based whole-body controller

- **[IEEE-RAS International Conference on Humanoid Robots'23]** Deep Imitation Learning for Humanoid Loco-manipulation through Human Teleoperation
> gripper, whole-body control (but classic controller for legs).
- **[RSS'23]** AnyTeleop: A General Vision-Based Dexterous Robot Arm-Hand Teleoperation System
> (ANY) Passive camera, pose estimation, vision+retargeting (Sequential Quadratic Programming SQP, Pinocchio), dexterous hand, motion generation~arm IK (Riemannian motion policies RMP).
- **[arxiv:2407]** Bunny-VisionPro: Real-Time Bimanual Dexterous Teleoperation for Imitation Learning
> Active vision (Vision-pro), haptic feedback, (gradient from active to passive) loop joint retargeting, (Jacobian) singularity avoidance, (sphere) collision avoidance.
- **[arXiv:2407]** Open-TeleVision: Teleoperation with Immersive Active Visual Feedback.
> Active vision action space, a head-mounted camera on robot, remote control.
- **[RSS'02]** Multi-fingered exoskeleton haptic device using passive force feedback for dexterous teleoperation
- **[arXiv:2403]** DexCap: Scalable and Portable Mocap Data Collection System for Dexterous Manipulation
> Glove, human-in-the-loop correction

- **[arXiv:2403]** H2O: Learning Human-to-Humanoid Real-Time Whole-Body Teleoperation
> Learning-based lower body control.
- **[arXiv:2406]** OmniH2O: Universal and Dexterous Human-to-Humanoid Whole-Body Teleoperation and Learning
> + upper body retargeting.

Question:
- Is there any common metric to choose the most suitable one?

## Mobile Manipulation

* **[arxiv'2407]** Towards Open-World Mobile Manipulation in Homes: Lessons from the Neurips 2023 HomeRobot Open Vocabulary Mobile Manipulation Challenge

* **[arxiv'2406]** RoboCasa: Large-Scale Simulation of Everyday Tasks for Generalist Robots

* **[arXiv:2402]** Pushing the Limits of Cross-Embodiment Learning for Manipulation and Navigation
> Diffusion policy

## Bimanual

* **[arxiv'2403]** HumanoidBench: Simulated Humanoid Benchmark for Whole-Body Locomotion and Manipulation
> RL only

* **[arxiv'2206]** Towards Human-Level Bimanual Dexterous Manipulation with Reinforcement Learning

* **[arxiv'2009]** robosuite: A Modular Simulation Framework and Benchmark for Robot Learning
> Baxter robot

* **[arXiv:2010]** Deep Imitation Learning for Bimanual Robotic Manipulation
> task primitives + recurrent graph neural network 

* **[RAL'22]** A Bimanual Manipulation Taxonomy

| Bimanual Category                        | Abbreviation            |
|------------------------------------------|-------------------------|
| No action                                | no action               |
| Unimanual left                           | uni left                |
| Unimanual right                          | uni right               |
| Loosely coupled & uncoordinated bimanual | loosely                 |
| Tightly coupled asymmetrical left dominant | tightly asym left      |
| Tightly coupled asymmetrical right dominant | tightly asym right    |
| Tightly coupled symmetrical              | tightly sym             |

* **[arXiv:2405]** Empowering Embodied Manipulation: A Bimanual-Mobile Robot Manipulation Dataset for Household Tasks, no code yet

* **[2021]** The KIT Bimanual Manipulation Dataset
> Video

* **[arxiv:2406]** BiKC: Keypose-Conditioned Consistency Policy for Bimanual Robotic Manipulation

* **[RSS'23]** Learning Fine-Grained Bimanual Manipulation with Low-Cost Hardware, [code](https://tonyzhaozh.github.io/aloha/)
> Transfer Cube and Bimanual Insertion

* **[ICLR'23]** ManiSkill2: A Unified Benchmark for Generalizable Manipulation Skills
> two tasks

* **[CoRL'23 Oral]** Stabilize to Act: Learning to Coordinate for Bimanual Manipulation
> Stabilizing Position Model (one arm) + BCRNN (another, considered as single-arm)

* **[2024.05]** SCREWMIMIC: Bimanual Imitation from Human Videos with Screw Space Projection
> only screw

* **[arXiv:2403]** OPEN TEACH: A Versatile Teleoperation System for Robotic Manipulation
> Teach bimanual manipulation w/ Meta Quest 3, w/o gripper

* **[arXiv:2106]** DAIR: Disentangled Attention Intrinsic Regularization for Safe and Efficient Bimanual Manipulation
> domination and conflict problem. Disentangled attention loss.

* **[arXiv:2211]** CLAS: Coordinating Multi-Robot Manipulation with Central Latent Action Spaces
> Robosuite

* **[arXiv:2407]** VoxAct-B: Voxel-Based Acting and Stabilizing Policy for Bimanual Manipulation
> RLBench, another PerAct^2. Leverages OWL-ViT to prioritize key regions within the scene and reconstruct a voxel grid.

* **[arXiv:2401]** Multi-task real-robot data with gaze attention for dual-arm fine manipulation
> Gaze predictor

* **[arXiv:2108]** Transformer-based deep imitation learning for dual-arm robot manipulation
> Gaze predictor

* **[arXiv:2403]** Bi-KVIL: Keypoints-based Visual Imitation Learning of Bimanual Manipulation Tasks
> Hybrid Master-Slave Relationships (HMSR) among objects and hands

* **[ICRA'22]** HandoverSim: A Simulation Framework and Benchmark for Human-to-Robot Object Handovers, benchmark no demonstration

* **[arXiv:2405]** Bi-VLA: Vision-Language-Action Model-Based System for Bimanual Robotic Dexterous Manipulations
> LLM-based Code Generator + Motion controller, no finetuning

* **[CVPR'24]** OakInk2: A Dataset of Bimanual Hands-Object Manipulation in Complex Task Completion
> Affordance

* **[RAL'23]** LEMMA: Learning Language-Conditioned Multi-Robot Manipulation
> High-level + Low-level planning

* **[TRO'22]** Goal-conditioned dual-action imitation learning for dexterous dual-arm robot manipulation
> Peel the banana, gaze policy, global and local action

* **[ICLR'23]**  Dualafford: Learning collaborative visual affordance for dual-gripper manipulation
> First Gripper Module, Second Gripper Module, Collaborative Adaption procedure

* **[arXiv:2309]** GELLO: A General, Low-Cost, and Intuitive Teleoperation Framework for Robot Manipulators
> bimanual data collection system, used by VoxAct-B

* **[ICRA'2020]** Efficient Bimanual Manipulation Using Learned Task Schemas
> Like 'SkillDiffuser', assign different subtasks (skills) for different arms.

Conclusion: Try to separate the visual observation of both arms.

### Planning

- **[arxiv:2406]** DAG-Plan: Generating Directed Acyclic Dependency Graphs for Dual-Arm Cooperative Planning, no code yet, private env

- **[arXiv:2405]** Hierarchical World Models as Visual Whole-Body Humanoid Controllers
> No reward or primitive skills, Tracking World Model + Puppeteer World Model

- **[arXiv:2402]** Expressive Whole-Body Control for Humanoid Robots
> 

### Locomotion

- **[RSS'24 Outstanding Nominee]** Advancing Humanoid Locomotion: Mastering Challenging Terrains with Denoising World Model Learning

### Sim-to-Real

- **[arXiv:2310]** Sim-to-Real Learning for Humanoid Box Loco-Manipulation
> 5 Primitives
