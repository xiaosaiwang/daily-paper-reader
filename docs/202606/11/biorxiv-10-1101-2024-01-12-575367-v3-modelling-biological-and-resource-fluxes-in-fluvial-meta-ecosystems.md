---
title: Modelling biological and resource fluxes in fluvial meta-ecosystems
title_zh: 河流元生态系统中生物与资源通量的建模
authors: "Talluto, L., del Campo, R., Estevez, E., Fuss, T., Thuile Bistarelli, L., Martini, J., Singer, G. A."
date: 2026-06-04
pdf: "https://www.biorxiv.org/content/10.1101/2024.01.12.575367v3.full.pdf"
tags: ["query:ag-bg-div"]
score: 6.0
evidence: 跨生态系统资源与生物通量建模
tldr: 河流生态系统中，跨生态系统的能量、养分和生物流动对群落组装和功能至关重要，但现有模型未能同时考虑资源和生物流及其反馈。本文提出一个耦合资源和生物流的数学模型，并开发R包，用于模拟河流网络中的分布动态和反馈作用。计算机实验验证了模型能预测分布并揭示反馈机制。该研究为meta-ecosystem理论在河流中的应用提供了实用工具，促进理解生物多样性与生态系统功能的关联。
source: biorxiv
selection_source: fresh_fetch
motivation: 河流系统中资源和生物流相互依赖，但缺乏同时整合两者的模型，限制了meta-ecosystem理论的应用。
method: 构建耦合资源和生物流的数学框架，开发R语言软件包，模拟河流网络中的扩散、消费与资源传输反馈。
result: 计算机实验成功预测资源和生物沿河流网络的分布，并揭示资源浓度影响生物定殖、生物消费改变资源动态的反馈。
conclusion: 该模型为研究河流meta-ecosystem提供了有效工具，有助于揭示跨生态系统流动对生物多样性和生态系统功能的影响。
---

## 摘要
元生态系统理论预测，能量、营养物质和生物在生态系统间的跨界流动对局域群落构建和生态系统功能具有重要意义。该理论的发展也有望增强我们对生物多样性与生态系统功能关系的理解。元生态系统理论特别适用于河流研究，因为水流迫使相连生态系统之间存在强烈的空间相互关系。然而，目前同时处理资源和生物流动并将其明确联系起来的模型尚缺乏。我们提出了一个用于资源和生物跨界流动的模型及相关的R包，可用于预测它们在河流网络中的分布以及元生态系统功能。该模型整合了这两个关键组成部分之间的反馈——资源浓度代表了生物的生境维度，改变了网络不同地点的定殖和灭绝动态，同时生物也会消耗资源，从而改变向下游输送的浓度。为展示模型能力，我们呈现了一项计算机实验和分析，并提供了示例代码。

## Abstract
Meta-ecosystem theory predicts that cross-ecosystem flows of energy, nutrients, and organisms have important implications for local community assembly and ecosystem functioning. Developments in the theory also have the potential to enhance our understanding of biodiversity-ecosystem functioning relationships. Meta-ecosystem theory is particularly well-suited to the study of rivers, because water flow forces strong spatial interrelationships among connected ecosystems. However, models that address flows of both resources and organisms and explicitly link both are lacking. We present a model and associated R-package for cross-ecosystem flows of both resources and organisms that can be used to predict their distribution in river networks, as well as meta-ecosystem functioning. The model incorporates feedbacks between these two crucial components--resource concentrations represent niche dimensions for organisms, modifying the colonisation and extinction dynamics and different locations in the network, and organisms also consume resources, thereby modifying the concentrations that are transported downstream. To illustrate the capabilities of the model, we present an in silico experiment and analysis, as well as providing sample code.