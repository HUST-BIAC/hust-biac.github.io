---
layout: pageWithLeftNav
pageType: 3
title: 科学研究
subtitle: 研究方向
cover-img: /assets/img/title.jpg
---
<!--
 * @Author: Conghao Wong
 * @Date: 2023-03-08 19:13:03
 * @LastEditors: Conghao Wong
 * @LastEditTime: 2023-04-27 15:06:02
 * @Description: file content
 * @Github: https://cocoon2wong.github.io
 * Copyright 2023 Conghao Wong, All Rights Reserved.
-->

<link rel="stylesheet" type="text/css" href="/assets/css/user.css">

## 研究方向

<div class="t_grid_back">
    <div>
        <h3>人工智能与机器视觉</h3>
    </div>
    <div style="text-align: right;">
        <a class="btn btn-info btn-lg get-started-btn btn_dark" href="/researchs/researchs_index">返回研究方向首页</a>
    </div>
</div>

---

- 人工智能与机器视觉理论与算法；
- 基于人工智能的防伪；
- 鉴伪理论与技术；
- 自然语言处理；
- 机器人算法与系统。

#### 基于人工智能及智能物联相关的防伪、鉴伪理论与技术

---

提出了基于人工智能的多模态、多视角鉴伪算法。

<div style="text-align: center;">
    <img style="height: 250px;" src="/assets/img/researchs/1/image001.png">
</div> 


#### 多模态、多视角、多光谱理论研究

---

跨模态表征旨在利用不同模态数据之间的互补性，剔除模态之间的冗余，从而获得更为有效的特征表示，提高训练模型的准确性和鲁棒性。本实验室围绕多模态数据的异构特性展开研究并取得显著理论成果，并针对跨模态检索、多模态或多视角学习等内容开发鲁棒算法，成果应用于视频监控、推荐系统等领域。

<div style="text-align: center;">
    <img style="width: 60%;" src="/assets/img/researchs/1/M-1.jpg">
    <img style="width: 60%;" src="/assets/img/researchs/1/M-2.jpg">
</div> 

部分代表性论文：

- Hyperspectral Image Classification via Spatial Window-Based Multiview Intact Feature Learning.  IEEE Trans.  Geosci.  Remote.  Sens. 59(3): 2294-2306 (2021)
- Modal-Regression-Based Structured Low-Rank Matrix Recovery for Multiview Learning.  IEEE Trans.  Neural Networks Learn.  Syst. 32(3): 1204-1216 (2021)
- Multiview Hybrid Embedding: A Divide-and-Conquer Approach.  IEEE Trans.  Cybernetics. 50(8): 3640-3653 (2020)
- Multi-view Common Component Discriminant Analysis for Cross-view Classification. Pattern Recognition , 92:37-51, 2019. 
- Multi-view manifold learning with locality alignment. Pattern Recognition 78:154-166, 2018.
- ...
#### 图像细粒度分析与识别

---

细粒度图像具有相似的外观，围绕特征差异较小，局部判别区域定位困难，判别依据难以量化的问题，提出基于弱监督端到端学习的超球体特征编码算法，完成同一大类别下视觉差异极小的细粒度子类别识别，实现目标的精细化分类。相关研究可应用于军事目标检测、海关边检、农林农业、无人零售等领域。

<div style="text-align: center;">
    <img style="width: 100%;" src="/assets/img/researchs/1/FGVC-1.jpg">
    <img style="width: 50%;" src="/assets/img/researchs/1/FGVC-2.gif">
</div> 

在该领域的研究中，中心已发表A类论文10余篇，专利2项，相关成果在机器人等工程领域得到了实际应用。

#### 零样本学习

---

零样本学习旨在通过属性的语义辅助信息的指导下，实现从已知类到未知类的知识迁移，从而识别未知类样本。相关研究被应用于自动驾驶新场景感知、机器人导航、光学字符识别等实际场景。我们针对零样本学习中的跨数据集偏差、视觉-语义特征的异构性、视觉-语义特征的语义表示差异性等问题，分别提出基于特征增强、层次适应、关键公共语义知识挖掘的零样本学习系统方法，相关成果发表于TPAMI/TNNLS/NeurIPS/CVPR/ICCV/AAAI/IJCAI等国际权威期刊和会议。


<div style="text-align: center;">
    <img style="width: 60%;" src="/assets/img/researchs/1/z-1.png">
    <p></p>
    <img style="width: 60%;" src="/assets/img/researchs/1/z-2.png">
     <p></p>
    <img style="width: 60%;" src="/assets/img/researchs/1/z-3.png">
</div> 

相关研究已发表A类论文20余篇，专利1项，并得到AI Time等专业AI媒体报道与广泛传播。

部分代表性论文：

- TransZero++: Cross Attribute-Guided Transformer for Zero- Shot Learning. TPAMI, 2022.
- HSVA: Hierarchical Semantic-Visual Adaptation for Zero-Shot Learning. NeurIPS, 2021.
- MSDN: Mutually Semantic Distillation Network for Zero- Shot Learning. CVPR, 2022.
- FREE: Feature Refinement for Generalized Zero-shot Learning. ICCV, 2021
- GNDAN: Graph Navigated Dual Attention Network for Zero-Shot Learning. TNNLS, 2022.
- ...

#### 多智能体轨迹预测

---

多智能体轨迹预测通过智能体在一段时间内的观测轨迹、以及视频的上下文信息，预测其未来某段时间内的所有轨迹。相关研究可被应用于视频行为分析、机器人导航、自动驾驶等实际场景。轨迹预测需要重点研究智能体之间异质的交互关系、场景的多维度运动限制、以及智能体活动的不确定因素等问题。围绕智能体交互关系语义漂移、智能体轨迹的多尺度建模与分析等问题，提出了对应的轨迹预测算法及模型。相关成果发表于Pattern Recognition 、ECCV等国际知名期刊及会议，并申请相关发明专利3项。

<div style="text-align: center;">
    <img style="width: 100%;" src="/assets/img/researchs/1/A-1.png">
    <p></p>
    <img style="width: 30%;" src="/assets/img/researchs/1/A-2.png">
</div> 

此外，相关成果发表A类论文10余篇，专利3项，相关成果被应用于机器人工程项目，取得了“华为杯”中国人工智能创新大赛全国三等奖。

部分代表性论文和专利：

- CSCNet: Contextual semantic consistency network for trajectory prediction in crowded spaces. Pattern Recognition 126 (2022): 108552.
- View Vertically: A hierarchical network for trajectory prediction via fourier spectrums. ECCV 2022: 682-700.
- 一种频域视角下智能体轨迹预测方法、系统、设备及介质
- 一种基于语义一致性的轨迹预测方法及装置
- ...

#### 运动评测机器人

---
 
<div style="text-align: center;">
    <img style="height: 200px;" src="/assets/img/researchs/1/image006.gif">
    <img style="height: 200px;" src="/assets/img/researchs/1/image007.gif">
    <img style="height: 200px;" src="/assets/img/researchs/1/image004.png">
    <img style="height: 200px;" src="/assets/img/researchs/1/image008.gif">
    <img style="height: 200px;" src="/assets/img/researchs/1/image009.gif">
</div> 
  
 
 
