# RL-ISP

## Reinforcement Learning-Based Sequential Parameter Tuning for Image Signal Processing

**IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI), 2026**

Xinyu Sun, Bing Li, Congyan Lang, Zhikun Zhao, Juan Wang, Weihua Xiong, Weiming Hu, and Long Cheng

[Paper / 论文](https://ieeexplore.ieee.org/abstract/document/11297856/) · [DOI](https://doi.org/10.1109/TPAMI.2025.3642837) · [Dataset / 数据集](#dataset--数据集) · [Citation / 引用](#citation--引用)

## Overview / 论文介绍

This work formulates hardware image signal processing (ISP) parameter tuning as sequential optimization. **SARL-ISP** learns a single-agent tuning policy, while **MARL-ISP** uses collaborating agents to model interactions between ISP modules. A serialized parameter tuning module (**SPTM**) and a feature selection module (**FSM**) support sequential tuning and feature exchange. Experiments evaluate the methods on downstream tasks including object detection and instance segmentation.

本项目为论文配套仓库，用于整理论文资料、数据集说明及后续代码发布。

## Code / 代码

**代码整理中（Code is being organized）。**

代码及运行说明将在整理完成后更新至本仓库。

## Dataset / 数据集

### Contents / 数据内容

数据集按 Case 组织。计划通过百度网盘发布各 Case 内的以下文件，保留原有 Case 目录名和图像文件名：

| 文件类型 | 内容 |
| --- | --- |
| `.raw` | RAW 格式图像 |
| `.bmp` | BMP 格式图像 |

本次数据发布范围仅包含 RAW 和 BMP 图像，其他类型文件不包含在发布包中。

以下为目录结构示意，`*.raw`、`*.bmp` 表示对应类型文件，并非实际文件名：

```text
DATAS/
├── Case001/
│   ├── *.raw
│   └── *.bmp
├── Case002/
│   ├── *.raw
│   └── *.bmp
└── ...
```

最终 Case 数量、图像数量、数据大小及 RAW 读取参数（如分辨率、位深和 Bayer 排列）将在数据整理完成后补充。图像对应关系和数据划分以正式发布说明为准。

### Download / 下载

完整数据集将通过 **百度网盘（Baidu Netdisk）** 提供，下载信息将在此处更新。

| 项目 | 信息 |
| --- | --- |
| 发布状态 | 数据整理中，尚未开放下载 |
| 百度网盘链接 | 待补充 |
| 提取码 | 待补充 |
| 发布内容 | 各 Case 中的 RAW 和 BMP 图像 |

下载信息更新后，请下载并解压数据包，保留上述目录结构。

## Citation / 引用

如果本论文或数据集对你的研究有帮助，请引用：

```bibtex
@article{sun2026rlisp,
  title   = {Reinforcement Learning-Based Sequential Parameter Tuning for Image Signal Processing},
  author  = {Sun, Xinyu and Li, Bing and Lang, Congyan and Zhao, Zhikun and Wang, Juan and Xiong, Weihua and Hu, Weiming and Cheng, Long},
  journal = {IEEE Transactions on Pattern Analysis and Machine Intelligence},
  year    = {2026},
  volume  = {48},
  number  = {4},
  pages   = {4114--4131},
  doi     = {10.1109/TPAMI.2025.3642837},
  url     = {https://ieeexplore.ieee.org/abstract/document/11297856/}
}
```
