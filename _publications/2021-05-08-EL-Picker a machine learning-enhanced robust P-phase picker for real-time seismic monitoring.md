---
title: "EL-Picker: 基于集成学习的余震P波初动实时拾取方法"
collection: publications
permalink: /publication/2021-05-25-Exploiting Real-time Search Engine Queries for Earthquake Detection A Summary of Results
excerpt: '在实时地震监测中, 地震 P 波 (primary wave) 的初动拾取任务具有至关重要的作用, 其有助于 地震应急响应的及时实施. 虽然此前在该领域已开展了大量的研究, 但是如何从地震分布密集并且充 满噪声的监测波形中有效地识别出 P 波仍然是一个具有挑战性的任务. 例如对于大地震的余震监测, 实践中使用的普遍方法仍依赖于专家辅助标注. 本文针对地震实时监测任务, 基于集成学习策略, 提 出一个全新的技术框架 EL-Picker, 实现从连续地震波形中自主拾取 P 波的初动到时. 具体而言, EL-Picker 包含 3 个模块, 即触发器、分类器和精化器. 其中, 分类器模块借鉴集成学习策略, 实现对多 个个体学习器的整合, 提升整体模型性能. 基于汶川 Ms8.0 地震的余震数据集进行的大量实验, 我们 发现 EL-Picker 不仅较好地实现 P 波初动拾取效果, 并且多诊断出 120% 被人工遗漏的地震 P 波. 同 时, 实验结果也启发我们探索如何针对不同的地震站台选取个性化的个体学习器构建分类器模块. 此 外, 我们进一步地讨论了被人工遗漏的地震波形的规律特点, 用于指导人工地震标注. 这些发现清晰 地验证了 EL-Picker 框架的鲁棒性、时效性、灵活性以及稳定性.'
date: 2021-05-08
venue: '《中国科学：信息科学》'
paperurl: 
citation: 'Shen, Dazhong, Qi Zhang, Tong Xu, Hengshu Zhu, Wenjia Zhao, Zikai Yin, Peilun Zhou, Lihua Fang, Enhong Chen, and Hui Xiong. "EL-Picker: 基于集成学习的余震 P 波初动实时拾取方法." Scientia Sinica Informationis 51, no. 6 (2021): 912-926.'
---
在实时地震监测中, 地震 P 波 (primary wave) 的初动拾取任务具有至关重要的作用, 其有助于 地震应急响应的及时实施. 虽然此前在该领域已开展了大量的研究, 但是如何从地震分布密集并且充 满噪声的监测波形中有效地识别出 P 波仍然是一个具有挑战性的任务. 例如对于大地震的余震监测, 实践中使用的普遍方法仍依赖于专家辅助标注. 本文针对地震实时监测任务, 基于集成学习策略, 提 出一个全新的技术框架 EL-Picker, 实现从连续地震波形中自主拾取 P 波的初动到时. 具体而言, EL-Picker 包含 3 个模块, 即触发器、分类器和精化器. 其中, 分类器模块借鉴集成学习策略, 实现对多 个个体学习器的整合, 提升整体模型性能. 基于汶川 Ms8.0 地震的余震数据集进行的大量实验, 我们 发现 EL-Picker 不仅较好地实现 P 波初动拾取效果, 并且多诊断出 120% 被人工遗漏的地震 P 波. 同 时, 实验结果也启发我们探索如何针对不同的地震站台选取个性化的个体学习器构建分类器模块. 此 外, 我们进一步地讨论了被人工遗漏的地震波形的规律特点, 用于指导人工地震标注. 这些发现清晰 地验证了 EL-Picker 框架的鲁棒性、时效性、灵活性以及稳定性.

[Download paper here](https://7-z-7.github.io/files/2021EL-Picker a machine learning-enhanced robust P-phase picker for real-time seismic monitoring.pdf)