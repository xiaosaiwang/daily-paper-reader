---
title: "eCOMET: An R package for evaluating metabolic diversity and enrichment from LC-MS/MS data to test ecological hypotheses from individuals to ecosystems"
title_zh: eCOMET：一个用于评估LC-MS/MS数据代谢多样性和富集性以检验从个体到生态系统生态假设的R包
authors: "Choi, M.-S., Forrister, D. L., Dury, G. J., Kang, K. B., Sedio, B. E., Joo, Y."
date: 2026-06-05
pdf: "https://www.biorxiv.org/content/10.64898/2026.06.02.729701v1.full.pdf"
tags: ["query:ag-bg-div"]
score: 6.0
evidence: 用于评估代谢多样性的R包，可应用于功能多样性测量
tldr: 生态代谢组学中，多工具输出整合依赖自定义代码形成工作流瓶颈。eCOMET R包将特征元数据、定量表、相似性矩阵和注释整合为统一数据对象，支持多样性、差异度量和差异积累分析。该包简化了工作流，降低了代谢组学在生态学中的应用门槛，有助于检验个体到生态系统尺度的假说。
source: biorxiv
selection_source: fresh_fetch
motivation: 生态代谢组学中多工具输出整合依赖自定义代码，形成工作流瓶颈，阻碍生态学研究者应用代谢组学。
method: eCOMET整合特征元数据、定量表、特征相异矩阵和注释为统一R数据对象，提供多样性和差异度量计算及差分积累分析。
result: 实现了代谢组数据的整合、标准化和统计检验，支持从个体到生态系统尺度的代谢多样性和富集度评估。
conclusion: eCOMET简化了生态代谢组学工作流，降低技术门槛，助力研究者检验生态进化假说。
---

## 摘要
· 代谢组学方法近年来呈指数级增长，为多种植物代谢物的生态功能和进化影响提供了新见解。代谢组学需要掌握众多工具，其输出通常通过内部定制代码进行整合，这构成了工作流程瓶颈，并阻碍了可能从代谢组学视角受益的生态学、进化生物学和行为学研究者的入门。· 我们推出了eCOMET，一个用于整合和协调常见代谢组学生物信息学工具输出，并进行适用于生态代谢组学的统计分析和数据可视化的R包。· 我们的包将代谢组特征元数据与定量表（如mzmine）、特征相异矩阵（如修正余弦和DreaMS）以及特征注释（如SIRIUS）整合到一个统一的R数据对象中，以促进下游分析，包括多样性和差异性指标的计算以及差异积累分析。

## Abstract
{middle dot} Methods in metabolomics have grown exponentially in recent years, providing new insight into the ecological function and evolutionary impact of diverse plant metabolites. Metabolomics requires a command of numerous tools, the outputs of which are typically integrated through in-house, custom code that presents a workflow bottleneck and a barrier to entry for researchers in ecology, evolution, and behavior who may benefit from adding a metabolomics perspective to their research. {middle dot} We introduce eCOMET, an R package for integrating and harmonizing the outputs of common metabolomics bioinformatics tools and conducting statistical analyses and data visualization methods useful for ecological metabolomics. {middle dot} Our package combines metabolome feature metadata with quantification tables (e.g., mzmine), feature dissimilarity matrices (e.g., modified cosine and DreaMS), and feature annotations (e.g., SIRIUS) into a cohesive R data object to facilitate downstream analyses, including the calculation of diversity and disparity metrics and differential accumulation analysis.