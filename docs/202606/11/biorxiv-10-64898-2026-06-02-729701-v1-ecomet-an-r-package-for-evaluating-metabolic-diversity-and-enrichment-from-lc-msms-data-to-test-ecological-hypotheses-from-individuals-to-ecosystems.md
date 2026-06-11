---
title: "eCOMET: An R package for evaluating metabolic diversity and enrichment from LC-MS/MS data to test ecological hypotheses from individuals to ecosystems"
title_zh: "eCOMET: 一个用于从LC-MS/MS数据评估代谢多样性和富集以检验从个体到生态系统生态假说的R包"
authors: "Choi, M.-S., Forrister, D. L., Dury, G. J., Kang, K. B., Sedio, B. E., Joo, Y."
date: 2026-06-05
pdf: "https://www.biorxiv.org/content/10.64898/2026.06.02.729701v1.full.pdf"
tags: ["query:ag-bg-div"]
score: 6.0
evidence: 代谢多样性分析R包，与植物功能多样性评估相关
tldr: 生态代谢组学研究中，整合多种生物信息学工具的输出存在工作流瓶颈，阻碍了研究者应用。eCOMET R包将特征元数据、量化表、相异矩阵和注释统一为数据对象，支持多样性度量和差异积累分析。该工具降低了代谢组学在生态学、进化和行为学领域的使用门槛，为揭示植物代谢物的生态功能和进化影响提供新途径。
source: biorxiv
selection_source: fresh_fetch
motivation: 代谢组学工具输出整合困难，现有工作流依赖定制代码，限制了生态、进化与行为学领域研究者应用代谢组学。
method: eCOMET整合mzmine、DreaMS、SIRIUS等工具的输出为统一R数据对象，并计算多样性和差异指标。
result: 实现代谢组特征元数据、量化表、相异矩阵和注释的集成，支持生态代谢组学的统计分析与可视化。
conclusion: 使代谢组学更易用于生态学、进化和行为学研究，推动生态代谢组学产生新见解。
---

## 摘要
代谢组学方法近年来呈指数级增长，为多样植物代谢物的生态功能和进化影响提供了新见解。代谢组学需要掌握众多工具，其输出通常通过内部自定义代码整合，这构成了工作流程瓶颈，并阻碍了生态学、进化与行为学领域的研究人员进入，这些研究人员可能从将代谢组学视角添加到他们的研究中获益。我们介绍eCOMET，一个用于整合和协调常见代谢组学生物信息学工具输出，并进行有益于生态代谢组学的统计分析和数据可视化方法的R包。我们的包将代谢组特征元数据与定量表（例如mzmine）、特征不相似性矩阵（例如修正余弦和DreaMS）以及特征注释（例如SIRIUS）结合成一个内聚的R数据对象，以促进下游分析，包括多样性和差异度量的计算以及差异积累分析。我们的目标是使代谢组学更易于生态学、进化与行为学领域的更广泛研究人员使用，以释放生态代谢组学在这些领域产生新洞察的潜力。

## Abstract
O_LIMethods in metabolomics have grown exponentially in recent years, providing new insight into the ecological function and evolutionary impact of diverse plant metabolites. Metabolomics requires a command of numerous tools, the outputs of which are typically integrated through in-house, custom code that presents a workflow bottleneck and a barrier to entry for researchers in ecology, evolution, and behavior who may benefit from adding a metabolomics perspective to their research.
C_LIO_LIWe introduce eCOMET, an R package for integrating and harmonizing the outputs of common metabolomics bioinformatics tools and conducting statistical analyses and data visualization methods useful for ecological metabolomics.
C_LIO_LIOur package combines metabolome feature metadata with quantification tables (e.g., mzmine), feature dissimilarity matrices (e.g., modified cosine and DreaMS), and feature annotations (e.g., SIRIUS) into a cohesive R data object to facilitate downstream analyses, including the calculation of diversity and disparity metrics and differential accumulation analysis.
C_LIO_LIOur goal is to make metabolomics accessible to a wider range of researchers in ecology, evolution, and behavior to unlock the potential of ecological metabolomics to generate novel insight in these fields.
C_LI