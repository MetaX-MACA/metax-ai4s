# AI4S · 沐曦开发者社区

面向生物、医疗、材料、气象与物理等领域的 GPU 加速模型、仿真与开发生态。

**沐曦GPU · AI4S · 科学智能生态**

---

## 📑 快速导航

- [🧬 生物 Biology](#-生物-biology)
- [🏥 医疗 Medical](#-医疗-medical)
- [⚛️ 材料 Materials](#️-材料-materials)
- [🌤️ 气象 Weather](#️-气象-weather)
- [🧊 物理 Physics](#-物理-physics)
- [🔧 环境与依赖](#-环境与依赖)
- [🤝 参与贡献](#-参与贡献)
- [⚖️ 合规声明](#️-合规声明)

---

## 🧬 生物 Biology

> **生命科学 · 蛋白质 · 分子与药物发现**
>
> 主仓库：<https://github.com/MetaX-MACA/LifeScience>

### 已适配模型

| 模型 / 工具 | 类型 | 描述 |
| --- | --- | --- |
| [BioT5+](https://github.com/MetaX-MACA/LifeScience/tree/main/BioT5%2B) | 多模态 | 分子 · 蛋白质 · 反应 |
| [BoltzGen](https://github.com/MetaX-MACA/LifeScience/tree/main/BoltzGen) | 扩散设计 | 针对靶点的结合蛋白生成与排序 |
| [Boltz-2](https://github.com/MetaX-MACA/LifeScience/tree/main/Boltz-2) | 扩散 | 复合物结构 · 亲和力 |
| [DeepFRI](https://github.com/MetaX-MACA/LifeScience/tree/main/DeepFRI) | GCN+LSTM | GO 功能注释 |
| [DiffDock](https://github.com/MetaX-MACA/LifeScience/tree/main/DiffDock) | 扩散 | 小分子-蛋白对接 |
| [OpenFold3](https://github.com/MetaX-MACA/LifeScience/tree/main/OpenFold3) | AlphaFold3 风格 | 全原子生物分子结构预测 |
| [OpenDDE](https://github.com/MetaX-MACA/LifeScience/tree/main/OpenDDE) | 扩散 | 生物分子共折叠与药物设计 |
| [ProteinBert](https://github.com/MetaX-MACA/LifeScience/tree/main/ProteinBert) | BERT | 蛋白质表征 |

### 模型集合

<details>
<summary><strong>ESM3 系列</strong> —— 蛋白质序列、结构与功能生成</summary>

- [ESM3](https://github.com/MetaX-MACA/LifeScience/tree/main/ESM3) —— *生成与补全*：蛋白质序列 · 结构 · 功能
- [ESMC](https://github.com/MetaX-MACA/LifeScience/tree/main/ESM3) —— *蛋白质语言模型*：序列嵌入 · 掩码预测 · 隐藏状态分析
- [ESMFold2](https://github.com/MetaX-MACA/LifeScience/tree/main/ESM3) —— *全原子预测*：蛋白 · DNA/RNA · 配体结构预测

</details>

<details>
<summary><strong>Foundry 系列</strong> —— RF3 · RFD3 · ProteinMPNN 等</summary>

- [RoseTTAFold3 / RF3](https://github.com/MetaX-MACA/LifeScience/tree/main/Foundry) —— *全原子预测*：全原子生物分子结构预测
- [RFdiffusion3 / RFD3](https://github.com/MetaX-MACA/LifeScience/tree/main/Foundry) —— *生成式设计*：结合蛋白 · 酶 · 对称结构设计
- [RFD3NA](https://github.com/MetaX-MACA/LifeScience/tree/main/Foundry) —— *核苷酸扩展*：蛋白-DNA-RNA 多聚体设计
- [ProteinMPNN](https://github.com/MetaX-MACA/LifeScience/tree/main/Foundry) —— *序列设计*：通过全原子结构序列设计
- [LigandMPNN](https://github.com/MetaX-MACA/LifeScience/tree/main/Foundry) —— *序列设计*：通过全原子结构序列设计

</details>

### 更多模型即将发布

<details>
<summary>点击查看完整列表</summary>

| 模型 | 描述 |
| --- | --- |
| Basenji2 | 跨物种调控序列活性预测 |
| BindCraft | 功能蛋白结合剂一键式设计流程 |
| Bonito | 测序电信号数据分析模型 |
| cell2location | 空间转录组细胞类型定位 |
| DyneTrion | 跨时间尺度蛋白质动力学生成模拟 |
| ESM2 | 蛋白质语言模型 |
| Genos | 人类基因组基础模型 |
| LucaOne | 核酸与蛋白统一基础模型 |
| MoFlow | 分子图生成流模型 |
| Nucleotide Transformer (NT) | DNA序列大规模基础模型 |
| OpenFold | AlphaFold2的PyTorch复现，可训练且内存高效 |
| ProtTrans | 蛋白质语言模型 (ProtT5/ProtBert等) |
| SaProt | 结构感知蛋白质语言模型 |
| Uni-Fold | 超越AlphaFold的蛋白质折叠平台，支持单体/多聚体训练 |
| Uni-Mol | 分子模型 |

> ℹ️ 以上模型即将发布，敬请期待。

</details>

---

## 🏥 医疗 Medical

> **医学影像 · 分割 · 配准 · 三维理解 · 病理**
>
> 主仓库：<https://github.com/MetaX-MACA/MedicalImage>

| 模型 / 工具 | 类型 | 描述 |
| --- | --- | --- |
| [MONAI](https://github.com/MetaX-MACA/MedicalImage/tree/main/MONAI) | 框架 | 医学影像深度学习 |
| [MedSAM](https://github.com/MetaX-MACA/MedicalImage/tree/main/segmentation/MedSAM) | 分割 | 可提示通用 2D 分割 |
| [MedSAM2](https://github.com/MetaX-MACA/MedicalImage/tree/main/segmentation/MedSAM2) | 分割 | 可提示通用 3D 分割 |
| [nnInteractive](https://github.com/MetaX-MACA/MedicalImage/tree/main/segmentation/nnInteractive) | 分割 | 3D交互式分割（点/涂抹/框/套索） |
| [nnUNet](https://github.com/MetaX-MACA/MedicalImage/tree/main/segmentation/nnUNet) | 分割 | 自适应 U-Net 框架 |
| [SAM-Med3D](https://github.com/MetaX-MACA/MedicalImage/tree/main/segmentation/SAM-Med3D) | 分割 | 3D 医学图像通用分割 |
| [TotalSegmentatorV2](https://github.com/MetaX-MACA/MedicalImage/tree/main/segmentation/TotalSegmentatorV2) | 分割 | CT 全身 104 结构分割 |
| [VISTA3D](https://github.com/MetaX-MACA/MedicalImage/tree/main/segmentation/vista3d) | 分割 | 可提示 CT/MR 基础模型 |
| [prov-gigapath](https://github.com/MetaX-MACA/MedicalImage/tree/main/pathology/prov-gigapath) | 病理 | 全切片病理基础模型 |

---

## ⚛️ 材料 Materials

> **材料建模 · 分子与原子尺度学习 · 计算材料**
>
> 主仓库：<https://github.com/MetaX-MACA/Materials>

| 模型 / 工具 | 类型 | 描述 |
| --- | --- | --- |
| [ALIGNN](https://github.com/MetaX-MACA/Materials/tree/main/ALIGNN) | 性质预测 | 材料性质预测 |
| [Aviary](https://github.com/MetaX-MACA/Materials/tree/main/Aviary) | 模型库 | 多模型材料发现 |
| [EquiformerV2](https://github.com/MetaX-MACA/Materials/tree/main/EquiformerV2) | 机器学习势 | 催化体系能量与力预测 |
| [MACE](https://github.com/MetaX-MACA/Materials/tree/main/MACE) | 机器学习势 | 原子间势训练与推理 |
| [MatGL](https://github.com/MetaX-MACA/Materials/tree/main/MatGL) | 图深度学习 | 材料图神经网络势函数 |
| [MatRIS](https://github.com/MetaX-MACA/Materials/tree/main/MatRIS) | 机器学习势 | 材料模拟与计算 |
| [MatterGen](https://github.com/MetaX-MACA/Materials/tree/main/MatterGen) | 生成式 AI | 无机材料设计 |
| [MatterSim](https://github.com/MetaX-MACA/Materials/tree/main/MatterSim) | 模拟 | 原子尺度材料模拟 |

### 更多模型即将发布

<details>
<summary>点击查看完整列表</summary>

| 模型 | 描述 |
| --- | --- |
| DeepMD-kit | 深度势能分子动力学套件 |
| MEGNet | 材料图网络，分子/晶体的通用 ML 框架 |
| M3GNet | 含三体相互作用的通用原子间势 |

> ℹ️ 以上模型即将发布，敬请期待。

</details>

---

## 🌤️ 气象 Weather

> **天气与气候 · 数据驱动预报 · 地球系统建模**
>
> 主仓库：<https://github.com/MetaX-MACA/WeatherForecast>

| 模型名称 | 预报时效 | 模型内核 | 推理框架 |
| --- | --- | --- | --- |
| [FourCastNet](https://github.com/MetaX-MACA/WeatherForecast/tree/main/short-range-forecast/FourCastNet) | 短、中期 | 数据驱动 | PyTorch |
| [FourCastNet V2](https://github.com/MetaX-MACA/WeatherForecast/tree/main/short-range-forecast/FourCastNetV2) | 短、中期 | 数据驱动 | PyTorch |
| [Aurora](https://github.com/MetaX-MACA/WeatherForecast/tree/main/short-range-forecast/Aurora) | 中期 | 数据驱动 | PyTorch |
| [GraphCast](https://github.com/MetaX-MACA/WeatherForecast/tree/main/short-range-forecast/GraphCast) | 中期 | 数据驱动 | JAX |
| [GenCast](https://github.com/MetaX-MACA/WeatherForecast/tree/main/short-range-forecast/GenCast) | 中期 | 数据驱动 | JAX |
| [NowcastNet](https://github.com/MetaX-MACA/WeatherForecast/tree/main/nowcasting/NowcastNET) | 临近（3h） | 数据驱动+物理 | PyTorch |

### 更多模型即将发布

<details>
<summary>点击查看完整列表</summary>

| 模型 | 描述 |
| --- | --- |
| FengWu | 风乌气象模型 |
| FengYuan | 中国气象局风源模型 |
| FuXi | 复旦大学伏羲模型 |
| FuXi-S2S | 伏羲次季节-季节尺度延伸期预报 |
| Pangu-Weather | 华为盘古气象大模型 |

> ℹ️ 以上模型即将发布，敬请期待。

</details>

---

## 🧊 物理 Physics

> **面向物理世界的统一计算入口**：覆盖工程物理模型、传统与新型模拟方法，以及 Physics AI 开发框架。
>
> 主仓库：<https://github.com/MetaX-MACA/Physics>

**覆盖领域**：`Fluid` · `Thermal` · `Mechanics` · `Electromagnetics` · `Multiphysics`

### 📦 Models

| 模型 | 描述 |
| --- | --- |
| [DeepCFD](https://github.com/MetaX-MACA/Physics/tree/main/Models/DeepCFD) | 稳态流场代理模型 |
| [GeoPT](https://github.com/MetaX-MACA/Physics/tree/main/Models/GeoPT) | 复杂几何物理建模 |
| [PaddleScience-ModelZoo](https://github.com/MetaX-MACA/Physics/tree/main/Models/PaddleScience-ModelZoo) | 包含 [ANEURYSM](https://github.com/MetaX-MACA/Physics/tree/main/Models/PaddleScience-ModelZoo/ANEURYSM)、[CFD-GCN](https://github.com/MetaX-MACA/Physics/tree/main/Models/PaddleScience-ModelZoo/CFD-GCN)、[DrivAerNet](https://github.com/MetaX-MACA/Physics/tree/main/Models/PaddleScience-ModelZoo/DrivAerNet) 等 |
| [PhysicsNeMo-ModelZoo](https://github.com/MetaX-MACA/Physics/tree/main/Models/PhysicsNeMo-ModelZoo) | 包含 [AeroGraphNet](https://github.com/MetaX-MACA/Physics/tree/main/Models/PhysicsNeMo-ModelZoo/AeroGraphNet)、[DarcyFno](https://github.com/MetaX-MACA/Physics/tree/main/Models/PhysicsNeMo-ModelZoo/DarcyFno)、[DarcyNestedFnos](https://github.com/MetaX-MACA/Physics/tree/main/Models/PhysicsNeMo-ModelZoo/DarcyNestedFnos)、[DarcyTransolver](https://github.com/MetaX-MACA/Physics/tree/main/Models/PhysicsNeMo-ModelZoo/DarcyTransolver)、[Datacenter](https://github.com/MetaX-MACA/Physics/tree/main/Models/PhysicsNeMo-ModelZoo/Datacenter)、[Domino](https://github.com/MetaX-MACA/Physics/tree/main/Models/PhysicsNeMo-ModelZoo/Domino) 等 |

### 🎮 Simulation（即将发布）

| 工具 | 描述 |
| --- | --- |
| Newton | Physics simulation |
| MuJoCo | Physics engine |
| Warp | GPU physics computing |
| CFD | 流体数值模拟 |
| FEM | 结构与多物理场 |

### 🧱 Frameworks

| 框架 | 描述 |
| --- | --- |
| [PhysicsNeMo](https://github.com/MetaX-MACA/Physics/tree/main/Frameworks/PhysicsNeMo) | Physics AI |
| [PaddleScience](https://github.com/MetaX-MACA/Physics/tree/main/Frameworks/PaddleScience) | Scientific ML |
| [DeepXDE](https://github.com/MetaX-MACA/Physics/tree/main/Frameworks/DeepXDE) | PINN / PDE |
| [NeuralOperator](https://github.com/MetaX-MACA/Physics/tree/main/Frameworks/NeuralOperator) | FNO / TFNO |
| [PINA](https://github.com/MetaX-MACA/Physics/tree/main/Frameworks/PINA) | PINNs 框架 |

---

## 🔧 环境与依赖

| 项目 | 说明 |
| --- | --- |
| **硬件** | 沐曦 GPU (曦云C / 曦索X) |
| **OS** | Linux |
| **软件栈** | MXMACA 平台 |
| **框架** | PyTorch / PaddlePaddle / JAX |
| **语言** | Python 3.8+ |

---

## 🤝 参与贡献

- 🔗 **GitHub 组织**：[MetaX-MACA](https://github.com/MetaX-MACA)
- 🐛 **问题反馈**：通过 Issues 反馈问题
- 💻 **代码贡献**：提交 Pull Request
- 💬 **社区讨论**：[加入开发者论坛讨论](https://developer.metax-tech.com/forum/)

---

## ⚖️ 合规声明

在使用各仓库中的任何资源前，请仔细阅读并遵守以下声明：

- **独立项目**：各仓库中的每个子项目均为独立的开源项目，保留其原有的许可证和版权声明。我方仅提供**聚合分发**服务，不对这些项目的功能、安全性或合规性做额外担保。
- **使用责任**：您有责任理解并遵守每个子项目自带的许可证条款。在使用或分发任何子项目时，请确保完全符合其许可证要求。
- **修改与组合**：如子项目内包含由我方提供的 Patch 文件或适配文件，这些特定文件的许可证将放置于对应的子文件夹中，请在使用时一并遵循。

---

<div align="center">

© 沐曦 GPU · AI4S 生态 ｜ [GitHub 组织](https://github.com/MetaX-MACA) ｜ [沐曦开发者社区](https://developer.metax-tech.com/)

</div>