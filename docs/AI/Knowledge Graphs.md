
### Knowledge Graphs
|Publish Date|Title|Authors|Homepage|Code|
| :---: | :---: | :---: | :---: | :---: |
|**2026-03-16**|**OpenSeeker: Democratizing Frontier Search Agents by Fully Open-Sourcing Training Data**|Yuwen Du et.al.|[2603.15594v1](http://arxiv.org/abs/2603.15594v1)|null|
|**2026-03-16**|**Lore: Repurposing Git Commit Messages as a Structured Knowledge Protocol for AI Coding Agents**|Ivan Stetsenko et.al.|[2603.15566v1](http://arxiv.org/abs/2603.15566v1)|null|
|**2026-03-16**|**Can LLMs Model Incorrect Student Reasoning? A Case Study on Distractor Generation**|Yanick Zengaffinen et.al.|[2603.15547v1](http://arxiv.org/abs/2603.15547v1)|null|
|**2026-03-16**|**InterveneBench: Benchmarking LLMs for Intervention Reasoning and Causal Study Design in Real Social Systems**|Shaojie Shi et.al.|[2603.15542v1](http://arxiv.org/abs/2603.15542v1)|null|
|**2026-03-16**|**DOT: Dynamic Knob Selection and Online Sampling for Automated Database Tuning**|Yifan Wang et.al.|[2603.15540v1](http://arxiv.org/abs/2603.15540v1)|null|

#### Abstracts
##### **OpenSeeker: Democratizing Frontier Search Agents by Fully Open-Sourcing Training Data**
2603.15594v1 by Yuwen Du, Rui Ye, Shuo Tang, Xinyu Zhu, Yijun Lu, Yuzhu Cai, Siheng Chen

Deep search capabilities have become an indispensable competency for frontier Large Language Model (LLM) agents, yet the development of high-performance search agents remains dominated by industrial giants due to a lack of transparent, high-quality training data. This persistent data scarcity has fundamentally hindered the progress of the broader research community in developing and innovating within this domain. To bridge this gap, we introduce OpenSeeker, the first fully open-source search agent (i.e., model and data) that achieves frontier-level performance through two core technical innovations: (1) Fact-grounded scalable controllable QA synthesis, which reverse-engineers the web graph via topological expansion and entity obfuscation to generate complex, multi-hop reasoning tasks with controllable coverage and complexity. (2) Denoised trajectory synthesis, which employs a retrospective summarization mechanism to denoise the trajectory, therefore promoting the teacher LLMs to generate high-quality actions. Experimental results demonstrate that OpenSeeker, trained (a single training run) on only 11.7k synthesized samples, achieves state-of-the-art performance across multiple benchmarks including BrowseComp, BrowseComp-ZH, xbench-DeepSearch, and WideSearch. Notably, trained with simple SFT, OpenSeeker significantly outperforms the second-best fully open-source agent DeepDive (e.g., 29.5% v.s. 15.3% on BrowseComp), and even surpasses industrial competitors such as Tongyi DeepResearch (trained via extensive continual pre-training, SFT, and RL) on BrowseComp-ZH (48.4% v.s. 46.7%). We fully open-source the complete training dataset and the model weights to democratize frontier search agent research and foster a more transparent, collaborative ecosystem.

摘要：

##### **Lore: Repurposing Git Commit Messages as a Structured Knowledge Protocol for AI Coding Agents**
2603.15566v1 by Ivan Stetsenko

As AI coding agents become both primary producers and consumers of source code, the software industry faces an accelerating loss of institutional knowledge. Each commit captures a code diff but discards the reasoning behind it - the constraints, rejected alternatives, and forward-looking context that shaped the decision. I term this discarded reasoning the Decision Shadow. This paper proposes Lore, a lightweight protocol that restructures commit messages - using native git trailers - into self-contained decision records carrying constraints, rejected alternatives, agent directives, and verification metadata. Lore requires no infrastructure beyond git, is queryable via a standalone CLI tool, and is discoverable by any agent capable of running shell commands. The paper formalizes the protocol, compares it against five competing approaches, stress-tests it against its strongest objections, and outlines an empirical validation path.

摘要：

##### **Can LLMs Model Incorrect Student Reasoning? A Case Study on Distractor Generation**
2603.15547v1 by Yanick Zengaffinen, Andreas Opedal, Donya Rooein, Kv Aditya Srivatsa, Shashank Sonkar, Mrinmaya Sachan

Modeling plausible student misconceptions is critical for AI in education. In this work, we examine how large language models (LLMs) reason about misconceptions when generating multiple-choice distractors, a task that requires modeling incorrect yet plausible answers by coordinating solution knowledge, simulating student misconceptions, and evaluating plausibility. We introduce a taxonomy for analyzing the strategies used by state-of-the-art LLMs, examining their reasoning procedures and comparing them to established best practices in the learning sciences. Our structured analysis reveals a surprising alignment between their processes and best practices: the models typically solve the problem correctly first, then articulate and simulate multiple potential misconceptions, and finally select a set of distractors. An analysis of failure modes reveals that errors arise primarily from failures in recovering the correct solution and selecting among response candidates, rather than simulating errors or structuring the process. Consistent with these results, we find that providing the correct solution in the prompt improves alignment with human-authored distractors by 8%, highlighting the critical role of anchoring to the correct solution when generating plausible incorrect student reasoning. Overall, our analysis offers a structured and interpretable lens into LLMs' ability to model incorrect student reasoning and produce high-quality distractors.

摘要：

##### **InterveneBench: Benchmarking LLMs for Intervention Reasoning and Causal Study Design in Real Social Systems**
2603.15542v1 by Shaojie Shi, Zhengyu Shi, Lingran Zheng, Xinyu Su, Anna Xie, Bohao Lv, Rui Xu, Zijian Chen, Zhichao Chen, Guolei Liu, Naifu Zhang, Mingjian Dong, Zhuo Quan, Bohao Chen, Teqi Hao, Yuan Qi, Yinghui Xu, Libo Wu

Causal inference in social science relies on end-to-end, intervention-centered research-design reasoning grounded in real-world policy interventions, but current benchmarks fail to evaluate this capability of large language models (LLMs). We present InterveneBench, a benchmark designed to assess such reasoning in realistic social settings. Each instance in InterveneBench is derived from an empirical social science study and requires models to reason about policy interventions and identification assumptions without access to predefined causal graphs or structural equations. InterveneBench comprises 744 peer-reviewed studies across diverse policy domains. Experimental results show that state-of-the-art LLMs struggle under this setting. To address this limitation, we further propose a multi-agent framework, STRIDES. It achieves significant performance improvements over state-of-the-art reasoning models. Our code and data are available at https://github.com/Sii-yuning/STRIDES.

摘要：

##### **DOT: Dynamic Knob Selection and Online Sampling for Automated Database Tuning**
2603.15540v1 by Yifan Wang, Debabrota Basu, Pierre Bourhis, Romain Rouvoy, Patrick Royer

Database Management Systems (DBMS) are crucial for efficient data management and access control, but their administration remains challenging for Database Administrators (DBAs). Tuning, in particular, is known to be difficult. Modern systems have many tuning parameters, but only a subset significantly impacts performance. Focusing on these influential parameters reduces the search space and optimizes performance. Current methods rely on costly warm-up phases and human expertise to identify important tuning parameters. In this paper, we present DOT, a dynamic knob selection and online sampling DBMS tuning algorithm. DOT uses Recursive Feature Elimination with Cross-Validation (RFECV) to prune low-importance tuning parameters and a Likelihood Ratio Test (LRT) strategy to balance exploration and exploitation. For parameter search, DOT uses a Bayesian Optimization (BO) algorithm to optimize configurations on-the-fly, eliminating the need for warm-up phases or prior knowledge (although existing knowledge can be incorporated). Experiments show that DOT achieves matching or outperforming performance compared to state-of-the-art tuners while substantially reducing tuning overhead.

摘要：

