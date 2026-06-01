---
title: "Beyond the annotated: protein foundation models enable robust prediction of microbial root competence"
title_zh: 超越注释：蛋白质基础模型实现对微生物根系定殖能力的稳健预测
authors: "Matyskova, P., Selten, G., Pieterse, C. M., Abeln, S., de Jonge, R."
date: 2026-05-26
pdf: "https://www.biorxiv.org/content/10.64898/2026.05.22.727091v1.full.pdf"
tags: ["query:ag-bg-div"]
score: 6.0
evidence: 蛋白质基础模型预测微生物根系定殖能力，这是一个关键的地下功能性状
tldr: 根能力是土壤细菌定殖植物根的关键生态性状。传统基于注释或序列聚类的方法受限于注释偏见和特征维度过高，难以跨进化远缘细菌泛化。本研究对比了蛋白/ DNA基础模型（ESM-2、Bacformer、DNABERT-S）与传统方法，发现只有预训练蛋白序列表示在测试菌属于训练集完全未见门类时仍保持预测性能，其中Bacformer因整合基因组上下文最强。特征归因揭示TonB/SusD受体、小分子转运蛋白及未注释蛋白对根能力重要。
source: biorxiv
selection_source: fresh_fetch
motivation: 传统基于注释或聚类的方法对未充分研究细菌有偏差，且特征维度过高，限制了模型在远缘细菌中的泛化能力。
method: 使用蛋白和DNA基础模型（ESM-2、Bacformer、DNABERT-S）以及注释/聚类特征（KEGG、OrthoFinder），在拟南芥微生物组数据上预测根能力。
result: 当测试菌与训练菌进化远缘时，仅预训练蛋白表示（尤其Bacformer）保持高性能；特征归因锁定TonB/SusD受体、小分子转运蛋白及未知蛋白。
conclusion: 蛋白基础模型支持跨远缘细菌的泛化，并能鉴定未知的根能力决定因子，推动微生物生态预测。
---

## 摘要
背景根系定殖能力，即土壤细菌在植物根系上定殖和生长的能力，是影响植物营养、生长和健康的关键生态特征。然而，跨细菌鉴定根系定殖的基因组决定因素仍然具有挑战性，部分原因是模型的泛化能力强烈依赖于基因组表示方式。基于人工注释的传统方法不完整且偏向于特征明确的生物体和功能，限制了泛化能力。序列相似性聚类提高了覆盖度，但相对于数据集大小产生了高维特征，阻碍了训练。基础模型通过学习紧凑表示而不依赖先验注释，提供了一种替代方案。

结果在这里，我们使用来自拟南芥的合成微生物群落数据，比较了蛋白质和DNA基础模型（ESM-2、Bacformer、DNABERT-S）的预训练基因组表示与基于注释和聚类的特征（KEGG orthology、OrthoFinder蛋白质家族）在预测根系定殖能力方面的表现，并评估了跨细菌的泛化能力。当训练集和测试集包含分类学相关的细菌时，大多数方法表现相似。然而，当测试细菌属于训练中完全不存在的门类时，反映了所有细菌分类水平上的高度进化分离，只有预训练的蛋白质表示保留了预测性能。Bacformer衍生的表示整合了基因组上下文，支持最强的泛化能力，表明保守的基因组组织有助于预测根系定殖。特征归因量化了蛋白质对模型决策的贡献，将根系定殖与TonB/SusD依赖性受体、小分子转运蛋白以及具有保守调控基序和与碳饥饿响应位点同源性的未注释蛋白质联系起来。

结论蛋白质基础模型支持跨进化远缘细菌的泛化，并鉴定了根系定殖的基因组决定因素，包括未注释的蛋白质。

## Abstract
BackgroundRoot competence, the ability of soil bacteria to establish and grow on plant roots, is a key ecological trait influencing plant nutrition, growth, and health. However, identifying genomic determinants of root competence across bacteria remains challenging, in part because model generalisability depends strongly on how genomes are represented. Traditional approaches based on curated annotations are incomplete and biased toward well-characterised organisms and functions, limiting generalisation. Sequence-similarity clustering improves coverage but yields high-dimensional features relative to dataset size, hindering training. Foundation models offer an alternative by learning com-pact representations without relying on prior annotation.

ResultsHere, we compared pretrained genome representations from protein and DNA foundation models (ESM-2, Bacformer, DNABERT-S) with annotation- and clustering-based features (KEGG orthology, OrthoFinder protein families) for predicting root competence using synthetic microbial community data from Arabidop-sis thaliana and assessed generalisability across bacteria. When training and test sets contained taxonomically related bacteria, most approaches performed similarly. However, when test bacteria belonged to phyla entirely absent from training, reflecting high evolutionary separation across all levels of bacterial classification, only pretrained protein representations retained predictive performance. Bacformer-derived representations, which incorporate genomic context, supported the strongest generalisation, suggesting that conserved genomic organisation contributes to predicting root competence. Feature attribution quantifying protein contributions to model decisions linked root competence to TonB/SusD-dependent receptors, small-molecule transporters, and unannotated proteins with conserved regulatory motifs and homology to carbon starvation-response loci.

ConclusionsProtein foundation models support generalisation across evolutionarily distant bacteria and identify genomic determinants of root competence, including unannotated proteins.