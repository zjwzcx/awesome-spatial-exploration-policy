# Awesome Next-Best-View (NBV) Planning [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of awesome NBV planning papers, inspired by [awesome-computer-vision](https://github.com/jbhuang0604/awesome-computer-vision).


## Table of Contents

- [Survey](#survey)
- [Papers](#papers)
- [Talks](#talks)
- [Implementations](#implementations)

## Survey
- [Semantically-aware Neural Radiance Fields for Visual Scene Understanding: A Comprehensive Review](https://arxiv.org/abs/2402.11141), Thang-Anh-Quan Nguyen*, Amine Bourki*, Màtyàs Macudzinski, Anthony Brunel, and Mohammed Bennamoun (*: Equal contribution), Arxiv 2024 | [github](https://github.com/abourki/SoTA-Semantically-aware-NeRFs) | [bibtex](citations/survey_semantically-awareNeRFs.txt)
- [BeyondPixels: A Comprehensive Review of the Evolution of Neural Radiance Fields](https://arxiv.org/abs/2306.03000), AKM Shahariar Azad Rabby and Chengcui Zhang, Arxiv 2023 | [bibtex](citations/BeyondPixels.txt)
- [Neural Volume Rendering: NeRF And Beyond](https://arxiv.org/abs/2101.05204), Dellaert and Yen-Chen, Arxiv 2020 | [blog](https://dellaert.github.io/NeRF/) | [github](https://raw.githubusercontent.com/yenchenlin/awesome-NeRF/main/NeRF-and-Beyond.bib) | [bibtex](https://github.com/yenchenlin/awesome-NeRF/blob/main/citations/nerf-survey.txt)
- [NeRF: Neural Radiance Field in 3D Vision, Introduction and Review](https://arxiv.org/abs/2210.00379), Kyle Gao, Yina Gao, Hongjie He, Dening Lu, Linlin Xu, Jonathan Li
- [Neural Fields in Robotics: A Survey](https://arxiv.org/abs/2410.20220), Muhammad Zubair Irshad, Mauro Comi, Yen-Chen Lin, Nick Heppert, Abhinav Valada, Zsolt Kira, Rares Ambrus, Johnathan Trembley

## Papers
- [NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis](https://www.matthewtancik.com/nerf), Mildenhall et al., ECCV 2020 | [github](https://github.com/bmild/nerf)  | [bibtex](./NeRF-and-Beyond.bib#L168-L173) <!---Mildenhall20eccv_nerf-->


<details open>
<summary>Faster Inference</summary>

- [Learning Neural Transmittance for Efficient Rendering of Reflectance Fields](https://cseweb.ucsd.edu/~viscomp/projects/NeuralTransmittance/index.html), Mohammad Shafiei et al., BMVC 2021 | [bibtex](./citations/NeuralTransmittance.txt)

</details>




<details open>
<summary>Deformable</summary>

- [Deformable Neural Radiance Fields](https://nerfies.github.io/), Park et al., Arxiv 2020 | [github](https://github.com/google/nerfies) | [bibtex](./NeRF-and-Beyond.bib#L206-L212) <!---Park20arxiv_nerfies-->
- [D-NeRF: Neural Radiance Fields for Dynamic Scenes](https://www.albertpumarola.com/research/D-NeRF/index.html), Pumarola et al., CVPR 2021 | [github](https://github.com/albertpumarola/D-NeRF) | [bibtex](./NeRF-and-Beyond.bib#L214-L220) <!---Pumarola20arxiv_D_NeRF-->

</details>



<details open>
<summary>Generalization</summary>

- [GRAF: Generative Radiance Fields for 3D-Aware Image Synthesis](https://arxiv.org/abs/2007.02442), Schwarz et al., NeurIPS 2020 | [github](https://github.com/autonomousvision/graf)  | [bibtex](./NeRF-and-Beyond.bib#L237-L243) <!---Schwarz20neurips_graf-->
- [GRF: Learning a General Radiance Field for 3D Scene Representation and Rendering](https://arxiv.org/abs/2010.04595), Trevithick and Yang, Arxiv 2020 | [github](https://github.com/alextrevithick/GRF) | [bibtex](./NeRF-and-Beyond.bib#L291-L297) <!---Trevithick20arxiv_GRF-->
- [pixelNeRF: Neural Radiance Fields from One or Few Images](https://arxiv.org/abs/2012.02190), Yu et al., CVPR 2021 | [github](https://github.com/sxyu/pixel-nerf) | [bibtex](./NeRF-and-Beyond.bib#L329-L335) <!---Yu20arxiv_pixelNeRF-->
- [Learned Initializations for Optimizing Coordinate-Based Neural Representations](https://arxiv.org/abs/2012.02189), Tancik et al., CVPR 2021 | [github](https://github.com/tancik/learnit) | [bibtex](./NeRF-and-Beyond.bib#L268-L274) <!---Tancik20arxiv_meta-->
- [pi-GAN: Periodic Implicit Generative Adversarial Networks for 3D-Aware Image Synthesis](https://marcoamonteiro.github.io/pi-GAN-website/), Chan et al., CVPR 2021 | [bibtex](./NeRF-and-Beyond.bib#L24-L30) <!---Chan20arxiv_piGAN-->
- [Portrait Neural Radiance Fields from a Single Image](https://portrait-nerf.github.io/), Gao et al., Arxiv 2020 | [bibtex](./NeRF-and-Beyond.bib#L95-L101) <!---Gao20arxiv_pNeRF-->
- [ShaRF: Shape-conditioned Radiance Fields from a Single View](https://arxiv.org/pdf/2102.08860.pdf), Rematas et al., ICML 2021 | [bibtex](./citations/sharf.txt)
- [IBRNet: Learning Multi-View Image-Based Rendering](https://ibrnet.github.io/static/paper.pdf), Wang et al., CVPR 2021 | [github](https://github.com/googleinterns/IBRNet) | [bibtex](./citations/ibr.txt)
- [CAMPARI: Camera-Aware Decomposed Generative Neural Radiance Fields](https://arxiv.org/pdf/2103.17269.pdf), Niemeyer & Geiger, Arxiv 2021 | [bibtex](./citations/CAMPARI.txt)
- [NeRF-VAE: A Geometry Aware 3D Scene Generative Model](https://arxiv.org/pdf/2104.00587.pdf), Kosiorek et al., Arxiv 2021 | [bibtex](./citations/nerf-vae.txt)
- [Unconstrained Scene Generation with Locally Conditioned Radiance Fields](https://apple.github.io/ml-gsn/), DeVries et al., Arxiv 2021 | [bibtex](./citations/gsn.txt)
- [MVSNeRF: Fast Generalizable Radiance Field Reconstruction from Multi-View Stereo](https://apchenstu.github.io/mvsnerf/), Chen et al., ICCV 2021 | [github](https://github.com/apchenstu/mvsnerf) | [bibtex](./citations/mvsnerf.txt)
- [Stereo Radiance Fields (SRF): Learning View Synthesis from Sparse Views of Novel Scenes](https://virtualhumans.mpi-inf.mpg.de/srf/), Chibane et al., CVPR 2021 | [bibtex](./citations/srf.txt)
- [Neural Rays for Occlusion-aware Image-based Rendering](https://liuyuan-pal.github.io/NeuRay/), Liu et al., Arxiv 2021 | [bibtex](./citations/neuray.txt)
- [Putting NeRF on a Diet: Semantically Consistent Few-Shot View Synthesis](https://www.ajayj.com/dietnerf), Matthew Tancik et al., Arxiv 2021 | [bibtex](./citations/DietNeRF.txt)
- [MINE: Towards Continuous Depth MPI with NeRF for Novel View Synthesis](https://vincentfung13.github.io/projects/mine/), Jiaxin Li et al., ICCV 2021 | [github](https://github.com/vincentfung13/MINE) | [bibtex](./citations/MINE.txt)
- [TöRF: Time-of-Flight Radiance Fields for Dynamic Scene View Synthesis](https://imaging.cs.cmu.edu/torf/), Benjamin Attal et al., NeurIPS 2021 | [bibtex](./citations/turf.txt)
- [CodeNeRF: Disentangled Neural Radiance Fields for Object Categories](https://sites.google.com/view/wbjang/home/codenerf), Jang et al., ICCV 2021 | [bibtex](./citations/CodeNeRF.txt)
- [StyleNeRF: A Style-based 3D-Aware Generator for High-resolution Image Synthesis](http://jiataogu.me/style_nerf/), Gu et al., Arxiv 2021 | [bibtex](./citations/stylenerf.txt)
- [Generative Occupancy Fields for 3D Surface-Aware Image Synthesis](https://sheldontsui.github.io/projects/GOF), Xu et al., NeurIPS 2021 | [github](https://github.com/SheldonTsui/GOF_NeurIPS2021) | [bibtex](./citations/gof.txt)
- [NeRF in the Dark: High Dynamic Range View Synthesis from Noisy Raw Images](https://bmild.github.io/rawnerf/), Ben Mildenhall et al, arXiv 2021 | [bibtex](./citations/rawnerf.txt)
- [Point-NeRF: Point-based Neural Radiance Fields](https://xharlie.github.io/projects/project_sites/pointnerf/index.html), Xu et al., CVPR 2022 | [github](https://github.com/Xharlie/pointnerf) | [bibtex](./citations/Point-NeRF.txt)
- [SinNeRF: Training Neural Radiance Fields on Complex Scenes from a Single Image](https://vita-group.github.io/SinNeRF/), Xu et al., ECCV 2022 | [github](https://github.com/VITA-Group/SinNeRF) | [bibtex](./citations/SinNeRF.txt)
- [Rodin: A Generative Model for Sculpting 3D Digital Avatars Using Diffusion](https://3d-avatar-diffusion.microsoft.com/), Wang et al., CVPR 2023 | [github](https://3d-avatar-diffusion.microsoft.com/) | [bibtex](./citations/rodin.txt)
- [SurfelNeRF: Neural Surfel Radiance Fields for Online Photorealistic Reconstruction of Indoor Scenes](https://arxiv.org/abs/2304.08971), Gao et al., CVPR 2023 | [github](https://gymat.github.io/SurfelNeRF-web/) | [bibtex](./citations/SurfelNeRF.txt)
- [NeO 360: Neural Fields for Sparse View Synthesis of Outdoor Scenes](https://arxiv.org/abs/2308.12967), Irshad et al., ICCV 2023 | [github](https://github.com/zubair-irshad/NeO-360) | [bibtex](./citations/SurfelNeRF.txt)
- [X-NeRF: Explicit Neural Radiance Field for Multi-Scene 360° Insufficient RGB-D Views](https://arxiv.org/abs/2210.05135), Zhu et al., WACV 2023 | [github](https://github.com/HaoyiZhu/XNeRF) | [bibtex](./citations/x-nerf.txt)
- [UFORecon: Generalizable Sparse-View Surface Reconstruction from Arbitrary and Unfavorable Sets](https://arxiv.org/abs/2403.05086), Na et al., CVPR 2024 | [github](https://github.com/Youngju-Na/UFORecon) | [bibtex](./citations/uforecon.txt)
- [🏡Know Your Neighbors: Improving Single-View Reconstruction via Spatial Vision-Language Reasoning](https://arxiv.org/abs/2404.03658), Li et al., CVPR 2024 | [github](https://github.com/ruili3/Know-Your-Neighbors) | [bibtex](./citations/KYN.txt)
</details>


<details open>
<summary>Pre-training</summary>
- [NeRF-MAE: Masked AutoEncoders for Self-Supervised 3D Representation Learning for Neural Radiance Fields](https://arxiv.org/pdf/2404.01300), Irshad et al., ECCV 2024 | [bibtex](./citations/nerf-mae.txt)
- [Ponder: Point Cloud Pre-training via Neural Rendering](https://openaccess.thecvf.com/content/ICCV2023/html/Huang_Ponder_Point_Cloud_Pre-training_via_Neural_Rendering_ICCV_2023_paper.html), Huang et al., ICCV 2023 | [bibtex](./citations/ponder.txt)
- [PonderV2: Pave the Way for 3D Foundation Model with A Universal Pre-training Paradigm](https://arxiv.org/abs/2310.08586), Zhu et al., Arxiv 2023 | [github](https://github.com/OpenGVLab/PonderV2) | [bibtex](./citations/ponderv2.txt)
- [UniPAD: A Universal Pre-training Paradigm for Autonomous Driving](https://arxiv.org/abs/2310.08370), Yang et al., Arxiv 2023 | [github](https://github.com/Nightmare-n/UniPAD) | [bibtex](./citations/unipad.txt)
</details>

## Implementations
#### Libraries
- [Visu3d](https://github.com/google-research/visu3d), [@google](https://github.com/google-research), 2022

## License
MIT
