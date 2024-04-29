# arxiv-daily
 Automated deployment @ 2024-04-29 11:42:01 Asia/Taipei
> Welcome to contribute! Add your topics and keywords in [`topic.yml`](https://github.com/jawatech/arxiv-daily-in-place/blob/main/database/topic.yml).
> You can also view historical data through the [storage](https://github.com/jawatech/arxiv-daily-in-place/blob/main/database/storage).

## AI

### LLM
|Publish Date|Title|Authors|PDF|Code|
| :---: | :---: | :---: | :---: | :---: |
|**2024-04-26**|**Probabilistic Inference in Language Models via Twisted Sequential Monte Carlo**|Numerous capability and safety techniques of Large Language Models (LLMs),
including RLHF, automated red-teaming, prompt engineering, and infilling, can
be cast as sampling from an unnormalized target distribution defined by a given
reward or potential function over the full sequence. In this work, we leverage
the rich toolkit of Sequential Monte Carlo (SMC) for these probabilistic
inference problems. In particular, we use learned twist functions to estimate
the expected future value of the potential at each timestep, which enables us
to focus inference-time computation on promising partial sequences. We propose
a novel contrastive method for learning the twist functions, and establish
connections with the rich literature of soft reinforcement learning. As a
complementary application of our twisted SMC framework, we present methods for
evaluating the accuracy of language model inference techniques using novel
bidirectional SMC bounds on the log partition function. These bounds can be
used to estimate the KL divergence between the inference and target
distributions in both directions. We apply our inference evaluation techniques
to show that twisted SMC is effective for sampling undesirable outputs from a
pretrained model (a useful component of harmlessness training and automated
red-teaming), generating reviews with varied sentiment, and performing
infilling tasks.|Stephen Zhao et.al.|[2404.17546v1](http://arxiv.org/abs/2404.17546v1)|null|
|**2024-04-26**|**Large Language Model Agent as a Mechanical Designer**|Conventional mechanical design paradigms rely on experts systematically
refining concepts through experience-guided modification and FEA to meet
specific requirements. However, this approach can be time-consuming and heavily
dependent on prior knowledge and experience. While numerous machine learning
models have been developed to streamline this intensive and expert-driven
iterative process, these methods typically demand extensive training data and
considerable computational resources. Furthermore, methods based on deep
learning are usually restricted to the specific domains and tasks for which
they were trained, limiting their applicability across different tasks. This
creates a trade-off between the efficiency of automation and the demand for
resources. In this study, we present a novel approach that integrates
pre-trained LLMs with a FEM module. The FEM module evaluates each design and
provides essential feedback, guiding the LLMs to continuously learn, plan,
generate, and optimize designs without the need for domain-specific training.
We demonstrate the effectiveness of our proposed framework in managing the
iterative optimization of truss structures, showcasing its capability to reason
about and refine designs according to structured feedback and criteria. Our
results reveal that these LLM-based agents can successfully generate truss
designs that comply with natural language specifications with a success rate of
up to 90%, which varies according to the applied constraints. By employing
prompt-based optimization techniques we show that LLM based agents exhibit
optimization behavior when provided with solution-score pairs to iteratively
refine designs to meet specifications. This ability of LLM agents to produce
viable designs and optimize them based on their inherent reasoning capabilities
highlights their potential to develop and implement effective design strategies
autonomously.|Yayati Jadhav et.al.|[2404.17525v1](http://arxiv.org/abs/2404.17525v1)|null|
|**2024-04-26**|**On the Use of Large Language Models to Generate Capability Ontologies**|Capability ontologies are increasingly used to model functionalities of
systems or machines. The creation of such ontological models with all
properties and constraints of capabilities is very complex and can only be done
by ontology experts. However, Large Language Models (LLMs) have shown that they
can generate machine-interpretable models from natural language text input and
thus support engineers / ontology experts. Therefore, this paper investigates
how LLMs can be used to create capability ontologies. We present a study with a
series of experiments in which capabilities with varying complexities are
generated using different prompting techniques and with different LLMs. Errors
in the generated ontologies are recorded and compared. To analyze the quality
of the generated ontologies, a semi-automated approach based on RDF syntax
checking, OWL reasoning, and SHACL constraints is used. The results of this
study are very promising because even for complex capabilities, the generated
ontologies are almost free of errors.|Luis Miguel Vieira da Silva et.al.|[2404.17524v1](http://arxiv.org/abs/2404.17524v1)|null|
|**2024-04-26**|**Enhancing Legal Compliance and Regulation Analysis with Large Language Models**|This research explores the application of Large Language Models (LLMs) for
automating the extraction of requirement-related legal content in the food
safety domain and checking legal compliance of regulatory artifacts. With
Industry 4.0 revolutionizing the food industry and with the General Data
Protection Regulation (GDPR) reshaping privacy policies and data processing
agreements, there is a growing gap between regulatory analysis and recent
technological advancements. This study aims to bridge this gap by leveraging
LLMs, namely BERT and GPT models, to accurately classify legal provisions and
automate compliance checks. Our findings demonstrate promising results,
indicating LLMs' significant potential to enhance legal compliance and
regulatory analysis efficiency, notably by reducing manual workload and
improving accuracy within reasonable time and financial constraints.|Shabnam Hassani et.al.|[2404.17522v1](http://arxiv.org/abs/2404.17522v1)|null|
|**2024-04-26**|**A Comprehensive Evaluation on Event Reasoning of Large Language Models**|Event reasoning is a fundamental ability that underlies many applications. It
requires event schema knowledge to perform global reasoning and needs to deal
with the diversity of the inter-event relations and the reasoning paradigms.
How well LLMs accomplish event reasoning on various relations and reasoning
paradigms remains unknown. To mitigate this disparity, we comprehensively
evaluate the abilities of event reasoning of LLMs. We introduce a novel
benchmark EV2 for EValuation of EVent reasoning. EV2 consists of two levels of
evaluation of schema and instance and is comprehensive in relations and
reasoning paradigms. We conduct extensive experiments on EV2. We find that LLMs
have abilities to accomplish event reasoning but their performances are far
from satisfactory. We also notice the imbalance of event reasoning abilities in
LLMs. Besides, LLMs have event schema knowledge, however, they're not aligned
with humans on how to utilize the knowledge. Based on these findings, we
introduce two methods to guide the LLMs to utilize the event schema knowledge.
Both methods achieve improvements.|Zhengwei Tao et.al.|[2404.17513v1](http://arxiv.org/abs/2404.17513v1)|[link](https://github.com/tzwwww/ev2)|
|**2024-04-26**|**Causally Abstracted Multi-armed Bandits**|Multi-armed bandits (MAB) and causal MABs (CMAB) are established frameworks
for decision-making problems. The majority of prior work typically studies and
solves individual MAB and CMAB in isolation for a given problem and associated
data. However, decision-makers are often faced with multiple related problems
and multi-scale observations where joint formulations are needed in order to
efficiently exploit the problem structures and data dependencies. Transfer
learning for CMABs addresses the situation where models are defined on
identical variables, although causal connections may differ. In this work, we
extend transfer learning to setups involving CMABs defined on potentially
different variables, with varying degrees of granularity, and related via an
abstraction map. Formally, we introduce the problem of causally abstracted MABs
(CAMABs) by relying on the theory of causal abstraction in order to express a
rigorous abstraction map. We propose algorithms to learn in a CAMAB, and study
their regret. We illustrate the limitations and the strengths of our algorithms
on a real-world scenario related to online advertising.|Fabio Massimo Zennaro et.al.|[2404.17493v1](http://arxiv.org/abs/2404.17493v1)|null|
|**2024-04-26**|**Tabular Data Contrastive Learning via Class-Conditioned and Feature-Correlation Based Augmentation**|Contrastive learning is a model pre-training technique by first creating
similar views of the original data, and then encouraging the data and its
corresponding views to be close in the embedding space. Contrastive learning
has witnessed success in image and natural language data, thanks to the
domain-specific augmentation techniques that are both intuitive and effective.
Nonetheless, in tabular domain, the predominant augmentation technique for
creating views is through corrupting tabular entries via swapping values, which
is not as sound or effective. We propose a simple yet powerful improvement to
this augmentation technique: corrupting tabular data conditioned on class
identity. Specifically, when corrupting a specific tabular entry from an anchor
row, instead of randomly sampling a value in the same feature column from the
entire table uniformly, we only sample from rows that are identified to be
within the same class as the anchor row. We assume the semi-supervised learning
setting, and adopt the pseudo labeling technique for obtaining class identities
over all table rows. We also explore the novel idea of selecting features to be
corrupted based on feature correlation structures. Extensive experiments show
that the proposed approach consistently outperforms the conventional corruption
method for tabular data classification tasks. Our code is available at
https://github.com/willtop/Tabular-Class-Conditioned-SSL.|Wei Cui et.al.|[2404.17489v1](http://arxiv.org/abs/2404.17489v1)|[link](https://github.com/willtop/tabular-class-conditioned-ssl)|
|**2024-04-26**|**Conformal Prediction with Learned Features**|In this paper, we focus on the problem of conformal prediction with
conditional guarantees. Prior work has shown that it is impossible to construct
nontrivial prediction sets with full conditional coverage guarantees. A wealth
of research has considered relaxations of full conditional guarantees, relying
on some predefined uncertainty structures. Departing from this line of
thinking, we propose Partition Learning Conformal Prediction (PLCP), a
framework to improve conditional validity of prediction sets through learning
uncertainty-guided features from the calibration data. We implement PLCP
efficiently with alternating gradient descent, utilizing off-the-shelf machine
learning models. We further analyze PLCP theoretically and provide conditional
guarantees for infinite and finite sample sizes. Finally, our experimental
results over four real-world and synthetic datasets show the superior
performance of PLCP compared to state-of-the-art methods in terms of coverage
and length in both classification and regression scenarios.|Shayan Kiyani et.al.|[2404.17487v1](http://arxiv.org/abs/2404.17487v1)|null|
|**2024-04-26**|**ReproHum #0087-01: Human Evaluation Reproduction Report for Generating Fact Checking Explanations**|This paper presents a partial reproduction of Generating Fact Checking
Explanations by Anatanasova et al (2020) as part of the ReproHum element of the
ReproNLP shared task to reproduce the findings of NLP research regarding human
evaluation. This shared task aims to investigate the extent to which NLP as a
field is becoming more or less reproducible over time. Following the
instructions provided by the task organisers and the original authors, we
collect relative rankings of 3 fact-checking explanations (comprising a gold
standard and the outputs of 2 models) for 40 inputs on the criteria of
Coverage. The results of our reproduction and reanalysis of the original work's
raw results lend support to the original findings, with similar patterns seen
between the original work and our reproduction. Whilst we observe slight
variation from the original results, our findings support the main conclusions
drawn by the original authors pertaining to the efficacy of their proposed
models.|Tyler Loakman et.al.|[2404.17481v1](http://arxiv.org/abs/2404.17481v1)|null|
|**2024-04-26**|**CEval: A Benchmark for Evaluating Counterfactual Text Generation**|Counterfactual text generation aims to minimally change a text, such that it
is classified differently. Judging advancements in method development for
counterfactual text generation is hindered by a non-uniform usage of data sets
and metrics in related work. We propose CEval, a benchmark for comparing
counterfactual text generation methods. CEval unifies counterfactual and text
quality metrics, includes common counterfactual datasets with human
annotations, standard baselines (MICE, GDBA, CREST) and the open-source
language model LLAMA-2. Our experiments found no perfect method for generating
counterfactual text. Methods that excel at counterfactual metrics often produce
lower-quality text while LLMs with simple prompts generate high-quality text
but struggle with counterfactual criteria. By making CEval available as an
open-source Python library, we encourage the community to contribute more
methods and maintain consistent evaluation in future work.|Van Bach Nguyen et.al.|[2404.17475v1](http://arxiv.org/abs/2404.17475v1)|null|
|**2024-04-26**|**Ruffle&Riley: Insights from Designing and Evaluating a Large Language Model-Based Conversational Tutoring System**|Conversational tutoring systems (CTSs) offer learning experiences through
interactions based on natural language. They are recognized for promoting
cognitive engagement and improving learning outcomes, especially in reasoning
tasks. Nonetheless, the cost associated with authoring CTS content is a major
obstacle to widespread adoption and to research on effective instructional
design. In this paper, we discuss and evaluate a novel type of CTS that
leverages recent advances in large language models (LLMs) in two ways: First,
the system enables AI-assisted content authoring by inducing an easily editable
tutoring script automatically from a lesson text. Second, the system automates
the script orchestration in a learning-by-teaching format via two LLM-based
agents (Ruffle&Riley) acting as a student and a professor. The system allows
for free-form conversations that follow the ITS-typical inner and outer loop
structure. We evaluate Ruffle&Riley's ability to support biology lessons in two
between-subject online user studies (N = 200) comparing the system to simpler
QA chatbots and reading activity. Analyzing system usage patterns,
pre/post-test scores and user experience surveys, we find that Ruffle&Riley
users report high levels of engagement, understanding and perceive the offered
support as helpful. Even though Ruffle&Riley users require more time to
complete the activity, we did not find significant differences in short-term
learning gains over the reading activity. Our system architecture and user
study provide various insights for designers of future CTSs. We further
open-source our system to support ongoing research on effective instructional
design of LLM-based learning technologies.|Robin Schmucker et.al.|[2404.17460v1](http://arxiv.org/abs/2404.17460v1)|null|
|**2024-04-26**|**Domain Adaptive and Fine-grained Anomaly Detection for Single-cell Sequencing Data and Beyond**|Fined-grained anomalous cell detection from affected tissues is critical for
clinical diagnosis and pathological research. Single-cell sequencing data
provide unprecedented opportunities for this task. However, current anomaly
detection methods struggle to handle domain shifts prevalent in multi-sample
and multi-domain single-cell sequencing data, leading to suboptimal
performance. Moreover, these methods fall short of distinguishing anomalous
cells into pathologically distinct subtypes. In response, we propose ACSleuth,
a novel, reconstruction deviation-guided generative framework that integrates
the detection, domain adaptation, and fine-grained annotating of anomalous
cells into a methodologically cohesive workflow. Notably, we present the first
theoretical analysis of using reconstruction deviations output by generative
models for anomaly detection in lieu of domain shifts. This analysis informs us
to develop a novel and superior maximum mean discrepancy-based anomaly scorer
in ACSleuth. Extensive benchmarks over various single-cell data and other types
of tabular data demonstrate ACSleuth's superiority over the state-of-the-art
methods in identifying and subtyping anomalies in multi-sample and multi-domain
contexts. Our code is available at https://github.com/Catchxu/ACsleuth.|Kaichen Xu et.al.|[2404.17454v1](http://arxiv.org/abs/2404.17454v1)|[link](https://github.com/catchxu/acsleuth)|
|**2024-04-26**|**"ChatGPT Is Here to Help, Not to Replace Anybody" -- An Evaluation of Students' Opinions On Integrating ChatGPT In CS Courses**|Large Language Models (LLMs) like GPT and Bard are capable of producing code
based on textual descriptions, with remarkable efficacy. Such technology will
have profound implications for computing education, raising concerns about
cheating, excessive dependence, and a decline in computational thinking skills,
among others. There has been extensive research on how teachers should handle
this challenge but it is also important to understand how students feel about
this paradigm shift. In this research, 52 first-year CS students were surveyed
in order to assess their views on technologies with code-generation
capabilities, both from academic and professional perspectives. Our findings
indicate that while students generally favor the academic use of GPT, they
don't over rely on it, only mildly asking for its help. Although most students
benefit from GPT, some struggle to use it effectively, urging the need for
specific GPT training. Opinions on GPT's impact on their professional lives
vary, but there is a consensus on its importance in academic practice.|Bruno Pereira Cipriano et.al.|[2404.17443v1](http://arxiv.org/abs/2404.17443v1)|null|
|**2024-04-26**|**Real-World Deployment of a Hierarchical Uncertainty-Aware Collaborative Multiagent Planning System**|We would like to enable a collaborative multiagent team to navigate at long
length scales and under uncertainty in real-world environments. In practice,
planning complexity scales with the number of agents in the team, with the
length scale of the environment, and with environmental uncertainty. Enabling
tractable planning requires developing abstract models that can represent
complex, high-quality plans. However, such models often abstract away
information needed to generate directly-executable plans for real-world agents
in real-world environments, as planning in such detail, especially in the
presence of real-world uncertainty, would be computationally intractable. In
this paper, we describe the deployment of a planning system that used a
hierarchy of planners to execute collaborative multiagent navigation tasks in
real-world, unknown environments. By developing a planning system that was
robust to failures at every level of the planning hierarchy, we enabled the
team to complete collaborative navigation tasks, even in the presence of
imperfect planning abstractions and real-world uncertainty. We deployed our
approach on a Clearpath Husky-Jackal team navigating in a structured outdoor
environment, and demonstrated that the system enabled the agents to
successfully execute collaborative plans.|Martina Stadler Kurtz et.al.|[2404.17438v1](http://arxiv.org/abs/2404.17438v1)|null|
|**2024-04-26**|**Evaluation of Geographical Distortions in Language Models: A Crucial Step Towards Equitable Representations**|Language models now constitute essential tools for improving efficiency for
many professional tasks such as writing, coding, or learning. For this reason,
it is imperative to identify inherent biases. In the field of Natural Language
Processing, five sources of bias are well-identified: data, annotation,
representation, models, and research design. This study focuses on biases
related to geographical knowledge. We explore the connection between geography
and language models by highlighting their tendency to misrepresent spatial
information, thus leading to distortions in the representation of geographical
distances. This study introduces four indicators to assess these distortions,
by comparing geographical and semantic distances. Experiments are conducted
from these four indicators with ten widely used language models. Results
underscore the critical necessity of inspecting and rectifying spatial biases
in language models to ensure accurate and equitable representations.|Rémy Decoupes et.al.|[2404.17401v1](http://arxiv.org/abs/2404.17401v1)|null|
|**2024-04-26**|**Spatial-frequency Dual-Domain Feature Fusion Network for Low-Light Remote Sensing Image Enhancement**|Low-light remote sensing images generally feature high resolution and high
spatial complexity, with continuously distributed surface features in space.
This continuity in scenes leads to extensive long-range correlations in spatial
domains within remote sensing images. Convolutional Neural Networks, which rely
on local correlations for long-distance modeling, struggle to establish
long-range correlations in such images. On the other hand, transformer-based
methods that focus on global information face high computational complexities
when processing high-resolution remote sensing images. From another
perspective, Fourier transform can compute global information without
introducing a large number of parameters, enabling the network to more
efficiently capture the overall image structure and establish long-range
correlations. Therefore, we propose a Dual-Domain Feature Fusion Network (DFFN)
for low-light remote sensing image enhancement. Specifically, this challenging
task of low-light enhancement is divided into two more manageable sub-tasks:
the first phase learns amplitude information to restore image brightness, and
the second phase learns phase information to refine details. To facilitate
information exchange between the two phases, we designed an information fusion
affine block that combines data from different phases and scales. Additionally,
we have constructed two dark light remote sensing datasets to address the
current lack of datasets in dark light remote sensing image enhancement.
Extensive evaluations show that our method outperforms existing
state-of-the-art methods. The code is available at
https://github.com/iijjlk/DFFN.|Zishu Yao et.al.|[2404.17400v1](http://arxiv.org/abs/2404.17400v1)|null|
|**2024-04-26**|**Child Speech Recognition in Human-Robot Interaction: Problem Solved?**|Automated Speech Recognition shows superhuman performance for adult English
speech on a range of benchmarks, but disappoints when fed children's speech.
This has long sat in the way of child-robot interaction. Recent evolutions in
data-driven speech recognition, including the availability of Transformer
architectures and unprecedented volumes of training data, might mean a
breakthrough for child speech recognition and social robot applications aimed
at children. We revisit a study on child speech recognition from 2017 and show
that indeed performance has increased, with newcomer OpenAI Whisper doing
markedly better than leading commercial cloud services. While transcription is
not perfect yet, the best model recognises 60.3% of sentences correctly barring
small grammatical differences, with sub-second transcription time running on a
local GPU, showing potential for usable autonomous child-robot speech
interactions.|Ruben Janssens et.al.|[2404.17394v1](http://arxiv.org/abs/2404.17394v1)|null|
|**2024-04-26**|**M3BAT: Unsupervised Domain Adaptation for Multimodal Mobile Sensing with Multi-Branch Adversarial Training**|Over the years, multimodal mobile sensing has been used extensively for
inferences regarding health and well being, behavior, and context. However, a
significant challenge hindering the widespread deployment of such models in
real world scenarios is the issue of distribution shift. This is the phenomenon
where the distribution of data in the training set differs from the
distribution of data in the real world, the deployment environment. While
extensively explored in computer vision and natural language processing, and
while prior research in mobile sensing briefly addresses this concern, current
work primarily focuses on models dealing with a single modality of data, such
as audio or accelerometer readings, and consequently, there is little research
on unsupervised domain adaptation when dealing with multimodal sensor data. To
address this gap, we did extensive experiments with domain adversarial neural
networks (DANN) showing that they can effectively handle distribution shifts in
multimodal sensor data. Moreover, we proposed a novel improvement over DANN,
called M3BAT, unsupervised domain adaptation for multimodal mobile sensing with
multi-branch adversarial training, to account for the multimodality of sensor
data during domain adaptation with multiple branches. Through extensive
experiments conducted on two multimodal mobile sensing datasets, three
inference tasks, and 14 source-target domain pairs, including both regression
and classification, we demonstrate that our approach performs effectively on
unseen domains. Compared to directly deploying a model trained in the source
domain to the target domain, the model shows performance increases up to 12%
AUC (area under the receiver operating characteristics curves) on
classification tasks, and up to 0.13 MAE (mean absolute error) on regression
tasks.|Lakmal Meegahapola et.al.|[2404.17391v1](http://arxiv.org/abs/2404.17391v1)|null|
|**2024-04-26**|**Assessing the Potential of AI for Spatially Sensitive Nature-Related Financial Risks**|There is growing recognition among financial institutions, financial
regulators and policy makers of the importance of addressing nature-related
risks and opportunities. Evaluating and assessing nature-related risks for
financial institutions is challenging due to the large volume of heterogeneous
data available on nature and the complexity of investment value chains and the
various components' relationship to nature. The dual problem of scaling data
analytics and analysing complex systems can be addressed using Artificial
Intelligence (AI). We address issues such as plugging existing data gaps with
discovered data, data estimation under uncertainty, time series analysis and
(near) real-time updates. This report presents potential AI solutions for
models of two distinct use cases, the Brazil Beef Supply Use Case and the Water
Utility Use Case. Our two use cases cover a broad perspective within
sustainable finance. The Brazilian cattle farming use case is an example of
greening finance - integrating nature-related considerations into mainstream
financial decision-making to transition investments away from sectors with poor
historical track records and unsustainable operations. The deployment of
nature-based solutions in the UK water utility use case is an example of
financing green - driving investment to nature-positive outcomes. The two use
cases also cover different sectors, geographies, financial assets and AI
modelling techniques, providing an overview on how AI could be applied to
different challenges relating to nature's integration into finance. This report
is primarily aimed at financial institutions but is also of interest to ESG
data providers, TNFD, systems modellers, and, of course, AI practitioners.|Steven Reece et.al.|[2404.17369v1](http://arxiv.org/abs/2404.17369v1)|null|
|**2024-04-26**|**Similarity Equivariant Graph Neural Networks for Homogenization of Metamaterials**|Soft, porous mechanical metamaterials exhibit pattern transformations that
may have important applications in soft robotics, sound reduction and
biomedicine. To design these innovative materials, it is important to be able
to simulate them accurately and quickly, in order to tune their mechanical
properties. Since conventional simulations using the finite element method
entail a high computational cost, in this article we aim to develop a machine
learning-based approach that scales favorably to serve as a surrogate model. To
ensure that the model is also able to handle various microstructures, including
those not encountered during training, we include the microstructure as part of
the network input. Therefore, we introduce a graph neural network that predicts
global quantities (energy, stress stiffness) as well as the pattern
transformations that occur (the kinematics). To make our model as accurate and
data-efficient as possible, various symmetries are incorporated into the model.
The starting point is an E(n)-equivariant graph neural network (which respects
translation, rotation and reflection) that has periodic boundary conditions
(i.e., it is in-/equivariant with respect to the choice of RVE), is scale
in-/equivariant, can simulate large deformations, and can predict scalars,
vectors as well as second and fourth order tensors (specifically energy, stress
and stiffness). The incorporation of scale equivariance makes the model
equivariant with respect to the similarities group, of which the Euclidean
group E(n) is a subgroup. We show that this network is more accurate and
data-efficient than graph neural networks with fewer symmetries. To create an
efficient graph representation of the finite element discretization, we use
only the internal geometrical hole boundaries from the finite element mesh to
achieve a better speed-up and scaling with the mesh size.|Fleur Hendriks et.al.|[2404.17365v1](http://arxiv.org/abs/2404.17365v1)|null|
|**2024-04-26**|**A Bionic Natural Language Parser Equivalent to a Pushdown Automaton**|Assembly Calculus (AC), proposed by Papadimitriou et al., aims to reproduce
advanced cognitive functions through simulating neural activities, with several
applications based on AC having been developed, including a natural language
parser proposed by Mitropolsky et al. However, this parser lacks the ability to
handle Kleene closures, preventing it from parsing all regular languages and
rendering it weaker than Finite Automata (FA). In this paper, we propose a new
bionic natural language parser (BNLP) based on AC and integrates two new
biologically rational structures, Recurrent Circuit and Stack Circuit which are
inspired by RNN and short-term memory mechanism. In contrast to the original
parser, the BNLP can fully handle all regular languages and Dyck languages.
Therefore, leveraging the Chomsky-Sch \H{u}tzenberger theorem, the BNLP which
can parse all Context-Free Languages can be constructed. We also formally prove
that for any PDA, a Parser Automaton corresponding to BNLP can always be
formed, ensuring that BNLP has a description ability equal to that of PDA and
addressing the deficiencies of the original parser.|Zhenghao Wei et.al.|[2404.17343v1](http://arxiv.org/abs/2404.17343v1)|null|
|**2024-04-26**|**Can a Multichoice Dataset be Repurposed for Extractive Question Answering?**|The rapid evolution of Natural Language Processing (NLP) has favored major
languages such as English, leaving a significant gap for many others due to
limited resources. This is especially evident in the context of data
annotation, a task whose importance cannot be underestimated, but which is
time-consuming and costly. Thus, any dataset for resource-poor languages is
precious, in particular when it is task-specific. Here, we explore the
feasibility of repurposing existing datasets for a new NLP task: we repurposed
the Belebele dataset (Bandarkar et al., 2023), which was designed for
multiple-choice question answering (MCQA), to enable extractive QA (EQA) in the
style of machine reading comprehension. We present annotation guidelines and a
parallel EQA dataset for English and Modern Standard Arabic (MSA). We also
present QA evaluation results for several monolingual and cross-lingual QA
pairs including English, MSA, and five Arabic dialects. Our aim is to enable
others to adapt our approach for the 120+ other language variants in Belebele,
many of which are deemed under-resourced. We also conduct a thorough analysis
and share our insights from the process, which we hope will contribute to a
deeper understanding of the challenges and the opportunities associated with
task reformulation in NLP research.|Teresa Lynn et.al.|[2404.17342v1](http://arxiv.org/abs/2404.17342v1)|null|
|**2024-04-26**|**Metronome: tracing variation in poetic meters via local sequence alignment**|All poetic forms come from somewhere. Prosodic templates can be copied for
generations, altered by individuals, imported from foreign traditions, or
fundamentally changed under the pressures of language evolution. Yet these
relationships are notoriously difficult to trace across languages and times.
This paper introduces an unsupervised method for detecting structural
similarities in poems using local sequence alignment. The method relies on
encoding poetic texts as strings of prosodic features using a four-letter
alphabet; these sequences are then aligned to derive a distance measure based
on weighted symbol (mis)matches. Local alignment allows poems to be clustered
according to emergent properties of their underlying prosodic patterns. We
evaluate method performance on a meter recognition tasks against strong
baselines and show its potential for cross-lingual and historical research
using three short case studies: 1) mutations in quantitative meter in classical
Latin, 2) European diffusion of the Renaissance hendecasyllable, and 3)
comparative alignment of modern meters in 18--19th century Czech, German and
Russian. We release an implementation of the algorithm as a Python package with
an open license.|Ben Nagy et.al.|[2404.17337v1](http://arxiv.org/abs/2404.17337v1)|[link](https://github.com/bnagy/metronome-paper)|
|**2024-04-26**|**Introducing cosmosGPT: Monolingual Training for Turkish Language Models**|The number of open source language models that can produce Turkish is
increasing day by day, as in other languages. In order to create the basic
versions of such models, the training of multilingual models is usually
continued with Turkish corpora. The alternative is to train the model with only
Turkish corpora. In this study, we first introduce the cosmosGPT models that we
created with this alternative method. Then, we introduce new finetune datasets
for basic language models to fulfill user requests and new evaluation datasets
for measuring the capabilities of Turkish language models. Finally, a
comprehensive comparison of the adapted Turkish language models on different
capabilities is presented. The results show that the language models we built
with the monolingual corpus have promising performance despite being about 10
times smaller than the others.|H. Toprak Kesgin et.al.|[2404.17336v1](http://arxiv.org/abs/2404.17336v1)|null|
|**2024-04-26**|**A Novel Spike Transformer Network for Depth Estimation from Event Cameras via Cross-modality Knowledge Distillation**|Depth estimation is crucial for interpreting complex environments, especially
in areas such as autonomous vehicle navigation and robotics. Nonetheless,
obtaining accurate depth readings from event camera data remains a formidable
challenge. Event cameras operate differently from traditional digital cameras,
continuously capturing data and generating asynchronous binary spikes that
encode time, location, and light intensity. Yet, the unique sampling mechanisms
of event cameras render standard image based algorithms inadequate for
processing spike data. This necessitates the development of innovative,
spike-aware algorithms tailored for event cameras, a task compounded by the
irregularity, continuity, noise, and spatial and temporal characteristics
inherent in spiking data.Harnessing the strong generalization capabilities of
transformer neural networks for spatiotemporal data, we propose a purely
spike-driven spike transformer network for depth estimation from spiking camera
data. To address performance limitations with Spiking Neural Networks (SNN), we
introduce a novel single-stage cross-modality knowledge transfer framework
leveraging knowledge from a large vision foundational model of artificial
neural networks (ANN) (DINOv2) to enhance the performance of SNNs with limited
data. Our experimental results on both synthetic and real datasets show
substantial improvements over existing models, with notable gains in Absolute
Relative and Square Relative errors (49% and 39.77% improvements over the
benchmark model Spike-T, respectively). Besides accuracy, the proposed model
also demonstrates reduced power consumptions, a critical factor for practical
applications.|Xin Zhang et.al.|[2404.17335v1](http://arxiv.org/abs/2404.17335v1)|null|
|**2024-04-26**|**Part-Guided 3D RL for Sim2Real Articulated Object Manipulation**|Manipulating unseen articulated objects through visual feedback is a critical
but challenging task for real robots. Existing learning-based solutions mainly
focus on visual affordance learning or other pre-trained visual models to guide
manipulation policies, which face challenges for novel instances in real-world
scenarios. In this paper, we propose a novel part-guided 3D RL framework, which
can learn to manipulate articulated objects without demonstrations. We combine
the strengths of 2D segmentation and 3D RL to improve the efficiency of RL
policy training. To improve the stability of the policy on real robots, we
design a Frame-consistent Uncertainty-aware Sampling (FUS) strategy to get a
condensed and hierarchical 3D representation. In addition, a single versatile
RL policy can be trained on multiple articulated object manipulation tasks
simultaneously in simulation and shows great generalizability to novel
categories and instances. Experimental results demonstrate the effectiveness of
our framework in both simulation and real-world settings. Our code is available
at
https://github.com/THU-VCLab/Part-Guided-3D-RL-for-Sim2Real-Articulated-Object-Manipulation.|Pengwei Xie et.al.|[2404.17302v1](http://arxiv.org/abs/2404.17302v1)|[link](https://github.com/thu-vclab/part-guided-3d-rl-for-sim2real-articulated-object-manipulation)|
|**2024-04-26**|**When to Trust LLMs: Aligning Confidence with Response Quality**|Despite the success of large language models (LLMs) in natural language
generation, much evidence shows that LLMs may produce incorrect or nonsensical
text. This limitation highlights the importance of discerning when to trust
LLMs, especially in safety-critical domains. Existing methods, which rely on
verbalizing confidence to tell the reliability by inducing top-k responses and
sampling-aggregating multiple responses, often fail, due to the lack of
objective guidance of confidence. To address this, we propose
CONfidence-Quality-ORDerpreserving alignment approach (CONQORD), leveraging
reinforcement learning with a tailored dual-component reward function. This
function encompasses quality reward and orderpreserving alignment reward
functions. Specifically, the order-preserving reward incentivizes the model to
verbalize greater confidence for responses of higher quality to align the order
of confidence and quality. Experiments demonstrate that our CONQORD
significantly improves the alignment performance between confidence levels and
response accuracy, without causing the model to become over-cautious.
Furthermore, the aligned confidence provided by CONQORD informs when to trust
LLMs, and acts as a determinant for initiating the retrieval process of
external knowledge. Aligning confidence with response quality ensures more
transparent and reliable responses, providing better trustworthiness.|Shuchang Tao et.al.|[2404.17287v1](http://arxiv.org/abs/2404.17287v1)|null|
|**2024-04-26**|**Reinforcement Retrieval Leveraging Fine-grained Feedback for Fact Checking News Claims with Black-Box LLM**|Retrieval-augmented language models have exhibited promising performance
across various areas of natural language processing (NLP), including
fact-critical tasks. However, due to the black-box nature of advanced large
language models (LLMs) and the non-retrieval-oriented supervision signal of
specific tasks, the training of retrieval model faces significant challenges
under the setting of black-box LLM. We propose an approach leveraging
Fine-grained Feedback with Reinforcement Retrieval (FFRR) to enhance
fact-checking on news claims by using black-box LLM. FFRR adopts a two-level
strategy to gather fine-grained feedback from the LLM, which serves as a reward
for optimizing the retrieval policy, by rating the retrieved documents based on
the non-retrieval ground truth of the task. We evaluate our model on two public
datasets for real-world news claim verification, and the results demonstrate
that FFRR achieves significant improvements over strong LLM-enabled and non-LLM
baselines.|Xuan Zhang et.al.|[2404.17283v1](http://arxiv.org/abs/2404.17283v1)|[link](https://github.com/jadecurl/ffrr)|
|**2024-04-26**|**Enhancing Privacy and Security of Autonomous UAV Navigation**|Autonomous Unmanned Aerial Vehicles (UAVs) have become essential tools in
defense, law enforcement, disaster response, and product delivery. These
autonomous navigation systems require a wireless communication network, and of
late are deep learning based. In critical scenarios such as border protection
or disaster response, ensuring the secure navigation of autonomous UAVs is
paramount. But, these autonomous UAVs are susceptible to adversarial attacks
through the communication network or the deep learning models - eavesdropping /
man-in-the-middle / membership inference / reconstruction. To address this
susceptibility, we propose an innovative approach that combines Reinforcement
Learning (RL) and Fully Homomorphic Encryption (FHE) for secure autonomous UAV
navigation. This end-to-end secure framework is designed for real-time video
feeds captured by UAV cameras and utilizes FHE to perform inference on
encrypted input images. While FHE allows computations on encrypted data,
certain computational operators are yet to be implemented. Convolutional neural
networks, fully connected neural networks, activation functions and OpenAI Gym
Library are meticulously adapted to the FHE domain to enable encrypted data
processing. We demonstrate the efficacy of our proposed approach through
extensive experimentation. Our proposed approach ensures security and privacy
in autonomous UAV navigation with negligible loss in performance.|Vatsal Aggarwal et.al.|[2404.17225v1](http://arxiv.org/abs/2404.17225v1)|null|
|**2024-04-26**|**Prompting Techniques for Reducing Social Bias in LLMs through System 1 and System 2 Cognitive Processes**|Dual process theory posits that human cognition arises via two systems.
System 1, which is a quick, emotional, and intuitive process, which is subject
to cognitive biases, and System 2, a slow, onerous, and deliberate process. NLP
researchers often compare zero-shot prompting in LLMs to System 1 reasoning and
chain-of-thought (CoT) prompting to System 2. In line with this interpretation,
prior research has found that using CoT prompting in LLMs leads to reduced
gender bias. We investigate the relationship between bias, CoT prompting, and
dual process theory in LLMs directly. We compare zero-shot, CoT, and a variety
of dual process theory-based prompting strategies on two bias datasets spanning
nine different social bias categories. We also use human and machine personas
to determine whether the effects of dual process theory in LLMs are based on
modeling human cognition or inherent to the system. We find that a human
persona, System 2, and CoT prompting all tend to reduce social biases in LLMs,
though the best combination of features depends on the exact model and bias
category -- resulting in up to a 13 percent drop in stereotypical judgments by
an LLM.|Mahammed Kamruzzaman et.al.|[2404.17218v1](http://arxiv.org/abs/2404.17218v1)|null|
|**2024-04-26**|**Prompting Towards Alleviating Code-Switched Data Scarcity in Under-Resourced Languages with GPT as a Pivot**|Many multilingual communities, including numerous in Africa, frequently
engage in code-switching during conversations. This behaviour stresses the need
for natural language processing technologies adept at processing code-switched
text. However, data scarcity, particularly in African languages, poses a
significant challenge, as many are low-resourced and under-represented. In this
study, we prompted GPT 3.5 to generate Afrikaans--English and Yoruba--English
code-switched sentences, enhancing diversity using topic-keyword pairs,
linguistic guidelines, and few-shot examples. Our findings indicate that the
quality of generated sentences for languages using non-Latin scripts, like
Yoruba, is considerably lower when compared with the high Afrikaans-English
success rate. There is therefore a notable opportunity to refine prompting
guidelines to yield sentences suitable for the fine-tuning of language models.
We propose a framework for augmenting the diversity of synthetically generated
code-switched data using GPT and propose leveraging this technology to mitigate
data scarcity in low-resourced languages, underscoring the essential role of
native speakers in this process.|Michelle Terblanche et.al.|[2404.17216v1](http://arxiv.org/abs/2404.17216v1)|null|
|**2024-04-26**|**Human-Imperceptible Retrieval Poisoning Attacks in LLM-Powered Applications**|Presently, with the assistance of advanced LLM application development
frameworks, more and more LLM-powered applications can effortlessly augment the
LLMs' knowledge with external content using the retrieval augmented generation
(RAG) technique. However, these frameworks' designs do not have sufficient
consideration of the risk of external content, thereby allowing attackers to
undermine the applications developed with these frameworks. In this paper, we
reveal a new threat to LLM-powered applications, termed retrieval poisoning,
where attackers can guide the application to yield malicious responses during
the RAG process. Specifically, through the analysis of LLM application
frameworks, attackers can craft documents visually indistinguishable from
benign ones. Despite the documents providing correct information, once they are
used as reference sources for RAG, the application is misled into generating
incorrect responses. Our preliminary experiments indicate that attackers can
mislead LLMs with an 88.33\% success rate, and achieve a 66.67\% success rate
in the real-world application, demonstrating the potential impact of retrieval
poisoning.|Quan Zhang et.al.|[2404.17196v1](http://arxiv.org/abs/2404.17196v1)|null|
|**2024-04-26**|**TIGQA:An Expert Annotated Question Answering Dataset in Tigrinya**|The absence of explicitly tailored, accessible annotated datasets for
educational purposes presents a notable obstacle for NLP tasks in languages
with limited resources.This study initially explores the feasibility of using
machine translation (MT) to convert an existing dataset into a Tigrinya dataset
in SQuAD format. As a result, we present TIGQA, an expert annotated educational
dataset consisting of 2.68K question-answer pairs covering 122 diverse topics
such as climate, water, and traffic. These pairs are from 537 context
paragraphs in publicly accessible Tigrinya and Biology books. Through
comprehensive analyses, we demonstrate that the TIGQA dataset requires skills
beyond simple word matching, requiring both single-sentence and
multiple-sentence inference abilities. We conduct experiments using
state-of-the art MRC methods, marking the first exploration of such models on
TIGQA. Additionally, we estimate human performance on the dataset and juxtapose
it with the results obtained from pretrained models.The notable disparities
between human performance and best model performance underscore the potential
for further enhancements to TIGQA through continued research. Our dataset is
freely accessible via the provided link to encourage the research community to
address the challenges in the Tigrinya MRC.|Hailay Teklehaymanot et.al.|[2404.17194v1](http://arxiv.org/abs/2404.17194v1)|null|
|**2024-04-26**|**MCSDNet: Mesoscale Convective System Detection Network via Multi-scale Spatiotemporal Information**|The accurate detection of Mesoscale Convective Systems (MCS) is crucial for
meteorological monitoring due to their potential to cause significant
destruction through severe weather phenomena such as hail, thunderstorms, and
heavy rainfall. However, the existing methods for MCS detection mostly targets
on single-frame detection, which just considers the static characteristics and
ignores the temporal evolution in the life cycle of MCS. In this paper, we
propose a novel encoder-decoder neural network for MCS detection(MCSDNet).
MCSDNet has a simple architecture and is easy to expand. Different from the
previous models, MCSDNet targets on multi-frames detection and leverages
multi-scale spatiotemporal information for the detection of MCS regions in
remote sensing imagery(RSI). As far as we know, it is the first work to utilize
multi-scale spatiotemporal information to detect MCS regions. Firstly, we
design a multi-scale spatiotemporal information module to extract multi-level
semantic from different encoder levels, which makes our models can extract more
detail spatiotemporal features. Secondly, a Spatiotemporal Mix Unit(STMU) is
introduced to MCSDNet to capture both intra-frame features and inter-frame
correlations, which is a scalable module and can be replaced by other
spatiotemporal module, e.g., CNN, RNN, Transformer and our proposed Dual
Spatiotemporal Attention(DSTA). This means that the future works about
spatiotemporal modules can be easily integrated to our model. Finally, we
present MCSRSI, the first publicly available dataset for multi-frames MCS
detection based on visible channel images from the FY-4A satellite. We also
conduct several experiments on MCSRSI and find that our proposed MCSDNet
achieve the best performance on MCS detection task when comparing to other
baseline methods.|Jiajun Liang et.al.|[2404.17186v1](http://arxiv.org/abs/2404.17186v1)|null|
|**2024-04-26**|**A Unified Label-Aware Contrastive Learning Framework for Few-Shot Named Entity Recognition**|Few-shot Named Entity Recognition (NER) aims to extract named entities using
only a limited number of labeled examples. Existing contrastive learning
methods often suffer from insufficient distinguishability in context vector
representation because they either solely rely on label semantics or completely
disregard them. To tackle this issue, we propose a unified label-aware
token-level contrastive learning framework. Our approach enriches the context
by utilizing label semantics as suffix prompts. Additionally, it simultaneously
optimizes context-context and context-label contrastive learning objectives to
enhance generalized discriminative contextual representations.Extensive
experiments on various traditional test domains (OntoNotes, CoNLL'03, WNUT'17,
GUM, I2B2) and the large-scale few-shot NER dataset (FEWNERD) demonstrate the
effectiveness of our approach. It outperforms prior state-of-the-art models by
a significant margin, achieving an average absolute gain of 7% in micro F1
scores across most scenarios. Further analysis reveals that our model benefits
from its powerful transfer capability and improved contextual representations.|Haojie Zhang et.al.|[2404.17178v1](http://arxiv.org/abs/2404.17178v1)|null|
|**2024-04-26**|**Exploring Beyond Logits: Hierarchical Dynamic Labeling Based on Embeddings for Semi-Supervised Classification**|In semi-supervised learning, methods that rely on confidence learning to
generate pseudo-labels have been widely proposed. However, increasing research
finds that when faced with noisy and biased data, the model's representation
network is more reliable than the classification network. Additionally, label
generation methods based on model predictions often show poor adaptability
across different datasets, necessitating customization of the classification
network. Therefore, we propose a Hierarchical Dynamic Labeling (HDL) algorithm
that does not depend on model predictions and utilizes image embeddings to
generate sample labels. We also introduce an adaptive method for selecting
hyperparameters in HDL, enhancing its versatility. Moreover, HDL can be
combined with general image encoders (e.g., CLIP) to serve as a fundamental
data processing module. We extract embeddings from datasets with class-balanced
and long-tailed distributions using pre-trained semi-supervised models.
Subsequently, samples are re-labeled using HDL, and the re-labeled samples are
used to further train the semi-supervised models. Experiments demonstrate
improved model performance, validating the motivation that representation
networks are more reliable than classifiers or predictors. Our approach has the
potential to change the paradigm of pseudo-label generation in semi-supervised
learning.|Yanbiao Ma et.al.|[2404.17173v1](http://arxiv.org/abs/2404.17173v1)|null|
|**2024-04-26**|**Quantifying Memorization of Domain-Specific Pre-trained Language Models using Japanese Newspaper and Paywalls**|Dominant pre-trained language models (PLMs) have been successful in
high-quality natural language generation. However, the analysis of their
generation is not mature: do they acquire generalizable linguistic
abstractions, or do they simply memorize and recover substrings of the training
data? Especially, few studies focus on domain-specific PLM. In this study, we
pre-trained domain-specific GPT-2 models using a limited corpus of Japanese
newspaper articles and quantified memorization of training data by comparing
them with general Japanese GPT-2 models. Our experiments revealed that
domain-specific PLMs sometimes "copy and paste" on a large scale. Furthermore,
we replicated the empirical finding that memorization is related to
duplication, model size, and prompt length, in Japanese the same as in previous
English studies. Our evaluations are relieved from data contamination concerns
by focusing on newspaper paywalls, which prevent their use as training data. We
hope that our paper encourages a sound discussion such as the security and
copyright of PLMs.|Shotaro Ishihara et.al.|[2404.17143v1](http://arxiv.org/abs/2404.17143v1)|null|
|**2024-04-26**|**Small Language Models Need Strong Verifiers to Self-Correct Reasoning**|Self-correction has emerged as a promising solution to boost the reasoning
performance of large language models (LLMs), where LLMs refine their solutions
using self-generated critiques that pinpoint the errors. This work explores
whether smaller-size (<= 13B) language models (LMs) have the ability of
self-correction on reasoning tasks with minimal inputs from stronger LMs. We
propose a novel pipeline that prompts smaller LMs to collect self-correction
data that supports the training of self-refinement abilities. First, we
leverage correct solutions to guide the model in critiquing their incorrect
responses. Second, the generated critiques, after filtering, are used for
supervised fine-tuning of the self-correcting reasoner through solution
refinement. Our experimental results show improved self-correction abilities of
two models on five datasets spanning math and commonsense reasoning, with
notable performance gains when paired with a strong GPT-4-based verifier,
though limitations are identified when using a weak self-verifier for
determining when to correct.|Yunxiang Zhang et.al.|[2404.17140v1](http://arxiv.org/abs/2404.17140v1)|null|
|**2024-04-26**|**Automated Data Visualization from Natural Language via Large Language Models: An Exploratory Study**|The Natural Language to Visualization (NL2Vis) task aims to transform
natural-language descriptions into visual representations for a grounded table,
enabling users to gain insights from vast amounts of data. Recently, many deep
learning-based approaches have been developed for NL2Vis. Despite the
considerable efforts made by these approaches, challenges persist in
visualizing data sourced from unseen databases or spanning multiple tables.
Taking inspiration from the remarkable generation capabilities of Large
Language Models (LLMs), this paper conducts an empirical study to evaluate
their potential in generating visualizations, and explore the effectiveness of
in-context learning prompts for enhancing this task. In particular, we first
explore the ways of transforming structured tabular data into sequential text
prompts, as to feed them into LLMs and analyze which table content contributes
most to the NL2Vis. Our findings suggest that transforming structured tabular
data into programs is effective, and it is essential to consider the table
schema when formulating prompts. Furthermore, we evaluate two types of LLMs:
finetuned models (e.g., T5-Small) and inference-only models (e.g., GPT-3.5),
against state-of-the-art methods, using the NL2Vis benchmarks (i.e., nvBench).
The experimental results reveal that LLMs outperform baselines, with
inference-only models consistently exhibiting performance improvements, at
times even surpassing fine-tuned models when provided with certain few-shot
demonstrations through in-context learning. Finally, we analyze when the LLMs
fail in NL2Vis, and propose to iteratively update the results using strategies
such as chain-of-thought, role-playing, and code-interpreter. The experimental
results confirm the efficacy of iterative updates and hold great potential for
future study.|Yang Wu et.al.|[2404.17136v1](http://arxiv.org/abs/2404.17136v1)|null|
|**2024-04-26**|**Process Mining Embeddings: Learning Vector Representations for Petri Nets**|Process mining offers powerful techniques for discovering, analyzing, and
enhancing real-world business processes. In this context, Petri nets provide an
expressive means of modeling process behavior. However, directly analyzing and
comparing intricate Petri net presents challenges. This study introduces
PetriNet2Vec, a novel unsupervised methodology based on Natural Language
Processing concepts inspired by Doc2Vec and designed to facilitate the
effective comparison, clustering, and classification of process models
represented as embedding vectors. These embedding vectors allow us to quantify
similarities and relationships between different process models. Our
methodology was experimentally validated using the PDC Dataset, featuring 96
diverse Petri net models. We performed cluster analysis, created UMAP
visualizations, and trained a decision tree to provide compelling evidence for
the capability of PetriNet2Vec to discern meaningful patterns and relationships
among process models and their constituent tasks. Through a series of
experiments, we demonstrated that PetriNet2Vec was capable of learning the
structure of Petri nets, as well as the main properties used to simulate the
process models of our dataset. Furthermore, our results showcase the utility of
the learned embeddings in two crucial downstream tasks within process mining
enhancement: process classification and process retrieval.|Juan G. Colonna et.al.|[2404.17129v1](http://arxiv.org/abs/2404.17129v1)|[link](https://github.com/juancolonna/petrinet2vec)|
|**2024-04-26**|**Deep Evidential Learning for Dose Prediction**|In this work, we present a novel application of an uncertainty-quantification
framework called Deep Evidential Learning in the domain of radiotherapy dose
prediction. Using medical images of the Open Knowledge-Based Planning Challenge
dataset, we found that this model can be effectively harnessed to yield
uncertainty estimates that inherited correlations with prediction errors upon
completion of network training. This was achieved only after reformulating the
original loss function for a stable implementation. We found that (i)epistemic
uncertainty was highly correlated with prediction errors, with various
association indices comparable or stronger than those for Monte-Carlo Dropout
and Deep Ensemble methods, (ii)the median error varied with uncertainty
threshold much more linearly for epistemic uncertainty in Deep Evidential
Learning relative to these other two conventional frameworks, indicative of a
more uniformly calibrated sensitivity to model errors, (iii)relative to
epistemic uncertainty, aleatoric uncertainty demonstrated a more significant
shift in its distribution in response to Gaussian noise added to CT intensity,
compatible with its interpretation as reflecting data noise. Collectively, our
results suggest that Deep Evidential Learning is a promising approach that can
endow deep-learning models in radiotherapy dose prediction with statistical
robustness. Towards enhancing its clinical relevance, we demonstrate how we can
use such a model to construct the predicted Dose-Volume-Histograms' confidence
intervals.|Hai Siong Tan et.al.|[2404.17126v1](http://arxiv.org/abs/2404.17126v1)|null|
|**2024-04-26**|**Text Sentiment Analysis and Classification Based on Bidirectional Gated Recurrent Units (GRUs) Model**|This paper explores the importance of text sentiment analysis and
classification in the field of natural language processing, and proposes a new
approach to sentiment analysis and classification based on the bidirectional
gated recurrent units (GRUs) model. The study firstly analyses the word cloud
model of the text with six sentiment labels, and then carries out data
preprocessing, including the steps of removing special symbols, punctuation
marks, numbers, stop words and non-alphabetic parts. Subsequently, the data set
is divided into training set and test set, and through model training and
testing, it is found that the accuracy of the validation set is increased from
85% to 93% with training, which is an increase of 8%; at the same time, the
loss value of the validation set decreases from 0.7 to 0.1 and tends to be
stable, and the model is gradually close to the actual value, which can
effectively classify the text emotions. The confusion matrix shows that the
accuracy of the model on the test set reaches 94.8%, the precision is 95.9%,
the recall is 99.1%, and the F1 score is 97.4%, which proves that the model has
good generalisation ability and classification effect. Overall, the study
demonstrated an effective method for text sentiment analysis and classification
with satisfactory results.|Wei Xu et.al.|[2404.17123v1](http://arxiv.org/abs/2404.17123v1)|null|
|**2024-04-26**|**2M-NER: Contrastive Learning for Multilingual and Multimodal NER with Language and Modal Fusion**|Named entity recognition (NER) is a fundamental task in natural language
processing that involves identifying and classifying entities in sentences into
pre-defined types. It plays a crucial role in various research fields,
including entity linking, question answering, and online product
recommendation. Recent studies have shown that incorporating multilingual and
multimodal datasets can enhance the effectiveness of NER. This is due to
language transfer learning and the presence of shared implicit features across
different modalities. However, the lack of a dataset that combines
multilingualism and multimodality has hindered research exploring the
combination of these two aspects, as multimodality can help NER in multiple
languages simultaneously. In this paper, we aim to address a more challenging
task: multilingual and multimodal named entity recognition (MMNER), considering
its potential value and influence. Specifically, we construct a large-scale
MMNER dataset with four languages (English, French, German and Spanish) and two
modalities (text and image). To tackle this challenging MMNER task on the
dataset, we introduce a new model called 2M-NER, which aligns the text and
image representations using contrastive learning and integrates a multimodal
collaboration module to effectively depict the interactions between the two
modalities. Extensive experimental results demonstrate that our model achieves
the highest F1 score in multilingual and multimodal NER tasks compared to some
comparative and representative baselines. Additionally, in a challenging
analysis, we discovered that sentence-level alignment interferes a lot with NER
models, indicating the higher level of difficulty in our dataset.|Dongsheng Wang et.al.|[2404.17122v1](http://arxiv.org/abs/2404.17122v1)|null|
|**2024-04-26**|**Talking Nonsense: Probing Large Language Models' Understanding of Adversarial Gibberish Inputs**|Large language models (LLMs) exhibit excellent ability to understand human
languages, but do they also understand their own language that appears
gibberish to us? In this work we delve into this question, aiming to uncover
the mechanisms underlying such behavior in LLMs. We employ the Greedy
Coordinate Gradient optimizer to craft prompts that compel LLMs to generate
coherent responses from seemingly nonsensical inputs. We call these inputs LM
Babel and this work systematically studies the behavior of LLMs manipulated by
these prompts. We find that the manipulation efficiency depends on the target
text's length and perplexity, with the Babel prompts often located in lower
loss minima compared to natural prompts. We further examine the structure of
the Babel prompts and evaluate their robustness. Notably, we find that guiding
the model to generate harmful texts is not more difficult than into generating
benign texts, suggesting lack of alignment for out-of-distribution prompts.|Valeriia Cherepanova et.al.|[2404.17120v1](http://arxiv.org/abs/2404.17120v1)|null|
|**2024-04-26**|**CLARE: Cognitive Load Assessment in REaltime with Multimodal Data**|We present a novel multimodal dataset for Cognitive Load Assessment in
REaltime (CLARE). The dataset contains physiological and gaze data from 24
participants with self-reported cognitive load scores as ground-truth labels.
The dataset consists of four modalities, namely, Electrocardiography (ECG),
Electrodermal Activity (EDA), Electroencephalogram (EEG), and Gaze tracking. To
map diverse levels of mental load on participants during experiments, each
participant completed four nine-minutes sessions on a computer-based operator
performance and mental workload task (the MATB-II software) with varying levels
of complexity in one minute segments. During the experiment, participants
reported their cognitive load every 10 seconds. For the dataset, we also
provide benchmark binary classification results with machine learning and deep
learning models on two different evaluation schemes, namely, 10-fold and
leave-one-subject-out (LOSO) cross-validation. Benchmark results show that for
10-fold evaluation, the convolutional neural network (CNN) based deep learning
model achieves the best classification performance with ECG, EDA, and Gaze. In
contrast, for LOSO, the best performance is achieved by the deep learning model
with ECG, EDA, and EEG.|Anubhav Bhatti et.al.|[2404.17098v1](http://arxiv.org/abs/2404.17098v1)|null|
|**2024-04-25**|**CyNetDiff -- A Python Library for Accelerated Implementation of Network Diffusion Models**|In recent years, there has been increasing interest in network diffusion
models and related problems. The most popular of these are the independent
cascade and linear threshold models. Much of the recent experimental work done
on these models requires a large number of simulations conducted on large
graphs, a computationally expensive task suited for low-level languages.
However, many researchers prefer the use of higher-level languages (such as
Python) for their flexibility and shorter development times. Moreover, in many
research tasks, these simulations are the most computationally intensive task,
so it would be desirable to have a library for these with an interface to a
high-level language with the performance of a low-level language. To fill this
niche, we introduce CyNetDiff, a Python library with components written in
Cython to provide improved performance for these computationally intensive
diffusion tasks.|Eliot W. Robson et.al.|[2404.17059v1](http://arxiv.org/abs/2404.17059v1)|null|
|**2024-04-25**|**Agentive Permissions in Multiagent Systems**|This paper proposes to distinguish four forms of agentive permissions in
multiagent settings. The main technical results are the complexity analysis of
model checking, the semantic undefinability of modalities that capture these
forms of permissions through each other, and a complete logical system
capturing the interplay between these modalities.|Qi Shi et.al.|[2404.17053v1](http://arxiv.org/abs/2404.17053v1)|null|
|**2024-04-25**|**Generative AI in Color-Changing Systems: Re-Programmable 3D Object Textures with Material and Design Constraints**|Advances in Generative AI tools have allowed designers to manipulate existing
3D models using text or image-based prompts, enabling creators to explore
different design goals. Photochromic color-changing systems, on the other hand,
allow for the reprogramming of surface texture of 3D models, enabling easy
customization of physical objects and opening up the possibility of using
object surfaces for data display. However, existing photochromic systems
require the user to manually design the desired texture, inspect the simulation
of the pattern on the object, and verify the efficacy of the generated pattern.
These manual design, inspection, and verification steps prevent the user from
efficiently exploring the design space of possible patterns. Thus, by designing
an automated workflow desired for an end-to-end texture application process, we
can allow rapid iteration on different practicable patterns.
  In this workshop paper, we discuss the possibilities of extending generative
AI systems, with material and design constraints for reprogrammable surfaces
with photochromic materials. By constraining generative AI systems to colors
and materials possible to be physically realized with photochromic dyes, we can
create tools that would allow users to explore different viable patterns, with
text and image-based prompts. We identify two focus areas in this topic:
photochromic material constraints and design constraints for data-encoded
textures. We highlight the current limitations of using generative AI tools to
create viable textures using photochromic material. Finally, we present
possible approaches to augment generative AI methods to take into account the
photochromic material constraints, allowing for the creation of viable
photochromic textures rapidly and easily.|Yunyi Zhu et.al.|[2404.17028v1](http://arxiv.org/abs/2404.17028v1)|null|
|**2024-04-25**|**Player-Driven Emergence in LLM-Driven Game Narrative**|We explore how interaction with large language models (LLMs) can give rise to
emergent behaviors, empowering players to participate in the evolution of game
narratives. Our testbed is a text-adventure game in which players attempt to
solve a mystery under a fixed narrative premise, but can freely interact with
non-player characters generated by GPT-4, a large language model. We recruit 28
gamers to play the game and use GPT-4 to automatically convert the game logs
into a node-graph representing the narrative in the player's gameplay. We find
that through their interactions with the non-deterministic behavior of the LLM,
players are able to discover interesting new emergent nodes that were not a
part of the original narrative but have potential for being fun and engaging.
Players that created the most emergent nodes tended to be those that often
enjoy games that facilitate discovery, exploration and experimentation.|Xiangyu Peng et.al.|[2404.17027v1](http://arxiv.org/abs/2404.17027v1)|null|
|**2024-04-25**|**Generating Minimalist Adversarial Perturbations to Test Object-Detection Models: An Adaptive Multi-Metric Evolutionary Search Approach**|Deep Learning (DL) models excel in computer vision tasks but can be
susceptible to adversarial examples. This paper introduces Triple-Metric
EvoAttack (TM-EVO), an efficient algorithm for evaluating the robustness of
object-detection DL models against adversarial attacks. TM-EVO utilizes a
multi-metric fitness function to guide an evolutionary search efficiently in
creating effective adversarial test inputs with minimal perturbations. We
evaluate TM-EVO on widely-used object-detection DL models, DETR and Faster
R-CNN, and open-source datasets, COCO and KITTI. Our findings reveal that
TM-EVO outperforms the state-of-the-art EvoAttack baseline, leading to
adversarial tests with less noise while maintaining efficiency.|Cristopher McIntyre-Garcia et.al.|[2404.17020v1](http://arxiv.org/abs/2404.17020v1)|[link](https://github.com/cmcin019/tm-evo)|
|**2024-04-25**|**Türkçe Dil Modellerinin Performans Karşılaştırması Performance Comparison of Turkish Language Models**|The developments that language models have provided in fulfilling almost all
kinds of tasks have attracted the attention of not only researchers but also
the society and have enabled them to become products. There are commercially
successful language models available. However, users may prefer open-source
language models due to cost, data privacy, or regulations. Yet, despite the
increasing number of these models, there is no comprehensive comparison of
their performance for Turkish. This study aims to fill this gap in the
literature. A comparison is made among seven selected language models based on
their contextual learning and question-answering abilities. Turkish datasets
for contextual learning and question-answering were prepared, and both
automatic and human evaluations were conducted. The results show that for
question-answering, continuing pretraining before fine-tuning with
instructional datasets is more successful in adapting multilingual models to
Turkish and that in-context learning performances do not much related to
question-answering performances.|Eren Dogan et.al.|[2404.17010v1](http://arxiv.org/abs/2404.17010v1)|null|
|**2024-04-25**|**Evaluating Class Membership Relations in Knowledge Graphs using Large Language Models**|A backbone of knowledge graphs are their class membership relations, which
assign entities to a given class. As part of the knowledge engineering process,
we propose a new method for evaluating the quality of these relations by
processing descriptions of a given entity and class using a zero-shot
chain-of-thought classifier that uses a natural language intensional definition
of a class. We evaluate the method using two publicly available knowledge
graphs, Wikidata and CaLiGraph, and 7 large language models. Using the
gpt-4-0125-preview large language model, the method's classification
performance achieves a macro-averaged F1-score of 0.830 on data from Wikidata
and 0.893 on data from CaLiGraph. Moreover, a manual analysis of the
classification errors shows that 40.9% of errors were due to the knowledge
graphs, with 16.0% due to missing relations and 24.9% due to incorrectly
asserted relations. These results show how large language models can assist
knowledge engineers in the process of knowledge graph refinement. The code and
data are available on Github.|Bradley P. Allen et.al.|[2404.17000v1](http://arxiv.org/abs/2404.17000v1)|[link](https://github.com/bradleypallen/evaluating-kg-class-memberships-using-llms)|
|**2024-04-25**|**IDIL: Imitation Learning of Intent-Driven Expert Behavior**|When faced with accomplishing a task, human experts exhibit intentional
behavior. Their unique intents shape their plans and decisions, resulting in
experts demonstrating diverse behaviors to accomplish the same task. Due to the
uncertainties encountered in the real world and their bounded rationality,
experts sometimes adjust their intents, which in turn influences their
behaviors during task execution. This paper introduces IDIL, a novel imitation
learning algorithm to mimic these diverse intent-driven behaviors of experts.
Iteratively, our approach estimates expert intent from heterogeneous
demonstrations and then uses it to learn an intent-aware model of their
behavior. Unlike contemporary approaches, IDIL is capable of addressing
sequential tasks with high-dimensional state representations, while
sidestepping the complexities and drawbacks associated with adversarial
training (a mainstay of related techniques). Our empirical results suggest that
the models generated by IDIL either match or surpass those produced by recent
imitation learning benchmarks in metrics of task performance. Moreover, as it
creates a generative model, IDIL demonstrates superior performance in intent
inference metrics, crucial for human-agent interactions, and aptly captures a
broad spectrum of expert behaviors.|Sangwon Seo et.al.|[2404.16989v1](http://arxiv.org/abs/2404.16989v1)|null|
|**2024-04-25**|**Examining the robustness of LLM evaluation to the distributional assumptions of benchmarks**|Benchmarks have emerged as the central approach for evaluating Large Language
Models (LLMs). The research community often relies on a model's average
performance across the test prompts of a benchmark to evaluate the model's
performance. This is consistent with the assumption that the test prompts
within a benchmark represent a random sample from a real-world distribution of
interest. We note that this is generally not the case; instead, we hold that
the distribution of interest varies according to the specific use case. We find
that (1) the correlation in model performance across test prompts is
non-random, (2) accounting for correlations across test prompts can change
model rankings on major benchmarks, (3) explanatory factors for these
correlations include semantic similarity and common LLM failure points.|Melissa Ailem et.al.|[2404.16966v1](http://arxiv.org/abs/2404.16966v1)|null|
|**2024-04-25**|**A Closer Look at Classification Evaluation Metrics and a Critical Reflection of Common Evaluation Practice**|Classification systems are evaluated in a countless number of papers.
However, we find that evaluation practice is often nebulous. Frequently,
metrics are selected without arguments, and blurry terminology invites
misconceptions. For instance, many works use so-called 'macro' metrics to rank
systems (e.g., 'macro F1') but do not clearly specify what they would expect
from such a 'macro' metric. This is problematic, since picking a metric can
affect paper findings as well as shared task rankings, and thus any clarity in
the process should be maximized.
  Starting from the intuitive concepts of bias and prevalence, we perform an
analysis of common evaluation metrics, considering expectations as found
expressed in papers. Equipped with a thorough understanding of the metrics, we
survey metric selection in recent shared tasks of Natural Language Processing.
The results show that metric choices are often not supported with convincing
arguments, an issue that can make any ranking seem arbitrary. This work aims at
providing overview and guidance for more informed and transparent metric
selection, fostering meaningful evaluation.|Juri Opitz et.al.|[2404.16958v1](http://arxiv.org/abs/2404.16958v1)|null|
|**2024-04-25**|**Taming False Positives in Out-of-Distribution Detection with Human Feedback**|Robustness to out-of-distribution (OOD) samples is crucial for safely
deploying machine learning models in the open world. Recent works have focused
on designing scoring functions to quantify OOD uncertainty. Setting appropriate
thresholds for these scoring functions for OOD detection is challenging as OOD
samples are often unavailable up front. Typically, thresholds are set to
achieve a desired true positive rate (TPR), e.g., $95\%$ TPR. However, this can
lead to very high false positive rates (FPR), ranging from 60 to 96\%, as
observed in the Open-OOD benchmark. In safety-critical real-life applications,
e.g., medical diagnosis, controlling the FPR is essential when dealing with
various OOD samples dynamically. To address these challenges, we propose a
mathematically grounded OOD detection framework that leverages expert feedback
to \emph{safely} update the threshold on the fly. We provide theoretical
results showing that it is guaranteed to meet the FPR constraint at all times
while minimizing the use of human feedback. Another key feature of our
framework is that it can work with any scoring function for OOD uncertainty
quantification. Empirical evaluation of our system on synthetic and benchmark
OOD datasets shows that our method can maintain FPR at most $5\%$ while
maximizing TPR.|Harit Vishwakarma et.al.|[2404.16954v1](http://arxiv.org/abs/2404.16954v1)|[link](https://github.com/2454511550lin/tamefalsepositives-ood)|
|**2024-04-25**|**Make-it-Real: Unleashing Large Multimodal Model's Ability for Painting 3D Objects with Realistic Materials**|Physically realistic materials are pivotal in augmenting the realism of 3D
assets across various applications and lighting conditions. However, existing
3D assets and generative models often lack authentic material properties.
Manual assignment of materials using graphic software is a tedious and
time-consuming task. In this paper, we exploit advancements in Multimodal Large
Language Models (MLLMs), particularly GPT-4V, to present a novel approach,
Make-it-Real: 1) We demonstrate that GPT-4V can effectively recognize and
describe materials, allowing the construction of a detailed material library.
2) Utilizing a combination of visual cues and hierarchical text prompts, GPT-4V
precisely identifies and aligns materials with the corresponding components of
3D objects. 3) The correctly matched materials are then meticulously applied as
reference for the new SVBRDF material generation according to the original
diffuse map, significantly enhancing their visual authenticity. Make-it-Real
offers a streamlined integration into the 3D content creation workflow,
showcasing its utility as an essential tool for developers of 3D assets.|Ye Fang et.al.|[2404.16829v1](http://arxiv.org/abs/2404.16829v1)|null|
|**2024-04-25**|**A Survey of Generative Search and Recommendation in the Era of Large Language Models**|With the information explosion on the Web, search and recommendation are
foundational infrastructures to satisfying users' information needs. As the two
sides of the same coin, both revolve around the same core research problem,
matching queries with documents or users with items. In the recent few decades,
search and recommendation have experienced synchronous technological paradigm
shifts, including machine learning-based and deep learning-based paradigms.
Recently, the superintelligent generative large language models have sparked a
new paradigm in search and recommendation, i.e., generative search (retrieval)
and recommendation, which aims to address the matching problem in a generative
manner. In this paper, we provide a comprehensive survey of the emerging
paradigm in information systems and summarize the developments in generative
search and recommendation from a unified perspective. Rather than simply
categorizing existing works, we abstract a unified framework for the generative
paradigm and break down the existing works into different stages within this
framework to highlight the strengths and weaknesses. And then, we distinguish
generative search and recommendation with their unique challenges, identify
open problems and future directions, and envision the next information-seeking
paradigm.|Yongqi Li et.al.|[2404.16924v1](http://arxiv.org/abs/2404.16924v1)|null|
|**2024-04-25**|**IndicGenBench: A Multilingual Benchmark to Evaluate Generation Capabilities of LLMs on Indic Languages**|As large language models (LLMs) see increasing adoption across the globe, it
is imperative for LLMs to be representative of the linguistic diversity of the
world. India is a linguistically diverse country of 1.4 Billion people. To
facilitate research on multilingual LLM evaluation, we release IndicGenBench -
the largest benchmark for evaluating LLMs on user-facing generation tasks
across a diverse set 29 of Indic languages covering 13 scripts and 4 language
families. IndicGenBench is composed of diverse generation tasks like
cross-lingual summarization, machine translation, and cross-lingual question
answering. IndicGenBench extends existing benchmarks to many Indic languages
through human curation providing multi-way parallel evaluation data for many
under-represented Indic languages for the first time. We evaluate a wide range
of proprietary and open-source LLMs including GPT-3.5, GPT-4, PaLM-2, mT5,
Gemma, BLOOM and LLaMA on IndicGenBench in a variety of settings. The largest
PaLM-2 models performs the best on most tasks, however, there is a significant
performance gap in all languages compared to English showing that further
research is needed for the development of more inclusive multilingual language
models. IndicGenBench is released at
www.github.com/google-research-datasets/indic-gen-bench|Harman Singh et.al.|[2404.16816v1](http://arxiv.org/abs/2404.16816v1)|null|
|**2024-04-25**|**Make Your LLM Fully Utilize the Context**|While many contemporary large language models (LLMs) can process lengthy
input, they still struggle to fully utilize information within the long
context, known as the lost-in-the-middle challenge. We hypothesize that it
stems from insufficient explicit supervision during the long-context training,
which fails to emphasize that any position in a long context can hold crucial
information. Based on this intuition, our study presents information-intensive
(IN2) training, a purely data-driven solution to overcome lost-in-the-middle.
Specifically, IN2 training leverages a synthesized long-context question-answer
dataset, where the answer requires (1) fine-grained information awareness on a
short segment (~128 tokens) within a synthesized long context (4K-32K tokens),
and (2) the integration and reasoning of information from two or more short
segments. Through applying this information-intensive training on Mistral-7B,
we present FILM-7B (FILl-in-the-Middle). To thoroughly assess the ability of
FILM-7B for utilizing long contexts, we design three probing tasks that
encompass various context styles (document, code, and structured-data context)
and information retrieval patterns (forward, backward, and bi-directional
retrieval). The probing results demonstrate that FILM-7B can robustly retrieve
information from different positions in its 32K context window. Beyond these
probing tasks, FILM-7B significantly improves the performance on real-world
long-context tasks (e.g., 23.5->26.9 F1 score on NarrativeQA), while
maintaining a comparable performance on short-context tasks (e.g., 59.3->59.2
accuracy on MMLU). Github Link: https://github.com/microsoft/FILM.|Shengnan An et.al.|[2404.16811v2](http://arxiv.org/abs/2404.16811v2)|[link](https://github.com/microsoft/FILM)|
|**2024-04-25**|**Improving Diversity of Commonsense Generation by Large Language Models via In-Context Learning**|Generative Commonsense Reasoning (GCR) requires a model to reason about a
situation using commonsense knowledge, while generating coherent sentences.
Although the quality of the generated sentences is crucial, the diversity of
the generation is equally important because it reflects the model's ability to
use a range of commonsense knowledge facts. Large Language Models (LLMs) have
shown proficiency in enhancing the generation quality across various tasks
through in-context learning (ICL) using given examples without the need for any
fine-tuning. However, the diversity aspect in LLM outputs has not been
systematically studied before. To address this, we propose a simple method that
diversifies the LLM generations, while preserving their quality. Experimental
results on three benchmark GCR datasets show that our method achieves an ideal
balance between the quality and diversity. Moreover, the sentences generated by
our proposed method can be used as training data to improve diversity in
existing commonsense generators.|Tianhui Zhang et.al.|[2404.16807v1](http://arxiv.org/abs/2404.16807v1)|null|
|**2024-04-25**|**A Short Survey of Human Mobility Prediction in Epidemic Modeling from Transformers to LLMs**|This paper provides a comprehensive survey of recent advancements in
leveraging machine learning techniques, particularly Transformer models, for
predicting human mobility patterns during epidemics. Understanding how people
move during epidemics is essential for modeling the spread of diseases and
devising effective response strategies. Forecasting population movement is
crucial for informing epidemiological models and facilitating effective
response planning in public health emergencies. Predicting mobility patterns
can enable authorities to better anticipate the geographical and temporal
spread of diseases, allocate resources more efficiently, and implement targeted
interventions. We review a range of approaches utilizing both pretrained
language models like BERT and Large Language Models (LLMs) tailored
specifically for mobility prediction tasks. These models have demonstrated
significant potential in capturing complex spatio-temporal dependencies and
contextual patterns in textual data.|Christian N. Mayemba et.al.|[2404.16921v1](http://arxiv.org/abs/2404.16921v1)|null|
|**2024-04-25**|**AAPL: Adding Attributes to Prompt Learning for Vision-Language Models**|Recent advances in large pre-trained vision-language models have demonstrated
remarkable performance on zero-shot downstream tasks. Building upon this,
recent studies, such as CoOp and CoCoOp, have proposed the use of prompt
learning, where context within a prompt is replaced with learnable vectors,
leading to significant improvements over manually crafted prompts. However, the
performance improvement for unseen classes is still marginal, and to tackle
this problem, data augmentation has been frequently used in traditional
zero-shot learning techniques. Through our experiments, we have identified
important issues in CoOp and CoCoOp: the context learned through traditional
image augmentation is biased toward seen classes, negatively impacting
generalization to unseen classes. To address this problem, we propose
adversarial token embedding to disentangle low-level visual augmentation
features from high-level class information when inducing bias in learnable
prompts. Through our novel mechanism called "Adding Attributes to Prompt
Learning", AAPL, we guide the learnable context to effectively extract text
features by focusing on high-level features for unseen classes. We have
conducted experiments across 11 datasets, and overall, AAPL shows favorable
performances compared to the existing methods in few-shot learning, zero-shot
learning, cross-dataset, and domain generalization tasks.|Gahyeon Kim et.al.|[2404.16804v1](http://arxiv.org/abs/2404.16804v1)|[link](https://github.com/Gahyeonkim09/AAPL)|
|**2024-04-25**|**Weak-to-Strong Extrapolation Expedites Alignment**|Although the capabilities of large language models (LLMs) ideally scale up
with increasing data and compute, they are inevitably constrained by limited
resources in reality. Suppose we have a moderately trained LLM (e.g., trained
to align with human preference) in hand, can we further exploit its potential
and cheaply acquire a stronger model? In this paper, we propose a simple method
called ExPO to boost LLMs' alignment with human preference. ExPO assumes that a
medium-aligned model can be interpolated between a less-aligned (weaker) model,
e.g., the initial SFT model, and a better-aligned (stronger) one, thereby
directly obtaining this stronger model by extrapolating from the weights of the
former two relatively weaker models. On the AlpacaEval 2.0 benchmark, we show
that ExPO pushes models trained with less preference data (e.g., 10% or 20%) to
reach and even surpass the fully-trained one, without any additional training.
Furthermore, ExPO also significantly improves off-the-shelf DPO/RLHF models and
exhibits decent scalability across model sizes from 7B to 70B. Our work
demonstrates the efficacy of model extrapolation in exploiting LLMs'
capabilities, suggesting a promising direction that deserves future
exploration.|Chujie Zheng et.al.|[2404.16792v1](http://arxiv.org/abs/2404.16792v1)|[link](https://github.com/chujiezheng/llm-extrapolation)|
|**2024-04-25**|**Continual Learning of Large Language Models: A Comprehensive Survey**|The recent success of large language models (LLMs) trained on static,
pre-collected, general datasets has sparked numerous research directions and
applications. One such direction addresses the non-trivial challenge of
integrating pre-trained LLMs into dynamic data distributions, task structures,
and user preferences. Pre-trained LLMs, when tailored for specific needs, often
experience significant performance degradation in previous knowledge domains --
a phenomenon known as "catastrophic forgetting". While extensively studied in
the continual learning (CL) community, it presents new manifestations in the
realm of LLMs. In this survey, we provide a comprehensive overview of the
current research progress on LLMs within the context of CL. This survey is
structured into four main sections: we first describe an overview of
continually learning LLMs, consisting of two directions of continuity: vertical
continuity (or vertical continual learning), i.e., continual adaptation from
general to specific capabilities, and horizontal continuity (or horizontal
continual learning), i.e., continual adaptation across time and domains
(Section 3). We then summarize three stages of learning LLMs in the context of
modern CL: Continual Pre-Training (CPT), Domain-Adaptive Pre-training (DAP),
and Continual Fine-Tuning (CFT) (Section 4). Then we provide an overview of
evaluation protocols for continual learning with LLMs, along with the current
available data sources (Section 5). Finally, we discuss intriguing questions
pertaining to continual learning for LLMs (Section 6). The full list of papers
examined in this survey is available at
https://github.com/Wang-ML-Lab/llm-continual-learning-survey.|Haizhou Shi et.al.|[2404.16789v1](http://arxiv.org/abs/2404.16789v1)|[link](https://github.com/wang-ml-lab/llm-continual-learning-survey)|
|**2024-04-25**|**Modeling Selective Feature Attention for Representation-based Siamese Text Matching**|Representation-based Siamese networks have risen to popularity in lightweight
text matching due to their low deployment and inference costs. While word-level
attention mechanisms have been implemented within Siamese networks to improve
performance, we propose Feature Attention (FA), a novel downstream block
designed to enrich the modeling of dependencies among embedding features.
Employing "squeeze-and-excitation" techniques, the FA block dynamically adjusts
the emphasis on individual features, enabling the network to concentrate more
on features that significantly contribute to the final classification. Building
upon FA, we introduce a dynamic "selection" mechanism called Selective Feature
Attention (SFA), which leverages a stacked BiGRU Inception structure. The SFA
block facilitates multi-scale semantic extraction by traversing different
stacked BiGRU layers, encouraging the network to selectively concentrate on
semantic information and embedding features across varying levels of
abstraction. Both the FA and SFA blocks offer a seamless integration capability
with various Siamese networks, showcasing a plug-and-play characteristic.
Experimental evaluations conducted across diverse text matching baselines and
benchmarks underscore the indispensability of modeling feature attention and
the superiority of the "selection" mechanism.|Jianxiang Zang et.al.|[2404.16776v1](http://arxiv.org/abs/2404.16776v1)|[link](https://github.com/hggzjx/sfa)|
|**2024-04-25**|**REBEL: Reinforcement Learning via Regressing Relative Rewards**|While originally developed for continuous control problems, Proximal Policy
Optimization (PPO) has emerged as the work-horse of a variety of reinforcement
learning (RL) applications including the fine-tuning of generative models.
Unfortunately, PPO requires multiple heuristics to enable stable convergence
(e.g. value networks, clipping) and is notorious for its sensitivity to the
precise implementation of these components. In response, we take a step back
and ask what a minimalist RL algorithm for the era of generative models would
look like. We propose REBEL, an algorithm that cleanly reduces the problem of
policy optimization to regressing the relative rewards via a direct policy
parameterization between two completions to a prompt, enabling strikingly
lightweight implementation. In theory, we prove that fundamental RL algorithms
like Natural Policy Gradient can be seen as variants of REBEL, which allows us
to match the strongest known theoretical guarantees in terms of convergence and
sample complexity in the RL literature. REBEL can also cleanly incorporate
offline data and handle the intransitive preferences we frequently see in
practice. Empirically, we find that REBEL provides a unified approach to
language modeling and image generation with stronger or similar performance as
PPO and DPO, all while being simpler to implement and more computationally
tractable than PPO.|Zhaolin Gao et.al.|[2404.16767v1](http://arxiv.org/abs/2404.16767v1)|null|
|**2024-04-25**|**Prefix Text as a Yarn: Eliciting Non-English Alignment in Foundation Language Model**|While supervised fine-tuning (SFT) has been a straightforward approach for
tailoring the output of foundation large language model (LLM) to specific
preferences, concerns have been raised about the depth of this alignment, with
some critiques suggesting it is merely "superficial". We critically examine
this hypothesis within the scope of cross-lingual generation tasks, proposing
that the effectiveness of SFT may be constrained by its reliance on prior
tokens to guide cross-lingual generation. Based on this crucial insight, and in
response to the challenges posed by the costly and limited availability of
non-English data for SFT, we introduce a novel training-free alignment method
named PreTTY, which employs minimal task-related prior tokens to bridge the
foundation LLM and the SFT LLM, achieving comparable performance without
training. Experiments on machine translation and part-of-speech tagging across
eight languages demonstrate the efficacy of PreTTY in cross-lingual settings.
Remarkably, by initiating the decoding process with only one or two prior
tokens, foundation LLMs can achieve performance comparable to their SFT
counterparts. This method presents a cost-effective alternative to SFT and
advances the democratization of multilingual LLMs.|Runzhe Zhan et.al.|[2404.16766v1](http://arxiv.org/abs/2404.16766v1)|null|
|**2024-04-25**|**Automatic Speech Recognition System-Independent Word Error Rate Estimation**|Word error rate (WER) is a metric used to evaluate the quality of
transcriptions produced by Automatic Speech Recognition (ASR) systems. In many
applications, it is of interest to estimate WER given a pair of a speech
utterance and a transcript. Previous work on WER estimation focused on building
models that are trained with a specific ASR system in mind (referred to as ASR
system-dependent). These are also domain-dependent and inflexible in real-world
applications. In this paper, a hypothesis generation method for ASR
System-Independent WER estimation (SIWE) is proposed. In contrast to prior
work, the WER estimators are trained using data that simulates ASR system
output. Hypotheses are generated using phonetically similar or linguistically
more likely alternative words. In WER estimation experiments, the proposed
method reaches a similar performance to ASR system-dependent WER estimators on
in-domain data and achieves state-of-the-art performance on out-of-domain data.
On the out-of-domain data, the SIWE model outperformed the baseline estimators
in root mean square error and Pearson correlation coefficient by relative
17.58% and 18.21%, respectively, on Switchboard and CALLHOME. The performance
was further improved when the WER of the training set was close to the WER of
the evaluation dataset.|Chanho Park et.al.|[2404.16743v2](http://arxiv.org/abs/2404.16743v2)|null|
|**2024-04-25**|**Distilling Privileged Information for Dubins Traveling Salesman Problems with Neighborhoods**|This paper presents a novel learning approach for Dubins Traveling Salesman
Problems(DTSP) with Neighborhood (DTSPN) to quickly produce a tour of a
non-holonomic vehicle passing through neighborhoods of given task points. The
method involves two learning phases: initially, a model-free reinforcement
learning approach leverages privileged information to distill knowledge from
expert trajectories generated by the LinKernighan heuristic (LKH) algorithm.
Subsequently, a supervised learning phase trains an adaptation network to solve
problems independently of privileged information. Before the first learning
phase, a parameter initialization technique using the demonstration data was
also devised to enhance training efficiency. The proposed learning method
produces a solution about 50 times faster than LKH and substantially
outperforms other imitation learning and RL with demonstration schemes, most of
which fail to sense all the task points.|Min Kyu Shin et.al.|[2404.16721v1](http://arxiv.org/abs/2404.16721v1)|null|
|**2024-04-25**|**Features Fusion for Dual-View Mammography Mass Detection**|Detection of malignant lesions on mammography images is extremely important
for early breast cancer diagnosis. In clinical practice, images are acquired
from two different angles, and radiologists can fully utilize information from
both views, simultaneously locating the same lesion. However, for automatic
detection approaches such information fusion remains a challenge. In this
paper, we propose a new model called MAMM-Net, which allows the processing of
both mammography views simultaneously by sharing information not only on an
object level, as seen in existing works, but also on a feature level.
MAMM-Net's key component is the Fusion Layer, based on deformable attention and
designed to increase detection precision while keeping high recall. Our
experiments show superior performance on the public DDSM dataset compared to
the previous state-of-the-art model, while introducing new helpful features
such as lesion annotation on pixel-level and classification of lesions
malignancy.|Arina Varlamova et.al.|[2404.16718v1](http://arxiv.org/abs/2404.16718v1)|null|
|**2024-04-25**|**Embracing Diversity: Interpretable Zero-shot classification beyond one vector per class**|Vision-language models enable open-world classification of objects without
the need for any retraining. While this zero-shot paradigm marks a significant
advance, even today's best models exhibit skewed performance when objects are
dissimilar from their typical depiction. Real world objects such as pears
appear in a variety of forms -- from diced to whole, on a table or in a bowl --
yet standard VLM classifiers map all instances of a class to a \it{single
vector based on the class label}. We argue that to represent this rich
diversity within a class, zero-shot classification should move beyond a single
vector. We propose a method to encode and account for diversity within a class
using inferred attributes, still in the zero-shot setting without retraining.
We find our method consistently outperforms standard zero-shot classification
over a large suite of datasets encompassing hierarchies, diverse object states,
and real-world geographic diversity, as well finer-grained datasets where
intra-class diversity may be less prevalent. Importantly, our method is
inherently interpretable, offering faithful explanations for each inference to
facilitate model debugging and enhance transparency. We also find our method
scales efficiently to a large number of attributes to account for diversity --
leading to more accurate predictions for atypical instances. Finally, we
characterize a principled trade-off between overall and worst class accuracy,
which can be tuned via a hyperparameter of our method. We hope this work spurs
further research into the promise of zero-shot classification beyond a single
class vector for capturing diversity in the world, and building transparent AI
systems without compromising performance.|Mazda Moayeri et.al.|[2404.16717v1](http://arxiv.org/abs/2404.16717v1)|null|
|**2024-04-25**|**Layer Skip: Enabling Early Exit Inference and Self-Speculative Decoding**|We present LayerSkip, an end-to-end solution to speed-up inference of large
language models (LLMs). First, during training we apply layer dropout, with low
dropout rates for earlier layers and higher dropout rates for later layers, and
an early exit loss where all transformer layers share the same exit. Second,
during inference, we show that this training recipe increases the accuracy of
early exit at earlier layers, without adding any auxiliary layers or modules to
the model. Third, we present a novel self-speculative decoding solution where
we exit at early layers and verify and correct with remaining layers of the
model. Our proposed self-speculative decoding approach has less memory
footprint than other speculative decoding approaches and benefits from shared
compute and activations of the draft and verification stages. We run
experiments on different Llama model sizes on different types of training:
pretraining from scratch, continual pretraining, finetuning on specific data
domain, and finetuning on specific task. We implement our inference solution
and show speedups of up to 2.16x on summarization for CNN/DM documents, 1.82x
on coding, and 2.0x on TOPv2 semantic parsing task.|Mostafa Elhoushi et.al.|[2404.16710v1](http://arxiv.org/abs/2404.16710v1)|null|
|**2024-04-25**|**Cooperate or Collapse: Emergence of Sustainability Behaviors in a Society of LLM Agents**|In the rapidly evolving field of artificial intelligence, ensuring safe
decision-making of Large Language Models (LLMs) is a significant challenge.
This paper introduces Governance of the Commons Simulation (GovSim), a
simulation platform designed to study strategic interactions and cooperative
decision-making in LLMs. Through this simulation environment, we explore the
dynamics of resource sharing among AI agents, highlighting the importance of
ethical considerations, strategic planning, and negotiation skills. GovSim is
versatile and supports any text-based agent, including LLMs agents. Using the
Generative Agent framework, we create a standard agent that facilitates the
integration of different LLMs. Our findings reveal that within GovSim, only two
out of 15 tested LLMs managed to achieve a sustainable outcome, indicating a
significant gap in the ability of models to manage shared resources.
Furthermore, we find that by removing the ability of agents to communicate,
they overuse the shared resource, highlighting the importance of communication
for cooperation. Interestingly, most LLMs lack the ability to make
universalized hypotheses, which highlights a significant weakness in their
reasoning skills. We open source the full suite of our research results,
including the simulation environment, agent prompts, and a comprehensive web
interface.|Giorgio Piatti et.al.|[2404.16698v1](http://arxiv.org/abs/2404.16698v1)|null|
|**2024-04-25**|**Influence of Solution Efficiency and Valence of Instruction on Additive and Subtractive Solution Strategies in Humans and GPT-4**|We explored the addition bias, a cognitive tendency to prefer adding elements
over removing them to alter an initial state or structure, by conducting four
preregistered experiments examining the problem-solving behavior of both humans
and OpenAl's GPT-4 large language model. The experiments involved 588
participants from the U.S. and 680 iterations of the GPT-4 model. The
problem-solving task was either to create symmetry within a grid (Experiments 1
and 3) or to edit a summary (Experiments 2 and 4). As hypothesized, we found
that overall, the addition bias was present. Solution efficiency (Experiments 1
and 2) and valence of the instruction (Experiments 3 and 4) played important
roles. Human participants were less likely to use additive strategies when
subtraction was relatively more efficient than when addition and subtraction
were equally efficient. GPT-4 exhibited the opposite behavior, with a strong
addition bias when subtraction was more efficient. In terms of instruction
valence, GPT-4 was more likely to add words when asked to "improve" compared to
"edit", whereas humans did not show this effect. When we looked at the addition
bias under different conditions, we found more biased responses for GPT-4
compared to humans. Our findings highlight the importance of considering
comparable and sometimes superior subtractive alternatives, as well as
reevaluating one's own and particularly the language models' problem-solving
behavior.|Lydia Uhler et.al.|[2404.16692v1](http://arxiv.org/abs/2404.16692v1)|null|
|**2024-04-25**|**Prediction Is All MoE Needs: Expert Load Distribution Goes from Fluctuating to Stabilizing**|MoE facilitates the development of large models by making the computational
complexity of the model no longer scale linearly with increasing parameters.
The learning sparse gating network selects a set of experts for each token to
be processed; however, this may lead to differences in the number of tokens
processed by each expert over several successive iterations, i.e., the expert
load fluctuations, which reduces computational parallelization and resource
utilization. To this end, we traced and analyzed loads of each expert in the
training iterations for several large language models in this work, and defined
the transient state with "obvious load fluctuation" and the stable state with
"temporal locality". Moreover, given the characteristics of these two states
and the computational overhead, we deployed three classical prediction
algorithms that achieve accurate expert load prediction results. For the GPT3
350M model, the average error rates for predicting the expert load proportion
over the next 1,000 and 2,000 steps are approximately 1.3% and 1.8%,
respectively. This work can provide valuable guidance for expert placement or
resource allocation for MoE model training. Based on this work, we will propose
an expert placement scheme for transient and stable states in our coming work.|Peizhuang Cong et.al.|[2404.16914v1](http://arxiv.org/abs/2404.16914v1)|null|
|**2024-04-25**|**DE-CGAN: Boosting rTMS Treatment Prediction with Diversity Enhancing Conditional Generative Adversarial Networks**|Repetitive Transcranial Magnetic Stimulation (rTMS) is a well-supported,
evidence-based treatment for depression. However, patterns of response to this
treatment are inconsistent. Emerging evidence suggests that artificial
intelligence can predict rTMS treatment outcomes for most patients using fMRI
connectivity features. While these models can reliably predict treatment
outcomes for many patients for some underrepresented fMRI connectivity measures
DNN models are unable to reliably predict treatment outcomes. As such we
propose a novel method, Diversity Enhancing Conditional General Adversarial
Network (DE-CGAN) for oversampling these underrepresented examples. DE-CGAN
creates synthetic examples in difficult-to-classify regions by first
identifying these data points and then creating conditioned synthetic examples
to enhance data diversity. Through empirical experiments we show that a
classification model trained using a diversity enhanced training set
outperforms traditional data augmentation techniques and existing benchmark
results. This work shows that increasing the diversity of a training dataset
can improve classification model performance. Furthermore, this work provides
evidence for the utility of synthetic patients providing larger more robust
datasets for both AI researchers and psychiatrists to explore variable
relationships.|Matthew Squires et.al.|[2404.16913v1](http://arxiv.org/abs/2404.16913v1)|null|
|**2024-04-25**|**EmoVIT: Revolutionizing Emotion Insights with Visual Instruction Tuning**|Visual Instruction Tuning represents a novel learning paradigm involving the
fine-tuning of pre-trained language models using task-specific instructions.
This paradigm shows promising zero-shot results in various natural language
processing tasks but is still unexplored in vision emotion understanding. In
this work, we focus on enhancing the model's proficiency in understanding and
adhering to instructions related to emotional contexts. Initially, we identify
key visual clues critical to visual emotion recognition. Subsequently, we
introduce a novel GPT-assisted pipeline for generating emotion visual
instruction data, effectively addressing the scarcity of annotated instruction
data in this domain. Expanding on the groundwork established by InstructBLIP,
our proposed EmoVIT architecture incorporates emotion-specific instruction
data, leveraging the powerful capabilities of Large Language Models to enhance
performance. Through extensive experiments, our model showcases its proficiency
in emotion classification, adeptness in affective reasoning, and competence in
comprehending humor. The comparative analysis provides a robust benchmark for
Emotion Visual Instruction Tuning in the era of LLMs, providing valuable
insights and opening avenues for future exploration in this domain. Our code is
available at \url{https://github.com/aimmemotion/EmoVIT}.|Hongxia Xie et.al.|[2404.16670v1](http://arxiv.org/abs/2404.16670v1)|[link](https://github.com/aimmemotion/emovit)|
|**2024-04-25**|**Formal Specification, Assessment, and Enforcement of Fairness for Generative AIs**|Reinforcing or even exacerbating societal biases and inequalities will
increase significantly as generative AI increasingly produces useful artifacts,
from text to images and beyond, for the real world. We address these issues by
formally characterizing the notion of fairness for generative AI as a basis for
monitoring and enforcing fairness. We define two levels of fairness using the
notion of infinite sequences of abstractions of AI-generated artifacts such as
text or images. The first is the fairness demonstrated on the generated
sequences, which is evaluated only on the outputs while agnostic to the prompts
and models used. The second is the inherent fairness of the generative AI
model, which requires that fairness be manifested when input prompts are
neutral, that is, they do not explicitly instruct the generative AI to produce
a particular type of output. We also study relative intersectional fairness to
counteract the combinatorial explosion of fairness when considering multiple
categories together with lazy fairness enforcement. Finally, fairness
monitoring and enforcement are tested against some current generative AI
models.|Chih-Hong Cheng et.al.|[2404.16663v2](http://arxiv.org/abs/2404.16663v2)|[link](https://github.com/semta-group/fairgenai)|
|**2024-04-25**|**Benchmarking Mobile Device Control Agents across Diverse Configurations**|Developing autonomous agents for mobile devices can significantly enhance
user interactions by offering increased efficiency and accessibility. However,
despite the growing interest in mobile device control agents, the absence of a
commonly adopted benchmark makes it challenging to quantify scientific progress
in this area. In this work, we introduce B-MoCA: a novel benchmark designed
specifically for evaluating mobile device control agents. To create a realistic
benchmark, we develop B-MoCA based on the Android operating system and define
60 common daily tasks. Importantly, we incorporate a randomization feature that
changes various aspects of mobile devices, including user interface layouts and
language settings, to assess generalization performance. We benchmark diverse
agents, including agents employing large language models (LLMs) or multi-modal
LLMs as well as agents trained from scratch using human expert demonstrations.
While these agents demonstrate proficiency in executing straightforward tasks,
their poor performance on complex tasks highlights significant opportunities
for future research to enhance their effectiveness. Our source code is publicly
available at https://b-moca.github.io.|Juyong Lee et.al.|[2404.16660v1](http://arxiv.org/abs/2404.16660v1)|null|
|**2024-04-25**|**ProbGate at EHRSQL 2024: Enhancing SQL Query Generation Accuracy through Probabilistic Threshold Filtering and Error Handling**|Recently, deep learning-based language models have significantly enhanced
text-to-SQL tasks, with promising applications in retrieving patient records
within the medical domain. One notable challenge in such applications is
discerning unanswerable queries. Through fine-tuning model, we demonstrate the
feasibility of converting medical record inquiries into SQL queries.
Additionally, we introduce an entropy-based method to identify and filter out
unanswerable results. We further enhance result quality by filtering
low-confidence SQL through log probability-based distribution, while
grammatical and schema errors are mitigated by executing queries on the actual
database. We experimentally verified that our method can filter unanswerable
questions, which can be widely utilized even when the parameters of the model
are not accessible, and that it can be effectively utilized in practice.|Sangryul Kim et.al.|[2404.16659v1](http://arxiv.org/abs/2404.16659v1)|[link](https://github.com/venzino-han/probgate_ehrsql)|
|**2024-04-25**|**A Self-Organizing Clustering System for Unsupervised Distribution Shift Detection**|Modeling non-stationary data is a challenging problem in the field of
continual learning, and data distribution shifts may result in negative
consequences on the performance of a machine learning model. Classic learning
tools are often vulnerable to perturbations of the input covariates, and are
sensitive to outliers and noise, and some tools are based on rigid algebraic
assumptions. Distribution shifts are frequently occurring due to changes in raw
materials for production, seasonality, a different user base, or even
adversarial attacks. Therefore, there is a need for more effective distribution
shift detection techniques.
  In this work, we propose a continual learning framework for monitoring and
detecting distribution changes. We explore the problem in a latent space
generated by a bio-inspired self-organizing clustering and statistical aspects
of the latent space. In particular, we investigate the projections made by two
topology-preserving maps: the Self-Organizing Map and the Scale Invariant Map.
Our method can be applied in both a supervised and an unsupervised context. We
construct the assessment of changes in the data distribution as a comparison of
Gaussian signals, making the proposed method fast and robust. We compare it to
other unsupervised techniques, specifically Principal Component Analysis (PCA)
and Kernel-PCA. Our comparison involves conducting experiments using sequences
of images (based on MNIST and injected shifts with adversarial samples),
chemical sensor measurements, and the environmental variable related to ozone
levels. The empirical study reveals the potential of the proposed approach.|Sebastián Basterrech et.al.|[2404.16656v1](http://arxiv.org/abs/2404.16656v1)|null|
|**2024-04-25**|**Análise de ambiguidade linguística em modelos de linguagem de grande escala (LLMs)**|Linguistic ambiguity continues to represent a significant challenge for
natural language processing (NLP) systems, notwithstanding the advancements in
architectures such as Transformers and BERT. Inspired by the recent success of
instructional models like ChatGPT and Gemini (In 2023, the artificial
intelligence was called Bard.), this study aims to analyze and discuss
linguistic ambiguity within these models, focusing on three types prevalent in
Brazilian Portuguese: semantic, syntactic, and lexical ambiguity. We create a
corpus comprising 120 sentences, both ambiguous and unambiguous, for
classification, explanation, and disambiguation. The models capability to
generate ambiguous sentences was also explored by soliciting sets of sentences
for each type of ambiguity. The results underwent qualitative analysis, drawing
on recognized linguistic references, and quantitative assessment based on the
accuracy of the responses obtained. It was evidenced that even the most
sophisticated models, such as ChatGPT and Gemini, exhibit errors and
deficiencies in their responses, with explanations often providing
inconsistent. Furthermore, the accuracy peaked at 49.58 percent, indicating the
need for descriptive studies for supervised learning.|Lavínia de Carvalho Moraes et.al.|[2404.16653v1](http://arxiv.org/abs/2404.16653v1)|null|
|**2024-04-25**|**Tele-FLM Technical Report**|Large language models (LLMs) have showcased profound capabilities in language
understanding and generation, facilitating a wide array of applications.
However, there is a notable paucity of detailed, open-sourced methodologies on
efficiently scaling LLMs beyond 50 billion parameters with minimum
trial-and-error cost and computational resources. In this report, we introduce
Tele-FLM (aka FLM-2), a 52B open-sourced multilingual large language model that
features a stable, efficient pre-training paradigm and enhanced factual
judgment capabilities. Tele-FLM demonstrates superior multilingual language
modeling abilities, measured by BPB on textual corpus. Besides, in both English
and Chinese foundation model evaluation, it is comparable to strong
open-sourced models that involve larger pre-training FLOPs, such as Llama2-70B
and DeepSeek-67B. In addition to the model weights, we share the core designs,
engineering practices, and training details, which we expect to benefit both
the academic and industrial communities.|Xiang Li et.al.|[2404.16645v1](http://arxiv.org/abs/2404.16645v1)|null|
|**2024-04-25**|**Legal Aspects for Software Developers Interested in Generative AI Applications**|Recent successes in Generative Artificial Intelligence (GenAI) have led to
new technologies capable of generating high-quality code, natural language, and
images. The next step is to integrate GenAI technology into products, a task
typically conducted by software developers. Such product development always
comes with a certain risk of liability. Within this article, we want to shed
light on the current state of two such risks: data protection and copyright.
Both aspects are crucial for GenAI. This technology deals with data for both
model training and generated output. We summarize key aspects regarding our
current knowledge that every software developer involved in product development
using GenAI should be aware of to avoid critical mistakes that may expose them
to liability claims.|Steffen Herbold et.al.|[2404.16630v1](http://arxiv.org/abs/2404.16630v1)|null|
|**2024-04-25**|**Incorporating Lexical and Syntactic Knowledge for Unsupervised Cross-Lingual Transfer**|Unsupervised cross-lingual transfer involves transferring knowledge between
languages without explicit supervision. Although numerous studies have been
conducted to improve performance in such tasks by focusing on cross-lingual
knowledge, particularly lexical and syntactic knowledge, current approaches are
limited as they only incorporate syntactic or lexical information. Since each
type of information offers unique advantages and no previous attempts have
combined both, we attempt to explore the potential of this approach. In this
paper, we present a novel framework called "Lexicon-Syntax Enhanced
Multilingual BERT" that combines both lexical and syntactic knowledge.
Specifically, we use Multilingual BERT (mBERT) as the base model and employ two
techniques to enhance its learning capabilities. The code-switching technique
is used to implicitly teach the model lexical alignment information, while a
syntactic-based graph attention network is designed to help the model encode
syntactic structure. To integrate both types of knowledge, we input
code-switched sequences into both the syntactic module and the mBERT base model
simultaneously. Our extensive experimental results demonstrate this framework
can consistently outperform all baselines of zero-shot cross-lingual transfer,
with the gains of 1.0~3.7 points on text classification, named entity
recognition (ner), and semantic parsing tasks. Keywords:cross-lingual transfer,
lexicon, syntax, code-switching, graph attention network|Jianyu Zheng et.al.|[2404.16627v1](http://arxiv.org/abs/2404.16627v1)|[link](https://github.com/tian14267/ls_mbert)|
|**2024-04-25**|**Hippocrates: An Open-Source Framework for Advancing Large Language Models in Healthcare**|The integration of Large Language Models (LLMs) into healthcare promises to
transform medical diagnostics, research, and patient care. Yet, the progression
of medical LLMs faces obstacles such as complex training requirements, rigorous
evaluation demands, and the dominance of proprietary models that restrict
academic exploration. Transparent, comprehensive access to LLM resources is
essential for advancing the field, fostering reproducibility, and encouraging
innovation in healthcare AI. We present Hippocrates, an open-source LLM
framework specifically developed for the medical domain. In stark contrast to
previous efforts, it offers unrestricted access to its training datasets,
codebase, checkpoints, and evaluation protocols. This open approach is designed
to stimulate collaborative research, allowing the community to build upon,
refine, and rigorously evaluate medical LLMs within a transparent ecosystem.
Also, we introduce Hippo, a family of 7B models tailored for the medical
domain, fine-tuned from Mistral and LLaMA2 through continual pre-training,
instruction tuning, and reinforcement learning from human and AI feedback. Our
models outperform existing open medical LLMs models by a large-margin, even
surpassing models with 70B parameters. Through Hippocrates, we aspire to unlock
the full potential of LLMs not just to advance medical knowledge and patient
care but also to democratize the benefits of AI research in healthcare, making
them available across the globe.|Emre Can Acikgoz et.al.|[2404.16621v1](http://arxiv.org/abs/2404.16621v1)|null|
|**2024-04-25**|**SFMViT: SlowFast Meet ViT in Chaotic World**|The task of spatiotemporal action localization in chaotic scenes is a
challenging task toward advanced video understanding. Paving the way with
high-quality video feature extraction and enhancing the precision of
detector-predicted anchors can effectively improve model performance. To this
end, we propose a high-performance dual-stream spatiotemporal feature
extraction network SFMViT with an anchor pruning strategy. The backbone of our
SFMViT is composed of ViT and SlowFast with prior knowledge of spatiotemporal
action localization, which fully utilizes ViT's excellent global feature
extraction capabilities and SlowFast's spatiotemporal sequence modeling
capabilities. Secondly, we introduce the confidence maximum heap to prune the
anchors detected in each frame of the picture to filter out the effective
anchors. These designs enable our SFMViT to achieve a mAP of 26.62% in the
Chaotic World dataset, far exceeding existing models. Code is available at
https://github.com/jfightyr/SlowFast-Meet-ViT.|Jiaying Lin et.al.|[2404.16609v1](http://arxiv.org/abs/2404.16609v1)|[link](https://github.com/jfightyr/slowfast-meet-vit)|
|**2024-04-25**|**Understanding Privacy Risks of Embeddings Induced by Large Language Models**|Large language models (LLMs) show early signs of artificial general
intelligence but struggle with hallucinations. One promising solution to
mitigate these hallucinations is to store external knowledge as embeddings,
aiding LLMs in retrieval-augmented generation. However, such a solution risks
compromising privacy, as recent studies experimentally showed that the original
text can be partially reconstructed from text embeddings by pre-trained
language models. The significant advantage of LLMs over traditional pre-trained
models may exacerbate these concerns. To this end, we investigate the
effectiveness of reconstructing original knowledge and predicting entity
attributes from these embeddings when LLMs are employed. Empirical findings
indicate that LLMs significantly improve the accuracy of two evaluated tasks
over those from pre-trained models, regardless of whether the texts are
in-distribution or out-of-distribution. This underscores a heightened potential
for LLMs to jeopardize user privacy, highlighting the negative consequences of
their widespread use. We further discuss preliminary strategies to mitigate
this risk.|Zhihao Zhu et.al.|[2404.16587v1](http://arxiv.org/abs/2404.16587v1)|null|
|**2024-04-25**|**Neural Interaction Energy for Multi-Agent Trajectory Prediction**|Maintaining temporal stability is crucial in multi-agent trajectory
prediction. Insufficient regularization to uphold this stability often results
in fluctuations in kinematic states, leading to inconsistent predictions and
the amplification of errors. In this study, we introduce a framework called
Multi-Agent Trajectory prediction via neural interaction Energy (MATE). This
framework assesses the interactive motion of agents by employing neural
interaction energy, which captures the dynamics of interactions and illustrates
their influence on the future trajectories of agents. To bolster temporal
stability, we introduce two constraints: inter-agent interaction constraint and
intra-agent motion constraint. These constraints work together to ensure
temporal stability at both the system and agent levels, effectively mitigating
prediction fluctuations inherent in multi-agent systems. Comparative
evaluations against previous methods on four diverse datasets highlight the
superior prediction accuracy and generalization capabilities of our model.|Kaixin Shen et.al.|[2404.16579v1](http://arxiv.org/abs/2404.16579v1)|null|
|**2024-04-25**|**Exploring Internal Numeracy in Language Models: A Case Study on ALBERT**|It has been found that Transformer-based language models have the ability to
perform basic quantitative reasoning. In this paper, we propose a method for
studying how these models internally represent numerical data, and use our
proposal to analyze the ALBERT family of language models. Specifically, we
extract the learned embeddings these models use to represent tokens that
correspond to numbers and ordinals, and subject these embeddings to Principal
Component Analysis (PCA). PCA results reveal that ALBERT models of different
sizes, trained and initialized separately, consistently learn to use the axes
of greatest variation to represent the approximate ordering of various
numerical concepts. Numerals and their textual counterparts are represented in
separate clusters, but increase along the same direction in 2D space. Our
findings illustrate that language models, trained purely to model text, can
intuit basic mathematical concepts, opening avenues for NLP applications that
intersect with quantitative reasoning.|Ulme Wennberg et.al.|[2404.16574v1](http://arxiv.org/abs/2404.16574v1)|null|
|**2024-04-25**|**Evaluating Large Language Models on Time Series Feature Understanding: A Comprehensive Taxonomy and Benchmark**|Large Language Models (LLMs) offer the potential for automatic time series
analysis and reporting, which is a critical task across many domains, spanning
healthcare, finance, climate, energy, and many more. In this paper, we propose
a framework for rigorously evaluating the capabilities of LLMs on time series
understanding, encompassing both univariate and multivariate forms. We
introduce a comprehensive taxonomy of time series features, a critical
framework that delineates various characteristics inherent in time series data.
Leveraging this taxonomy, we have systematically designed and synthesized a
diverse dataset of time series, embodying the different outlined features. This
dataset acts as a solid foundation for assessing the proficiency of LLMs in
comprehending time series. Our experiments shed light on the strengths and
limitations of state-of-the-art LLMs in time series understanding, revealing
which features these models readily comprehend effectively and where they
falter. In addition, we uncover the sensitivity of LLMs to factors including
the formatting of the data, the position of points queried within a series and
the overall time series length.|Elizabeth Fons et.al.|[2404.16563v1](http://arxiv.org/abs/2404.16563v1)|null|
|**2024-04-25**|**Evolve Cost-aware Acquisition Functions Using Large Language Models**|Many real-world optimization scenarios involve expensive evaluation with
unknown and heterogeneous costs. Cost-aware Bayesian optimization stands out as
a prominent solution in addressing these challenges. To approach the global
optimum within a limited budget in a cost-efficient manner, the design of
cost-aware acquisition functions (AFs) becomes a crucial step. However,
traditional manual design paradigm typically requires extensive domain
knowledge and involves a labor-intensive trial-and-error process. This paper
introduces EvolCAF, a novel framework that integrates large language models
(LLMs) with evolutionary computation (EC) to automatically design cost-aware
AFs. Leveraging the crossover and mutation in the algorithm space, EvolCAF
offers a novel design paradigm, significantly reduces the reliance on domain
expertise and model training. The designed cost-aware AF maximizes the
utilization of available information from historical data, surrogate models and
budget details. It introduces novel ideas not previously explored in the
existing literature on acquisition function design, allowing for clear
interpretations to provide insights into its behavior and decision-making
process. In comparison to the well-known EIpu and EI-cool methods designed by
human experts, our approach showcases remarkable efficiency and generalization
across various tasks, including 12 synthetic problems and 3 real-world
hyperparameter tuning test sets.|Yiming Yao et.al.|[2404.16906v1](http://arxiv.org/abs/2404.16906v1)|null|
|**2024-04-25**|**DeepKalPose: An Enhanced Deep-Learning Kalman Filter for Temporally Consistent Monocular Vehicle Pose Estimation**|This paper presents DeepKalPose, a novel approach for enhancing temporal
consistency in monocular vehicle pose estimation applied on video through a
deep-learning-based Kalman Filter. By integrating a Bi-directional Kalman
filter strategy utilizing forward and backward time-series processing, combined
with a learnable motion model to represent complex motion patterns, our method
significantly improves pose accuracy and robustness across various conditions,
particularly for occluded or distant vehicles. Experimental validation on the
KITTI dataset confirms that DeepKalPose outperforms existing methods in both
pose accuracy and temporal consistency.|Leandro Di Bella et.al.|[2404.16558v1](http://arxiv.org/abs/2404.16558v1)|null|
|**2024-04-25**|**Energy-Latency Manipulation of Multi-modal Large Language Models via Verbose Samples**|Despite the exceptional performance of multi-modal large language models
(MLLMs), their deployment requires substantial computational resources. Once
malicious users induce high energy consumption and latency time (energy-latency
cost), it will exhaust computational resources and harm availability of
service. In this paper, we investigate this vulnerability for MLLMs,
particularly image-based and video-based ones, and aim to induce high
energy-latency cost during inference by crafting an imperceptible perturbation.
We find that high energy-latency cost can be manipulated by maximizing the
length of generated sequences, which motivates us to propose verbose samples,
including verbose images and videos. Concretely, two modality non-specific
losses are proposed, including a loss to delay end-of-sequence (EOS) token and
an uncertainty loss to increase the uncertainty over each generated token. In
addition, improving diversity is important to encourage longer responses by
increasing the complexity, which inspires the following modality specific loss.
For verbose images, a token diversity loss is proposed to promote diverse
hidden states. For verbose videos, a frame feature diversity loss is proposed
to increase the feature diversity among frames. To balance these losses, we
propose a temporal weight adjustment algorithm. Experiments demonstrate that
our verbose samples can largely extend the length of generated sequences.|Kuofeng Gao et.al.|[2404.16557v1](http://arxiv.org/abs/2404.16557v1)|null|
|**2024-04-25**|**Developing Acoustic Models for Automatic Speech Recognition in Swedish**|This paper is concerned with automatic continuous speech recognition using
trainable systems. The aim of this work is to build acoustic models for spoken
Swedish. This is done employing hidden Markov models and using the SpeechDat
database to train their parameters. Acoustic modeling has been worked out at a
phonetic level, allowing general speech recognition applications, even though a
simplified task (digits and natural number recognition) has been considered for
model evaluation. Different kinds of phone models have been tested, including
context independent models and two variations of context dependent models.
Furthermore many experiments have been done with bigram language models to tune
some of the system parameters. System performance over various speaker subsets
with different sex, age and dialect has also been examined. Results are
compared to previous similar studies showing a remarkable improvement.|Giampiero Salvi et.al.|[2404.16547v1](http://arxiv.org/abs/2404.16547v1)|null|
|**2024-04-25**|**Samsung Research China-Beijing at SemEval-2024 Task 3: A multi-stage framework for Emotion-Cause Pair Extraction in Conversations**|In human-computer interaction, it is crucial for agents to respond to human
by understanding their emotions. Unraveling the causes of emotions is more
challenging. A new task named Multimodal Emotion-Cause Pair Extraction in
Conversations is responsible for recognizing emotion and identifying causal
expressions. In this study, we propose a multi-stage framework to generate
emotion and extract the emotion causal pairs given the target emotion. In the
first stage, Llama-2-based InstructERC is utilized to extract the emotion
category of each utterance in a conversation. After emotion recognition, a
two-stream attention model is employed to extract the emotion causal pairs
given the target emotion for subtask 2 while MuTEC is employed to extract
causal span for subtask 1. Our approach achieved first place for both of the
two subtasks in the competition.|Shen Zhang et.al.|[2404.16905v1](http://arxiv.org/abs/2404.16905v1)|null|
|**2024-04-25**|**SIDEs: Separating Idealization from Deceptive Explanations in xAI**|Explainable AI (xAI) methods are important for establishing trust in using
black-box models. However, recent criticism has mounted against current xAI
methods that they disagree, are necessarily false, and can be manipulated,
which has started to undermine the deployment of black-box models. Rudin (2019)
goes so far as to say that we should stop using black-box models altogether in
high-stakes cases because xAI explanations "must be wrong". However, strict
fidelity to the truth is historically not a desideratum in science.
Idealizations -- the intentional distortions introduced to scientific theories
and models -- are commonplace in the natural sciences and are seen as a
successful scientific tool. Thus, it is not falsehood qua falsehood that is the
issue. In this paper, I outline the need for xAI research to engage in
idealization evaluation. Drawing on the use of idealizations in the natural
sciences and philosophy of science, I introduce a novel framework for
evaluating whether xAI methods engage in successful idealizations or deceptive
explanations (SIDEs). SIDEs evaluates whether the limitations of xAI methods,
and the distortions that they introduce, can be part of a successful
idealization or are indeed deceptive distortions as critics suggest. I discuss
the role that existing research can play in idealization evaluation and where
innovation is necessary. Through a qualitative analysis we find that leading
feature importance methods and counterfactual explanations are subject to
idealization failure and suggest remedies for ameliorating idealization
failure.|Emily Sullivan et.al.|[2404.16534v1](http://arxiv.org/abs/2404.16534v1)|null|
|**2024-04-25**|**Global Concept Explanations for Graphs by Contrastive Learning**|Beyond improving trust and validating model fairness, xAI practices also have
the potential to recover valuable scientific insights in application domains
where little to no prior human intuition exists. To that end, we propose a
method to extract global concept explanations from the predictions of graph
neural networks to develop a deeper understanding of the tasks underlying
structure-property relationships. We identify concept explanations as dense
clusters in the self-explaining Megan models subgraph latent space. For each
concept, we optimize a representative prototype graph and optionally use GPT-4
to provide hypotheses about why each structure has a certain effect on the
prediction. We conduct computational experiments on synthetic and real-world
graph property prediction tasks. For the synthetic tasks we find that our
method correctly reproduces the structural rules by which they were created.
For real-world molecular property regression and classification tasks, we find
that our method rediscovers established rules of thumb. More specifically, our
results for molecular mutagenicity prediction indicate more fine-grained
resolution of structural details than existing explainability methods,
consistent with previous results from chemistry literature. Overall, our
results show promising capability to extract the underlying structure-property
relationships for complex graph property prediction tasks.|Jonas Teufel et.al.|[2404.16532v1](http://arxiv.org/abs/2404.16532v1)|[link](https://github.com/aimat-lab/megan_global_explanations)|
|**2024-04-25**|**Building a Japanese Document-Level Relation Extraction Dataset Assisted by Cross-Lingual Transfer**|Document-level Relation Extraction (DocRE) is the task of extracting all
semantic relationships from a document. While studies have been conducted on
English DocRE, limited attention has been given to DocRE in non-English
languages. This work delves into effectively utilizing existing English
resources to promote DocRE studies in non-English languages, with Japanese as
the representative case. As an initial attempt, we construct a dataset by
transferring an English dataset to Japanese. However, models trained on such a
dataset suffer from low recalls. We investigate the error cases and attribute
the failure to different surface structures and semantics of documents
translated from English and those written by native speakers. We thus switch to
explore if the transferred dataset can assist human annotation on Japanese
documents. In our proposal, annotators edit relation predictions from a model
trained on the transferred dataset. Quantitative analysis shows that relation
recommendations suggested by the model help reduce approximately 50% of the
human edit steps compared with the previous approach. Experiments quantify the
performance of existing DocRE models on our collected dataset, portraying the
challenges of Japanese and cross-lingual DocRE.|Youmi Ma et.al.|[2404.16506v1](http://arxiv.org/abs/2404.16506v1)|null|

### Medical
|Publish Date|Title|Authors|PDF|Code|
| :---: | :---: | :---: | :---: | :---: |
|**2024-04-26**|**Domain Adaptive and Fine-grained Anomaly Detection for Single-cell Sequencing Data and Beyond**|Fined-grained anomalous cell detection from affected tissues is critical for
clinical diagnosis and pathological research. Single-cell sequencing data
provide unprecedented opportunities for this task. However, current anomaly
detection methods struggle to handle domain shifts prevalent in multi-sample
and multi-domain single-cell sequencing data, leading to suboptimal
performance. Moreover, these methods fall short of distinguishing anomalous
cells into pathologically distinct subtypes. In response, we propose ACSleuth,
a novel, reconstruction deviation-guided generative framework that integrates
the detection, domain adaptation, and fine-grained annotating of anomalous
cells into a methodologically cohesive workflow. Notably, we present the first
theoretical analysis of using reconstruction deviations output by generative
models for anomaly detection in lieu of domain shifts. This analysis informs us
to develop a novel and superior maximum mean discrepancy-based anomaly scorer
in ACSleuth. Extensive benchmarks over various single-cell data and other types
of tabular data demonstrate ACSleuth's superiority over the state-of-the-art
methods in identifying and subtyping anomalies in multi-sample and multi-domain
contexts. Our code is available at https://github.com/Catchxu/ACsleuth.|Kaichen Xu et.al.|[2404.17454v1](http://arxiv.org/abs/2404.17454v1)|[link](https://github.com/catchxu/acsleuth)|
|**2024-04-26**|**M3BAT: Unsupervised Domain Adaptation for Multimodal Mobile Sensing with Multi-Branch Adversarial Training**|Over the years, multimodal mobile sensing has been used extensively for
inferences regarding health and well being, behavior, and context. However, a
significant challenge hindering the widespread deployment of such models in
real world scenarios is the issue of distribution shift. This is the phenomenon
where the distribution of data in the training set differs from the
distribution of data in the real world, the deployment environment. While
extensively explored in computer vision and natural language processing, and
while prior research in mobile sensing briefly addresses this concern, current
work primarily focuses on models dealing with a single modality of data, such
as audio or accelerometer readings, and consequently, there is little research
on unsupervised domain adaptation when dealing with multimodal sensor data. To
address this gap, we did extensive experiments with domain adversarial neural
networks (DANN) showing that they can effectively handle distribution shifts in
multimodal sensor data. Moreover, we proposed a novel improvement over DANN,
called M3BAT, unsupervised domain adaptation for multimodal mobile sensing with
multi-branch adversarial training, to account for the multimodality of sensor
data during domain adaptation with multiple branches. Through extensive
experiments conducted on two multimodal mobile sensing datasets, three
inference tasks, and 14 source-target domain pairs, including both regression
and classification, we demonstrate that our approach performs effectively on
unseen domains. Compared to directly deploying a model trained in the source
domain to the target domain, the model shows performance increases up to 12%
AUC (area under the receiver operating characteristics curves) on
classification tasks, and up to 0.13 MAE (mean absolute error) on regression
tasks.|Lakmal Meegahapola et.al.|[2404.17391v1](http://arxiv.org/abs/2404.17391v1)|null|
|**2024-04-26**|**Prevalent Frequency of Emotional and Physical Symptoms in Social Anxiety using Zero Shot Classification: An Observational Study**|Social anxiety represents a prevalent challenge in modern society, affecting
individuals across personal and professional spheres. Left unaddressed, this
condition can yield substantial negative consequences, impacting social
interactions and performance. Further understanding its diverse physical and
emotional symptoms becomes pivotal for comprehensive diagnosis and tailored
therapeutic interventions. This study analyze prevalence and frequency of
social anxiety symptoms taken from Mayo Clinic, exploring diverse human
experiences from utilizing a large Reddit dataset dedicated to this issue.
Leveraging these platforms, the research aims to extract insights and examine a
spectrum of physical and emotional symptoms linked to social anxiety disorder.
Upholding ethical considerations, the study maintains strict user anonymity
within the dataset. By employing a novel approach, the research utilizes
BART-based multi-label zero-shot classification to identify and measure symptom
prevalence and significance in the form of probability score for each symptom
under consideration. Results uncover distinctive patterns: "Trembling" emerges
as a prevalent physical symptom, while emotional symptoms like "Fear of being
judged negatively" exhibit high frequencies. These findings offer insights into
the multifaceted nature of social anxiety, aiding clinical practices and
interventions tailored to its diverse expressions.|Muhammad Rizwan et.al.|[2404.17183v1](http://arxiv.org/abs/2404.17183v1)|null|
|**2024-04-26**|**Deep Evidential Learning for Dose Prediction**|In this work, we present a novel application of an uncertainty-quantification
framework called Deep Evidential Learning in the domain of radiotherapy dose
prediction. Using medical images of the Open Knowledge-Based Planning Challenge
dataset, we found that this model can be effectively harnessed to yield
uncertainty estimates that inherited correlations with prediction errors upon
completion of network training. This was achieved only after reformulating the
original loss function for a stable implementation. We found that (i)epistemic
uncertainty was highly correlated with prediction errors, with various
association indices comparable or stronger than those for Monte-Carlo Dropout
and Deep Ensemble methods, (ii)the median error varied with uncertainty
threshold much more linearly for epistemic uncertainty in Deep Evidential
Learning relative to these other two conventional frameworks, indicative of a
more uniformly calibrated sensitivity to model errors, (iii)relative to
epistemic uncertainty, aleatoric uncertainty demonstrated a more significant
shift in its distribution in response to Gaussian noise added to CT intensity,
compatible with its interpretation as reflecting data noise. Collectively, our
results suggest that Deep Evidential Learning is a promising approach that can
endow deep-learning models in radiotherapy dose prediction with statistical
robustness. Towards enhancing its clinical relevance, we demonstrate how we can
use such a model to construct the predicted Dose-Volume-Histograms' confidence
intervals.|Hai Siong Tan et.al.|[2404.17126v1](http://arxiv.org/abs/2404.17126v1)|null|
|**2024-04-25**|**Attributing Responsibility in AI-Induced Incidents: A Computational Reflective Equilibrium Framework for Accountability**|The pervasive integration of Artificial Intelligence (AI) has introduced
complex challenges in the responsibility and accountability in the event of
incidents involving AI-enabled systems. The interconnectivity of these systems,
ethical concerns of AI-induced incidents, coupled with uncertainties in AI
technology and the absence of corresponding regulations, have made traditional
responsibility attribution challenging. To this end, this work proposes a
Computational Reflective Equilibrium (CRE) approach to establish a coherent and
ethically acceptable responsibility attribution framework for all stakeholders.
The computational approach provides a structured analysis that overcomes the
limitations of conceptual approaches in dealing with dynamic and multifaceted
scenarios, showcasing the framework's explainability, coherence, and adaptivity
properties in the responsibility attribution process. We examine the pivotal
role of the initial activation level associated with claims in equilibrium
computation. Using an AI-assisted medical decision-support system as a case
study, we illustrate how different initializations lead to diverse
responsibility distributions. The framework offers valuable insights into
accountability in AI-induced incidents, facilitating the development of a
sustainable and resilient system through continuous monitoring, revision, and
reflection.|Yunfei Ge et.al.|[2404.16957v1](http://arxiv.org/abs/2404.16957v1)|null|
|**2024-04-25**|**Taming False Positives in Out-of-Distribution Detection with Human Feedback**|Robustness to out-of-distribution (OOD) samples is crucial for safely
deploying machine learning models in the open world. Recent works have focused
on designing scoring functions to quantify OOD uncertainty. Setting appropriate
thresholds for these scoring functions for OOD detection is challenging as OOD
samples are often unavailable up front. Typically, thresholds are set to
achieve a desired true positive rate (TPR), e.g., $95\%$ TPR. However, this can
lead to very high false positive rates (FPR), ranging from 60 to 96\%, as
observed in the Open-OOD benchmark. In safety-critical real-life applications,
e.g., medical diagnosis, controlling the FPR is essential when dealing with
various OOD samples dynamically. To address these challenges, we propose a
mathematically grounded OOD detection framework that leverages expert feedback
to \emph{safely} update the threshold on the fly. We provide theoretical
results showing that it is guaranteed to meet the FPR constraint at all times
while minimizing the use of human feedback. Another key feature of our
framework is that it can work with any scoring function for OOD uncertainty
quantification. Empirical evaluation of our system on synthetic and benchmark
OOD datasets shows that our method can maintain FPR at most $5\%$ while
maximizing TPR.|Harit Vishwakarma et.al.|[2404.16954v1](http://arxiv.org/abs/2404.16954v1)|[link](https://github.com/2454511550lin/tamefalsepositives-ood)|
|**2024-04-25**|**Features Fusion for Dual-View Mammography Mass Detection**|Detection of malignant lesions on mammography images is extremely important
for early breast cancer diagnosis. In clinical practice, images are acquired
from two different angles, and radiologists can fully utilize information from
both views, simultaneously locating the same lesion. However, for automatic
detection approaches such information fusion remains a challenge. In this
paper, we propose a new model called MAMM-Net, which allows the processing of
both mammography views simultaneously by sharing information not only on an
object level, as seen in existing works, but also on a feature level.
MAMM-Net's key component is the Fusion Layer, based on deformable attention and
designed to increase detection precision while keeping high recall. Our
experiments show superior performance on the public DDSM dataset compared to
the previous state-of-the-art model, while introducing new helpful features
such as lesion annotation on pixel-level and classification of lesions
malignancy.|Arina Varlamova et.al.|[2404.16718v1](http://arxiv.org/abs/2404.16718v1)|null|
|**2024-04-25**|**Report on Candidate Computational Indicators for Conscious Valenced Experience**|This report enlists 13 functional conditions cashed out in computational
terms that have been argued to be constituent of conscious valenced experience.
These are extracted from existing empirical and theoretical literature on,
among others, animal sentience, medical disorders, anaesthetics, philosophy,
evolution, neuroscience, and artificial intelligence.|Andres Campero et.al.|[2404.16696v1](http://arxiv.org/abs/2404.16696v1)|null|
|**2024-04-25**|**ProbGate at EHRSQL 2024: Enhancing SQL Query Generation Accuracy through Probabilistic Threshold Filtering and Error Handling**|Recently, deep learning-based language models have significantly enhanced
text-to-SQL tasks, with promising applications in retrieving patient records
within the medical domain. One notable challenge in such applications is
discerning unanswerable queries. Through fine-tuning model, we demonstrate the
feasibility of converting medical record inquiries into SQL queries.
Additionally, we introduce an entropy-based method to identify and filter out
unanswerable results. We further enhance result quality by filtering
low-confidence SQL through log probability-based distribution, while
grammatical and schema errors are mitigated by executing queries on the actual
database. We experimentally verified that our method can filter unanswerable
questions, which can be widely utilized even when the parameters of the model
are not accessible, and that it can be effectively utilized in practice.|Sangryul Kim et.al.|[2404.16659v1](http://arxiv.org/abs/2404.16659v1)|[link](https://github.com/venzino-han/probgate_ehrsql)|
|**2024-04-25**|**Hippocrates: An Open-Source Framework for Advancing Large Language Models in Healthcare**|The integration of Large Language Models (LLMs) into healthcare promises to
transform medical diagnostics, research, and patient care. Yet, the progression
of medical LLMs faces obstacles such as complex training requirements, rigorous
evaluation demands, and the dominance of proprietary models that restrict
academic exploration. Transparent, comprehensive access to LLM resources is
essential for advancing the field, fostering reproducibility, and encouraging
innovation in healthcare AI. We present Hippocrates, an open-source LLM
framework specifically developed for the medical domain. In stark contrast to
previous efforts, it offers unrestricted access to its training datasets,
codebase, checkpoints, and evaluation protocols. This open approach is designed
to stimulate collaborative research, allowing the community to build upon,
refine, and rigorously evaluate medical LLMs within a transparent ecosystem.
Also, we introduce Hippo, a family of 7B models tailored for the medical
domain, fine-tuned from Mistral and LLaMA2 through continual pre-training,
instruction tuning, and reinforcement learning from human and AI feedback. Our
models outperform existing open medical LLMs models by a large-margin, even
surpassing models with 70B parameters. Through Hippocrates, we aspire to unlock
the full potential of LLMs not just to advance medical knowledge and patient
care but also to democratize the benefits of AI research in healthcare, making
them available across the globe.|Emre Can Acikgoz et.al.|[2404.16621v1](http://arxiv.org/abs/2404.16621v1)|null|
|**2024-04-25**|**DiffSeg: A Segmentation Model for Skin Lesions Based on Diffusion Difference**|Weakly supervised medical image segmentation (MIS) using generative models is
crucial for clinical diagnosis. However, the accuracy of the segmentation
results is often limited by insufficient supervision and the complex nature of
medical imaging. Existing models also only provide a single outcome, which does
not allow for the measurement of uncertainty. In this paper, we introduce
DiffSeg, a segmentation model for skin lesions based on diffusion difference
which exploits diffusion model principles to ex-tract noise-based features from
images with diverse semantic information. By discerning difference between
these noise features, the model identifies diseased areas. Moreover, its
multi-output capability mimics doctors' annotation behavior, facilitating the
visualization of segmentation result consistency and ambiguity. Additionally,
it quantifies output uncertainty using Generalized Energy Distance (GED),
aiding interpretability and decision-making for physicians. Finally, the model
integrates outputs through the Dense Conditional Random Field (DenseCRF)
algorithm to refine the segmentation boundaries by considering inter-pixel
correlations, which improves the accuracy and optimizes the segmentation
results. We demonstrate the effectiveness of DiffSeg on the ISIC 2018 Challenge
dataset, outperforming state-of-the-art U-Net-based methods.|Zhihao Shuai et.al.|[2404.16474v1](http://arxiv.org/abs/2404.16474v1)|null|
|**2024-04-25**|**Light-weight Retinal Layer Segmentation with Global Reasoning**|Automatic retinal layer segmentation with medical images, such as optical
coherence tomography (OCT) images, serves as an important tool for diagnosing
ophthalmic diseases. However, it is challenging to achieve accurate
segmentation due to low contrast and blood flow noises presented in the images.
In addition, the algorithm should be light-weight to be deployed for practical
clinical applications. Therefore, it is desired to design a light-weight
network with high performance for retinal layer segmentation. In this paper, we
propose LightReSeg for retinal layer segmentation which can be applied to OCT
images. Specifically, our approach follows an encoder-decoder structure, where
the encoder part employs multi-scale feature extraction and a Transformer block
for fully exploiting the semantic information of feature maps at all scales and
making the features have better global reasoning capabilities, while the
decoder part, we design a multi-scale asymmetric attention (MAA) module for
preserving the semantic information at each encoder scale. The experiments show
that our approach achieves a better segmentation performance compared to the
current state-of-the-art method TransUnet with 105.7M parameters on both our
collected dataset and two other public datasets, with only 3.3M parameters.|Xiang He et.al.|[2404.16346v1](http://arxiv.org/abs/2404.16346v1)|null|
|**2024-04-25**|**Semantic Segmentation Refiner for Ultrasound Applications with Zero-Shot Foundation Models**|Despite the remarkable success of deep learning in medical imaging analysis,
medical image segmentation remains challenging due to the scarcity of
high-quality labeled images for supervision. Further, the significant domain
gap between natural and medical images in general and ultrasound images in
particular hinders fine-tuning models trained on natural images to the task at
hand. In this work, we address the performance degradation of segmentation
models in low-data regimes and propose a prompt-less segmentation method
harnessing the ability of segmentation foundation models to segment abstract
shapes. We do that via our novel prompt point generation algorithm which uses
coarse semantic segmentation masks as input and a zero-shot prompt-able
foundation model as an optimization target. We demonstrate our method on a
segmentation findings task (pathologic anomalies) in ultrasound images. Our
method's advantages are brought to light in varying degrees of low-data regime
experiments on a small-scale musculoskeletal ultrasound images dataset,
yielding a larger performance gain as the training set size decreases.|Hedda Cohen Indelman et.al.|[2404.16325v1](http://arxiv.org/abs/2404.16325v1)|null|
|**2024-04-25**|**LLM-Based Section Identifiers Excel on Open Source but Stumble in Real World Applications**|Electronic health records (EHR) even though a boon for healthcare
practitioners, are growing convoluted and longer every day. Sifting around
these lengthy EHRs is taxing and becomes a cumbersome part of physician-patient
interaction. Several approaches have been proposed to help alleviate this
prevalent issue either via summarization or sectioning, however, only a few
approaches have truly been helpful in the past. With the rise of automated
methods, machine learning (ML) has shown promise in solving the task of
identifying relevant sections in EHR. However, most ML methods rely on labeled
data which is difficult to get in healthcare. Large language models (LLMs) on
the other hand, have performed impressive feats in natural language processing
(NLP), that too in a zero-shot manner, i.e. without any labeled data. To that
end, we propose using LLMs to identify relevant section headers. We find that
GPT-4 can effectively solve the task on both zero and few-shot settings as well
as segment dramatically better than state-of-the-art methods. Additionally, we
also annotate a much harder real world dataset and find that GPT-4 struggles to
perform well, alluding to further research and harder benchmarks.|Saranya Krishnamoorthy et.al.|[2404.16294v1](http://arxiv.org/abs/2404.16294v1)|[link](https://github.com/inqbator-evicore/llm_section_identifiers)|
|**2024-04-24**|**Investigating the prompt leakage effect and black-box defenses for multi-turn LLM interactions**|Prompt leakage in large language models (LLMs) poses a significant security
and privacy threat, particularly in retrieval-augmented generation (RAG)
systems. However, leakage in multi-turn LLM interactions along with mitigation
strategies has not been studied in a standardized manner. This paper
investigates LLM vulnerabilities against prompt leakage across 4 diverse
domains and 10 closed- and open-source LLMs. Our unique multi-turn threat model
leverages the LLM's sycophancy effect and our analysis dissects task
instruction and knowledge leakage in the LLM response. In a multi-turn setting,
our threat model elevates the average attack success rate (ASR) to 86.2%,
including a 99% leakage with GPT-4 and claude-1.3. We find that some black-box
LLMs like Gemini show variable susceptibility to leakage across domains - they
are more likely to leak contextual knowledge in the news domain compared to the
medical domain. Our experiments measure specific effects of 6 black-box defense
strategies, including a query-rewriter in the RAG scenario. Our proposed
multi-tier combination of defenses still has an ASR of 5.3% for black-box LLMs,
indicating room for enhancement and future direction for LLM security research.|Divyansh Agarwal et.al.|[2404.16251v2](http://arxiv.org/abs/2404.16251v2)|null|
|**2024-04-24**|**ABCD: Trust enhanced Attention based Convolutional Autoencoder for Risk Assessment**|Anomaly detection in industrial systems is crucial for preventing equipment
failures, ensuring risk identification, and maintaining overall system
efficiency. Traditional monitoring methods often rely on fixed thresholds and
empirical rules, which may not be sensitive enough to detect subtle changes in
system health and predict impending failures. To address this limitation, this
paper proposes, a novel Attention-based convolutional autoencoder (ABCD) for
risk detection and map the risk value derive to the maintenance planning. ABCD
learns the normal behavior of conductivity from historical data of a real-world
industrial cooling system and reconstructs the input data, identifying
anomalies that deviate from the expected patterns. The framework also employs
calibration techniques to ensure the reliability of its predictions. Evaluation
results demonstrate that with the attention mechanism in ABCD a 57.4% increase
in performance and a reduction of false alarms by 9.37% is seen compared to
without attention. The approach can effectively detect risks, the risk priority
rank mapped to maintenance, providing valuable insights for cooling system
designers and service personnel. Calibration error of 0.03% indicates that the
model is well-calibrated and enhances model's trustworthiness, enabling
informed decisions about maintenance strategies|Sarala Naidu et.al.|[2404.16183v1](http://arxiv.org/abs/2404.16183v1)|null|
|**2024-04-24**|**Mamba-360: Survey of State Space Models as Transformer Alternative for Long Sequence Modelling: Methods, Applications, and Challenges**|Sequence modeling is a crucial area across various domains, including Natural
Language Processing (NLP), speech recognition, time series forecasting, music
generation, and bioinformatics. Recurrent Neural Networks (RNNs) and Long Short
Term Memory Networks (LSTMs) have historically dominated sequence modeling
tasks like Machine Translation, Named Entity Recognition (NER), etc. However,
the advancement of transformers has led to a shift in this paradigm, given
their superior performance. Yet, transformers suffer from $O(N^2)$ attention
complexity and challenges in handling inductive bias. Several variations have
been proposed to address these issues which use spectral networks or
convolutions and have performed well on a range of tasks. However, they still
have difficulty in dealing with long sequences. State Space Models(SSMs) have
emerged as promising alternatives for sequence modeling paradigms in this
context, especially with the advent of S4 and its variants, such as S4nd,
Hippo, Hyena, Diagnol State Spaces (DSS), Gated State Spaces (GSS), Linear
Recurrent Unit (LRU), Liquid-S4, Mamba, etc. In this survey, we categorize the
foundational SSMs based on three paradigms namely, Gating architectures,
Structural architectures, and Recurrent architectures. This survey also
highlights diverse applications of SSMs across domains such as vision, video,
audio, speech, language (especially long sequence modeling), medical (including
genomics), chemical (like drug design), recommendation systems, and time series
analysis, including tabular data. Moreover, we consolidate the performance of
SSMs on benchmark datasets like Long Range Arena (LRA), WikiText, Glue, Pile,
ImageNet, Kinetics-400, sstv2, as well as video datasets such as Breakfast,
COIN, LVU, and various time series datasets. The project page for Mamba-360
work is available on this webpage.\url{https://github.com/badripatro/mamba360}.|Badri Narayana Patro et.al.|[2404.16112v1](http://arxiv.org/abs/2404.16112v1)|[link](https://github.com/badripatro/mamba360)|
|**2024-04-24**|**Mammo-CLIP: Leveraging Contrastive Language-Image Pre-training (CLIP) for Enhanced Breast Cancer Diagnosis with Multi-view Mammography**|Although fusion of information from multiple views of mammograms plays an
important role to increase accuracy of breast cancer detection, developing
multi-view mammograms-based computer-aided diagnosis (CAD) schemes still faces
challenges and no such CAD schemes have been used in clinical practice. To
overcome the challenges, we investigate a new approach based on Contrastive
Language-Image Pre-training (CLIP), which has sparked interest across various
medical imaging tasks. By solving the challenges in (1) effectively adapting
the single-view CLIP for multi-view feature fusion and (2) efficiently
fine-tuning this parameter-dense model with limited samples and computational
resources, we introduce Mammo-CLIP, the first multi-modal framework to process
multi-view mammograms and corresponding simple texts. Mammo-CLIP uses an early
feature fusion strategy to learn multi-view relationships in four mammograms
acquired from the CC and MLO views of the left and right breasts. To enhance
learning efficiency, plug-and-play adapters are added into CLIP image and text
encoders for fine-tuning parameters and limiting updates to about 1% of the
parameters. For framework evaluation, we assembled two datasets
retrospectively. The first dataset, comprising 470 malignant and 479 benign
cases, was used for few-shot fine-tuning and internal evaluation of the
proposed Mammo-CLIP via 5-fold cross-validation. The second dataset, including
60 malignant and 294 benign cases, was used to test generalizability of
Mammo-CLIP. Study results show that Mammo-CLIP outperforms the state-of-art
cross-view transformer in AUC (0.841 vs. 0.817, 0.837 vs. 0.807) on both
datasets. It also surpasses previous two CLIP-based methods by 20.3% and 14.3%.
This study highlights the potential of applying the finetuned vision-language
models for developing next-generation, image-text-based CAD schemes of breast
cancer.|Xuxin Chen et.al.|[2404.15946v1](http://arxiv.org/abs/2404.15946v1)|null|
|**2024-04-24**|**Assessing The Potential Of Mid-Sized Language Models For Clinical QA**|Large language models, such as GPT-4 and Med-PaLM, have shown impressive
performance on clinical tasks; however, they require access to compute, are
closed-source, and cannot be deployed on device. Mid-size models such as
BioGPT-large, BioMedLM, LLaMA 2, and Mistral 7B avoid these drawbacks, but
their capacity for clinical tasks has been understudied. To help assess their
potential for clinical use and help researchers decide which model they should
use, we compare their performance on two clinical question-answering (QA)
tasks: MedQA and consumer query answering. We find that Mistral 7B is the best
performing model, winning on all benchmarks and outperforming models trained
specifically for the biomedical domain. While Mistral 7B's MedQA score of 63.0%
approaches the original Med-PaLM, and it often can produce plausible responses
to consumer health queries, room for improvement still exists. This study
provides the first head-to-head assessment of open source mid-sized models on
clinical tasks.|Elliot Bolton et.al.|[2404.15894v1](http://arxiv.org/abs/2404.15894v1)|null|
|**2024-04-24**|**Enhancing Diagnosis through AI-driven Analysis of Reflectance Confocal Microscopy**|Reflectance Confocal Microscopy (RCM) is a non-invasive imaging technique
used in biomedical research and clinical dermatology. It provides virtual
high-resolution images of the skin and superficial tissues, reducing the need
for physical biopsies. RCM employs a laser light source to illuminate the
tissue, capturing the reflected light to generate detailed images of
microscopic structures at various depths. Recent studies explored AI and
machine learning, particularly CNNs, for analyzing RCM images. Our study
proposes a segmentation strategy based on textural features to identify
clinically significant regions, empowering dermatologists in effective image
interpretation and boosting diagnostic confidence. This approach promises to
advance dermatological diagnosis and treatment.|Hong-Jun Yoon et.al.|[2404.16080v1](http://arxiv.org/abs/2404.16080v1)|null|
|**2024-04-24**|**Anomaly Detection for Incident Response at Scale**|We present a machine learning-based anomaly detection product, AI Detect and
Respond (AIDR), that monitors Walmart's business and system health in
real-time. During the validation over 3 months, the product served predictions
from over 3000 models to more than 25 application, platform, and operation
teams, covering 63\% of major incidents and reducing the mean-time-to-detect
(MTTD) by more than 7 minutes. Unlike previous anomaly detection methods, our
solution leverages statistical, ML and deep learning models while continuing to
incorporate rule-based static thresholds to incorporate domain-specific
knowledge. Both univariate and multivariate ML models are deployed and
maintained through distributed services for scalability and high availability.
AIDR has a feedback loop that assesses model quality with a combination of
drift detection algorithms and customer feedback. It also offers
self-onboarding capabilities and customizability. AIDR has achieved success
with various internal teams with lower time to detection and fewer false
positives than previous methods. As we move forward, we aim to expand incident
coverage and prevention, reduce noise, and integrate further with root cause
recommendation (RCR) to enable an end-to-end AIDR experience.|Hanzhang Wang et.al.|[2404.16887v1](http://arxiv.org/abs/2404.16887v1)|null|
|**2024-04-23**|**Adapting an Artificial Intelligence Sexually Transmitted Diseases Symptom Checker Tool for Mpox Detection: The HeHealth Experience**|Artificial Intelligence applications have shown promise in the management of
pandemics and have been widely used to assist the identification,
classification, and diagnosis of medical images. In response to the global
outbreak of Monkeypox (Mpox), the HeHealth.ai team leveraged an existing tool
to screen for sexually transmitted diseases to develop a digital screening test
for symptomatic Mpox through AI approaches. Prior to the global outbreak of
Mpox, the team developed a smartphone app, where app users can use their own
smartphone cameras to take pictures of their own penises to screen for
symptomatic STD. The AI model was initially developed using 5000 cases and use
a modified convolutional neural network to output prediction scores across
visually diagnosable penis pathologies including Syphilis, Herpes Simplex
Virus, and Human Papilloma Virus. From June 2022 to October 2022, a total of
about 22,000 users downloaded the HeHealth app, and about 21,000 images have
been analyzed using HeHealth AI technology. We then engaged in formative
research, stakeholder engagement, rapid consolidation images, a validation
study, and implementation of the tool from July 2022. From July 2022 to October
2022, a total of 1000 Mpox related images had been used to train the Mpox
symptom checker tool. Our digital symptom checker tool showed accuracy of 87%
to rule in Mpox and 90% to rule out symptomatic Mpox. Several hurdles
identified included issues of data privacy and security for app users, initial
lack of data to train the AI tool, and the potential generalizability of input
data. We offer several suggestions to help others get started on similar
projects in emergency situations, including engaging a wide range of
stakeholders, having a multidisciplinary team, prioritizing pragmatism, as well
as the concept that big data in fact is made up of small data.|Rayner Kay Jin Tan et.al.|[2404.16885v1](http://arxiv.org/abs/2404.16885v1)|null|
|**2024-04-23**|**PRISM: Patient Records Interpretation for Semantic Clinical Trial Matching using Large Language Models**|Clinical trial matching is the task of identifying trials for which patients
may be potentially eligible. Typically, this task is labor-intensive and
requires detailed verification of patient electronic health records (EHRs)
against the stringent inclusion and exclusion criteria of clinical trials. This
process is manual, time-intensive, and challenging to scale up, resulting in
many patients missing out on potential therapeutic options. Recent advancements
in Large Language Models (LLMs) have made automating patient-trial matching
possible, as shown in multiple concurrent research studies. However, the
current approaches are confined to constrained, often synthetic datasets that
do not adequately mirror the complexities encountered in real-world medical
data. In this study, we present the first, end-to-end large-scale empirical
evaluation of clinical trial matching using real-world EHRs. Our study
showcases the capability of LLMs to accurately match patients with appropriate
clinical trials. We perform experiments with proprietary LLMs, including GPT-4
and GPT-3.5, as well as our custom fine-tuned model called OncoLLM and show
that OncoLLM, despite its significantly smaller size, not only outperforms
GPT-3.5 but also matches the performance of qualified medical doctors. All
experiments were carried out on real-world EHRs that include clinical notes and
available clinical trials from a single cancer center in the United States.|Shashi Kant Gupta et.al.|[2404.15549v1](http://arxiv.org/abs/2404.15549v1)|null|
|**2024-04-23**|**Multi-scale Intervention Planning based on Generative Design**|The scarcity of green spaces, in urban environments, consists a critical
challenge. There are multiple adverse effects, impacting the health and
well-being of the citizens. Small scale interventions, e.g. pocket parks, is a
viable solution, but comes with multiple constraints, involving the design and
implementation over a specific area. In this study, we harness the capabilities
of generative AI for multi-scale intervention planning, focusing on nature
based solutions. By leveraging image-to-image and image inpainting algorithms,
we propose a methodology to address the green space deficit in urban areas.
Focusing on two alleys in Thessaloniki, where greenery is lacking, we
demonstrate the efficacy of our approach in visualizing NBS interventions. Our
findings underscore the transformative potential of emerging technologies in
shaping the future of urban intervention planning processes.|Ioannis Kavouras et.al.|[2404.15492v1](http://arxiv.org/abs/2404.15492v1)|null|
|**2024-04-23**|**IryoNLP at MEDIQA-CORR 2024: Tackling the Medical Error Detection & Correction Task On the Shoulders of Medical Agents**|In natural language processing applied to the clinical domain, utilizing
large language models has emerged as a promising avenue for error detection and
correction on clinical notes, a knowledge-intensive task for which annotated
data is scarce. This paper presents MedReAct'N'MedReFlex, which leverages a
suite of four LLM-based medical agents. The MedReAct agent initiates the
process by observing, analyzing, and taking action, generating trajectories to
guide the search to target a potential error in the clinical notes.
Subsequently, the MedEval agent employs five evaluators to assess the targeted
error and the proposed correction. In cases where MedReAct's actions prove
insufficient, the MedReFlex agent intervenes, engaging in reflective analysis
and proposing alternative strategies. Finally, the MedFinalParser agent formats
the final output, preserving the original style while ensuring the integrity of
the error correction process. One core component of our method is our RAG
pipeline based on our ClinicalCorp corpora. Among other well-known sources
containing clinical guidelines and information, we preprocess and release the
open-source MedWiki dataset for clinical RAG application. Our results
demonstrate the central role of our RAG approach with ClinicalCorp leveraged
through the MedReAct'N'MedReFlex framework. It achieved the ninth rank on the
MEDIQA-CORR 2024 final leaderboard.|Jean-Philippe Corbeil et.al.|[2404.15488v1](http://arxiv.org/abs/2404.15488v1)|[link](https://github.com/microsoft/iryonlp-mediqa-corr-2024)|
|**2024-04-23**|**Machine Learning Techniques with Fairness for Prediction of Completion of Drug and Alcohol Rehabilitation**|The aim of this study is to look at predicting whether a person will complete
a drug and alcohol rehabilitation program and the number of times a person
attends. The study is based on demographic data obtained from Substance Abuse
and Mental Health Services Administration (SAMHSA) from both admissions and
discharge data from drug and alcohol rehabilitation centers in Oklahoma.
Demographic data is highly categorical which led to binary encoding being used
and various fairness measures being utilized to mitigate bias of nine
demographic variables. Kernel methods such as linear, polynomial, sigmoid, and
radial basis functions were compared using support vector machines at various
parameter ranges to find the optimal values. These were then compared to
methods such as decision trees, random forests, and neural networks. Synthetic
Minority Oversampling Technique Nominal (SMOTEN) for categorical data was used
to balance the data with imputation for missing data. The nine bias variables
were then intersectionalized to mitigate bias and the dual and triple
interactions were integrated to use the probabilities to look at worst case
ratio fairness mitigation. Disparate Impact, Statistical Parity difference,
Conditional Statistical Parity Ratio, Demographic Parity, Demographic Parity
Ratio, Equalized Odds, Equalized Odds Ratio, Equal Opportunity, and Equalized
Opportunity Ratio were all explored at both the binary and multiclass
scenarios.|Karen Roberts-Licklider et.al.|[2404.15418v1](http://arxiv.org/abs/2404.15418v1)|null|
|**2024-04-23**|**CT-GLIP: 3D Grounded Language-Image Pretraining with CT Scans and Radiology Reports for Full-Body Scenarios**|Medical Vision-Language Pretraining (Med-VLP) establishes a connection
between visual content from medical images and the relevant textual
descriptions. Existing Med-VLP methods primarily focus on 2D images depicting a
single body part, notably chest X-rays. In this paper, we extend the scope of
Med-VLP to encompass 3D images, specifically targeting full-body scenarios, by
using a multimodal dataset of CT images and reports. Compared with the 2D
counterpart, 3D VLP is required to effectively capture essential semantics from
significantly sparser representation in 3D imaging. In this paper, we introduce
CT-GLIP (Grounded Language-Image Pretraining with CT scans), a novel method
that constructs organ-level image-text pairs to enhance multimodal contrastive
learning, aligning grounded visual features with precise diagnostic text.
Additionally, we developed an abnormality dictionary to augment contrastive
learning with diverse contrastive pairs. Our method, trained on a multimodal CT
dataset comprising 44,011 organ-level vision-text pairs from 17,702 patients
across 104 organs, demonstrates it can identify organs and abnormalities in a
zero-shot manner using natural languages. The performance of CT-GLIP is
validated on a separate test set of 1,130 patients, focusing on the 16 most
frequent abnormalities across 7 organs. The experimental results show our
model's superior performance over the standard CLIP framework across zero-shot
and fine-tuning scenarios, using both CNN and ViT architectures.|Jingyang Lin et.al.|[2404.15272v2](http://arxiv.org/abs/2404.15272v2)|null|
|**2024-04-23**|**A review of deep learning-based information fusion techniques for multimodal medical image classification**|Multimodal medical imaging plays a pivotal role in clinical diagnosis and
research, as it combines information from various imaging modalities to provide
a more comprehensive understanding of the underlying pathology. Recently, deep
learning-based multimodal fusion techniques have emerged as powerful tools for
improving medical image classification. This review offers a thorough analysis
of the developments in deep learning-based multimodal fusion for medical
classification tasks. We explore the complementary relationships among
prevalent clinical modalities and outline three main fusion schemes for
multimodal classification networks: input fusion, intermediate fusion
(encompassing single-level fusion, hierarchical fusion, and attention-based
fusion), and output fusion. By evaluating the performance of these fusion
techniques, we provide insight into the suitability of different network
architectures for various multimodal fusion scenarios and application domains.
Furthermore, we delve into challenges related to network architecture
selection, handling incomplete multimodal data management, and the potential
limitations of multimodal fusion. Finally, we spotlight the promising future of
Transformer-based multimodal fusion techniques and give recommendations for
future research in this rapidly evolving field.|Yihao Li et.al.|[2404.15022v1](http://arxiv.org/abs/2404.15022v1)|null|
|**2024-04-23**|**Clustering of timed sequences -- Application to the analysis of care pathways**|Improving the future of healthcare starts by better understanding the current
actual practices in hospitals. This motivates the objective of discovering
typical care pathways from patient data. Revealing homogeneous groups of care
pathways can be achieved through clustering. The difficulty in clustering care
pathways, represented by sequences of timestamped events, lies in defining a
semantically appropriate metric and clustering algorithms.
  In this article, we adapt two methods developed for time series to time
sequences: the drop-DTW metric and the DBA approach for the construction of
averaged time sequences. These methods are then applied in clustering
algorithms to propose original and sound clustering algorithms for timed
sequences.
  This approach is experimented with and evaluated on synthetic and real use
cases.|Thomas Guyet et.al.|[2404.15379v1](http://arxiv.org/abs/2404.15379v1)|null|
|**2024-04-23**|**Grounded Knowledge-Enhanced Medical VLP for Chest X-Ray**|Medical vision-language pre-training has emerged as a promising approach for
learning domain-general representations of medical image and text. Current
algorithms that exploit the global and local alignment between medical image
and text could however be marred by the redundant information in medical data.
To address this issue, we propose a grounded knowledge-enhanced medical
vision-language pre-training (GK-MVLP) framework for chest X-ray. In this
framework, medical knowledge is grounded to the appropriate anatomical regions
by using a transformer-based grounded knowledge-enhanced module for
fine-grained alignment between anatomical region-level visual features and the
textural features of medical knowledge. The performance of GK-MVLP is
competitive with or exceeds the state of the art on downstream chest X-ray
disease classification, disease localization, report generation, and medical
visual question-answering tasks. Our results show the advantage of
incorporating grounding mechanism to remove biases and improve the alignment
between chest X-ray image and radiology report.|Qiao Deng et.al.|[2404.14750v1](http://arxiv.org/abs/2404.14750v1)|null|
|**2024-04-22**|**DAIC-WOZ: On the Validity of Using the Therapist's prompts in Automatic Depression Detection from Clinical Interviews**|Automatic depression detection from conversational data has gained
significant interest in recent years. The DAIC-WOZ dataset, interviews
conducted by a human-controlled virtual agent, has been widely used for this
task. Recent studies have reported enhanced performance when incorporating
interviewer's prompts into the model. In this work, we hypothesize that this
improvement might be mainly due to a bias present in these prompts, rather than
the proposed architectures and methods. Through ablation experiments and
qualitative analysis, we discover that models using interviewer's prompts learn
to focus on a specific region of the interviews, where questions about past
experiences with mental health issues are asked, and use them as discriminative
shortcuts to detect depressed participants. In contrast, models using
participant responses gather evidence from across the entire interview.
Finally, to highlight the magnitude of this bias, we achieve a 0.90 F1 score by
intentionally exploiting it, the highest result reported to date on this
dataset using only textual information. Our findings underline the need for
caution when incorporating interviewers' prompts into models, as they may
inadvertently learn to exploit targeted prompts, rather than learning to
characterize the language and behavior that are genuinely indicative of the
patient's mental health condition.|Sergio Burdisso et.al.|[2404.14463v1](http://arxiv.org/abs/2404.14463v1)|null|
|**2024-04-22**|**Adaptive Collaboration Strategy for LLMs in Medical Decision Making**|Foundation models have become invaluable in advancing the medical field.
Despite their promise, the strategic deployment of LLMs for effective utility
in complex medical tasks remains an open question. Our novel framework, Medical
Decision-making Agents (MDAgents) aims to address this gap by automatically
assigning the effective collaboration structure for LLMs. Assigned solo or
group collaboration structure is tailored to the complexity of the medical task
at hand, emulating real-world medical decision making processes. We evaluate
our framework and baseline methods with state-of-the-art LLMs across a suite of
challenging medical benchmarks: MedQA, MedMCQA, PubMedQA, DDXPlus, PMC-VQA,
Path-VQA, and MedVidQA, achieving the best performance in 5 out of 7 benchmarks
that require an understanding of multi-modal medical reasoning. Ablation
studies reveal that MDAgents excels in adapting the number of collaborating
agents to optimize efficiency and accuracy, showcasing its robustness in
diverse scenarios. We also explore the dynamics of group consensus, offering
insights into how collaborative agents could behave in complex clinical team
dynamics. Our code can be found at https://github.com/mitmedialab/MDAgents.|Yubin Kim et.al.|[2404.15155v1](http://arxiv.org/abs/2404.15155v1)|[link](https://github.com/mitmedialab/mdagents)|
|**2024-04-21**|**A Nasal Cytology Dataset for Object Detection and Deep Learning**|Nasal Cytology is a new and efficient clinical technique to diagnose rhinitis
and allergies that is not much widespread due to the time-consuming nature of
cell counting; that is why AI-aided counting could be a turning point for the
diffusion of this technique. In this article we present the first dataset of
rhino-cytological field images: the NCD (Nasal Cytology Dataset), aimed to
train and deploy Object Detection models to support physicians and biologists
during clinical practice. The real distribution of the cytotypes, populating
the nasal mucosa has been replicated, sampling images from slides of clinical
patients, and manually annotating each cell found on them. The correspondent
object detection task presents non'trivial issues associated with the strong
class imbalancement, involving the rarest cell types. This work contributes to
some of open challenges by presenting a novel machine learning-based approach
to aid the automated detection and classification of nasal mucosa cells: the
DETR and YOLO models shown good performance in detecting cells and classifying
them correctly, revealing great potential to accelerate the work of rhinology
experts.|Mauro Camporeale et.al.|[2404.13745v1](http://arxiv.org/abs/2404.13745v1)|null|
|**2024-04-21**|**Bt-GAN: Generating Fair Synthetic Healthdata via Bias-transforming Generative Adversarial Networks**|Synthetic data generation offers a promising solution to enhance the
usefulness of Electronic Healthcare Records (EHR) by generating realistic
de-identified data. However, the existing literature primarily focuses on the
quality of synthetic health data, neglecting the crucial aspect of fairness in
downstream predictions. Consequently, models trained on synthetic EHR have
faced criticism for producing biased outcomes in target tasks. These biases can
arise from either spurious correlations between features or the failure of
models to accurately represent sub-groups. To address these concerns, we
present Bias-transforming Generative Adversarial Networks (Bt-GAN), a GAN-based
synthetic data generator specifically designed for the healthcare domain. In
order to tackle spurious correlations (i), we propose an
information-constrained Data Generation Process that enables the generator to
learn a fair deterministic transformation based on a well-defined notion of
algorithmic fairness. To overcome the challenge of capturing exact sub-group
representations (ii), we incentivize the generator to preserve sub-group
densities through score-based weighted sampling. This approach compels the
generator to learn from underrepresented regions of the data manifold. We
conduct extensive experiments using the MIMIC-III database. Our results
demonstrate that Bt-GAN achieves SOTA accuracy while significantly improving
fairness and minimizing bias amplification. We also perform an in-depth
explainability analysis to provide additional evidence supporting the validity
of our study. In conclusion, our research introduces a novel and professional
approach to addressing the limitations of synthetic data generation in the
healthcare domain. By incorporating fairness considerations and leveraging
advanced techniques such as GANs, we pave the way for more reliable and
unbiased predictions in healthcare applications.|Resmi Ramachandranpillai et.al.|[2404.13634v3](http://arxiv.org/abs/2404.13634v3)|null|
|**2024-04-21**|**SmartMem: Layout Transformation Elimination and Adaptation for Efficient DNN Execution on Mobile**|This work is motivated by recent developments in Deep Neural Networks,
particularly the Transformer architectures underlying applications such as
ChatGPT, and the need for performing inference on mobile devices. Focusing on
emerging transformers (specifically the ones with computationally efficient
Swin-like architectures) and large models (e.g., Stable Diffusion and LLMs)
based on transformers, we observe that layout transformations between the
computational operators cause a significant slowdown in these applications.
This paper presents SmartMem, a comprehensive framework for eliminating most
layout transformations, with the idea that multiple operators can use the same
tensor layout through careful choice of layout and implementation of
operations. Our approach is based on classifying the operators into four
groups, and considering combinations of producer-consumer edges between the
operators. We develop a set of methods for searching such layouts. Another
component of our work is developing efficient memory layouts for 2.5
dimensional memory commonly seen in mobile devices. Our experimental results
show that SmartMem outperforms 5 state-of-the-art DNN execution frameworks on
mobile devices across 18 varied neural networks, including CNNs, Transformers
with both local and global attention, as well as LLMs. In particular, compared
to DNNFusion, SmartMem achieves an average speedup of 2.8$\times$, and
outperforms TVM and MNN with speedups of 6.9$\times$ and 7.9$\times$,
respectively, on average.|Wei Niu et.al.|[2404.13528v1](http://arxiv.org/abs/2404.13528v1)|null|
|**2024-04-21**|**Parameter Efficient Fine Tuning: A Comprehensive Analysis Across Applications**|The rise of deep learning has marked significant progress in fields such as
computer vision, natural language processing, and medical imaging, primarily
through the adaptation of pre-trained models for specific tasks. Traditional
fine-tuning methods, involving adjustments to all parameters, face challenges
due to high computational and memory demands. This has led to the development
of Parameter Efficient Fine-Tuning (PEFT) techniques, which selectively update
parameters to balance computational efficiency with performance. This review
examines PEFT approaches, offering a detailed comparison of various strategies
highlighting applications across different domains, including text generation,
medical imaging, protein modeling, and speech synthesis. By assessing the
effectiveness of PEFT methods in reducing computational load, speeding up
training, and lowering memory usage, this paper contributes to making deep
learning more accessible and adaptable, facilitating its wider application and
encouraging innovation in model optimization. Ultimately, the paper aims to
contribute towards insights into PEFT's evolving landscape, guiding researchers
and practitioners in overcoming the limitations of conventional fine-tuning
approaches.|Charith Chandra Sai Balne et.al.|[2404.13506v2](http://arxiv.org/abs/2404.13506v2)|null|
|**2024-04-20**|**SiNC+: Adaptive Camera-Based Vitals with Unsupervised Learning of Periodic Signals**|Subtle periodic signals, such as blood volume pulse and respiration, can be
extracted from RGB video, enabling noncontact health monitoring at low cost.
Advancements in remote pulse estimation -- or remote photoplethysmography
(rPPG) -- are currently driven by deep learning solutions. However, modern
approaches are trained and evaluated on benchmark datasets with ground truth
from contact-PPG sensors. We present the first non-contrastive unsupervised
learning framework for signal regression to mitigate the need for labelled
video data. With minimal assumptions of periodicity and finite bandwidth, our
approach discovers the blood volume pulse directly from unlabelled videos. We
find that encouraging sparse power spectra within normal physiological
bandlimits and variance over batches of power spectra is sufficient for
learning visual features of periodic signals. We perform the first experiments
utilizing unlabelled video data not specifically created for rPPG to train
robust pulse rate estimators. Given the limited inductive biases, we
successfully applied the same approach to camera-based respiration by changing
the bandlimits of the target signal. This shows that the approach is general
enough for unsupervised learning of bandlimited quasi-periodic signals from
different domains. Furthermore, we show that the framework is effective for
finetuning models on unlabelled video from a single subject, allowing for
personalized and adaptive signal regressors.|Jeremy Speth et.al.|[2404.13449v1](http://arxiv.org/abs/2404.13449v1)|null|
|**2024-04-20**|**MultiConfederated Learning: Inclusive Non-IID Data handling with Decentralized Federated Learning**|Federated Learning (FL) has emerged as a prominent privacy-preserving
technique for enabling use cases like confidential clinical machine learning.
FL operates by aggregating models trained by remote devices which owns the
data. Thus, FL enables the training of powerful global models using
crowd-sourced data from a large number of learners, without compromising their
privacy. However, the aggregating server is a single point of failure when
generating the global model. Moreover, the performance of the model suffers
when the data is not independent and identically distributed (non-IID data) on
all remote devices. This leads to vastly different models being aggregated,
which can reduce the performance by as much as 50% in certain scenarios.
  In this paper, we seek to address the aforementioned issues while retaining
the benefits of FL. We propose MultiConfederated Learning: a decentralized FL
framework which is designed to handle non-IID data. Unlike traditional FL,
MultiConfederated Learning will maintain multiple models in parallel (instead
of a single global model) to help with convergence when the data is non-IID.
With the help of transfer learning, learners can converge to fewer models. In
order to increase adaptability, learners are allowed to choose which updates to
aggregate from their peers.|Michael Duchesne et.al.|[2404.13421v1](http://arxiv.org/abs/2404.13421v1)|null|
|**2024-04-20**|**UnibucLLM: Harnessing LLMs for Automated Prediction of Item Difficulty and Response Time for Multiple-Choice Questions**|This work explores a novel data augmentation method based on Large Language
Models (LLMs) for predicting item difficulty and response time of retired USMLE
Multiple-Choice Questions (MCQs) in the BEA 2024 Shared Task. Our approach is
based on augmenting the dataset with answers from zero-shot LLMs (Falcon,
Meditron, Mistral) and employing transformer-based models based on six
alternative feature combinations. The results suggest that predicting the
difficulty of questions is more challenging. Notably, our top performing
methods consistently include the question text, and benefit from the
variability of LLM answers, highlighting the potential of LLMs for improving
automated assessment in medical licensing exams. We make our code available
https://github.com/ana-rogoz/BEA-2024.|Ana-Cristina Rogoz et.al.|[2404.13343v1](http://arxiv.org/abs/2404.13343v1)|[link](https://github.com/ana-rogoz/bea-2024)|
|**2024-04-20**|**Practical Battery Health Monitoring using Uncertainty-Aware Bayesian Neural Network**|Battery health monitoring and prediction are critically important in the era
of electric mobility with a huge impact on safety, sustainability, and economic
aspects. Existing research often focuses on prediction accuracy but tends to
neglect practical factors that may hinder the technology's deployment in
real-world applications. In this paper, we address these practical
considerations and develop models based on the Bayesian neural network for
predicting battery end-of-life. Our models use sensor data related to battery
health and apply distributions, rather than single-point, for each parameter of
the models. This allows the models to capture the inherent randomness and
uncertainty of battery health, which leads to not only accurate predictions but
also quantifiable uncertainty. We conducted an experimental study and
demonstrated the effectiveness of our proposed models, with a prediction error
rate averaging 13.9%, and as low as 2.9% for certain tested batteries.
Additionally, all predictions include quantifiable certainty, which improved by
66% from the initial to the mid-life stage of the battery. This research has
practical values for battery technologies and contributes to accelerating the
technology adoption in the industry.|Yunyi Zhao et.al.|[2404.14444v1](http://arxiv.org/abs/2404.14444v1)|null|
|**2024-04-19**|**Beyond Self-Consistency: Ensemble Reasoning Boosts Consistency and Accuracy of LLMs in Cancer Staging**|Advances in large language models (LLMs) have encouraged their adoption in
the healthcare domain where vital clinical information is often contained in
unstructured notes. Cancer staging status is available in clinical reports, but
it requires natural language processing to extract the status from the
unstructured text. With the advance in clinical-oriented LLMs, it is promising
to extract such status without extensive efforts in training the algorithms.
Prompting approaches of the pre-trained LLMs that elicit a model's reasoning
process, such as chain-of-thought, may help to improve the trustworthiness of
the generated responses. Using self-consistency further improves model
performance, but often results in inconsistent generations across the multiple
reasoning paths. In this study, we propose an ensemble reasoning approach with
the aim of improving the consistency of the model generations. Using an open
access clinical large language model to determine the pathologic cancer stage
from real-world pathology reports, we show that the ensemble reasoning approach
is able to improve both the consistency and performance of the LLM in
determining cancer stage, thereby demonstrating the potential to use these
models in clinical or other domains where reliability and trustworthiness are
critical.|Chia-Hsuan Chang et.al.|[2404.13149v1](http://arxiv.org/abs/2404.13149v1)|null|
|**2024-04-19**|**Explainable AI for Fair Sepsis Mortality Predictive Model**|Artificial intelligence supports healthcare professionals with predictive
modeling, greatly transforming clinical decision-making. This study addresses
the crucial need for fairness and explainability in AI applications within
healthcare to ensure equitable outcomes across diverse patient demographics. By
focusing on the predictive modeling of sepsis-related mortality, we propose a
method that learns a performance-optimized predictive model and then employs
the transfer learning process to produce a model with better fairness. Our
method also introduces a novel permutation-based feature importance algorithm
aiming at elucidating the contribution of each feature in enhancing fairness on
predictions. Unlike existing explainability methods concentrating on explaining
feature contribution to predictive performance, our proposed method uniquely
bridges the gap in understanding how each feature contributes to fairness. This
advancement is pivotal, given sepsis's significant mortality rate and its role
in one-third of hospital deaths. Our method not only aids in identifying and
mitigating biases within the predictive model but also fosters trust among
healthcare stakeholders by improving the transparency and fairness of model
predictions, thereby contributing to more equitable and trustworthy healthcare
delivery.|Chia-Hsuan Chang et.al.|[2404.13139v1](http://arxiv.org/abs/2404.13139v1)|null|
|**2024-04-19**|**Eye-tracking in Mixed Reality for Diagnosis of Neurodegenerative Diseases**|Parkinson's disease ranks as the second most prevalent neurodegenerative
disorder globally. This research aims to develop a system leveraging Mixed
Reality capabilities for tracking and assessing eye movements. In this paper,
we present a medical scenario and outline the development of an application
designed to capture eye-tracking signals through Mixed Reality technology for
the evaluation of neurodegenerative diseases. Additionally, we introduce a
pipeline for extracting clinically relevant features from eye-gaze analysis,
describing the capabilities of the proposed system from a medical perspective.
The study involved a cohort of healthy control individuals and patients
suffering from Parkinson's disease, showcasing the feasibility and potential of
the proposed technology for non-intrusive monitoring of eye movement patterns
for the diagnosis of neurodegenerative diseases.
  Clinical relevance - Developing a non-invasive biomarker for Parkinson's
disease is urgently needed to accurately detect the disease's onset. This would
allow for the timely introduction of neuroprotective treatment at the earliest
stage and enable the continuous monitoring of intervention outcomes. The
ability to detect subtle changes in eye movements allows for early diagnosis,
offering a critical window for intervention before more pronounced symptoms
emerge. Eye tracking provides objective and quantifiable biomarkers, ensuring
reliable assessments of disease progression and cognitive function. The eye
gaze analysis using Mixed Reality glasses is wireless, facilitating convenient
assessments in both home and hospital settings. The approach offers the
advantage of utilizing hardware that requires no additional specialized
attachments, enabling examinations through personal eyewear.|Mateusz Daniol et.al.|[2404.12984v1](http://arxiv.org/abs/2404.12984v1)|null|
|**2024-04-19**|**A Large-scale Medical Visual Task Adaptation Benchmark**|Visual task adaptation has been demonstrated to be effective in adapting
pre-trained Vision Transformers (ViTs) to general downstream visual tasks using
specialized learnable layers or tokens. However, there is yet a large-scale
benchmark to fully explore the effect of visual task adaptation on the
realistic and important medical domain, particularly across diverse medical
visual modalities, such as color images, X-ray, and CT. To close this gap, we
present Med-VTAB, a large-scale Medical Visual Task Adaptation Benchmark
consisting of 1.68 million medical images for diverse organs, modalities, and
adaptation approaches. Based on Med-VTAB, we explore the scaling law of medical
prompt tuning concerning tunable parameters and the generalizability of medical
visual adaptation using non-medical/medical pre-train weights. Besides, we
study the impact of patient ID out-of-distribution on medical visual
adaptation, which is a real and challenging scenario. Furthermore, results from
Med-VTAB indicate that a single pre-trained model falls short in medical task
adaptation. Therefore, we introduce GMoE-Adapter, a novel method that combines
medical and general pre-training weights through a gated mixture-of-experts
adapter, achieving state-of-the-art results in medical visual task adaptation.|Shentong Mo et.al.|[2404.12876v1](http://arxiv.org/abs/2404.12876v1)|null|
|**2024-04-19**|**Multi Class Depression Detection Through Tweets using Artificial Intelligence**|Depression is a significant issue nowadays. As per the World Health
Organization (WHO), in 2023, over 280 million individuals are grappling with
depression. This is a huge number; if not taken seriously, these numbers will
increase rapidly. About 4.89 billion individuals are social media users. People
express their feelings and emotions on platforms like Twitter, Facebook,
Reddit, Instagram, etc. These platforms contain valuable information which can
be used for research purposes. Considerable research has been conducted across
various social media platforms. However, certain limitations persist in these
endeavors. Particularly, previous studies were only focused on detecting
depression and the intensity of depression in tweets. Also, there existed
inaccuracies in dataset labeling. In this research work, five types of
depression (Bipolar, major, psychotic, atypical, and postpartum) were predicted
using tweets from the Twitter database based on lexicon labeling. Explainable
AI was used to provide reasoning by highlighting the parts of tweets that
represent type of depression. Bidirectional Encoder Representations from
Transformers (BERT) was used for feature extraction and training. Machine
learning and deep learning methodologies were used to train the model. The BERT
model presented the most promising results, achieving an overall accuracy of
0.96.|Muhammad Osama Nusrat et.al.|[2404.13104v1](http://arxiv.org/abs/2404.13104v1)|[link](https://github.com/mnusrat786/masters-thesis)|
|**2024-04-19**|**COIN: Counterfactual inpainting for weakly supervised semantic segmentation for medical images**|Deep learning is dramatically transforming the field of medical imaging and
radiology, enabling the identification of pathologies in medical images,
including computed tomography (CT) and X-ray scans. However, the performance of
deep learning models, particularly in segmentation tasks, is often limited by
the need for extensive annotated datasets. To address this challenge, the
capabilities of weakly supervised semantic segmentation are explored through
the lens of Explainable AI and the generation of counterfactual explanations.
The scope of this research is development of a novel counterfactual inpainting
approach (COIN) that flips the predicted classification label from abnormal to
normal by using a generative model. For instance, if the classifier deems an
input medical image X as abnormal, indicating the presence of a pathology, the
generative model aims to inpaint the abnormal region, thus reversing the
classifier's original prediction label. The approach enables us to produce
precise segmentations for pathologies without depending on pre-existing
segmentation masks. Crucially, image-level labels are utilized, which are
substantially easier to acquire than creating detailed segmentation masks. The
effectiveness of the method is demonstrated by segmenting synthetic targets and
actual kidney tumors from CT images acquired from Tartu University Hospital in
Estonia. The findings indicate that COIN greatly surpasses established
attribution methods, such as RISE, ScoreCAM, and LayerCAM, as well as an
alternative counterfactual explanation method introduced by Singla et al. This
evidence suggests that COIN is a promising approach for semantic segmentation
of tumors in CT images, and presents a step forward in making deep learning
applications more accessible and effective in healthcare, where annotated data
is scarce.|Dmytro Shvetsov et.al.|[2404.12832v1](http://arxiv.org/abs/2404.12832v1)|[link](https://github.com/dmytro-shvetsov/counterfactual-search)|
|**2024-04-19**|**DensePANet: An improved generative adversarial network for photoacoustic tomography image reconstruction from sparse data**|Image reconstruction is an essential step of every medical imaging method,
including Photoacoustic Tomography (PAT), which is a promising modality of
imaging, that unites the benefits of both ultrasound and optical imaging
methods. Reconstruction of PAT images using conventional methods results in
rough artifacts, especially when applied directly to sparse PAT data. In recent
years, generative adversarial networks (GANs) have shown a powerful performance
in image generation as well as translation, rendering them a smart choice to be
applied to reconstruction tasks. In this study, we proposed an end-to-end
method called DensePANet to solve the problem of PAT image reconstruction from
sparse data. The proposed model employs a novel modification of UNet in its
generator, called FD-UNet++, which considerably improves the reconstruction
performance. We evaluated the method on various in-vivo and simulated datasets.
Quantitative and qualitative results show the better performance of our model
over other prevalent deep learning techniques.|Hesam Hakimnejad et.al.|[2404.13101v1](http://arxiv.org/abs/2404.13101v1)|null|
|**2024-04-19**|**Transformer-Based Classification Outcome Prediction for Multimodal Stroke Treatment**|This study proposes a multi-modal fusion framework Multitrans based on the
Transformer architecture and self-attention mechanism. This architecture
combines the study of non-contrast computed tomography (NCCT) images and
discharge diagnosis reports of patients undergoing stroke treatment, using a
variety of methods based on Transformer architecture approach to predicting
functional outcomes of stroke treatment. The results show that the performance
of single-modal text classification is significantly better than single-modal
image classification, but the effect of multi-modal combination is better than
any single modality. Although the Transformer model only performs worse on
imaging data, when combined with clinical meta-diagnostic information, both can
learn better complementary information and make good contributions to
accurately predicting stroke treatment effects..|Danqing Ma et.al.|[2404.12634v1](http://arxiv.org/abs/2404.12634v1)|null|
|**2024-04-19**|**GluMarker: A Novel Predictive Modeling of Glycemic Control Through Digital Biomarkers**|The escalating prevalence of diabetes globally underscores the need for
diabetes management. Recent research highlights the growing focus on digital
biomarkers in diabetes management, with innovations in computational frameworks
and noninvasive monitoring techniques using personalized glucose metrics.
However, they predominantly focus on insulin dosing and specific glucose
values, or with limited attention given to overall glycemic control. This
leaves a gap in expanding the scope of digital biomarkers for overall glycemic
control in diabetes management. To address such a research gap, we propose
GluMarker -- an end-to-end framework for modeling digital biomarkers using
broader factors sources to predict glycemic control. Through the assessment and
refinement of various machine learning baselines, GluMarker achieves
state-of-the-art on Anderson's dataset in predicting next-day glycemic control.
Moreover, our research identifies key digital biomarkers for the next day's
glycemic control prediction. These identified biomarkers are instrumental in
illuminating the daily factors that influence glycemic management, offering
vital insights for diabetes care.|Ziyi Zhou et.al.|[2404.12605v1](http://arxiv.org/abs/2404.12605v1)|null|
|**2024-04-18**|**DF-DM: A foundational process model for multimodal data fusion in the artificial intelligence era**|In the big data era, integrating diverse data modalities poses significant
challenges, particularly in complex fields like healthcare. This paper
introduces a new process model for multimodal Data Fusion for Data Mining,
integrating embeddings and the Cross-Industry Standard Process for Data Mining
with the existing Data Fusion Information Group model. Our model aims to
decrease computational costs, complexity, and bias while improving efficiency
and reliability. We also propose "disentangled dense fusion", a novel embedding
fusion method designed to optimize mutual information and facilitate dense
inter-modality feature interaction, thereby minimizing redundant information.
  We demonstrate the model's efficacy through three use cases: predicting
diabetic retinopathy using retinal images and patient metadata, domestic
violence prediction employing satellite imagery, internet, and census data, and
identifying clinical and demographic features from radiography images and
clinical notes. The model achieved a Macro F1 score of 0.92 in diabetic
retinopathy prediction, an R-squared of 0.854 and sMAPE of 24.868 in domestic
violence prediction, and a macro AUC of 0.92 and 0.99 for disease prediction
and sex classification, respectively, in radiological analysis.
  These results underscore the Data Fusion for Data Mining model's potential to
significantly impact multimodal data processing, promoting its adoption in
diverse, resource-constrained settings.|David Restrepo et.al.|[2404.12278v1](http://arxiv.org/abs/2404.12278v1)|null|
|**2024-04-18**|**Relationship Discovery for Drug Recommendation**|Medication recommendation systems are designed to deliver personalized drug
suggestions that are closely aligned with individual patient needs. Previous
studies have primarily concentrated on developing medication embeddings,
achieving significant progress. Nonetheless, these approaches often fall short
in accurately reflecting individual patient profiles, mainly due to challenges
in distinguishing between various patient conditions and the inability to
establish precise correlations between specific conditions and appropriate
medications. In response to these issues, we introduce DisMed, a model that
focuses on patient conditions to enhance personalization. DisMed employs causal
inference to discern clear, quantifiable causal links. It then examines patient
conditions in depth, recognizing and adapting to the evolving nuances of these
conditions, and mapping them directly to corresponding medications.
Additionally, DisMed leverages data from multiple patient visits to propose
combinations of medications. Comprehensive testing on real-world datasets
demonstrates that DisMed not only improves the customization of patient
profiles but also surpasses leading models in both precision and safety.|Xiang Li et.al.|[2404.12228v1](http://arxiv.org/abs/2404.12228v1)|null|
|**2024-04-18**|**A Symmetric Regressor for MRI-Based Assessment of Striatal Dopamine Transporter Uptake in Parkinson's Disease**|Dopamine transporter (DAT) imaging is commonly used for monitoring
Parkinson's disease (PD), where striatal DAT uptake amount is computed to
assess PD severity. However, DAT imaging has a high cost and the risk of
radiance exposure and is not available in general clinics. Recently, MRI patch
of the nigral region has been proposed as a safer and easier alternative. This
paper proposes a symmetric regressor for predicting the DAT uptake amount from
the nigral MRI patch. Acknowledging the symmetry between the right and left
nigrae, the proposed regressor incorporates a paired input-output model that
simultaneously predicts the DAT uptake amounts for both the right and left
striata. Moreover, it employs a symmetric loss that imposes a constraint on the
difference between right-to-left predictions, resembling the high correlation
in DAT uptake amounts in the two lateral sides. Additionally, we propose a
symmetric Monte-Carlo (MC) dropout method for providing a fruitful uncertainty
estimate of the DAT uptake prediction, which utilizes the above symmetry. We
evaluated the proposed approach on 734 nigral patches, which demonstrated
significantly improved performance of the symmetric regressor compared with the
standard regressors while giving better explainability and feature
representation. The symmetric MC dropout also gave precise uncertainty ranges
with a high probability of including the true DAT uptake amounts within the
range.|Walid Abdullah Al et.al.|[2404.11929v1](http://arxiv.org/abs/2404.11929v1)|[link](https://github.com/awjibon/mri_dat)|
|**2024-04-18**|**Cross-model Mutual Learning for Exemplar-based Medical Image Segmentation**|Medical image segmentation typically demands extensive dense annotations for
model training, which is both time-consuming and skill-intensive. To mitigate
this burden, exemplar-based medical image segmentation methods have been
introduced to achieve effective training with only one annotated image. In this
paper, we introduce a novel Cross-model Mutual learning framework for
Exemplar-based Medical image Segmentation (CMEMS), which leverages two models
to mutually excavate implicit information from unlabeled data at multiple
granularities. CMEMS can eliminate confirmation bias and enable collaborative
training to learn complementary information by enforcing consistency at
different granularities across models. Concretely, cross-model image
perturbation based mutual learning is devised by using weakly perturbed images
to generate high-confidence pseudo-labels, supervising predictions of strongly
perturbed images across models. This approach enables joint pursuit of
prediction consistency at the image granularity. Moreover, cross-model
multi-level feature perturbation based mutual learning is designed by letting
pseudo-labels supervise predictions from perturbed multi-level features with
different resolutions, which can broaden the perturbation space and enhance the
robustness of our framework. CMEMS is jointly trained using exemplar data,
synthetic data, and unlabeled data in an end-to-end manner. Experimental
results on two medical image datasets indicate that the proposed CMEMS
outperforms the state-of-the-art segmentation methods with extremely limited
supervision.|Qing En et.al.|[2404.11812v1](http://arxiv.org/abs/2404.11812v1)|null|
|**2024-04-17**|**A Secure and Trustworthy Network Architecture for Federated Learning Healthcare Applications**|Federated Learning (FL) has emerged as a promising approach for
privacy-preserving machine learning, particularly in sensitive domains such as
healthcare. In this context, the TRUSTroke project aims to leverage FL to
assist clinicians in ischemic stroke prediction. This paper provides an
overview of the TRUSTroke FL network infrastructure. The proposed architecture
adopts a client-server model with a central Parameter Server (PS). We introduce
a Docker-based design for the client nodes, offering a flexible solution for
implementing FL processes in clinical settings. The impact of different
communication protocols (HTTP or MQTT) on FL network operation is analyzed,
with MQTT selected for its suitability in FL scenarios. A control plane to
support the main operations required by FL processes is also proposed. The
paper concludes with an analysis of security aspects of the FL architecture,
addressing potential threats and proposing mitigation strategies to increase
the trustworthiness level.|Antonio Boiano et.al.|[2404.11698v1](http://arxiv.org/abs/2404.11698v1)|null|
|**2024-04-17**|**Towards Reliable Empirical Machine Unlearning Evaluation: A Game-Theoretic View**|Machine unlearning is the process of updating machine learning models to
remove the information of specific training data samples, in order to comply
with data protection regulations that allow individuals to request the removal
of their personal data. Despite the recent development of numerous unlearning
algorithms, reliable evaluation of these algorithms remains an open research
question. In this work, we focus on membership inference attack (MIA) based
evaluation, one of the most common approaches for evaluating unlearning
algorithms, and address various pitfalls of existing evaluation metrics that
lack reliability. Specifically, we propose a game-theoretic framework that
formalizes the evaluation process as a game between unlearning algorithms and
MIA adversaries, measuring the data removal efficacy of unlearning algorithms
by the capability of the MIA adversaries. Through careful design of the game,
we demonstrate that the natural evaluation metric induced from the game enjoys
provable guarantees that the existing evaluation metrics fail to satisfy.
Furthermore, we propose a practical and efficient algorithm to estimate the
evaluation metric induced from the game, and demonstrate its effectiveness
through both theoretical analysis and empirical experiments. This work presents
a novel and reliable approach to empirically evaluating unlearning algorithms,
paving the way for the development of more effective unlearning techniques.|Yiwen Tu et.al.|[2404.11577v1](http://arxiv.org/abs/2404.11577v1)|null|
|**2024-04-17**|**Prompt-Guided Generation of Structured Chest X-Ray Report Using a Pre-trained LLM**|Medical report generation automates radiology descriptions from images,
easing the burden on physicians and minimizing errors. However, current methods
lack structured outputs and physician interactivity for clear, clinically
relevant reports. Our method introduces a prompt-guided approach to generate
structured chest X-ray reports using a pre-trained large language model (LLM).
First, we identify anatomical regions in chest X-rays to generate focused
sentences that center on key visual elements, thereby establishing a structured
report foundation with anatomy-based sentences. We also convert the detected
anatomy into textual prompts conveying anatomical comprehension to the LLM.
Additionally, the clinical context prompts guide the LLM to emphasize
interactivity and clinical requirements. By integrating anatomy-focused
sentences and anatomy/clinical prompts, the pre-trained LLM can generate
structured chest X-ray reports tailored to prompted anatomical regions and
clinical contexts. We evaluate using language generation and clinical
effectiveness metrics, demonstrating strong performance.|Hongzhao Li et.al.|[2404.11209v1](http://arxiv.org/abs/2404.11209v1)|null|
|**2024-04-17**|**Explainable Machine Learning System for Predicting Chronic Kidney Disease in High-Risk Cardiovascular Patients**|As the global population ages, the incidence of Chronic Kidney Disease (CKD)
is rising. CKD often remains asymptomatic until advanced stages, which
significantly burdens both the healthcare system and patient quality of life.
This research developed an explainable machine learning system for predicting
CKD in patients with cardiovascular risks, utilizing medical history and
laboratory data. The Random Forest model achieved the highest sensitivity of
88.2%. The study introduces a comprehensive explainability framework that
extends beyond traditional feature importance methods, incorporating global and
local interpretations, bias inspection, biomedical relevance, and safety
assessments. Key predictive features identified in global interpretation were
the use of diabetic and ACEI/ARB medications, and initial eGFR values. Local
interpretation provided model insights through counterfactual explanations,
which aligned with other system parts. After conducting a bias inspection, it
was found that the initial eGFR values and CKD predictions exhibited some bias,
but no significant gender bias was identified. The model's logic, extracted by
scoped rules, was confirmed to align with existing medical literature. The
safety assessment tested potentially dangerous cases and confirmed that the
model behaved safely. This system enhances the explainability, reliability, and
accountability of the model, promoting its potential integration into
healthcare settings and compliance with upcoming regulatory standards, and
showing promise for broader applications in healthcare machine learning.|Nantika Nguycharoen et.al.|[2404.11148v1](http://arxiv.org/abs/2404.11148v1)|null|
|**2024-04-17**|**AKGNet: Attribute Knowledge-Guided Unsupervised Lung-Infected Area Segmentation**|Lung-infected area segmentation is crucial for assessing the severity of lung
diseases. However, existing image-text multi-modal methods typically rely on
labour-intensive annotations for model training, posing challenges regarding
time and expertise. To address this issue, we propose a novel attribute
knowledge-guided framework for unsupervised lung-infected area segmentation
(AKGNet), which achieves segmentation solely based on image-text data without
any mask annotation. AKGNet facilitates text attribute knowledge learning,
attribute-image cross-attention fusion, and high-confidence-based pseudo-label
exploration simultaneously. It can learn statistical information and capture
spatial correlations between image and text attributes in the embedding space,
iteratively refining the mask to enhance segmentation. Specifically, we
introduce a text attribute knowledge learning module by extracting attribute
knowledge and incorporating it into feature representations, enabling the model
to learn statistical information and adapt to different attributes. Moreover,
we devise an attribute-image cross-attention module by calculating the
correlation between attributes and images in the embedding space to capture
spatial dependency information, thus selectively focusing on relevant regions
while filtering irrelevant areas. Finally, a self-training mask improvement
process is employed by generating pseudo-labels using high-confidence
predictions to iteratively enhance the mask and segmentation. Experimental
results on a benchmark medical image dataset demonstrate the superior
performance of our method compared to state-of-the-art segmentation techniques
in unsupervised scenarios.|Qing En et.al.|[2404.11008v1](http://arxiv.org/abs/2404.11008v1)|null|
|**2024-04-17**|**Leveraging 3D LiDAR Sensors to Enable Enhanced Urban Safety and Public Health: Pedestrian Monitoring and Abnormal Activity Detection**|The integration of Light Detection and Ranging (LiDAR) and Internet of Things
(IoT) technologies offers transformative opportunities for public health
informatics in urban safety and pedestrian well-being. This paper proposes a
novel framework utilizing these technologies for enhanced 3D object detection
and activity classification in urban traffic scenarios. By employing elevated
LiDAR, we obtain detailed 3D point cloud data, enabling precise pedestrian
activity monitoring. To overcome urban data scarcity, we create a specialized
dataset through simulated traffic environments in Blender, facilitating
targeted model training. Our approach employs a modified Point
Voxel-Region-based Convolutional Neural Network (PV-RCNN) for robust 3D
detection and PointNet for classifying pedestrian activities, significantly
benefiting urban traffic management and public health by offering insights into
pedestrian behavior and promoting safer urban environments. Our dual-model
approach not only enhances urban traffic management but also contributes
significantly to public health by providing insights into pedestrian behavior
and promoting safer urban environment.|Nawfal Guefrachi et.al.|[2404.10978v1](http://arxiv.org/abs/2404.10978v1)|null|
|**2024-04-16**|**CrossGP: Cross-Day Glucose Prediction Excluding Physiological Information**|The increasing number of diabetic patients is a serious issue in society
today, which has significant negative impacts on people's health and the
country's financial expenditures. Because diabetes may develop into potential
serious complications, early glucose prediction for diabetic patients is
necessary for timely medical treatment. Existing glucose prediction methods
typically utilize patients' private data (e.g. age, gender, ethnicity) and
physiological parameters (e.g. blood pressure, heart rate) as reference
features for glucose prediction, which inevitably leads to privacy protection
concerns. Moreover, these models generally focus on either long-term
(monthly-based) or short-term (minute-based) predictions. Long-term prediction
methods are generally inaccurate because of the external uncertainties that can
greatly affect the glucose values, while short-term ones fail to provide timely
medical guidance. Based on the above issues, we propose CrossGP, a novel
machine-learning framework for cross-day glucose prediction solely based on the
patient's external activities without involving any physiological parameters.
Meanwhile, we implement three baseline models for comparison. Extensive
experiments on Anderson's dataset strongly demonstrate the superior performance
of CrossGP and prove its potential for future real-life applications.|Ziyi Zhou et.al.|[2404.10901v1](http://arxiv.org/abs/2404.10901v1)|null|
|**2024-04-16**|**Mixed Prototype Consistency Learning for Semi-supervised Medical Image Segmentation**|Recently, prototype learning has emerged in semi-supervised medical image
segmentation and achieved remarkable performance. However, the scarcity of
labeled data limits the expressiveness of prototypes in previous methods,
potentially hindering the complete representation of prototypes for class
embedding. To address this problem, we propose the Mixed Prototype Consistency
Learning (MPCL) framework, which includes a Mean Teacher and an auxiliary
network. The Mean Teacher generates prototypes for labeled and unlabeled data,
while the auxiliary network produces additional prototypes for mixed data
processed by CutMix. Through prototype fusion, mixed prototypes provide extra
semantic information to both labeled and unlabeled prototypes. High-quality
global prototypes for each class are formed by fusing two enhanced prototypes,
optimizing the distribution of hidden embeddings used in consistency learning.
Extensive experiments on the left atrium and type B aortic dissection datasets
demonstrate MPCL's superiority over previous state-of-the-art approaches,
confirming the effectiveness of our framework. The code will be released soon.|Lijian Li et.al.|[2404.10717v1](http://arxiv.org/abs/2404.10717v1)|null|
|**2024-04-16**|**AAVDiff: Experimental Validation of Enhanced Viability and Diversity in Recombinant Adeno-Associated Virus (AAV) Capsids through Diffusion Generation**|Recombinant adeno-associated virus (rAAV) vectors have revolutionized gene
therapy, but their broad tropism and suboptimal transduction efficiency limit
their clinical applications. To overcome these limitations, researchers have
focused on designing and screening capsid libraries to identify improved
vectors. However, the large sequence space and limited resources present
challenges in identifying viable capsid variants. In this study, we propose an
end-to-end diffusion model to generate capsid sequences with enhanced
viability. Using publicly available AAV2 data, we generated 38,000 diverse AAV2
viral protein (VP) sequences, and evaluated 8,000 for viral selection. The
results attested the superiority of our model compared to traditional methods.
Additionally, in the absence of AAV9 capsid data, apart from one wild-type
sequence, we used the same model to directly generate a number of viable
sequences with up to 9 mutations. we transferred the remaining 30,000 samples
to the AAV9 domain. Furthermore, we conducted mutagenesis on AAV9 VP
hypervariable regions VI and V, contributing to the continuous improvement of
the AAV9 VP sequence. This research represents a significant advancement in the
design and functional validation of rAAV vectors, offering innovative solutions
to enhance specificity and transduction efficiency in gene therapy
applications.|Lijun Liu et.al.|[2404.10573v2](http://arxiv.org/abs/2404.10573v2)|null|
|**2024-04-16**|**A Sentiment Analysis of Medical Text Based on Deep Learning**|The field of natural language processing (NLP) has made significant progress
with the rapid development of deep learning technologies. One of the research
directions in text sentiment analysis is sentiment analysis of medical texts,
which holds great potential for application in clinical diagnosis. However, the
medical field currently lacks sufficient text datasets, and the effectiveness
of sentiment analysis is greatly impacted by different model design approaches,
which presents challenges. Therefore, this paper focuses on the medical domain,
using bidirectional encoder representations from transformers (BERT) as the
basic pre-trained model and experimenting with modules such as convolutional
neural network (CNN), fully connected network (FCN), and graph convolutional
networks (GCN) at the output layer. Experiments and analyses were conducted on
the METS-CoV dataset to explore the training performance after integrating
different deep learning networks. The results indicate that CNN models
outperform other networks when trained on smaller medical text datasets in
combination with pre-trained models like BERT. This study highlights the
significance of model selection in achieving effective sentiment analysis in
the medical domain and provides a reference for future research to develop more
efficient model architectures.|Yinan Chen et.al.|[2404.10503v1](http://arxiv.org/abs/2404.10503v1)|null|
|**2024-04-16**|**Integration of Self-Supervised BYOL in Semi-Supervised Medical Image Recognition**|Image recognition techniques heavily rely on abundant labeled data,
particularly in medical contexts. Addressing the challenges associated with
obtaining labeled data has led to the prominence of self-supervised learning
and semi-supervised learning, especially in scenarios with limited annotated
data. In this paper, we proposed an innovative approach by integrating
self-supervised learning into semi-supervised models to enhance medical image
recognition. Our methodology commences with pre-training on unlabeled data
utilizing the BYOL method. Subsequently, we merge pseudo-labeled and labeled
datasets to construct a neural network classifier, refining it through
iterative fine-tuning. Experimental results on three different datasets
demonstrate that our approach optimally leverages unlabeled data, outperforming
existing methods in terms of accuracy for medical image recognition.|Hao Feng et.al.|[2404.10405v1](http://arxiv.org/abs/2404.10405v1)|null|
|**2024-04-16**|**Generating Counterfactual Trajectories with Latent Diffusion Models for Concept Discovery**|Trustworthiness is a major prerequisite for the safe application of opaque
deep learning models in high-stakes domains like medicine. Understanding the
decision-making process not only contributes to fostering trust but might also
reveal previously unknown decision criteria of complex models that could
advance the state of medical research. The discovery of decision-relevant
concepts from black box models is a particularly challenging task. This study
proposes Concept Discovery through Latent Diffusion-based Counterfactual
Trajectories (CDCT), a novel three-step framework for concept discovery
leveraging the superior image synthesis capabilities of diffusion models. In
the first step, CDCT uses a Latent Diffusion Model (LDM) to generate a
counterfactual trajectory dataset. This dataset is used to derive a
disentangled representation of classification-relevant concepts using a
Variational Autoencoder (VAE). Finally, a search algorithm is applied to
identify relevant concepts in the disentangled latent space. The application of
CDCT to a classifier trained on the largest public skin lesion dataset revealed
not only the presence of several biases but also meaningful biomarkers.
Moreover, the counterfactuals generated within CDCT show better FID scores than
those produced by a previously established state-of-the-art method, while being
12 times more resource-efficient. Unsupervised concept discovery holds great
potential for the application of trustworthy AI and the further development of
human knowledge in various domains. CDCT represents a further step in this
direction.|Payal Varshney et.al.|[2404.10356v1](http://arxiv.org/abs/2404.10356v1)|null|
|**2024-04-16**|**CARE to Compare: A real-world dataset for anomaly detection in wind turbine data**|Anomaly detection plays a crucial role in the field of predictive maintenance
for wind turbines, yet the comparison of different algorithms poses a difficult
task because domain specific public datasets are scarce. Many comparisons of
different approaches either use benchmarks composed of data from many different
domains, inaccessible data or one of the few publicly available datasets which
lack detailed information about the faults. Moreover, many publications
highlight a couple of case studies where fault detection was successful. With
this paper we publish a high quality dataset that contains data from 36 wind
turbines across 3 different wind farms as well as the most detailed fault
information of any public wind turbine dataset as far as we know. The new
dataset contains 89 years worth of real-world operating data of wind turbines,
distributed across 44 labeled time frames for anomalies that led up to faults,
as well as 51 time series representing normal behavior. Additionally, the
quality of training data is ensured by turbine-status-based labels for each
data point. Furthermore, we propose a new scoring method, called CARE
(Coverage, Accuracy, Reliability and Earliness), which takes advantage of the
information depth that is present in the dataset to identify a good all-around
anomaly detection model. This score considers the anomaly detection
performance, the ability to recognize normal behavior properly and the
capability to raise as few false alarms as possible while simultaneously
detecting anomalies early.|Christian Gück et.al.|[2404.10320v2](http://arxiv.org/abs/2404.10320v2)|null|
|**2024-04-16**|**Clustering and Data Augmentation to Improve Accuracy of Sleep Assessment and Sleep Individuality Analysis**|Recently, growing health awareness, novel methods allow individuals to
monitor sleep at home. Utilizing sleep sounds offers advantages over
conventional methods like smartwatches, being non-intrusive, and capable of
detecting various physiological activities. This study aims to construct a
machine learning-based sleep assessment model providing evidence-based
assessments, such as poor sleep due to frequent movement during sleep onset.
Extracting sleep sound events, deriving latent representations using VAE,
clustering with GMM, and training LSTM for subjective sleep assessment achieved
a high accuracy of 94.8% in distinguishing sleep satisfaction. Moreover,
TimeSHAP revealed differences in impactful sound event types and timings for
different individuals.|Shintaro Tamai et.al.|[2404.10299v1](http://arxiv.org/abs/2404.10299v1)|null|
|**2024-04-15**|**Emergent Language Symbolic Autoencoder (ELSA) with Weak Supervision to Model Hierarchical Brain Networks**|Brain networks display a hierarchical organization, a complexity that poses a
challenge for existing deep learning models, often structured as flat
classifiers, leading to difficulties in interpretability and the 'black box'
issue. To bridge this gap, we propose a novel architecture: a symbolic
autoencoder informed by weak supervision and an Emergent Language (EL)
framework. This model moves beyond traditional flat classifiers by producing
hierarchical clusters and corresponding imagery, subsequently represented
through symbolic sentences to improve the clinical interpretability of
hierarchically organized data such as intrinsic brain networks, which can be
characterized using resting-state fMRI images. Our innovation includes a
generalized hierarchical loss function designed to ensure that both sentences
and images accurately reflect the hierarchical structure of functional brain
networks. This enables us to model functional brain networks from a broader
perspective down to more granular details. Furthermore, we introduce a
quantitative method to assess the hierarchical consistency of these symbolic
representations. Our qualitative analyses show that our model successfully
generates hierarchically organized, clinically interpretable images, a finding
supported by our quantitative evaluations. We find that our best performing
loss function leads to a hierarchical consistency of over 97% when identifying
images corresponding to brain networks. This approach not only advances the
interpretability of deep learning models in neuroimaging analysis but also
represents a significant step towards modeling the intricate hierarchical
nature of brain networks.|Ammar Ahmed Pallikonda Latheef et.al.|[2404.10031v1](http://arxiv.org/abs/2404.10031v1)|null|
|**2024-04-15**|**Harnessing GPT-4V(ision) for Insurance: A Preliminary Exploration**|The emergence of Large Multimodal Models (LMMs) marks a significant milestone
in the development of artificial intelligence. Insurance, as a vast and complex
discipline, involves a wide variety of data forms in its operational processes,
including text, images, and videos, thereby giving rise to diverse multimodal
tasks. Despite this, there has been limited systematic exploration of
multimodal tasks specific to insurance, nor a thorough investigation into how
LMMs can address these challenges. In this paper, we explore GPT-4V's
capabilities in the insurance domain. We categorize multimodal tasks by
focusing primarily on visual aspects based on types of insurance (e.g., auto,
household/commercial property, health, and agricultural insurance) and
insurance stages (e.g., risk assessment, risk monitoring, and claims
processing). Our experiment reveals that GPT-4V exhibits remarkable abilities
in insurance-related tasks, demonstrating not only a robust understanding of
multimodal content in the insurance domain but also a comprehensive knowledge
of insurance scenarios. However, there are notable shortcomings: GPT-4V
struggles with detailed risk rating and loss assessment, suffers from
hallucination in image understanding, and shows variable support for different
languages. Through this work, we aim to bridge the insurance domain with
cutting-edge LMM technology, facilitate interdisciplinary exchange and
development, and provide a foundation for the continued advancement and
evolution of future research endeavors.|Chenwei Lin et.al.|[2404.09690v1](http://arxiv.org/abs/2404.09690v1)|null|
|**2024-04-15**|**Privacy-Preserving Intrusion Detection using Convolutional Neural Networks**|Privacy-preserving analytics is designed to protect valuable assets. A common
service provision involves the input data from the client and the model on the
analyst's side. The importance of the privacy preservation is fuelled by legal
obligations and intellectual property concerns. We explore the use case of a
model owner providing an analytic service on customer's private data. No
information about the data shall be revealed to the analyst and no information
about the model shall be leaked to the customer. Current methods involve costs:
accuracy deterioration and computational complexity. The complexity, in turn,
results in a longer processing time, increased requirement on computing
resources, and involves data communication between the client and the server.
In order to deploy such service architecture, we need to evaluate the optimal
setting that fits the constraints. And that is what this paper addresses. In
this work, we enhance an attack detection system based on Convolutional Neural
Networks with privacy-preserving technology based on PriMIA framework that is
initially designed for medical data.|Martin Kodys et.al.|[2404.09625v1](http://arxiv.org/abs/2404.09625v1)|null|
|**2024-04-15**|**Efficient and accurate neural field reconstruction using resistive memory**|Human beings construct perception of space by integrating sparse observations
into massively interconnected synapses and neurons, offering a superior
parallelism and efficiency. Replicating this capability in AI finds wide
applications in medical imaging, AR/VR, and embodied AI, where input data is
often sparse and computing resources are limited. However, traditional signal
reconstruction methods on digital computers face both software and hardware
challenges. On the software front, difficulties arise from storage
inefficiencies in conventional explicit signal representation. Hardware
obstacles include the von Neumann bottleneck, which limits data transfer
between the CPU and memory, and the limitations of CMOS circuits in supporting
parallel processing. We propose a systematic approach with software-hardware
co-optimizations for signal reconstruction from sparse inputs. Software-wise,
we employ neural field to implicitly represent signals via neural networks,
which is further compressed using low-rank decomposition and structured
pruning. Hardware-wise, we design a resistive memory-based computing-in-memory
(CIM) platform, featuring a Gaussian Encoder (GE) and an MLP Processing Engine
(PE). The GE harnesses the intrinsic stochasticity of resistive memory for
efficient input encoding, while the PE achieves precise weight mapping through
a Hardware-Aware Quantization (HAQ) circuit. We demonstrate the system's
efficacy on a 40nm 256Kb resistive memory-based in-memory computing macro,
achieving huge energy efficiency and parallelism improvements without
compromising reconstruction quality in tasks like 3D CT sparse reconstruction,
novel view synthesis, and novel view synthesis for dynamic scenes. This work
advances the AI-driven signal restoration technology and paves the way for
future efficient and robust medical AI and 3D vision applications.|Yifei Yu et.al.|[2404.09613v1](http://arxiv.org/abs/2404.09613v1)|null|
|**2024-04-15**|**WiTUnet: A U-Shaped Architecture Integrating CNN and Transformer for Improved Feature Alignment and Local Information Fusion**|Low-dose computed tomography (LDCT) has become the technology of choice for
diagnostic medical imaging, given its lower radiation dose compared to standard
CT, despite increasing image noise and potentially affecting diagnostic
accuracy. To address this, advanced deep learning-based LDCT denoising
algorithms have been developed, primarily using Convolutional Neural Networks
(CNNs) or Transformer Networks with the Unet architecture. This architecture
enhances image detail by integrating feature maps from the encoder and decoder
via skip connections. However, current methods often overlook enhancements to
the Unet architecture itself, focusing instead on optimizing encoder and
decoder structures. This approach can be problematic due to the significant
differences in feature map characteristics between the encoder and decoder,
where simple fusion strategies may not effectively reconstruct images.In this
paper, we introduce WiTUnet, a novel LDCT image denoising method that utilizes
nested, dense skip pathways instead of traditional skip connections to improve
feature integration. WiTUnet also incorporates a windowed Transformer structure
to process images in smaller, non-overlapping segments, reducing computational
load. Additionally, the integration of a Local Image Perception Enhancement
(LiPe) module in both the encoder and decoder replaces the standard multi-layer
perceptron (MLP) in Transformers, enhancing local feature capture and
representation. Through extensive experimental comparisons, WiTUnet has
demonstrated superior performance over existing methods in key metrics such as
Peak Signal-to-Noise Ratio (PSNR), Structural Similarity (SSIM), and Root Mean
Square Error (RMSE), significantly improving noise removal and image quality.|Bin Wang et.al.|[2404.09533v1](http://arxiv.org/abs/2404.09533v1)|[link](https://github.com/woldier/witunet)|
|**2024-04-14**|**Weight Copy and Low-Rank Adaptation for Few-Shot Distillation of Vision Transformers**|Few-shot knowledge distillation recently emerged as a viable approach to
harness the knowledge of large-scale pre-trained models, using limited data and
computational resources. In this paper, we propose a novel few-shot feature
distillation approach for vision transformers. Our approach is based on two key
steps. Leveraging the fact that vision transformers have a consistent
depth-wise structure, we first copy the weights from intermittent layers of
existing pre-trained vision transformers (teachers) into shallower
architectures (students), where the intermittence factor controls the
complexity of the student transformer with respect to its teacher. Next, we
employ an enhanced version of Low-Rank Adaptation (LoRA) to distill knowledge
into the student in a few-shot scenario, aiming to recover the information
processing carried out by the skipped teacher layers. We present comprehensive
experiments with supervised and self-supervised transformers as teachers, on
five data sets from various domains, including natural, medical and satellite
images. The empirical results confirm the superiority of our approach over
competitive baselines. Moreover, the ablation results demonstrate the
usefulness of each component of the proposed pipeline.|Diana-Nicoleta Grigore et.al.|[2404.09326v2](http://arxiv.org/abs/2404.09326v2)|null|
|**2024-04-14**|**Characterizing Soft-Error Resiliency in Arm's Ethos-U55 Embedded Machine Learning Accelerator**|As Neural Processing Units (NPU) or accelerators are increasingly deployed in
a variety of applications including safety critical applications such as
autonomous vehicle, and medical imaging, it is critical to understand the
fault-tolerance nature of the NPUs. We present a reliability study of Arm's
Ethos-U55, an important industrial-scale NPU being utilised in embedded and IoT
applications. We perform large scale RTL-level fault injections to characterize
Ethos-U55 against the Automotive Safety Integrity Level D (ASIL-D) resiliency
standard commonly used for safety-critical applications such as autonomous
vehicles. We show that, under soft errors, all four configurations of the NPU
fall short of the required level of resiliency for a variety of neural networks
running on the NPU. We show that it is possible to meet the ASIL-D level
resiliency without resorting to conventional strategies like Dual Core Lock
Step (DCLS) that has an area overhead of 100%. We achieve so through selective
protection, where hardware structures are selectively protected (e.g.,
duplicated, hardened) based on their sensitivity to soft errors and their
silicon areas. To identify the optimal configuration that minimizes the area
overhead while meeting the ASIL-D standard, the main challenge is the large
search space associated with the time-consuming RTL simulation. To address this
challenge, we present a statistical analysis tool that is validated against Arm
silicon and that allows us to quickly navigate hundreds of billions of fault
sites without exhaustive RTL fault injections. We show that by carefully
duplicating a small fraction of the functional blocks and hardening the Flops
in other blocks meets the ASIL-D safety standard while introducing an area
overhead of only 38%.|Abhishek Tyagi et.al.|[2404.09317v1](http://arxiv.org/abs/2404.09317v1)|null|
|**2024-04-14**|**TLDR at SemEval-2024 Task 2: T5-generated clinical-Language summaries for DeBERTa Report Analysis**|This paper introduces novel methodologies for the Natural Language Inference
for Clinical Trials (NLI4CT) task. We present TLDR (T5-generated
clinical-Language summaries for DeBERTa Report Analysis) which incorporates
T5-model generated premise summaries for improved entailment and contradiction
analysis in clinical NLI tasks. This approach overcomes the challenges posed by
small context windows and lengthy premises, leading to a substantial
improvement in Macro F1 scores: a 0.184 increase over truncated premises. Our
comprehensive experimental evaluation, including detailed error analysis and
ablations, confirms the superiority of TLDR in achieving consistency and
faithfulness in predictions against semantically altered inputs.|Spandan Das et.al.|[2404.09136v1](http://arxiv.org/abs/2404.09136v1)|[link](https://github.com/shahriarnz14/tldr-t5-generated-clinical-language-for-deberta-report-analysis)|
|**2024-04-13**|**Advanced Neural Network Architecture for Enhanced Multi-Lead ECG Arrhythmia Detection through Optimized Feature Extraction**|Cardiovascular diseases are a pervasive global health concern, contributing
significantly to morbidity and mortality rates worldwide. Among these
conditions, arrhythmia, characterized by irregular heart rhythms, presents
formidable diagnostic challenges. This study introduces an innovative approach
utilizing deep learning techniques, specifically Convolutional Neural Networks
(CNNs), to address the complexities of arrhythmia classification. Leveraging
multi-lead Electrocardiogram (ECG) data, our CNN model, comprising six layers
with a residual block, demonstrates promising outcomes in identifying five
distinct heartbeat types: Left Bundle Branch Block (LBBB), Right Bundle Branch
Block (RBBB), Atrial Premature Contraction (APC), Premature Ventricular
Contraction (PVC), and Normal Beat. Through rigorous experimentation, we
highlight the transformative potential of our methodology in enhancing
diagnostic accuracy for cardiovascular arrhythmias. Arrhythmia diagnosis
remains a critical challenge in cardiovascular care, often relying on manual
interpretation of ECG signals, which can be time-consuming and prone to
subjectivity. To address these limitations, we propose a novel approach that
leverages deep learning algorithms to automate arrhythmia classification. By
employing advanced CNN architectures and multi-lead ECG data, our methodology
offers a robust solution for precise and efficient arrhythmia detection.
Through comprehensive evaluation, we demonstrate the effectiveness of our
approach in facilitating more accurate clinical decision-making, thereby
improving patient outcomes in managing cardiovascular arrhythmias.|Bhavith Chandra Challagundla et.al.|[2404.15347v1](http://arxiv.org/abs/2404.15347v1)|null|
|**2024-04-13**|**Adapting Mental Health Prediction Tasks for Cross-lingual Learning via Meta-Training and In-context Learning with Large Language Model**|Timely identification is essential for the efficient handling of mental
health illnesses such as depression. However, the current research fails to
adequately address the prediction of mental health conditions from social media
data in low-resource African languages like Swahili. This study introduces two
distinct approaches utilising model-agnostic meta-learning and leveraging large
language models (LLMs) to address this gap. Experiments are conducted on three
datasets translated to low-resource language and applied to four mental health
tasks, which include stress, depression, depression severity and suicidal
ideation prediction. we first apply a meta-learning model with
self-supervision, which results in improved model initialisation for rapid
adaptation and cross-lingual transfer. The results show that our meta-trained
model performs significantly better than standard fine-tuning methods,
outperforming the baseline fine-tuning in macro F1 score with 18\% and 0.8\%
over XLM-R and mBERT. In parallel, we use LLMs' in-context learning
capabilities to assess their performance accuracy across the Swahili mental
health prediction tasks by analysing different cross-lingual prompting
approaches. Our analysis showed that Swahili prompts performed better than
cross-lingual prompts but less than English prompts. Our findings show that
in-context learning can be achieved through cross-lingual transfer through
carefully crafted prompt templates with examples and instructions.|Zita Lifelo et.al.|[2404.09045v1](http://arxiv.org/abs/2404.09045v1)|null|
|**2024-04-13**|**A Fourier-enhanced multi-modal 3D small object optical mark recognition and positioning method for percutaneous abdominal puncture surgical navigation**|Navigation for thoracoabdominal puncture surgery is used to locate the needle
entry point on the patient's body surface. The traditional reflective ball
navigation method is difficult to position the needle entry point on the soft,
irregular, smooth chest and abdomen. Due to the lack of clear characteristic
points on the body surface using structured light technology, it is difficult
to identify and locate arbitrary needle insertion points. Based on the high
stability and high accuracy requirements of surgical navigation, this paper
proposed a novel method, a muti-modal 3D small object medical marker detection
method, which identifies the center of a small single ring as the needle
insertion point. Moreover, this novel method leverages Fourier transform
enhancement technology to augment the dataset, enrich image details, and
enhance the network's capability. The method extracts the Region of Interest
(ROI) of the feature image from both enhanced and original images, followed by
generating a mask map. Subsequently, the point cloud of the ROI from the depth
map is obtained through the registration of ROI point cloud contour fitting. In
addition, this method employs Tukey loss for optimal precision. The
experimental results show this novel method proposed in this paper not only
achieves high-precision and high-stability positioning, but also enables the
positioning of any needle insertion point.|Zezhao Guo et.al.|[2404.08990v1](http://arxiv.org/abs/2404.08990v1)|null|
|**2024-04-13**|**Leveraging Large Language Model as Simulated Patients for Clinical Education**|Simulated Patients (SPs) play a crucial role in clinical medical education by
providing realistic scenarios for student practice. However, the high cost of
training and hiring qualified SPs, along with the heavy workload and potential
risks they face in consistently portraying actual patients, limit students'
access to this type of clinical training. Consequently, the integration of
computer program-based simulated patients has emerged as a valuable educational
tool in recent years. With the rapid development of Large Language Models
(LLMs), their exceptional capabilities in conversational artificial
intelligence and role-playing have been demonstrated, making them a feasible
option for implementing Virtual Simulated Patient (VSP). In this paper, we
present an integrated model-agnostic framework called CureFun that harnesses
the potential of LLMs in clinical medical education. This framework facilitates
natural conversations between students and simulated patients, evaluates their
dialogue, and provides suggestions to enhance students' clinical inquiry
skills. Through comprehensive evaluations, our approach demonstrates more
authentic and professional SP-scenario dialogue flows compared to other
LLM-based chatbots, thus proving its proficiency in simulating patients.
Additionally, leveraging CureFun's evaluation ability, we assess several
medical LLMs and discuss the possibilities and limitations of using LLMs as
virtual doctors from the perspective of their diagnostic abilities.|Yanzeng Li et.al.|[2404.13066v2](http://arxiv.org/abs/2404.13066v2)|null|
|**2024-04-12**|**Is ChatGPT Transforming Academics' Writing Style?**|Based on one million arXiv papers submitted from May 2018 to January 2024, we
assess the textual density of ChatGPT's writing style in their abstracts by
means of a statistical analysis of word frequency changes. Our model is
calibrated and validated on a mixture of real abstracts and ChatGPT-modified
abstracts (simulated data) after a careful noise analysis. We find that ChatGPT
is having an increasing impact on arXiv abstracts, especially in the field of
computer science, where the fraction of ChatGPT-revised abstracts is estimated
to be approximately 35%, if we take the output of one of the simplest prompts,
"revise the following sentences", as a baseline. We conclude with an analysis
of both positive and negative aspects of the penetration of ChatGPT into
academics' writing style.|Mingmeng Geng et.al.|[2404.08627v1](http://arxiv.org/abs/2404.08627v1)|null|
|**2024-04-12**|**Automatic Quantification of Serial PET/CT Images for Pediatric Hodgkin Lymphoma Patients Using a Longitudinally-Aware Segmentation Network**|$\textbf{Purpose}$: Automatic quantification of longitudinal changes in PET
scans for lymphoma patients has proven challenging, as residual disease in
interim-therapy scans is often subtle and difficult to detect. Our goal was to
develop a longitudinally-aware segmentation network (LAS-Net) that can quantify
serial PET/CT images for pediatric Hodgkin lymphoma patients.
$\textbf{Materials and Methods}$: This retrospective study included baseline
(PET1) and interim (PET2) PET/CT images from 297 patients enrolled in two
Children's Oncology Group clinical trials (AHOD1331 and AHOD0831). LAS-Net
incorporates longitudinal cross-attention, allowing relevant features from PET1
to inform the analysis of PET2. Model performance was evaluated using Dice
coefficients for PET1 and detection F1 scores for PET2. Additionally, we
extracted and compared quantitative PET metrics, including metabolic tumor
volume (MTV) and total lesion glycolysis (TLG) in PET1, as well as qPET and
$\Delta$SUVmax in PET2, against physician measurements. We quantified their
agreement using Spearman's $\rho$ correlations and employed bootstrap
resampling for statistical analysis. $\textbf{Results}$: LAS-Net detected
residual lymphoma in PET2 with an F1 score of 0.606 (precision/recall:
0.615/0.600), outperforming all comparator methods (P<0.01). For baseline
segmentation, LAS-Net achieved a mean Dice score of 0.772. In PET
quantification, LAS-Net's measurements of qPET, $\Delta$SUVmax, MTV and TLG
were strongly correlated with physician measurements, with Spearman's $\rho$ of
0.78, 0.80, 0.93 and 0.96, respectively. The performance remained high, with a
slight decrease, in an external testing cohort. $\textbf{Conclusion}$: LAS-Net
achieved high performance in quantifying PET metrics across serial scans,
highlighting the value of longitudinal awareness in evaluating multi-time-point
imaging datasets.|Xin Tie et.al.|[2404.08611v1](http://arxiv.org/abs/2404.08611v1)|[link](https://github.com/xtie97/las-net)|
|**2024-04-12**|**RLHF Deciphered: A Critical Analysis of Reinforcement Learning from Human Feedback for LLMs**|State-of-the-art large language models (LLMs) have become indispensable tools
for various tasks. However, training LLMs to serve as effective assistants for
humans requires careful consideration. A promising approach is reinforcement
learning from human feedback (RLHF), which leverages human feedback to update
the model in accordance with human preferences and mitigate issues like
toxicity and hallucinations. Yet, an understanding of RLHF for LLMs is largely
entangled with initial design choices that popularized the method and current
research focuses on augmenting those choices rather than fundamentally
improving the framework. In this paper, we analyze RLHF through the lens of
reinforcement learning principles to develop an understanding of its
fundamentals, dedicating substantial focus to the core component of RLHF -- the
reward model. Our study investigates modeling choices, caveats of function
approximation, and their implications on RLHF training algorithms, highlighting
the underlying assumptions made about the expressivity of reward. Our analysis
improves the understanding of the role of reward models and methods for their
training, concurrently revealing limitations of the current methodology. We
characterize these limitations, including incorrect generalization, model
misspecification, and the sparsity of feedback, along with their impact on the
performance of a language model. The discussion and analysis are substantiated
by a categorical review of current literature, serving as a reference for
researchers and practitioners to understand the challenges of RLHF and build
upon existing efforts.|Shreyas Chaudhari et.al.|[2404.08555v2](http://arxiv.org/abs/2404.08555v2)|null|
|**2024-04-12**|**An improved tabular data generator with VAE-GMM integration**|The rising use of machine learning in various fields requires robust methods
to create synthetic tabular data. Data should preserve key characteristics
while addressing data scarcity challenges. Current approaches based on
Generative Adversarial Networks, such as the state-of-the-art CTGAN model,
struggle with the complex structures inherent in tabular data. These data often
contain both continuous and discrete features with non-Gaussian distributions.
Therefore, we propose a novel Variational Autoencoder (VAE)-based model that
addresses these limitations. Inspired by the TVAE model, our approach
incorporates a Bayesian Gaussian Mixture model (BGM) within the VAE
architecture. This avoids the limitations imposed by assuming a strictly
Gaussian latent space, allowing for a more accurate representation of the
underlying data distribution during data generation. Furthermore, our model
offers enhanced flexibility by allowing the use of various differentiable
distributions for individual features, making it possible to handle both
continuous and discrete data types. We thoroughly validate our model on three
real-world datasets with mixed data types, including two medically relevant
ones, based on their resemblance and utility. This evaluation demonstrates
significant outperformance against CTGAN and TVAE, establishing its potential
as a valuable tool for generating synthetic tabular data in various domains,
particularly in healthcare.|Patricia A. Apellániz et.al.|[2404.08434v1](http://arxiv.org/abs/2404.08434v1)|null|
|**2024-04-12**|**Improving Health Question Answering with Reliable and Time-Aware Evidence Retrieval**|In today's digital world, seeking answers to health questions on the Internet
is a common practice. However, existing question answering (QA) systems often
rely on using pre-selected and annotated evidence documents, thus making them
inadequate for addressing novel questions. Our study focuses on the open-domain
QA setting, where the key challenge is to first uncover relevant evidence in
large knowledge bases. By utilizing the common retrieve-then-read QA pipeline
and PubMed as a trustworthy collection of medical research documents, we answer
health questions from three diverse datasets. We modify different retrieval
settings to observe their influence on the QA pipeline's performance, including
the number of retrieved documents, sentence selection process, the publication
year of articles, and their number of citations. Our results reveal that
cutting down on the amount of retrieved documents and favoring more recent and
highly cited documents can improve the final macro F1 score up to 10%. We
discuss the results, highlight interesting examples, and outline challenges for
future research, like managing evidence disagreement and crafting user-friendly
explanations.|Juraj Vladika et.al.|[2404.08359v1](http://arxiv.org/abs/2404.08359v1)|[link](https://github.com/jvladika/improving-health-qa)|
|**2024-04-11**|**Generating Synthetic Satellite Imagery With Deep-Learning Text-to-Image Models -- Technical Challenges and Implications for Monitoring and Verification**|Novel deep-learning (DL) architectures have reached a level where they can
generate digital media, including photorealistic images, that are difficult to
distinguish from real data. These technologies have already been used to
generate training data for Machine Learning (ML) models, and large
text-to-image models like DALL-E 2, Imagen, and Stable Diffusion are achieving
remarkable results in realistic high-resolution image generation. Given these
developments, issues of data authentication in monitoring and verification
deserve a careful and systematic analysis: How realistic are synthetic images?
How easily can they be generated? How useful are they for ML researchers, and
what is their potential for Open Science? In this work, we use novel DL models
to explore how synthetic satellite images can be created using conditioning
mechanisms. We investigate the challenges of synthetic satellite image
generation and evaluate the results based on authenticity and state-of-the-art
metrics. Furthermore, we investigate how synthetic data can alleviate the lack
of data in the context of ML methods for remote-sensing. Finally we discuss
implications of synthetic satellite imagery in the context of monitoring and
verification.|Tuong Vy Nguyen et.al.|[2404.07754v1](http://arxiv.org/abs/2404.07754v1)|null|
|**2024-04-11**|**Medical mT5: An Open-Source Multilingual Text-to-Text LLM for The Medical Domain**|Research on language technology for the development of medical applications
is currently a hot topic in Natural Language Understanding and Generation.
Thus, a number of large language models (LLMs) have recently been adapted to
the medical domain, so that they can be used as a tool for mediating in
human-AI interaction. While these LLMs display competitive performance on
automated medical texts benchmarks, they have been pre-trained and evaluated
with a focus on a single language (English mostly). This is particularly true
of text-to-text models, which typically require large amounts of
domain-specific pre-training data, often not easily accessible for many
languages. In this paper, we address these shortcomings by compiling, to the
best of our knowledge, the largest multilingual corpus for the medical domain
in four languages, namely English, French, Italian and Spanish. This new corpus
has been used to train Medical mT5, the first open-source text-to-text
multilingual model for the medical domain. Additionally, we present two new
evaluation benchmarks for all four languages with the aim of facilitating
multilingual research in this domain. A comprehensive evaluation shows that
Medical mT5 outperforms both encoders and similarly sized text-to-text models
for the Spanish, French, and Italian benchmarks, while being competitive with
current state-of-the-art LLMs in English.|Iker García-Ferrero et.al.|[2404.07613v1](http://arxiv.org/abs/2404.07613v1)|null|
|**2024-04-11**|**Contrastive-Based Deep Embeddings for Label Noise-Resilient Histopathology Image Classification**|Recent advancements in deep learning have proven highly effective in medical
image classification, notably within histopathology. However, noisy labels
represent a critical challenge in histopathology image classification, where
accurate annotations are vital for training robust deep learning models.
Indeed, deep neural networks can easily overfit label noise, leading to severe
degradations in model performance. While numerous public pathology foundation
models have emerged recently, none have evaluated their resilience to label
noise. Through thorough empirical analyses across multiple datasets, we exhibit
the label noise resilience property of embeddings extracted from foundation
models trained in a self-supervised contrastive manner. We demonstrate that
training with such embeddings substantially enhances label noise robustness
when compared to non-contrastive-based ones as well as commonly used
noise-resilient methods. Our results unequivocally underline the superiority of
contrastive learning in effectively mitigating the label noise challenge. Code
is publicly available at
https://github.com/LucasDedieu/NoiseResilientHistopathology.|Lucas Dedieu et.al.|[2404.07605v1](http://arxiv.org/abs/2404.07605v1)|[link](https://github.com/lucasdedieu/noiseresilienthistopathology)|
|**2024-04-11**|**Socially Pertinent Robots in Gerontological Healthcare**|Despite the many recent achievements in developing and deploying social
robotics, there are still many underexplored environments and applications for
which systematic evaluation of such systems by end-users is necessary. While
several robotic platforms have been used in gerontological healthcare, the
question of whether or not a social interactive robot with multi-modal
conversational capabilities will be useful and accepted in real-life facilities
is yet to be answered. This paper is an attempt to partially answer this
question, via two waves of experiments with patients and companions in a
day-care gerontological facility in Paris with a full-sized humanoid robot
endowed with social and conversational interaction capabilities. The software
architecture, developed during the H2020 SPRING project, together with the
experimental protocol, allowed us to evaluate the acceptability (AES) and
usability (SUS) with more than 60 end-users. Overall, the users are receptive
to this technology, especially when the robot perception and action skills are
robust to environmental clutter and flexible to handle a plethora of different
interactions.|Xavier Alameda-Pineda et.al.|[2404.07560v1](http://arxiv.org/abs/2404.07560v1)|null|
|**2024-04-11**|**Introducing L2M3, A Multilingual Medical Large Language Model to Advance Health Equity in Low-Resource Regions**|Addressing the imminent shortfall of 10 million health workers by 2030,
predominantly in Low- and Middle-Income Countries (LMICs), this paper
introduces an innovative approach that harnesses the power of Large Language
Models (LLMs) integrated with machine translation models. This solution is
engineered to meet the unique needs of Community Health Workers (CHWs),
overcoming language barriers, cultural sensitivities, and the limited
availability of medical dialog datasets. I have crafted a model that not only
boasts superior translation capabilities but also undergoes rigorous
fine-tuning on open-source datasets to ensure medical accuracy and is equipped
with comprehensive safety features to counteract the risks of misinformation.
  Featuring a modular design, this approach is specifically structured for
swift adaptation across various linguistic and cultural contexts, utilizing
open-source components to significantly reduce healthcare operational costs.
This strategic innovation markedly improves the accessibility and quality of
healthcare services by providing CHWs with contextually appropriate medical
knowledge and diagnostic tools. This paper highlights the transformative impact
of this context-aware LLM, underscoring its crucial role in addressing the
global healthcare workforce deficit and propelling forward healthcare outcomes
in LMICs.|Agasthya Gangavarapu et.al.|[2404.08705v1](http://arxiv.org/abs/2404.08705v1)|null|
|**2024-04-10**|**Measuring proximity to standard planes during fetal brain ultrasound scanning**|This paper introduces a novel pipeline designed to bring ultrasound (US)
plane pose estimation closer to clinical use for more effective navigation to
the standard planes (SPs) in the fetal brain. We propose a semi-supervised
segmentation model utilizing both labeled SPs and unlabeled 3D US volume
slices. Our model enables reliable segmentation across a diverse set of fetal
brain images. Furthermore, the model incorporates a classification mechanism to
identify the fetal brain precisely. Our model not only filters out frames
lacking the brain but also generates masks for those containing it, enhancing
the relevance of plane pose regression in clinical settings. We focus on fetal
brain navigation from 2D ultrasound (US) video analysis and combine this model
with a US plane pose regression network to provide sensorless proximity
detection to SPs and non-SPs planes; we emphasize the importance of proximity
detection to SPs for guiding sonographers, offering a substantial advantage
over traditional methods by allowing earlier and more precise adjustments
during scanning. We demonstrate the practical applicability of our approach
through validation on real fetal scan videos obtained from sonographers of
varying expertise levels. Our findings demonstrate the potential of our
approach to complement existing fetal US technologies and advance prenatal
diagnostic practices.|Chiara Di Vece et.al.|[2404.07124v1](http://arxiv.org/abs/2404.07124v1)|null|
|**2024-04-10**|**Advancing Real-time Pandemic Forecasting Using Large Language Models: A COVID-19 Case Study**|Forecasting the short-term spread of an ongoing disease outbreak is a
formidable challenge due to the complexity of contributing factors, some of
which can be characterized through interlinked, multi-modality variables such
as epidemiological time series data, viral biology, population demographics,
and the intersection of public policy and human behavior. Existing forecasting
model frameworks struggle with the multifaceted nature of relevant data and
robust results translation, which hinders their performances and the provision
of actionable insights for public health decision-makers. Our work introduces
PandemicLLM, a novel framework with multi-modal Large Language Models (LLMs)
that reformulates real-time forecasting of disease spread as a text reasoning
problem, with the ability to incorporate real-time, complex, non-numerical
information that previously unattainable in traditional forecasting models.
This approach, through a unique AI-human cooperative prompt design and time
series representation learning, encodes multi-modal data for LLMs. The model is
applied to the COVID-19 pandemic, and trained to utilize textual public health
policies, genomic surveillance, spatial, and epidemiological time series data,
and is subsequently tested across all 50 states of the U.S. Empirically,
PandemicLLM is shown to be a high-performing pandemic forecasting framework
that effectively captures the impact of emerging variants and can provide
timely and accurate predictions. The proposed PandemicLLM opens avenues for
incorporating various pandemic-related data in heterogeneous formats and
exhibits performance benefits over existing models. This study illuminates the
potential of adapting LLMs and representation learning to enhance pandemic
forecasting, illustrating how AI innovations can strengthen pandemic responses
and crisis management in the future.|Hongru Du et.al.|[2404.06962v1](http://arxiv.org/abs/2404.06962v1)|[link](https://github.com/miemieyanga/pandemicllm)|
|**2024-04-10**|**SleepPPG-Net2: Deep learning generalization for sleep staging from photoplethysmography**|Background: Sleep staging is a fundamental component in the diagnosis of
sleep disorders and the management of sleep health. Traditionally, this
analysis is conducted in clinical settings and involves a time-consuming
scoring procedure. Recent data-driven algorithms for sleep staging, using the
photoplethysmogram (PPG) time series, have shown high performance on local test
sets but lower performance on external datasets due to data drift. Methods:
This study aimed to develop a generalizable deep learning model for the task of
four class (wake, light, deep, and rapid eye movement (REM)) sleep staging from
raw PPG physiological time-series. Six sleep datasets, totaling 2,574 patients
recordings, were used. In order to create a more generalizable representation,
we developed and evaluated a deep learning model called SleepPPG-Net2, which
employs a multi-source domain training approach.SleepPPG-Net2 was benchmarked
against two state-of-the-art models. Results: SleepPPG-Net2 showed consistently
higher performance over benchmark approaches, with generalization performance
(Cohen's kappa) improving by up to 19%. Performance disparities were observed
in relation to age, sex, and sleep apnea severity. Conclusion: SleepPPG-Net2
sets a new standard for staging sleep from raw PPG time-series.|Shirel Attia et.al.|[2404.06869v1](http://arxiv.org/abs/2404.06869v1)|null|
|**2024-04-10**|**Multi-Label Continual Learning for the Medical Domain: A Novel Benchmark**|Multi-label image classification in dynamic environments is a problem that
poses significant challenges. Previous studies have primarily focused on
scenarios such as Domain Incremental Learning and Class Incremental Learning,
which do not fully capture the complexity of real-world applications. In this
paper, we study the problem of classification of medical imaging in the
scenario termed New Instances and New Classes, which combines the challenges of
both new class arrivals and domain shifts in a single framework. Unlike
traditional scenarios, it reflects the realistic nature of CL in domains such
as medical imaging, where updates may introduce both new classes and changes in
domain characteristics. To address the unique challenges posed by this complex
scenario, we introduce a novel approach called Pseudo-Label Replay. This method
aims to mitigate forgetting while adapting to new classes and domain shifts by
combining the advantages of the Replay and Pseudo-Label methods and solving
their limitations in the proposed scenario. We evaluate our proposed approach
on a challenging benchmark consisting of two datasets, seven tasks, and
nineteen classes, modeling a realistic Continual Learning scenario. Our
experimental findings demonstrate the effectiveness of Pseudo-Label Replay in
addressing the challenges posed by the complex scenario proposed. Our method
surpasses existing approaches, exhibiting superior performance while showing
minimal forgetting.|Marina Ceccon et.al.|[2404.06859v2](http://arxiv.org/abs/2404.06859v2)|null|
|**2024-04-10**|**Accuracy of a Large Language Model in Distinguishing Anti- And Pro-vaccination Messages on Social Media: The Case of Human Papillomavirus Vaccination**|Objective. Vaccination has engendered a spectrum of public opinions, with
social media acting as a crucial platform for health-related discussions. The
emergence of artificial intelligence technologies, such as large language
models (LLMs), offers a novel opportunity to efficiently investigate public
discourses. This research assesses the accuracy of ChatGPT, a widely used and
freely available service built upon an LLM, for sentiment analysis to discern
different stances toward Human Papillomavirus (HPV) vaccination. Methods.
Messages related to HPV vaccination were collected from social media supporting
different message formats: Facebook (long format) and Twitter (short format). A
selection of 1,000 human-evaluated messages was input into the LLM, which
generated multiple response instances containing its classification results.
Accuracy was measured for each message as the level of concurrence between
human and machine decisions, ranging between 0 and 1. Results. Average accuracy
was notably high when 20 response instances were used to determine the machine
decision of each message: .882 (SE = .021) and .750 (SE = .029) for anti- and
pro-vaccination long-form; .773 (SE = .027) and .723 (SE = .029) for anti- and
pro-vaccination short-form, respectively. Using only three or even one instance
did not lead to a severe decrease in accuracy. However, for long-form messages,
the language model exhibited significantly lower accuracy in categorizing
pro-vaccination messages than anti-vaccination ones. Conclusions. ChatGPT shows
potential in analyzing public opinions on HPV vaccination using social media
content. However, understanding the characteristics and limitations of a
language model within specific public health contexts remains imperative.|Soojong Kim et.al.|[2404.06731v1](http://arxiv.org/abs/2404.06731v1)|null|
|**2024-04-09**|**Federated learning model for predicting major postoperative complications**|Background: The accurate prediction of postoperative complication risk using
Electronic Health Records (EHR) and artificial intelligence shows great
potential. Training a robust artificial intelligence model typically requires
large-scale and diverse datasets. In reality, collecting medical data often
encounters challenges surrounding privacy protection. Methods: This
retrospective cohort study includes adult patients who were admitted to UFH
Gainesville (GNV) (n = 79,850) and Jacksonville (JAX) (n = 28,636) for any type
of inpatient surgical procedure. Using perioperative and intraoperative
features, we developed federated learning models to predict nine major
postoperative complications (i.e., prolonged intensive care unit stay and
mechanical ventilation). We compared federated learning models with local
learning models trained on a single site and central learning models trained on
pooled dataset from two centers. Results: Our federated learning models
achieved the area under the receiver operating characteristics curve (AUROC)
values ranged from 0.81 for wound complications to 0.92 for prolonged ICU stay
at UFH GNV center. At UFH JAX center, these values ranged from 0.73-0.74 for
wound complications to 0.92-0.93 for hospital mortality. Federated learning
models achieved comparable AUROC performance to central learning models, except
for prolonged ICU stay, where the performance of federated learning models was
slightly higher than central learning models at UFH GNV center, but slightly
lower at UFH JAX center. In addition, our federated learning model obtained
comparable performance to the best local learning model at each center,
demonstrating strong generalizability. Conclusion: Federated learning is shown
to be a useful tool to train robust and generalizable models from large scale
data across multiple institutions where data protection barriers are high.|Yonggi Park et.al.|[2404.06641v1](http://arxiv.org/abs/2404.06641v1)|null|
|**2024-04-09**|**Test-Time Adaptation with SaLIP: A Cascade of SAM and CLIP for Zero shot Medical Image Segmentation**|The Segment Anything Model (SAM) and CLIP are remarkable vision foundation
models (VFMs). SAM, a prompt driven segmentation model, excels in segmentation
tasks across diverse domains, while CLIP is renowned for its zero shot
recognition capabilities. However, their unified potential has not yet been
explored in medical image segmentation. To adapt SAM to medical imaging,
existing methods primarily rely on tuning strategies that require extensive
data or prior prompts tailored to the specific task, making it particularly
challenging when only a limited number of data samples are available. This work
presents an in depth exploration of integrating SAM and CLIP into a unified
framework for medical image segmentation. Specifically, we propose a simple
unified framework, SaLIP, for organ segmentation. Initially, SAM is used for
part based segmentation within the image, followed by CLIP to retrieve the mask
corresponding to the region of interest (ROI) from the pool of SAM generated
masks. Finally, SAM is prompted by the retrieved ROI to segment a specific
organ. Thus, SaLIP is training and fine tuning free and does not rely on domain
expertise or labeled data for prompt engineering. Our method shows substantial
enhancements in zero shot segmentation, showcasing notable improvements in DICE
scores across diverse segmentation tasks like brain (63.46%), lung (50.11%),
and fetal head (30.82%), when compared to un prompted SAM. Code and text
prompts will be available online.|Sidra Aleem et.al.|[2404.06362v1](http://arxiv.org/abs/2404.06362v1)|null|
|**2024-04-09**|**Advancements in Radiomics and Artificial Intelligence for Thyroid Cancer Diagnosis**|Thyroid cancer is an increasing global health concern that requires advanced
diagnostic methods. The application of AI and radiomics to thyroid cancer
diagnosis is examined in this review. A review of multiple databases was
conducted in compliance with PRISMA guidelines until October 2023. A
combination of keywords led to the discovery of an English academic publication
on thyroid cancer and related subjects. 267 papers were returned from the
original search after 109 duplicates were removed. Relevant studies were
selected according to predetermined criteria after 124 articles were eliminated
based on an examination of their abstract and title. After the comprehensive
analysis, an additional six studies were excluded. Among the 28 included
studies, radiomics analysis, which incorporates ultrasound (US) images,
demonstrated its effectiveness in diagnosing thyroid cancer. Various results
were noted, some of the studies presenting new strategies that outperformed the
status quo. The literature has emphasized various challenges faced by AI
models, including interpretability issues, dataset constraints, and operator
dependence. The synthesized findings of the 28 included studies mentioned the
need for standardization efforts and prospective multicenter studies to address
these concerns. Furthermore, approaches to overcome these obstacles were
identified, such as advances in explainable AI technology and personalized
medicine techniques. The review focuses on how AI and radiomics could transform
the diagnosis and treatment of thyroid cancer. Despite challenges, future
research on multidisciplinary cooperation, clinical applicability validation,
and algorithm improvement holds the potential to improve patient outcomes and
diagnostic precision in the treatment of thyroid cancer.|Milad Yousefi et.al.|[2404.07239v1](http://arxiv.org/abs/2404.07239v1)|null|
|**2024-04-09**|**EPL: Evidential Prototype Learning for Semi-supervised Medical Image Segmentation**|Although current semi-supervised medical segmentation methods can achieve
decent performance, they are still affected by the uncertainty in unlabeled
data and model predictions, and there is currently a lack of effective
strategies that can explore the uncertain aspects of both simultaneously. To
address the aforementioned issues, we propose Evidential Prototype Learning
(EPL), which utilizes an extended probabilistic framework to effectively fuse
voxel probability predictions from different sources and achieves prototype
fusion utilization of labeled and unlabeled data under a generalized evidential
framework, leveraging voxel-level dual uncertainty masking. The uncertainty not
only enables the model to self-correct predictions but also improves the guided
learning process with pseudo-labels and is able to feed back into the
construction of hidden features. The method proposed in this paper has been
experimented on LA, Pancreas-CT and TBAD datasets, achieving the
state-of-the-art performance in three different labeled ratios, which strongly
demonstrates the effectiveness of our strategy.|Yuanpeng He et.al.|[2404.06181v1](http://arxiv.org/abs/2404.06181v1)|null|
|**2024-04-09**|**Uncertainty-aware Evidential Fusion-based Learning for Semi-supervised Medical Image Segmentation**|Although the existing uncertainty-based semi-supervised medical segmentation
methods have achieved excellent performance, they usually only consider a
single uncertainty evaluation, which often fails to solve the problem related
to credibility completely. Therefore, based on the framework of evidential deep
learning, this paper integrates the evidential predictive results in the
cross-region of mixed and original samples to reallocate the confidence degree
and uncertainty measure of each voxel, which is realized by emphasizing
uncertain information of probability assignments fusion rule of traditional
evidence theory. Furthermore, we design a voxel-level asymptotic learning
strategy by introducing information entropy to combine with the fused
uncertainty measure to estimate voxel prediction more precisely. The model will
gradually pay attention to the prediction results with high uncertainty in the
learning process, to learn the features that are difficult to master. The
experimental results on LA, Pancreas-CT, ACDC and TBAD datasets demonstrate the
superior performance of our proposed method in comparison with the existing
state of the arts.|Yuanpeng He et.al.|[2404.06177v2](http://arxiv.org/abs/2404.06177v2)|null|
|**2024-04-09**|**Tackling Structural Hallucination in Image Translation with Local Diffusion**|Recent developments in diffusion models have advanced conditioned image
generation, yet they struggle with reconstructing out-of-distribution (OOD)
images, such as unseen tumors in medical images, causing "image hallucination"
and risking misdiagnosis. We hypothesize such hallucinations result from local
OOD regions in the conditional images. We verify that partitioning the OOD
region and conducting separate image generations alleviates hallucinations in
several applications. From this, we propose a training-free diffusion framework
that reduces hallucination with multiple Local Diffusion processes. Our
approach involves OOD estimation followed by two modules: a "branching" module
generates locally both within and outside OOD regions, and a "fusion" module
integrates these predictions into one. Our evaluation shows our method
mitigates hallucination over baseline models quantitatively and qualitatively,
reducing misdiagnosis by 40% and 25% in the real-world medical and natural
image datasets, respectively. It also demonstrates compatibility with various
pre-trained diffusion models.|Seunghoi Kim et.al.|[2404.05980v3](http://arxiv.org/abs/2404.05980v3)|null|

### Medical explainable AI
|Publish Date|Title|Authors|PDF|Code|
| :---: | :---: | :---: | :---: | :---: |
|**2024-04-25**|**Attributing Responsibility in AI-Induced Incidents: A Computational Reflective Equilibrium Framework for Accountability**|The pervasive integration of Artificial Intelligence (AI) has introduced
complex challenges in the responsibility and accountability in the event of
incidents involving AI-enabled systems. The interconnectivity of these systems,
ethical concerns of AI-induced incidents, coupled with uncertainties in AI
technology and the absence of corresponding regulations, have made traditional
responsibility attribution challenging. To this end, this work proposes a
Computational Reflective Equilibrium (CRE) approach to establish a coherent and
ethically acceptable responsibility attribution framework for all stakeholders.
The computational approach provides a structured analysis that overcomes the
limitations of conceptual approaches in dealing with dynamic and multifaceted
scenarios, showcasing the framework's explainability, coherence, and adaptivity
properties in the responsibility attribution process. We examine the pivotal
role of the initial activation level associated with claims in equilibrium
computation. Using an AI-assisted medical decision-support system as a case
study, we illustrate how different initializations lead to diverse
responsibility distributions. The framework offers valuable insights into
accountability in AI-induced incidents, facilitating the development of a
sustainable and resilient system through continuous monitoring, revision, and
reflection.|Yunfei Ge et.al.|[2404.16957v1](http://arxiv.org/abs/2404.16957v1)|null|
|**2024-04-19**|**Explainable AI for Fair Sepsis Mortality Predictive Model**|Artificial intelligence supports healthcare professionals with predictive
modeling, greatly transforming clinical decision-making. This study addresses
the crucial need for fairness and explainability in AI applications within
healthcare to ensure equitable outcomes across diverse patient demographics. By
focusing on the predictive modeling of sepsis-related mortality, we propose a
method that learns a performance-optimized predictive model and then employs
the transfer learning process to produce a model with better fairness. Our
method also introduces a novel permutation-based feature importance algorithm
aiming at elucidating the contribution of each feature in enhancing fairness on
predictions. Unlike existing explainability methods concentrating on explaining
feature contribution to predictive performance, our proposed method uniquely
bridges the gap in understanding how each feature contributes to fairness. This
advancement is pivotal, given sepsis's significant mortality rate and its role
in one-third of hospital deaths. Our method not only aids in identifying and
mitigating biases within the predictive model but also fosters trust among
healthcare stakeholders by improving the transparency and fairness of model
predictions, thereby contributing to more equitable and trustworthy healthcare
delivery.|Chia-Hsuan Chang et.al.|[2404.13139v1](http://arxiv.org/abs/2404.13139v1)|null|
|**2024-04-19**|**Multi Class Depression Detection Through Tweets using Artificial Intelligence**|Depression is a significant issue nowadays. As per the World Health
Organization (WHO), in 2023, over 280 million individuals are grappling with
depression. This is a huge number; if not taken seriously, these numbers will
increase rapidly. About 4.89 billion individuals are social media users. People
express their feelings and emotions on platforms like Twitter, Facebook,
Reddit, Instagram, etc. These platforms contain valuable information which can
be used for research purposes. Considerable research has been conducted across
various social media platforms. However, certain limitations persist in these
endeavors. Particularly, previous studies were only focused on detecting
depression and the intensity of depression in tweets. Also, there existed
inaccuracies in dataset labeling. In this research work, five types of
depression (Bipolar, major, psychotic, atypical, and postpartum) were predicted
using tweets from the Twitter database based on lexicon labeling. Explainable
AI was used to provide reasoning by highlighting the parts of tweets that
represent type of depression. Bidirectional Encoder Representations from
Transformers (BERT) was used for feature extraction and training. Machine
learning and deep learning methodologies were used to train the model. The BERT
model presented the most promising results, achieving an overall accuracy of
0.96.|Muhammad Osama Nusrat et.al.|[2404.13104v1](http://arxiv.org/abs/2404.13104v1)|[link](https://github.com/mnusrat786/masters-thesis)|
|**2024-04-19**|**COIN: Counterfactual inpainting for weakly supervised semantic segmentation for medical images**|Deep learning is dramatically transforming the field of medical imaging and
radiology, enabling the identification of pathologies in medical images,
including computed tomography (CT) and X-ray scans. However, the performance of
deep learning models, particularly in segmentation tasks, is often limited by
the need for extensive annotated datasets. To address this challenge, the
capabilities of weakly supervised semantic segmentation are explored through
the lens of Explainable AI and the generation of counterfactual explanations.
The scope of this research is development of a novel counterfactual inpainting
approach (COIN) that flips the predicted classification label from abnormal to
normal by using a generative model. For instance, if the classifier deems an
input medical image X as abnormal, indicating the presence of a pathology, the
generative model aims to inpaint the abnormal region, thus reversing the
classifier's original prediction label. The approach enables us to produce
precise segmentations for pathologies without depending on pre-existing
segmentation masks. Crucially, image-level labels are utilized, which are
substantially easier to acquire than creating detailed segmentation masks. The
effectiveness of the method is demonstrated by segmenting synthetic targets and
actual kidney tumors from CT images acquired from Tartu University Hospital in
Estonia. The findings indicate that COIN greatly surpasses established
attribution methods, such as RISE, ScoreCAM, and LayerCAM, as well as an
alternative counterfactual explanation method introduced by Singla et al. This
evidence suggests that COIN is a promising approach for semantic segmentation
of tumors in CT images, and presents a step forward in making deep learning
applications more accessible and effective in healthcare, where annotated data
is scarce.|Dmytro Shvetsov et.al.|[2404.12832v1](http://arxiv.org/abs/2404.12832v1)|[link](https://github.com/dmytro-shvetsov/counterfactual-search)|
|**2024-04-09**|**Advancements in Radiomics and Artificial Intelligence for Thyroid Cancer Diagnosis**|Thyroid cancer is an increasing global health concern that requires advanced
diagnostic methods. The application of AI and radiomics to thyroid cancer
diagnosis is examined in this review. A review of multiple databases was
conducted in compliance with PRISMA guidelines until October 2023. A
combination of keywords led to the discovery of an English academic publication
on thyroid cancer and related subjects. 267 papers were returned from the
original search after 109 duplicates were removed. Relevant studies were
selected according to predetermined criteria after 124 articles were eliminated
based on an examination of their abstract and title. After the comprehensive
analysis, an additional six studies were excluded. Among the 28 included
studies, radiomics analysis, which incorporates ultrasound (US) images,
demonstrated its effectiveness in diagnosing thyroid cancer. Various results
were noted, some of the studies presenting new strategies that outperformed the
status quo. The literature has emphasized various challenges faced by AI
models, including interpretability issues, dataset constraints, and operator
dependence. The synthesized findings of the 28 included studies mentioned the
need for standardization efforts and prospective multicenter studies to address
these concerns. Furthermore, approaches to overcome these obstacles were
identified, such as advances in explainable AI technology and personalized
medicine techniques. The review focuses on how AI and radiomics could transform
the diagnosis and treatment of thyroid cancer. Despite challenges, future
research on multidisciplinary cooperation, clinical applicability validation,
and algorithm improvement holds the potential to improve patient outcomes and
diagnostic precision in the treatment of thyroid cancer.|Milad Yousefi et.al.|[2404.07239v1](http://arxiv.org/abs/2404.07239v1)|null|
|**2024-04-06**|**Predictive Modeling for Breast Cancer Classification in the Context of Bangladeshi Patients: A Supervised Machine Learning Approach with Explainable AI**|Breast cancer has rapidly increased in prevalence in recent years, making it
one of the leading causes of mortality worldwide. Among all cancers, it is by
far the most common. Diagnosing this illness manually requires significant time
and expertise. Since detecting breast cancer is a time-consuming process,
preventing its further spread can be aided by creating machine-based forecasts.
Machine learning and Explainable AI are crucial in classification as they not
only provide accurate predictions but also offer insights into how the model
arrives at its decisions, aiding in the understanding and trustworthiness of
the classification results. In this study, we evaluate and compare the
classification accuracy, precision, recall, and F-1 scores of five different
machine learning methods using a primary dataset (500 patients from Dhaka
Medical College Hospital). Five different supervised machine learning
techniques, including decision tree, random forest, logistic regression, naive
bayes, and XGBoost, have been used to achieve optimal results on our dataset.
Additionally, this study applied SHAP analysis to the XGBoost model to
interpret the model's predictions and understand the impact of each feature on
the model's output. We compared the accuracy with which several algorithms
classified the data, as well as contrasted with other literature in this field.
After final evaluation, this study found that XGBoost achieved the best model
accuracy, which is 97%.|Taminul Islam et.al.|[2404.04686v1](http://arxiv.org/abs/2404.04686v1)|null|
|**2024-04-05**|**Enhancing Breast Cancer Diagnosis in Mammography: Evaluation and Integration of Convolutional Neural Networks and Explainable AI**|The study introduces an integrated framework combining Convolutional Neural
Networks (CNNs) and Explainable Artificial Intelligence (XAI) for the enhanced
diagnosis of breast cancer using the CBIS-DDSM dataset. Utilizing a fine-tuned
ResNet50 architecture, our investigation not only provides effective
differentiation of mammographic images into benign and malignant categories but
also addresses the opaque "black-box" nature of deep learning models by
employing XAI methodologies, namely Grad-CAM, LIME, and SHAP, to interpret CNN
decision-making processes for healthcare professionals. Our methodology
encompasses an elaborate data preprocessing pipeline and advanced data
augmentation techniques to counteract dataset limitations, and transfer
learning using pre-trained networks, such as VGG-16, DenseNet and ResNet was
employed. A focal point of our study is the evaluation of XAI's effectiveness
in interpreting model predictions, highlighted by utilising the Hausdorff
measure to assess the alignment between AI-generated explanations and expert
annotations quantitatively. This approach plays a critical role for XAI in
promoting trustworthiness and ethical fairness in AI-assisted diagnostics. The
findings from our research illustrate the effective collaboration between CNNs
and XAI in advancing diagnostic methods for breast cancer, thereby facilitating
a more seamless integration of advanced AI technologies within clinical
settings. By enhancing the interpretability of AI-driven decisions, this work
lays the groundwork for improved collaboration between AI systems and medical
practitioners, ultimately enriching patient care. Furthermore, the implications
of our research extend well beyond the current methodologies, advocating for
subsequent inquiries into the integration of multimodal data and the refinement
of AI explanations to satisfy the needs of clinical practice.|Maryam Ahmed et.al.|[2404.03892v2](http://arxiv.org/abs/2404.03892v2)|null|
|**2024-03-26**|**Addressing Social Misattributions of Large Language Models: An HCXAI-based Approach**|Human-centered explainable AI (HCXAI) advocates for the integration of social
aspects into AI explanations. Central to the HCXAI discourse is the Social
Transparency (ST) framework, which aims to make the socio-organizational
context of AI systems accessible to their users. In this work, we suggest
extending the ST framework to address the risks of social misattributions in
Large Language Models (LLMs), particularly in sensitive areas like mental
health. In fact LLMs, which are remarkably capable of simulating roles and
personas, may lead to mismatches between designers' intentions and users'
perceptions of social attributes, risking to promote emotional manipulation and
dangerous behaviors, cases of epistemic injustice, and unwarranted trust. To
address these issues, we propose enhancing the ST framework with a fifth
'W-question' to clarify the specific social attributions assigned to LLMs by
its designers and users. This addition aims to bridge the gap between LLM
capabilities and user perceptions, promoting the ethically responsible
development and use of LLM-based technology.|Andrea Ferrario et.al.|[2403.17873v1](http://arxiv.org/abs/2403.17873v1)|null|
|**2024-03-26**|**Clinical Domain Knowledge-Derived Template Improves Post Hoc AI Explanations in Pneumothorax Classification**|Background: Pneumothorax is an acute thoracic disease caused by abnormal air
collection between the lungs and chest wall. To address the opaqueness often
associated with deep learning (DL) models, explainable artificial intelligence
(XAI) methods have been introduced to outline regions related to pneumothorax
diagnoses made by DL models. However, these explanations sometimes diverge from
actual lesion areas, highlighting the need for further improvement. Method: We
propose a template-guided approach to incorporate the clinical knowledge of
pneumothorax into model explanations generated by XAI methods, thereby
enhancing the quality of these explanations. Utilizing one lesion delineation
created by radiologists, our approach first generates a template that
represents potential areas of pneumothorax occurrence. This template is then
superimposed on model explanations to filter out extraneous explanations that
fall outside the template's boundaries. To validate its efficacy, we carried
out a comparative analysis of three XAI methods with and without our template
guidance when explaining two DL models in two real-world datasets. Results: The
proposed approach consistently improved baseline XAI methods across twelve
benchmark scenarios built on three XAI methods, two DL models, and two
datasets. The average incremental percentages, calculated by the performance
improvements over the baseline performance, were 97.8% in Intersection over
Union (IoU) and 94.1% in Dice Similarity Coefficient (DSC) when comparing model
explanations and ground-truth lesion areas. Conclusions: In the context of
pneumothorax diagnoses, we proposed a template-guided approach for improving AI
explanations. We anticipate that our template guidance will forge a fresh
approach to elucidating AI models by integrating clinical domain expertise.|Han Yuan et.al.|[2403.18871v1](http://arxiv.org/abs/2403.18871v1)|null|
|**2024-03-03**|**Enhancing Neural Machine Translation of Low-Resource Languages: Corpus Development, Human Evaluation and Explainable AI Architectures**|In the current machine translation (MT) landscape, the Transformer
architecture stands out as the gold standard, especially for high-resource
language pairs. This research delves into its efficacy for low-resource
language pairs including both the English$\leftrightarrow$Irish and
English$\leftrightarrow$Marathi language pairs. Notably, the study identifies
the optimal hyperparameters and subword model type to significantly improve the
translation quality of Transformer models for low-resource language pairs.
  The scarcity of parallel datasets for low-resource languages can hinder MT
development. To address this, gaHealth was developed, the first bilingual
corpus of health data for the Irish language. Focusing on the health domain,
models developed using this in-domain dataset exhibited very significant
improvements in BLEU score when compared with models from the LoResMT2021
Shared Task. A subsequent human evaluation using the multidimensional quality
metrics error taxonomy showcased the superior performance of the Transformer
system in reducing both accuracy and fluency errors compared to an RNN-based
counterpart.
  Furthermore, this thesis introduces adaptNMT and adaptMLLM, two open-source
applications streamlined for the development, fine-tuning, and deployment of
neural machine translation models. These tools considerably simplify the setup
and evaluation process, making MT more accessible to both developers and
translators. Notably, adaptNMT, grounded in the OpenNMT ecosystem, promotes
eco-friendly natural language processing research by highlighting the
environmental footprint of model development. Fine-tuning of MLLMs by adaptMLLM
demonstrated advancements in translation performance for two low-resource
language pairs: English$\leftrightarrow$Irish and
English$\leftrightarrow$Marathi, compared to baselines from the LoResMT2021
Shared Task.|Séamus Lankford et.al.|[2403.01580v1](http://arxiv.org/abs/2403.01580v1)|null|
|**2024-02-28**|**Artificial Intelligence and Diabetes Mellitus: An Inside Look Through the Retina**|Diabetes mellitus (DM) predisposes patients to vascular complications.
Retinal images and vasculature reflect the body's micro- and macrovascular
health. They can be used to diagnose DM complications, including diabetic
retinopathy (DR), neuropathy, nephropathy, and atherosclerotic cardiovascular
disease, as well as forecast the risk of cardiovascular events. Artificial
intelligence (AI)-enabled systems developed for high-throughput detection of DR
using digitized retinal images have become clinically adopted. Beyond DR
screening, AI integration also holds immense potential to address challenges
associated with the holistic care of the patient with DM. In this work, we aim
to comprehensively review the literature for studies on AI applications based
on retinal images related to DM diagnosis, prognostication, and management. We
will describe the findings of holistic AI-assisted diabetes care, including but
not limited to DR screening, and discuss barriers to implementing such systems,
including issues concerning ethics, data privacy, equitable access, and
explainability. With the ability to evaluate the patient's health status vis a
vis DM complication as well as risk prognostication of future cardiovascular
complications, AI-assisted retinal image analysis has the potential to become a
central tool for modern personalized medicine in patients with DM.|Yasin Sadeghi Bazargani et.al.|[2402.18600v1](http://arxiv.org/abs/2402.18600v1)|null|
|**2024-02-22**|**Multi-stakeholder Perspective on Responsible Artificial Intelligence and Acceptability in Education**|This study investigates the acceptability of different artificial
intelligence (AI) applications in education from a multi-stakeholder
perspective, including students, teachers, and parents. Acknowledging the
transformative potential of AI in education, it addresses concerns related to
data privacy, AI agency, transparency, explainability and the ethical
deployment of AI. Through a vignette methodology, participants were presented
with four scenarios where AI's agency, transparency, explainability, and
privacy were manipulated. After each scenario, participants completed a survey
that captured their perceptions of AI's global utility, individual usefulness,
justice, confidence, risk, and intention to use each scenario's AI if
available. The data collection comprising a final sample of 1198
multi-stakeholder participants was distributed through a partner institution
and social media campaigns and focused on individual responses to four AI use
cases. A mediation analysis of the data indicated that acceptance and trust in
AI varies significantly across stakeholder groups. We found that the key
mediators between high and low levels of AI's agency, transparency, and
explainability, as well as the intention to use the different educational AI,
included perceived global utility, justice, and confidence. The study
highlights that the acceptance of AI in education is a nuanced and multifaceted
issue that requires careful consideration of specific AI applications and their
characteristics, in addition to the diverse stakeholders' perceptions.|A. J. Karran et.al.|[2402.15027v2](http://arxiv.org/abs/2402.15027v2)|null|
|**2024-02-12**|**Deciphering Heartbeat Signatures: A Vision Transformer Approach to Explainable Atrial Fibrillation Detection from ECG Signals**|Remote patient monitoring based on wearable single-lead electrocardiogram
(ECG) devices has significant potential for enabling the early detection of
heart disease, especially in combination with artificial intelligence (AI)
approaches for automated heart disease detection. There have been prior studies
applying AI approaches based on deep learning for heart disease detection.
However, these models are yet to be widely accepted as a reliable aid for
clinical diagnostics, in part due to the current black-box perception
surrounding many AI algorithms. In particular, there is a need to identify the
key features of the ECG signal that contribute toward making an accurate
diagnosis, thereby enhancing the interpretability of the model. In the present
study, we develop a vision transformer approach to identify atrial fibrillation
based on single-lead ECG data. A residual network (ResNet) approach is also
developed for comparison with the vision transformer approach. These models are
applied to the Chapman-Shaoxing dataset to classify atrial fibrillation, as
well as another common arrhythmia, sinus bradycardia, and normal sinus rhythm
heartbeats. The models enable the identification of the key regions of the
heartbeat that determine the resulting classification, and highlight the
importance of P-waves and T-waves, as well as heartbeat duration and signal
amplitude, in distinguishing normal sinus rhythm from atrial fibrillation and
sinus bradycardia.|Aruna Mohan et.al.|[2402.09474v1](http://arxiv.org/abs/2402.09474v1)|null|
|**2024-02-05**|**Illuminate: A novel approach for depression detection with explainable analysis and proactive therapy using prompt engineering**|This paper introduces a novel paradigm for depression detection and treatment
using advanced Large Language Models (LLMs): Generative Pre-trained Transformer
4 (GPT-4), Llama 2 chat, and Gemini. These LLMs are fine-tuned with specialized
prompts to diagnose, explain, and suggest therapeutic interventions for
depression. A unique few-shot prompting method enhances the models' ability to
analyze and explain depressive symptoms based on the DSM-5 criteria. In the
interaction phase, the models engage in empathetic dialogue management, drawing
from resources like PsychDB and a Cognitive Behavioral Therapy (CBT) Guide,
fostering supportive interactions with individuals experiencing major
depressive disorders. Additionally, the research introduces the Illuminate
Database, enriched with various CBT modules, aiding in personalized therapy
recommendations. The study evaluates LLM performance using metrics such as F1
scores, Precision, Recall, Cosine similarity, and Recall-Oriented Understudy
for Gisting Evaluation (ROUGE) across different test sets, demonstrating their
effectiveness. This comprehensive approach blends cutting-edge AI with
established psychological methods, offering new possibilities in mental health
care and showcasing the potential of LLMs in revolutionizing depression
diagnosis and treatment strategies.|Aryan Agrawal et.al.|[2402.05127v1](http://arxiv.org/abs/2402.05127v1)|null|
|**2024-01-24**|**Information That Matters: Exploring Information Needs of People Affected by Algorithmic Decisions**|Explanations of AI systems rarely address the information needs of people
affected by algorithmic decision-making (ADM). This gap between conveyed
information and information that matters to affected stakeholders can impede
understanding and adherence to regulatory frameworks such as the AI Act. To
address this gap, we present the "XAI Novice Question Bank": A catalog of
affected stakeholders' information needs in two ADM use cases (employment
prediction and health monitoring), covering the categories data, system
context, system usage, and system specifications. Information needs were
gathered in an interview study where participants received explanations in
response to their inquiries. Participants further reported their understanding
and decision confidence, showing that while confidence tended to increase after
receiving explanations, participants also met understanding challenges, such as
being unable to tell why their understanding felt incomplete. Explanations
further influenced participants' perceptions of the systems' risks and
benefits, which they confirmed or changed depending on the use case. When risks
were perceived as high, participants expressed particular interest in
explanations about intention, such as why and to what end a system was put in
place. With this work, we aim to support the inclusion of affected stakeholders
into explainability by contributing an overview of information and challenges
relevant to them when deciding on the adoption of ADM systems. We close by
summarizing our findings in a list of six key implications that inform the
design of future explanations for affected stakeholder audiences.|Timothée Schmude et.al.|[2401.13324v4](http://arxiv.org/abs/2401.13324v4)|null|
|**2024-01-02**|**Evaluating Large Language Models on the GMAT: Implications for the Future of Business Education**|The rapid evolution of artificial intelligence (AI), especially in the domain
of Large Language Models (LLMs) and generative AI, has opened new avenues for
application across various fields, yet its role in business education remains
underexplored. This study introduces the first benchmark to assess the
performance of seven major LLMs, OpenAI's models (GPT-3.5 Turbo, GPT-4, and
GPT-4 Turbo), Google's models (PaLM 2, Gemini 1.0 Pro), and Anthropic's models
(Claude 2 and Claude 2.1), on the GMAT, which is a key exam in the admission
process for graduate business programs. Our analysis shows that most LLMs
outperform human candidates, with GPT-4 Turbo not only outperforming the other
models but also surpassing the average scores of graduate students at top
business schools. Through a case study, this research examines GPT-4 Turbo's
ability to explain answers, evaluate responses, identify errors, tailor
instructions, and generate alternative scenarios. The latest LLM versions,
GPT-4 Turbo, Claude 2.1, and Gemini 1.0 Pro, show marked improvements in
reasoning tasks compared to their predecessors, underscoring their potential
for complex problem-solving. While AI's promise in education, assessment, and
tutoring is clear, challenges remain. Our study not only sheds light on LLMs'
academic potential but also emphasizes the need for careful development and
application of AI in education. As AI technology advances, it is imperative to
establish frameworks and protocols for AI interaction, verify the accuracy of
AI-generated content, ensure worldwide access for diverse learners, and create
an educational environment where AI supports human expertise. This research
sets the stage for further exploration into the responsible use of AI to enrich
educational experiences and improve exam preparation and assessment methods.|Vahid Ashrafimoghari et.al.|[2401.02985v1](http://arxiv.org/abs/2401.02985v1)|null|
|**2023-12-29**|**XAI for In-hospital Mortality Prediction via Multimodal ICU Data**|Predicting in-hospital mortality for intensive care unit (ICU) patients is
key to final clinical outcomes. AI has shown advantaged accuracy but suffers
from the lack of explainability. To address this issue, this paper proposes an
eXplainable Multimodal Mortality Predictor (X-MMP) approaching an efficient,
explainable AI solution for predicting in-hospital mortality via multimodal ICU
data. We employ multimodal learning in our framework, which can receive
heterogeneous inputs from clinical data and make decisions. Furthermore, we
introduce an explainable method, namely Layer-Wise Propagation to Transformer,
as a proper extension of the LRP method to Transformers, producing explanations
over multimodal inputs and revealing the salient features attributed to
prediction. Moreover, the contribution of each modality to clinical outcomes
can be visualized, assisting clinicians in understanding the reasoning behind
decision-making. We construct a multimodal dataset based on MIMIC-III and
MIMIC-III Waveform Database Matched Subset. Comprehensive experiments on
benchmark datasets demonstrate that our proposed framework can achieve
reasonable interpretation with competitive prediction accuracy. In particular,
our framework can be easily transferred to other clinical tasks, which
facilitates the discovery of crucial factors in healthcare research.|Xingqiao Li et.al.|[2312.17624v1](http://arxiv.org/abs/2312.17624v1)|[link](https://github.com/lixingqiao/xai-icu)|
|**2023-12-22**|**Joining Forces for Pathology Diagnostics with AI Assistance: The EMPAIA Initiative**|Over the past decade, artificial intelligence (AI) methods in pathology have
advanced substantially. However, integration into routine clinical practice has
been slow due to numerous challenges, including technical and regulatory
hurdles in translating research results into clinical diagnostic products and
the lack of standardized interfaces. The open and vendor-neutral EMPAIA
initiative addresses these challenges. Here, we provide an overview of EMPAIA's
achievements and lessons learned. EMPAIA integrates various stakeholders of the
pathology AI ecosystem, i.e., pathologists, computer scientists, and industry.
In close collaboration, we developed technical interoperability standards,
recommendations for AI testing and product development, and explainability
methods. We implemented the modular and open-source EMPAIA platform and
successfully integrated 14 AI-based image analysis apps from 8 different
vendors, demonstrating how different apps can use a single standardized
interface. We prioritized requirements and evaluated the use of AI in real
clinical settings with 14 different pathology laboratories in Europe and Asia.
In addition to technical developments, we created a forum for all stakeholders
to share information and experiences on digital pathology and AI. Commercial,
clinical, and academic stakeholders can now adopt EMPAIA's common open-source
interfaces, providing a unique opportunity for large-scale standardization and
streamlining of processes. Further efforts are needed to effectively and
broadly establish AI assistance in routine laboratory use. To this end, a
sustainable infrastructure, the non-profit association EMPAIA International,
has been established to continue standardization and support broad
implementation and advocacy for an AI-assisted digital pathology future.|Norman Zerbe et.al.|[2401.09450v2](http://arxiv.org/abs/2401.09450v2)|null|
|**2023-12-18**|**Robust Stochastic Graph Generator for Counterfactual Explanations**|Counterfactual Explanation (CE) techniques have garnered attention as a means
to provide insights to the users engaging with AI systems. While extensively
researched in domains such as medical imaging and autonomous vehicles, Graph
Counterfactual Explanation (GCE) methods have been comparatively
under-explored. GCEs generate a new graph similar to the original one, with a
different outcome grounded on the underlying predictive model. Among these GCE
techniques, those rooted in generative mechanisms have received relatively
limited investigation despite demonstrating impressive accomplishments in other
domains, such as artistic styles and natural language modelling. The preference
for generative explainers stems from their capacity to generate counterfactual
instances during inference, leveraging autonomously acquired perturbations of
the input graph. Motivated by the rationales above, our study introduces
RSGG-CE, a novel Robust Stochastic Graph Generator for Counterfactual
Explanations able to produce counterfactual examples from the learned latent
space considering a partially ordered generation sequence. Furthermore, we
undertake quantitative and qualitative analyses to compare RSGG-CE's
performance against SoA generative explainers, highlighting its increased
ability to engendering plausible counterfactual candidates.|Mario Alfonso Prado-Romero et.al.|[2312.11747v2](http://arxiv.org/abs/2312.11747v2)|null|
|**2023-12-10**|**Evaluating the Utility of Model Explanations for Model Development**|One of the motivations for explainable AI is to allow humans to make better
and more informed decisions regarding the use and deployment of AI models. But
careful evaluations are needed to assess whether this expectation has been
fulfilled. Current evaluations mainly focus on algorithmic properties of
explanations, and those that involve human subjects often employ subjective
questions to test human's perception of explanation usefulness, without being
grounded in objective metrics and measurements. In this work, we evaluate
whether explanations can improve human decision-making in practical scenarios
of machine learning model development. We conduct a mixed-methods user study
involving image data to evaluate saliency maps generated by SmoothGrad,
GradCAM, and an oracle explanation on two tasks: model selection and
counterfactual simulation. To our surprise, we did not find evidence of
significant improvement on these tasks when users were provided with any of the
saliency maps, even the synthetic oracle explanation designed to be simple to
understand and highly indicative of the answer. Nonetheless, explanations did
help users more accurately describe the models. These findings suggest caution
regarding the usefulness and potential for misunderstanding in saliency-based
explanations.|Shawn Im et.al.|[2312.06032v1](http://arxiv.org/abs/2312.06032v1)|null|
|**2023-12-05**|**Building Trustworthy NeuroSymbolic AI Systems: Consistency, Reliability, Explainability, and Safety**|Explainability and Safety engender Trust. These require a model to exhibit
consistency and reliability. To achieve these, it is necessary to use and
analyze data and knowledge with statistical and symbolic AI methods relevant to
the AI application - neither alone will do. Consequently, we argue and seek to
demonstrate that the NeuroSymbolic AI approach is better suited for making AI a
trusted AI system. We present the CREST framework that shows how Consistency,
Reliability, user-level Explainability, and Safety are built on NeuroSymbolic
methods that use data and knowledge to support requirements for critical
applications such as health and well-being. This article focuses on Large
Language Models (LLMs) as the chosen AI system within the CREST framework. LLMs
have garnered substantial attention from researchers due to their versatility
in handling a broad array of natural language processing (NLP) scenarios. For
example, ChatGPT and Google's MedPaLM have emerged as highly promising
platforms for providing information in general and health-related queries,
respectively. Nevertheless, these models remain black boxes despite
incorporating human feedback and instruction-guided tuning. For instance,
ChatGPT can generate unsafe responses despite instituting safety guardrails.
CREST presents a plausible approach harnessing procedural and graph-based
knowledge within a NeuroSymbolic framework to shed light on the challenges
associated with LLMs.|Manas Gaur et.al.|[2312.06798v1](http://arxiv.org/abs/2312.06798v1)|null|
|**2023-11-28**|**Deployment of a Robust and Explainable Mortality Prediction Model: The COVID-19 Pandemic and Beyond**|This study investigated the performance, explainability, and robustness of
deployed artificial intelligence (AI) models in predicting mortality during the
COVID-19 pandemic and beyond. The first study of its kind, we found that
Bayesian Neural Networks (BNNs) and intelligent training techniques allowed our
models to maintain performance amidst significant data shifts. Our results
emphasize the importance of developing robust AI models capable of matching or
surpassing clinician predictions, even under challenging conditions. Our
exploration of model explainability revealed that stochastic models generate
more diverse and personalized explanations thereby highlighting the need for AI
models that provide detailed and individualized insights in real-world clinical
settings. Furthermore, we underscored the importance of quantifying uncertainty
in AI models which enables clinicians to make better-informed decisions based
on reliable predictions. Our study advocates for prioritizing implementation
science in AI research for healthcare and ensuring that AI solutions are
practical, beneficial, and sustainable in real-world clinical environments. By
addressing unique challenges and complexities in healthcare settings,
researchers can develop AI models that effectively improve clinical practice
and patient outcomes.|Jacob R. Epifano et.al.|[2311.17133v1](http://arxiv.org/abs/2311.17133v1)|null|
|**2023-11-27**|**Variational Autoencoders for Feature Exploration and Malignancy Prediction of Lung Lesions**|Lung cancer is responsible for 21% of cancer deaths in the UK and five-year
survival rates are heavily influenced by the stage the cancer was identified
at. Recent studies have demonstrated the capability of AI methods for accurate
and early diagnosis of lung cancer from routine scans. However, this evidence
has not translated into clinical practice with one barrier being a lack of
interpretable models. This study investigates the application Variational
Autoencoders (VAEs), a type of generative AI model, to lung cancer lesions.
Proposed models were trained on lesions extracted from 3D CT scans in the
LIDC-IDRI public dataset. Latent vector representations of 2D slices produced
by the VAEs were explored through clustering to justify their quality and used
in an MLP classifier model for lung cancer diagnosis, the best model achieved
state-of-the-art metrics of AUC 0.98 and 93.1% accuracy. Cluster analysis shows
the VAE latent space separates the dataset of malignant and benign lesions
based on meaningful feature components including tumour size, shape, patient
and malignancy class. We also include a comparative analysis of the standard
Gaussian VAE (GVAE) and the more recent Dirichlet VAE (DirVAE), which replaces
the prior with a Dirichlet distribution to encourage a more explainable latent
space with disentangled feature representation. Finally, we demonstrate the
potential for latent space traversals corresponding to clinically meaningful
feature changes.|Benjamin Keel et.al.|[2311.15719v1](http://arxiv.org/abs/2311.15719v1)|[link](https://github.com/benkeel/vae_lung_lesion_bmvc)|
|**2023-11-24**|**MRxaI: Black-Box Explainability for Image Classifiers in a Medical Setting**|Existing tools for explaining the output of image classifiers can be divided
into white-box, which rely on access to the model internals, and black-box,
agnostic to the model. As the usage of AI in the medical domain grows, so too
does the usage of explainability tools. Existing work on medical image
explanations focuses on white-box tools, such as gradcam. However, there are
clear advantages to switching to a black-box tool, including the ability to use
it with any classifier and the wide selection of black-box tools available. On
standard images, black-box tools are as precise as white-box. In this paper we
compare the performance of several black-box methods against gradcam on a brain
cancer MRI dataset. We demonstrate that most black-box tools are not suitable
for explaining medical image classifications and present a detailed analysis of
the reasons for their shortcomings. We also show that one black-box tool, a
causal explainability-based rex, performs as well as \gradcam.|Nathan Blake et.al.|[2311.14471v1](http://arxiv.org/abs/2311.14471v1)|null|
|**2023-11-21**|**Moderating Model Marketplaces: Platform Governance Puzzles for AI Intermediaries**|The AI development community is increasingly making use of hosting
intermediaries such as Hugging Face provide easy access to user-uploaded models
and training data. These model marketplaces lower technical deployment barriers
for hundreds of thousands of users, yet can be used in numerous potentially
harmful and illegal ways. In this article, we explain ways in which AI systems,
which can both `contain' content and be open-ended tools, present one of the
trickiest platform governance challenges seen to date. We provide case studies
of several incidents across three illustrative platforms -- Hugging Face,
GitHub and Civitai -- to examine how model marketplaces moderate models.
Building on this analysis, we outline important (and yet nevertheless limited)
practices that industry has been developing to respond to moderation demands:
licensing, access and use restrictions, automated content moderation, and open
policy development. While the policy challenge at hand is a considerable one,
we conclude with some ideas as to how platforms could better mobilize resources
to act as a careful, fair, and proportionate regulatory access point.|Robert Gorwa et.al.|[2311.12573v2](http://arxiv.org/abs/2311.12573v2)|null|
|**2023-11-20**|**Ovarian Cancer Data Analysis using Deep Learning: A Systematic Review from the Perspectives of Key Features of Data Analysis and AI Assurance**|Background and objectives: By extracting this information, Machine or Deep
Learning (ML/DL)-based autonomous data analysis tools can assist clinicians and
cancer researchers in discovering patterns and relationships from complex data
sets. Many DL-based analyses on ovarian cancer (OC) data have recently been
published. These analyses are highly diverse in various aspects of cancer
(e.g., subdomain(s) and cancer type they address) and data analysis features.
However, a comprehensive understanding of these analyses in terms of these
features and AI assurance (AIA) is currently lacking. This systematic review
aims to fill this gap by examining the existing literature and identifying
important aspects of OC data analysis using DL, explicitly focusing on the key
features and AI assurance perspectives. Methods: The PRISMA framework was used
to conduct comprehensive searches in three journal databases. Only studies
published between 2015 and 2023 in peer-reviewed journals were included in the
analysis. Results: In the review, a total of 96 DL-driven analyses were
examined. The findings reveal several important insights regarding DL-driven
ovarian cancer data analysis: - Most studies 71% (68 out of 96) focused on
detection and diagnosis, while no study addressed the prediction and prevention
of OC. - The analyses were predominantly based on samples from a non-diverse
population (75% (72/96 studies)), limited to a geographic location or country.
- Only a small proportion of studies (only 33% (32/96)) performed integrated
analyses, most of which used homogeneous data (clinical or omics). - Notably, a
mere 8.3% (8/96) of the studies validated their models using external and
diverse data sets, highlighting the need for enhanced model validation, and -
The inclusion of AIA in cancer data analysis is in a very early stage; only
2.1% (2/96) explicitly addressed AIA through explainability.|Muta Tah Hira et.al.|[2311.11932v1](http://arxiv.org/abs/2311.11932v1)|null|
|**2023-11-18**|**Representing visual classification as a linear combination of words**|Explainability is a longstanding challenge in deep learning, especially in
high-stakes domains like healthcare. Common explainability methods highlight
image regions that drive an AI model's decision. Humans, however, heavily rely
on language to convey explanations of not only "where" but "what".
Additionally, most explainability approaches focus on explaining individual AI
predictions, rather than describing the features used by an AI model in
general. The latter would be especially useful for model and dataset auditing,
and potentially even knowledge generation as AI is increasingly being used in
novel tasks. Here, we present an explainability strategy that uses a
vision-language model to identify language-based descriptors of a visual
classification task. By leveraging a pre-trained joint embedding space between
images and text, our approach estimates a new classification task as a linear
combination of words, resulting in a weight for each word that indicates its
alignment with the vision-based classifier. We assess our approach using two
medical imaging classification tasks, where we find that the resulting
descriptors largely align with clinical knowledge despite a lack of
domain-specific language training. However, our approach also identifies the
potential for 'shortcut connections' in the public datasets used. Towards a
functional measure of explainability, we perform a pilot reader study where we
find that the AI-identified words can enable non-expert humans to perform a
specialized medical task at a non-trivial level. Altogether, our results
emphasize the potential of using multimodal foundational models to deliver
intuitive, language-based explanations of visual tasks.|Shobhit Agarwal et.al.|[2311.10933v1](http://arxiv.org/abs/2311.10933v1)|[link](https://github.com/lotterlab/task_word_explainability)|
|**2023-11-03**|**Towards objective and systematic evaluation of bias in medical imaging AI**|Artificial intelligence (AI) models trained using medical images for clinical
tasks often exhibit bias in the form of disparities in performance between
subgroups. Since not all sources of biases in real-world medical imaging data
are easily identifiable, it is challenging to comprehensively assess how those
biases are encoded in models, and how capable bias mitigation methods are at
ameliorating performance disparities. In this article, we introduce a novel
analysis framework for systematically and objectively investigating the impact
of biases in medical images on AI models. We developed and tested this
framework for conducting controlled in silico trials to assess bias in medical
imaging AI using a tool for generating synthetic magnetic resonance images with
known disease effects and sources of bias. The feasibility is showcased by
using three counterfactual bias scenarios to measure the impact of simulated
bias effects on a convolutional neural network (CNN) classifier and the
efficacy of three bias mitigation strategies. The analysis revealed that the
simulated biases resulted in expected subgroup performance disparities when the
CNN was trained on the synthetic datasets. Moreover, reweighing was identified
as the most successful bias mitigation strategy for this setup, and we
demonstrated how explainable AI methods can aid in investigating the
manifestation of bias in the model using this framework. Developing fair AI
models is a considerable challenge given that many and often unknown sources of
biases can be present in medical imaging datasets. In this work, we present a
novel methodology to objectively study the impact of biases and mitigation
strategies on deep learning pipelines, which can support the development of
clinical AI that is robust and responsible.|Emma A. M. Stanley et.al.|[2311.02115v1](http://arxiv.org/abs/2311.02115v1)|[link](https://github.com/estanley16/simba)|
|**2023-10-29**|**Predicting recovery following stroke: deep learning, multimodal data and feature selection using explainable AI**|Machine learning offers great potential for automated prediction of
post-stroke symptoms and their response to rehabilitation. Major challenges for
this endeavour include the very high dimensionality of neuroimaging data, the
relatively small size of the datasets available for learning, and how to
effectively combine neuroimaging and tabular data (e.g. demographic information
and clinical characteristics). This paper evaluates several solutions based on
two strategies. The first is to use 2D images that summarise MRI scans. The
second is to select key features that improve classification accuracy.
Additionally, we introduce the novel approach of training a convolutional
neural network (CNN) on images that combine regions-of-interest extracted from
MRIs, with symbolic representations of tabular data. We evaluate a series of
CNN architectures (both 2D and a 3D) that are trained on different
representations of MRI and tabular data, to predict whether a composite measure
of post-stroke spoken picture description ability is in the aphasic or
non-aphasic range. MRI and tabular data were acquired from 758 English speaking
stroke survivors who participated in the PLORAS study. The classification
accuracy for a baseline logistic regression was 0.678 for lesion size alone,
rising to 0.757 and 0.813 when initial symptom severity and recovery time were
successively added. The highest classification accuracy 0.854 was observed when
8 regions-of-interest was extracted from each MRI scan and combined with lesion
size, initial severity and recovery time in a 2D Residual Neural Network.Our
findings demonstrate how imaging and tabular data can be combined for high
post-stroke classification accuracy, even when the dataset is small in machine
learning terms. We conclude by proposing how the current models could be
improved to achieve even higher levels of accuracy using images from hospital
scanners.|Adam White et.al.|[2310.19174v1](http://arxiv.org/abs/2310.19174v1)|null|
|**2023-10-03**|**Trainable Noise Model as an XAI evaluation method: application on Sobol for remote sensing image segmentation**|eXplainable Artificial Intelligence (XAI) has emerged as an essential
requirement when dealing with mission-critical applications, ensuring
transparency and interpretability of the employed black box AI models. The
significance of XAI spans various domains, from healthcare to finance, where
understanding the decision-making process of deep learning algorithms is
essential. Most AI-based computer vision models are often black boxes; hence,
providing explainability of deep neural networks in image processing is crucial
for their wide adoption and deployment in medical image analysis, autonomous
driving, and remote sensing applications. Recently, several XAI methods for
image classification tasks have been introduced. On the contrary, image
segmentation has received comparatively less attention in the context of
explainability, although it is a fundamental task in computer vision
applications, especially in remote sensing. Only some research proposes
gradient-based XAI algorithms for image segmentation. This paper adapts the
recent gradient-free Sobol XAI method for semantic segmentation. To measure the
performance of the Sobol method for segmentation, we propose a quantitative XAI
evaluation method based on a learnable noise model. The main objective of this
model is to induce noise on the explanation maps, where higher induced noise
signifies low accuracy and vice versa. A benchmark analysis is conducted to
evaluate and compare performance of three XAI methods, including Seg-Grad-CAM,
Seg-Grad-CAM++ and Seg-Sobol using the proposed noise-based evaluation
technique. This constitutes the first attempt to run and evaluate XAI methods
using high-resolution satellite images.|Hossein Shreim et.al.|[2310.01828v2](http://arxiv.org/abs/2310.01828v2)|[link](https://github.com/geoaigroup/geoai-ecrs2023)|
|**2023-09-26**|**Creating Trustworthy LLMs: Dealing with Hallucinations in Healthcare AI**|Large language models have proliferated across multiple domains in as short
period of time. There is however hesitation in the medical and healthcare
domain towards their adoption because of issues like factuality, coherence, and
hallucinations. Give the high stakes nature of healthcare, many researchers
have even cautioned against its usage until these issues are resolved. The key
to the implementation and deployment of LLMs in healthcare is to make these
models trustworthy, transparent (as much possible) and explainable. In this
paper we describe the key elements in creating reliable, trustworthy, and
unbiased models as a necessary condition for their adoption in healthcare.
Specifically we focus on the quantification, validation, and mitigation of
hallucinations in the context in healthcare. Lastly, we discuss how the future
of LLMs in healthcare may look like.|Muhammad Aurangzeb Ahmad et.al.|[2311.01463v1](http://arxiv.org/abs/2311.01463v1)|null|
|**2023-09-20**|**When to Trust AI: Advances and Challenges for Certification of Neural Networks**|Artificial intelligence (AI) has been advancing at a fast pace and it is now
poised for deployment in a wide range of applications, such as autonomous
systems, medical diagnosis and natural language processing. Early adoption of
AI technology for real-world applications has not been without problems,
particularly for neural networks, which may be unstable and susceptible to
adversarial examples. In the longer term, appropriate safety assurance
techniques need to be developed to reduce potential harm due to avoidable
system failures and ensure trustworthiness. Focusing on certification and
explainability, this paper provides an overview of techniques that have been
developed to ensure safety of AI decisions and discusses future challenges.|Marta Kwiatkowska et.al.|[2309.11196v1](http://arxiv.org/abs/2309.11196v1)|null|
|**2023-09-19**|**Functional requirements to mitigate the Risk of Harm to Patients from Artificial Intelligence in Healthcare**|The Directorate General for Parliamentary Research Services of the European
Parliament has prepared a report to the Members of the European Parliament
where they enumerate seven main risks of Artificial Intelligence (AI) in
medicine and healthcare: patient harm due to AI errors, misuse of medical AI
tools, bias in AI and the perpetuation of existing inequities, lack of
transparency, privacy and security issues, gaps in accountability, and
obstacles in implementation.
  In this study, we propose fourteen functional requirements that AI systems
may implement to reduce the risks associated with their medical purpose: AI
passport, User management, Regulation check, Academic use only disclaimer, data
quality assessment, Clinicians double check, Continuous performance evaluation,
Audit trail, Continuous usability test, Review of retrospective/simulated
cases, Bias check, eXplainable AI, Encryption and use of field-tested
libraries, and Semantic interoperability.
  Our intention here is to provide specific high-level specifications of
technical solutions to ensure continuous good performance and use of AI systems
to benefit patients in compliance with the future EU regulatory framework.|Juan M. García-Gómez et.al.|[2309.10424v1](http://arxiv.org/abs/2309.10424v1)|null|
|**2023-09-19**|**QXAI: Explainable AI Framework for Quantitative Analysis in Patient Monitoring Systems**|Artificial Intelligence techniques can be used to classify a patient's
physical activities and predict vital signs for remote patient monitoring.
Regression analysis based on non-linear models like deep learning models has
limited explainability due to its black-box nature. This can require
decision-makers to make blind leaps of faith based on non-linear model results,
especially in healthcare applications. In non-invasive monitoring, patient data
from tracking sensors and their predisposing clinical attributes act as input
features for predicting future vital signs. Explaining the contributions of
various features to the overall output of the monitoring application is
critical for a clinician's decision-making. In this study, an Explainable AI
for Quantitative analysis (QXAI) framework is proposed with post-hoc model
explainability and intrinsic explainability for regression and classification
tasks in a supervised learning approach. This was achieved by utilizing the
Shapley values concept and incorporating attention mechanisms in deep learning
models. We adopted the artificial neural networks (ANN) and attention-based
Bidirectional LSTM (BiLSTM) models for the prediction of heart rate and
classification of physical activities based on sensor data. The deep learning
models achieved state-of-the-art results in both prediction and classification
tasks. Global explanation and local explanation were conducted on input data to
understand the feature contribution of various patient data. The proposed QXAI
framework was evaluated using PPG-DaLiA data to predict heart rate and mobile
health (MHEALTH) data to classify physical activities based on sensor data.
Monte Carlo approximation was applied to the framework to overcome the time
complexity and high computation power requirements required for Shapley value
calculations.|Thanveer Shaik et.al.|[2309.10293v3](http://arxiv.org/abs/2309.10293v3)|null|
|**2023-09-18**|**Evaluation of Human-Understandability of Global Model Explanations using Decision Tree**|In explainable artificial intelligence (XAI) research, the predominant focus
has been on interpreting models for experts and practitioners. Model agnostic
and local explanation approaches are deemed interpretable and sufficient in
many applications. However, in domains like healthcare, where end users are
patients without AI or domain expertise, there is an urgent need for model
explanations that are more comprehensible and instil trust in the model's
operations. We hypothesise that generating model explanations that are
narrative, patient-specific and global(holistic of the model) would enable
better understandability and enable decision-making. We test this using a
decision tree model to generate both local and global explanations for patients
identified as having a high risk of coronary heart disease. These explanations
are presented to non-expert users. We find a strong individual preference for a
specific type of explanation. The majority of participants prefer global
explanations, while a smaller group prefers local explanations. A task based
evaluation of mental models of these participants provide valuable feedback to
enhance narrative global explanations. This, in turn, guides the design of
health informatics systems that are both trustworthy and actionable.|Adarsa Sivaprasad et.al.|[2309.09917v1](http://arxiv.org/abs/2309.09917v1)|null|
|**2023-09-02**|**An explainable three dimension framework to uncover learning patterns: A unified look in variable sulci recognition**|Explainable AI is crucial in medical imaging. In the challenging field of
neuroscience, visual topics present a high level of complexity, particularly
within three-dimensional space. The application of neuroscience, which involves
identifying brain sulcal features from MRI, faces significant hurdles due to
varying annotation protocols among experts and the intricate three-dimension
functionality of the brain. Consequently, traditional explainability approaches
fall short in effectively validating and evaluating these networks. To address
this, we first present a mathematical formulation delineating various
categories of explanation needs across diverse computer vision tasks,
categorized into self-explanatory, semi-explanatory, non-explanatory, and
new-pattern learning applications based on the reliability of the validation
protocol. With respect to this mathematical formulation, we propose a 3D
explainability framework aimed at validating the outputs of deep learning
networks in detecting the paracingulate sulcus an essential brain anatomical
feature. The framework integrates local 3D explanations, global explanations
through dimensionality reduction, concatenated global explanations, and
statistical shape features, unveiling new insights into pattern learning. We
trained and tested two advanced 3D deep learning networks on the challenging
TOP-OSLO dataset, significantly improving sulcus detection accuracy,
particularly on the left hemisphere. During evaluation with diverse annotation
protocols for this dataset, we highlighted the crucial role of an unbiased
annotation process in achieving precise predictions and effective pattern
learning within our proposed 3D framework. The proposed framework not only
annotates the variable sulcus but also uncovers hidden AI knowledge, promising
to advance our understanding of brain anatomy and function.|Michail Mamalakis et.al.|[2309.00903v2](http://arxiv.org/abs/2309.00903v2)|[link](https://github.com/ece7048/3dsulci)|
|**2023-08-28**|**Leveraging A Medical Knowledge Graph into Large Language Models for Diagnosis Prediction**|Electronic Health Records (EHRs) and routine documentation practices play a
vital role in patients' daily care, providing a holistic record of health,
diagnoses, and treatment. However, complex and verbose EHR narratives overload
healthcare providers, risking diagnostic inaccuracies. While Large Language
Models (LLMs) have showcased their potential in diverse language tasks, their
application in the healthcare arena needs to ensure the minimization of
diagnostic errors and the prevention of patient harm. In this paper, we outline
an innovative approach for augmenting the proficiency of LLMs in the realm of
automated diagnosis generation, achieved through the incorporation of a medical
knowledge graph (KG) and a novel graph model: Dr.Knows, inspired by the
clinical diagnostic reasoning process. We derive the KG from the National
Library of Medicine's Unified Medical Language System (UMLS), a robust
repository of biomedical knowledge. Our method negates the need for
pre-training and instead leverages the KG as an auxiliary instrument aiding in
the interpretation and summarization of complex medical concepts. Using
real-world hospital datasets, our experimental results demonstrate that the
proposed approach of combining LLMs with KG has the potential to improve the
accuracy of automated diagnosis generation. More importantly, our approach
offers an explainable diagnostic pathway, edging us closer to the realization
of AI-augmented diagnostic decision support systems.|Yanjun Gao et.al.|[2308.14321v1](http://arxiv.org/abs/2308.14321v1)|null|
|**2023-08-18**|**Deciphering knee osteoarthritis diagnostic features with explainable artificial intelligence: A systematic review**|Existing artificial intelligence (AI) models for diagnosing knee
osteoarthritis (OA) have faced criticism for their lack of transparency and
interpretability, despite achieving medical-expert-like performance. This
opacity makes them challenging to trust in clinical practice. Recently,
explainable artificial intelligence (XAI) has emerged as a specialized
technique that can provide confidence in the model's prediction by revealing
how the prediction is derived, thus promoting the use of AI systems in
healthcare. This paper presents the first survey of XAI techniques used for
knee OA diagnosis. The XAI techniques are discussed from two perspectives: data
interpretability and model interpretability. The aim of this paper is to
provide valuable insights into XAI's potential towards a more reliable knee OA
diagnosis approach and encourage its adoption in clinical practice.|Yun Xin Teoh et.al.|[2308.09380v1](http://arxiv.org/abs/2308.09380v1)|null|
|**2023-08-16**|**Explainable AI for clinical risk prediction: a survey of concepts, methods, and modalities**|Recent advancements in AI applications to healthcare have shown incredible
promise in surpassing human performance in diagnosis and disease prognosis.
With the increasing complexity of AI models, however, concerns regarding their
opacity, potential biases, and the need for interpretability. To ensure trust
and reliability in AI systems, especially in clinical risk prediction models,
explainability becomes crucial. Explainability is usually referred to as an AI
system's ability to provide a robust interpretation of its decision-making
logic or the decisions themselves to human stakeholders. In clinical risk
prediction, other aspects of explainability like fairness, bias, trust, and
transparency also represent important concepts beyond just interpretability. In
this review, we address the relationship between these concepts as they are
often used together or interchangeably. This review also discusses recent
progress in developing explainable models for clinical risk prediction,
highlighting the importance of quantitative and clinical evaluation and
validation across multiple common modalities in clinical practice. It
emphasizes the need for external validation and the combination of diverse
interpretability methods to enhance trust and fairness. Adopting rigorous
testing, such as using synthetic datasets with known generative factors, can
further improve the reliability of explainability methods. Open access and
code-sharing resources are essential for transparency and reproducibility,
enabling the growth and trustworthiness of explainable research. While
challenges exist, an end-to-end approach to explainability in clinical risk
prediction, incorporating stakeholders from clinicians to developers, is
essential for success.|Munib Mesinovic et.al.|[2308.08407v1](http://arxiv.org/abs/2308.08407v1)|null|
|**2023-08-11**|**FUTURE-AI: International consensus guideline for trustworthy and deployable artificial intelligence in healthcare**|Despite major advances in artificial intelligence (AI) for medicine and
healthcare, the deployment and adoption of AI technologies remain limited in
real-world clinical practice. In recent years, concerns have been raised about
the technical, clinical, ethical and legal risks associated with medical AI. To
increase real world adoption, it is essential that medical AI tools are trusted
and accepted by patients, clinicians, health organisations and authorities.
This work describes the FUTURE-AI guideline as the first international
consensus framework for guiding the development and deployment of trustworthy
AI tools in healthcare. The FUTURE-AI consortium was founded in 2021 and
currently comprises 118 inter-disciplinary experts from 51 countries
representing all continents, including AI scientists, clinicians, ethicists,
and social scientists. Over a two-year period, the consortium defined guiding
principles and best practices for trustworthy AI through an iterative process
comprising an in-depth literature review, a modified Delphi survey, and online
consensus meetings. The FUTURE-AI framework was established based on 6 guiding
principles for trustworthy AI in healthcare, i.e. Fairness, Universality,
Traceability, Usability, Robustness and Explainability. Through consensus, a
set of 28 best practices were defined, addressing technical, clinical, legal
and socio-ethical dimensions. The recommendations cover the entire lifecycle of
medical AI, from design, development and validation to regulation, deployment,
and monitoring. FUTURE-AI is a risk-informed, assumption-free guideline which
provides a structured approach for constructing medical AI tools that will be
trusted, deployed and adopted in real-world practice. Researchers are
encouraged to take the recommendations into account in proof-of-concept stages
to facilitate future translation towards clinical practice of medical AI.|Karim Lekadir et.al.|[2309.12325v1](http://arxiv.org/abs/2309.12325v1)|null|
|**2023-08-10**|**Explainable AI applications in the Medical Domain: a systematic review**|Artificial Intelligence in Medicine has made significant progress with
emerging applications in medical imaging, patient care, and other areas. While
these applications have proven successful in retrospective studies, very few of
them were applied in practice.The field of Medical AI faces various challenges,
in terms of building user trust, complying with regulations, using data
ethically.Explainable AI (XAI) aims to enable humans understand AI and trust
its results. This paper presents a literature review on the recent developments
of XAI solutions for medical decision support, based on a representative sample
of 198 articles published in recent years. The systematic synthesis of the
relevant articles resulted in several findings. (1) model-agnostic XAI
techniques were mostly employed in these solutions, (2) deep learning models
are utilized more than other types of machine learning models, (3)
explainability was applied to promote trust, but very few works reported the
physicians participation in the loop, (4) visual and interactive user interface
is more useful in understanding the explanation and the recommendation of the
system. More research is needed in collaboration between medical and AI
experts, that could guide the development of suitable frameworks for the
design, implementation, and evaluation of XAI solutions in medicine.|Nicoletta Prentzas et.al.|[2308.05411v1](http://arxiv.org/abs/2308.05411v1)|null|
|**2023-08-01**|**Exploring the Role of Explainability in AI-Assisted Embryo Selection**|In Vitro Fertilization is among the most widespread treatments for
infertility. One of its main challenges is the evaluation and selection of
embryo for implantation, a process with large inter- and intra-clinician
variability. Deep learning based methods are gaining attention, but their
opaque nature compromises their acceptance in the clinical context, where
transparency in the decision making is key. In this paper we analyze the
current work in the explainability of AI-assisted embryo analysis models,
identifying the limitations. We also discuss how these models could be
integrated in the clinical context as decision support systems, considering the
needs of clinicians and patients. Finally, we propose guidelines for the sake
of increasing interpretability and trustworthiness, pushing this technology
forward towards established clinical practice.|Lucia Urcelay et.al.|[2308.02534v1](http://arxiv.org/abs/2308.02534v1)|null|
|**2023-07-26**|**A New Perspective on Evaluation Methods for Explainable Artificial Intelligence (XAI)**|Within the field of Requirements Engineering (RE), the increasing
significance of Explainable Artificial Intelligence (XAI) in aligning
AI-supported systems with user needs, societal expectations, and regulatory
standards has garnered recognition. In general, explainability has emerged as
an important non-functional requirement that impacts system quality. However,
the supposed trade-off between explainability and performance challenges the
presumed positive influence of explainability. If meeting the requirement of
explainability entails a reduction in system performance, then careful
consideration must be given to which of these quality aspects takes precedence
and how to compromise between them. In this paper, we critically examine the
alleged trade-off. We argue that it is best approached in a nuanced way that
incorporates resource availability, domain characteristics, and considerations
of risk. By providing a foundation for future research and best practices, this
work aims to advance the field of RE for AI.|Timo Speith et.al.|[2307.14246v1](http://arxiv.org/abs/2307.14246v1)|null|
|**2023-07-26**|**Revisiting the Performance-Explainability Trade-Off in Explainable Artificial Intelligence (XAI)**|Within the field of Requirements Engineering (RE), the increasing
significance of Explainable Artificial Intelligence (XAI) in aligning
AI-supported systems with user needs, societal expectations, and regulatory
standards has garnered recognition. In general, explainability has emerged as
an important non-functional requirement that impacts system quality. However,
the supposed trade-off between explainability and performance challenges the
presumed positive influence of explainability. If meeting the requirement of
explainability entails a reduction in system performance, then careful
consideration must be given to which of these quality aspects takes precedence
and how to compromise between them. In this paper, we critically examine the
alleged trade-off. We argue that it is best approached in a nuanced way that
incorporates resource availability, domain characteristics, and considerations
of risk. By providing a foundation for future research and best practices, this
work aims to advance the field of RE for AI.|Barnaby Crook et.al.|[2307.14239v1](http://arxiv.org/abs/2307.14239v1)|null|
|**2023-07-26**|**Acceptable risks in Europe's proposed AI Act: Reasonableness and other principles for deciding how much risk management is enough**|This paper critically evaluates the European Commission's proposed AI Act's
approach to risk management and risk acceptability for high-risk AI systems
that pose risks to fundamental rights and safety. The Act aims to promote
"trustworthy" AI with a proportionate regulatory burden. Its provisions on risk
acceptability require residual risks from high-risk systems to be reduced or
eliminated "as far as possible", having regard to the "state of the art". This
criterion, especially if interpreted narrowly, is unworkable and promotes
neither proportionate regulatory burden, nor trustworthiness. By contrast the
Parliament's most recent draft amendments to the risk management provisions
introduce "reasonableness", cost-benefit analysis, and are more transparent
about the value-laden and contextual nature of risk acceptability judgements.
This paper argues that the Parliament's approach is more workable, and better
balances the goals of proportionality and trustworthiness. It explains what
reasonableness in risk acceptability judgments would entail, drawing on
principles from negligence law and European medical devices regulation. And it
contends that the approach to risk acceptability judgments need a firm
foundation of civic legitimacy: including detailed guidance or involvement from
regulators, and meaningful input from affected stakeholders.|Henry Fraser et.al.|[2308.02047v1](http://arxiv.org/abs/2308.02047v1)|null|
|**2023-07-21**|**eXplainable Artificial Intelligence (XAI) in aging clock models**|eXplainable Artificial Intelligence (XAI) is a rapidly progressing field of
machine learning, aiming to unravel the predictions of complex models. XAI is
especially required in sensitive applications, e.g. in health care, when
diagnosis, recommendations and treatment choices might rely on the decisions
made by artificial intelligence systems. AI approaches have become widely used
in aging research as well, in particular, in developing biological clock models
and identifying biomarkers of aging and age-related diseases. However, the
potential of XAI here awaits to be fully appreciated. We discuss the
application of XAI for developing the "aging clocks" and present a
comprehensive analysis of the literature categorized by the focus on particular
physiological systems.|Alena Kalyakulina et.al.|[2307.13704v3](http://arxiv.org/abs/2307.13704v3)|null|
|**2023-07-19**|**Interpreting and Correcting Medical Image Classification with PIP-Net**|Part-prototype models are explainable-by-design image classifiers, and a
promising alternative to black box AI. This paper explores the applicability
and potential of interpretable machine learning, in particular PIP-Net, for
automated diagnosis support on real-world medical imaging data. PIP-Net learns
human-understandable prototypical image parts and we evaluate its accuracy and
interpretability for fracture detection and skin cancer diagnosis. We find that
PIP-Net's decision making process is in line with medical classification
standards, while only provided with image-level class labels. Because of
PIP-Net's unsupervised pretraining of prototypes, data quality problems such as
undesired text in an X-ray or labelling errors can be easily identified.
Additionally, we are the first to show that humans can manually correct the
reasoning of PIP-Net by directly disabling undesired prototypes. We conclude
that part-prototype models are promising for medical applications due to their
interpretability and potential for advanced model debugging.|Meike Nauta et.al.|[2307.10404v2](http://arxiv.org/abs/2307.10404v2)|[link](https://github.com/m-nauta/pipnet)|
|**2023-07-15**|**Explaining and visualizing black-box models through counterfactual paths**|Explainable AI (XAI) is an increasingly important area of machine learning
research, which aims to make black-box models transparent and interpretable. In
this paper, we propose a novel approach to XAI that uses the so-called
counterfactual paths generated by conditional permutations of features. The
algorithm measures feature importance by identifying sequential permutations of
features that most influence changes in model predictions. It is particularly
suitable for generating explanations based on counterfactual paths in knowledge
graphs incorporating domain knowledge. Counterfactual paths introduce an
additional graph dimension to current XAI methods in both explaining and
visualizing black-box models. Experiments with synthetic and medical data
demonstrate the practical applicability of our approach.|Bastian Pfeifer et.al.|[2307.07764v3](http://arxiv.org/abs/2307.07764v3)|[link](https://github.com/pievos101/cpath)|
|**2023-07-05**|**Beyond Known Reality: Exploiting Counterfactual Explanations for Medical Research**|The field of explainability in artificial intelligence (AI) has witnessed a
growing number of studies and increasing scholarly interest. However, the lack
of human-friendly and individual interpretations in explaining the outcomes of
machine learning algorithms has significantly hindered the acceptance of these
methods by clinicians in their research and clinical practice. To address this
issue, our study uses counterfactual explanations to explore the applicability
of "what if?" scenarios in medical research. Our aim is to expand our
understanding of magnetic resonance imaging (MRI) features used for diagnosing
pediatric posterior fossa brain tumors beyond existing boundaries. In our case
study, the proposed concept provides a novel way to examine alternative
decision-making scenarios that offer personalized and context-specific
insights, enabling the validation of predictions and clarification of
variations under diverse circumstances. Additionally, we explore the potential
use of counterfactuals for data augmentation and evaluate their feasibility as
an alternative approach in our medical research case. The results demonstrate
the promising potential of using counterfactual explanations to enhance
acceptance of AI-driven methods in clinical research.|Toygar Tanyel et.al.|[2307.02131v5](http://arxiv.org/abs/2307.02131v5)|[link](https://github.com/toygarr/counterfactual-explanations-for-medical-research)|
|**2023-06-30**|**AI and Non AI Assessments for Dementia**|Current progress in the artificial intelligence domain has led to the
development of various types of AI-powered dementia assessments, which can be
employed to identify patients at the early stage of dementia. It can
revolutionize the dementia care settings. It is essential that the medical
community be aware of various AI assessments and choose them considering their
degrees of validity, efficiency, practicality, reliability, and accuracy
concerning the early identification of patients with dementia (PwD). On the
other hand, AI developers should be informed about various non-AI assessments
as well as recently developed AI assessments. Thus, this paper, which can be
readable by both clinicians and AI engineers, fills the gap in the literature
in explaining the existing solutions for the recognition of dementia to
clinicians, as well as the techniques used and the most widespread dementia
datasets to AI engineers. It follows a review of papers on AI and non-AI
assessments for dementia to provide valuable information about various dementia
assessments for both the AI and medical communities. The discussion and
conclusion highlight the most prominent research directions and the maturity of
existing solutions.|Mahboobeh Parsapoor et.al.|[2307.01210v1](http://arxiv.org/abs/2307.01210v1)|null|
|**2023-06-12**|**Active Globally Explainable Learning for Medical Images via Class Association Embedding and Cyclic Adversarial Generation**|Explainability poses a major challenge to artificial intelligence (AI)
techniques. Current studies on explainable AI (XAI) lack the efficiency of
extracting global knowledge about the learning task, thus suffer deficiencies
such as imprecise saliency, context-aware absence and vague meaning. In this
paper, we propose the class association embedding (CAE) approach to address
these issues. We employ an encoder-decoder architecture to embed sample
features and separate them into class-related and individual-related style
vectors simultaneously. Recombining the individual-style code of a given sample
with the class-style code of another leads to a synthetic sample with preserved
individual characters but changed class assignment, following a cyclic
adversarial learning strategy. Class association embedding distills the global
class-related features of all instances into a unified domain with well
separation between classes. The transition rules between different classes can
be then extracted and further employed to individual instances. We then propose
an active XAI framework which manipulates the class-style vector of a certain
sample along guided paths towards the counter-classes, resulting in a series of
counter-example synthetic samples with identical individual characters.
Comparing these counterfactual samples with the original ones provides a
global, intuitive illustration to the nature of the classification tasks. We
adopt the framework on medical image classification tasks, which show that more
precise saliency maps with powerful context-aware representation can be
achieved compared with existing methods. Moreover, the disease pathology can be
directly visualized via traversing the paths in the class-style space.|Ruitao Xie et.al.|[2306.07306v1](http://arxiv.org/abs/2306.07306v1)|null|
|**2023-06-09**|**HiTZ@Antidote: Argumentation-driven Explainable Artificial Intelligence for Digital Medicine**|Providing high quality explanations for AI predictions based on machine
learning is a challenging and complex task. To work well it requires, among
other factors: selecting a proper level of generality/specificity of the
explanation; considering assumptions about the familiarity of the explanation
beneficiary with the AI task under consideration; referring to specific
elements that have contributed to the decision; making use of additional
knowledge (e.g. expert evidence) which might not be part of the prediction
process; and providing evidence supporting negative hypothesis. Finally, the
system needs to formulate the explanation in a clearly interpretable, and
possibly convincing, way. Given these considerations, ANTIDOTE fosters an
integrated vision of explainable AI, where low-level characteristics of the
deep learning process are combined with higher level schemes proper of the
human argumentation capacity. ANTIDOTE will exploit cross-disciplinary
competences in deep learning and argumentation to support a broader and
innovative view of explainable AI, where the need for high-quality explanations
for clinical cases deliberation is critical. As a first result of the project,
we publish the Antidote CasiMedicos dataset to facilitate research on
explainable AI in general, and argumentation in the medical domain in
particular.|Rodrigo Agerri et.al.|[2306.06029v1](http://arxiv.org/abs/2306.06029v1)|null|
|**2023-06-07**|**XInsight: Revealing Model Insights for GNNs with Flow-based Explanations**|Progress in graph neural networks has grown rapidly in recent years, with
many new developments in drug discovery, medical diagnosis, and recommender
systems. While this progress is significant, many networks are `black boxes'
with little understanding of the `what' exactly the network is learning. Many
high-stakes applications, such as drug discovery, require human-intelligible
explanations from the models so that users can recognize errors and discover
new knowledge. Therefore, the development of explainable AI algorithms is
essential for us to reap the benefits of AI.
  We propose an explainability algorithm for GNNs called eXplainable Insight
(XInsight) that generates a distribution of model explanations using GFlowNets.
Since GFlowNets generate objects with probabilities proportional to a reward,
XInsight can generate a diverse set of explanations, compared to previous
methods that only learn the maximum reward sample. We demonstrate XInsight by
generating explanations for GNNs trained on two graph classification tasks:
classifying mutagenic compounds with the MUTAG dataset and classifying acyclic
graphs with a synthetic dataset that we have open-sourced. We show the utility
of XInsight's explanations by analyzing the generated compounds using QSAR
modeling, and we find that XInsight generates compounds that cluster by
lipophilicity, a known correlate of mutagenicity. Our results show that
XInsight generates a distribution of explanations that uncovers the underlying
relationships demonstrated by the model. They also highlight the importance of
generating a diverse set of explanations, as it enables us to discover hidden
relationships in the model and provides valuable guidance for further analysis.|Eli Laird et.al.|[2306.04791v1](http://arxiv.org/abs/2306.04791v1)|null|
|**2023-06-06**|**Explainable AI using expressive Boolean formulas**|We propose and implement an interpretable machine learning classification
model for Explainable AI (XAI) based on expressive Boolean formulas. Potential
applications include credit scoring and diagnosis of medical conditions. The
Boolean formula defines a rule with tunable complexity (or interpretability),
according to which input data are classified. Such a formula can include any
operator that can be applied to one or more Boolean variables, thus providing
higher expressivity compared to more rigid rule-based and tree-based
approaches. The classifier is trained using native local optimization
techniques, efficiently searching the space of feasible formulas. Shallow rules
can be determined by fast Integer Linear Programming (ILP) or Quadratic
Unconstrained Binary Optimization (QUBO) solvers, potentially powered by
special purpose hardware or quantum devices. We combine the expressivity and
efficiency of the native local optimizer with the fast operation of these
devices by executing non-local moves that optimize over subtrees of the full
Boolean formula. We provide extensive numerical benchmarking results featuring
several baselines on well-known public datasets. Based on the results, we find
that the native local rule classifier is generally competitive with the other
classifiers. The addition of non-local moves achieves similar results with
fewer iterations, and therefore using specialized or quantum hardware could
lead to a speedup by fast proposal of non-local moves.|Gili Rosenberg et.al.|[2306.03976v1](http://arxiv.org/abs/2306.03976v1)|null|
|**2023-06-06**|**Utterance Classification with Logical Neural Network: Explainable AI for Mental Disorder Diagnosis**|In response to the global challenge of mental health problems, we proposes a
Logical Neural Network (LNN) based Neuro-Symbolic AI method for the diagnosis
of mental disorders. Due to the lack of effective therapy coverage for mental
disorders, there is a need for an AI solution that can assist therapists with
the diagnosis. However, current Neural Network models lack explainability and
may not be trusted by therapists. The LNN is a Recurrent Neural Network
architecture that combines the learning capabilities of neural networks with
the reasoning capabilities of classical logic-based AI. The proposed system
uses input predicates from clinical interviews to output a mental disorder
class, and different predicate pruning techniques are used to achieve
scalability and higher scores. In addition, we provide an insight extraction
method to aid therapists with their diagnosis. The proposed system addresses
the lack of explainability of current Neural Network models and provides a more
trustworthy solution for mental disorder diagnosis.|Yeldar Toleubay et.al.|[2306.03902v1](http://arxiv.org/abs/2306.03902v1)|null|
|**2023-06-02**|**XAI Renaissance: Redefining Interpretability in Medical Diagnostic Models**|As machine learning models become increasingly prevalent in medical
diagnostics, the need for interpretability and transparency becomes paramount.
The XAI Renaissance signifies a significant shift in the field, aiming to
redefine the interpretability of medical diagnostic models. This paper explores
the innovative approaches and methodologies within the realm of Explainable AI
(XAI) that are revolutionizing the interpretability of medical diagnostic
models. By shedding light on the underlying decision-making process, XAI
techniques empower healthcare professionals to understand, trust, and
effectively utilize these models for accurate and reliable medical diagnoses.
This review highlights the key advancements in XAI for medical diagnostics and
their potential to transform the healthcare landscape, ultimately improving
patient outcomes and fostering trust in AI-driven diagnostic systems.|Sujith K Mandala et.al.|[2306.01668v1](http://arxiv.org/abs/2306.01668v1)|null|
|**2023-05-26**|**A Novel real-time arrhythmia detection model using YOLOv8**|In a landscape characterized by heightened connectivity and mobility, coupled
with a surge in cardiovascular ailments, the imperative to curtail healthcare
expenses through remote monitoring of cardiovascular health has become more
pronounced. The accurate detection and classification of cardiac arrhythmias
are pivotal for diagnosing individuals with heart irregularities. This study
underscores the feasibility of employing electrocardiograms (ECG) measurements
in the home environment for real-time arrhythmia detection. Presenting a fresh
application for arrhythmia detection, this paper leverages the cutting-edge
You-Only-Look-Once (YOLO)v8 algorithm to categorize single-lead ECG signals. We
introduce a novel loss-modified YOLOv8 model, fine-tuned on the MIT-BIH
arrhythmia dataset, enabling real-time continuous monitoring. The obtained
results substantiate the efficacy of our approach, with the model attaining an
average accuracy of 99.5% and 0.992 mAP@50, and a rapid detection time of 0.002
seconds on an NVIDIA Tesla V100. Our investigation exemplifies the potential of
real-time arrhythmia detection, enabling users to visually interpret the model
output within the comfort of their homes. Furthermore, this study lays the
groundwork for an extension into a real-time explainable AI (XAI) model capable
of deployment in the healthcare sector, thereby significantly advancing the
realm of healthcare solutions.|Guang Jun Nicholas Ang et.al.|[2305.16727v3](http://arxiv.org/abs/2305.16727v3)|null|
|**2023-05-22**|**Breast Cancer Segmentation using Attention-based Convolutional Network and Explainable AI**|Breast cancer (BC) remains a significant health threat, with no long-term
cure currently available. Early detection is crucial, yet mammography
interpretation is hindered by high false positives and negatives. With BC
incidence projected to surpass lung cancer, improving early detection methods
is vital. Thermography, using high-resolution infrared cameras, offers promise,
especially when combined with artificial intelligence (AI). This work presents
an attention-based convolutional neural network for segmentation, providing
increased speed and precision in BC detection and classification. The system
enhances images and performs cancer segmentation with explainable AI. We
propose a transformer-attention-based convolutional architecture (UNet) for
fault identification and employ Gradient-weighted Class Activation Mapping
(Grad-CAM) to analyze areas of bias and weakness in the UNet architecture with
IRT images. The superiority of our proposed framework is confirmed when
compared with existing deep learning frameworks.|Jai Vardhan et.al.|[2305.14389v2](http://arxiv.org/abs/2305.14389v2)|null|
|**2023-05-18**|**What Symptoms and How Long? An Interpretable AI Approach for Depression Detection in Social Media**|Depression is the most prevalent and serious mental illness, which induces
grave financial and societal ramifications. Depression detection is key for
early intervention to mitigate those consequences. Such a high-stake decision
inherently necessitates interpretability. Although a few depression detection
studies attempt to explain the decision based on the importance score or
attention weights, these explanations misalign with the clinical depression
diagnosis criterion that is based on depressive symptoms. To fill this gap, we
follow the computational design science paradigm to develop a novel Multi-Scale
Temporal Prototype Network (MSTPNet). MSTPNet innovatively detects and
interprets depressive symptoms as well as how long they last. Extensive
empirical analyses using a large-scale dataset show that MSTPNet outperforms
state-of-the-art depression detection methods with an F1-score of 0.851. This
result also reveals new symptoms that are unnoted in the survey approach, such
as sharing admiration for a different life. We further conduct a user study to
demonstrate its superiority over the benchmarks in interpretability. This study
contributes to IS literature with a novel interpretable deep learning model for
depression detection in social media. In practice, our proposed method can be
implemented in social media platforms to provide personalized online resources
for detected depressed patients.|Junwei Kuang et.al.|[2305.13127v2](http://arxiv.org/abs/2305.13127v2)|null|
|**2023-05-17**|**Echoes of Biases: How Stigmatizing Language Affects AI Performance**|Electronic health records (EHRs) serve as an essential data source for the
envisioned artificial intelligence (AI)-driven transformation in healthcare.
However, clinician biases reflected in EHR notes can lead to AI models
inheriting and amplifying these biases, perpetuating health disparities. This
study investigates the impact of stigmatizing language (SL) in EHR notes on
mortality prediction using a Transformer-based deep learning model and
explainable AI (XAI) techniques. Our findings demonstrate that SL written by
clinicians adversely affects AI performance, particularly so for black
patients, highlighting SL as a source of racial disparity in AI model
development. To explore an operationally efficient way to mitigate SL's impact,
we investigate patterns in the generation of SL through a clinicians'
collaborative network, identifying central clinicians as having a stronger
impact on racial disparity in the AI model. We find that removing SL written by
central clinicians is a more efficient bias reduction strategy than eliminating
all SL in the entire corpus of data. This study provides actionable insights
for responsible AI development and contributes to understanding clinician
behavior and EHR note writing in healthcare.|Yizhi Liu et.al.|[2305.10201v4](http://arxiv.org/abs/2305.10201v4)|null|
|**2023-05-05**|**Explaining the ghosts: Feminist intersectional XAI and cartography as methods to account for invisible labour**|Contemporary automation through AI entails a substantial amount of
behind-the-scenes human labour, which is often both invisibilised and
underpaid. Since invisible labour, including labelling and maintenance work, is
an integral part of contemporary AI systems, it remains important to sensitise
users to its role. We suggest that this could be done through explainable AI
(XAI) design, particularly feminist intersectional XAI. We propose the method
of cartography, which stems from feminist intersectional research, to draw out
a systemic perspective of AI and include dimensions of AI that pertain to
invisible labour.|Goda Klumbyte et.al.|[2305.03376v1](http://arxiv.org/abs/2305.03376v1)|null|
|**2023-04-25**|**Towards Explainable and Safe Conversational Agents for Mental Health: A Survey**|Virtual Mental Health Assistants (VMHAs) are seeing continual advancements to
support the overburdened global healthcare system that gets 60 million primary
care visits, and 6 million Emergency Room (ER) visits annually. These systems
are built by clinical psychologists, psychiatrists, and Artificial Intelligence
(AI) researchers for Cognitive Behavioral Therapy (CBT). At present, the role
of VMHAs is to provide emotional support through information, focusing less on
developing a reflective conversation with the patient. A more comprehensive,
safe and explainable approach is required to build responsible VMHAs to ask
follow-up questions or provide a well-informed response. This survey offers a
systematic critical review of the existing conversational agents in mental
health, followed by new insights into the improvements of VMHAs with contextual
knowledge, datasets, and their emerging role in clinical decision support. We
also provide new directions toward enriching the user experience of VMHAs with
explainability, safety, and wholesome trustworthiness. Finally, we provide
evaluation metrics and practical considerations for VMHAs beyond the current
literature to build trust between VMHAs and patients in active communications.|Surjodeep Sarkar et.al.|[2304.13191v1](http://arxiv.org/abs/2304.13191v1)|null|
|**2023-04-04**|**A Brief Review of Explainable Artificial Intelligence in Healthcare**|XAI refers to the techniques and methods for building AI applications which
assist end users to interpret output and predictions of AI models. Black box AI
applications in high-stakes decision-making situations, such as medical domain
have increased the demand for transparency and explainability since wrong
predictions may have severe consequences. Model explainability and
interpretability are vital successful deployment of AI models in healthcare
practices. AI applications' underlying reasoning needs to be transparent to
clinicians in order to gain their trust. This paper presents a systematic
review of XAI aspects and challenges in the healthcare domain. The primary
goals of this study are to review various XAI methods, their challenges, and
related machine learning models in healthcare. The methods are discussed under
six categories: Features-oriented methods, global methods, concept models,
surrogate models, local pixel-based methods, and human-centric methods. Most
importantly, the paper explores XAI role in healthcare problems to clarify its
necessity in safety-critical applications. The paper intends to establish a
comprehensive understanding of XAI-related applications in the healthcare field
by reviewing the related experimental results. To facilitate future research
for filling research gaps, the importance of XAI models from different
viewpoints and their limitations are investigated.|Zahra Sadeghi et.al.|[2304.01543v1](http://arxiv.org/abs/2304.01543v1)|null|
|**2023-03-22**|**Reveal to Revise: An Explainable AI Life Cycle for Iterative Bias Correction of Deep Models**|State-of-the-art machine learning models often learn spurious correlations
embedded in the training data. This poses risks when deploying these models for
high-stake decision-making, such as in medical applications like skin cancer
detection. To tackle this problem, we propose Reveal to Revise (R2R), a
framework entailing the entire eXplainable Artificial Intelligence (XAI) life
cycle, enabling practitioners to iteratively identify, mitigate, and
(re-)evaluate spurious model behavior with a minimal amount of human
interaction. In the first step (1), R2R reveals model weaknesses by finding
outliers in attributions or through inspection of latent concepts learned by
the model. Secondly (2), the responsible artifacts are detected and spatially
localized in the input data, which is then leveraged to (3) revise the model
behavior. Concretely, we apply the methods of RRR, CDEP and ClArC for model
correction, and (4) (re-)evaluate the model's performance and remaining
sensitivity towards the artifact. Using two medical benchmark datasets for
Melanoma detection and bone age estimation, we apply our R2R framework to VGG,
ResNet and EfficientNet architectures and thereby reveal and correct real
dataset-intrinsic artifacts, as well as synthetic variants in a controlled
setting. Completing the XAI life cycle, we demonstrate multiple R2R iterations
to mitigate different biases. Code is available on
https://github.com/maxdreyer/Reveal2Revise.|Frederik Pahde et.al.|[2303.12641v2](http://arxiv.org/abs/2303.12641v2)|[link](https://github.com/maxdreyer/reveal2revise)|
|**2023-03-11**|**Explainable AI for Time Series via Virtual Inspection Layers**|The field of eXplainable Artificial Intelligence (XAI) has greatly advanced
in recent years, but progress has mainly been made in computer vision and
natural language processing. For time series, where the input is often not
interpretable, only limited research on XAI is available. In this work, we put
forward a virtual inspection layer, that transforms the time series to an
interpretable representation and allows to propagate relevance attributions to
this representation via local XAI methods like layer-wise relevance propagation
(LRP). In this way, we extend the applicability of a family of XAI methods to
domains (e.g. speech) where the input is only interpretable after a
transformation. Here, we focus on the Fourier transformation which is
prominently applied in the interpretation of time series and LRP and refer to
our method as DFT-LRP. We demonstrate the usefulness of DFT-LRP in various time
series classification settings like audio and electronic health records. We
showcase how DFT-LRP reveals differences in the classification strategies of
models trained in different domains (e.g., time vs. frequency domain) or helps
to discover how models act on spurious correlations in the data.|Johanna Vielhaben et.al.|[2303.06365v1](http://arxiv.org/abs/2303.06365v1)|null|
|**2023-03-08**|**Towards Trust of Explainable AI in Thyroid Nodule Diagnosis**|The ability to explain the prediction of deep learning models to end-users is
an important feature to leverage the power of artificial intelligence (AI) for
the medical decision-making process, which is usually considered
non-transparent and challenging to comprehend. In this paper, we apply
state-of-the-art eXplainable artificial intelligence (XAI) methods to explain
the prediction of the black-box AI models in the thyroid nodule diagnosis
application. We propose new statistic-based XAI methods, namely Kernel Density
Estimation and Density map, to explain the case of no nodule detected. XAI
methods' performances are considered under a qualitative and quantitative
comparison as feedback to improve the data quality and the model performance.
Finally, we survey to assess doctors' and patients' trust in XAI explanations
of the model's decisions on thyroid nodule images.|Truong Thanh Hung Nguyen et.al.|[2303.04731v1](http://arxiv.org/abs/2303.04731v1)|[link](https://github.com/hungntt/xai_thyroid)|
|**2023-03-06**|**Cybersecurity of AI medical devices: risks, legislation, and challenges**|Medical devices and artificial intelligence systems rapidly transform
healthcare provisions. At the same time, due to their nature, AI in or as
medical devices might get exposed to cyberattacks, leading to patient safety
and security risks. This book chapter is divided into three parts. The first
part starts by setting the scene where we explain the role of cybersecurity in
healthcare. Then, we briefly define what we refer to when we talk about AI that
is considered a medical device by itself or supports one. To illustrate the
risks such medical devices pose, we provide three examples: the poisoning of
datasets, social engineering, and data or source code extraction. In the second
part, the paper provides an overview of the European Union's regulatory
framework relevant for ensuring the cybersecurity of AI as or in medical
devices (MDR, NIS Directive, Cybersecurity Act, GDPR, the AI Act proposal and
the NIS 2 Directive proposal). Finally, the third part of the paper examines
possible challenges stemming from the EU regulatory framework. In particular,
we look toward the challenges deriving from the two legislative proposals and
their interaction with the existing legislation concerning AI medical devices'
cybersecurity. They are structured as answers to the following questions: (1)
how will the AI Act interact with the MDR regarding the cybersecurity and
safety requirements?; (2) how should we interpret incident notification
requirements from the NIS 2 Directive proposal and MDR?; and (3) what are the
consequences of the evolving term of critical infrastructures?
  [This is a draft chapter. The final version will be available in Research
Handbook on Health, AI and the Law edited by Barry Solaiman & I. Glenn Cohen,
forthcoming 2023, Edward Elgar Publishing Ltd]|Elisabetta Biasin et.al.|[2303.03140v1](http://arxiv.org/abs/2303.03140v1)|null|
|**2023-02-06**|**LAVA: Granular Neuron-Level Explainable AI for Alzheimer's Disease Assessment from Fundus Images**|Alzheimer's Disease (AD) is a progressive neurodegenerative disease and the
leading cause of dementia. Early diagnosis is critical for patients to benefit
from potential intervention and treatment. The retina has been hypothesized as
a diagnostic site for AD detection owing to its anatomical connection with the
brain. Developed AI models for this purpose have yet to provide a rational
explanation about the decision and neither infer the stage of disease's
progression. Along this direction, we propose a novel model-agnostic
explainable-AI framework, called Granular Neuron-level Explainer (LAVA), an
interpretation prototype that probes into intermediate layers of the
Convolutional Neural Network (CNN) models to assess the AD continuum directly
from the retinal imaging without longitudinal or clinical evaluation. This
method is applied to validate the retinal vasculature as a biomarker and
diagnostic modality for Alzheimer's Disease (AD) evaluation. UK Biobank
cognitive tests and vascular morphological features suggest LAVA shows strong
promise and effectiveness in identifying AD stages across the progression
continuum.|Nooshin Yousefzadeh et.al.|[2302.03008v2](http://arxiv.org/abs/2302.03008v2)|null|
|**2023-02-02**|**Diagrammatization: Rationalizing with diagrammatic AI explanations for abductive-deductive reasoning on hypotheses**|Many visualizations have been developed for explainable AI (XAI), but they
often require further reasoning by users to interpret. We argue that XAI should
support diagrammatic and abductive reasoning for the AI to perform hypothesis
generation and evaluation to reduce the interpretability gap. We propose
Diagrammatization to i) perform Peircean abductive-deductive reasoning, ii)
follow domain conventions, and iii) explain with diagrams visually or verbally.
We implemented DiagramNet for a clinical application to predict cardiac
diagnoses from heart auscultation, and explain with shape-based murmur
diagrams. In modeling studies, we found that DiagramNet not only provides
faithful murmur shape explanations, but also has better prediction performance
than baseline models. We further demonstrate the interpretability and
trustworthiness of diagrammatic explanations in a qualitative user study with
medical students, showing that clinically-relevant, diagrammatic explanations
are preferred over technical saliency map explanations. This work contributes
insights into providing domain-conventional abductive explanations for
user-centric XAI.|Brian Y. Lim et.al.|[2302.01241v2](http://arxiv.org/abs/2302.01241v2)|null|
|**2023-02-02**|**LesionAid: Vision Transformers-based Skin Lesion Generation and Classification**|Skin cancer is one of the most prevalent forms of human cancer. It is
recognized mainly visually, beginning with clinical screening and continuing
with the dermoscopic examination, histological assessment, and specimen
collection. Deep convolutional neural networks (CNNs) perform highly segregated
and potentially universal tasks against a classified finegrained object. This
research proposes a novel multi-class prediction framework that classifies skin
lesions based on ViT and ViTGAN. Vision transformers-based GANs (Generative
Adversarial Networks) are utilized to tackle the class imbalance. The framework
consists of four main phases: ViTGANs, Image processing, and explainable AI.
Phase 1 consists of generating synthetic images to balance all the classes in
the dataset. Phase 2 consists of applying different data augmentation
techniques and morphological operations to increase the size of the data.
Phases 3 & 4 involve developing a ViT model for edge computing systems that can
identify patterns and categorize skin lesions from the user's skin visible in
the image. In phase 3, after classifying the lesions into the desired class
with ViT, we will use explainable AI (XAI) that leads to more explainable
results (using activation maps, etc.) while ensuring high predictive accuracy.
Real-time images of skin diseases can capture by a doctor or a patient using
the camera of a mobile application to perform an early examination and
determine the cause of the skin lesion. The whole framework is compared with
the existing frameworks for skin lesion detection.|Ghanta Sai Krishna et.al.|[2302.01104v1](http://arxiv.org/abs/2302.01104v1)|null|
|**2023-02-01**|**SkinCon: A skin disease dataset densely annotated by domain experts for fine-grained model debugging and analysis**|For the deployment of artificial intelligence (AI) in high-risk settings,
such as healthcare, methods that provide interpretability/explainability or
allow fine-grained error analysis are critical. Many recent methods for
interpretability/explainability and fine-grained error analysis use concepts,
which are meta-labels that are semantically meaningful to humans. However,
there are only a few datasets that include concept-level meta-labels and most
of these meta-labels are relevant for natural images that do not require domain
expertise. Densely annotated datasets in medicine focused on meta-labels that
are relevant to a single disease such as melanoma. In dermatology, skin disease
is described using an established clinical lexicon that allows clinicians to
describe physical exam findings to one another. To provide a medical dataset
densely annotated by domain experts with annotations useful across multiple
disease processes, we developed SkinCon: a skin disease dataset densely
annotated by dermatologists. SkinCon includes 3230 images from the Fitzpatrick
17k dataset densely annotated with 48 clinical concepts, 22 of which have at
least 50 images representing the concept. The concepts used were chosen by two
dermatologists considering the clinical descriptor terms used to describe skin
lesions. Examples include "plaque", "scale", and "erosion". The same concepts
were also used to label 656 skin disease images from the Diverse Dermatology
Images dataset, providing an additional external dataset with diverse skin tone
representations. We review the potential applications for the SkinCon dataset,
such as probing models, concept-based explanations, and concept bottlenecks.
Furthermore, we use SkinCon to demonstrate two of these use cases: debugging
mistakes of an existing dermatology AI model with concepts and developing
interpretable models with post-hoc concept bottleneck models.|Roxana Daneshjou et.al.|[2302.00785v1](http://arxiv.org/abs/2302.00785v1)|null|
|**2023-01-19**|**Decision-Focused Evaluation: Analyzing Performance of Deployed Restless Multi-Arm Bandits**|Restless multi-arm bandits (RMABs) is a popular decision-theoretic framework
that has been used to model real-world sequential decision making problems in
public health, wildlife conservation, communication systems, and beyond.
Deployed RMAB systems typically operate in two stages: the first predicts the
unknown parameters defining the RMAB instance, and the second employs an
optimization algorithm to solve the constructed RMAB instance.
  In this work we provide and analyze the results from a first-of-its-kind
deployment of an RMAB system in public health domain, aimed at improving
maternal and child health. Our analysis is focused towards understanding the
relationship between prediction accuracy and overall performance of deployed
RMAB systems. This is crucial for determining the value of investing in
improving predictive accuracy towards improving the final system performance,
and is useful for diagnosing, monitoring deployed RMAB systems.
  Using real-world data from our deployed RMAB system, we demonstrate that an
improvement in overall prediction accuracy may even be accompanied by a
degradation in the performance of RMAB system -- a broad investment of
resources to improve overall prediction accuracy may not yield expected
results. Following this, we develop decision-focused evaluation metrics to
evaluate the predictive component and show that it is better at explaining
(both empirically and theoretically) the overall performance of a deployed RMAB
system.|Paritosh Verma et.al.|[2301.07835v1](http://arxiv.org/abs/2301.07835v1)|null|
|**2023-01-18**|**Exemplars and Counterexemplars Explanations for Image Classifiers, Targeting Skin Lesion Labeling**|Explainable AI consists in developing mechanisms allowing for an interaction
between decision systems and humans by making the decisions of the formers
understandable. This is particularly important in sensitive contexts like in
the medical domain. We propose a use case study, for skin lesion diagnosis,
illustrating how it is possible to provide the practitioner with explanations
on the decisions of a state of the art deep neural network classifier trained
to characterize skin lesions from examples. Our framework consists of a trained
classifier onto which an explanation module operates. The latter is able to
offer the practitioner exemplars and counterexemplars for the classification
diagnosis thus allowing the physician to interact with the automatic diagnosis
system. The exemplars are generated via an adversarial autoencoder. We
illustrate the behavior of the system on representative examples.|Carlo Metta et.al.|[2302.03033v1](http://arxiv.org/abs/2302.03033v1)|null|
|**2023-01-17**|**Monotonicity for AI ethics and society: An empirical study of the monotonic neural additive model in criminology, education, health care, and finance**|Algorithm fairness in the application of artificial intelligence (AI) is
essential for a better society. As the foundational axiom of social mechanisms,
fairness consists of multiple facets. Although the machine learning (ML)
community has focused on intersectionality as a matter of statistical parity,
especially in discrimination issues, an emerging body of literature addresses
another facet -- monotonicity. Based on domain expertise, monotonicity plays a
vital role in numerous fairness-related areas, where violations could misguide
human decisions and lead to disastrous consequences. In this paper, we first
systematically evaluate the significance of applying monotonic neural additive
models (MNAMs), which use a fairness-aware ML algorithm to enforce both
individual and pairwise monotonicity principles, for the fairness of AI ethics
and society. We have found, through a hybrid method of theoretical reasoning,
simulation, and extensive empirical analysis, that considering monotonicity
axioms is essential in all areas of fairness, including criminology, education,
health care, and finance. Our research contributes to the interdisciplinary
research at the interface of AI ethics, explainable AI (XAI), and
human-computer interactions (HCIs). By evidencing the catastrophic consequences
if monotonicity is not met, we address the significance of monotonicity
requirements in AI applications. Furthermore, we demonstrate that MNAMs are an
effective fairness-aware ML approach by imposing monotonicity restrictions
integrating human intelligence.|Dangxing Chen et.al.|[2301.07060v1](http://arxiv.org/abs/2301.07060v1)|null|
|**2023-01-15**|**Rationalizing Predictions by Adversarial Information Calibration**|Explaining the predictions of AI models is paramount in safety-critical
applications, such as in legal or medical domains. One form of explanation for
a prediction is an extractive rationale, i.e., a subset of features of an
instance that lead the model to give its prediction on that instance. For
example, the subphrase ``he stole the mobile phone'' can be an extractive
rationale for the prediction of ``Theft''. Previous works on generating
extractive rationales usually employ a two-phase model: a selector that selects
the most important features (i.e., the rationale) followed by a predictor that
makes the prediction based exclusively on the selected features. One
disadvantage of these works is that the main signal for learning to select
features comes from the comparison of the answers given by the predictor to the
ground-truth answers. In this work, we propose to squeeze more information from
the predictor via an information calibration method. More precisely, we train
two models jointly: one is a typical neural model that solves the task at hand
in an accurate but black-box manner, and the other is a selector-predictor
model that additionally produces a rationale for its prediction. The first
model is used as a guide for the second model. We use an adversarial technique
to calibrate the information extracted by the two models such that the
difference between them is an indicator of the missed or over-selected
features. In addition, for natural language tasks, we propose a
language-model-based regularizer to encourage the extraction of fluent
rationales. Experimental results on a sentiment analysis task, a hate speech
recognition task as well as on three tasks from the legal domain show the
effectiveness of our approach to rationale extraction.|Lei Sha et.al.|[2301.06009v1](http://arxiv.org/abs/2301.06009v1)|null|
|**2023-01-05**|**Semantic match: Debugging feature attribution methods in XAI for healthcare**|The recent spike in certified Artificial Intelligence (AI) tools for
healthcare has renewed the debate around adoption of this technology. One
thread of such debate concerns Explainable AI (XAI) and its promise to render
AI devices more transparent and trustworthy. A few voices active in the medical
AI space have expressed concerns on the reliability of Explainable AI
techniques and especially feature attribution methods, questioning their use
and inclusion in guidelines and standards. Despite valid concerns, we argue
that existing criticism on the viability of post-hoc local explainability
methods throws away the baby with the bathwater by generalizing a problem that
is specific to image data. We begin by characterizing the problem as a lack of
semantic match between explanations and human understanding. To understand when
feature importance can be used reliably, we introduce a distinction between
feature importance of low- and high-level features. We argue that for data
types where low-level features come endowed with a clear semantics, such as
tabular data like Electronic Health Records (EHRs), semantic match can be
obtained, and thus feature attribution methods can still be employed in a
meaningful and useful way. Finally, we sketch a procedure to test whether
semantic match has been achieved.|Giovanni Cinà et.al.|[2301.02080v3](http://arxiv.org/abs/2301.02080v3)|null|
|**2022-12-17**|**Context-dependent Explainability and Contestability for Trustworthy Medical Artificial Intelligence: Misclassification Identification of Morbidity Recognition Models in Preterm Infants**|Although machine learning (ML) models of AI achieve high performances in
medicine, they are not free of errors. Empowering clinicians to identify
incorrect model recommendations is crucial for engendering trust in medical AI.
Explainable AI (XAI) aims to address this requirement by clarifying AI
reasoning to support the end users. Several studies on biomedical imaging
achieved promising results recently. Nevertheless, solutions for models using
tabular data are not sufficient to meet the requirements of clinicians yet.
This paper proposes a methodology to support clinicians in identifying failures
of ML models trained with tabular data. We built our methodology on three main
pillars: decomposing the feature set by leveraging clinical context latent
space, assessing the clinical association of global explanations, and Latent
Space Similarity (LSS) based local explanations. We demonstrated our
methodology on ML-based recognition of preterm infant morbidities caused by
infection. The risk of mortality, lifelong disability, and antibiotic
resistance due to model failures was an open research question in this domain.
We achieved to identify misclassification cases of two models with our
approach. By contextualizing local explanations, our solution provides
clinicians with actionable insights to support their autonomy for informed
final decisions.|Isil Guzey et.al.|[2212.08821v1](http://arxiv.org/abs/2212.08821v1)|null|
|**2022-12-16**|**It is not "accuracy vs. explainability" -- we need both for trustworthy AI systems**|We are witnessing the emergence of an AI economy and society where AI
technologies are increasingly impacting health care, business, transportation
and many aspects of everyday life. Many successes have been reported where AI
systems even surpassed the accuracy of human experts. However, AI systems may
produce errors, can exhibit bias, may be sensitive to noise in the data, and
often lack technical and judicial transparency resulting in reduction in trust
and challenges in their adoption. These recent shortcomings and concerns have
been documented in scientific but also in general press such as accidents with
self driving cars, biases in healthcare, hiring and face recognition systems
for people of color, seemingly correct medical decisions later found to be made
due to wrong reasons etc. This resulted in emergence of many government and
regulatory initiatives requiring trustworthy and ethical AI to provide accuracy
and robustness, some form of explainability, human control and oversight,
elimination of bias, judicial transparency and safety. The challenges in
delivery of trustworthy AI systems motivated intense research on explainable AI
systems (XAI). Aim of XAI is to provide human understandable information of how
AI systems make their decisions. In this paper we first briefly summarize
current XAI work and then challenge the recent arguments of accuracy vs.
explainability for being mutually exclusive and being focused only on deep
learning. We then present our recommendations for the use of XAI in full
lifecycle of high stakes trustworthy AI systems delivery, e.g. development,
validation and certification, and trustworthy production and maintenance.|D. Petkovic et.al.|[2212.11136v2](http://arxiv.org/abs/2212.11136v2)|null|
|**2022-12-02**|**SimpleMind adds thinking to deep neural networks**|Deep neural networks (DNNs) detect patterns in data and have shown
versatility and strong performance in many computer vision applications.
However, DNNs alone are susceptible to obvious mistakes that violate simple,
common sense concepts and are limited in their ability to use explicit
knowledge to guide their search and decision making. While overall DNN
performance metrics may be good, these obvious errors, coupled with a lack of
explainability, have prevented widespread adoption for crucial tasks such as
medical image analysis. The purpose of this paper is to introduce SimpleMind,
an open-source software framework for Cognitive AI focused on medical image
understanding. It allows creation of a knowledge base that describes expected
characteristics and relationships between image objects in an intuitive
human-readable form. The SimpleMind framework brings thinking to DNNs by: (1)
providing methods for reasoning with the knowledge base about image content,
such as spatial inferencing and conditional reasoning to check DNN outputs; (2)
applying process knowledge, in the form of general-purpose software agents,
that are chained together to accomplish image preprocessing, DNN prediction,
and result post-processing, and (3) performing automatic co-optimization of all
knowledge base parameters to adapt agents to specific problems. SimpleMind
enables reasoning on multiple detected objects to ensure consistency, providing
cross checking between DNN outputs. This machine reasoning improves the
reliability and trustworthiness of DNNs through an interpretable model and
explainable decisions. Example applications are provided that demonstrate how
SimpleMind supports and improves deep neural networks by embedding them within
a Cognitive AI framework.|Youngwon Choi et.al.|[2212.00951v1](http://arxiv.org/abs/2212.00951v1)|[link](https://gitlab.com/sm-ai-team/simplemind)|
|**2022-11-27**|**Attribution-based XAI Methods in Computer Vision: A Review**|The advancements in deep learning-based methods for visual perception tasks
have seen astounding growth in the last decade, with widespread adoption in a
plethora of application areas from autonomous driving to clinical decision
support systems. Despite their impressive performance, these deep
learning-based models remain fairly opaque in their decision-making process,
making their deployment in human-critical tasks a risky endeavor. This in turn
makes understanding the decisions made by these models crucial for their
reliable deployment. Explainable AI (XAI) methods attempt to address this by
offering explanations for such black-box deep learning methods. In this paper,
we provide a comprehensive survey of attribution-based XAI methods in computer
vision and review the existing literature for gradient-based,
perturbation-based, and contrastive methods for XAI, and provide insights on
the key challenges in developing and evaluating robust XAI methods.|Kumar Abhishek et.al.|[2211.14736v1](http://arxiv.org/abs/2211.14736v1)|null|
|**2022-11-08**|**Privacy Meets Explainability: A Comprehensive Impact Benchmark**|Since the mid-10s, the era of Deep Learning (DL) has continued to this day,
bringing forth new superlatives and innovations each year. Nevertheless, the
speed with which these innovations translate into real applications lags behind
this fast pace. Safety-critical applications, in particular, underlie strict
regulatory and ethical requirements which need to be taken care of and are
still active areas of debate. eXplainable AI (XAI) and privacy-preserving
machine learning (PPML) are both crucial research fields, aiming at mitigating
some of the drawbacks of prevailing data-hungry black-box models in DL. Despite
brisk research activity in the respective fields, no attention has yet been
paid to their interaction. This work is the first to investigate the impact of
private learning techniques on generated explanations for DL-based models. In
an extensive experimental analysis covering various image and time series
datasets from multiple domains, as well as varying privacy techniques, XAI
methods, and model architectures, the effects of private training on generated
explanations are studied. The findings suggest non-negligible changes in
explanations through the introduction of privacy. Apart from reporting
individual effects of PPML on XAI, the paper gives clear recommendations for
the choice of techniques in real applications. By unveiling the
interdependencies of these pivotal technologies, this work is a first step
towards overcoming the remaining hurdles for practically applicable AI in
safety-critical domains.|Saifullah Saifullah et.al.|[2211.04110v1](http://arxiv.org/abs/2211.04110v1)|null|
|**2022-11-05**|**Predicting Treatment Adherence of Tuberculosis Patients at Scale**|Tuberculosis (TB), an infectious bacterial disease, is a significant cause of
death, especially in low-income countries, with an estimated ten million new
cases reported globally in $2020$. While TB is treatable, non-adherence to the
medication regimen is a significant cause of morbidity and mortality. Thus,
proactively identifying patients at risk of dropping off their medication
regimen enables corrective measures to mitigate adverse outcomes. Using a proxy
measure of extreme non-adherence and a dataset of nearly $700,000$ patients
from four states in India, we formulate and solve the machine learning (ML)
problem of early prediction of non-adherence based on a custom rank-based
metric. We train ML models and evaluate against baselines, achieving a $\sim
100\%$ lift over rule-based baselines and $\sim 214\%$ over a random
classifier, taking into account country-wide large-scale future deployment. We
deal with various issues in the process, including data quality,
high-cardinality categorical data, low target prevalence, distribution shift,
variation across cohorts, algorithmic fairness, and the need for robustness and
explainability. Our findings indicate that risk stratification of non-adherent
patients is a viable, deployable-at-scale ML solution. As the official AI
partner of India's Central TB Division, we are working on multiple city and
state-level pilots with the goal of pan-India deployment.|Mihir Kulkarni et.al.|[2211.02943v2](http://arxiv.org/abs/2211.02943v2)|null|
|**2022-11-02**|**Explainable AI over the Internet of Things (IoT): Overview, State-of-the-Art and Future Directions**|Explainable Artificial Intelligence (XAI) is transforming the field of
Artificial Intelligence (AI) by enhancing the trust of end-users in machines.
As the number of connected devices keeps on growing, the Internet of Things
(IoT) market needs to be trustworthy for the end-users. However, existing
literature still lacks a systematic and comprehensive survey work on the use of
XAI for IoT. To bridge this lacking, in this paper, we address the XAI
frameworks with a focus on their characteristics and support for IoT. We
illustrate the widely-used XAI services for IoT applications, such as security
enhancement, Internet of Medical Things (IoMT), Industrial IoT (IIoT), and
Internet of City Things (IoCT). We also suggest the implementation choice of
XAI models over IoT systems in these applications with appropriate examples and
summarize the key inferences for future works. Moreover, we present the
cutting-edge development in edge XAI structures and the support of
sixth-generation (6G) communication services for IoT applications, along with
key inferences. In a nutshell, this paper constitutes the first holistic
compilation on the development of XAI-based frameworks tailored for the demands
of future IoT use cases.|Senthil Kumar Jagatheesaperumal et.al.|[2211.01036v2](http://arxiv.org/abs/2211.01036v2)|null|
|**2022-10-24**|**Human-centered XAI for Burn Depth Characterization**|Approximately 1.25 million people in the United States are treated each year
for burn injuries. Precise burn injury classification is an important aspect of
the medical AI field. In this work, we propose an explainable human-in-the-loop
framework for improving burn ultrasound classification models. Our framework
leverages an explanation system based on the LIME classification explainer to
corroborate and integrate a burn expert's knowledge -- suggesting new features
and ensuring the validity of the model. Using this framework, we discover that
B-mode ultrasound classifiers can be enhanced by supplying textural features.
More specifically, we confirm that texture features based on the Gray Level
Co-occurance Matrix (GLCM) of ultrasound frames can increase the accuracy of
transfer learned burn depth classifiers. We test our hypothesis on real data
from porcine subjects. We show improvements in the accuracy of burn depth
classification -- from ~88% to ~94% -- once modified according to our
framework.|Maxwell J. Jacobson et.al.|[2210.13535v2](http://arxiv.org/abs/2210.13535v2)|null|
|**2022-10-07**|**What Do End-Users Really Want? Investigation of Human-Centered XAI for Mobile Health Apps**|In healthcare, AI systems support clinicians and patients in diagnosis,
treatment, and monitoring, but many systems' poor explainability remains
challenging for practical application. Overcoming this barrier is the goal of
explainable AI (XAI). However, an explanation can be perceived differently and,
thus, not solve the black-box problem for everyone. The domain of
Human-Centered AI deals with this problem by adapting AI to users. We present a
user-centered persona concept to evaluate XAI and use it to investigate
end-users preferences for various explanation styles and contents in a mobile
health stress monitoring application. The results of our online survey show
that users' demographics and personality, as well as the type of explanation,
impact explanation preferences, indicating that these are essential features
for XAI design. We subsumed the results in three prototypical user personas:
power-, casual-, and privacy-oriented users. Our insights bring an interactive,
human-centered XAI closer to practical application.|Katharina Weitz et.al.|[2210.03506v1](http://arxiv.org/abs/2210.03506v1)|null|
|**2022-10-07**|**Explainable AI based Glaucoma Detection using Transfer Learning and LIME**|Glaucoma is the second driving reason for partial or complete blindness among
all the visual deficiencies which mainly occurs because of excessive pressure
in the eye due to anxiety or depression which damages the optic nerve and
creates complications in vision. Traditional glaucoma screening is a
time-consuming process that necessitates the medical professionals' constant
attention, and even so time to time due to the time constrains and pressure
they fail to classify correctly that leads to wrong treatment. Numerous efforts
have been made to automate the entire glaucoma classification procedure
however, these existing models in general have a black box characteristics that
prevents users from understanding the key reasons behind the prediction and
thus medical practitioners generally can not rely on these system. In this
article after comparing with various pre-trained models, we propose a transfer
learning model that is able to classify Glaucoma with 94.71\% accuracy. In
addition, we have utilized Local Interpretable Model-Agnostic
Explanations(LIME) that introduces explainability in our system. This
improvement enables medical professionals obtain important and comprehensive
information that aid them in making judgments. It also lessen the opacity and
fragility of the traditional deep learning models.|Touhidul Islam Chayan et.al.|[2210.03332v1](http://arxiv.org/abs/2210.03332v1)|null|
|**2022-09-30**|**Evaluation of importance estimators in deep learning classifiers for Computed Tomography**|Deep learning has shown superb performance in detecting objects and
classifying images, ensuring a great promise for analyzing medical imaging.
Translating the success of deep learning to medical imaging, in which doctors
need to understand the underlying process, requires the capability to interpret
and explain the prediction of neural networks. Interpretability of deep neural
networks often relies on estimating the importance of input features (e.g.,
pixels) with respect to the outcome (e.g., class probability). However, a
number of importance estimators (also known as saliency maps) have been
developed and it is unclear which ones are more relevant for medical imaging
applications. In the present work, we investigated the performance of several
importance estimators in explaining the classification of computed tomography
(CT) images by a convolutional deep network, using three distinct evaluation
metrics. First, the model-centric fidelity measures a decrease in the model
accuracy when certain inputs are perturbed. Second, concordance between
importance scores and the expert-defined segmentation masks is measured on a
pixel level by a receiver operating characteristic (ROC) curves. Third, we
measure a region-wise overlap between a XRAI-based map and the segmentation
mask by Dice Similarity Coefficients (DSC). Overall, two versions of SmoothGrad
topped the fidelity and ROC rankings, whereas both Integrated Gradients and
SmoothGrad excelled in DSC evaluation. Interestingly, there was a critical
discrepancy between model-centric (fidelity) and human-centric (ROC and DSC)
evaluation. Expert expectation and intuition embedded in segmentation maps does
not necessarily align with how the model arrived at its prediction.
Understanding this difference in interpretability would help harnessing the
power of deep learning in medicine.|Lennart Brocki et.al.|[2209.15398v1](http://arxiv.org/abs/2209.15398v1)|null|
|**2022-09-30**|**An Interactive Interpretability System for Breast Cancer Screening with Deep Learning**|Deep learning methods, in particular convolutional neural networks, have
emerged as a powerful tool in medical image computing tasks. While these
complex models provide excellent performance, their black-box nature may hinder
real-world adoption in high-stakes decision-making. In this paper, we propose
an interactive system to take advantage of state-of-the-art interpretability
techniques to assist radiologists with breast cancer screening. Our system
integrates a deep learning model into the radiologists' workflow and provides
novel interactions to promote understanding of the model's decision-making
process. Moreover, we demonstrate that our system can take advantage of user
interactions progressively to provide finer-grained explainability reports with
little labeling overhead. Due to the generic nature of the adopted
interpretability technique, our system is domain-agnostic and can be used for
many different medical image computing tasks, presenting a novel perspective on
how we can leverage visual analytics to transform originally static
interpretability techniques to augment human decision making and promote the
adoption of medical AI.|Yuzhe Lu et.al.|[2210.08979v1](http://arxiv.org/abs/2210.08979v1)|null|
|**2022-09-14**|**Explainable AI for clinical and remote health applications: a survey on tabular and time series data**|Nowadays Artificial Intelligence (AI) has become a fundamental component of
healthcare applications, both clinical and remote, but the best performing AI
systems are often too complex to be self-explaining. Explainable AI (XAI)
techniques are defined to unveil the reasoning behind the system's predictions
and decisions, and they become even more critical when dealing with sensitive
and personal health data. It is worth noting that XAI has not gathered the same
attention across different research areas and data types, especially in
healthcare. In particular, many clinical and remote health applications are
based on tabular and time series data, respectively, and XAI is not commonly
analysed on these data types, while computer vision and Natural Language
Processing (NLP) are the reference applications. To provide an overview of XAI
methods that are most suitable for tabular and time series data in the
healthcare domain, this paper provides a review of the literature in the last 5
years, illustrating the type of generated explanations and the efforts provided
to evaluate their relevance and quality. Specifically, we identify clinical
validation, consistency assessment, objective and standardised quality
evaluation, and human-centered quality assessment as key features to ensure
effective explanations for the end users. Finally, we highlight the main
research challenges in the field as well as the limitations of existing XAI
methods.|Flavio Di Martino et.al.|[2209.06528v1](http://arxiv.org/abs/2209.06528v1)|null|
|**2022-08-31**|**Enhancing Early Lung Cancer Detection on Chest Radiographs with AI-assistance: A Multi-Reader Study**|Objectives: The present study evaluated the impact of a commercially
available explainable AI algorithm in augmenting the ability of clinicians to
identify lung cancer on chest X-rays (CXR).
  Design: This retrospective study evaluated the performance of 11 clinicians
for detecting lung cancer from chest radiographs, with and without assistance
from a commercially available AI algorithm (red dot, Behold.ai) that predicts
suspected lung cancer from CXRs. Clinician performance was evaluated against
clinically confirmed diagnoses.
  Setting: The study analysed anonymised patient data from an NHS hospital; the
dataset consisted of 400 chest radiographs from adult patients (18 years and
above) who had a CXR performed in 2020, with corresponding clinical text
reports.
  Participants: A panel of readers consisting of 11 clinicians (consultant
radiologists, radiologist trainees and reporting radiographers) participated in
this study.
  Main outcome measures: Overall accuracy, sensitivity, specificity and
precision for detecting lung cancer on CXRs by clinicians, with and without AI
input. Agreement rates between clinicians and performance standard deviation
were also evaluated, with and without AI input.
  Results: The use of the AI algorithm by clinicians led to an improved overall
performance for lung tumour detection, achieving an overall increase of 17.4%
of lung cancers being identified on CXRs which would have otherwise been
missed, an overall increase in detection of smaller tumours, a 24% and 13%
increased detection of stage 1 and stage 2 lung cancers respectively, and
standardisation of clinician performance.
  Conclusions: This study showed great promise in the clinical utility of AI
algorithms in improving early lung cancer diagnosis and promoting health equity
through overall improvement in reader performances, without impacting
downstream imaging resources.|Gaetan Dissez et.al.|[2208.14742v1](http://arxiv.org/abs/2208.14742v1)|null|
|**2022-08-24**|**GAN-based generative modelling for dermatological applications -- comparative study**|The lack of sufficiently large open medical databases is one of the biggest
challenges in AI-powered healthcare. Synthetic data created using Generative
Adversarial Networks (GANs) appears to be a good solution to mitigate the
issues with privacy policies. The other type of cure is decentralized protocol
across multiple medical institutions without exchanging local data samples. In
this paper, we explored unconditional and conditional GANs in centralized and
decentralized settings. The centralized setting imitates studies on large but
highly unbalanced skin lesion dataset, while the decentralized one simulates a
more realistic hospital scenario with three institutions. We evaluated models'
performance in terms of fidelity, diversity, speed of training, and predictive
ability of classifiers trained on the generated synthetic data. In addition we
provided explainability through exploration of latent space and embeddings
projection focused both on global and local explanations. Calculated distance
between real images and their projections in the latent space proved the
authenticity and generalization of trained GANs, which is one of the main
concerns in this type of applications. The open source code for conducted
studies is publicly available at
\url{https://github.com/aidotse/stylegan2-ada-pytorch}.|Sandra Carrasco Limeros et.al.|[2208.11702v1](http://arxiv.org/abs/2208.11702v1)|[link](https://github.com/aidotse/stylegan2-ada-pytorch)|
|**2022-08-05**|**Planning and Scheduling in Digital Health with Answer Set Programming**|In the hospital world there are several complex combinatory problems, and
solving these problems is important to increase the degree of patients'
satisfaction and the quality of care offered. The problems in the healthcare
are complex since to solve them several constraints and different type of
resources should be taken into account. Moreover, the solutions must be
evaluated in a small amount of time to ensure the usability in real scenarios.
We plan to propose solutions to these kind of problems both expanding already
tested solutions and by modelling solutions for new problems, taking into
account the literature and by using real data when available. Solving these
kind of problems is important but, since the European Commission established
with the General Data Protection Regulation that each person has the right to
ask for explanation of the decision taken by an AI, without developing
Explainability methodologies the usage of AI based solvers e.g. those based on
Answer Set programming will be limited. Thus, another part of the research will
be devoted to study and propose new methodologies for explaining the solutions
obtained.|Marco Mochi et.al.|[2208.03099v1](http://arxiv.org/abs/2208.03099v1)|null|
|**2022-07-26**|**AI Approaches in Processing and Using Data in Personalized Medicine**|In modern dynamic constantly developing society, more and more people suffer
from chronic and serious diseases and doctors and patients need special and
sophisticated medical and health support. Accordingly, prominent health
stakeholders have recognized the importance of development of such services to
make patients life easier. Such support requires the collection of huge amount
of patients complex data like clinical, environmental, nutritional, daily
activities, variety of data from smart wearable devices, data from clothing
equipped with sensors etc. Holistic patients data must be properly aggregated,
processed, analyzed, and presented to the doctors and caregivers to recommend
adequate treatment and actions to improve patients health related parameters
and general wellbeing. Advanced artificial intelligence techniques offer the
opportunity to analyze such big data, consume them, and derive new knowledge to
support personalized medical decisions. New approaches like those based on
advanced machine learning, federated learning, transfer learning, explainable
artificial intelligence open new paths for more quality use of health and
medical data in future. In this paper, we will present some crucial aspects and
characteristic examples in the area of application of a range of artificial
intelligence approaches in personalized medical decisions.|Mirjana Ivanovic et.al.|[2208.04698v1](http://arxiv.org/abs/2208.04698v1)|null|
|**2022-07-22**|**TRUST-LAPSE: An Explainable and Actionable Mistrust Scoring Framework for Model Monitoring**|Continuous monitoring of trained ML models to determine when their
predictions should and should not be trusted is essential for their safe
deployment. Such a framework ought to be high-performing, explainable, post-hoc
and actionable. We propose TRUST-LAPSE, a "mistrust" scoring framework for
continuous model monitoring. We assess the trustworthiness of each input
sample's model prediction using a sequence of latent-space embeddings.
Specifically, (a) our latent-space mistrust score estimates mistrust using
distance metrics (Mahalanobis distance) and similarity metrics (cosine
similarity) in the latent-space and (b) our sequential mistrust score
determines deviations in correlations over the sequence of past input
representations in a non-parametric, sliding-window based algorithm for
actionable continuous monitoring. We evaluate TRUST-LAPSE via two downstream
tasks: (1) distributionally shifted input detection, and (2) data drift
detection. We evaluate across diverse domains - audio and vision using public
datasets and further benchmark our approach on challenging, real-world
electroencephalograms (EEG) datasets for seizure detection. Our latent-space
mistrust scores achieve state-of-the-art results with AUROCs of 84.1 (vision),
73.9 (audio), and 77.1 (clinical EEGs), outperforming baselines by over 10
points. We expose critical failures in popular baselines that remain
insensitive to input semantic content, rendering them unfit for real-world
model monitoring. We show that our sequential mistrust scores achieve high
drift detection rates; over 90% of the streams show < 20% error for all
domains. Through extensive qualitative and quantitative evaluations, we show
that our mistrust scores are more robust and provide explainability for easy
adoption into practice.|Nandita Bhaskhar et.al.|[2207.11290v2](http://arxiv.org/abs/2207.11290v2)|[link](https://github.com/nanbhas/trustlapse)|
|**2022-07-12**|**Revealing Unfair Models by Mining Interpretable Evidence**|The popularity of machine learning has increased the risk of unfair models
getting deployed in high-stake applications, such as justice system,
drug/vaccination design, and medical diagnosis. Although there are effective
methods to train fair models from scratch, how to automatically reveal and
explain the unfairness of a trained model remains a challenging task. Revealing
unfairness of machine learning models in interpretable fashion is a critical
step towards fair and trustworthy AI. In this paper, we systematically tackle
the novel task of revealing unfair models by mining interpretable evidence
(RUMIE). The key idea is to find solid evidence in the form of a group of data
instances discriminated most by the model. To make the evidence interpretable,
we also find a set of human-understandable key attributes and decision rules
that characterize the discriminated data instances and distinguish them from
the other non-discriminated data. As demonstrated by extensive experiments on
many real-world data sets, our method finds highly interpretable and solid
evidence to effectively reveal the unfairness of trained models. Moreover, it
is much more scalable than all of the baseline methods.|Mohit Bajaj et.al.|[2207.05811v1](http://arxiv.org/abs/2207.05811v1)|null|
|**2022-07-11**|**From Correlation to Causation: Formalizing Interpretable Machine Learning as a Statistical Process**|Explainable AI (XAI) is a necessity in safety-critical systems such as in
clinical diagnostics due to a high risk for fatal decisions. Currently,
however, XAI resembles a loose collection of methods rather than a well-defined
process. In this work, we elaborate on conceptual similarities between the
largest subgroup of XAI, interpretable machine learning (IML), and classical
statistics. Based on these similarities, we present a formalization of IML
along the lines of a statistical process. Adopting this statistical view allows
us to interpret machine learning models and IML methods as sophisticated
statistical tools. Based on this interpretation, we infer three key questions,
which we identify as crucial for the success and adoption of IML in
safety-critical settings. By formulating these questions, we further aim to
spark a discussion about what distinguishes IML from classical statistics and
what our perspective implies for the future of the field.|Lukas Klein et.al.|[2207.04969v1](http://arxiv.org/abs/2207.04969v1)|null|
|**2022-07-09**|**Explainable AI (XAI) in Biomedical Signal and Image Processing: Promises and Challenges**|Artificial intelligence has become pervasive across disciplines and fields,
and biomedical image and signal processing is no exception. The growing and
widespread interest on the topic has triggered a vast research activity that is
reflected in an exponential research effort. Through study of massive and
diverse biomedical data, machine and deep learning models have revolutionized
various tasks such as modeling, segmentation, registration, classification and
synthesis, outperforming traditional techniques. However, the difficulty in
translating the results into biologically/clinically interpretable information
is preventing their full exploitation in the field. Explainable AI (XAI)
attempts to fill this translational gap by providing means to make the models
interpretable and providing explanations. Different solutions have been
proposed so far and are gaining increasing interest from the community. This
paper aims at providing an overview on XAI in biomedical data processing and
points to an upcoming Special Issue on Deep Learning in Biomedical Image and
Signal Processing of the IEEE Signal Processing Magazine that is going to
appear in March 2022.|Guang Yang et.al.|[2207.04295v1](http://arxiv.org/abs/2207.04295v1)|null|
|**2022-07-06**|**Towards the Use of Saliency Maps for Explaining Low-Quality Electrocardiograms to End Users**|When using medical images for diagnosis, either by clinicians or artificial
intelligence (AI) systems, it is important that the images are of high quality.
When an image is of low quality, the medical exam that produced the image often
needs to be redone. In telemedicine, a common problem is that the quality issue
is only flagged once the patient has left the clinic, meaning they must return
in order to have the exam redone. This can be especially difficult for people
living in remote regions, who make up a substantial portion of the patients at
Portal Telemedicina, a digital healthcare organization based in Brazil. In this
paper, we report on ongoing work regarding (i) the development of an AI system
for flagging and explaining low-quality medical images in real-time, (ii) an
interview study to understand the explanation needs of stakeholders using the
AI system at OurCompany, and, (iii) a longitudinal user study design to examine
the effect of including explanations on the workflow of the technicians in our
clinics. To the best of our knowledge, this would be the first longitudinal
study on evaluating the effects of XAI methods on end-users -- stakeholders
that use AI systems but do not have AI-specific expertise. We welcome feedback
and suggestions on our experimental setup.|Ana Lucic et.al.|[2207.02726v1](http://arxiv.org/abs/2207.02726v1)|null|
|**2022-06-30**|**Why we do need Explainable AI for Healthcare**|The recent spike in certified Artificial Intelligence (AI) tools for
healthcare has renewed the debate around adoption of this technology. One
thread of such debate concerns Explainable AI and its promise to render AI
devices more transparent and trustworthy. A few voices active in the medical AI
space have expressed concerns on the reliability of Explainable AI techniques,
questioning their use and inclusion in guidelines and standards. Revisiting
such criticisms, this article offers a balanced and comprehensive perspective
on the utility of Explainable AI, focusing on the specificity of clinical
applications of AI and placing them in the context of healthcare interventions.
Against its detractors and despite valid concerns, we argue that the
Explainable AI research program is still central to human-machine interaction
and ultimately our main tool against loss of control, a danger that cannot be
prevented by rigorous clinical validation alone.|Giovanni Cinà et.al.|[2206.15363v1](http://arxiv.org/abs/2206.15363v1)|null|
|**2022-06-09**|**Process Knowledge-Infused AI: Towards User-level Explainability, Interpretability, and Safety**|AI systems have been widely adopted across various domains in the real world.
However, in high-value, sensitive, or safety-critical applications such as
self-management for personalized health or food recommendation with a specific
purpose (e.g., allergy-aware recipe recommendations), their adoption is
unlikely. Firstly, the AI system needs to follow guidelines or well-defined
processes set by experts; the data alone will not be adequate. For example, to
diagnose the severity of depression, mental healthcare providers use Patient
Health Questionnaire (PHQ-9). So if an AI system were to be used for diagnosis,
the medical guideline implied by the PHQ-9 needs to be used. Likewise, a
nutritionist's knowledge and steps would need to be used for an AI system that
guides a diabetic patient in developing a food plan. Second, the BlackBox
nature typical of many current AI systems will not work; the user of an AI
system will need to be able to give user-understandable explanations,
explanations constructed using concepts that humans can understand and are
familiar with. This is the key to eliciting confidence and trust in the AI
system. For such applications, in addition to data and domain knowledge, the AI
systems need to have access to and use the Process Knowledge, an ordered set of
steps that the AI system needs to use or adhere to.|Amit Sheth et.al.|[2206.13349v1](http://arxiv.org/abs/2206.13349v1)|null|
