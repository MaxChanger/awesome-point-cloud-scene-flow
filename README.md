# Awesome-Point-Cloud-Scene-Flow [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)


```diff
- Recent papers (from 2019) 
- welcome to add if any information misses. 😎
```

---
## 2021
- Learning to Segment Rigid Motions from Two Frames [[2101.03694]](http://arxiv.org/abs/2101.03694)[[code]](https://github.com/gengshan-y/rigidmask)
- **[CVPR 21 Oral]** Weakly Supervised Learning of Rigid 3D Scene Flow [[2102.08945]](http://arxiv.org/abs/2102.08945)[[code]](https://github.com/zgojcic/Rigid3DSceneFlow)
- Scalable Scene Flow from Point Clouds in the Real World [[2103.01306]](http://arxiv.org/abs/2103.01306)
- **[CVPR 21]** FESTA: Flow Estimation via Spatial-Temporal Attention for Scene Point Clouds [[2104.00798]](http://arxiv.org/abs/2104.00798)


## 2020
- **[ECCV 20]** PointPWC-Net: A Coarse-to-Fine Network for Supervised and Self-Supervised Scene Flow Estimation on 3D Point Clouds [[1911.12408]](http://arxiv.org/abs/1911.12408)[[code]](https://github.com/DylanWusee/PointPWC)![GitHub stars](https://img.shields.io/github/stars/DylanWusee/PointPWC.svg?logo=github&label=Stars)
- **[ECCV 20]** FLOT: Scene Flow on Point Clouds Guided by Optimal Transport [[2007.11142]](http://arxiv.org/abs/2007.11142)[[code]](https://github.com/valeoai/FLOT)![GitHub stars](https://img.shields.io/github/stars/valeoai/FLOT.svg?logo=github&label=Stars)
- **[3DV 20]** Scene Flow from Point Clouds with or without Learning [[2011.00320]](http://arxiv.org/abs/2011.00320)
- **[3DV 20]** Adversarial Self-Supervised Scene Flow Estimation [[2011.00551]](http://arxiv.org/abs/2011.00551)
- **[[WACV 20](https://openaccess.thecvf.com/content_WACV_2020/html/Wang_FlowNet3D_Geometric_Losses_For_Deep_Scene_Flow_Estimation_WACV_2020_paper.html)]** FlowNet3D++: Geometric Losses For Deep Scene Flow Estimation [[1912.01438]](http://arxiv.org/abs/1912.01438)
- **[[CVPR 20](https://openaccess.thecvf.com/content_CVPR_2020/html/Mittal_Just_Go_With_the_Flow_Self-Supervised_Scene_Flow_Estimation_CVPR_2020_paper.html)]** Just Go With the Flow: Self-Supervised Scene Flow Estimation [[1912.00497]](https://arxiv.org/abs/1912.00497)[[code]](https://github.com/HimangiM/Just-Go-with-the-Flow-Self-Supervised-Scene-Flow-Estimation)![GitHub stars](https://img.shields.io/github/stars/HimangiM/Just-Go-with-the-Flow-Self-Supervised-Scene-Flow-Estimation.svg?logo=github&label=Stars)
- Hierarchical Attention Learning of Scene Flow in 3D Point Clouds [[2010.05762]](https://arxiv.org/abs/2010.05762)
- PWCLO-Net: Deep LiDAR Odometry in 3D Point Clouds Using Hierarchical Embedding Mask Optimization [[2012.00972]](https://arxiv.org/abs/2012.00972)
- FlowStep3D: Model Unrolling for Self-Supervised Scene Flow Estimation [[2011.10147]](https://arxiv.org/abs/2011.10147)
- RAFT-3D: Scene Flow using Rigid-Motion Embeddings [[2012.00726]](http://arxiv.org/abs/2012.00726)
- PV-RAFT: Point-Voxel Correlation Fields for Scene Flow Estimation of Point Clouds [[2012.00987]](https://arxiv.org/abs/2012.00987)
- VoxFlowNet: Learning Scene Flow in 3D Point Clouds through Voxel Grids [[code]](https://github.com/pablorpalafox/voxflownet)![GitHub stars](https://img.shields.io/github/stars/pablorpalafox/voxflownet.svg?logo=github&label=Stars)



---
## 2019
- **[[ICCV 19](https://openaccess.thecvf.com/content_ICCV_2019/html/Liu_MeteorNet_Deep_Learning_on_Dynamic_3D_Point_Cloud_Sequences_ICCV_2019_paper.html)]** MeteorNet: Deep Learning on Dynamic 3D Point Cloud Sequences [[1910.09165]](http://arxiv.org/abs/1910.09165)[[code]](https://github.com/xingyul/meteornet)![GitHub stars](https://img.shields.io/github/stars/xingyul/meteornet.svg?logo=github&label=Stars)
- **[[CVPR 19](https://openaccess.thecvf.com/content_CVPR_2019/html/Liu_FlowNet3D_Learning_Scene_Flow_in_3D_Point_Clouds_CVPR_2019_paper.html)]** FlowNet3D: Learning Scene Flow in 3D Point Clouds [[1806.01411]](https://arxiv.org/abs/1806.01411)[[code]](https://github.com/xingyul/flownet3d)![GitHub stars](https://img.shields.io/github/stars/xingyul/flownet3d.svg?logo=github&label=Stars)
- **[[CVPR 19](https://openaccess.thecvf.com/content_CVPR_2019/html/Gu_HPLFlowNet_Hierarchical_Permutohedral_Lattice_FlowNet_for_Scene_Flow_Estimation_on_CVPR_2019_paper.html)]** HPLFlowNet: Hierarchical Permutohedral Lattice FlowNet for Scene Flow Estimation on Large-scale Point Clouds [[1906.05332]](https://arxiv.org/abs/1906.05332)[[code]](https://github.com/laoreja/HPLFlowNet)![GitHub stars](https://img.shields.io/github/stars/laoreja/HPLFlowNet.svg?logo=github&label=Stars)



---
## Dataset

Since there is currently **no raw dataset for Scene Flow Estimation with a point cloud as input**, the pioneers [FlowNet3D ](https://github.com/xingyul/flownet3d)and [HPLFlowNet ](https://github.com/laoreja/HPLFlowNet)provide two versions of the dataset based on the raw dataset.

- FlyingThings3D [[official website]](https://lmb.informatik.uni-freiburg.de/resources/datasets/SceneFlowDatasets.en.html)
- KITTI 2015 [[official website]](http://www.cvlibs.net/datasets/kitti/eval_scene_flow.php?benchmark=flow)
- Processed by FlowNet3D [[code]](https://github.com/xingyul/flownet3d)
- Processed by HPLFlowNet [[code]](https://github.com/laoreja/HPLFlowNet)

> There are some differences in the way FlowNet3D and HPLFlowNet process data.
> [FlowNet3D **only** provides the code to process FlyingThings3D, HPLFlowNet provides code to process FlyingThings3D and KITTI15]
> Some papers will compare two kinds of data at the same time. [But at the moment there seems to be more comparisons on HPLFlowNet]

