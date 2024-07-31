# Awesome-Point-Cloud-Completion [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
This repository catalogs the papers I referenced while completing a project on point cloud completion using diffusion.

<img src="./assets/teaser.gif" width="696px">

#### [How to submit a pull request?](https://github.com/hitcslj/awesome-robust-depth-estimation/blob/main/how-to-PR.md)


## Table of Contents

- [Survey](#survey) 
- [Papers](#papers)
- [Benchmarks and Datasets](#Benchmarks-and-Datasets)
- [Talks](#talks)
- [Implementations](#implementations)

## Survey

- [Comprehensive Review of Deep Learning-Based 3D Point Cloud Completion Processing and Analysis](https://arxiv.org/abs/2203.03311), Fei et al., IEEE Transactions on Intelligent Transportation Systems 2017 | [bibtext](./citations/pc_survey1.txt) 
- [A Survey of Point Cloud Completion](https://ieeexplore.ieee.org/document/10433645), Zhuang et al., IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing 2017 | [bibtext](./citations/pc_survey2.txt) 


## Papers
<details open>
<summary>Point-based</summary>

- [PCN: Point Completion Network](https://arxiv.org/abs/1808.00671), Yuan et al., 3DV 2018 | [github](https://github.com/wentaoyuan/pcn) | [bibtext](./citations/pcn.txt) 
- [PoinTr: Diverse Point Cloud Completion with Geometry-Aware Transformers](https://arxiv.org/abs/2108.08839), Yu et al., ICCV 2021 | [github](https://github.com/yuxumin/PoinTr) | [bibtext](./citations/pointr.txt) 
- [A Conditional Point Diffusion-Refinement Paradigm for 3D Point Cloud Completion](https://arxiv.org/abs/2112.03530), Lyu et al., ICLR 2022 | [github](https://github.com/ZhaoyangLyu/Point_Diffusion_Refinement) | [bibtext](./citations/PDR.txt) 
- [AdaPoinTr: Diverse Point Cloud Completion with Adaptive Geometry-Aware Transformers](https://arxiv.org/abs/2301.04545), Yu et al., TPAMI 2023 | [github](https://github.com/yuxumin/PoinTr) | [bibtext](./citations/AdaPoinTr.txt)
- [PointAttN: You Only Need Attention for Point Cloud Completion](https://ojs.aaai.org/index.php/AAAI/article/view/28356), Wang et al., AAAI 2024 | [github](https://github.com/ohhhyeahhh/PointAttN) | [bibtext](./citations/pointAttn.txt)
- [T-CorresNet: Template Guided 3D Point Cloud Completion with Correspondence Pooling Query Generation Strategy](https://arxiv.org/abs/2407.05008v1), Duan et al., ECCV 2024 | [github](https://github.com/df-boy/T-CorresNet) | [bibtext](./citations/corresnet.txt)

</details>


<details open>
<summary>Voxel-based</summary>

- [High-Resolution Shape Completion Using Deep Neural Networks for Global Structure and Local Geometry Inference](https://arxiv.org/abs/1709.07599), Han et al., ICCV 2017 | [bibtext](./citations/pcn.txt) 
- [Learning 3D Shape Completion under Weak Supervision](https://arxiv.org/abs/1805.07290), Stutz et al., CVPR 2018 | [github](https://github.com/davidstutz/cvpr2018-shape-completion) | [bibtext](./citations/scweak.txt) 
- [Relation-Shape Convolutional Neural Network for Point Cloud Analysis](https://arxiv.org/abs/1904.07601), Liu et al., CVPR 2019 | [github](https://github.com/Yochengliu/Relation-Shape-CNN) | [bibtext](./citations/rscnn.txt) 

</details>

<details open>
<summary>PointVoxel(hybrid)-based</summary>

- [Point-Voxel CNN for Efficient 3D Deep Learning](https://arxiv.org/abs/1907.03739), Liu et al., NeurIPS 2019 | [github](https://github.com/mit-han-lab/pvcnn) | [bibtext](./citations/pvcnn.txt)
- [GRNet: Gridding Residual Network for Dense Point Cloud Completion](https://arxiv.org/abs/2006.03761), Xie et al., ECCV 2020 | [github](https://github.com/hzxie/GRNet) | [bibtext](./citations/grnet.txt)
- [3D Shape Generation and Completion through Point-Voxel Diffusion](https://arxiv.org/abs/2104.03670), Zhou et al., ICCV 2021 | [github](https://github.com/alexzhou907/PVD) | [bibtext](./citations/pvd.txt)

</details>

 

<details open>
<summary>TSDF-based</summary>

- [Diffusion-SDF: Text-to-Shape via Voxelized Diffusion](https://arxiv.org/abs/2212.03293), Li et al., CVPR 2023 | [github](https://github.com/ttlmh/Diffusion-SDF) | [bibtext](./citations/diffusionsdf.txt) 
- [DiffComplete: Diffusion-based Generative 3D Shape Completion](https://arxiv.org/abs/2306.16329), Chu et al., NeurIPS 2024 | [bibtext](./citations/diffcomplete.txt) 

</details>

<details open>
<summary>Latent feature-based</summary>

- [LION: Latent Point Diffusion Models for 3D Shape Generation](https://arxiv.org/abs/2210.06978), Zeng et al., NeurIPS 2022 | [github](https://github.com/nv-tlabs/LION) | [bibtext](./citations/lion.txt) 

</details>


<details open>
<summary>Neural Repersentation-based</summary>

- [Point-Cloud Completion with Pretrained Text-to-image Diffusion Models](https://arxiv.org/abs/2306.10533), Kasten et al., NeurIPS 2024| [github](https://github.com/NVlabs/sds-complete) | [bibtext](./citations/sds-complete.txt) 
- [Zero-shot Point Cloud Completion Via 2D Priors](https://arxiv.org/abs/2404.06814), Huang et al., arXiv 2024 | [bibtext](./citations/zeropc.txt) 

</details>

## Benchmarks and Datasets
- [ShapeNet](https://shapenet.org/) 
- [Completion3D: Stanford 3D Point Cloud Completion Benchmark](https://completion3d.stanford.edu/)

## Talks
- [Chulin Xie's talk, 2021](https://www.bilibili.com/video/BV1KP4y1w71q/?spm_id_from=333.337.search-card.all.click&vd_source=0fb3bb9416e8fa252211d77e6b01b9d0)
- [Xiaoyang Wu's talk, 2023](https://www.bilibili.com/video/BV1Az42187t9/?spm_id_from=333.337.search-card.all.click&vd_source=0fb3bb9416e8fa252211d77e6b01b9d0)

## Challenge
- [High-Quality Multi-View Partial Point Cloud for Completion](https://mvp-dataset.github.io/MVP/Completion.html), Pan et al., ICCV 2021 workshop | [github](https://github.com/paul007pl/MVP_Benchmark) | [bibtext](./citations/mvp-bench.txt) 


## Implementations
- TODO


## License 
awesome point cloud completion is released under the [MIT license](./LICENSE).

## Contact
Primary contact: hitcslj@stu.hit.edu.cn. You can also contact: hitcszgq@stu.hit.edu.cn.



