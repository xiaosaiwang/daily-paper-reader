---
title: "Catching the effects of biotic interactions on community data: partial correlations outperform marginal ones with proper abiotic modelling."
title_zh: 捕捉生物相互作用对群落数据的影响：适当非生物建模下，偏相关优于边际相关
authors: "Tous, J., Chiquet, J."
date: 2026-05-22
pdf: "https://www.biorxiv.org/content/10.64898/2026.05.20.726512v1.full.pdf"
tags: ["query:ag-bg-div"]
score: 7.0
evidence: 从群落数据推断生物相互作用的统计方法
tldr: 群落生态学中，联合物种分布模型（JSDM）推断的物种关联网络常被解释为生物相互作用，但二者并不等价。本研究采用VirtualCom模型模拟竞争与促进等相互作用，发现基于部分相关的JSDM比基于边缘相关的JSDM能更准确识别模拟的交互。同时，正确建模非生物效应是识别生物交互的关键，且建模方式需根据交互类型调整。
source: biorxiv
selection_source: fresh_fetch
motivation: 探究不同生物相互作用在群落数据中产生的统计模式，以及如何通过JSDM正确识别这些交互。
method: 使用VirtualCom模型模拟环境过程及竞争/促进交互，分别用部分相关和边缘相关的JSDM推断物种关联，对比识别效果。
result: 部分相关JSDM比边缘相关JSDM更准确捕捉模拟的交互；非生物效应的正确建模对识别生物交互至关重要。
conclusion: 基于部分相关的JSDM结合恰当的非生物效应建模，能更有效推断群落数据中的生物相互作用。
---

## 摘要
群落生态学的一个主要目标在于解析物种分布背后的过程。解决这一问题的一种广泛方法是在物种群落数据中识别模式，并将其与可能的过程联系起来。联合物种分布模型提供了一种通过推断关联网络来实现这一目标的方法，这些网络描述了物种之间的统计相关性和依赖性模式，但目前尚不清楚哪些过程可以解释这种相关性的存在。虽然现在已经确定联合物种分布模型推断的关联与生物相互作用之间并不等价，但后者仍然是前者可能的解释之一。然而，据我们所知，目前尚无专门研究不同类型相互作用所引发的统计模式，也没有研究这些相互作用在何种条件下可能或不可能表现为物种群落中的统计相关性/依赖性。为了探索这些问题，我们提出了一种“虚拟生态学家”方法，该方法通过模拟环境过程以及竞争和促进相互作用效应的VirtualCom模型，基于非生物和生物过程模拟群落数据。然后，我们研究联合物种分布模型在多大程度上能够检索到与模拟相互作用相匹配的物种间相关性。我们表明，当使用模拟物种间偏相关而非边际相关的联合物种分布模型时，这些相互作用更容易被识别。我们进一步证明了正确模拟非生物效应以识别生物效应的重要性，并且这些效应的“正确建模”取决于所涉及的相互作用类型。

## Abstract
A major goal of community ecology lies in the deciphering of the processes underlying species distribution. A widespread approach to this question is to identify patterns in species community data and relate them to possible processes. Joint Species Distribution Models (JS-DMs) offer one way to do so through the infernece of association networks that describe patterns of statistical correlations and dependencies between species, but it is unclear what processes can explain the presence of such correlations. While it has now been established that there is no equivalence between JSDM-inferred associations and biotic interactions, the later remain one possible explanation, among others, for the former. However, to our knowledge, there is no specific study of the statistical patterns induced by different types of interactions or of the conditions under which they may or may not appear as statistical correlations / dependencies in species communities. To explore these questions, we propose a "virtual ecologist" approach that consists in simulating community data based on abiotic and biotic processes with the VirtualCom model that emulates the effects of environmental processes and of competition and facilitation interactions. Then, we study to what extent JSDMs retrieve correlations between species that match the simulated interactions. We show that these interactions are better identified when using JSDMs that model partial correlations between species rather than marginal ones. We further demonstrate how critical it is to correctly model abiotic effects in order to identify biotic ones and that the "correct modelling" of these effects depend on the type of interactions at stake.