## 计算机视觉实验室 * 水下三维视觉课题组
**页面导航：** <a href="/index.html">课题组简介</a> | <a href="/research.html">研究内容</a> | <a href="/project.html">研究项目</a>
## 1. 基础方法研究
### 1.1 光度立体 （将光度信息融入到移动三维重建中）
**目标产物：（1）手持单光源三维成像设备；（2）水下ROV移动多光源三维成像设备**
- 近距离光度立体 <a href='#SPIC2022-1'>[SPIC2022-1]</a> <a href='#Opt-Eng2017-2'>[Opt-Eng2017-2]</a>
- 单光源移动光度立体 <a href='#IECON2018-1'>[IECON2018-1]</a>
- 晃动光度立体（移动状态下的光度立体）<a href='#IWAIT2022-1'>[IWAIT2022-1]</a>
- 多视角光度立体（多视角点云拼接）

### 1.2 双目立体视觉（服务于视觉定位与重建）
**目标产物：（1）视觉引导解决方案；（2）定位与避障关键技术**
- 鲁棒的特征描述子提取方法研究 <a href='#TIM2022-1'>[TIM2022-1]</a> <a href='#TIM2023-2'>[TIM2023-2]</a> <a href='#TCSVT023-1'>[TCSVT2023-1]</a>
- 误匹配剔除算法研究 <a href='#iCAST2020-3'>[iCAST2020-3]</a> 
- 双目稠密匹配方法研究 <a href='#ICIVC2022-1'>[ICIVC2022-1]</a> <a href='JMSE2023-1'>[JMSE2023-1]</a> 
- 多视角稠密匹配方法研究 <a href='#TIM2023-3'>[TIM2023-3]</a>

### 1.3 运动恢复结构方法（视觉高精度移动定位）
**目标产物：（1）移动定位系统；（2）稀疏全景三维建模** 
- 基于Marker定位的SfM <a href='#TIM2023-1'>[TIM2023-1]</a>

### 1.4 视觉SLAM、VIO（多传感器融合的高精度移动定位）
- 视觉SLAM基础研究 <a href='#ICDIS2022-3'>[ICDIS2022-3]</a>
- 线激光视觉SLAM <a href='#iCAST2020-1'>[iCAST2020-1]</a> <a href='#TEM2019-1'>[TEM2019-1]</a>
- 小场景的实时稠密三维重建
- 点线面特征融合SLAM

### 1.5 三维点云分析
- 基于三维点云的目标识别与定位
- 基于三维点云的缺陷检测
 
## 2. 应用研究
### 2.1 水下视觉
**目标产物：水下光学三维成像系统**
- 水下相机折射标定 <a href='#Opt-Eng2022-1'>[Opt-Eng2022-1]</a>
- 水下单目激光三角法 <a href='#Opt-Eng2017-1'>[Opt-Eng2017-1]</a>
- 水下双目立体视觉 <a href='#TIM2022-2'>[TIM2022-2]</a> 
- 水下光度立体 <a href='#JOE2021-1'>[JOE2021-1]</a>
- 水下重光照  <a href='#ICDIS2022-1'>[ICDIS2022-1]</a> 
- 水下SfM/SLAM

### 2.2 结构光三维重建
**目标产物：（1）线激光旋转扫描仪；（2）双目结构光稠密三维重建系统**
- 单目线结构光旋转扫描 <a href='#iCAST2020-2'>[iCAST2020-2]</a>
- 双目格雷码结构光三维重建 <a href='#TIM2022-2'>[TIM2022-2]</a>

### 2.3 结构化场景测量（平面场景下的点线面特征的综合利用）
- 单目 消防水柱喷射高度测量
- 单目 行人身高测量、骨架动态测量

### 2.4 视觉引导

[↑Top](#Top)

## 发表论文 
\# 学生一作，\* 通讯作者

**2023年**
* Jiaqi Leng#, Qingxuan Lv, Shu Zhang, Yuan Rao, Yimei Liu, Hao Fan\*. "Multilevel Inverse Patchmatch Network with Local and Global Refinement for Underwater Stereo Matching[J]", Journal of Marine Science and Engineering, 2023. <a name='JMSE2023-1'>[JMSE2023-1]</a> <a href="https://www.mdpi.com/2077-1312/11/5/930">链接</a> 
* Yuan Rao#, Yakun Ju, Cong Li, Eric Rigall, Jian Yang, Hao Fan\*, Junyu Dong\*. "Learning General Descriptors for Image Matching with Regression Feedback[J]",  IEEE Transactions on Circuits and Systems for Video Technology, 2023. <a name='TCSVT2023-1'>[TCSVT2023-1]</a> <a href="https://ieeexplore.ieee.org/document/10102528">链接</a> 
* Yimei Liu#, Yuan Rao, Eric Rigall, Hao Fan, Junyu Dong\*. "Incorporating Co-Visibility Reasoning Into Surface Depth Measurement[J]", IEEE Transactions on Instrumentation and Measurement, 2023. <a name='TIM2023-3'>[TIM2023-3]</a> <a href="https://ieeexplore.ieee.org/document/10081062">链接</a> 
* Yuan Rao#, Yakun Ju, Sen Wang, Hao Fan, Junyu Dong\*. "Learning Enriched Feature Descriptor for Image Matching and Visual Measurement[J]", IEEE Transactions on Instrumentation and Measurement, 2023. <a name='TIM2023-2'>[TIM2023-2]</a> <a href="https://ieeexplore.ieee.org/document/10058693">链接</a> 
* Zhenlin Jia#, Yuan Rao#, Hao Fan\*, Junyu Dong\*. "An Efficient Visual SfM Framework Using Planar Markers[J]", IEEE Transactions on Instrumentation and Measurement, 2023. <a name='TIM2023-1'>[TIM2023-1]</a> <a href="https://ieeexplore.ieee.org/document/10041830/authors">链接</a> 

**2022年**
* Yeqi Hu#, Wei Rao#, Lin Qi, Junyu Dong, Jinzhen Cai\*, Hao Fan\*. "A Refractive Stereo Structured-Light 3D Measurement System for Immersed Object[J]", IEEE Transactions on Instrumentation and Measurement, 2022. <a name='TIM2022-2'>[TIM2022-2]</a> <a href="https://ieeexplore.ieee.org/abstract/document/9996430">链接</a> 
* Guanqi Qi#, Zhengwu Shi, Yeqi Hu, Hao Fan\*, Junyu Dong. "Refraction calibration of housing parameters for a flat-port underwater camera[J]", Optical Engineering, Vol. 61, Issue 10, 104105 (October 2022). <a name='Opt-Eng2022-1'>[Opt-Eng2022-1]</a> <a href="https://doi.org/10.1117/1.OE.61.10.104105">链接</a>
* Cong Li#, Yuan Rao, Jian Yang, Kai Yang, Hao Fan\*, Junyu Dong\*. "Calibrated Relighting Network for Image Light Transfer[C]". 2022 4th International Conference on Data Intelligence and Security (ICDIS), Shenzhen, China, 2022, pp. 267-274. <a name='ICDIS2022-1'>[ICDIS2022-1]</a> <a href="https://ieeexplore.ieee.org/abstract/document/9984852">链接</a>
* Kai Yang#, Yumeng Jiang, Lin Qi, Hao Fan, Shu Zhang\*, Junyu Dong. "Visual Semantic SLAM Based on Examination of Moving Consistency in Dynamic Scenes[C]". <a name='ICDIS2022-2'>[ICDIS2022-2]</a> <a href="https://ieeexplore.ieee.org/abstract/document/9984881">链接</a>
* Yifan Liu#, Yuan Rao, Guanqi Qi, Hao Fan\*, Junyu Dong\*. "Robust Initialization for Stereo Visual-Inertial SLAM with Polar-Based Gravity Estimation[C]". 2022 4th International Conference on Data Intelligence and Security (ICDIS), Shenzhen, China, 2022, pp. 402-407. <a name='ICDIS2022-3'>[ICDIS2022-3]</a> <a href="https://ieeexplore.ieee.org/abstract/document/9984882">链接</a>
* Zhijie Xie#, Yuan Rao, Yeqi Hu, Hao Fan\*, Lin Qi\*, Junyu Dong. "Cascaded Feature Interaction Network for Stereo Matching[C]". 2022 7th International Conference on Image, Vision and Computing (ICIVC), Xi’an, China, 2022, pp. 312-318. <a name='ICIVC2022-1'>[ICIVC2022-1]</a> <a href="https://ieeexplore.ieee.org/abstract/document/9886692">链接</a>
* Changhao Chen#, Zhenlin Jia, Hao Fan\*, and Junyu Dong. "Dynamic photometric stereo for flat bas-relief surfaces[C]", Proc. SPIE 12177, International Workshop on Advanced Imaging Technology (IWAIT) 2022, 121771P (30 April 2022). <a name='IWAIT2022-1'>[IWAIT2022-1]</a> <a href="https://doi.org/10.1117/12.2624226">链接</a> 
* Yuan Rao#, Jian Yang, Yakun Ju, Cong Li, Eric Rigall, Hao Fan\*, Junyu Dong\*. Learning General Feature Descriptor for Visual Measurement with Hierarchical View Consistency[J]. IEEE Transactions on Instrumentation and Measurement, 2022. <a name='TIM2022-1'>[TIM2022-1]</a> <a href="https://ieeexplore.ieee.org/document/9761834/authors">链接</a> 
* Hao Fan, Yuan Rao#, Eric Rigall, Lin Qi, Zhile Wang, Junyu Dong*. Near-field photometric stereo using a ring-light imaging device[J]. Signal Processing: Image Communication, 2022, 102: 116605.  <a name='SPIC2022-1'>[SPIC2022-1]</a> <a href="https://www.sciencedirect.com/science/article/pii/S0923596521003039">链接</a>

**2021年**
* Hao Fan, Lin Qi, Changhao Chen, Yuan Rao, Linghui Kong, Junyu Dong*, Hui Yu. Underwater Optical 3-D Reconstruction of Photometric Stereo Considering Light Refraction and Attenuation[J]. IEEE Journal of Oceanic Engineering, 2021. <a name='JOE2021-1'>[JOE2021-1]</a> <a href="https://ieeexplore.ieee.org/abstract/document/9491044">链接</a>

**2020年**
* Zhengwu Shi#, Qingxuan Lv, Shu Zhang, Lin Qi, Hao Fan*, Junyu Dong. A Visual-SLAM based Line Laser Scanning System using Semantically Segmented Images[C]. 2020 11th International Conference on Awareness Science and Technology (iCAST). IEEE, 2020. <a name='iCAST2020-1'>[iCAST2020-1]</a> <a href="https://ieeexplore.ieee.org/abstract/document/9319479/authors#authors">链接</a>
* Chenxin Jia#, Ying Cao, Jian Yang, Yuan Rao, Hao Fan*, Wenlin Yao. Improving Visual-Inertial Odometry with Robust Outlier Rejection and Loop Closure[C]. 2020 11th International Conference on Awareness Science and Technology (iCAST). IEEE, 2020. <a name='iCAST2020-2'>[iCAST2020-2]</a> <a href="https://ieeexplore.ieee.org/abstract/document/9319474/authors#authors">链接</a>
* Zhihao Zhu#, Jian Yang, Xianglong Wang, Guanqi Qi, Chuang Wu, Hao Fan*, Lin Qi, Junyu Dong. Rotation Axis Calibration of Laser Line Rotating-Scan System for 3D Reconstruction[C]//2020 11th International Conference on Awareness Science and Technology (iCAST). IEEE, 2020. <a name='iCAST2020-3'>[iCAST2020-3]</a> <a href="https://ieeexplore.ieee.org/abstract/document/9319495/authors#authors">链接</a>

**2019年之前**
* Jie Gao#, Hao Fan, Junyu Dong*, Shu Zhang, Lin Qi, Hui Yu. SLAM-based laser scanning for 3D reconstruction[J]. Test Engineering and Management, 2019, 81(11-12): 949-955. <a name='TEM2019-1'>[TEM2019-1]</a>
* Hao Fan#, Lin Qi, Junyu Dong, Gongfa Li, Hui Yu*. Dynamic 3d surface reconstruction using a hand-held camera[C]. IECON 2018-44th Annual Conference of the IEEE Industrial Electronics Society. IEEE, 2018: 3244-3249. <a name='IECON2018-1'>[IECON2018-1]</a> <a href="https://ieeexplore.ieee.org/abstract/document/8592826/authors#authors">链接</a>
* Hao Fan#, Lin Qi, Yakun Ju, Junyu Dong*, Hui Yu. Refractive laser triangulation and photometric stereo in underwater environment[J]. Optical Engineering, 2017, 56(11): 113101. <a name='Opt-Eng2017-1'>[Opt-Eng2017-1]</a> <a href="https://www.spiedigitallibrary.org/journals/Optical-Engineering/volume-56/issue-11/113101/Refractive-laser-triangulation-and-photometric-stereo-in-underwater-environment/10.1117/1.OE.56.11.113101.short?SSO=1">链接</a>
* Hao Fan#, Lin Qi, Nan Wang, Junyu Dong*, Yijun Chen, Hui Yu. Deviation correction method for close-range photometric stereo with nonuniform illumination[J]. Optical Engineering, 2017, 56(10): 103102. <a name='Opt-Eng2017-2'>[Opt-Eng2017-2]</a> <a href="https://www.spiedigitallibrary.org/journals/Optical-Engineering/volume-56/issue-10/103102/Deviation-correction-method-for-close-range-photometric-stereo-with-nonuniform/10.1117/1.OE.56.10.103102.short">链接</a>

[↑Top](#Top)
