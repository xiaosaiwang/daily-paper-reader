---
title: "MycorrhizaFinder: an efficient machine learning tool to quantify endomycorrhizal colonisation of real-world roots"
title_zh: MycorrhizaFinder：一种高效机器学习工具，用于量化真实世界中根部的内生菌根定殖
authors: "Kowal, J., Upham, R., Buckley, S., Kiani, A., Rickards, M., Serpell, E., Bidartondo, M. I., Evangelisti, E., Schornack, S., Sibbit, J., Treder, K., Weidinger, S., Suz, L. M."
date: 2026-05-25
pdf: "https://www.biorxiv.org/content/10.64898/2026.03.04.709422v3.full.pdf"
tags: ["query:ag-bg-div"]
score: 8.0
evidence: 用于量化根部菌根定殖的机器学习工具
tldr: "根内生菌根真菌定殖评估是菌根研究的重要指标，但传统显微镜方法耗时且难以大规模应用。针对这一问题，本文开发了MycorrhizaFinder，一个基于AI的工具，利用来自多样草地和荒地的根样本训练，可识别丛枝菌根(AM)、欧石楠菌根(ErM)和深色有隔内生真菌(DSE)结构。该工具允许用户自定义置信阈值以处理形态模糊性，在无监督条件下对AM和ErM定殖评估的Macro F1分别达到66%和57%。MycorrhizaFinder无需编程技能，支持用户自定义训练，可推动生态系统中菌根状态的可扩展、可重复监测。"
source: biorxiv
selection_source: fresh_fetch
motivation: 传统显微镜方法评估根内生菌根定殖耗时，难以实现大规模生态监测，亟需高效自动化工具。
method: 训练AI工具MycorrhizaFinder，使用野外根样本涵盖AM、ErM和DSE结构，引入用户自定义置信阈值处理形态模糊性。
result: "无监督基线Macro F1：AM定殖66%，ErM定殖57%。"
conclusion: MycorrhizaFinder易用且无需编程，支持定制训练，适用于不同仪器和染色协议，可促进大规模菌根监测和土地利用变化追踪。
---

## 摘要
摘要
背景与目标：内生菌根真菌对根部的定殖长期以来一直是菌根研究中最常用的指标之一。然而，由于使用传统显微镜技术评估定殖需要大量时间，大规模定殖研究不切实际。基于人工智能的方法可能提高产出并促进生态系统评估。
方法：我们在来自多种草地和石楠地的田间根部上训练了一种人工智能工具（MycorrhizaFinder），这些根部宿主为常见的北欧植物，含有各种丛枝菌根（AM）和欧石楠菌根（ErM）真菌结构，以及田间根部中常见的深色隔膜内生菌（DSE）。我们引入了用户自定义的置信度阈值，以鼓励用户处理不可避免的形态模糊性，例如ErM和DSE。使用宏F1统计量评估工具开发。
结果：我们提供了一个从根部处理和显微镜载玻片扫描到半自动模型训练和性能评估的示例工作流程。在无人监督的情况下，我们的自动基线宏F1对于丛枝菌根定殖评估为66%，对于欧石楠菌根定殖评估为57%。
结论：MycorrhizaFinder用户友好，无需编程技能，并为希望使用自己标记的菌根根部数据集（包括从不同仪器或染色方案获取的图像）训练该工具的高级农学家或生态学家提供了灵活性。这种适应性使用户能够为特定生态系统或实验设计定制模型。结合真菌的分子鉴定和/或功能评估，MycorrhizaFinder可以支持跨生态系统的可扩展和可重复监测，以评估菌根状态并追踪随时间变化的土地利用变化。

## Abstract
AbstractO_ST_ABSBackground and aimsC_ST_ABSRoot colonisation by endomycorrhizal fungi has long been one of the most widely used metrics in mycorrhizal studies. However, due to the significant time required to assess colonisation using traditional microscope techniques, studies of colonisation at large scales are impractical. AI-powered approaches may increase output and facilitate ecosystem assessments.

MethodsWe trained an AI-powered tool (MycorrhizaFinder) on field roots from diverse grasslands and heathlands hosting common Northern European plants with a range of arbuscular (AM) and ericoid mycorrhizal (ErM) fungal structures, and dark septate endophytes (DSE), also common in field-sourced roots. We incorporated a user-customized confidence threshold to encourage the user to engage with inevitable morphological ambiguities, in e.g. ErM and DSE. A Macro F1 statistic was used to assess the tools development.

ResultsWe provide a sample workflow from root processing and microscope slide scanning to semi-automated model training and performance evaluation. Without human supervision, our automated baseline Macro F1 is 66% for arbuscular and at 57% for ericoid mycorrhizal colonisation assessment.

ConclusionMycorrhizaFinder is user friendly, requires no programming skills and offers flexibility for advanced agronomists or ecologists who wish to train the tool using their own labelled mycorrhizal root datasets, including images acquired from different instruments or staining protocols. This adaptability allows users to customize the model for specific ecosystems or experimental designs. Leveraged with molecular identification and/or functional assessment of fungi, MycorrhizaFinder could support scalable and repeatable monitoring across ecosystems to assess mycorrhizal status and track land-use changes over time.

---

## 论文详细总结（自动生成）

好的，以下是根据您提供的论文摘要与元数据信息生成的结构化、客观、深入的中文总结。

### 1. 论文的核心问题与整体含义（研究动机和背景）

- **核心问题**：传统上，评估内生菌根真菌（包括丛枝菌根AM、欧石楠菌根ErM以及深色有隔内生真菌DSE）在植物根部的定殖情况，依赖人工显微镜观察，过程极其耗时费力，导致大规模生态监测和长期追踪研究难以开展。
- **研究动机**：为了突破这一瓶颈，亟需一种高效、可重复且易于推广的自动化方法，以便在区域乃至宏观尺度上评估植物菌根状态，进而支持土地利用变化追踪和生态系统功能研究。
- **整体含义**：该论文旨在开发一个名为 MycorrhizaFinder 的机器学习工具，专门用于量化真实世界（野外采集）根部样本中的内生菌根定殖率，从而为菌根生态学研究提供一种可扩展、可重复的监测方案。

### 2. 论文提出的方法论：核心思想、关键技术细节、算法流程

- **核心思想**：利用深度学习图像识别技术，训练一个能够自动识别和量化根内AM、ErM和DSE结构的模型，并引入用户可自定义的置信度阈值机制，以处理形态学上的模糊性（例如ErM与DSE难以区分的情况）。
- **关键技术细节**：
    - **数据来源**：模型训练数据来自多种北欧草地和石楠地的田间真实根部样本，包含常见宿主植物。
    - **标记结构**：训练数据涵盖了丛枝菌根（AM）、欧石楠菌根（ErM）以及深色有隔内生真菌（DSE）的典型形态结构。
    - **用户自定义阈值**：允许用户调整置信度阈值，从而在准确率和召回率之间做出权衡，适应不同研究场景对假阳性/假阴性的容忍度。
- **算法/工作流程**（根据摘要描述）：
    1.  **根处理与载玻片扫描**：将野外采集的根样本进行清理、染色（按照标准协议），然后使用显微镜自动扫描载玻片，获取全视野数字图像。
    2.  **半自动模型训练**：用户提供一部分已人工标注的根部图像，MycorrhizaFinder利用这些数据训练或微调自身的AI模型。
    3.  **性能评估**：使用宏F1分数（Macro F1）评估模型在多个形态类别上的整体表现。
    4.  **自动定殖评估**：训练好的模型可对新的扫描图像进行自动分析，输出定殖百分比。`（注意：原文未披露具体使用的深度学习架构，如CNN、U-Net或Transformer等）`

### 3. 实验设计：数据集、基准与对比方法

- **数据集与场景**：
    - 使用**野外采集的根部样本**，来自北欧的草地和石楠地，宿主植物为常见北欧物种。这些样本包含了多种菌根结构（AM, ErM, DSE）及其形态变异，代表了“真实世界”的复杂性。
- **基准（Benchmark）**：
    - 论文设定了“自动基线”（Automated Baseline），即在**完全没有人类监督**的条件下，直接由模型输出评估结果。
- **对比方法**：
    - **未明确提及与其他方法对比**。文中没有提到与已有的类似工具（如RootDetector、MycoPatt等）或传统形态学方法进行定量比较。整个实验设计主要是在**自建数据集上，仅报告了模型的绝对表现**。

### 4. 资源与算力

- **未明确说明**。论文摘要及元数据中**没有提及**训练MycorrhizaFinder时所使用的GPU型号、数量、显存、训练时长或计算集群等信息。需要指出，这是该论文在技术报告完整性方面的一个明显缺失。

### 5. 实验数量与充分性

- **实验数量**：论文在正文中仅报告了一个核心结果：在无人类监督条件下，针对AM定殖评估的Macro F1为**66%**，针对ErM定殖评估的Macro F1为**57%**。未明确说明是否进行了消融实验（例如不同阈值的影响、不同数据集分割、不同模型架构对比等）。也未报告交叉验证结果、不同染色方案或不同成像系统的鲁棒性测试。
- **充分性与客观性**：
    - **不充分**。从提供的信息看，实验设计较为单一，缺乏系统地评估模型在不同场景下的泛化能力。仅凭一个Macro F1分数无法全面评判模型的实际应用价值。例如：
        - 未报告精确率（Precision）和召回率（Recall）的单独数值。
        - 未对比“有用户监督”和“无用户监督”两种情况下的性能差异。
        - 未展示模型在不同真菌定殖强度（低、中、高）下的表现。
        - 未与传统的“网格交叉法”等手动定量方法进行时间与精度的对标。
    - **公平性**：由于未与其他现有工具或方法进行公平比较，无法断言MycorrhizaFinder的优越性。不过，其“用户自定义阈值”和“针对真实世界根部训练”的设计思路具有一定的实践意义。

### 6. 论文的主要结论与发现

- **主要发现**：MycorrhizaFinder能够在无人监督的自动模式下，分别以66%和57%的宏F1分数评估AM和ErM定殖，为大规模自动化菌根定殖评估提供了一个可行的起点。
- **结论**：该工具用户友好、无需编程技能，并允许高级用户利用自己标注的数据集进行再训练，以适应不同的成像系统、染色协议或特定生态系统。结合分子鉴定和功能评估，MycorrhizaFinder有望支持跨生态系统的可扩展、可重复监测，用于评估菌根状态和追踪土地利用变化。

### 7. 优点：方法或实验设计上的亮点

- **高度用户友好**：明确声称无需编程技能，降低了AI工具在生物学家和生态学家中的使用门槛。
- **针对真实世界的复杂性**：直接使用野外来源的根部样本（而非实验室培养的干净根部）进行训练，处理了DSE等常见但易混淆的结构。
- **用户自定义置信阈值**：这是一个非常实用的亮点。允许用户根据自身实验对假阳性/假阴性的容忍度来调整模型的判定严苛程度，从而参与到模型决策中，而不是完全黑盒。
- **灵活性**：支持用户用自己的数据（包括不同仪器、不同染色方案）来训练或微调模型，这对于在不同实验室之间推广应用至关重要。

### 8. 不足与局限

- **性能仍有较大提升空间**：66%和57%的Macro F1分数对于实际的高精度定量研究（如细根尺度功能分析）可能不够可靠，存在较高的误判风险。
- **实验设计不充分**：如前所述，缺乏消融实验、泛化实验、与现有方法的对比、以及详细的数据集描述。这限制了结果的科学严谨性和可复现性。
- **形态模糊性未根本解决**：虽然引入了置信阈值，但“ErM与DSE”等模糊性本身存疑，高度依赖用户对阈值的调整，可能引入主观偏差。
- **算力与实现细节缺失**：未提供GPU等信息，其他研究者难以评估其资源需求，也不利于验证与复现。
- **应用限制**：目前仅针对北欧草地和石楠地植物训练，模型对其他地区（如热带、寒带）或其他植物类群的根部定殖评估效果未知。对不同的染色方案（如台盼蓝、墨水染色等）和成像设备（如普通明场显微镜 vs. 共聚焦显微镜）的实际鲁棒性未经验证。

（完）
