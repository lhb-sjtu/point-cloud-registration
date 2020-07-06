### Point Cloud Registration: Papers and Codes

The partial-view point cloud will be aligned to the complete shape in order to obtain the 6D pose. Generally, coarse registration should be conduct firstly to provide an intial alignment, and dense registration methods like ICP (Iterative Closest Point) will be conducted to obtain the final 6D pose.

#### 1 Correspondence-based Methods

***2020:***

**[PRL]** Fuzzy Logic and Histogram of Normal Orientation-based 3D Keypoint Detection for Point Clouds, [[paper](https://www.sciencedirect.com/science/article/abs/pii/S016786552030180X)]

**[arXiv]** Latent Fingerprint Registration via Matching Densely Sampled Points, [[paper](https://arxiv.org/pdf/2005.05878.pdf)]

**[arXiv]** RPM-Net: Robust Point Matching using Learned Features, [[paper](https://arxiv.org/pdf/2003.13479.pdf)]

**[arXiv]** End-to-End Learning Local Multi-view Descriptors for 3D Point Clouds, [[paper](https://arxiv.org/pdf/2003.05855.pdf)]

**[arXiv]** D3Feat: Joint Learning of Dense Detection and Description of 3D Local Features, [[paper](https://arxiv.org/pdf/2003.03164.pdf)]

**[arXiv]** Self-supervised Point Set Local Descriptors for Point Cloud Registration, [[paper](https://arxiv.org/pdf/2003.05199.pdf)]

**[arXiv]** StickyPillars: Robust feature matching on point clouds using Graph Neural Networks, [[paper](https://arxiv.org/pdf/2002.03983.pdf)]

***2019:***

**[arXiv]** 3DRegNet: A Deep Neural Network for 3D Point Registration, [[paper](https://arxiv.org/abs/1904.01701)] [[code](https://github.com/goncalo120/3DRegNet)]

**[CVPR]** The Perfect Match: 3D Point Cloud Matching with Smoothed Densities, [[paper](http://openaccess.thecvf.com/content_CVPR_2019/papers/Gojcic_The_Perfect_Match_3D_Point_Cloud_Matching_With_Smoothed_Densities_CVPR_2019_paper.pdf)]

**[arXiv]** LCD: Learned Cross-Domain Descriptors for 2D-3D Matching, [[paper](https://arxiv.org/pdf/1911.09326.pdf)]

***2018:***

**[arXiv]** Dense Object Nets: Learning Dense Visual Object Descriptors By and For Robotic Manipulation, [[paper](https://arxiv.org/abs/1806.08756)]

**[ECCV]** 3DFeat-Net: Weakly Supervised Local 3D Features for Point Cloud Registration, [[paper](https://arxiv.org/abs/1807.09413)] [[code](https://github.com/yewzijian/3DFeatNet)]

***2017:***

**[CVPR]** 3DMatch: Learning Local Geometric Descriptors from RGB-D Reconstructions, [[paper](https://arxiv.org/abs/1603.08182)] [[code](https://github.com/andyzeng/3dmatch-toolbox)]

***2016:***

**[arXiv]** Lessons from the Amazon Picking Challenge, [[paper](https://arxiv.org/abs/1601.05484v2)]

**[arXiv]** Team Delft's Robot Winner of the Amazon Picking Challenge 2016, [[paper](https://arxiv.org/abs/1610.05514)]

**[IJCV]** A comprehensive performance evaluation of 3D local feature descriptors, [[paper](https://link.springer.com/article/10.1007/s11263-015-0824-y)]

***2014:***

**[CVIU]** SHOT: Unique signatures of histograms for surface and texture description, [[paper](https://www.sciencedirect.com/science/article/pii/S1077314214000988))]

***2011:***

**[ICCVW]** CAD-model recognition and 6DOF pose estimation using 3D cues, [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6130296)]

***2009:***

**[ICRA]** Fast Point Feature Histograms (FPFH) for 3D registration, [[paper](https://www.cvl.iis.u-tokyo.ac.jp/class2016/2016w/papers/6.3DdataProcessing/Rusu_FPFH_ICRA2009.pdf)]



#### 2 Template-based Methods

***Survey papers:***

***2020:***

**[arXiv]** When Deep Learning Meets Data Alignment: A Review on Deep Registration Networks (DRNs), [[paper](https://arxiv.org/pdf/2003.03167.pdf)]

**[arXiv]** Least Squares Optimization: from Theory to Practice, [[paper](https://arxiv.org/pdf/2002.11051.pdf)]



***2020:***

**[arXiv]** An Analysis of SVD for Deep Rotation Estimation, [[paper](https://arxiv.org/pdf/2006.14616.pdf)]

**[arXiv]** Applying Lie Groups Approaches for Rigid Registration of Point Clouds, [[paper](https://arxiv.org/pdf/2006.13341.pdf)]

**[arXiv]** Unsupervised Learning of 3D Point Set Registration, [[paper](https://arxiv.org/pdf/2006.06200.pdf)]

**[arXiv]** Minimum Potential Energy of Point Cloud for Robust Global Registration, [[paper](https://arxiv.org/pdf/2006.06460.pdf)]

**[arXiv]** Learning 3D-3D Correspondences for One-shot Partial-to-partial Registration, [[paper](https://arxiv.org/pdf/2006.04523.pdf)]

**[arXiv]** A Dynamical Perspective on Point Cloud Registration, [[paper](https://arxiv.org/pdf/2005.03190.pdf)]

**[arXiv]** Feature-metric Registration: A Fast Semi-supervised Approach for Robust Point Cloud Registration without Correspondences, [[paper](https://arxiv.org/pdf/2005.01014.pdf)]

**[CVPR]** Deep Global Registration, [[paper](https://arxiv.org/pdf/2004.11540.pdf)]

**[arXiv]** DPDist : Comparing Point Clouds Using Deep Point Cloud Distance, [[paper](https://arxiv.org/pdf/2004.11784.pdf)]

**[arXiv]** Single Shot 6D Object Pose Estimation, [[paper](https://arxiv.org/pdf/2004.12729.pdf)]

**[arXiv]** A Benchmark for Point Clouds Registration Algorithms, [[paper](https://arxiv.org/pdf/2003.12841.pdf)] [[code](https://github.com/iralabdisco/point_clouds_registration_benchmark)]

**[arXiv]** PointGMM: a Neural GMM Network for Point Clouds, [[paper](https://arxiv.org/pdf/2003.13326.pdf)]

**[arXiv]** SceneCAD: Predicting Object Alignments and Layouts in RGB-D Scans, [[paper](https://arxiv.org/pdf/2003.12622.pdf)]

**[arXiv]** TEASER: Fast and Certifiable Point Cloud Registration, [[paper](https://arxiv.org/pdf/2001.07715.pdf)] [[code](https://github.com/MIT-SPARK/TEASER-plusplus)]

**[arXiv]** Plane Pair Matching for Efficient 3D View Registration, [[paper](https://arxiv.org/pdf/2001.07058.pdf)]

**[arXiv]** Learning multiview 3D point cloud registration, [[paper](https://arxiv.org/pdf/2001.05119.pdf)]

**[arXiv]** Robust, Occlusion-aware Pose Estimation for Objects Grasped by Adaptive Hands, [[paper](https://arxiv.org/pdf/2003.03518.pdf)]

**[arXiv]** Non-iterative One-step Solution for Point Set Registration Problem on Pose Estimation without Correspondence, [[paper](https://arxiv.org/pdf/2003.00457.pdf)]

**[arXiv]** 6D Object Pose Regression via Supervised Learning on Point Clouds, [[paper](https://arxiv.org/pdf/2001.08942.pdf)]

***2019:***

**[arXiv]** One Framework to Register Them All: PointNet Encoding for Point Cloud Alignment, [[paper](https://arxiv.org/abs/1912.05766)]

**[arXiv]** DeepICP: An End-to-End Deep Neural Network for 3D Point Cloud Registration, [[paper](https://arxiv.org/pdf/1905.04153v2.pdf)]

**[NeurIPS]** PRNet: Self-Supervised Learning for Partial-to-Partial Registration, [[paper](https://arxiv.org/abs/1910.12240)]

**[CVPR]** PointNetLK: Robust & Efficient Point Cloud Registration using PointNet, [[paper](https://arxiv.org/abs/1903.05711)] [[code](https://github.com/hmgoforth/PointNetLK)]

**[ICCV]** End-to-End CAD Model Retrieval and 9DoF Alignment in 3D Scans, [[paper](http://openaccess.thecvf.com/content_ICCV_2019/papers/Avetisyan_End-to-End_CAD_Model_Retrieval_and_9DoF_Alignment_in_3D_Scans_ICCV_2019_paper.pdf)]

**[arXiv]** Iterative Matching Point, [[paper](https://arxiv.org/abs/1910.10328)]

**[arXiv]** Deep Closest Point: Learning Representations for Point Cloud Registration, [[paper](https://arxiv.org/abs/1905.03304)] [[code](https://github.com/WangYueFt/dcp)]

**[arXiv]** PCRNet: Point Cloud Registration Network using PointNet Encoding, [[paper](https://arxiv.org/abs/1908.07906)] [[code](https://github.com/vinits5/pcrnet)]

***2016:***

**[TPAMI]** Go-ICP: A Globally Optimal Solution to 3D ICP Point-Set Registration, [[paper](https://arxiv.org/pdf/1605.03344.pdf)] [[code](https://github.com/yangjiaolong/Go-ICP)]

***2014:***

**[SGP]** Super 4PCS Fast Global Pointcloud Registration via Smart Indexing, [[paper](https://geometry.cs.ucl.ac.uk/projects/2014/super4PCS/super4pcs.pdf)] [[code](https://github.com/nmellado/Super4PCS)]



#### 3 Voting-based Methods

***2020:***

**[arXiv]** MoreFusion: Multi-object Reasoning for 6D Pose Estimation from Volumetric Fusion, [[paper](https://arxiv.org/pdf/2004.04336.pdf)] [[code](https://github.com/wkentaro/morefusion)]

**[arXiv]** YOLOff: You Only Learn Offsets for robust 6DoF object pose estimation, [[paper](https://arxiv.org/pdf/2002.00911.pdf)]

**[arXiv]** LRF-Net: Learning Local Reference Frames for 3D Local Shape Description and Matching, [[paper](https://arxiv.org/pdf/2001.07832.pdf)]

***2019:***

**[arXiv]** PVN3D: A Deep Point-wise 3D Keypoints Voting Network for 6DoF Pose Estimation, [[paper](https://arxiv.org/abs/1911.04231)] [[code]()]

**[CVPR]** Densefusion: 6d object pose estimation by iterative dense fusion, [[paper](https://arxiv.org/abs/1901.04780)] [[code](https://github.com/j96w/DenseFusion)]

