# Awesome Visual Localization [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of visual (re)localization related resources, inspired by [awesome-computer-vision](https://github.com/jbhuang0604/awesome-computer-vision). 
The list focuses on the research of visual localization, i.e. estimates 6 DoF camera poses of query RGB/RGB-D frames in known scenes (with databases). 

This document is a work in progress. 
Please suggest papers/resources through pull requests. 
If you believe this list is missing something or has factually inaccurate info, you can also new an issue. All contributions are appreciated.


## Table of Contents

- [Image Retrieval](#image-retrieval)
- [Camera Pose Regression](#camera-pose-regression)
- [Feature Matching](#feature-matching)
- [Scene Coordinate Regression](#scene-coordinate-regression)
- [Camera Pose Optimization and Refinement](#camera-pose-optimization-and-refinement)
- [Datasets and Benchmarks](#datasets-and-benchmarks)




## Image Retrieval

- [2023 ICCV] EigenPlaces: Training Viewpoint Robust Models for Visual Place Recognition [[paper]](https://arxiv.org/pdf/2308.10832) [[code]](https://github.com/gmberton/EigenPlaces)
- [2022 CVPR] Rethinking Visual Geo-localization for Large-Scale Applications [[paper]](https://arxiv.org/pdf/2204.02287) [[code]](https://github.com/gmberton/CosPlace)
- [2022 IJCV] Investigating the Role of Image Retrieval for Visual Localization - An exhaustive benchmark [[paper]](https://arxiv.org/pdf/2205.15761.pdf)
- [2020 ECCV] Self-supervising Fine-grained Region Similarities for Large-scale Image Localization [[paper]](https://arxiv.org/pdf/2006.03926) [[code]](https://github.com/yxgeee/OpenIBL)
- [2020 3DV] Benchmarking Image Retrieval for Visual Localization [[paper]](https://arxiv.org/pdf/2011.11946.pdf)
- [2019 ICCV] Learning with Average Precision: Training Image Retrieval with a Listwise Loss [[paper]](https://arxiv.org/pdf/1906.07589) [[code]](https://github.com/naver/deep-image-retrieval)
- [2018 CVPR] PointNetVLAD: Deep Point Cloud Based Retrieval for Large-Scale Place Recognition [[paper]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Uy_PointNetVLAD_Deep_Point_CVPR_2018_paper.pdf) [[code]](https://openaccess.thecvf.com/content_iccv_2015/papers/Zeisl_Camera_Pose_Voting_ICCV_2015_paper.pdf)
- [2017 CVPR] Large-Scale Image Retrieval with Attentive Deep Local Features [[paper]](https://arxiv.org/pdf/1612.06321)
- [2016 CVPR] NetVLAD: CNN architecture for weakly supervised place recognition [[paper]](https://openaccess.thecvf.com/content_cvpr_2016/papers/Arandjelovic_NetVLAD_CNN_Architecture_CVPR_2016_paper.pdf) [[code]](https://github.com/Relja/netvlad)
- [2016 CVPR] Large-Scale Location Recognition and the Geometric Burstiness Problem [[paper]](https://openaccess.thecvf.com/content_cvpr_2016/papers/Sattler_Large-Scale_Location_Recognition_CVPR_2016_paper.pdf) [[code]](https://github.com/tsattler/geometric_burstiness)
- [2015 CVPR] 24/7 place recognition by view synthesis [[paper]](https://openaccess.thecvf.com/content_cvpr_2015/papers/Torii_247_Place_Recognition_2015_CVPR_paper.pdf) [[code]](http://www.ok.ctrl.titech.ac.jp/~torii/project/247/)
- [2014 TVCG] Real-Time RGB-D Camera Relocalization via Randomized Ferns for Keyframe Encoding [[paper]](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/glocker2014tvcg5B15D.pdf)
- [2013 CVPR] All about VLAD [[paper]](https://openaccess.thecvf.com/content_cvpr_2013/papers/Arandjelovic_All_About_VLAD_2013_CVPR_paper.pdf)
- [2012 BMVC] Image Retrieval for Image-Based Localization Revisited [[paper]](https://www.graphics.rwth-aachen.de/publication/188/sattler_weyand_bmvc12.pdf)
- [2012 BMVC] 6D Relocalisation for RGBD Cameras Using Synthetic View Regression
- [2011 IROS] Real-Time Loop Detection with Bags of Binary Words [[paper]](http://doriangalvez.com/papers/GalvezIROS11.pdf)




## Camera Pose Regression

- [2025 CVPR] Reloc3r: Large-Scale Training of Relative Camera Pose Regression for Generalizable, Fast, and Accurate Visual Localization [[paper]](https://arxiv.org/pdf/2412.08376) [[code]](https://github.com/ffrivera0/reloc3r)
- [2024 ECCV] SPVLoc: Semantic Panoramic Viewport Matching for 6D Camera Localization in Unseen Environments [[paper]](https://arxiv.org/pdf/2404.10527) [[code]](https://fraunhoferhhi.github.io/spvloc/)
- [2024 ECCV] Learning Neural Volumetric Pose Features for Camera Localization [[paper]](https://arxiv.org/pdf/2403.12800)
- [2024 CVPR] Map-Relative Pose Regression for Visual Re-Localization [[paper]](https://arxiv.org/pdf/2404.09884) [[code]](https://github.com/nianticlabs/marepo)
- [2023 AAAI] RobustLoc: Robust Camera Pose Regression in Challenging Driving Environments [[paper]](https://arxiv.org/pdf/2211.11238.pdf) [[code]](https://github.com/sijieaaa/RobustLoc)
- [2022 ECCV] Map-Free Visual Relocalization: Metric Pose Relative to a Single Image [[paper]](https://arxiv.org/pdf/2210.05494) [[code]](https://github.com/nianticlabs/map-free-reloc)
- [2022 ECCV] DFNet: Enhance Absolute Pose Regression with Direct Feature Matching [[paper]](https://arxiv.org/pdf/2204.00559.pdf) [[code]](https://github.com/ActiveVisionLab/DFNet)
- [2022 ECCV] Camera Pose Auto-Encoders for Improving Pose Regression [[paper]](https://arxiv.org/abs/2207.05530) [[code]](https://github.com/yolish/camera-pose-auto-encoders)
- [2022 WACV] CoordiNet: uncertainty-aware pose regressor for reliable vehicle localization [[paper]](https://openaccess.thecvf.com/content/WACV2022/papers/Moreau_CoordiNet_Uncertainty-Aware_Pose_Regressor_for_Reliable_Vehicle_Localization_WACV_2022_paper.pdf)
- [2021 3DV] Direct-PoseNet: Absolute Pose Regression with Photometric Consistency [[paper]](https://arxiv.org/pdf/2104.04073.pdf) [[code]](https://github.com/ActiveVisionLab/direct-posenet)
- [2021 3DV] Visual Camera Re-Localization Using Graph Neural Networks and Relative Pose Supervision [[paper]](https://arxiv.org/pdf/2104.02538.pdf) [[code]](https://github.com/nianticlabs/relpose-gnn)
- [2021 ICCV] Learning Multi-Scene Absolute Pose Regression with Transformers [[paper]](https://arxiv.org/pdf/2103.11468.pdf) [[code]](https://github.com/yolish/multi-scene-pose-transformer)
- [2021 ICRA] Learning to Localize in New Environments from Synthetic Training Data [[paper]](https://arxiv.org/pdf/2011.04539) [[code]](https://github.com/DLR-RM/ExReNet)
- [2021 CoRL] LENS: Localization enhanced by NeRF synthesis [[paper]](https://arxiv.org/abs/2110.06558) 
- [2020 ECCV] 6D Camera Relocalization in Ambiguous Scenes via Continuous Multimodal Inference [[paper]](https://arxiv.org/pdf/2004.04807.pdf) [[code]](https://multimodal3dvision.github.io/)
- [2020 CVPR] Learning Multi-view Camera Relocalization with Graph Neural Networks [[paper]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Xue_Learning_Multi-View_Camera_Relocalization_With_Graph_Neural_Networks_CVPR_2020_paper.pdf)
- [2020 AAAI] AtLoc: Attention Guided Camera Localization [[paper]](https://arxiv.org/pdf/1909.03557.pdf) [[code]](https://github.com/BingCS/AtLoc)
- [2019 ECCV] CamNet: Coarse-to-Fine Retrieval for Camera Re-Localization [[paper]](http://openaccess.thecvf.com/content_ICCV_2019/papers/Ding_CamNet_Coarse-to-Fine_Retrieval_for_Camera_Re-Localization_ICCV_2019_paper.pdf)
- [2019 CVPR] Understanding the Limitations of CNN-based Absolute Camera Pose Regression [[paper]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Sattler_Understanding_the_Limitations_of_CNN-Based_Absolute_Camera_Pose_Regression_CVPR_2019_paper.pdf)
- [2018 ECCV] RelocNet: Continuous Metric Learning Relocalisation using Neural Nets [[paper]](https://openaccess.thecvf.com/content_ECCV_2018/papers/Vassileios_Balntas_RelocNet_Continous_Metric_ECCV_2018_paper.pdf) 
- [2018 BMVC] Improved Visual Relocalization by Discovering Anchor Points [[paper]](https://arxiv.org/pdf/1811.04370.pdf) [[code]](https://github.com/Soham0/Improved-Visual-Relocalization)
- [2018 CVPR] Geometry-Aware Learning of Maps for Camera Localization [[paper]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Brahmbhatt_Geometry-Aware_Learning_of_CVPR_2018_paper.pdf) [[code]](https://github.com/NVlabs/geomapnet)
- [2018 RA-L] VLocNet++: Deep Multitask Learning for Semantic Visual Localization and Odometry [[paper]](https://arxiv.org/pdf/1804.08366.pdf)
- [2017 ICCV Workshop] Camera Relocalization by Computing Pairwise Relative Poses Using Convolutional Neural Network [[paper]](https://openaccess.thecvf.com/content_ICCV_2017_workshops/papers/w17/Laskar_Camera_Relocalization_by_ICCV_2017_paper.pdf) [[code]](https://github.com/AaltoVision/camera-relocalisation)
- [2017 IROS] Deep regression for monocular camera-based 6-dof global localization in outdoor environments [[paper]](https://ieeexplore.ieee.org/iel7/8119304/8202121/08205957.pdf)
- [2017 CVPR] Geometric loss functions for camera pose regression with deep learning [[paper]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Kendall_Geometric_Loss_Functions_CVPR_2017_paper.pdf)
- [2017 CVPR] Image-based localization using LSTMs for structured feature correlation [[paper]](https://openaccess.thecvf.com/content_ICCV_2017/papers/Walch_Image-Based_Localization_Using_ICCV_2017_paper.pdf)
- [2016 ICRA] Modelling Uncertainty in Deep Learning for Camera Relocalization [[paper]](https://arxiv.org/pdf/1509.05909.pdf)
- [2015 ICCV] PoseNet: A Convolutional Network for Real-Time 6-DOF Camera Relocalization [[paper]](https://openaccess.thecvf.com/content_iccv_2015/papers/Kendall_PoseNet_A_Convolutional_ICCV_2015_paper.pdf)




## Feature Matching

- [2024 ECCV] Grounding Image Matching in 3D with MASt3R [[paper]](https://arxiv.org/pdf/2406.09756) [[code]](https://github.com/naver/mast3r)
- [2024 CVPR] RoMa: Robust Dense Feature Matching [[paper]](https://arxiv.org/pdf/2305.15404) [[code]](https://github.com/Parskatt/RoMa)
- [2024 CVPR] Efficient LoFTR: Semi-Dense Local Feature Matching with Sparse-Like Speed [[paper]](https://arxiv.org/pdf/2403.04765) [[code]](https://github.com/zju3dv/EfficientLoFTR)
- [2024 CVPR] Matching 2D Images in 3D: Metric Relative Pose from Metric Correspondences [[paper]](https://arxiv.org/pdf/2404.06337) [[code]](https://github.com/nianticlabs/mickey) 
- [2024 CVPR] DeViLoc: Learning to Produce Semi-dense Correspondences for Visual Localization [[paper]](https://arxiv.org/pdf/2402.08359) [[code]](https://github.com/TruongKhang/DeViLoc)
- [2024 CVPR] DGC-GNN: Leveraging Geometry and Color Cues for Visual Descriptor-Free 2D-3D Matching [[paper]](https://arxiv.org/pdf/2306.12547) [[code]](https://github.com/AaltoVision/DGC-GNN-release)
- [2023 ICCV] LightGlue: Local Feature Matching at Light Speed [[paper]](https://arxiv.org/pdf/2306.13643) [[code]](https://github.com/cvg/LightGlue)
- [2023 ICCV] Guiding Local Feature Matching with Surface Curvature [[paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Wang_Guiding_Local_Feature_Matching_with_Surface_Curvature_ICCV_2023_paper.pdf) [[code]](https://github.com/AaltoVision/surface-curvature-estimator)
- [2022 ECCV] MeshLoc: Mesh-Based Visual Localization [[paper]](https://arxiv.org/abs/2207.10762) [[code]](https://github.com/tsattler/meshloc_release)
- [2022 CVPR] SceneSqueezer: Learning to Compress Scene for Camera Relocalization [[paper]](https://openaccess.thecvf.com/content/CVPR2022/html/Yang_SceneSqueezer_Learning_To_Compress_Scene_for_Camera_Relocalization_CVPR_2022_paper.html) 
- [2021 IJCV] Reference Pose Generation for Long-term Visual Localization via Learned Features and View Synthesis [[paper]](https://arxiv.org/pdf/2005.05179.pdf)
- [2021 ICCV Workshop] MegLoc: A Robust and Accurate Visual Localization Pipeline [[paper]](https://arxiv.org/pdf/2111.13063v1.pdf)
- [2021 ICCV Workshop] Pose Refinement with Joint Optimization of Visual Points and Lines [[paper]](https://arxiv.org/pdf/2110.03940.pdf)
- [2021 ICRA & ICCV Workshop] Retrieval and Localization with Observation Constraints [[paper]](https://arxiv.org/pdf/2108.08516.pdf)
- [2021 CVPR] Back to the Feature: Learning Robust Camera Localization from Pixels to Pose [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Sarlin_Back_to_the_Feature_Learning_Robust_Camera_Localization_From_Pixels_CVPR_2021_paper.pdf) [[code]](https://github.com/cvg/pixloc)
- [2021 CVPR] LoFTR: Detector-Free Local Feature Matching with Transformers [[paper]](https://arxiv.org/pdf/2104.00680) [[code]](https://github.com/zju3dv/LoFTR)
- [2020 3DV] Using Image Sequences for Long-Term Visual Localization [[paper]](https://ieeexplore.ieee.org/abstract/document/9320360)
- [2020 ECCV Workshop] Hierarchical Localization with hloc and SuperGlue [[slides]](https://psarlin.com/assets/talks/hloc+SuperGlue_15min_ltvl_slides.pdf) [[code]](https://github.com/cvg/Hierarchical-Localization)
- [2020 IROS] KR-Net: A Dependable Visual Kidnap Recovery Network for Indoor Spaces [[paper]](http://ras.papercept.net/images/temp/IROS/files/2098.pdf)
- [2020 ICRA] To Learn or Not to Learn: Visual Localization from Essential Matrices [[paper]](https://arxiv.org/pdf/1908.01293.pdf)
- [2020 arXiv] Robust Image Retrieval-based Visual Localization using Kapture [[paper]](https://arxiv.org/pdf/2007.13867.pdf) [[code]](https://github.com/naver/kapture-localization)
- [2019 CVPR] From Coarse to Fine: Robust Hierarchical Localization at Large Scale [[paper]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Sarlin_From_Coarse_to_Fine_Robust_Hierarchical_Localization_at_Large_Scale_CVPR_2019_paper.pdf) [[code]](https://github.com/ethz-asl/hfnet)
- [2019 CVPR] D2-Net: A Trainable CNN for Joint Description and Detection of Local Features [[paper]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Dusmanu_D2-Net_A_Trainable_CNN_for_Joint_Description_and_Detection_of_CVPR_2019_paper.pdf) [[code]](https://github.com/mihaidusmanu/d2-net)
- [2018 CoRL] Leveraging Deep Visual Descriptors for Hierarchical Efficient Localization [[paper]](https://arxiv.org/pdf/1809.01019.pdf) [[code]](https://github.com/ethz-asl/hierarchical_loc)
- [2018 CVPR] InLoc: Indoor Visual Localization with Dense Matching and View Synthesis [[paper]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Taira_InLoc_Indoor_Visual_CVPR_2018_paper.pdf) [[code]](https://github.com/HajimeTaira/InLoc_demo)
- [2017 ICCV] Efficient Global 2D-3D Matching for Camera Localization in a Large-Scale 3D Map [[paper]](https://openaccess.thecvf.com/content_ICCV_2017/papers/Liu_Efficient_Global_2D-3D_ICCV_2017_paper.pdf)
- [2017 CVPR] Are Large-Scale 3D Models Really Necessary for Accurate Visual Localization? [[paper]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Sattler_Are_Large-Scale_3D_CVPR_2017_paper.pdf)
- [2017 ICRA] [RA-L] Self-supervised Visual Descriptor Learning for Dense Correspondence [[paper]](https://homes.cs.washington.edu/~tws10/3163.pdf)
- [2016 TPAMI] Efficient & Effective Prioritized Matching for Large-Scale Image-Based Localization [[paper]](http://www.cvlibs.net/projects/autonomous_vision_survey/literature/Sattler2016PAMI.pdf)
- [2015 ICCV] Camera Pose Voting for Large-Scale Image-Based Localization [[paper]](https://openaccess.thecvf.com/content_iccv_2015/papers/Zeisl_Camera_Pose_Voting_ICCV_2015_paper.pdf)
- [2012 ECCV] Improving Image-Based Localization by Active Correspondence Search [[paper]](https://www.graphics.rwth-aachen.de/media/papers/sattler_eccv12_preprint_1.pdf) [[code]](https://www.graphics.rwth-aachen.de/software/image-localization/)
- [2012 CVPR] Real-time Image-based 6-DOF Localization in Large-Scale Environments [[paper]](https://snsinha.github.io/pdfs/LimCVPR2012.pdf)
- [2011 ICCV] Fast Image-Based Localization using Direct 2D-to-3D Matching [[paper]](https://www.graphics.rwth-aachen.de/media/papers/sattler_iccv11_preprint_011.pdf)




## Scene Coordinate Regression

- [2025 CVPR] R-SCoRe: Revisiting Scene Coordinate Regression for Robust Large-Scale Visual Localization [[paper]](https://arxiv.org/pdf/2501.01421) [[code]](https://github.com/cvg/scrstudio) 
- [2024 ECCV] Scene Coordinate Reconstruction: Posing of Image Collections via Incremental Learning of a Relocalizer [[paper]](https://arxiv.org/pdf/2404.14351) [[code]](https://github.com/nianticlabs/acezero)
- [2024 CVPR] DUSt3R: Geometric 3D Vision Made Easy [[paper]](https://arxiv.org/pdf/2312.14132v1) [[code]](https://github.com/naver/dust3r)
- [2024 CVPR] GLACE: Global Local Accelerated Coordinate Encoding [[paper]](https://arxiv.org/pdf/2406.04340) [[code]](https://github.com/cvg/glace)
- [2024 CVPR Workshop] SACReg: Scene-Agnostic Coordinate Regression for Visual Localization [[paper]](https://arxiv.org/pdf/2307.11702)
- [2024 IJCV] HSCNet++: Hierarchical Scene Coordinate Classification and Regression for Visual Localization with Transformer [[paper]](https://arxiv.org/pdf/2305.03595)
- [2023 CVPR] Accelerated Coordinate Encoding: Learning to Relocalize in Minutes using RGB and Poses [[paper]](https://arxiv.org/pdf/2305.14059) [[code]](https://nianticlabs.github.io/ace/)
- [2022 3DV] Visual Localization via Few-Shot Scene Region Classification [[paper]](https://arxiv.org/pdf/2208.06933.pdf) [[code]](https://github.com/siyandong/SRC)
- [2022 ECCV] Towards Accurate Active Camera Localization [[paper]](https://arxiv.org/abs/2012.04263) [[code]](https://github.com/qhFang/AccurateACL)
- [2022 CVPR] CrossLoc: Scalable Aerial Localization Assisted by Multimodal Synthetic Data [[paper]](https://arxiv.org/abs/2112.09081) [[code]](https://github.com/TOPO-EPFL/CrossLoc)
- [2021 ICCV] Continual Learning for Image-Based Camera Localization [[paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Wang_Continual_Learning_for_Image-Based_Camera_Localization_ICCV_2021_paper.pdf) [[code]](https://github.com/AaltoVision/CL_HSCNet)
- [2021 TPAMI] Visual Camera Re-Localization from RGB and RGB-D Images Using DSAC [[paper]](https://arxiv.org/pdf/2002.12324.pdf) [[code]](https://github.com/vislearn/dsacstar)
- [2021 CVPR] Robust Neural Routing Through Space Partitions for Camera Relocalization in Dynamic Indoor Environments [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Dong_Robust_Neural_Routing_Through_Space_Partitions_for_Camera_Relocalization_in_CVPR_2021_paper.pdf) [[code]](https://github.com/siyandong/NeuralRouting)
- [2021 CVPR] Learning Camera Localization via Dense Scene Matching [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Tang_Learning_Camera_Localization_via_Dense_Scene_Matching_CVPR_2021_paper.pdf) [[code]](https://github.com/Tangshitao/Dense-Scene-Matching)
- [2021 CVPR] VS-Net: Voting with Segmentation for Visual Localization [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Huang_VS-Net_Voting_With_Segmentation_for_Visual_Localization_CVPR_2021_paper.pdf) [[code]](https://github.com/zju3dv/VS-Net)
- [2020 CVPR] KFNet: Learning Temporal Camera Relocalization using Kalman Filtering [[paper]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Zhou_KFNet_Learning_Temporal_Camera_Relocalization_Using_Kalman_Filtering_CVPR_2020_paper.pdf) [[code]](https://github.com/zlthinker/KFNet)
- [2020 CVPR] Hierarchical Scene Coordinate Classification and Regression for Visual Localization [[paper]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Hierarchical_Scene_Coordinate_Classification_and_Regression_for_Visual_Localization_CVPR_2020_paper.pdf) [[code]](https://github.com/AaltoVision/hscnet)
- [2019 3DV] Let’s Take This Online: Adapting Scene Coordinate Regression Network Predictions for Online RGB-D Camera Relocalisation [[paper]](https://arxiv.org/pdf/1906.08744.pdf)
- [2019 TPAMI] Real-Time RGB-D Camera Pose Estimation in Novel Scenes using a Relocalisation Cascade [[paper]](https://arxiv.org/pdf/1810.12163.pdf) [[code]](https://github.com/torrvision/spaint)
- [2019 ICCV] SANet: Scene Agnostic Network for Camera Localization [[paper]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Yang_SANet_Scene_Agnostic_Network_for_Camera_Localization_ICCV_2019_paper.pdf) [[code]](https://github.com/sfu-gruvi-3dv/sanet_relocal_demo)
- [2019 ICCV] Expert Sample Consensus Applied to Camera Re-Localization [[paper]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Brachmann_Expert_Sample_Consensus_Applied_to_Camera_Re-Localization_ICCV_2019_paper.pdf) [[code]](https://github.com/vislearn/esac)
- [2018 IROS] Exploiting Points and Lines in Regression Forests for RGB-D Camera Relocalization [[paper]](https://arxiv.org/pdf/1710.10519.pdf)
- [2018 RSS] Full-Frame Scene Coordinate Regression for Image-Based Localization [[paper]](https://arxiv.org/pdf/1802.03237.pdf)
- [2018 CVPR] Learning Less is More – 6D Camera Localization via 3D Surface Regression [[paper]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Brachmann_Learning_Less_Is_CVPR_2018_paper.pdf) [[code]](https://github.com/vislearn/LessMore)
- [2017 IROS] Backtracking Regression Forests for Accurate Camera Relocalization [[paper]](https://arxiv.org/pdf/1710.07965.pdf)
- [2017 CVPR] DSAC - Differentiable RANSAC for Camera Localization [[paper]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Brachmann_DSAC_-_Differentiable_CVPR_2017_paper.pdf) [[code]](https://github.com/cvlab-dresden/DSAC)
- [2017 CVPR] On-the-Fly Adaptation of Regression Forests for Online Camera Relocalisation [[paper]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Cavallari_On-The-Fly_Adaptation_of_CVPR_2017_paper.pdf) [[code]](https://github.com/torrvision/spaint)
- [2017 ICRA] Random Forests versus Neural Networks − What’s Best for Camera Localization? [[paper]](https://arxiv.org/pdf/1609.05797.pdf)
- [2016 CVPR] Uncertainty-Driven 6D Pose Estimation of Objects and Scenes from a Single RGB Image [[paper]](https://openaccess.thecvf.com/content_cvpr_2016/papers/Brachmann_Uncertainty-Driven_6D_Pose_CVPR_2016_paper.pdf)
- [2015 CVPR] Exploiting Uncertainty in Regression Forests for Accurate Camera Relocalization [[paper]](https://openaccess.thecvf.com/content_cvpr_2015/papers/Valentin_Exploiting_Uncertainty_in_2015_CVPR_paper.pdf)
- [2014 CVPR] Multi-Output Learning for Camera Relocalization [[paper]](https://openaccess.thecvf.com/content_cvpr_2014/papers/Guzman-Rivera_Multi-Output_Learning_for_2014_CVPR_paper.pdf)
- [2013 CVPR] Scene Coordinate Regression Forests for Camera Relocalization in RGB-D Images [[paper]](https://openaccess.thecvf.com/content_cvpr_2013/papers/Shotton_Scene_Coordinate_Regression_2013_CVPR_paper.pdf)




## Camera Pose Optimization and Refinement

- [2025 ICLR] GS-CPR: Efficient Camera Pose Refinement via 3D Gaussian Splatting [[paper]](https://openreview.net/forum?id=mP7uV59iJM) [[code]](https://github.com/XRIM-Lab/GS-CPR)
- [2024 ECCV] Robust Incremental Structure-from-Motion with Hybrid Features [[paper]](https://arxiv.org/pdf/2409.19811)
- [2024 ECCV] Global Structure-from-Motion Revisited [[paper]](https://arxiv.org/pdf/2407.20219) [[code]](https://github.com/colmap/glomap)
- [2024 ECCV] Gravity-aligned Rotation Averaging with Circular Regression [[paper]](https://arxiv.org/pdf/2410.12763) [[code]](https://github.com/colmap/glomap) 
- [2024 ECCV] StereoGlue: Robust Estimation with Single-Point Solvers [[paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/07485.pdf) [[code]](https://github.com/danini/stereoglue)
- [2024 CVPR] Absolute Pose from One or Two Scaled and Oriented Features [[paper]](https://openaccess.thecvf.com/content/CVPR2024/papers/Ventura_Absolute_Pose_from_One_or_Two_Scaled_and_Oriented_Features_CVPR_2024_paper.pdf) [[code]](https://github.com/danini/absolute-pose-from-oriented-and-scaled-features)
- [2024 CVPR] Neural Refinement for Absolute Pose Regression with Feature Synthesis [[paper]](https://arxiv.org/pdf/2303.10087) [[code]](https://github.com/ActiveVisionLab/NeFeS)
- [2024 ICRA] HR-APR: APR-agnostic Framework with Uncertainty Estimation and Hierarchical Refinement for Camera Relocalisation [[paper]](https://arxiv.org/pdf/2402.14371) [[code]](https://github.com/lck666666/HR-APR)
- [2024 3DV] Self-Supervised Learning of Neural Implicit Feature Fields for Camera Pose Refinement [[paper]](https://arxiv.org/pdf/2406.08463)
- [2023 arXiv] Lazy Visual Localization via Motion Averaging [[paper]](https://arxiv.org/pdf/2307.09981)
- [PoseLib](https://github.com/PoseLib/PoseLib)
- [RansacLib](https://github.com/tsattler/RansacLib)
- [2016 CVPR] Structure-from-Motion Revisited [[paper]](https://openaccess.thecvf.com/content_cvpr_2016/papers/Schonberger_Structure-From-Motion_Revisited_CVPR_2016_paper.pdf) [[code]](https://github.com/colmap/colmap)




## Datasets and Benchmarks


### In/Outdoor
- [2022 ECCV] [LaMAR](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136670677.pdf) [[page]](https://lamar.ethz.ch/)
- [2021 ICCV Workshop] [ETH-Microsoft](https://github.com/cvg/visloc-iccv2021)


### Indoor
- [2022 CVPR] [Indoor-6](https://github.com/microsoft/SceneLandmarkLocalization) [[paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Do_Learning_To_Detect_Scene_Landmarks_for_Camera_Localization_CVPR_2022_paper.pdf)
- [2022 ECCV] [ACL](https://github.com/qhFang/AccurateACL) [[paper]](https://arxiv.org/abs/2012.04263)
- [2021 ICCV] [SfM pGT for 7-Scenes and 12-Scenes](https://github.com/tsattler/visloc_pseudo_gt_limitations/) [[paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Brachmann_On_the_Limits_of_Pseudo_Ground_Truth_in_Visual_Camera_ICCV_2021_paper.pdf)
- [2021 CVPR] [NAVERLABS](https://naverlabs.com/datasets) [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Lee_Large-Scale_Localization_Datasets_in_Crowded_Indoor_Spaces_CVPR_2021_paper.pdf)
- [2020 ECCV] [RIO10](http://vmnavab26.in.tum.de/RIO10/) [[paper]](https://arxiv.org/pdf/2008.02004.pdf)
- [2018 CVPR] [InLoc](http://www.ok.sc.e.titech.ac.jp/INLOC/) [[paper]](https://arxiv.org/pdf/1803.10368.pdf)
- [2016 3DV] [4-Scenes(12-Scenes)](https://graphics.stanford.edu/projects/reloc/) [[paper]](https://arxiv.org/pdf/1603.05772v1.pdf)
- [2013 CVPR] [7-Scenes](https://www.microsoft.com/en-us/research/project/rgb-d-dataset-7-scenes/) [[paper]](https://openaccess.thecvf.com/content_cvpr_2013/papers/Shotton_Scene_Coordinate_Regression_2013_CVPR_paper.pdf)


### Outdoor
- [2022 ECCV] [Map-free Visual Relocalization](https://arxiv.org/pdf/2210.05494.pdf). [[page]](https://research.nianticlabs.com/mapfree-reloc-benchmark)
- [2022 CVPR] [CrossLoc](https://github.com/TOPO-EPFL/CrossLoc-Benchmark-Datasets) [[paper]](https://arxiv.org/abs/2112.09081)
- [2021 ICCV] [CrowdDriven](https://www.mapillary.com) [[paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Jafarzadeh_CrowdDriven_A_New_Challenging_Dataset_for_Outdoor_Visual_Localization_ICCV_2021_paper.pdf)
- [2020 ECCV Workshop] [Symphony Seasons](https://dream.georgiatech-metz.fr/datasets/symphony-lake-dataset-visual-benchmark/)
- [2019 CVPR Workshop] [SILDa](https://sites.google.com/view/ltvl2019/home)
- [2018 CVPR] [Aachen Day-Night, RobotCar Seasons, CMU Seasons](https://www.visuallocalization.net/datasets/) [[paper]](https://openaccess.thecvf.com/content_cvpr_2018/papers/Sattler_Benchmarking_6DOF_Outdoor_CVPR_2018_paper.pdf)
- [2015 ICCV] [Cambridge](https://www.repository.cam.ac.uk/handle/1810/251342;jsessionid=723149435103CA63B4C0BF868374A589) [[paper]](https://openaccess.thecvf.com/content_iccv_2015/papers/Kendall_PoseNet_A_Convolutional_ICCV_2015_paper.pdf)


### Challenges
- [2021 ICCV] [Long-Term Visual Localization under Changing Conditions](https://sites.google.com/view/ltvl2021/home)
- [2021 ICCV] [Map-Based Localization for Autonomous Driving](https://sites.google.com/view/mlad-iccv2021)
- [2020 ECCV] [Long-Term Visual Localization under Changing Conditions](https://www.visuallocalization.net/workshop/eccv/2020/)
- [2020 ECCV] [Map-Based Localization for Autonomous Driving](https://sites.google.com/view/mlad-eccv2020/home)
- [2019 CVPR] [Long-Term Visual Localization under Changing Conditions](https://sites.google.com/view/ltvl2019/home)


### Tools
- [kapture](https://github.com/naver/kapture)
- [TOPO-DataGen](https://github.com/TOPO-EPFL/TOPO-DataGen)

