# arxiv-daily
 Automated deployment @ 2026-03-17 21:03:25 Asia/Taipei
> Welcome to contribute! Add your topics and keywords in [`topic.yml`](https://github.com/jawatech/arxiv-daily-in-place/blob/main/database/topic.yml).
> You can also view historical data through the [storage](https://github.com/jawatech/arxiv-daily-in-place/blob/main/database/storage).

## AI

### LLM
|Publish Date|Title|Authors|Homepage|Code|
| :---: | :---: | :---: | :---: | :---: |
|**2026-03-16**|**Mixture-of-Depths Attention**|Lianghui Zhu et.al.|[2603.15619v1](http://arxiv.org/abs/2603.15619v1)|null|
|**2026-03-16**|**Mechanistic Origin of Moral Indifference in Language Models**|Lingyu Li et.al.|[2603.15615v1](http://arxiv.org/abs/2603.15615v1)|null|
|**2026-03-16**|**Code-A1: Adversarial Evolving of Code LLM and Test LLM via Reinforcement Learning**|Aozhe Wang et.al.|[2603.15611v1](http://arxiv.org/abs/2603.15611v1)|null|
|**2026-03-16**|**Do Metrics for Counterfactual Explanations Align with User Perception?**|Felix Liedeker et.al.|[2603.15607v1](http://arxiv.org/abs/2603.15607v1)|null|
|**2026-03-16**|**From Passive Observer to Active Critic: Reinforcement Learning Elicits Process Reasoning for Robotic Manipulation**|Yibin Liu et.al.|[2603.15600v1](http://arxiv.org/abs/2603.15600v1)|null|

#### Abstracts
##### **Mixture-of-Depths Attention**
2603.15619v1 by Lianghui Zhu, Yuxin Fang, Bencheng Liao, Shijie Wang, Tianheng Cheng, Zilong Huang, Chen Chen, Lai Wei, Yutao Zeng, Ya Wang, Yi Lin, Yu Li, Xinggang Wang

Scaling depth is a key driver for large language models (LLMs). Yet, as LLMs become deeper, they often suffer from signal degradation: informative features formed in shallow layers are gradually diluted by repeated residual updates, making them harder to recover in deeper layers. We introduce mixture-of-depths attention (MoDA), a mechanism that allows each attention head to attend to sequence KV pairs at the current layer and depth KV pairs from preceding layers. We further describe a hardware-efficient algorithm for MoDA that resolves non-contiguous memory-access patterns, achieving 97.3% of FlashAttention-2's efficiency at a sequence length of 64K. Experiments on 1.5B-parameter models demonstrate that MoDA consistently outperforms strong baselines. Notably, it improves average perplexity by 0.2 across 10 validation benchmarks and increases average performance by 2.11% on 10 downstream tasks, with a negligible 3.7% FLOPs computational overhead. We also find that combining MoDA with post-norm yields better performance than using it with pre-norm. These results suggest that MoDA is a promising primitive for depth scaling. Code is released at https://github.com/hustvl/MoDA .

摘要：

##### **Mechanistic Origin of Moral Indifference in Language Models**
2603.15615v1 by Lingyu Li, Yan Teng, Yingchun Wang

Existing behavioral alignment techniques for Large Language Models (LLMs) often neglect the discrepancy between surface compliance and internal unaligned representations, leaving LLMs vulnerable to long-tail risks. More crucially, we posit that LLMs possess an inherent state of moral indifference due to compressing distinct moral concepts into uniform probability distributions. We verify and remedy this indifference in LLMs' latent representations, utilizing 251k moral vectors constructed upon Prototype Theory and the Social-Chemistry-101 dataset. Firstly, our analysis across 23 models reveals that current LLMs fail to represent the distinction between opposed moral categories and fine-grained typicality gradients within these categories; notably, neither model scaling, architecture, nor explicit alignment reshapes this indifference. We then employ Sparse Autoencoders on Qwen3-8B, isolate mono-semantic moral features, and targetedly reconstruct their topological relationships to align with ground-truth moral vectors. This representational alignment naturally improves moral reasoning and granularity, achieving a 75% pairwise win-rate on the independent adversarial Flames benchmark. Finally, we elaborate on the remedial nature of current intervention methods from an experientialist philosophy, arguing that endogenously aligned AI might require a transformation from post-hoc corrections to proactive cultivation.

摘要：

##### **Code-A1: Adversarial Evolving of Code LLM and Test LLM via Reinforcement Learning**
2603.15611v1 by Aozhe Wang, Yuchen Yan, Nan Zhou, Zhengxi Lu, Weiming Lu, Jun Xiao, Yueting Zhuang, Yongliang Shen

Reinforcement learning for code generation relies on verifiable rewards from unit test pass rates. Yet high-quality test suites are scarce, existing datasets offer limited coverage, and static rewards fail to adapt as models improve. Recent self-play methods unify code and test generation in a single model, but face a inherent dilemma: white-box access leads to self-collusion where the model produces trivial tests for easy rewards, yet black-box restriction yields generic tests that miss implementation-specific bugs. We introduce Code-A1, an adversarial co-evolution framework that jointly optimizes a Code LLM and a Test LLM with opposing objectives. The Code LLM is rewarded for passing more tests, while the Test LLM is rewarded for exposing more defects. This architectural separation eliminates self-collusion risks and safely enables white-box test generation, where the Test LLM can inspect candidate code to craft targeted adversarial tests. We further introduce a Mistake Book mechanism for experience replay and a composite reward balancing test validity with adversarial difficulty. Experiments on Qwen2.5-Coder models demonstrate that Code-A1 achieves code generation performance matching or exceeding models trained on human-annotated tests, while significantly improving test generation capability.

摘要：

##### **Do Metrics for Counterfactual Explanations Align with User Perception?**
2603.15607v1 by Felix Liedeker, Basil Ell, Philipp Cimiano, Christoph Düsing

Explainability is widely regarded as essential for trustworthy artificial intelligence systems. However, the metrics commonly used to evaluate counterfactual explanations are algorithmic evaluation metrics that are rarely validated against human judgments of explanation quality. This raises the question of whether such metrics meaningfully reflect user perceptions. We address this question through an empirical study that directly compares algorithmic evaluation metrics with human judgments across three datasets. Participants rated counterfactual explanations along multiple dimensions of perceived quality, which we relate to a comprehensive set of standard counterfactual metrics. We analyze both individual relationships and the extent to which combinations of metrics can predict human assessments. Our results show that correlations between algorithmic metrics and human ratings are generally weak and strongly dataset-dependent. Moreover, increasing the number of metrics used in predictive models does not lead to reliable improvements, indicating structural limitations in how current metrics capture criteria relevant for humans. Overall, our findings suggest that widely used counterfactual evaluation metrics fail to reflect key aspects of explanation quality as perceived by users, underscoring the need for more human-centered approaches to evaluating explainable artificial intelligence.

摘要：

##### **From Passive Observer to Active Critic: Reinforcement Learning Elicits Process Reasoning for Robotic Manipulation**
2603.15600v1 by Yibin Liu, Yaxing Lyu, Daqi Gao, Zhixuan Liang, Weiliang Tang, Shilong Mu, Xiaokang Yang, Yao Mu

Accurate process supervision remains a critical challenge for long-horizon robotic manipulation. A primary bottleneck is that current video MLLMs, trained primarily under a Supervised Fine-Tuning (SFT) paradigm, function as passive "Observers" that recognize ongoing events rather than evaluating the current state relative to the final task goal. In this paper, we introduce PRIMO R1 (Process Reasoning Induced Monitoring), a 7B framework that transforms video MLLMs into active "Critics". We leverage outcome-based Reinforcement Learning to incentivize explicit Chain-of-Thought generation for progress estimation. Furthermore, our architecture constructs a structured temporal input by explicitly anchoring the video sequence between initial and current state images. Supported by the proposed PRIMO Dataset and Benchmark, extensive experiments across diverse in-domain environments and out-of-domain real-world humanoid scenarios demonstrate that PRIMO R1 achieves state-of-the-art performance. Quantitatively, our 7B model achieves a 50% reduction in the mean absolute error of specialized reasoning baselines, demonstrating significant relative accuracy improvements over 72B-scale general MLLMs. Furthermore, PRIMO R1 exhibits strong zero-shot generalization on difficult failure detection tasks. We establish state-of-the-art performance on RoboFail benchmark with 67.0% accuracy, surpassing closed-source models like OpenAI o1 by 6.0%.

摘要：


### Medical explainable AI
|Publish Date|Title|Authors|Homepage|Code|
| :---: | :---: | :---: | :---: | :---: |
|**2026-03-16**|**Do Metrics for Counterfactual Explanations Align with User Perception?**|Felix Liedeker et.al.|[2603.15607v1](http://arxiv.org/abs/2603.15607v1)|null|
|**2026-03-16**|**Grokking as a Variance-Limited Phase Transition: Spectral Gating and the Epsilon-Stability Threshold**|Pratyush Acharya et.al.|[2603.15492v1](http://arxiv.org/abs/2603.15492v1)|null|
|**2026-03-16**|**Listening to the Echo: User-Reaction Aware Policy Optimization via Scalar-Verbal Hybrid Reinforcement Learning**|Jing Ye et.al.|[2603.15434v1](http://arxiv.org/abs/2603.15434v1)|null|
|**2026-03-16**|**GradCFA: A Hybrid Gradient-Based Counterfactual and Feature Attribution Explanation Algorithm for Local Interpretation of Neural Networks**|Jacob Sanderson et.al.|[2603.15373v1](http://arxiv.org/abs/2603.15373v1)|null|
|**2026-03-16**|**Intelligent Co-Design: An Interactive LLM Framework for Interior Spatial Design via Multi-Modal Agents**|Ren Jian Lim et.al.|[2603.15341v1](http://arxiv.org/abs/2603.15341v1)|null|

#### Abstracts
##### **Do Metrics for Counterfactual Explanations Align with User Perception?**
2603.15607v1 by Felix Liedeker, Basil Ell, Philipp Cimiano, Christoph Düsing

Explainability is widely regarded as essential for trustworthy artificial intelligence systems. However, the metrics commonly used to evaluate counterfactual explanations are algorithmic evaluation metrics that are rarely validated against human judgments of explanation quality. This raises the question of whether such metrics meaningfully reflect user perceptions. We address this question through an empirical study that directly compares algorithmic evaluation metrics with human judgments across three datasets. Participants rated counterfactual explanations along multiple dimensions of perceived quality, which we relate to a comprehensive set of standard counterfactual metrics. We analyze both individual relationships and the extent to which combinations of metrics can predict human assessments. Our results show that correlations between algorithmic metrics and human ratings are generally weak and strongly dataset-dependent. Moreover, increasing the number of metrics used in predictive models does not lead to reliable improvements, indicating structural limitations in how current metrics capture criteria relevant for humans. Overall, our findings suggest that widely used counterfactual evaluation metrics fail to reflect key aspects of explanation quality as perceived by users, underscoring the need for more human-centered approaches to evaluating explainable artificial intelligence.

摘要：

##### **Grokking as a Variance-Limited Phase Transition: Spectral Gating and the Epsilon-Stability Threshold**
2603.15492v1 by Pratyush Acharya, Habish Dhakal

Standard optimization theories struggle to explain grokking, where generalization occurs long after training convergence. While geometric studies attribute this to slow drift, they often overlook the interaction between the optimizer's noise structure and landscape curvature. This work analyzes AdamW dynamics on modular arithmetic tasks, revealing a ``Spectral Gating'' mechanism that regulates the transition from memorization to generalization.
  We find that AdamW operates as a variance-gated stochastic system. Grokking is constrained by a stability condition: the generalizing solution resides in a sharp basin ($λ_{max}^H$) initially inaccessible under low-variance regimes. The ``delayed'' phase represents the accumulation of gradient variance required to lift the effective stability ceiling, permitting entry into this sharp manifold.
  Our ablation studies identify three complexity regimes: (1) \textbf{Capacity Collapse} ($P < 23$), where rank-deficiency prevents structural learning; (2) \textbf{The Variance-Limited Regime} ($P \approx 41$), where generalization waits for the spectral gate to open; and (3) \textbf{Stability Override} ($P > 67$), where memorization becomes dimensionally unstable. Furthermore, we challenge the "Flat Minima" hypothesis for algorithmic tasks, showing that isotropic noise injection fails to induce grokking. Generalization requires the \textit{anisotropic rectification} unique to adaptive optimizers, which directs noise into the tangent space of the solution manifold.

摘要：

##### **Listening to the Echo: User-Reaction Aware Policy Optimization via Scalar-Verbal Hybrid Reinforcement Learning**
2603.15434v1 by Jing Ye, Xinpei Zhao, Lu Xiang, Yaping Zhang, Chengqing Zong

While current emotional support dialogue systems typically rely on expert-defined scalar rewards for alignment, these signals suffer from severe information sparsity. They cannot explain why a response failed or how to adapt to dynamic user states, often diverging from the actual goal of facilitating positive emotional shifts. In practice, the most direct and reliable learning signal emerges from the user's continuous reactions during ongoing interaction. We therefore propose Reaction Aware Policy Optimization (RAPO), a framework that optimizes over interaction consequences rather than rubric scores. RAPO treats dialogue as a reaction-driven process and utilizes simulated user responses to generate dense natural-language feedback through three core components: Hindsight Dialogue Selection, which isolates pivotal turns that meaningfully alter user emotional trajectories; Generative Hindsight Feedback, which transforms user reactions into contrastive ranking signals and natural-language critiques; and Scalar-Verbal Hybrid Policy Optimization, which couples scalar reward optimization for global alignment with verbal feedback distillation for fine-grained semantic refinement. Extensive experiments on ESC and Sotopia demonstrate that RAPO significantly outperforms strong reinforcement learning baselines in driving positive interaction outcomes.

摘要：

##### **GradCFA: A Hybrid Gradient-Based Counterfactual and Feature Attribution Explanation Algorithm for Local Interpretation of Neural Networks**
2603.15373v1 by Jacob Sanderson, Hua Mao, Wai Lok Woo

Explainable Artificial Intelligence (XAI) is increasingly essential as AI systems are deployed in critical fields such as healthcare and finance, offering transparency into AI-driven decisions. Two major XAI paradigms, counterfactual explanations (CFX) and feature attribution (FA), serve distinct roles in model interpretability. This study introduces GradCFA, a hybrid framework combining CFX and FA to improve interpretability by explicitly optimizing feasibility, plausibility, and diversity - key qualities often unbalanced in existing methods. Unlike most CFX research focused on binary classification, GradCFA extends to multi-class scenarios, supporting a wider range of applications. We evaluate GradCFA's validity, proximity, sparsity, plausibility, and diversity against state-of-the-art methods, including Wachter, DiCE, CARE for CFX, and SHAP for FA. Results show GradCFA effectively generates feasible, plausible, and diverse counterfactuals while offering valuable FA insights. By identifying influential features and validating their impact, GradCFA advances AI interpretability. The code for implementation of this work can be found at: https://github.com/jacob-ws/GradCFs .

摘要：

##### **Intelligent Co-Design: An Interactive LLM Framework for Interior Spatial Design via Multi-Modal Agents**
2603.15341v1 by Ren Jian Lim, Rushi Dai

In architectural interior design, miscommunication frequently arises as clients lack design knowledge, while designers struggle to explain complex spatial relationships, leading to delayed timelines and financial losses. Recent advancements in generative layout tools narrow the gap by automating 3D visualizations. However, prevailing methodologies exhibit limitations: rule-based systems implement hard-coded spatial constraints that restrict participatory engagement, while data-driven models rely on extensive training datasets. Recent large language models (LLMs) bridge this gap by enabling intuitive reasoning about spatial relationships through natural language. This research presents an LLM-based, multimodal, multi-agent framework that dynamically converts natural language descriptions and imagery into 3D designs. Specialized agents (Reference, Spatial, Interactive, Grader), operating via prompt guidelines, collaboratively address core challenges: the agent system enables real-time user interaction for iterative spatial refinement, while Retrieval-Augmented Generation (RAG) reduces data dependency without requiring task-specific model training. This framework accurately interprets spatial intent and generates optimized 3D indoor design, improving productivity, and encouraging nondesigner participation. Evaluations across diverse floor plans and user questionnaires demonstrate effectiveness. An independent LLM evaluator consistently rated participatory layouts higher in user intent alignment, aesthetic coherence, functionality, and circulation. Questionnaire results indicated 77% satisfaction and a clear preference over traditional design software. These findings suggest the framework enhances user-centric communication and fosters more inclusive, effective, and resilient design processes. Project page: https://rsigktyper.github.io/AICodesign/

摘要：


### Medical
|Publish Date|Title|Authors|Homepage|Code|
| :---: | :---: | :---: | :---: | :---: |
|**2026-03-16**|**GradCFA: A Hybrid Gradient-Based Counterfactual and Feature Attribution Explanation Algorithm for Local Interpretation of Neural Networks**|Jacob Sanderson et.al.|[2603.15373v1](http://arxiv.org/abs/2603.15373v1)|null|
|**2026-03-16**|**From Documents to Spans: Code-Centric Learning for LLM-based ICD Coding**|Xu Zhang et.al.|[2603.15270v1](http://arxiv.org/abs/2603.15270v1)|null|
|**2026-03-16**|**Open Biomedical Knowledge Graphs at Scale: Construction, Federation, and AI Agent Access with Samyama Graph Database**|Madhulatha Mandarapu et.al.|[2603.15080v1](http://arxiv.org/abs/2603.15080v1)|null|
|**2026-03-16**|**FairMed-XGB: A Bayesian-Optimised Multi-Metric Framework with Explainability for Demographic Equity in Critical Healthcare Data**|Mitul Goswami et.al.|[2603.14947v1](http://arxiv.org/abs/2603.14947v1)|null|
|**2026-03-16**|**A Hybrid AI and Rule-Based Decision Support System for Disease Diagnosis and Management Using Labs**|Muhammad Hammad Maqsood et.al.|[2603.14876v1](http://arxiv.org/abs/2603.14876v1)|null|

#### Abstracts
##### **GradCFA: A Hybrid Gradient-Based Counterfactual and Feature Attribution Explanation Algorithm for Local Interpretation of Neural Networks**
2603.15373v1 by Jacob Sanderson, Hua Mao, Wai Lok Woo

Explainable Artificial Intelligence (XAI) is increasingly essential as AI systems are deployed in critical fields such as healthcare and finance, offering transparency into AI-driven decisions. Two major XAI paradigms, counterfactual explanations (CFX) and feature attribution (FA), serve distinct roles in model interpretability. This study introduces GradCFA, a hybrid framework combining CFX and FA to improve interpretability by explicitly optimizing feasibility, plausibility, and diversity - key qualities often unbalanced in existing methods. Unlike most CFX research focused on binary classification, GradCFA extends to multi-class scenarios, supporting a wider range of applications. We evaluate GradCFA's validity, proximity, sparsity, plausibility, and diversity against state-of-the-art methods, including Wachter, DiCE, CARE for CFX, and SHAP for FA. Results show GradCFA effectively generates feasible, plausible, and diverse counterfactuals while offering valuable FA insights. By identifying influential features and validating their impact, GradCFA advances AI interpretability. The code for implementation of this work can be found at: https://github.com/jacob-ws/GradCFs .

摘要：

##### **From Documents to Spans: Code-Centric Learning for LLM-based ICD Coding**
2603.15270v1 by Xu Zhang, Wenxin Ma, Chenxu Wu, Rongsheng Wang, Kun Zhang, S. Kevin Zhou

ICD coding is a critical yet challenging task in healthcare. Recently, LLM-based methods demonstrate stronger generalization than discriminative methods in ICD coding. However, fine-tuning LLMs for ICD coding faces three major challenges. First, existing public ICD coding datasets provide limited coverage of the ICD code space, restricting a model's ability to generalize to unseen codes. Second, naive fine-tuning diminishes the interpretability of LLMs, as few public datasets contain explicit supporting evidence for assigned codes. Third, ICD coding typically involves long clinical documents, making fine-tuning LLMs computationally expensive. To address these issues, we propose Code-Centric Learning, a training framework that shifts supervision from full clinical documents to scalable, short evidence spans. The key idea of this framework is that span-level learning improves LLMs' ability to perform document-level ICD coding. Our proposed framework consists of a mixed training strategy and code-centric data expansion, which substantially reduces training cost, improves accuracy on unseen ICD codes and preserves interpretability. Under the same LLM backbone, our method substantially outperforms strong baselines. Notably, our method enables small-scale LLMs to achieve performance comparable to much larger proprietary models, demonstrating its effectiveness and potential for fully automated ICD coding.

摘要：

##### **Open Biomedical Knowledge Graphs at Scale: Construction, Federation, and AI Agent Access with Samyama Graph Database**
2603.15080v1 by Madhulatha Mandarapu, Sandeep Kunkunuru

Biomedical knowledge is fragmented across siloed databases -- Reactome for pathways, STRING for protein interactions, Gene Ontology for functional annotations, ClinicalTrials.gov for study registries, and dozens more. Researchers routinely download flat files from each source and write bespoke scripts to cross-reference them, a process that is slow, error-prone, and not reproducible. We present two open-source biomedical knowledge graphs -- Pathways KG (118,686 nodes, 834,785 edges from 5 sources) and Clinical Trials KG (7,774,446 nodes, 26,973,997 edges from 5 sources) -- built on Samyama, a high-performance graph database written in Rust.
  Our contributions are threefold. First, we describe a reproducible ETL pattern for constructing large-scale KGs from heterogeneous public data sources, with cross-source deduplication, batch Cypher loading, and portable snapshot export. Second, we demonstrate cross-KG federation: loading both snapshots into a single graph tenant enables property-based joins across datasets, answering questions like ``Which biological pathways are disrupted by drugs currently in Phase~3 trials for breast cancer?'' -- a query that neither KG can answer alone. Third, we introduce schema-driven MCP server generation: each KG automatically exposes typed tools for LLM agents via the Model Context Protocol, enabling natural-language access to graph queries without manual tool authoring.
  All data sources are open-license (CC~BY~4.0, CC0, OBO). Snapshots, ETL code, and MCP configurations are publicly available. The combined federated graph (7.89M nodes, 27.8M edges) loads in 76 seconds on commodity hardware (Mac Mini M4, 16GB RAM), and the signature cross-KG query -- ``which pathways are disrupted by drugs in Phase~3 breast cancer trials?'' -- returns validated results in 2.1 seconds.

摘要：

##### **FairMed-XGB: A Bayesian-Optimised Multi-Metric Framework with Explainability for Demographic Equity in Critical Healthcare Data**
2603.14947v1 by Mitul Goswami, Romit Chatterjee, Arif Ahmed Sekh

Machine learning models deployed in critical care settings exhibit demographic biases, particularly gender disparities, that undermine clinical trust and equitable treatment. This paper introduces FairMed-XGB, a novel framework that systematically detects and mitigates gender-based prediction bias while preserving model performance and transparency. The framework integrates a fairness-aware loss function combining Statistical Parity Difference, Theil Index, and Wasserstein Distance, jointly optimised via Bayesian Search into an XGBoost classifier. Post-mitigation evaluation on seven clinically distinct cohorts derived from the MIMIC-IV-ED and eICU databases demonstrates substantial bias reduction: Statistical Parity Difference decreases by 40 to 51 percent on MIMIC-IV-ED and 10 to 19 percent on eICU; Theil Index collapses by four to five orders of magnitude to near-zero values; Wasserstein Distance is reduced by 20 to 72 percent. These gains are achieved with negligible degradation in predictive accuracy (AUC-ROC drop <0.02). SHAP-based explainability reveals that the framework diminishes reliance on gender-proxy features, providing clinicians with actionable insights into how and where bias is corrected. FairMed-XGB offers a robust, interpretable, and ethically aligned solution for equitable clinical decision-making, paving the way for trustworthy deployment of AI in high-stakes healthcare environments.

摘要：

##### **A Hybrid AI and Rule-Based Decision Support System for Disease Diagnosis and Management Using Labs**
2603.14876v1 by Muhammad Hammad Maqsood, Mubashir Sajid, Khubaib Ahmed, Muhammad Usamah Shahid, Muddassar Farooq

This research paper outlines the development and implementation of a novel Clinical Decision Support System (CDSS) that integrates AI predictive modeling with medical knowledge bases. It utilizes the quantifiable information elements in lab results for inferring likely diagnoses a patient might have. Subsequently, suggesting investigations to confirm the likely diagnoses -- an assistive tool for physicians. The system fuses knowledge contained in a rule-base expert system with inferences of data driven predictors based on the features in labs. The data for 593,055 patients was collected from 547 primary care centers across the US to model our decision support system and derive Real-Word Evidence (RWE) to make it relevant for a large demographic of patients. Our Rule-Base comprises clinically validated rules, modeling 59 health conditions that can directly confirm one or more of diseases and assign ICD-10 codes to them. The Likely Diagnosis system uses multi-class classification, covering 37 ICD-10 codes, which are grouped together into 11 categories based on the labs that physicians prescribe to confirm the diagnosis. This research offers a novel system that assists a physician by utilizing medical profile of a patient and routine lab investigations to predict a group of likely diseases and then confirm them, coupled with providing explanations for inferences, thereby assisting physicians to reduce misdiagnosis of patients in clinical decision-making.

摘要：


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

