---
layout: archive
title: "My Research"
permalink: /publications/
author_profile: true
---

  My full publication list can be found on <u><a href="https://scholar.google.com/citations?hl=en&user=7ZNoHJkAAAAJ&view_op=list_works&sortby=pubdate">my Google Scholar profile</a>.</u>

<!-- {% include base_path %} -->
<!-- *: corresponding author -->

### Recent Research Highlights

Since June 2023, my research has centered on leveraging LLMs as a key use case for RL, particularly from an Inverse RL perspective. **My recent works focus on improving the general capabilities of LLMs through advanced reward modeling and alignment**. Some key insights and contributions include:
- **Necessity of Alignment in Any Application of LLMs**: Any use of LLMs can be significantly enhanced through reward modeling and alignment. Without such models, LLMs function as universal samplers, but integrating reward models allows optimization and search at inference time.
  
- **Reward Modeling from an Inverse RL Lens**: My work addresses both **data** and **model** aspects of reward modeling from an Inverse RL lens:
    - [Prompt-OIRL](https://arxiv.org/pdf/2309.06553.pdf) for improving reasoning,
    - [InverseRLignment](https://openreview.net/pdf/97e8ef1506b4477fd9dc41a76ea3257f65c66c5e.pdf) for building reward models from demonstration data,
    - [DataCOPE](https://openreview.net/forum?id=wg5y4AK6l7) for evaluating the data for reward modeling, and reward modeling reliability,
    - [ABC](https://arxiv.org/pdf/2402.00782.pdf) for addressing credit assignment via dense rewards, and
    - [RATP](https://arxiv.org/pdf/2402.07812.pdf) for modeling LLMs' thought processes as MDPs and using MCTS and reward models to optimize.

- **Order-Consistency in Reward Modeling**: We recently developed an order-consistency framework for reward modeling in alignment. This includes the first asymptotic theory justifying the use of Bradley-Terry models and classifiers, supported by large-scale experiments (over 100,000 runs). (Paper and code to be released soon.)

### Research Philosophy
  - I am equally passionate about both the scientific discovery and engineering aspects of research, believing that great research must clearly separate and achieve both types of progress. Philosophically, I view science as a process of denoising --- uncovering the **minimal rules that explain complex observations** or **finding the minimalist approach to solve a practical problem effectively** brings me great fulfillment. One of my favorite films is _The Theory of Everything_, and it is an honor to pursue my PhD at DAMTP, Cambridge --- where the story took place.
  - In my research journey, several key contributions reflect this philosophy: I introduced self-imitation as a strong control method [(PCHID)](https://proceedings.neurips.cc/paper_files/paper/2019/file/3891b14b5d8cce2fdd8dcdb4ded28f6d-Paper.pdf); demonstrated Q-learning can be highly-efficient for continuous control [(ZOSPI)](https://arxiv.org/pdf/2006.06600); early termination and recurrent networks are sufficient to solve constrained-MDPs [(ETMDP)](https://arxiv.org/pdf/2107.04200); I propose to use _linear reward shifting_ as a powerful technique for either exploration or exploitation, in both online and offline RL [(RewardShifting)](https://proceedings.neurips.cc/paper_files/paper/2022/file/f600d1a3f6a63f782680031f3ce241a7-Paper-Conference.pdf); I use tree-based reward models to streamline reward modeling research, offering high flexibility and efficient ensemble practice without heavy memory usage.

### Research Keywords
🤖️ My research focuses on **Reinforcement Learning**, a fundamental path toward _Superhuman Intelligence_. Applications of my work span across **robotics🦾, healthcare💉, finance📈, and large language models🧠**. Some of my research keywords include:

- **(Inverse) RL in Language Models** (2023-); **Inverse RL** (2021-); **Interpretable RL** (2023-); 
- **Uncertainty Quantification** (2022-); **Off-Policy Evaluation and Reward Modeling** (2022-);
- Value-Based Deep-RL (2021-); Offline RL (2021-); Optimism in Exploration (2021-); 
- Continuous Control via Supervised Learning (2020-); Goal-Conditioned RL (2020-)
- **RL for Robotics and Control** (2019-)

