# Awesome Exploration Policy [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of awesome exploration policy papers, inspired by [awesome-computer-vision](https://github.com/jbhuang0604/awesome-computer-vision) and [awesome-NeRF](https://github.com/awesome-NeRF/awesome-NeRF).

We classify the primary technical frameworks of existing NBV policies into the following categories: 1) information gain (a.k.a. uncertainty), 2) reinforcement learning, 3) regression/recurrent prediction.

The exploration task, as known as or similar to next-best-view planning and active mapping, aims to determine the next best viewpoints to better model the target objects or scenes. The downstream tasks include: 3D reconstruction, neural rendering, SLAM, visual localization, object understanding, robotic manipulation.


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
- [A Survey on Active Simultaneous Localization and Mapping: State of the Art and New Frontiers](https://ieeexplore.ieee.org/abstract/document/10075065?casa_token=2C8evIgOOiMAAAAA:FAPNd2PC5v8QMh1SV25jHtyGzvhYVInMiJokq1c0lTg_D0PGFOKOHY0Khtt_at0gZSwgCSvggoo), Ahmed et al., T-RO, 2023
- [A Review on Viewpoints and Path Planning for UAV-Based 3-D Reconstruction](https://ieeexplore.ieee.org/abstract/document/10124957), Maboudi et al., IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing, 2023
- [Active SLAM: A Review On Last Decade](https://arxiv.org/abs/2212.11654), Ahmed et al., Sensors, 2023



## Papers

<!-- <details open> -->
<!-- <summary>Indoor Scenes</summary> -->
### Indoor Scenes

#### Reinforcement Learning
- [GLEAM: Learning Generalizable Exploration Policy for Active Mapping in Complex 3D Indoor Scenes](https://arxiv.org/abs/2505.20294), Chen et al., arXiv 2025
- [Learning to Explore using Active Neural SLAM](https://arxiv.org/abs/2004.05155), Chaplot et al., ICLR 2020
- [Learning Exploration Policies for Navigation](https://arxiv.org/abs/1903.01959), Chen et al., ICLR 2019


#### Information Gain

- [ActiveGS: Active Scene Reconstruction Using Gaussian Splatting](https://arxiv.org/abs/2412.17769), Jin et al., RA-L 2025
- [Multi-robot collaborative dense scene reconstruction](https://dl.acm.org/doi/10.1145/3306346.3322942), Dong et al., TOG 2019
- [Density-aware NeRF Ensembles: Quantifying Predictive Uncertainty in Neural Radiance Fields](https://arxiv.org/abs/2209.08718), Sünderhauf et al., arXiv 2022




#### Recurrent Prediction
- [Where to Explore Next? ExHistCNN for History-aware Autonomous 3D Exploration](https://arxiv.org/abs/2011.14669), Wang et al., ECCV 2020

<!-- </details> -->



<!-- <details open> -->
<!-- <summary>Outdoor Scenes</summary> -->
### Outdoor Scenes

#### Reinforcement Learning
- [GenNBV: Generalizable Next-Best-View Policy for Active 3D Reconstruction](), Chen et al., CVPR 2024
- [Next-Best View Policy for 3D Reconstruction](), Peralta et al., ECCV 2020 Workshop

#### Information Gain
- [Semantically Informed Next Best View Planning for Autonomous Aerial 3D Reconstruction](), Kay et al., IROS 2021
- [Next-Best-View planning for surface reconstruction of large-scale 3D environments with multiple UAVs](), Hardouin et al., IROS 2020
- [Learn-to-Score: Efficient 3D Scene Exploration by Predicting View Utility](),  et al., ECCV 2018

<!-- #### Recurrent Prediction
- [](),  et al., arXiv 2018 -->

<!-- </details> -->



<!-- <details open> -->
<!-- <summary>Objects</summary> -->

### Objects

#### Reinforcement Learning
- [RL-NBV: A deep reinforcement learning based next-best-view method for unknown object reconstruction](), Wang et al., Pattern Recognition 2024
- [Bag of Views: An Appearance-based Approach to Next-Best-View Planning for 3D Reconstruction](),  et al., arXiv 2023
- [Learning to Select Camera Views: Efficient Multiview Understanding at Few Glances](),  et al., arXiv 2023
- [A Reinforcement Learning Approach to the View Planning Problem](https://cseweb.ucsd.edu/~viscomp/projects/NeuralTransmittance/index.html), Kaba et al., CVPR 2017 | [bibtex](./citations/NeuralTransmittance.txt)


#### Information Gain
- [Multi-Sensor Next-Best-View Planning as Matroid-Constrained Submodular Maximization](), Lauri et al., RA-L 2020
- [Active Implicit Reconstruction Using One-Shot View Planning](), Hu et al., ICRA 2024
- [SO-NeRF: Active View Planning for NeRF using Surrogate Objectives](), Lee et al., arXiv 2023
- [FisherRF: Active View Selection and Uncertainty Quantification for Radiance Fields using Fisher Information](), Jiang et al., arXiv 2023
- [NeU-NBV: Next Best View Planning Using Uncertainty Estimation in Image-Based Neural Rendering](), Jin et al., IROS 2023
- [A Global Generalized Maximum Coverage-based Solution to the Non-model-based View Planning Problem for Object Reconstruction](), Pan et al., CVIU 2023
- [ActiveRMAP: Radiance Field for Active Mapping And Planning](), Zhan et al., arXiv 2022
- [Uncertainty-Driven Active Vision for Implicit Scene Reconstruction](), Smith et al., arXiv 2022
- [ActiveNeRF: Learning where to See with Uncertainty Estimation](), Pan et al., ECCV 2022
- [Uncertainty Guided Policy for Active Robotic 3D Reconstruction using Neural Radiance Fields](), Lee et al., R-AL 2016
- [PC-NBV: A Point Cloud Based Deep Network for Efficient Next Best View Planning](),  et al., IROS 2020
- [A comparison of volumetric information gain metrics for active 3D object reconstruction](), Delmerico et al., Autonomous 2017
- [An information gain formulation for active volumetric 3D reconstruction](https://cseweb.ucsd.edu/~viscomp/projects/NeuralTransmittance/index.html), Isler et al., ICRA 2016 | [bibtex](./citations/NeuralTransmittance.txt)


#### Recurrent Prediction
- [Active Object Reconstruction Using a Guided View Planner](), Yang et al., arXiv 2018
- [Geometry-Aware Recurrent Neural Networks for Active Visual Recognition](), Cheng et al., arXiv 2018

<!-- </details> -->




## Implementations
##### Libraries
<!-- - [Visu3d](https://github.com/google-research/visu3d), [@google](https://github.com/google-research), 2022 -->

## License
MIT
