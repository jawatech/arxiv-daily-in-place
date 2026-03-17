
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

