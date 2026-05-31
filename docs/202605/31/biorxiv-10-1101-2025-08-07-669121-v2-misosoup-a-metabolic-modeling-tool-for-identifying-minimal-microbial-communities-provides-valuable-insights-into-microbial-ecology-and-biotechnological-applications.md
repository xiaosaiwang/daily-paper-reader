---
title: "misosoup: A metabolic modeling tool for identifying minimal microbial communities provides valuable insights into microbial ecology and biotechnological applications"
title_zh: misosoup：一种用于识别最小微生物群落的代谢建模工具，为微生物生态学和生物技术应用提供宝贵见解
authors: "Ochsner, N., San Roman, M., Jimenez-Fernandez, A., Bonhoeffer, S., Pascual-Garcia, A."
date: 2026-05-25
pdf: "https://www.biorxiv.org/content/10.1101/2025.08.07.669121v2.full.pdf"
tags: ["query:ag-bg-div"]
score: 6.0
evidence: 用于识别最小微生物群落的代谢建模工具
tldr: 微生物生存常依赖代谢相互作用，确定能在特定环境中存活的最小群落对理解生态分布、优化实验室培养及设计合成群落至关重要。为此开发了misosoup工具，通过基因组规模约束代谢建模系统识别最小群落。实验验证其能准确预测已知合作互养关系，应用于海洋微生物组发现交叉喂养驱动生态位扩张。misosoup为微生物生态研究与生物技术创新提供有力支撑。
source: biorxiv
selection_source: fresh_fetch
motivation: 需确定能在特定环境中生存的最小微生物群落，以理解微生物组织、改善培养和设计合成群落。
method: 开发misosoup Python包，基于基因组规模约束代谢建模系统搜索最小群落。
result: 验证预测已知最小群落，应用于60种海洋微生物揭示普遍交叉喂养驱动的生态位扩张。
conclusion: misosoup为微生物生态学和群落设计提供强大工具，兼具研究价值和生物技术应用潜力。
---

## 摘要
微生物的生存和功能往往依赖于群落内的代谢相互作用。因此，解析微生物组织的一个核心问题是确定哪些最小物种组能够在给定培养基中茁壮成长——这些被称为“最小群落”。回答这个问题对于理解微生物分布、加强实验室培养以及设计合成群落（SynComs）至关重要。在此，我们介绍misosoup，一个用于识别最小群落（最小供给群落搜索）的Python包。通过基于约束的全基因组规模代谢建模，misosoup能够系统性地识别在单个物种无法独自生存的环境中支持微生物生长的群落。我们通过实验验证的最小群落对misosoup进行了验证，展示了其预测已知合作相互作用、共培养物和具有生物技术潜力的联合体的能力。我们还通过将misosoup应用于一组60种海洋微生物，进一步说明了其用于探究广泛微生物生态学问题的用途，发现了普遍存在的由交叉喂养驱动的生态位扩展，并展示了misosoup提供的详细输出如何促进对热点话题（如功能群识别）的研究。总之，misosoup为微生物生态学和群落设计提供了一个强大的工具，在研究和生物技术创新中具有潜在应用。

重要性：微生物常常相互依赖才能生存，尤其是在它们无法独自生存的环境中。理解哪些小群微生物能够共同茁壮成长——称为最小群落——对于改进实验室研究、设计合成生态系统以及探索微生物在自然界中的传播至关重要。为此，我们开发了misosoup，这是一个利用先进代谢建模识别这些群落的Python工具。misosoup帮助科学家发现微生物如何通过共享营养物质（这一过程称为代谢交叉喂养）进行合作。当对来自不同来源的物种组进行测试时，该工具显示，物种在作为群体一部分时可以在更多环境中茁壮成长。这凸显了团队合作在微生物生命中的重要性。misosoup不仅能预测这些相互作用，还提供了详细的见解，可以指导生态学研究和生物技术创新。通过揭示微生物如何相互支持，misosoup有助于更深入地理解生命的相互联系，并为解决现实世界挑战提供工具。

## Abstract
Microbial survival and function often depend on metabolic interactions within communities. Therefore, a central question in disentangling microbial organization is determining which minimal groups of species are able to thrive in a given medium - referred to as "minimal communities". Answering this question is essential for understanding microbial distribution, enhancing laboratory cultivation, and designing synthetic communities (SynComs). Here, we introduce misosoup, a Python package for identifying minimal communities (MInimal Supplying community Search). Through genome-scale constraint-based metabolic modeling, misosoup enables the systematic identification of communities that support microbial growth in environments where individual species fail to survive alone. We validate misosoup against experimentally verified minimal communities, demonstrating its ability to predict known cooperative interactions, cocultures, and consortia with biotechnological potential. We further illustrate the use of misosoup to investigate broad microbial ecology questions by applying it to a set of 60 marine microbes, finding pervasive cross-feeding-driven niche expansion, and showing how the detailed outputs provided by misosoup facilitate research on hot topics such as the identification of functional groups. In summary, misosoup provides a powerful tool for microbial ecology and community design, with potential applications in both research and biotechnological innovation.

ImportanceMicrobes often rely on each other to survive, especially in environments where they cant live alone. Understanding which small groups of microbes can thrive together--called minimal communities--is key to improving lab research, designing synthetic ecosystems, and exploring how microbes spread in nature. To support this, we developed misosoup, a Python tool that identifies these communities using advanced metabolic modeling. misosoup helps scientists discover how microbes cooperate by sharing nutrients, a process known as metabolic cross-feeding. When tested on sets of species from different origins, the tool showed that species could thrive in more environments when part of a group. This highlights the importance of teamwork in microbial life. misosoup not only predicts these interactions but also provides detailed insights that can guide ecological studies and biotechnological innovation. By revealing how microbes support each other, misosoup contributes to a deeper understanding of lifes interconnectedness and offers tools for solving real-world challenges.