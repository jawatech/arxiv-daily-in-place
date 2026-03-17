
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

