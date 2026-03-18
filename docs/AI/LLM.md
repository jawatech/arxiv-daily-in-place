
### LLM
|Publish Date|Title|Authors|Homepage|Code|
| :---: | :---: | :---: | :---: | :---: |
|**2026-03-17**|**TRUST-SQL: Tool-Integrated Multi-Turn Reinforcement Learning for Text-to-SQL over Unknown Schemas**|Ai Jian et.al.|[2603.16448v1](http://arxiv.org/abs/2603.16448v1)|null|
|**2026-03-17**|**Visual Distraction Undermines Moral Reasoning in Vision-Language Models**|Xinyi Yang et.al.|[2603.16445v1](http://arxiv.org/abs/2603.16445v1)|null|
|**2026-03-17**|**Capability-Guided Compression: Toward Interpretability-Aware Budget Allocation for Large Language Models**|Rishaank Gupta et.al.|[2603.16440v1](http://arxiv.org/abs/2603.16440v1)|null|
|**2026-03-17**|**CD-FKD: Cross-Domain Feature Knowledge Distillation for Robust Single-Domain Generalization in Object Detection**|Junseok Lee et.al.|[2603.16439v1](http://arxiv.org/abs/2603.16439v1)|null|
|**2026-03-17**|**VQKV: High-Fidelity and High-Ratio Cache Compression via Vector-Quantization**|Yixuan Wang et.al.|[2603.16435v1](http://arxiv.org/abs/2603.16435v1)|null|

#### Abstracts
##### **TRUST-SQL: Tool-Integrated Multi-Turn Reinforcement Learning for Text-to-SQL over Unknown Schemas**
2603.16448v1 by Ai Jian, Xiaoyun Zhang, Wanrou Du, Jingqing Ruan, Jiangbo Pei, Weipeng Zhang, Ke Zeng, Xunliang Cai

Text-to-SQL parsing has achieved remarkable progress under the Full Schema Assumption. However, this premise fails in real-world enterprise environments where databases contain hundreds of tables with massive noisy metadata. Rather than injecting the full schema upfront, an agent must actively identify and verify only the relevant subset, giving rise to the Unknown Schema scenario we study in this work. To address this, we propose TRUST-SQL (Truthful Reasoning with Unknown Schema via Tools). We formulate the task as a Partially Observable Markov Decision Process where our autonomous agent employs a structured four-phase protocol to ground reasoning in verified metadata. Crucially, this protocol provides a structural boundary for our novel Dual-Track GRPO strategy. By applying token-level masked advantages, this strategy isolates exploration rewards from execution outcomes to resolve credit assignment, yielding a 9.9% relative improvement over standard GRPO. Extensive experiments across five benchmarks demonstrate that TRUST-SQL achieves an average absolute improvement of 30.6% and 16.6% for the 4B and 8B variants respectively over their base models. Remarkably, despite operating entirely without pre-loaded metadata, our framework consistently matches or surpasses strong baselines that rely on schema prefilling.

摘要：

##### **Visual Distraction Undermines Moral Reasoning in Vision-Language Models**
2603.16445v1 by Xinyi Yang, Chenheng Xu, Weijun Hong, Ce Mo, Qian Wang, Fang Fang, Yixin Zhu

Moral reasoning is fundamental to safe Artificial Intelligence (AI), yet ensuring its consistency across modalities becomes critical as AI systems evolve from text-based assistants to embodied agents. Current safety techniques demonstrate success in textual contexts, but concerns remain about generalization to visual inputs. Existing moral evaluation benchmarks rely on textonly formats and lack systematic control over variables that influence moral decision-making. Here we show that visual inputs fundamentally alter moral decision-making in state-of-the-art (SOTA) Vision-Language Models (VLMs), bypassing text-based safety mechanisms. We introduce Moral Dilemma Simulation (MDS), a multimodal benchmark grounded in Moral Foundation Theory (MFT) that enables mechanistic analysis through orthogonal manipulation of visual and contextual variables. The evaluation reveals that the vision modality activates intuition-like pathways that override the more deliberate and safer reasoning patterns observed in text-only contexts. These findings expose critical fragilities where language-tuned safety filters fail to constrain visual processing, demonstrating the urgent need for multimodal safety alignment.

摘要：

##### **Capability-Guided Compression: Toward Interpretability-Aware Budget Allocation for Large Language Models**
2603.16440v1 by Rishaank Gupta

Large language model compression has made substantial progress through pruning, quantization, and low-rank decomposition, yet a fundamental limitation persists across all existing methods: compression budgets are allocated without any representation of what individual model components functionally encode. We term this the capability-blind compression problem and argue it is a root cause of two well-documented failures -- the insensitivity of perplexity-based evaluation to reasoning capability loss, and the abrupt phase transitions in model performance recently characterized by Ma et al. (2026). We propose Capability-Guided Compression (CGC), a framework that addresses this by using Sparse Autoencoder (SAE)-derived capability density maps to allocate differential compression budgets across transformer components. Capability density is a formally defined scalar measure combining the feature breadth, activation entropy, and cross-input consistency of a component's SAE feature activation distribution. We prove theoretically that components with higher capability density exhibit lower structural redundancy and reach their individual phase transition points at lower compression ratios, providing the first pre-compression mechanism for component-level phase transition prediction. Experiments on GPT-2 Medium confirm that capability density is statistically independent of Wanda importance scores (Spearman rho = -0.054, n = 384 heads), establishing it as a genuinely novel compression signal orthogonal to all existing importance metrics. We report a negative result on PPL-based compression comparison and provide a principled diagnosis identifying GPT-2 Medium as an insufficient test bed for the full CGC hypothesis. The theoretical framework, density formalism, and orthogonality finding constitute a foundation for capability-aware compression research.

摘要：

##### **CD-FKD: Cross-Domain Feature Knowledge Distillation for Robust Single-Domain Generalization in Object Detection**
2603.16439v1 by Junseok Lee, Sungho Shin, Seongju Lee, Kyoobin Lee

Single-domain generalization is essential for object detection, particularly when training models on a single source domain and evaluating them on unseen target domains. Domain shifts, such as changes in weather, lighting, or scene conditions, pose significant challenges to the generalization ability of existing models. To address this, we propose Cross-Domain Feature Knowledge Distillation (CD-FKD), which enhances the generalization capability of the student network by leveraging both global and instance-wise feature distillation. The proposed method uses diversified data through downscaling and corruption to train the student network, whereas the teacher network receives the original source domain data. The student network mimics the features of the teacher through both global and instance-wise distillation, enabling it to extract object-centric features effectively, even for objects that are difficult to detect owing to corruption. Extensive experiments on challenging scenes demonstrate that CD-FKD outperforms state-of-the-art methods in both target domain generalization and source domain performance, validating its effectiveness in improving object detection robustness to domain shifts. This approach is valuable in real-world applications, like autonomous driving and surveillance, where robust object detection in diverse environments is crucial.

摘要：

##### **VQKV: High-Fidelity and High-Ratio Cache Compression via Vector-Quantization**
2603.16435v1 by Yixuan Wang, Qingyu Shi, Jiayu Zhou, Dianbo Liu, Ziwei He, Zhouhan Lin

The growing context length of Large Language Models (LLMs) enlarges the Key-Value (KV) cache, limiting deployment in resource-limited environments. Prior training-free approaches for KV cache compression typically rely on low-rank approximation or scalar quantization, which fail to simultaneously achieve high compression ratios and high reconstruction fidelity. We propose VQKV, a novel, training-free method introducing vector quantization (VQ) to obtain highly compressed KV representations while preserving high model fidelity, allowing for the representation of thousands of floating-point values with just a few integer indices. As a result, VQKV achieves an 82.8\% compression ratio on LLaMA3.1-8B while retaining 98.6\% of the baseline performance on LongBench and enabling 4.3x longer generation length on the same memory footprint.

摘要：

