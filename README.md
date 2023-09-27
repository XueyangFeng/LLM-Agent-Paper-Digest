# Awesome-LLM-Agent-Papers
For benefiting the research community and promoting LLM-powered agent direction, we organize papers related to LLM-powered agent that published on top conferences recently. Currently, our repository has included:
- `2023`: `NIPS`

We are glad for pointing out our misunderstandings, and welcome to contribute to this repository!

#### What's new:
- 2023/9/26	We add papers from `NIPS'23`.

## Contents

- [Agent Building](#Agent-Building)
  - [Agent Memory](#Agent-Memory)
  - [Agent Planning](#Agent-Planning)
  - [Agent Action](#Agent-Action)
- [Agent Application](#Agent-Application)
  - [Agent in Social Science](#Agent-in-Social-Science)
  - [Agent in Natural Science](#Agent-in-Natural-Science)
  - [Agent in Engineering](#Agent-in-Engineering)
- [Agent Evaluation](#Agent-Evaluation)


### Agent Building

#### Agent Profile

**[Agent Profile] CAMEL: Communicative Agents for “Mind” Exploration of Large Scale Language Model Society**.   [[Paper](https://arxiv.org/abs/2303.17760)]  [[Code](https://github.com/camel-ai/camel)]  <img src="https://img.shields.io/badge/NIPS-2023-green" alt="license"> <br>
**TLDR**: The paper presents CAMEL, a framework that fosters autonomous cooperation between communicative agents. Using a role-playing approach, it employs inception prompting to guide chat agents in tasks, aligning with human intentions. (通过角色扮演提高Agent能力)


#### Agent Memory

**[Agent Memory] Reflexion: language agents with verbal reinforcement learning**. [[Paper](https://arxiv.org/abs/2303.11366)] [[Code](https://github.com/noahshinn024/reflexion)] <img src="https://img.shields.io/badge/NIPS-2023-green" alt="license"> <br>
**TLDR**: Reflexion maintains the feedback signal from the tasks in long-term and short-term memory buffers for reflection to make better decisions on subsequent trials. (利用长短期记忆维护反馈并进行反思) 

**[Agent Memory] SwiftSage: A Generative Agent with Fast and Slow Thinking for Complex Interactive Tasks**. [[Paper](https://arxiv.org/abs/2305.17390)] [[Code](https://github.com/yuchenlin/SwiftSage)] <img src="https://img.shields.io/badge/NIPS-2023-green" alt="license"> <br>
**TLDR**: This paper introduces a novel agent framework called SWIFTSAGE, which combines a fast and intuitive thinking module, SWIFT, with a deliberate thinking module, SAGE, to optimize action planning in complex interactive reasoning tasks. SWIFT is a fine-tuned small encoder-decoder LM, while SAGE employs LLMs like GPT-4 for subgoal planning and grounding. (结合小模型快速思考和大模型深思熟虑) 

**[Agent Memory] Large Language Model Is Semi-Parametric Reinforcement Learning Agent**.   [[Paper](https://arxiv.org/abs/2306.07929)] [[Code](https://github.com/noahshinn024/reflexion)] <img src="https://img.shields.io/badge/NIPS-2023-green" alt="license"> <br>
**TLDR**: By equipping the LLM with a longterm experience memory, REMEMBERER is capable of exploiting the experiences from the past episodes even for different task goals, which excels an LLM-based agent with fixed exemplars or equipped with a transient working memory. (为LLM配备长期经验记忆，构建一个半参数化的强化学习agent) 


#### Agent Planning

**[Agent Planning] Describe, Explain, Plan and Select: Interactive Planning with LLMs Enables Open-World Multi-Task Agents**.  [[Paper](https://arxiv.org/abs/2302.01560)] [[Code](https://github.com/CraftJarvis/MC-Planner)] <img src="https://img.shields.io/badge/NIPS-2023-green" alt="license"> <br>
**TLDR**: LLM-powered agent could get better error correction through feedback, while introducing a goal selector to rank and improve planning based on predicted completion steps. (引入了任务选择器，实现了MineCraft中的多任务代理) 

**[Agent Planning] Large Language Models as Commonsense Knowledge for Large-Scale Task Planning**.  [[Paper](https://arxiv.org/abs/2305.14078)]  <img src="https://img.shields.io/badge/NIPS-2023-green" alt="license"> <br>
**TLDR**: Using Large Language Models (LLMs) as Common Sense World Models and Heuristic Strategies to Solve Complex Task Planning Prob. (利用大型语言模型（LLMs）作为常识世界模型和启发式策略来解决复杂任务规划问题) 

**[Agent Planning] Tree of Thoughts: Deliberate Problem Solving with Large Language Models**.   [[Paper](https://arxiv.org/abs/2305.10601)]  [[Code](https://github.com/ysymyth/tree-of-thought-llm)]  <img src="https://img.shields.io/badge/NIPS-2023-green" alt="license"> <br>
**TLDR**: we introduce a new framework for language model inference, "Tree of Thoughts" (ToT), which generalizes over the popular "Chain of Thought" approach to prompting language models, and enables exploration over coherent units of text ("thoughts") that serve as intermediate steps toward problem solving. (鼓励大模型考虑多个不同的推理路径) 

**[Agent Planning] Leveraging Pre-trained Large Language Models to Construct and Utilize World Models for Model-based Task Planning**.   [[Paper](https://arxiv.org/abs/2305.14909)]  [[Code](https://github.com/GuanSuns/LLMs-World-Models-for-Planning)]  <img src="https://img.shields.io/badge/NIPS-2023-green" alt="license"> <br>
**TLDR**:  we introduce a novel alternative paradigm that constructs an explicit world (domain) model in planning domain definition language (PDDL) and then uses it to plan with sound domain-independent planners.  (大模型+外部规划器) 

**[Agent Planning] Large Language Models can Implement Policy Iteration**.  [[Paper](https://arxiv.org/abs/2210.03821v2)]  <img src="https://img.shields.io/badge/NIPS-2023-green" alt="license"> <br>
**TLDR**:  In this work, we present an algorithm, ICPI, that learns to perform RL tasks without expert demonstrations or gradients. Instead we present a policy-iteration method in which the prompt content is the entire locus of learning. ICPI iteratively updates the contents of the prompt from which it derives its policy through trial-and-error interaction with an RL environment. (LLM作为model-base强化学习的world-model和policy)


#### Agent Action

**[Agent Action] GPT4Tools: Teaching Large Language Model to Use Tools via Self-instruction**.   [[Paper](https://arxiv.org/abs/2305.18752)]  [[Code](https://github.com/AILab-CVC/GPT4Tools)] <img src="https://img.shields.io/badge/NIPS-2023-green" alt="license"> <br>
**TLDR**: we propose the GPT4Tools based on self-instruct to enable open-source LLMs, such as LLaMA and OPT, to use tools. It generates an instruction-following dataset by prompting an advanced teacher with various multi-modal contexts. (用gpt生成工具使用记录，再用LoRA微调开源模型) 

**[Agent Action] AVIS: Autonomous Visual Information Seeking with Large Language Models**.  [[Paper](https://arxiv.org/abs/2306.08129v2)]  <img src="https://img.shields.io/badge/NIPS-2023-green" alt="license"> <br>
**TLDR**:  AVIS is an autonomous visual information seeking system that leverages a large language model (LLM) to dynamically strategize the utilization of external tools and to investigate their outputs, thereby acquiring the indispensable knowledge needed to provide answers to the posed questions. AVIS achieves state-of-the-art results on knowledge-intensive visual question answering benchmarks such as Infoseek and OK-VQA. (LLM动态制定使用外部工具的策略，从而获取视觉信息查询问题所需的必要知识)

### Agent Application

#### Agent in Social Science

**[Social Science] Using Large Language Model Annotations for Valid Downstream Statistical Inference in Social Science: Design-Based Semi-Supervised Learning**.  [[Paper](https://arxiv.org/abs/2306.04746)]  <img src="https://img.shields.io/badge/NIPS-2023-green" alt="license"> <br>
**TLDR**:  We present a new algorithm for using outputs from LLMs for downstream statistic alanalyses while guaranteeing statistical properties -- like asymptotic unbiasedness and proper uncertainty quantification -- which are fundamental to CSS research. (用LLM的输出进行社会科学的文档标签的下游统计分析)


#### Agent in Natural Science

**[Natural Science] De novo Drug Design using Reinforcement Learning with Multiple GPT Agents**.    <img src="https://img.shields.io/badge/NIPS-2023-green" alt="license"> <br>
**TLDR**: Awaiting publication.

#### Agent in Engineering

**[Engineering] LLMs for Semi-Automated Data Science: Introducing CAAFE for Context-Aware Automated Feature Engineering**.   [[Paper](https://arxiv.org/pdf/2305.03403.pdf)]  [[Code](https://github.com/automl/CAAFE)]  <img src="https://img.shields.io/badge/NIPS-2023-green" alt="license"> <br>
**TLDR**: This paper introduces a method called CAAFE that harnesses Large Language Models for feature engineering on tabular datasets. CAAFE iteratively generates semantically meaningful features based on dataset descriptions and provides explanations for the created features. This approach has improved performance across multiple datasets. (LLM自动优化特征工程)


**[Engineering] SheetCopilot: Bringing Software Productivity to the Next Level through Large Language Models**   [[Paper](https://arxiv.org/abs/2305.19308)]  [[Code](https://sheetcopilot-demo.github.io/)]  <img src="https://img.shields.io/badge/NIPS-2023-green" alt="license"> <br>
**TLDR**: The paper presents SheetCopilot, an agent using Large Language Models to interact with spreadsheets via natural language. It translates complex requests into actionable steps, outperforming traditional programming methods in various tasks. (Agent和电子表格交互)

**[Engineering] Zero-shot Visual Relation Detection via Composite Visual Cues from Large Language Models**.  [[Paper](https://arxiv.org/abs/2305.12476)]  <img src="https://img.shields.io/badge/NIPS-2023-green" alt="license"> <br>
**TLDR**:  We propose a novel method for zero-shot VRD: RECODE, which solves RElation detection via COmposite DEscription prompts. Specifically, RECODE first decomposes each predicate category into subject, object, and spatial components. Then, it leverages large language models (LLMs) to generate description-based prompts (or visual cues) for each component. (通过LLM给出的复合视觉线索进行零样本视觉关系检测)

**[Engineering] Zero-shot Visual Relation Detection via Composite Visual Cues from Large Language Models**.  [[Paper](https://arxiv.org/abs/2305.11175)] [[Code](https://github.com/OpenGVLab/VisionLLM)]  <img src="https://img.shields.io/badge/NIPS-2023-green" alt="license"> <br>
**TLDR**:  We present an LLM-based framework for vision-centric tasks, termed VisionLLM. This framework provides a unified perspective for vision and language tasks by treating images as a foreign language and aligning vision-centric tasks with language tasks that can be flexibly defined and managed using language instructions. An LLM-based decoder can then make appropriate predictions based on these instructions for open-ended tasks.(为以视觉为中心的任务提出了一个基于LLM的框架)

**[Engineering] 3D-LLM: Injecting the 3D World into Large Language Models**.  [[Paper](https://arxiv.org/abs/2307.12981)] [[Code](https://vis-www.cs.umass.edu/3dllm/)]  <img src="https://img.shields.io/badge/NIPS-2023-green" alt="license"> <br>
**TLDR**:  We propose to inject the 3D world into large language models and introduce a whole new family of 3D-LLMs. Specifically, 3D-LLMs can take 3D point clouds and their features as input and perform a diverse set of 3D-related tasks, including captioning, dense captioning, 3D question answering, task decomposition, 3D grounding, 3D-assisted dialog, navigation, and so on. (将3D世界注入到LLM中)

**[Engineering] Grammar Prompting for Domain-Specific Language Generation with Large Language Models**.  [[Paper](https://arxiv.org/abs/2305.19234)] <img src="https://img.shields.io/badge/NIPS-2023-green" alt="license"> <br>
**TLDR**:  
The paper explores the use of grammar prompting as a simple approach to enable large language models (LLMs) to use external knowledge and domain-specific constraints during in-context learning. The authors demonstrate that grammar prompting can enable LLMs to perform competitively on a diverse set of domain-specific language generation tasks, including semantic parsing, PDDL planning, and even molecule generation.(使用语法提示使LLMs在上下文学习期间使用外部知识和领域特定约束)


**[Engineering] What’s Left: Concept Grounding with Large Language Models**.   <img src="https://img.shields.io/badge/NIPS-2023-green" alt="license"> <br>
**TLDR**: Awaiting publication.


### Agent Evaluation
**[Agent Evaluation] Testing the General Deductive Reasoning Capacity of Large Language Models Using OOD Examples**.  [[Paper](https://arxiv.org/abs/2305.15269)]  <img src="https://img.shields.io/badge/NIPS-2023-green" alt="license"> <br>
**TLDR**:  To measure the general deductive reasoning ability of LLMs, we test on a broad set of deduction rules and measure their ability to generalize to more complex proofs from simpler demonstrations from multiple angles: depth-, width-, and compositional generalization. To facilitate systematic exploration, we construct a new synthetic and programmable reasoning dataset that enables control over deduction rules and proof complexity.  (使用OOD示例评估LLM的推理能力)

**[Agent Evaluation] Testing the General Deductive Reasoning Capacity of Large Language Models Using OOD Examples**.  <img src="https://img.shields.io/badge/NIPS-2023-green" alt="license"> <br>
**TLDR**:  
We propose CogEval, a Cognitive Science-Inspired protocol for Measurement and Evaluation for Large Language Models. Second, we use CogEval to systematically evaluate hypothesized latent abilities, cognitive maps and planning, across a number of LLMs using tasks with established construct validity and absent from LLM training sets. We find that, while LLMs show apparent competence in a few tasks with smaller graphs, evidence suggests against emergent planning capacities as they lack genuine understanding of latent task structures. (提出一种受认知科学启发的协议CogEval用于LLM的评估。)

**[Agent Evaluation] On the Planning Abilities of Large Language Models - A Critical Investigation**.   [[Paper](https://arxiv.org/abs/2302.06706)]  [[Code](https://github.com/karthikv792/LLMs-Planning)]  <img src="https://img.shields.io/badge/NIPS-2023-green" alt="license"> <br>
**TLDR**: By developing a benchmark suite based on the International Planning Competition, the study evaluates the performance of LLMs in three modes: autonomous, heuristic, and human-in-the-loop. (评估LLM的Planning能力)

**[Agent Evaluation] Large Language Models of Code Fail at Completing Code with Potential Bugs**.  [[Paper](https://arxiv.org/abs/2306.03438)] <img src="https://img.shields.io/badge/NIPS-2023-green" alt="license"> <br>
**TLDR**:  
We introduce and study the buggy-code completion problem, inspired by the realistic scenario of real-time code suggestion where the code context contains potential bugs – anti-patterns that can become bugs in the completed program. To systematically study the task, we introduce two datasets: one with synthetic bugs derived from semantics-altering operator changes (buggy-HumanEval) and one with realistic bugs derived from user submissions to coding problems (buggy-FixEval). We find that the presence of potential bugs significantly degrades the generation performance of the high-performing Code-LLMs.(引入了测试Code-LLM的buggy-code completion问题)


### Contributors

Xueyang Feng: `NIPS'23`

Lei Wang: `NIPS'23`

Chen Ma: `NIPS'23`
