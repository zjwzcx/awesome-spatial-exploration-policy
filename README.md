# Awesome Next-Best-View (NBV) Planning [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of awesome NBV planning papers, inspired by [awesome-computer-vision](https://github.com/jbhuang0604/awesome-computer-vision) and [awesome-NeRF](https://github.com/awesome-NeRF/awesome-NeRF).

The downstream tasks include: 3D reconstruction, neural rendering, SLAM, visual localization, object understanding, robotic manipulation.

We classify the primary technical frameworks of existing NBV policies into the following categories: 1) information gain (aka, uncertainty), 2) reinforcement learning, 3) regression/recurrent prediction.



## Table of Contents

- [Survey](#survey)
- [Papers](#papers)
  - [NBV policy for Objects](#objects)
  - [NBV policy for Indoor Scenes](#indoor-scenes)
  - [NBV policy for Outdoor Scenes](#outdoor-scenes)
  <!-- - [Information Gain-based](#information-gain) -->
  <!-- - [Reinforcement Learning-based](#reinforcement-learning) -->

<!-- - [](),  et al., ICRA 2016 | [bibtex](./citations/.txt) -->


## Survey
- [Semantically-aware Neural Radiance Fields for Visual Scene Understanding: A Comprehensive Review](https://arxiv.org/abs/2402.11141), Thang-Anh-Quan Nguyen*, Amine Bourki*, Màtyàs Macudzinski, Anthony Brunel, and Mohammed Bennamoun (*: Equal contribution), arXiv 2024 | [github](https://github.com/abourki/SoTA-Semantically-aware-NeRFs) | [bibtex](citations/survey_semantically-awareNeRFs.txt)


## Papers


<details open>
<summary>Objects</summary>
### Information Gain

- [](),  et al., ICRA 2016 | [bibtex](./citations/.txt) 
- [Multi-Sensor Next-Best-View Planning as Matroid-Constrained Submodular Maximization](), Lauri et al., RA-L 2020 | [bibtex](./citations/.txt) 
- [Active Implicit Reconstruction Using One-Shot View Planning](), Hu et al., ICRA 2024 | [bibtex](./citations/.txt) 
- [SO-NeRF: Active View Planning for NeRF using Surrogate Objectives](), Lee et al., arXiv 2023 | [bibtex](./citations/.txt) 
- [FisherRF: Active View Selection and Uncertainty Quantification for Radiance Fields using Fisher Information](), Jiang et al., arXiv 2023 | [bibtex](./citations/.txt) 
- [NeU-NBV: Next Best View Planning Using Uncertainty Estimation in Image-Based Neural Rendering](), Jin et al., IROS 2023 | [bibtex](./citations/.txt) 
- [A Global Generalized Maximum Coverage-based Solution to the Non-model-based View Planning Problem for Object Reconstruction](), Pan et al., CVIU 2023 | [bibtex](./citations/.txt)
- [ActiveRMAP: Radiance Field for Active Mapping And Planning](), Zhan et al., arXiv 2022 | [bibtex](./citations/.txt)
- [Uncertainty-Driven Active Vision for Implicit Scene Reconstruction](), Smith et al., arXiv 2022 | [bibtex](./citations/.txt)
- [ActiveNeRF: Learning where to See with Uncertainty Estimation](), Pan et al., ECCV 2022 | [bibtex](./citations/.txt)
- [Uncertainty Guided Policy for Active Robotic 3D Reconstruction using Neural Radiance Fields](), Lee et al., R-AL 2016 | [bibtex](./citations/.txt)
- [PC-NBV: A Point Cloud Based Deep Network for Efficient Next Best View Planning](),  et al., IROS 2020 | [bibtex](./citations/.txt)
- [A comparison of volumetric information gain metrics for active 3D object reconstruction](), Delmerico et al., Autonomous 2017 | [bibtex](./citations/.txt)
- [An information gain formulation for active volumetric 3D reconstruction](https://cseweb.ucsd.edu/~viscomp/projects/NeuralTransmittance/index.html), Isler et al., ICRA 2016 | [bibtex](./citations/NeuralTransmittance.txt)

### Reinforcement Learning
- [](),  et al., ICRA 2016 | [bibtex](./citations/.txt) 
- [RL-NBV: A deep reinforcement learning based next-best-view method for unknown object reconstruction](), Wang et al., Pattern Recognition 2024 | [bibtex](./citations/.txt) 
- [Bag of Views: An Appearance-based Approach to Next-Best-View Planning for 3D Reconstruction](),  et al., arXiv 2023 | [bibtex](./citations/.txt) 
- [Learning to Select Camera Views: Efficient Multiview Understanding at Few Glances](),  et al., arXiv 2023 | [bibtex](./citations/.txt)
- [A Reinforcement Learning Approach to the View Planning Problem](https://cseweb.ucsd.edu/~viscomp/projects/NeuralTransmittance/index.html), Kaba et al., CVPR 2017 | [bibtex](./citations/NeuralTransmittance.txt)



### Recurrent Prediction
- [Active Object Reconstruction Using a Guided View Planner](), Yang et al., arXiv 2018 | [bibtex](./citations/.txt) 
- [Geometry-Aware Recurrent Neural Networks for Active Visual Recognition](), Cheng et al., arXiv 2018 | [bibtex](./citations/.txt)

</details>




<details open>
<summary>Indoor Scenes</summary>
### Information Gain

- [Multi-robot collaborative dense scene reconstruction](), Dong et al., Transactions on Graphics 2019 | [bibtex](./citations/.txt) 
- [Density-aware NeRF Ensembles: Quantifying Predictive Uncertainty in Neural Radiance Fields](), Sünderhauf et al., arXiv 2022 | [bibtex](./citations/.txt)




### Reinforcement Learning
- [](),  et al., ICRA 2016 | [bibtex](./citations/.txt) 
- [Learning to Explore using Active Neural SLAM](), Chaplot et al., ICLR 2020 | [bibtex](./citations/.txt) 
- [Learning Exploration Policies for Navigation](), Chen et al., ICLR 2019 | [bibtex](./citations/.txt)

### Recurrent Prediction
- [](),  et al., ICRA 2016 | [bibtex](./citations/.txt) 
- [Where to Explore Next? ExHistCNN for History-aware Autonomous 3D Exploration](), Wang et al., ECCV 2020 | [bibtex](./citations/.txt)

</details>



<details open>
<summary>Outdoor Scenes</summary>
### Information Gain
- [Semantically Informed Next Best View Planning for Autonomous Aerial 3D Reconstruction](), Kay et al., IROS 2021 | [bibtex](./citations/.txt)
- [Next-Best-View planning for surface reconstruction of large-scale 3D environments with multiple UAVs](), Hardouin et al., IROS 2020 | [bibtex](./citations/.txt)
- [Learn-to-Score: Efficient 3D Scene Exploration by Predicting View Utility](),  et al., ECCV 2018 | [bibtex](./citations/.txt)

### Reinforcement Learning
- [GenNBV: Generalizable Next-Best-View Policy for Active 3D Reconstruction](), Chen et al., CVPR 2024 | [bibtex](./citations/.txt)
- [Next-Best View Policy for 3D Reconstruction](), Peralta et al., ECCV 2020 Workshop | [bibtex](./citations/.txt)


### Recurrent Prediction
- [](),  et al., arXiv 2018 | [bibtex](./citations/.txt)

</details>






## Implementations
#### Libraries
- [Visu3d](https://github.com/google-research/visu3d), [@google](https://github.com/google-research), 2022

## License
MIT
