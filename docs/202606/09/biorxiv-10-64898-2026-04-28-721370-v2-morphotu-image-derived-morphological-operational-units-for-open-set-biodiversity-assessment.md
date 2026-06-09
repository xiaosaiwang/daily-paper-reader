---
title: "MorphOTU: image-derived morphological operational units for open-set biodiversity assessment"
title_zh: MorphOTU：用于开放集生物多样性评估的源自图像的形态操作单元
authors: "Zhan, Z., Ye, M., Orr, M. C., Chen, W., Liu, X., Yue, L., Sun, X., Zhang, F."
date: 2026-06-02
pdf: "https://www.biorxiv.org/content/10.64898/2026.04.28.721370v2.full.pdf"
tags: ["query:ag-bg-div"]
score: 7.0
evidence: 提供从图像推导形态操作单元的方法，可用于功能多样性量化。
tldr: 生物多样性评估面临大量未命名物种难以系统组织的困境。现有分子方法虽能生成OTU但需测序且难关联形态，计算机视觉方法依赖封闭集标签。本文提出MorphOTU，一种基于图像直接构建形态操作单元的开放集框架。在五个标准数据集上，MorphOTU生成的单元接近真实物种分组，即使多数物种未参与训练，仍能准确近似α-多样性。在真实昆虫调查数据上表现鲁棒，且视觉解释聚焦生物性状。该框架为包含未命名物种的生物多样性量化提供了可扩展方案。
source: biorxiv
selection_source: fresh_fetch
motivation: 现有方法难以对未命名物种进行可扩展的形态学组织，缺乏开放集评估框架。
method: 提出MorphOTU，基于图像特征直接构建形态操作单元，无需物种标签，支持开放集。
result: MorphOTU在五个基准数据集和真实昆虫数据上近似物种分组，准确估计多样性，鲁棒且聚焦生物性状。
conclusion: MorphOTU实现基于图像的开放集生物多样性评估，可整合未命名物种，利用大规模数字图像库。
---

## 摘要
缺乏可扩展的系统来组织绝大多数未识别物种是生物多样性科学的一个核心障碍。分子方法可以生成不含物种名的OTU，但需要测序基础设施，并且通常难以与可观察形态联系起来，而大多数计算机视觉方法仍依赖封闭集的物种标签。这些限制阻碍了在真实生态系统开放、不完整条件下对生物多样性的量化。本文提出morphOTU，一种通用的基于图像的框架，直接从表型构建生物多样性操作单元。利用morphOTU，我们在跨越花卉、木材解剖学和甲虫背面习性的五个标准化基准数据集上推导出基于图像的OTU。这些单元紧密逼近参考物种级分组，包括近缘种，在大多数物种“训练时未见”的情况下保持连贯结构，并在稀疏标记或有限采样下准确逼近α-多样性指标。此外，morphOTU在异质、长尾的真实昆虫调查数据集上仍然有效，展示了超越标准化成像条件的稳健性。视觉解释表明，morphOTU持续聚焦于生物学上有意义的性状，并捕捉连续的表型变异。通过提供可扩展的开放集框架来量化表型多样性，morphOTU使得包括未命名物种在内的生物多样性评估成为可能，并释放了快速扩增的数字图像库的生态价值。

## Abstract
The absence of a scalable system for organizing the vast majority of unidentified species is a central obstacle in biodiversity science. Molecular methods can generate OTUs without species names but require sequencing infrastructure and often remain difficult to link to observable morphology, whereas most computer-vision methods still rely on closed-set species labels. These limitations hamper biodiversity quantification under the open, incomplete conditions that characterize real ecosystems. Here, we introduce morphOTUs, a general image-based framework that constructs operational units of biodiversity directly from phenotypes. Using morphOTU, we derive image-based OTUs across five standardized benchmark datasets spanning flowers, wood anatomy, and beetle dorsal habitus. These units closely approximate reference species-level groupings, including closely related species, retain coherent structure when most species are "unseen during training, and accurately approximate -diversity metrics under sparse labeling or limited sampling. Furthermore, morphOTUs remain effective on a heterogeneous, long-tailed real-world insect survey dataset, demonstrating robustness beyond standardized imaging conditions. Visual explanations reveal that morphOTU consistently focuses on biologically meaningful traits and captures continuous phenotypic variation. By providing a scalable and open-set framework for quantifying phenotypic diversity, morphOTUs enable biodiversity assessment that includes unnamed species and unlock the ecological value of rapidly expanding digital image repositories.