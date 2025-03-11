---
layout: archive
title: "My Research"
permalink: /publications/
author_profile: true
---

  My full publication list can be found on <u><a href="https://scholar.google.com/citations?hl=en&user=7ZNoHJkAAAAJ&view_op=list_works&sortby=pubdate">my Google Scholar profile</a>.</u>

<!-- {% include base_path %} -->
<!-- *: corresponding author -->

### Research Highlights

My RL research is driven by the belief that superhuman intelligence can only arise from interacting with the environment.
In my previous research, I’ve explored the topics of sparse-reward RL, reward shifting in value-based deep RL, and explainability, leading to 3 NeurIPS publications.
#### Deep Reinforcement Learning Research
I study novel RL algorithms by drawing inspirations from human learning, the foundations of value-based deep RL, and how to learn from RL policies through interpretable policy learning.

- [NeurIPS'2019 **Spotlight** (**top 2.4%**)] [Introducing a self-imitate supervised learning approach for sparse-reward multi-goal RL.](https://proceedings.neurips.cc/paper_files/paper/2019/file/3891b14b5d8cce2fdd8dcdb4ded28f6d-Paper.pdf) This paper is a seminal work for the line of supervised-learning-based goal reaching RL papers (e.g., GCSL from UC Berkeley).
- [NeurIPS'2022] [Investigating reward shifting (shaping) in value-based deep RL.](https://openreview.net/pdf?id=iCxRsZcVVAH) We studied how the simplest form of reward shaping --- reward shifting --- changes learning behaviors of value-based deep RL algorithms (e.g., DQN, TD3). We highlight that a simple reward shifting can be applied to boost exploration or exploitation.
- [NeurIPS'2023] [Interpretable offline RL algorithm.](https://proceedings.neurips.cc/paper_files/paper/2023/file/096b1019463f34eb241e87cfce8dfe16-Paper-Conference.pdf) We introduced an interpretable offline RL method that can be used to explain decisions through a corpus of examples.

In the LLM era (since June 2023), I see great potential in these models as an interface for understanding machine intelligence. To advance their abilities beyond imitation and memorization, reinforcement learning is an essential technique. Since many real-world tasks lack well-defined reward signals, we must learn those reward models from data. My research on LLM alignment (post-training) focuses on building reward models from diverse data sources, and is known as the Inverse Reinforcement Learning for LLM alignment:
#### Inverse RL for LLM Alignment Research
- [ICLR'2024] [Building reward models for mathematical reasoning (through prompt optimization).](https://arxiv.org/pdf/2309.06553)
- [Workshop@RLC2024] [Building reward models from demonstration data using Inverse RL.](https://arxiv.org/pdf/2405.15624)
- [ICLR'2025 **Oral** (**top 1.2%**)] [Rethinking the foundation of preference-based (embedding-based) reward modeling.](https://openreview.net/forum?id=rfdblE10qm)
- [ICML'2024] [Building dense reward models for LLM alignment.](https://arxiv.org/pdf/2402.00782)
- [DMLR'2024] [Data-centric reward modeling: Less can be more in LLM alignment.](https://openreview.net/forum?id=wg5y4AK6l7)
- [Workshop@NeurIPS'2024] [Position paper: Why do we always need reward models.](https://openreview.net/pdf?id=qpop1gQvVQ)
- [Preprint] [Active reward modeling: experimental design in preference-based reward modeling.](https://arxiv.org/pdf/2502.04354)
- [Preprint] [Embedding-based reward modeling infrastructure for GPU-free LLM alignment research.](https://arxiv.org/pdf/2502.04357)
#### This line of research has contributed to a series of tutorials at [AAAI 2025](https://underline.io/events/473/sessions?eventSessionId=19071) and (to appear at) [ACL 2025](https://2025.aclweb.org/program/tutorials/).


### Research Philosophy
  - I am equally passionate about both the scientific discovery and engineering aspects of research, believing that great research must clearly separate and achieve both types of progress. Philosophically, I view science as a process of denoising --- uncovering the **minimal rules that explain complex observations** or **finding the minimalist approach to solve a practical problem effectively** brings me great fulfillment. One of my favorite films is _The Theory of Everything_, and it is an honor to pursue my PhD at DAMTP, Cambridge --- where the story took place.
  - In my research journey, several key contributions reflect this philosophy: I introduced self-imitation as a strong control method [(PCHID)](https://proceedings.neurips.cc/paper_files/paper/2019/file/3891b14b5d8cce2fdd8dcdb4ded28f6d-Paper.pdf); demonstrated Q-learning can be highly-efficient for continuous control [(ZOSPI)](https://arxiv.org/pdf/2006.06600); early termination and recurrent networks are sufficient to solve constrained-MDPs [(ETMDP)](https://arxiv.org/pdf/2107.04200); I propose to use _linear reward shifting_ as a powerful technique for either exploration or exploitation, in both online and offline RL [(RewardShifting)](https://proceedings.neurips.cc/paper_files/paper/2022/file/f600d1a3f6a63f782680031f3ce241a7-Paper-Conference.pdf); I use tree-based reward models to streamline reward modeling research, offering high flexibility and efficient ensemble practice without heavy memory usage.

### Research Keywords
🤖️ My research focuses on **Reinforcement Learning**, a fundamental path toward _Superhuman Intelligence_. Applications of my work span across **robotics🦾, healthcare💉, finance📈, and large language models🧠**. Some of my research keywords include:

- **(Inverse) RL in Language Models** (2023-); **Inverse RL** (2021-); **Interpretable RL** (2023-); 
- **Uncertainty Quantification** (2022-); **Off-Policy Evaluation and Reward Modeling** (2022-);
- Value-Based Deep-RL (2021-); Offline RL (2021-); Optimism in Exploration (2021-); 
- Continuous Control via Supervised Learning (2020-); Goal-Conditioned RL (2020-)
- RL for Robotics and Control (2019-)

