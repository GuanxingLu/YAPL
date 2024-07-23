# NeRF

* **[ICCV'21 Oral]** Baking Neural Radiance Fields for Real-Time View Synthesis
> Sparse Neural Radiance Grid (SNeRG)


# 4D NeRF

* **[CVPR'21]** Space-time Neural Irradiance Fields for Free-Viewpoint Video, no code
* **[ICCV'21]** Nerfies: Deformable Neural Radiance Fields
* **[CVPR'22 Oral]** BANMo: Building Animatable 3D Neural Models from Many Casual Videos
* **[CVPR'24]** Video2Game: Real-time, Interactive, Realistic and Browser-Compatible Environment from a Single Video

# NeRF for manipulation

* **[CoRL'21 Oral]** 3D Neural Scene Representations for Visuomotor Control
> Given a goal image, use model-predictive path integral (MPPI) to control the end-effortor with learned world model.
> Contrastive loss + NeRF + auto-decoding test-time optimization
* **[CoRL'23 Oral]** GNFactor: Multi-Task Real Robot Learning with Generalizable Neural Feature Fields
> Generalizable MLP + Diffusion prior
* **[CoRL'22 Oral]** Evo-NeRF: Evolving NeRF for Sequential Robot Grasping of Transparent Objects, no code
> Eye-in-hand, grasping confidence with rgbd
* **[CVPR'23]** NeRF in the Palm of Your Hand: Corrective Augmentation for Robotics via Novel-View Synthesis, no code
> Eye-in-hand, generate a perturbed pose, and render the corresponding image and action.
* **[arXiv:2405]** NeRF in Robotics: A Survey
* **[RSS'24]** Reconciling Reality Through Simulation: A Real-to-Sim-to-Real Approach for Robust Manipulation

* **[ICLR'24 Oral]** ASID: ACTIVE EXPLORATION FOR SYSTEM IDENTIFICATION IN ROBOTIC MANIPULATION

* **[DGR@RSS2024]** Scaling Robot-Learning by Crowdsourcing Simulation Environments

* **[RSS'24]** URDFormer: A Pipeline for Constructing Articulated Simulation Environments from Real-World Images

* **[CVPR'22 Oral]** Ditto: Building Digital Twins of Articulated Objects from Interaction
>  Given visual observations before and after interaction, our method jointly reconstructs the part-level geometry and articulation model of the object.

# NeRF for navigation

* **[ICCV'23 NeRF4ADR Workshop]** AutoNeRF: Training Implicit Scene Representations with Autonomous Agents
> Downstream tasks
* **[arxiv'2403]** Learning Generalizable Feature Fields for Mobile Manipulation

# Gaussian Splatting


# 4D Gaussian Splatting

Ref: https://github.com/MrNeRF/awesome-3D-gaussian-splatting?tab=readme-ov-file#dynamics-and-deformation

* **[arXiv:2406]** L4GM: Large 4D Gaussian Reconstruction Model, no code yet
* **[3DV'24]** Dynamic 3D Gaussians: Tracking by Persistent Dynamic View Synthesis, good code
> Synchronized multi-camera systems
* **[CVPR'24]** 4D Gaussian Splatting for Real-Time Dynamic Scene Rendering, good code
> From monocular video
* **[CVPR'24]** Spacetime gaussian feature splatting for real-time dynamic view synthesis
* **[CVPR'24]**, Gaussian-Flow: 4D Reconstruction with Dynamic 3D Gaussian Particle, no code yet
* **[ICLR'24]**, Real-time Photorealistic Dynamic Scene Representation and Rendering with 4D Gaussian Splatting
> Large-scale scene results
* **[CVPR'24]** 3D Geometry-aware Deformable Gaussian Splatting for Dynamic View Synthesis
* **[arXiv:2402]** 4D Gaussian Splatting: Towards Efficient Novel View Synthesis for Dynamic Scenes
* **[CVPR'24]** Deformable 3D Gaussians for High-Fidelity Monocular Dynamic Scene Reconstruction
* **[arXiv:2404]** Per-Gaussian Embedding-Based Deformation for Deformable 3D Gaussian Splatting
> latent code + coarse&fine time embedding
* **[arXiv:2311]** An Efficient 3D Gaussian Representation for Monocular/Multi-view Dynamic Scenes
* **[CVPR'24]** CoGS: Controllable Gaussian Splatting, no code
* **[CVPR'24]** Gaussian-Flow: 4D Reconstruction with Dynamic 3D Gaussian Particle
* **[arXiv:2312]** MD-Splatting: Learning Metric Deformation from 4D Gaussians in Highly Deformable Scenes, Shuran Song, no code yet
* **[CVPR'24]** 3DGStream: On-the-Fly Training of 3D Gaussians for Efficient Streaming of
Photo-Realistic Free-Viewpoint Videos
* **[arxiv:2406]** EgoGaussian: Dynamic Scene Understanding from Egocentric Video with 3D Gaussian Splatting, no code yet
* **[arXiv:2401]** VR-GS: A Physical Dynamics-Aware Interactive Gaussian Splatting System in Virtual Reality, no code yet
* **[CVPR'2024]** SC-GS: Sparse-Controlled Gaussian Splatting for Editable Dynamic Scenes

# Gaussian Splatting for manipulation

* **[arxiv'2406]** Physically Embodied Gaussian Splatting: A Realtime Correctable World Model for Robotics
* **[arxiv'2403]** ManiGaussian: Dynamic Gaussian Splatting for Multi-task Robotic Manipulation
* **[arxiv'2405]** Object-Aware Gaussian Splatting for Robotic Manipulation

# RGB-D

* **[IROS'24]** VIHE: Transformer-Based 3D Object Manipulation Using Virtual In-Hand View

# Multi-view

* **[arXiv:2406]** 3D-MVP: 3D Multiview Pretraining for Robotic Manipulation

# Point Cloud

* **[arXiv:2403]** Near Real-Time SE(3)-Equivariant Robot Manipulation without Point Cloud Segmentation

# LLM Code

* **[arXiv:2404]** Re-Thinking Inverse Graphics With Large Language Models
> Finetune a LLM to decode a visual (CLIP) embedding into graphics code

* **[ICRA'24]** Gen2Sim: Scaling up Robot Learning in Simulation with Generative Models
> Automating generation of 3D assets, task descriptions, task decompositions and reward functions

# Diffusion

* **[CVPR'24 Highlight]** PhyScene: Physically Interactable 3D Scene Synthesis for Embodied AI
> Retrieve articulated objects from GAPartNet Dataset and simulate generated scenes in Omniverse Isaac Sim.
