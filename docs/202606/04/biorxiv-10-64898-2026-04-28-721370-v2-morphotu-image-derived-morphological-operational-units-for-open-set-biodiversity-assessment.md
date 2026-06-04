---
title: "MorphOTU: image-derived morphological operational units for open-set biodiversity assessment"
title_zh: MorphOTU：用于开放集生物多样性评估的影像衍生形态操作单元
authors: "Zhan, Z., Ye, M., Orr, M. C., Chen, W., Liu, X., Yue, L., Sun, X., Zhang, F."
date: 2026-06-02
pdf: "https://www.biorxiv.org/content/10.64898/2026.04.28.721370v2.full.pdf"
tags: ["query:ag-bg-div"]
score: 7.0
evidence: 基于图像的操作单元方法，支持跨营养级功能多样性评估
tldr: 生物多样性科学面临大量未识别物种无法系统组织的障碍。现有分子方法虽能生成操作单元，但需测序且难与形态关联；计算机视觉方法多依赖封闭物种标签，无法处理开放集。本文提出MorphOTU框架，直接从图像表型构建形态操作单元，在5个基准数据集和真实昆虫调查数据上近似物种分组、保持开放集结构、准确估测多样性指标，并关注生物性状。该方法可扩展、开源，支持包含未命名物种的生物多样性评估，挖掘数字图像库的生态价值。
source: biorxiv
selection_source: fresh_fetch
motivation: 现有方法依赖物种名或测序，无法大规模处理未识别物种，亟需基于图像的开放集框架量化表型多样性。
method: 提出MorphOTU，利用图像表型特征直接构建形态操作单元，无需物种标签，适用于开放集场景。
result: 在5个基准数据集上近似物种级分组，保留开放集结构，估测多样性准确，在真实昆虫数据中鲁棒。
conclusion: MorphOTU提供可扩展的开放集框架，使未命名物种纳入评估，释放数字图像资源的生态潜力。
---

## 摘要
缺乏可扩展的系统来组织绝大多数未识别物种是生物多样性科学的一个核心障碍。分子方法可以生成不含物种名称的操作分类单元（OTU），但需要测序基础设施，且通常难以与可观察的形态联系起来，而大多数计算机视觉方法仍然依赖于封闭集的物种标签。这些局限性阻碍了在开放、不完整的条件下（即真实生态系统的特征）进行生物多样性量化。在此，我们引入了morphOTU，这是一种基于图像的通用框架，直接从表型构建生物多样性的操作单元。利用morphOTU，我们在跨越花卉、木材解剖学和甲虫背部栖息地的五个标准化基准数据集上推导出基于图像的OTU。这些单元非常接近参考物种级别的分组，包括密切相关的物种，在大多数物种为“训练中未见”时仍保持连贯结构，并在稀疏标注或有限采样下准确近似α多样性指标。此外，morphOTU在一个异质性、长尾的真实世界昆虫调查数据集上仍然有效，证明了其在标准化成像条件之外的鲁棒性。可视化解释表明，morphOTU始终聚焦于生物学上有意义的性状，并捕捉连续的表型变异。通过提供一个可扩展和开放集的量化表型多样性的框架，morphOTU使得包含未命名物种的生物多样性评估成为可能，并释放了快速扩展的数字图像库的生态价值。

## Abstract
The absence of a scalable system for organizing the vast majority of unidentified species is a central obstacle in biodiversity science. Molecular methods can generate OTUs without species names but require sequencing infrastructure and often remain difficult to link to observable morphology, whereas most computer-vision methods still rely on closed-set species labels. These limitations hamper biodiversity quantification under the open, incomplete conditions that characterize real ecosystems. Here, we introduce morphOTUs, a general image-based framework that constructs operational units of biodiversity directly from phenotypes. Using morphOTU, we derive image-based OTUs across five standardized benchmark datasets spanning flowers, wood anatomy, and beetle dorsal habitus. These units closely approximate reference species-level groupings, including closely related species, retain coherent structure when most species are "unseen during training, and accurately approximate -diversity metrics under sparse labeling or limited sampling. Furthermore, morphOTUs remain effective on a heterogeneous, long-tailed real-world insect survey dataset, demonstrating robustness beyond standardized imaging conditions. Visual explanations reveal that morphOTU consistently focuses on biologically meaningful traits and captures continuous phenotypic variation. By providing a scalable and open-set framework for quantifying phenotypic diversity, morphOTUs enable biodiversity assessment that includes unnamed species and unlock the ecological value of rapidly expanding digital image repositories.