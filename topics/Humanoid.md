# Humanoid

## Mobile Manipulation

* **[arxiv'2407]** Towards Open-World Mobile Manipulation in Homes: Lessons from the Neurips 2023 HomeRobot Open Vocabulary Mobile Manipulation Challenge

* **[arxiv'2406]** RoboCasa: Large-Scale Simulation of Everyday Tasks for Generalist Robots

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

### Planning

- **[arxiv:2406]** DAG-Plan: Generating Directed Acyclic Dependency Graphs for Dual-Arm Cooperative Planning, no code yet, private env

- **[arxiv:2407]** Bunny-VisionPro: Real-Time Bimanual Dexterous Teleoperation for Imitation Learning
