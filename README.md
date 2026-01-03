# Awesome Spatial Exploration Policy [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of awesome spatial exploration policy papers, inspired by [awesome-computer-vision](https://github.com/jbhuang0604/awesome-computer-vision) and [awesome-NeRF](https://github.com/awesome-NeRF/awesome-NeRF).

We classify the primary technical frameworks of existing NBV policies into the following categories: 1) information gain (a.k.a. uncertainty), 2) reinforcement learning, 3) regression/recurrent prediction.

The exploration task, also known as next-best-view planning and active mapping, aims to determine the next best viewpoints to better model the target objects or scenes. The downstream tasks include: 3D reconstruction, neural rendering, SLAM, visual localization, object understanding, and robotic manipulation.


## Table of Contents

- [Survey](#survey)
- [Papers](#papers)
  - [Exploration Policy for Indoor Scenes](#indoor-scenes)
  - [Exploration Policy for Outdoor Scenes](#outdoor-scenes)
  - [Exploration Policy for Objects](#objects)
  <!-- - [Information Gain-based](#information-gain) -->
  <!-- - [Reinforcement Learning-based](#reinforcement-learning) -->

<!-- - [](),  et al., ICRA 2016-->


## Survey
- A Survey on Active Simultaneous Localization and Mapping: State of the Art and New Frontiers], Ahmed et al., T-RO 2023 | [Paper](https://ieeexplore.ieee.org/abstract/document/10075065?casa_token=2C8evIgOOiMAAAAA:FAPNd2PC5v8QMh1SV25jHtyGzvhYVInMiJokq1c0lTg_D0PGFOKOHY0Khtt_at0gZSwgCSvggoo)
- A Review on Viewpoints and Path Planning for UAV-Based 3-D Reconstruction, Maboudi et al., IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing, 2023 | [Paper](https://ieeexplore.ieee.org/abstract/document/10124957)
- Active SLAM: A Review On Last Decade, Ahmed et al., Sensors, 2023 | [Paper](https://arxiv.org/abs/2212.11654)



## Papers

<!-- <details open> -->
<!-- <summary>Indoor Scenes</summary> -->
### Indoor Scenes

#### Reinforcement Learning
- GLEAM: Learning Generalizable Exploration Policy for Active Mapping in Complex 3D Indoor Scenes, Chen et al., ICCV 2025 | [Paper](https://arxiv.org/abs/2505.20294) | [Project](https://xiao-chen.tech/gleam/) | [Code](https://github.com/zjwzcx/GLEAM)
- Hestia: Voxel-Face-Aware Hierarchical Next-Best-View Acquisition for Efficient 3D Reconstruction, Lu et al., WACV 2026 | [Paper](https://arxiv.org/abs/2508.01014) | [Project](https://johnnylu305.github.io/hestia) | [Code]()
- Learning to Explore using Active Neural SLAM, Chaplot et al., ICLR 2020 | [Paper](https://arxiv.org/abs/2004.05155) | [Code](https://github.com/devendrachaplot/Neural-SLAM)
- Learning Exploration Policies for Navigation, Chen et al., ICLR 2019 | [Paper](https://arxiv.org/abs/1903.01959) | [Code](https://github.com/taochenshh/exp4nav)


#### Information Gain
- NextBestPath: Efficient 3D Mapping of Unseen Environments, Li et al, ICLR 2025 | [Paper](https://arxiv.org/abs/2502.05378) | [Project](https://shiyao-li.github.io/nbp/)
- ActiveGS: Active Scene Reconstruction Using Gaussian Splatting, Jin et al., RA-L 2025 | [Paper](https://arxiv.org/abs/2412.17769)
- Active Neural Mapping at Scale, Kuang et al., IROS 2024 | [Paper](https://arxiv.org/abs/2409.20276)
- Active Neural Mapping, Yan et al., ICCV 2023 | [Paper](https://arxiv.org/abs/2308.16246) | [Project](https://zikeyan.github.io/active-INR/index.html)
- Continual Neural Mapping: Learning an Implicit Scene Representation from Sequential Observations, Yan et al., ICCV 2021 | [Paper](https://zikeyan.github.io/continual-INR/index.html) | [Project](https://zikeyan.github.io/continual-INR/index.html)
- Multi-robot collaborative dense scene reconstruction, Dong et al., TOG 2019 | [Paper](https://dl.acm.org/doi/10.1145/3306346.3322942)
- Density-aware NeRF Ensembles: Quantifying Predictive Uncertainty in Neural Radiance Fields, Sünderhauf et al., arXiv 2022 | [Paper](https://arxiv.org/abs/2209.08718)




#### Recurrent Prediction
- Where to Explore Next? ExHistCNN for History-aware Autonomous 3D Exploration, Wang et al., ECCV 2020 | [Paper](https://arxiv.org/abs/2011.14669)

<!-- </details> -->



<!-- <details open> -->
<!-- <summary>Outdoor Scenes</summary> -->
### Outdoor Scenes

#### Reinforcement Learning
- GenNBV: Generalizable Next-Best-View Policy for Active 3D Reconstruction, Chen et al., CVPR 2024 | [Paper](https://arxiv.org/abs/2402.16174) | [Project](https://gennbv.tech/) | [Code](https://github.com/zjwzcx/GenNBV)
- Next-Best View Policy for 3D Reconstruction, Peralta et al., ECCV 2020 Workshop | [Paper](https://arxiv.org/abs/2008.12664) | [Code](https://github.com/darylperalta/ScanRL)

#### Information Gain
- Semantically Informed Next Best View Planning for Autonomous Aerial 3D Reconstruction, Kay et al., IROS 2021 | [Paper](https://ieeexplore.ieee.org/document/9636352)
- Next-Best-View planning for surface reconstruction of large-scale 3D environments with multiple UAVs, Hardouin et al., IROS 2020 | [Paper](https://ieeexplore.ieee.org/document/9340897)
- Learn-to-Score: Efficient 3D Scene Exploration by Predicting View Utility,  et al., ECCV 2018 | [Paper](https://arxiv.org/abs/1806.10354)

<!-- #### Recurrent Prediction
- [](),  et al., arXiv 2018 -->

<!-- </details> -->



<!-- <details open> -->
<!-- <summary>Objects</summary> -->

### Objects

#### Reinforcement Learning
- RL-NBV: A deep reinforcement learning based next-best-view method for unknown object reconstruction, Wang et al., Pattern Recognition 2024 | [Paper](https://dl.acm.org/doi/abs/10.1016/j.patrec.2024.05.014)
- Bag of Views: An Appearance-based Approach to Next-Best-View Planning for 3D Reconstruction, Gazani et al., arXiv 2023 | [Paper](https://www.researchgate.net/publication/372313638_Bag_of_Views_An_Appearance-based_Approach_to_Next-Best-View_Planning_for_3D_Reconstruction)
- Learning to Select Camera Views: Efficient Multiview Understanding at Few Glances, Hou et al., CVPR 2024 | [Paper](https://arxiv.org/abs/2303.06145) | [Code](https://github.com/hou-yz/MVSelect)
- A Reinforcement Learning Approach to the View Planning Problem, Kaba et al., CVPR 2017 | [Paper](https://arxiv.org/abs/1610.06204)


#### Information Gain
- Beyond Uncertainty: Risk-Aware Active View Acquisition for Safe Robot Navigation and 3D Scene Understanding with FisherRF, Liu et al., arXiv 2024 | [Paper](https://arxiv.org/abs/2403.11396)
- FisherRF: Active View Selection and Uncertainty Quantification for Radiance Fields using Fisher Information, Jiang et al., ECCV 2024 | [Paper](https://arxiv.org/abs/2311.17874) | [Code](https://github.com/JiangWenPL/FisherRF)
- Active Implicit Reconstruction Using One-Shot View Planning, Hu et al., ICRA 2024 [Paper](https://arxiv.org/abs/2310.00685)
- SO-NeRF: Active View Planning for NeRF using Surrogate Objectives, Lee et al., arXiv 2023 | [Paper](https://arxiv.org/abs/2312.03266)
- NeU-NBV: Next Best View Planning Using Uncertainty Estimation in Image-Based Neural Rendering, Jin et al., IROS 2023 | [Paper](https://arxiv.org/abs/2303.01284) | [Code](https://github.com/dmar-bonn/neu-nbv)
- A Global Generalized Maximum Coverage-based Solution to the Non-model-based View Planning Problem for Object Reconstruction, Pan et al., CVIU 2023 | [Paper](https://dl.acm.org/doi/10.1016/j.cviu.2022.103585)
- ActiveRMAP: Radiance Field for Active Mapping And Planning, Zhan et al., arXiv 2022 | [Paper](https://arxiv.org/abs/2211.12656)
- Uncertainty-Driven Active Vision for Implicit Scene Reconstruction, Smith et al., arXiv 2022 | [Paper](https://arxiv.org/abs/2210.00978) | [Code](https://github.com/facebookresearch/Uncertainty-Driven-Active-Vision)
- ActiveNeRF: Learning where to See with Uncertainty Estimation, Pan et al., ECCV 2022 | [Paper](https://arxiv.org/abs/2209.08546)
- Uncertainty Guided Policy for Active Robotic 3D Reconstruction using Neural Radiance Fields, Lee et al., R-AL 2022 | [Paper](https://arxiv.org/abs/2209.08409) | [Video](https://www.youtube.com/watch?v=o__VGNqt2ok&ab_channel=SuryanshKumar)
- PC-NBV: A Point Cloud Based Deep Network for Efficient Next Best View Planning, Zeng et al., IROS 2020 | [Paper](https://ieeexplore.ieee.org/document/9340916) | [Code](https://github.com/Surean233/PC-NBV)
- Multi-Sensor Next-Best-View Planning as Matroid-Constrained Submodular Maximization, Lauri et al., RA-L 2020 | [Paper](https://arxiv.org/abs/2007.02084)
- A comparison of volumetric information gain metrics for active 3D object reconstruction, Delmerico et al., Autonomous Robots 2017 | [Paper](https://www.researchgate.net/publication/316362928_A_comparison_of_volumetric_information_gain_metrics_for_active_3D_object_reconstruction)
- An information gain formulation for active volumetric 3D reconstruction, Isler et al., ICRA 2016 | [Paper](https://ieeexplore.ieee.org/document/7487527) | [Project](https://cseweb.ucsd.edu/~viscomp/projects/NeuralTransmittance/index.html)


#### Recurrent Prediction
- Active Object Reconstruction Using a Guided View Planner, Yang et al., IJCAI 2018 | [Paper](https://dl.acm.org/doi/abs/10.5555/3304652.3304699)
- Geometry-Aware Recurrent Neural Networks for Active Visual Recognition, Cheng et al., NIPS 2018 | [Paper](https://arxiv.org/abs/1811.01292)

<!-- </details> -->




## Implementations
##### Libraries
<!-- - [Visu3d](https://github.com/google-research/visu3d), [@google](https://github.com/google-research), 2022 -->

## License
MIT
