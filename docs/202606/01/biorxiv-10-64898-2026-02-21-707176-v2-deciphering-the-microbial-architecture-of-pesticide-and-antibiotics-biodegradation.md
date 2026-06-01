---
title: Deciphering the microbial architecture of pesticide and antibiotics biodegradation
title_zh: 解读农药与抗生素生物降解的微生物架构
authors: "Thieffry, S., Aubert, J., Beguet, J., Devers-Lamrani, M., Martin-Laurent, F., PESCE, S., Romdhane, S., Rouard, N., Siol, M., Spor, A."
date: 2026-06-01
pdf: "https://www.biorxiv.org/content/10.64898/2026.02.21.707176v2.full.pdf"
tags: ["query:ag-bg-div"]
score: 6.0
evidence: 研究微生物功能多样性对降解功能的预测作用，与地下功能多样性效应相关
tldr: 微生物群落的降解功能预测是生物修复的关键。本研究通过自上而下方法获得农药和抗生素降解群落的组成变体，尝试用多样性指数和功能基因丰度作为降解能力的代理，但结果不稳定。进而借用基因组选择的统计模型，基于群落组成预测矿化潜力，发现使用物种存在/缺失数据比相对丰度更有效，随机森林模型也能筛选重要预测因子。最终提出借鉴基因型-表型映射的概念，构建降解功能的微生物架构，为理解群落水平功能提供新视角。
source: biorxiv
selection_source: fresh_fetch
motivation: 理解细菌群落降解农药和抗生素的功能对于微生物生态学和生物修复工程至关重要。
method: 通过自上而下方法获得降解群落组成变体，利用基因组选择统计模型和随机森林预测矿化潜力。
result: 相对丰度预测效果不佳，而存在/缺失数据能提供更清晰的功能信号，随机森林可有效选择预测因子。
conclusion: 建议借鉴基因型-表型映射的概念，构建降解功能的微生物架构以揭示群落水平功能。
---

## 摘要
理解细菌群落层面的新兴功能是微生物生态学的一大挑战，并可能为工程化微生物群落（例如在生物修复中）带来有前景的工具。在这里，通过自上而下的方法，我们获得了农药和抗生素降解群落的组成变体，并进一步研究了与其降解能力相关的群落特征。我们首先测试了多样性指数或功能基因丰度能否可靠地作为该功能的替代指标，并获得了令人鼓舞但多变的结果。进一步地，通过使用来自基因组选择文献的统计工具，我们能够基于细菌群落的组成对其矿化潜力进行准确预测。然而，基因型-表型与群落组成-矿化潜力之间的平行关系存在一个重要缺陷：细菌丰度的变化范围远大于给定基因座上的等位基因剂量，并且容易随时间变化（尤其是在矿化尺度上）。在这里，我们观察到使用存在/缺失数据而非相对丰度可以克服这些限制，并通过线性回归模型为矿化预测提供更清晰的功能信号。随机森林也可以内在处理微生物数据而无需转换，并选择显著的预测因子。我们建议借鉴基因型-表型映射中使用的工具和概念，以在群落水平上阐明微生物功能，同时牢记这两个领域之间的显著差异。这种平行关系在此通过降解功能的微生物架构概念得以体现，类似于表型性状的遗传架构。

## Abstract
Understanding emerging functions at the scale of a bacterial community is a major challenge in microbial ecology and could lead up to promising tools for engineering microbial communities, for example in bioremediation. Here, through a top-down approach we obtained compositional variants of pesticide and antibiotics-degrading communities and further investigated communities features associated with their degradation abilities. We first tested whether diversity index or functional genes abundance could reliably be used as a proxy for this function, and obtained encouraging, albeit variable results. Further, through the use of statistical tools borrowed from the genomic selection literature, we were able to derive accurate prediction of the mineralisation potential of a bacterial community, based on its composition. However, the parallel between genotype-phenotype and community composition-mineralisation potential suffers a crucial caveat: bacterial abundances vary on a much wider scale than allele dosage at a given locus and are prone to change over time (particularly at the mineralisation scale). Here we observed that using presence/absence data instead of relative abundance can overcome these limitations and provide a clearer functional signal for mineralisation prediction through linear regression models. Random forest can also intrinsically deal with microbial data without transformation and select for significant predictors. We suggest drawing inspiration from the tools and concepts used in genotype-phenotype mapping to elucidate microbial functions at the community level while keeping in mind the significant differences between these two fields. This parallel is here exemplified by the concept of microbial architecture of degrading functions, akin to the genetic architecture of phenotypic traits.