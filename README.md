# Awesome World Action Models

A list of papers on World Action Models (WAMs).

If we missed a relevant paper, project page, or code release, feel free to open an issue.

## Overview

- [Surveys](#surveys)
- [Learning Video Model and Policy](#learning-video-model-and-policy)
- [Video Model](#video-model)
- [Policy Head](#policy-head)


## Surveys

- *Do World Action Models Generalize Better than VLAs? A Robustness Study*. **`26.3`** [arXiv](https://arxiv.org/abs/2603.22078)

- *Understanding World or Predicting Future?: A Comprehensive Survey of World Models*. **`24.11`** [arXiv](https://arxiv.org/abs/2411.14499)


## Learning Video Model and Policy
 
This group focus on learning actions and future dynamics together.

- **DreamZero**: *World Action Models are Zero-shot Policies*. **`26.2`** [arXiv](https://arxiv.org/abs/2602.15922) [Project](https://dreamzero0.github.io) [Code](https://github.com/dreamzero0/dreamzero)
- **Unified World Models**: *Unified World Models: Coupling Video and Action Diffusion for Pretraining on Large Robotic Datasets*. [arXiv](https://arxiv.org/abs/2504.02792) [Project](https://weirdlabuw.github.io/uwm/) [Code](https://github.com/WEIRDLabUW/unified-world-model)
- **UVAM**: *Unified Video Action Model*. [arXiv](https://arxiv.org/abs/2503.00200) [Project](https://unified-video-action-model.github.io) [Code](https://github.com/ShuangLI59/unified_video_action)
- **Motus**: *Motus: A Unified Latent Action World Model*. [arXiv](https://arxiv.org/abs/2512.13030) [Project](https://motus-robotics.github.io/motus) [Code](https://github.com/thu-ml/Motus)
- **LeWorldModel**: *LeWorldModel: Stable End-to-End Joint-Embedding Predictive Architecture from Pixels*. **`26.3`** [arXiv](https://arxiv.org/abs/2603.19312) [Project](https://le-wm.github.io/) [Code](https://github.com/lucas-maes/le-wm)
- **VPP**: *Video Prediction Policy: A Generalist Robot Policy with Predictive Visual Representations*. [arXiv](https://arxiv.org/abs/2412.14803) [Project](https://video-prediction-policy.github.io) [Code](https://github.com/roboterax/video-prediction-policy)
- **UniSim**: *Learning Interactive Real-World Simulators*. [arXiv](https://arxiv.org/abs/2310.06114) [Project](https://universal-simulator.github.io/unisim/)
- **DayDreamer**: *DayDreamer: World Models for Physical Robot Learning*. [arXiv](https://arxiv.org/abs/2206.14176) [Project](https://danijar.com/project/daydreamer/) [Code](https://github.com/danijar/daydreamer)
- **VideoWorld**: *VideoWorld: Exploring Knowledge Learning from Unlabeled Videos*. [arXiv](https://arxiv.org/abs/2501.09781) [Project](https://maverickren.github.io/VideoWorld.github.io/) [Code](https://github.com/ByteDance-Seed/VideoWorld)
- **mimic-video**: *mimic-video: Video-Action Models for Generalizable Robot Control Beyond VLAs*. [arXiv](https://arxiv.org/abs/2512.15692) [Project](https://mimic-video.github.io)
- **VideoVLA**: *VideoVLA: Video Generators Can Be Generalizable Robot Manipulators*. [arXiv](https://arxiv.org/abs/2512.06963) [Project](https://videovla-nips2025.github.io/) [Code](https://github.com/VideoVLA-Project/VideoVLA)
- **DreamGen**: *DreamGen: Unlocking Generalization in Robot Learning through Video World Models*. [arXiv](https://arxiv.org/abs/2505.12705) [Project](https://research.nvidia.com/labs/gear/dreamgen/) [Code](https://github.com/nvidia/GR00T-dreams)
- **Genie Envisioner**: *Genie Envisioner: A Unified World Foundation Platform for Robotic Manipulation*. [arXiv](https://arxiv.org/abs/2508.05635) [Project](https://genie-envisioner.github.io) [Code](https://github.com/AgibotTech/Genie-Envisioner)
- **EnerVerse**: *EnerVerse: Envisioning Embodied Future Space for Robotics Manipulation*. [arXiv](https://arxiv.org/abs/2501.01895) [Project](https://sites.google.com/view/enerverse)
- **Video Policy**: *Video Generators are Robot Policies*. [arXiv](https://arxiv.org/abs/2508.00795) [Project](https://videopolicy.cs.columbia.edu) [Code](https://github.com/cvlab-columbia/videopolicy)
- **Causal World Modeling for Robot Control**: *Causal World Modeling for Robot Control*. [arXiv](https://arxiv.org/abs/2601.21998) [Project](https://technology.robbyant.com/lingbot-va) [Code](https://github.com/Robbyant/lingbot-va)
- **GR-2**: *GR-2: A Generative Video-Language-Action Model with Web-Scale Knowledge for Robot Manipulation*. [arXiv](https://arxiv.org/abs/2410.06158) [Project](https://gr2-manipulation.github.io)
- **GR-1**: *Unleashing Large-Scale Video Generative Pre-training for Visual Robot Manipulation*. [arXiv](https://arxiv.org/abs/2312.13139) [Project](https://gr1-manipulation.github.io) [Code](https://github.com/bytedance/GR-1)

- **Video Language Planning**. [arXiv](https://arxiv.org/abs/2310.10625) [Project](https://video-language-planning.github.io/)
- **UniPi**: *Learning Universal Policies via Text-Guided Video Generation*. [arXiv](https://arxiv.org/abs/2302.00111) [Project](https://universal-policy.github.io/unipi/)
- **Learning to Act from Actionless Videos through Dense Correspondences**. [arXiv](https://arxiv.org/abs/2310.08576) [Project](https://flow-diffusion.github.io/)

## Video Model

This group focus on video generation or future visual rollouts as a central part of policy learning.

- **VAMPO**: *VAMPO: Policy Optimization for Improving Visual Dynamics in Video Action Models*. [arXiv](https://arxiv.org/abs/2603.19370) [Project](https://vampo-robot.github.io/VAMPO) [Code](https://github.com/OpenHelix-Team/VAMPO)
- **S-VAM**: *S-VAM: Shortcut Video-Action Model by Self-Distilling Geometric and Semantic Foresight*. [arXiv](https://arxiv.org/abs/2603.16195) [Project](https://haodong-yan.github.io/S-VAM/)
- **Cosmos Policy**: *Cosmos Policy: Fine-Tuning Video Models for Visuomotor Control and Planning*. [arXiv](https://arxiv.org/abs/2601.16163) [Project](https://research.nvidia.com/labs/dir/cosmos-policy/) [Code](https://github.com/nvlabs/cosmos-policy)
- **Large Video Planner**: *Large Video Planner Enables Generalizable Robot Control*. [arXiv](https://arxiv.org/abs/2512.15840) [Project](https://www.boyuan.space/large-video-planner/) [Code](https://github.com/buoyancy99/large-video-planner/tree/main)
- **VideoAgent**: *VideoAgent: Self-Improving Video Generation for Embodied Planning*. [arXiv](https://arxiv.org/abs/2410.10076) [Project](https://video-as-agent.github.io/) [Code](https://github.com/Video-as-Agent/VideoAgent)
- **DTS**: *Draft-and-Target Sampling for Video Generation Policy*. [arXiv](https://arxiv.org/abs/2603.13438) [Code](https://github.com/ChaosTheProducer/DTS-AVDC)


## Policy Head

This group focuses on transferring motion, semantics, or other kind of information from video models into robot action.
- **Dream2Flow**: *Dream2Flow: Bridging Video Generation and Open-World Manipulation with 3D Object Flow*. [arXiv](https://arxiv.org/abs/2512.24766) [Project](https://dream2flow.github.io/) [Code](https://github.com/KDharmarajanDev/Dream2Flow/)
- **MM-ACT**: *MM-ACT: Learn from Multimodal Parallel Generation to Act*. [arXiv](https://arxiv.org/abs/2512.00975) [Project](https://github.com/HHYHRHY/MM-ACT)
- **F1**: *F1: A Vision-Language-Action Model Bridging Understanding and Generation to Actions*. [arXiv](https://arxiv.org/abs/2509.06951) [Project](https://aopolin-lv.github.io/F1-VLA/)
- **World Guidance**: *World Guidance: World Modeling in Condition Space for Action Generation*. [arXiv](https://arxiv.org/abs/2602.22010) [Project](https://selen-suyue.github.io/WoGNet/) [Code](https://github.com/Selen-Suyue/WoG)
- **Diffuser**: *Planning with Diffusion for Flexible Behavior Synthesis*. [arXiv](https://arxiv.org/abs/2205.09991) [Project](https://diffusion-planning.github.io/) [Code](https://github.com/jannerm/diffuser)
- **Seer**: *Predictive Inverse Dynamics Models are Scalable Learners for Robotic Manipulation*. [arXiv](https://arxiv.org/abs/2412.15109) [Project](https://github.com/InternRobotics/Seer) [Code](https://github.com/InternRobotics/Seer)
- **FRAPPE**: *FRAPPE: Infusing World Modeling into Generalist Policies via Multiple Future Representation Alignment*. [arXiv](https://arxiv.org/abs/2602.17259) [Project](https://h-zhao1997.github.io/frappe) [Code](https://github.com/OpenHelix-Team/frappe)
- **Action-to-Action Flow Matching**. [arXiv](https://arxiv.org/abs/2602.07322) [Project](https://lorenzo-0-0.github.io/A2A_Flow_Matching)

- **Dreamitate**: *Dreamitate: Real-World Visuomotor Policy Learning via Video Generation*. [arXiv](https://arxiv.org/abs/2406.16862) [Project](https://dreamitate.cs.columbia.edu/)
- **Gen2Act**: *Gen2Act: Human Video Generation in Novel Scenarios Enables Generalizable Robot Manipulation*. [arXiv](https://arxiv.org/abs/2409.16283) [Project](https://homangab.github.io/gen2act/)
- **Act2Goal**: *Act2Goal: From World Model To General Goal-conditioned Policy*. [arXiv](https://arxiv.org/abs/2512.23541) [Project](https://act2goal.github.io/)
- **Grounding Video Models to Actions through Goal-Conditioned Exploration**. [arXiv](https://arxiv.org/abs/2411.07223) [Project](https://video-to-action.github.io/)
- **Inverse Probabilistic Adaptation**: *Solving New Tasks by Adapting Internet Video Knowledge*. [arXiv](https://arxiv.org/abs/2504.15369) [Project](https://diffusion-supervision.github.io/adapt2act/)
- **Solving Robotic Tasks via Self-Adapting Improvement Loops with Internet Video Knowledge**. [OpenReview](https://openreview.net/forum?id=OAsXsLV2gg)


## Acknowledgements
Thanks to [Awesome VLA & WAM](https://github.com/DravenALG/awesome-vla-wam) for the template.

