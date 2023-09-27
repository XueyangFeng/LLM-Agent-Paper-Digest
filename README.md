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

#### Agent Memory

**[Agent Memory] Reflexion: language agents with verbal reinforcement learning**. [[Paper](https://arxiv.org/abs/2303.11366)] [[Code](https://github.com/noahshinn024/reflexion)] <img src="https://img.shields.io/badge/NIPS-2023-green" alt="license"> <br>
**TLDR**: Reflexion maintains the feedback signal from the tasks in long-term and short-term memory buffers for reflection to make better decisions on subsequent trials. (利用长短期记忆维护反馈并进行反思) 

#### Agent Planning

**[Agent Planning] Describe, Explain, Plan and Select: Interactive Planning with LLMs Enables Open-World Multi-Task Agents**.  [[Paper](https://arxiv.org/abs/2302.01560)] [[Code](https://github.com/CraftJarvis/MC-Planner)] <img src="https://img.shields.io/badge/NIPS-2023-green" alt="license"> <br>
**TLDR**: LLM-powered agent could get better error correction through feedback, while introducing a goal selector to rank and improve planning based on predicted completion steps. (引入了任务选择器，实现了MineCraft中的多任务代理) 

**[Agent Planning] Large Language Models as Commonsense Knowledge for Large-Scale Task Planning**.  [[Paper](https://arxiv.org/abs/2305.14078)]  <img src="https://img.shields.io/badge/NIPS-2023-green" alt="license"> <br>
**TLDR**: Using Large Language Models (LLMs) as Common Sense World Models and Heuristic Strategies to Solve Complex Task Planning Prob. (利用大型语言模型（LLMs）作为常识世界模型和启发式策略来解决复杂任务规划问题) 

**[Agent Planning] Tree of Thoughts: Deliberate Problem Solving with Large Language Models**.   [[Paper](https://arxiv.org/abs/2305.10601)]  [[Code](https://github.com/ysymyth/tree-of-thought-llm)]  <img src="https://img.shields.io/badge/NIPS-2023-green" alt="license"> <br>
**TLDR**: We introduce a new framework for language model inference, "Tree of Thoughts" (ToT), which generalizes over the popular "Chain of Thought" approach to prompting language models, and enables exploration over coherent units of text ("thoughts") that serve as intermediate steps toward problem solving. (鼓励大模型考虑多个不同的推理路径) 
 
#### Agent Action

**[Agent Action] GPT4Tools: Teaching Large Language Model to Use Tools via Self-instruction**.  [[Paper](https://arxiv.org/abs/2305.18752)]  [[Code](https://github.com/AILab-CVC/GPT4Tools)]  <img src="https://img.shields.io/badge/NIPS-2023-green" alt="license"> <br>
**TLDR**:  We propose theGPT4Tools based on self-instruct to enable open-source LLMs, such as LLaMA andOPT, to use tools. It generates an instruction-following dataset by promptingan advanced teacher with various multi-modal contexts. By using the Low-RankAdaptation (LoRA) optimization, our approach facilitates the open-source LLMsto solve a range of visual problems, including visual comprehension and imagegeneration. (GPT生成工具调用数据集来微调开源模型)

### Agent Application

#### Agent in Social Science

#### Agent in Natural Science

#### Agent in Engineer

### Agent Evaluation

**On the Planning Abilities of Large Language Models - A Critical Investigation**.  (2023-NIPS)



**SwiftSage: A Generative Agent with Fast and Slow Thinking for Complex Interactive Tasks**.  (2023-NIPS)

**CAMEL: Communicative Agents for “Mind” Exploration of Large Scale Language Model Society**.  (2023-NIPS)

**De novo Drug Design using Reinforcement Learning with Multiple GPT Agents**.  (2023-NIPS) 

**LLMs for Semi-Automated Data Science: Introducing CAAFE for Context-Aware Automated Feature Engineering**.  (2023-NIPS)

**Large Language Models Are Implicitly Topic Models: Explaining and Finding Good Demonstrations for In-Context Learning**.  (2023-NIPS)

**SheetCopilot: Bringing Software Productivity to the Next Level through Large Language Models**.  (2023-NIPS)

**Chameleon: Plug-and-Play Compositional Reasoning with Large Language Models**.  (2023-NIPS)

**Flocks of Stochastic Parrots: Differentially Private Prompt Learning for Large Language Models**.  (2023-NIPS)

**LayoutGPT: Compositional Visual Planning and Generation with Large Language Models**.  (2023-NIPS)

**AVIS: Autonomous Visual Information Seeking with Large Language Models**.  (2023-NIPS)

**Testing the General Deductive Reasoning Capacity of Large Language Models Using OOD Examples**.  (2023-NIPS)

**Fairness-guided Few-shot Prompting for Large Language Models**.  (2023-NIPS)

**Zero-shot Visual Relation Detection via Composite Visual Cues from Large Language Models**.  (2023-NIPS)

**VisionLLM: Large Language Model is also an Open-Ended Decoder for Vision-Centric Tasks**.  (2023-NIPS)

**LayoutPrompter: Awaken the Design Ability of Large Language Models**.  (2023-NIPS)

**3D-LLM: Injecting the 3D World into Large Language Models**.  (2023-NIPS)


**MarioGPT: Open-Ended Text2Level Generation through Large Language Models**.  (2023-NIPS)

**Evaluating Cognitive Maps in Large Language Models: No Emergent Planning**.  (2023-NIPS)

**Grammar Prompting for Domain-Specific Language Generation with Large Language Models**.  (2023-NIPS)

**Using Large Language Model Annotations for Valid Downstream Statistical Inference in Social Science: Design-Based Semi-Supervised Learning**.  (2023-NIPS)


**Leveraging Pre-trained Large Language Models to Construct and Utilize World Models for Model-based Task Planning**.  (2023-NIPS)

**Large Language Models of Code Fail at Completing Code with Potential Bugs**.  (2023-NIPS)

**In-Context Impersonation Reveals Large Language Models' Strengths and Biases**.  (2023-NIPS)

**Meta-in-context learning in large language models**.  (2023-NIPS)

**What’s Left: Concept Grounding with Large Language Models**.  (2023-NIPS)

**Thrust: Adaptively Propels Large Language Models with External Knowledge**.  (2023-NIPS)

**Large Language Model Is Semi-Parametric Reinforcement Learning Agent**.  (2023-NIPS)

**Large Language Models can Implement Policy Iteration**.  (2023-NIPS)

### Contributors

Xueyang Feng: `NIPS'23`

Lei Wang: `NIPS'23`

Chen Ma: `NIPS'23`
