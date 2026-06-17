# 视觉目标跟踪最新论文周报 / Weekly Report on Visual Object Tracking Papers

**报告日期范围 / Report Date Range:** 2026-06-11 ~ 2026-06-17

**生成日期 / Generated:** 2026-06-17

**数据来源 / Sources:** arXiv (cs.CV), CVPR 2026 Open Access, Google Scholar

---

## 一、概述 / Overview

本报告汇总了 2026 年 6 月 11 日至 6 月 17 日期间发表于 arXiv 及 CVPR 2026 的视觉目标跟踪领域最新论文，同时补充收录了 6 月上旬（6 月 1 日–10 日）的部分重要论文以及 CVPR 2026 大会中的跟踪相关论文，以便读者全面了解本周及近期的研究动态。

This report compiles the latest visual object tracking papers published on arXiv and at CVPR 2026 during June 11–17, 2026. It also supplements with notable papers from early June (June 1–10) and tracking-related papers from the CVPR 2026 conference, providing a comprehensive overview of recent research trends.

---

## 二、论文汇总表 / Summary Table

| 序号 | 标题 (含中文翻译) | 作者 | 来源 | 方法类别 (含中文) | 链接 |
|:---:|---|---|---|---|---|
| 1 | **FEMOT: Multi-Object Tracking using Frame and Event Cameras** / FEMOT：基于帧相机与事件相机的多目标跟踪 | Shiao Wang, Xiao Wang, Chao Wang, Yitao Li, Menghao Liu, Bo Jiang, Yaowei Wang, Yonghong Tian, Jin Tang | arXiv 2606.14094, 2026-06-12 | 多模态多目标跟踪 (RGB-Event MOT) | [Link](https://arxiv.org/abs/2606.14094) |
| 2 | **SAM-Deep-EIoU: Selective Mask Propagation for Multi-Object Tracking** / SAM-Deep-EIoU：面向多目标跟踪的选择性掩码传播 | Alexander Holmberg | arXiv 2606.13033, 2026-06-11 | 分割辅助多目标跟踪 (VOS-assisted MOT) | [Link](https://arxiv.org/abs/2606.13033) |
| 3 | **KATANA: A Fast, Low-Power Mapping of Kalman Filters onto Edge NPUs for Real-Time Tracking** / KATANA：面向实时跟踪的卡尔曼滤波器边缘NPU快速低功耗映射 | Bodhisatwa Kundu, Anish Rooj, Sumit Saha, Abhradeep Sarkar, Arghadip Das, Arnab Raha, Mrinal K. Naskar | arXiv 2606.14992, 2026-06-12 | 跟踪系统部署/边缘推理 (Edge Deployment) | [Link](https://arxiv.org/abs/2606.14992) |
| 4 | **MV3DT: Fully Distributed Multi-View 3D Tracking in Real-Time** / MV3DT：全分布式实时多视角3D跟踪 | Byron Hernandez, Fangyu Li, Aotian Wu, Paul J. Shin, Kaustubh Purandare, Henry Medeiros | arXiv 2606.13127, 2026-06-11 | 3D多目标跟踪 (3D MOT) | [Link](https://arxiv.org/abs/2606.13127) |
| 5 | **Edge-TSR: Beyond Benchmarks — Continuous Edge Inference for Fine-Grained Roadside Perception** / Edge-TSR：超越基准——面向精细路侧感知的连续边缘推理 | Aditya Mishra, Haroon Lone | arXiv 2606.17241, 2026-06-15 | 检测+跟踪边缘系统 (Detection+Tracking Edge System) | [Link](https://arxiv.org/abs/2606.17241) |
| 6 | **High-Fidelity 4D Hand-Object Capture via Multi-View Spatiotemporal Tracking** / 基于多视角时空跟踪的高保真4D手-物体捕捉 | Bo Peng, Xu Chen, Yi Gu, Hidenobu Matsuki, Mingsong Dou, Jingjing Shen, Deying Kong, Juyong Zhang, Zhengyang Shen | arXiv 2606.15908, 2026-06-14 | 4D手-物体跟踪 (4D Hand-Object Tracking) | [Link](https://arxiv.org/abs/2606.15908) |
| 7 | **Track2View: 4D-Consistent Camera-Controlled Video Generation via Paired 3D Point Tracks** / Track2View：基于配对3D点轨迹的4D一致性相机控制视频生成 | Feng Qiao, Zhaochong An, Zhexiao Xiong, Serge Belongie, Nathan Jacobs | arXiv 2606.15534, 2026-06-14 | 3D点跟踪 (3D Point Tracking) | [Link](https://arxiv.org/abs/2606.15534) |
| 8 | **PMOF: A Dataset and Benchmark for Passenger Monitoring Using Overhead Fisheye Cameras** / PMOF：基于顶部鱼眼相机的乘客监控数据集与基准 | Stella Katharina Wermuth, Qazi Arbab Ahmed, Klaus Neumann, Thorsten Jungeblut | arXiv 2606.13910, 2026-06-11 | 跟踪数据集 (Tracking Dataset) | [Link](https://arxiv.org/abs/2606.13910) |
| 9 | **VLHTrack: Vision-Language Guided Hyperspectral Object Tracking** / VLHTrack：视觉-语言引导的高光谱目标跟踪 | Rui Yao, Yuhong Zhang, Kunyang Sun, Hancheng Zhu, Jiaqi Zhao, Zhiwen Shao, Abdulmotaleb El Saddik | arXiv 2606.09167, 2026-06-08 | 高光谱单目标跟踪 (Hyperspectral SOT) | [Link](https://arxiv.org/abs/2606.09167) |
| 10 | **Does Appearance Help? A Systematic Study of Image-Based Re-Identification in Online 3D Multi-Pedestrian Tracking** / 外观信息有帮助吗？在线3D多行人跟踪中基于图像重识别的系统性研究 | Eduardo Borges, Luís Garrote, Urbano J. Nunes | arXiv 2606.07233, 2026-06-05 | 3D行人跟踪+重识别 (3D Pedestrian Tracking + ReID) | [Link](https://arxiv.org/abs/2606.07233) |
| 11 | **HDST-GNN: Heterogeneous Dynamic Spatiotemporal Graph Neural Networks for MOT in UAV Aerial Imagery** / HDST-GNN：面向无人机航拍图像多目标跟踪的异构动态时空图神经网络 | Phillip Jiang | arXiv 2606.05587, 2026-06-04 | 图神经网络多目标跟踪 (GNN-based MOT) | [Link](https://arxiv.org/abs/2606.05587) |
| 12 | **Seg2Track++: Probabilistic Track Validation and Data Association for MOTS** / Seg2Track++：面向多目标跟踪与分割的概率轨迹验证与数据关联 | Diogo Mendonça, Tiago Barros, Cristiano Premebida, Urbano J. Nunes | arXiv 2606.03875, 2026-06-02 | 分割辅助跟踪 (MOTS with SAM2) | [Link](https://arxiv.org/abs/2606.03875) |
| 13 | **CANMOT: Class-Aware Noise Modeling for Multi-Object Tracking in Autonomous Driving** / CANMOT：面向自动驾驶多目标跟踪的类别感知噪声建模 | Timo Osterburg, Stefan Schütte, Torsten Bertram | arXiv 2606.03590, 2026-06-02 | 自动驾驶多目标跟踪 (Autonomous Driving MOT) | [Link](https://arxiv.org/abs/2606.03590) |
| 14 | **SMAC: Spatial-Modal Joint Modeling for Multimodal Object Tracking** / SMAC：面向多模态目标跟踪的空间-模态联合建模 | Meijing Gao, Qitai Sun, Huanyu Sun, Bingxuan Yang, Bingzhou Sun, Xu Chen, Yonghao Yan, Yuxuan Yang | arXiv 2606.03370, 2026-06-02 | 多模态多目标跟踪 (RGB-T MOT) | [Link](https://arxiv.org/abs/2606.03370) |
| 15 | **AVTrack: Audio-Visual Tracking in Human-centric Complex Scenes** / AVTrack：以人为中心的复杂场景中的音视频跟踪 | Yaoting Wang, Yun Zhou, Zipei Zhang, Henghui Ding | arXiv 2606.02724, 2026-06-01 | 音视频跟踪 (Audio-Visual Tracking) | [Link](https://arxiv.org/abs/2606.02724) |
| 16 | **ConTrack: Constrained Hand Motion Tracking with Adaptive Trade-off Control** / ConTrack：自适应权衡控制的约束手部运动跟踪 | Yutong Liang, Quanquan Peng, Ri-Zhao Qiu, Xiaolong Wang | arXiv 2606.03177, 2026-06-02 | 手部运动跟踪 (Hand Motion Tracking) | [Link](https://arxiv.org/abs/2606.03177) |
| 17 | **Generalizable Structure-Aware Keypoint Correspondence for Category-Unified 3D Single Object Tracking** / 面向类别统一的3D单目标跟踪的可泛化结构感知关键点对应 | Jie Xiao, Yinchao Ma, Yuyang Tang, Dengqing Yang, Jianpeng Yang, Xu Zhou, Qiao Li, Wenfei Yang, Tianzhu Zhang | CVPR 2026 | 3D单目标跟踪 (3D SOT) | [Link](https://openaccess.thecvf.com/CVPR2026) |
| 18 | **RAGTrack: Language-aware RGBT Tracking with Retrieval-Augmented Generation** / RAGTrack：基于检索增强生成的语言感知RGBT跟踪 | Hao Li, Yuhao Wang, Wenning Hao, Pingping Zhang, Dong Wang, Huchuan Lu | CVPR 2026 | RGB-T单目标跟踪 (RGB-T SOT) | [Link](https://openaccess.thecvf.com/CVPR2026) |
| 19 | **TGTrack: Temporal Generative Learning for Unified Single Object Tracking** / TGTrack：面向统一单目标跟踪的时序生成学习 | Wanting Geng, Xin Chen, Chuanyu Sun, Jie Zhao, Ben Kang, Dong Wang, Huchuan Lu | CVPR 2026 | 生成式单目标跟踪 (Generative SOT) | [Link](https://openaccess.thecvf.com/CVPR2026) |
| 20 | **MV-TAP: Tracking Any Point in Multi-View Videos** / MV-TAP：多视角视频中的任意点跟踪 | Jahyeok Koo et al. | CVPR 2026 | 多视角点跟踪 (Multi-View Point Tracking) | [Link](https://openaccess.thecvf.com/CVPR2026) |
| 21 | **Dual-level Adaptation for Multi-Object Tracking** / 多目标跟踪的双层自适应 | Guo Wen et al. | CVPR 2026 | 多目标跟踪自适应 (MOT Adaptation) | [Link](https://openaccess.thecvf.com/CVPR2026) |
| 22 | **OneTrackerV2: Unified Multimodal Visual Tracking with Dual Mixture-of-Experts** / OneTrackerV2：基于双重混合专家的统一多模态视觉跟踪 | Lingyi Hong, Jinglun Li, Xinyu Zhou, Kaixun Jiang, Pinxue Guo, Zhaoyu Chen, Runze Li, Xingdong Sheng, Wenqiang Zhang | arXiv 2605.03716, 2026-05-05 | 统一多模态跟踪 (Unified Multimodal Tracking) | [Link](https://arxiv.org/abs/2605.03716) |

---

## 三、按主题分组的论文详细摘要 / Detailed Abstracts Grouped by Topic

### 3.1 多目标跟踪 / Multi-Object Tracking (MOT)

---

#### 论文 1 / Paper 1: FEMOT

**FEMOT: Multi-Object Tracking using Frame and Event Cameras**
**FEMOT：基于帧相机与事件相机的多目标跟踪**

**作者 / Authors:** Shiao Wang, Xiao Wang, Chao Wang, Yitao Li, Menghao Liu, Bo Jiang, Yaowei Wang, Yonghong Tian, Jin Tang

**日期 / Date:** 2026-06-12

**来源 / Source:** arXiv 2606.14094

**链接 / Link:** https://arxiv.org/abs/2606.14094

[EN] Conventional RGB cameras have been widely used in multi-object tracking due to their ability to capture rich appearance and semantic information. However, their performance is often degraded under complex real-world challenges, such as motion blur, low illumination, and overexposure. Bio-inspired event cameras offer high temporal resolution and high dynamic range, providing complementary cues under extreme scenarios. The authors propose FEMOT, a large-scale RGB-event multi-object tracking dataset covering diverse real-world scenarios and 14 challenging attributes. They also propose FEMOTR, a multimodal tracking framework that decouples RGB and event features and fuses them in the frequency domain for robust object localization and identity association.

[CN] 传统RGB相机因能捕捉丰富的外观和语义信息而被广泛用于多目标跟踪，但在运动模糊、低光照和过曝等复杂场景下性能退化。受生物启发的事件相机具有高时间分辨率和高动态范围，可在极端场景下提供互补信息。本文提出FEMOT——一个大规模RGB-事件多目标跟踪数据集，涵盖多种真实场景和14种挑战属性；同时提出FEMOTR多模态跟踪框架，在频域中解耦并融合RGB与事件特征，实现鲁棒的目标定位和身份关联。

**关键方法 / Key Methods:** 频域RGB-事件特征融合 (Frequency-domain RGB-Event feature fusion), 大规模基准数据集 (Large-scale benchmark dataset)

---

#### 论文 2 / Paper 2: SAM-Deep-EIoU

**SAM-Deep-EIoU: Selective Mask Propagation for Multi-Object Tracking**
**SAM-Deep-EIoU：面向多目标跟踪的选择性掩码传播**

**作者 / Authors:** Alexander Holmberg

**日期 / Date:** 2026-06-11

**来源 / Source:** arXiv 2606.13033

**链接 / Link:** https://arxiv.org/abs/2606.13033

[EN] Multi-object tracking has a heavy-tailed difficulty distribution: most frames are easy for a lightweight base tracker, while a small fraction are intrinsically hard. VOS models can preserve identity through hard frames where the base tracker fails, but they are much more expensive. The author proposes selective mask propagation, a training-free algorithm that dispatches from a base tracker to a VOS model only on windows where an assignment-uncertainty signal fires. On DanceTrack, it improves three different base trackers. On SportsMOT, SAM 3-Deep-EIoU with global track association achieves state-of-the-art performance with 86.8 HOTA.

[CN] 多目标跟踪具有长尾难度分布：大多数帧对轻量级基础跟踪器而言较为简单，仅少数帧本质上困难。视频目标分割（VOS）模型能在基础跟踪器失败的困难帧中保持身份一致性，但计算成本远高于基础跟踪器。本文提出选择性掩码传播——一种无需训练的算法，仅在分配不确定性信号触发时才将基础跟踪器切换至VOS模型。在DanceTrack上可提升三种不同的基础跟踪器；在SportsMOT上，结合全局轨迹关联的SAM 3-Deep-EIoU以86.8 HOTA达到了当前最优性能。

**关键方法 / Key Methods:** 不确定性驱动的选择性调度 (Uncertainty-driven selective dispatch), VOS与MOT黑盒融合 (Black-box VOS-MOT fusion), 无需训练 (Training-free)

---

#### 论文 3 / Paper 3: HDST-GNN

**HDST-GNN: Heterogeneous Dynamic Spatiotemporal Graph Neural Networks for MOT in UAV Aerial Imagery**
**HDST-GNN：面向无人机航拍图像多目标跟踪的异构动态时空图神经网络**

**作者 / Authors:** Phillip Jiang

**日期 / Date:** 2026-06-04

**来源 / Source:** arXiv 2606.05587

**链接 / Link:** https://arxiv.org/abs/2606.05587

[EN] Multi-object tracking from UAV imagery presents unique challenges: camera altitude varies across sequences, objects appear small and densely packed, and frequent occlusion causes identity switches. The author proposes HDST-GNN with three novel contributions: (1) Altitude-Adaptive Edge Construction that adjusts graph connectivity radius based on estimated camera altitude; (2) Heterogeneous Node Representation that models detections, confirmed tracklets, and lost tracklets as distinct node types with dedicated projections and five typed edge relations; (3) Occlusion-Gated Temporal Aggregation that gates attention contributions by occlusion confidence. HDST-GNN achieves 94.51% MOTA and 97.24% IDF1 on VisDrone2019-MOT, reducing identity switches by 81%.

[CN] 无人机航拍图像的多目标跟踪面临独特挑战：相机高度跨序列变化、目标小且密集、频繁遮挡导致身份切换。本文提出HDST-GNN，包含三个创新：(1) 高度自适应边构建——根据估计的相机高度调整图连接半径；(2) 异构节点表示——将检测、已确认轨迹和丢失轨迹建模为不同节点类型，配备专用投影和五种类型化边关系；(3) 遮挡门控时序聚合——按遮挡置信度门控注意力贡献。在VisDrone2019-MOT上达到94.51% MOTA和97.24% IDF1，身份切换减少81%。

**关键方法 / Key Methods:** 高度自适应图构建 (Altitude-adaptive graph construction), 异构节点表示 (Heterogeneous node representation), 遮挡门控聚合 (Occlusion-gated aggregation)

---

#### 论文 4 / Paper 4: Seg2Track++

**Seg2Track++: Probabilistic Track Validation and Data Association for Multi-Object Tracking and Segmentation**
**Seg2Track++：面向多目标跟踪与分割的概率轨迹验证与数据关联**

**作者 / Authors:** Diogo Mendonça, Tiago Barros, Cristiano Premebida, Urbano J. Nunes

**日期 / Date:** 2026-06-02

**来源 / Source:** arXiv 2606.03875

**链接 / Link:** https://arxiv.org/abs/2606.03875

[EN] Autonomous systems require robust Multi-Object Tracking and Segmentation (MOTS) to operate reliably in dynamic environments. Foundation models such as SAM2 have shown strong zero-shot generalization for segmentation, but their direct application to MOTS is limited by unreliable track association and false-positive propagation. This work introduces Seg2Track++, a framework that integrates instance segmentation with SAM2 and a novel track management module to perform zero-shot MOTS with enhanced temporal consistency. Tracks are associated using Mask Centroid Distance (MCD) and Confidence-Aware Cost Modulation (CCM), while Probabilistic Track Validation (PTV) employs a Bernoulli filter to validate track existence and suppress ghost tracks.

[CN] 自主系统需要鲁棒的多目标跟踪与分割（MOTS）以在动态环境中可靠运行。SAM2等基础模型展现了强大的零样本分割泛化能力，但直接应用于MOTS时受到不可靠轨迹关联和误检传播的限制。本文提出Seg2Track++，将SAM2实例分割与新型轨迹管理模块集成，实现具有增强时序一致性的零样本MOTS。使用掩码质心距离（MCD）和置信度感知代价调节（CCM）进行轨迹关联，并通过基于伯努利滤波的概率轨迹验证（PTV）验证轨迹存在性、抑制幽灵轨迹。

**关键方法 / Key Methods:** SAM2零样本分割 (SAM2 zero-shot segmentation), 伯努利滤波轨迹验证 (Bernoulli filter track validation), 置信度感知代价调节 (Confidence-aware cost modulation)

---

#### 论文 5 / Paper 5: CANMOT

**CANMOT: Class-Aware Noise Modeling for Multi-Object Tracking in Autonomous Driving**
**CANMOT：面向自动驾驶多目标跟踪的类别感知噪声建模**

**作者 / Authors:** Timo Osterburg, Stefan Schütte, Torsten Bertram

**日期 / Date:** 2026-06-02

**来源 / Source:** arXiv 2606.03590

**链接 / Link:** https://arxiv.org/abs/2606.03590

[EN] Kalman filter-based multi-object tracking remains a strong baseline for autonomous driving. In most practical systems, process noise and measurement noise covariances are defined globally and shared across object classes. This work proposes CANMOT, a class-aware and object-aligned noise modeling framework for KF-based 3D MOT. Class-specific diagonal process and measurement covariance matrices are introduced and optionally expressed in the object coordinate frame to preserve longitudinal-lateral anisotropy. Experiments on nuScenes show improved tracking performance and substantially reduced identity switches.

[CN] 基于卡尔曼滤波的多目标跟踪在自动驾驶中仍是强有力的基线方法。大多数实际系统中，过程噪声和测量噪声协方差被全局定义并在所有目标类别间共享。本文提出CANMOT——一种面向基于KF的3D MOT的类别感知与目标对齐噪声建模框架。引入类别特定的对角过程和测量协方差矩阵，并可选择在目标坐标系中表示以保持纵横向各向异性。在nuScenes上的实验表明跟踪性能提升且身份切换大幅减少。

**关键方法 / Key Methods:** 类别感知噪声协方差 (Class-aware noise covariance), 目标坐标系对齐 (Object coordinate frame alignment), 3D MOT

---

#### 论文 6 / Paper 6: Dual-level Adaptation for MOT (CVPR 2026)

**Dual-level Adaptation for Multi-Object Tracking: Building Test-Time Calibration from Experience and Intuition**
**多目标跟踪的双层自适应：从经验和直觉构建测试时校准**

**作者 / Authors:** Guo Wen et al.

**日期 / Date:** 2026-06 (CVPR 2026)

**来源 / Source:** CVPR 2026

**链接 / Link:** https://openaccess.thecvf.com/CVPR2026

[EN] Proposes a dual-level adaptation strategy for multi-object tracking that builds test-time calibration from both experience (historical tracking data) and intuition (current frame cues), improving tracking robustness under domain shifts.

[CN] 提出一种双层自适应策略，从经验（历史跟踪数据）和直觉（当前帧线索）两个层面构建测试时校准，提升域偏移下的跟踪鲁棒性。

**关键方法 / Key Methods:** 测试时自适应 (Test-time adaptation), 双层校准 (Dual-level calibration)

---

### 3.2 单目标跟踪 / Single Object Tracking (SOT)

---

#### 论文 7 / Paper 7: VLHTrack

**VLHTrack: Vision-Language Guided Hyperspectral Object Tracking via Semantics Fusion and Contextual Template Updating**
**VLHTrack：基于语义融合与上下文模板更新的视觉-语言引导高光谱目标跟踪**

**作者 / Authors:** Rui Yao, Yuhong Zhang, Kunyang Sun, Hancheng Zhu, Jiaqi Zhao, Zhiwen Shao, Abdulmotaleb El Saddik

**日期 / Date:** 2026-06-08

**来源 / Source:** arXiv 2606.09167

**链接 / Link:** https://arxiv.org/abs/2606.09167

[EN] Hyperspectral object tracking (HOT) leverages rich spectral information from hyperspectral videos. The authors propose VLHTrack, a novel hyperspectral vision-language joint tracking framework. They incorporate language priors to address spectral redundancy by designing a Language-Guided Band Selection Module (LBSM) that leverages LLM descriptions to establish semantic-to-spectral mapping. A Multi-Modal Vision-Language Fusion Module integrates visual and linguistic embeddings. To address target deformation in long-term sequences, a Dynamic Template Update with Mamba (DTUM) module leverages selective state space modeling to learn inter-frame dependencies for efficient template feature evolution. Experiments on HOT2023 and HOT2024 demonstrate superiority over state-of-the-art methods.

[CN] 高光谱目标跟踪利用高光谱视频中丰富的光谱信息。本文提出VLHTrack——一种新型高光谱视觉-语言联合跟踪框架。通过设计语言引导波段选择模块（LBSM），利用大语言模型描述建立语义到光谱的映射，解决光谱冗余问题。多模态视觉-语言融合模块无缝集成视觉和语言嵌入。为解决长期序列中的目标形变，提出基于Mamba的动态模板更新模块（DTUM），利用选择性状态空间建模学习帧间依赖关系，实现高效的模板特征演化。在HOT2023和HOT2024上超越了当前最优方法。

**关键方法 / Key Methods:** 语言引导波段选择 (Language-guided band selection), Mamba状态空间模型 (Mamba state space modeling), 视觉-语言融合 (Vision-language fusion)

---

#### 论文 8 / Paper 8: RAGTrack (CVPR 2026)

**RAGTrack: Language-aware RGBT Tracking with Retrieval-Augmented Generation**
**RAGTrack：基于检索增强生成的语言感知RGBT跟踪**

**作者 / Authors:** Hao Li, Yuhao Wang, Wenning Hao, Pingping Zhang, Dong Wang, Huchuan Lu

**日期 / Date:** 2026-06 (CVPR 2026)

**来源 / Source:** CVPR 2026

**链接 / Link:** https://openaccess.thecvf.com/CVPR2026

[EN] Introduces retrieval-augmented generation (RAG) into RGB-T tracking, enabling language-aware multimodal tracking that leverages textual information to improve robustness. By retrieving relevant visual-linguistic knowledge from external databases, RAGTrack enhances the tracker's ability to handle challenging scenarios such as occlusion, illumination changes, and thermal crossover.

[CN] 将检索增强生成（RAG）引入RGB-T跟踪领域，实现语言感知的多模态跟踪。通过从外部数据库检索相关的视觉-语言知识，RAGTrack增强了跟踪器在遮挡、光照变化和热成像交叉等挑战性场景下的鲁棒性。

**关键方法 / Key Methods:** 检索增强生成 (RAG), 语言感知跟踪 (Language-aware tracking), RGB-T融合 (RGB-T fusion)

---

#### 论文 9 / Paper 9: TGTrack (CVPR 2026)

**TGTrack: Temporal Generative Learning for Unified Single Object Tracking**
**TGTrack：面向统一单目标跟踪的时序生成学习**

**作者 / Authors:** Wanting Geng, Xin Chen, Chuanyu Sun, Jie Zhao, Ben Kang, Dong Wang, Huchuan Lu

**日期 / Date:** 2026-06 (CVPR 2026)

**来源 / Source:** CVPR 2026

**链接 / Link:** https://openaccess.thecvf.com/CVPR2026

[EN] Proposes a temporal generative learning approach that unifies single object tracking across different modalities and scenarios through generative modeling. By modeling the temporal dynamics of target appearance and motion as a generative process, TGTrack achieves robust unified tracking without requiring modality-specific architectural modifications.

[CN] 提出一种时序生成学习方法，通过生成式建模统一不同模态和场景下的单目标跟踪。将目标外观和运动的时序动态建模为生成过程，TGTrack实现了鲁棒的统一跟踪，无需针对特定模态修改架构。

**关键方法 / Key Methods:** 时序生成建模 (Temporal generative modeling), 统一跟踪框架 (Unified tracking framework)

---

#### 论文 10 / Paper 10: OneTrackerV2

**OneTrackerV2: Unified Multimodal Visual Tracking with Dual Mixture-of-Experts**
**OneTrackerV2：基于双重混合专家的统一多模态视觉跟踪**

**作者 / Authors:** Lingyi Hong, Jinglun Li, Xinyu Zhou, Kaixun Jiang, Pinxue Guo, Zhaoyu Chen, Runze Li, Xingdong Sheng, Wenqiang Zhang

**日期 / Date:** 2026-05-05

**来源 / Source:** arXiv 2605.03716

**链接 / Link:** https://arxiv.org/abs/2605.03716

[EN] Introduces OneTrackerV2, a unified multi-modal tracking framework enabling end-to-end training for any modality. Proposes Meta Merger to embed multi-modal information into a unified space, and Dual Mixture-of-Experts (DMoE): T-MoE models spatio-temporal relations for tracking, while M-MoE embeds multi-modal knowledge, disentangling cross-modal dependencies. Achieves state-of-the-art across five RGB and RGB+X tracking tasks and 12 benchmarks with a single end-to-end training.

[CN] 提出OneTrackerV2——一种统一的多模态跟踪框架，支持任意模态的端到端训练。提出Meta Merger将多模态信息嵌入统一空间，以及双重混合专家（DMoE）：T-MoE建模时空关系用于跟踪，M-MoE嵌入多模态知识以解耦跨模态依赖。通过单次端到端训练，在五种RGB和RGB+X跟踪任务及12个基准上达到当前最优。

**关键方法 / Key Methods:** 双重混合专家 (Dual MoE), Meta Merger模态统一 (Meta Merger modality unification), 端到端训练 (End-to-end training)

---

#### 论文 11 / Paper 11: Generalizable Structure-Aware 3D SOT (CVPR 2026)

**Generalizable Structure-Aware Keypoint Correspondence for Category-Unified 3D Single Object Tracking**
**面向类别统一的3D单目标跟踪的可泛化结构感知关键点对应**

**作者 / Authors:** Jie Xiao, Yinchao Ma, Yuyang Tang, Dengqing Yang, Jianpeng Yang, Xu Zhou, Qiao Li, Wenfei Yang, Tianzhu Zhang

**日期 / Date:** 2026-06 (CVPR 2026)

**来源 / Source:** CVPR 2026

**链接 / Link:** https://openaccess.thecvf.com/CVPR2026

[EN] Addresses the category-unification problem in 3D single object tracking on point clouds by proposing a structure-aware keypoint correspondence method that generalizes across object categories. By learning structural priors of different object types, the method establishes robust point-level correspondences that transfer to unseen categories.

[CN] 针对点云3D单目标跟踪中的类别统一问题，提出一种可跨目标类别泛化的结构感知关键点对应方法。通过学习不同目标类型的结构先验，建立可迁移到未见类别的鲁棒点级对应关系。

**关键方法 / Key Methods:** 结构感知关键点对应 (Structure-aware keypoint correspondence), 类别统一 (Category unification), 3D点云跟踪 (3D point cloud tracking)

---

### 3.3 3D/多视角跟踪 / 3D and Multi-View Tracking

---

#### 论文 12 / Paper 12: MV3DT

**MV3DT: Fully Distributed Multi-View 3D Tracking in Real-Time**
**MV3DT：全分布式实时多视角3D跟踪**

**作者 / Authors:** Byron Hernandez, Fangyu Li, Aotian Wu, Paul J. Shin, Kaustubh Purandare, Henry Medeiros

**日期 / Date:** 2026-06-11

**来源 / Source:** arXiv 2606.13127

**链接 / Link:** https://arxiv.org/abs/2606.13127

[EN] Multi-camera tracking with overlapping fields of view typically relies on centralized fusion, which creates computational bottlenecks that prevent deployment at scale. The authors present MV3DT, a fully distributed framework for real-time multi-view 3D tracking that achieves accurate identity propagation and occlusion recovery through peer-to-peer coordination, eliminating the need for central aggregation.

[CN] 具有重叠视场的多相机跟踪通常依赖集中式融合，会造成计算瓶颈从而阻碍大规模部署。本文提出MV3DT——一种全分布式实时多视角3D跟踪框架，通过对等协调实现精确的身份传播和遮挡恢复，无需中心聚合。

**关键方法 / Key Methods:** 全分布式架构 (Fully distributed architecture), 对等协调 (Peer-to-peer coordination), 无需中心化 (No central aggregation)

---

#### 论文 13 / Paper 13: Does Appearance Help?

**Does Appearance Help? A Systematic Study of Image-Based Re-Identification in Online 3D Multi-Pedestrian Tracking**
**外观信息有帮助吗？在线3D多行人跟踪中基于图像重识别的系统性研究**

**作者 / Authors:** Eduardo Borges, Luís Garrote, Urbano J. Nunes

**日期 / Date:** 2026-06-05

**来源 / Source:** arXiv 2606.07233

**链接 / Link:** https://arxiv.org/abs/2606.07233

[EN] LiDAR-based 3D MOT typically relies solely on geometric information, which is insufficient during prolonged occlusions. This work presents a systematic study of image-based ReID in online 3D MOT, utilizing a lightweight projection-based framework to decouple geometric and appearance modeling. A cascaded matching strategy successfully recovers occluded tracks without compromising overall precision. Experiments on KITTI show lightweight architectures offer an optimal trade-off between low latency and discriminative power.

[CN] 基于LiDAR的3D MOT通常仅依赖几何信息，在长时间遮挡期间不足以区分目标。本文对在线3D MOT中基于图像的ReID进行系统性研究，采用轻量级投影框架解耦几何和外观建模。级联匹配策略成功恢复被遮挡轨迹而不牺牲整体精度。在KITTI上的实验表明，轻量架构在低延迟和判别能力之间提供了最佳权衡。

**关键方法 / Key Methods:** 级联匹配策略 (Cascaded matching), 轻量级ReID (Lightweight ReID), 几何-外观解耦 (Geometry-appearance decoupling)

---

#### 论文 14 / Paper 14: MV-TAP (CVPR 2026)

**MV-TAP: Tracking Any Point in Multi-View Videos**
**MV-TAP：多视角视频中的任意点跟踪**

**作者 / Authors:** Jahyeok Koo et al.

**日期 / Date:** 2026-06 (CVPR 2026)

**来源 / Source:** CVPR 2026

**链接 / Link:** https://openaccess.thecvf.com/CVPR2026

[EN] Proposes MV-TAP, a method for tracking arbitrary points across multiple camera views in video sequences, enabling 3D-aware point tracking that leverages multi-view geometry for improved accuracy and consistency.

[CN] 提出MV-TAP，可在视频序列的多个相机视角间跟踪任意点，利用多视角几何实现3D感知的点跟踪，提升准确性和一致性。

**关键方法 / Key Methods:** 多视角点跟踪 (Multi-view point tracking), 3D感知 (3D-aware tracking)

---

#### 论文 15 / Paper 15: 4D Hand-Object Capture

**High-Fidelity 4D Hand-Object Capture via Multi-View Spatiotemporal Tracking and Physics-Aware Gaussians**
**基于多视角时空跟踪和物理感知高斯的高保真4D手-物体捕捉**

**作者 / Authors:** Bo Peng, Xu Chen, Yi Gu, Hidenobu Matsuki, Mingsong Dou, Jingjing Shen, Deying Kong, Juyong Zhang, Zhengyang Shen

**日期 / Date:** 2026-06-14

**来源 / Source:** arXiv 2606.15908

**链接 / Link:** https://arxiv.org/abs/2606.15908

[EN] The growing demand for high-fidelity 4D hand-object interaction data in embodied AI and spatial computing is bottlenecked by reliance on pre-scanned templates and markers. The authors propose a novel system for robust reconstruction of hands and objects from multi-view videos without templates or markers, consisting of: (1) a multi-view feed-forward transformer aggregating cross-view geometry and temporal cues, and (2) a hand-object physics-aware Gaussian-based optimization framework.

[CN] 具身AI和空间计算对高保真4D手-物体交互数据的需求日益增长，但受限于对预扫描模板和标记物的依赖。本文提出一种无需模板和标记物的多视角视频手-物体鲁棒重建系统，包含：(1) 聚合跨视角几何和时序线索的多视角前馈Transformer，以及 (2) 基于物理感知高斯的手-物体优化框架。

**关键方法 / Key Methods:** 多视角Transformer (Multi-view Transformer), 物理感知高斯优化 (Physics-aware Gaussian optimization), 无标记重建 (Marker-free reconstruction)

---

### 3.4 多模态跟踪 / Multimodal Tracking

---

#### 论文 16 / Paper 16: SMAC

**SMAC: Spatial-Modal Joint Modeling and Adaptive Representation Collapse for Multimodal Object Tracking**
**SMAC：面向多模态目标跟踪的空间-模态联合建模与自适应表示坍缩**

**作者 / Authors:** Meijing Gao, Qitai Sun, Huanyu Sun, Bingxuan Yang, Bingzhou Sun, Xu Chen, Yonghao Yan, Yuxuan Yang

**日期 / Date:** 2026-06-02

**来源 / Source:** arXiv 2606.03370

**链接 / Link:** https://arxiv.org/abs/2606.03370

[EN] Multimodal MOT under complex illumination remains challenging due to insufficient joint modeling of spatial and modal features. This paper proposes a spatial-modal convolution fusion and distillation-prompt-based framework. A Basic module performs spatial feature extraction and modal interaction via decoupled 3D convolution, while a Mixed module models nonlinear cross-modal correlations through amplitude-phase decomposition. A Distillation Prompt Guidance module generates dynamic modal weights under teacher supervision. The tracker achieves 63.31 HOTA and 79.21 MOTA on the UniRTL dataset.

[CN] 复杂光照条件下的多模态MOT因空间-模态特征联合建模不足而仍具挑战性。本文提出空间-模态卷积融合与蒸馏提示框架。基础模块通过解耦3D卷积进行空间特征提取和模态交互；混合模块通过振幅-相位分解建模非线性跨模态关联。蒸馏提示引导模块在教师监督下生成动态模态权重。在UniRTL数据集上达到63.31 HOTA和79.21 MOTA。

**关键方法 / Key Methods:** 解耦3D卷积 (Decoupled 3D convolution), 振幅-相位分解 (Amplitude-phase decomposition), 蒸馏提示引导 (Distillation prompt guidance)

---

#### 论文 17 / Paper 17: AVTrack

**AVTrack: Audio-Visual Tracking in Human-centric Complex Scenes**
**AVTrack：以人为中心的复杂场景中的音视频跟踪**

**作者 / Authors:** Yaoting Wang, Yun Zhou, Zipei Zhang, Henghui Ding

**日期 / Date:** 2026-06-01

**来源 / Source:** arXiv 2606.02724

**链接 / Link:** https://arxiv.org/abs/2606.02724

[EN] Audio-visual speaker tracking aims to localize and track active speakers by leveraging auditory and visual cues. Existing datasets are limited to simple or homogeneous scenes. The authors introduce AVTrack, a human-centric audio-visual instance segmentation dataset designed for dynamic real-world scenarios, featuring diverse conditions including camera motion, visual occlusions, and position changes. Evaluations of representative AVIS methods reveal substantial performance degradation, establishing AVTrack as a challenging benchmark.

[CN] 音视频说话人跟踪旨在利用听觉和视觉线索定位和跟踪活跃说话人。现有数据集局限于简单或同质场景。本文推出AVTrack——一个面向动态真实场景的以人为中心的音视频实例分割数据集，涵盖相机运动、视觉遮挡和位置变化等多种条件。对代表性AVIS方法的评估显示性能大幅下降，确立AVTrack为具有挑战性的基准。

**关键方法 / Key Methods:** 音视频实例分割 (Audio-visual instance segmentation), 以人为中心 (Human-centric), 多场景基准 (Multi-scenario benchmark)

---

### 3.5 跟踪系统部署与效率 / Tracking System Deployment and Efficiency

---

#### 论文 18 / Paper 18: KATANA

**KATANA: A Fast, Low-Power Mapping of Kalman Filters onto Edge NPUs for Real-Time Tracking**
**KATANA：面向实时跟踪的卡尔曼滤波器边缘NPU快速低功耗映射**

**作者 / Authors:** Bodhisatwa Kundu, Anish Rooj, Sumit Saha, Abhradeep Sarkar, Arghadip Das, Arnab Raha, Mrinal K. Naskar

**日期 / Date:** 2026-06-12

**来源 / Source:** arXiv 2606.14992

**链接 / Link:** https://arxiv.org/abs/2606.14992

[EN] State estimation is the closed-loop core of every real-time tracking system. The authors present KATANA, an NPU-aware optimization framework delivering the first end-to-end mapping of LKF and EKF onto commercial edge NPUs. Three algebraic graph rewrites — subtract-to-add reformulation, static-shape tensor fusion, and block-diagonal batched parallelization — ensure 100% of operations execute on the DPU matrix engine. On Intel Core Ultra Series 2, the optimized batched EKF reaches 223.35 FPS at 13.43W and the LKF reaches 408.73 FPS at 14.05W, achieving up to 97.9% reduction in dynamic energy versus CPU.

[CN] 状态估计是每个实时跟踪系统的闭环核心。本文提出KATANA——一种NPU感知优化框架，首次将线性卡尔曼滤波器（LKF）和扩展卡尔曼滤波器（EKF）端到端映射到商用边缘NPU上。三种代数图重写——减法转加法、静态形状张量融合和块对角批处理并行化——确保100%的操作在DPU矩阵引擎上执行。在Intel Core Ultra Series 2上，优化的批处理EKF在13.43W功耗下达到223.35 FPS，LKF在14.05W下达到408.73 FPS，动态能耗相比CPU降低高达97.9%。

**关键方法 / Key Methods:** NPU感知优化 (NPU-aware optimization), 代数图重写 (Algebraic graph rewrites), 边缘部署 (Edge deployment)

---

#### 论文 19 / Paper 19: Edge-TSR

**Edge-TSR: Beyond Benchmarks — Continuous Edge Inference for Fine-Grained Roadside Perception**
**Edge-TSR：超越基准——面向精细路侧感知的连续边缘推理**

**作者 / Authors:** Aditya Mishra, Haroon Lone

**日期 / Date:** 2026-06-15

**来源 / Source:** arXiv 2606.17241

**链接 / Link:** https://arxiv.org/abs/2606.17241

[EN] Continuous AI inference on resource-constrained edge hardware introduces deployment effects invisible to conventional benchmarks — temporal instability, thermal throttling, and workload-dependent variability. Edge-TSR integrates detection, tracking, fine-grained classification, and a lightweight track-aware temporal stabilization mechanism. The central finding is that benchmark-centric evaluation systematically overstates deployed edge performance by 20–30%. Edge-TSR recovers up to 10.16% classification accuracy over per-frame baselines while maintaining sustained real-time performance on NVIDIA Jetson Orin Nano.

[CN] 在资源受限的边缘硬件上进行连续AI推理会引入传统基准测试看不见的部署效应——时序不稳定、热节流和工作负载相关的性能波动。Edge-TSR集成检测、跟踪、细粒度分类和轻量级轨迹感知时序稳定机制。核心发现是：以基准为中心的评估系统性地将部署后的边缘性能高估了20–30%。Edge-TSR在NVIDIA Jetson Orin Nano上恢复高达10.16%的分类精度，同时维持持续实时性能。

**关键方法 / Key Methods:** 轨迹感知时序稳定 (Track-aware temporal stabilization), 部署感知评估 (Deployment-aware evaluation), 边缘推理优化 (Edge inference optimization)

---

### 3.6 跟踪数据集与基准 / Tracking Datasets and Benchmarks

---

#### 论文 20 / Paper 20: PMOF

**PMOF: A Dataset and Benchmark for Passenger Monitoring Using Overhead Fisheye Cameras**
**PMOF：基于顶部鱼眼相机的乘客监控数据集与基准**

**作者 / Authors:** Stella Katharina Wermuth, Qazi Arbab Ahmed, Klaus Neumann, Thorsten Jungeblut

**日期 / Date:** 2026-06-11

**来源 / Source:** arXiv 2606.13910

**链接 / Link:** https://arxiv.org/abs/2606.13910

[EN] Autonomous staff-free public transport requires reliable in-vehicle passenger monitoring. The authors introduce PMOF, the first public dataset of top-view fisheye imagery captured inside a moving vehicle. PMOF provides rotated bounding boxes, tracking identifiers, and action labels, supporting object detection, tracking, and action recognition tasks.

[CN] 无人值守自动驾驶公共交通需要可靠的车内乘客监控。本文推出PMOF——首个在行驶车辆内采集的顶视鱼眼图像公开数据集。PMOF提供旋转边界框、跟踪标识符和动作标签，支持目标检测、跟踪和动作识别任务。

**关键方法 / Key Methods:** 鱼眼图像跟踪 (Fisheye image tracking), 车内监控 (In-vehicle monitoring), 多任务基准 (Multi-task benchmark)

---

## 四、本周研究趋势总结 / Research Trends This Week

### 趋势 1 / Trend 1: 多模态融合持续升温 / Multimodal Fusion Continues to Heat Up

[EN] A significant portion of this week's papers address multimodal tracking: RGB-Event cameras (FEMOT), RGB-Thermal (SMAC, RAGTrack), hyperspectral + language (VLHTrack), and audio-visual (AVTrack). The field is clearly moving beyond single-modality tracking, with increasing emphasis on leveraging complementary information from diverse sensor modalities. Notably, language/vision-language models are beginning to play a guiding role in tracking (RAGTrack, VLHTrack).

[CN] 本周相当大比例的论文关注多模态跟踪：RGB-事件相机（FEMOT）、RGB-热成像（SMAC、RAGTrack）、高光谱+语言（VLHTrack）、音视频（AVTrack）。该领域明显超越单模态跟踪，越来越强调利用来自不同传感器的互补信息。值得注意的是，语言/视觉-语言模型开始在跟踪中发挥引导作用（RAGTrack、VLHTrack）。

### 趋势 2 / Trend 2: 分割基础模型深度融入跟踪 / Foundation Segmentation Models Deeply Integrated into Tracking

[EN] SAM2 and VOS models are increasingly being integrated into tracking pipelines. SAM-Deep-EIoU proposes selective dispatch to VOS models on hard frames. Seg2Track++ uses SAM2 for zero-shot MOTS with probabilistic track validation. This trend suggests that foundation segmentation models are becoming standard components in tracking systems, bridging the gap between detection-based and segmentation-based tracking paradigms.

[CN] SAM2和VOS模型正越来越多地被集成到跟踪流程中。SAM-Deep-EIoU提出在困难帧选择性调度至VOS模型；Seg2Track++利用SAM2实现带概率轨迹验证的零样本MOTS。这一趋势表明，基础分割模型正成为跟踪系统的标准组件，弥合了基于检测和基于分割的跟踪范式之间的差距。

### 趋势 3 / Trend 3: 边缘部署与实时性成为核心关切 / Edge Deployment and Real-Time Performance Become Central Concerns

[EN] KATANA maps Kalman filters onto edge NPUs with 97.9% energy reduction. Edge-TSR reveals that benchmark evaluations overstate edge deployment performance by 20–30% and proposes temporal stabilization for real-world deployment. These papers reflect a growing awareness that tracking systems must be designed and evaluated with deployment constraints in mind, including power budgets, thermal limits, and sustained inference quality.

[CN] KATANA将卡尔曼滤波器映射到边缘NPU，能耗降低97.9%；Edge-TSR揭示基准评估将边缘部署性能高估20–30%，并提出面向真实部署的时序稳定方案。这些论文反映了日益增长的共识：跟踪系统必须在考虑部署约束（包括功率预算、热限制和持续推理质量）的前提下进行设计和评估。

### 趋势 4 / Trend 4: Mamba/状态空间模型替代Transformer / Mamba/State-Space Models as Transformer Alternatives

[EN] VLHTrack uses Mamba-based selective state space modeling for dynamic template updating, and OneTrackerV2 employs novel Mixture-of-Experts architectures. The traditional Siamese and Transformer tracker paradigms are being supplemented (and in some cases replaced) by Mamba/state-space models and MoE architectures, offering better efficiency for long-sequence modeling in tracking.

[CN] VLHTrack使用基于Mamba的选择性状态空间建模进行动态模板更新，OneTrackerV2采用新型混合专家架构。传统的Siamese和Transformer跟踪器范式正在被Mamba/状态空间模型和MoE架构补充（某些情况下甚至替代），为跟踪中的长序列建模提供更好的效率。

### 趋势 5 / Trend 5: 3D/4D跟踪与多视角几何 / 3D/4D Tracking and Multi-View Geometry

[EN] Multiple papers address 3D and 4D tracking: category-unified 3D SOT (CVPR 2026), distributed multi-view 3D tracking (MV3DT), 3D pedestrian tracking with ReID, and 4D hand-object capture. MV-TAP enables tracking any point across multiple views. This reflects the field's expansion from 2D single-camera tracking to 3D multi-camera and point-cloud-based tracking, with increasing focus on generalization across object categories.

[CN] 多篇论文关注3D和4D跟踪：类别统一的3D SOT（CVPR 2026）、分布式多视角3D跟踪（MV3DT）、带ReID的3D行人跟踪以及4D手-物体捕捉。MV-TAP实现跨多视角的任意点跟踪。这反映了该领域从2D单相机跟踪向3D多相机和基于点云的跟踪的扩展，以及日益关注跨目标类别的泛化能力。

### 趋势 6 / Trend 6: 图神经网络与数据关联 / Graph Neural Networks and Data Association

[EN] HDST-GNN demonstrates the power of heterogeneous graph neural networks for UAV-based MOT, with altitude-adaptive graph construction and occlusion-gated temporal aggregation. GNN-based approaches are proving particularly effective for challenging scenarios with small, dense objects and frequent occlusions.

[CN] HDST-GNN展示了异构图神经网络在无人机MOT中的强大能力，具有高度自适应图构建和遮挡门控时序聚合。基于GNN的方法在目标小且密集、频繁遮挡的挑战性场景中展现出特别有效的性能。

---

## 五、推荐重点阅读论文 Top 5 / Top 5 Recommended Papers

### Top 1: FEMOT (arXiv 2606.14094)

**推荐理由 / Reason:**

[EN] FEMOT is the most comprehensive contribution this week, providing both a large-scale RGB-Event MOT dataset with 14 challenging attributes and a novel frequency-domain fusion framework (FEMOTR). It addresses the underexplored but important direction of event-camera-based tracking and establishes a solid benchmark for future research. The release of source code and dataset ensures reproducibility.

[CN] FEMOT是本周最全面的贡献，同时提供了包含14种挑战性属性的大规模RGB-事件MOT数据集和创新的频域融合框架（FEMOTR）。它解决了基于事件相机的跟踪这一探索不足但重要的方向，并为未来研究建立了坚实的基准。源代码和数据集的发布确保了可复现性。

### Top 2: TGTrack (CVPR 2026)

**推荐理由 / Reason:**

[EN] TGTrack from CVPR 2026 proposes a novel temporal generative learning paradigm for unified single object tracking. Its ability to unify tracking across different modalities and scenarios through generative modeling represents a potentially transformative shift in how tracking systems are designed — moving from discriminative to generative frameworks.

[CN] TGTrack来自CVPR 2026，提出了一种面向统一单目标跟踪的新型时序生成学习范式。它通过生成式建模统一不同模态和场景下的跟踪能力，代表了跟踪系统设计从判别式到生成式框架的潜在变革性转变。

### Top 3: VLHTrack (arXiv 2606.09167)

**推荐理由 / Reason:**

[EN] VLHTrack is notable for being the first to integrate vision-language models with hyperspectral tracking, using LLM-guided band selection and Mamba-based dynamic template updating. It represents the convergence of three important trends: multimodal fusion, language-guided perception, and state-space modeling, making it a forward-looking contribution.

[CN] VLHTrack的亮点在于首次将视觉-语言模型与高光谱跟踪结合，使用LLM引导的波段选择和基于Mamba的动态模板更新。它体现了三个重要趋势的融合：多模态融合、语言引导感知和状态空间建模，是一项具有前瞻性的贡献。

### Top 4: KATANA (arXiv 2606.14992)

**推荐理由 / Reason:**

[EN] KATANA addresses a critical but often overlooked aspect of tracking — efficient deployment on edge hardware. By achieving the first end-to-end mapping of Kalman filters onto commercial NPUs with 97.9% energy savings, it opens new possibilities for real-time tracking on battery-powered devices. Its practical significance for defense, autonomous driving, and robotics applications is substantial.

[CN] KATANA解决了跟踪中一个关键但常被忽视的方面——边缘硬件上的高效部署。通过首次将卡尔曼滤波器端到端映射到商用NPU并节省97.9%能耗，它为电池供电设备上的实时跟踪开辟了新可能。其在国防、自动驾驶和机器人应用中的实际意义重大。

### Top 5: SAM-Deep-EIoU (arXiv 2606.13033)

**推荐理由 / Reason:**

[EN] SAM-Deep-EIoU elegantly addresses the computational efficiency problem of integrating powerful VOS models into MOT pipelines through a training-free, uncertainty-driven selective dispatch mechanism. Its black-box design means it can benefit from future improvements in both base trackers and VOS models. Achieving state-of-the-art on SportsMOT with 86.8 HOTA demonstrates its practical effectiveness.

[CN] SAM-Deep-EIoU通过无需训练的不确定性驱动选择性调度机制，优雅地解决了将强大VOS模型集成到MOT流程中的计算效率问题。其黑盒设计意味着它可以受益于基础跟踪器和VOS模型的未来改进。在SportsMOT上以86.8 HOTA达到当前最优，证明了其实用有效性。

---

## 六、补充说明 / Supplementary Notes

本报告重点覆盖 2026 年 6 月 11 日至 17 日的论文，同时补充收录了 6 月上旬（6 月 1–10 日）的重要论文以及 CVPR 2026 大会中的跟踪相关工作。由于搜索工具的局限性，可能未能完整覆盖所有相关论文。建议读者持续关注 arXiv cs.CV 分类和主要会议的最新动态。

This report focuses on papers from June 11–17, 2026, while also supplementing with notable papers from early June (June 1–10) and tracking-related work from CVPR 2026. Due to search tool limitations, some relevant papers may not be fully covered. Readers are encouraged to follow arXiv cs.CV and major conference updates for the latest developments.

---

*报告由 QoderWork 自动生成 / Report auto-generated by QoderWork*
