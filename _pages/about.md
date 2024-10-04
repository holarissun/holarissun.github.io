---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

🚀 Hi there! I am Hao Sun, a final year PhD student at the University of Cambridge supervised by <a href="https://www.vanderschaar-lab.com/prof-mihaela-van-der-schaar/">Prof. Mihaela van der Schaar</a>, and I am working at the intersection of reinforcement learning (RL) and large language models (LLMs). During my M.Phil. study at MMLab@CUHK, I was advised by <a href="http://dahua.me/">Prof. Dahua Lin</a> and <a href="http://bzhou.ie.cuhk.edu.hk/">Prof. Bolei Zhou</a>; I received my BSc in Physics from the Yuanpei Honor Program, at Peking University, and a BSc from the Guanghua School of Management, at Peking University. My undergrad thesis was advised by <a href="https://zhouchenlin.github.io/">Prof. Zhouchen Lin</a>.


<mark> I am seeking research scientist roles, postdoctoral opportunities, and faculty positions starting in 2025.</mark>

### Recent Research Highlights
Since June 2023, I started to use LLM as a demonstrative usecase in my reality-centric reinforcement learning (RL) research, particularly from an Inverse RL perspective. I aim to enhance LLMs' general capabilities by improving reward modeling and alignment. Below are some of my recent insights and research contributions:
  1. Any LLM application can benefit from integrating reward models and alignment. Without reward models, LLMs can only function as universal samplers, but incorporating reward models enables **optimization** and **search** during inference.
  2. There are two core components in reward modeling: data and model. My work studies both from an Inverse RL perspective: [Prompt-OIRL](https://arxiv.org/pdf/2309.06553.pdf) improves reasoning with reward models, [InverseRLignment](https://openreview.net/pdf/97e8ef1506b4477fd9dc41a76ea3257f65c66c5e.pdf) builds reward models from SFT (demonstration) data. [DataCOPE](https://openreview.net/forum?id=wg5y4AK6l7) studies when reward modeling is reliable. [ABC](https://arxiv.org/pdf/2402.00782.pdf) improves the credit assignment problem in reward modeling by providing dense feedback in generation. [RATP](https://arxiv.org/pdf/2402.07812.pdf) characterize general thought processes as MDP and use MCTS with reward models to improve them.
  3. Our recent work introduces an **order-consistency framework** for reward modeling in alignment. We developed the first asymptotic theory to justify the use of Bradley-Terry models and classifiers in reward modeling, and validated these insights through very large-scale experiments (with over 100,000 runs). The paper and accompanying code will be released soon.

### Research Philosophy
  - I am equally passionate about both the scientific discovery and engineering aspects of research, believing that great research must clearly separate and achieve both types of progress. Philosophically, I view science as a process of denoising --- uncovering the **minimal rules that explain complex observations** or **finding the minimalism approach to effectively solve a practical problem** brings me great fulfillment. One of my favorite films is _The Theory of Everything_, and it is an honor to be pursuing my PhD at DAMTP, Cambridge, where the story took place.
  - In my research journey, several key contributions reflect this philosophy: I introduced self-imitation as a strong control method [(PCHID)](https://proceedings.neurips.cc/paper_files/paper/2019/file/3891b14b5d8cce2fdd8dcdb4ded28f6d-Paper.pdf); demonstrated Q-learning can be highly-efficient for continuous control [(ZOSPI)](https://arxiv.org/pdf/2006.06600); early termination and recurrent networks are sufficient to solve constrained-MDPs [(ETMDP)](https://arxiv.org/pdf/2107.04200); I propose to use _linear reward shifting_ as a powerful technique for either exploration or exploitation, in both online and offline RL [(RewardShifting)](https://proceedings.neurips.cc/paper_files/paper/2022/file/f600d1a3f6a63f782680031f3ce241a7-Paper-Conference.pdf); I use tree-based reward models to streamline reward modeling research, offering high flexibility and efficient ensemble practice without heavy memory usage.

### Research Keywords
🤖️ My research focuses on **Reinforcement Learning** and I believe it paves the only way to *Superhuman Intelligence*. My previous work on reinforcement learning has been applied to reality-centric applications like **robotics🦾, healthcare💉, finance📈, and large language models🧠**. My research keywords during the past years include:
- **(Inverse) RL in Language Models** (2023-); **Inverse RL** (2021-); **Interpretable RL** (2023-); 
- **Uncertainty Quantification** (2022-); **Off-Policy Evaluation and Reward Modeling** (2022-);
- Value-Based Deep-RL (2021-); Offline RL (2021-); Optimism in Exploration (2021-); 
- Continuous Control via Supervised Learning (2020-); Goal-Conditioned RL (2020-)
- **RL in Robotics** (2019-)



News
======
📄 (2024.09) [DataCOPE](https://openreview.net/forum?id=wg5y4AK6l7) is accepted by the Journal of Data-Centric Machine Learning Research (DMLR). <br>
📄 (2024.08) Attending RLC at Amherst. Presenting [InverseRLignment](https://openreview.net/pdf/97e8ef1506b4477fd9dc41a76ea3257f65c66c5e.pdf) at the RL beyond reward workshop with a score 9. <br>
📄 (2024.05) [InverseRLignment](https://openreview.net/pdf/97e8ef1506b4477fd9dc41a76ea3257f65c66c5e.pdf) is online, it **builds reward models from SFT data**. <br>
📄 (2024.05) [ABC](https://arxiv.org/pdf/2402.00782.pdf) is accepted by ICML 2024. <br>
📄 (2024.03) I wrote <a href="https://arxiv.org/abs/2403.12017">an article </a> arguing that **Supervised Fine Tuning is Inverse Reinforcement Learning**! <br>
💬 (2024.03) **Prompt-OIRL** and **RATP** are featured at the [Inspiration Exchange](https://www.vanderschaar-lab.com/engagement-sessions/inspiration-exchange/), recording is <a href="https://www.youtube.com/watch?v=NYYYbQ_EN30&ab_channel=vanderSchaarLab"> online </a>. <br>
📄 (2024.02) **2 RL+LLM papers** are online! [ABC](https://arxiv.org/pdf/2402.00782.pdf) uses the attention mechanism to solve the credit assignment problem in RLHF; [RATP](https://arxiv.org/pdf/2402.07812.pdf) uses MCTS to enhance the reasoning ability of LLMs with external documents<br>
📄 (2024.01) **1 RL+LLM paper** [Prompt-OIRL](https://arxiv.org/pdf/2309.06553.pdf) is accepted by ICLR 2024! It uses Inverse RL to Evaluate and Optimize Prompts for LLMs<br>
💬 (2024.01) Invited talk on **RLHF** at the [Intuit AI Research Forum](https://www.intuit.com/technology/). <a href="https://holarissun.github.io/files/RLHF_Dec.pdf"> slide </a> <br>
💬 (2023.12) Invited talk on **RLHF** at the [Likelihood Lab](http://www.maxlikelihood.cn/) <a href="https://holarissun.github.io/files/RLHF_Dec.pdf"> slide </a> <br>
💬 (2023.11) Invited talk on **RLHF** at the [CoAI group, THU.](https://huggingface.co/thu-coai) Discussion on the **problems of the Bradley-Terry Model** is included. <a href="https://holarissun.github.io/files/RLHF_Nov.pdf"> slide  </a> <br>
📄 (2023.10) [Prompt-OIRL](https://arxiv.org/pdf/2309.06553.pdf) is selected as an **oral presentation** at the NeurIPS 2023 ENLSP workshop!<br>
📄 (2023.10) I wrote <a href="https://arxiv.org/abs/2310.06147">an article </a> on **RLHF** to share my thoughts as an RL researcher in the Era of LLMs. <br>
📄 (2023.9) **2 papers** on [Interpretable Offline RL](https://arxiv.org/abs/2310.07747) and [Interpretable Uncertainty Quantification](https://arxiv.org/abs/2207.05161) are accepted by NeurIPS 2023. <br>
💬 (2023.9) Invited talk on **"Reinforcement Learning in the Era of LLMs"** at [Kuaishou Research](https://usrdc.kuaishou.com/). <a href="https://holarissun.github.io/files/RLHF_Kuai_final.pdf"> slide is online </a>  <br>
📄 (2023.2) **2 papers** are accepted by AISTATS 2023. <br>
💬 (2022.11) Invited talk on value-based DRL at HW Cloud Research. <a href="https://sites.google.com/view/rewardshaping"> slide is online </a>  <br>
📄 (2022.9) **1 paper** on [Value-Based DeepRL](https://proceedings.neurips.cc/paper_files/paper/2022/file/f600d1a3f6a63f782680031f3ce241a7-Paper-Conference.pdf) is accepted by NeurIPS 2022. 2 papers are presented at the FMDM workshop, and 2 papers are presented at the DeepRL workshop. <br>
📄 (2022.1) **1 paper** on [Offline GCRL](https://arxiv.org/abs/2202.04478) is accepted by ICLR 2022. <be>



🙋 More About Me
----
I love the scientific part of my research more than the engineering part. I deeply value the 'aha' moments in research and have great respect for studies that evoke such moments of insight. I firmly believe in Goodhart's Law: publications should never be the goal but rather the byproduct of a genuine pursuit of truth. Writing a paper is a way to share the joyful moments of exploration. 
In my spare time, I am passionate about embracing nature. I'm a climber🧗, a (big mountain) snowboarder🏂 and pow-hunter🌊, a (all mountain) skier⛷️ (slope id = email). I find great fulfillment in exploring both the physical and intellectual worlds.

🤝 I'm open to collaborations for more sparks of 'aha' moments. Please drop me an email if you find my work interesting. Let us push RL closer to superhuman intelligence! Here are some topics I'm actively working on:
- **Inverse and Forward Alignment** in Language Modeling: Multi-Objective, Meta-Learn, Uncertainty
- Data-Centric Perspective of **Reward Modeling**


<a href="https://clustrmaps.com/site/1bysk"  title="Visit tracker"><img src="//www.clustrmaps.com/map_v2.png?d=RtOCs2DxbgCleb2bwL7ZaU9kONDpyPNXGY_Guo_CtaM&cl=ffffff" /></a>

<!--

Education
======
 <span style="font-weight: bold;"> 💪 Ph.D., van der Schaar Lab, University of Cambridge, Jun.2025 (expected)<br>
  </span>
  - Research Topic: Reality-Centric Deep Reinforcement Learning

  <span style="font-weight: bold;"> 🎓 M.Phil., MMLab, The Chinese University of Hong Kong, Sep.2021.<br>
  </span>
  - Thesis:
    <a href="https://github.com/2Groza/MPhil_Thesis/blob/main/MPhil_Thesis.pdf">Toward Practical Deep Reinforcement Learning: Sample-Efficient Self-Supervised Continuous Control</a><br>
  
  - Slide can be found at: 
    <a href="https://github.com/2Groza/MPhil_Thesis/blob/main/Toward%20Practical%20Reinforcement%20Learning.pptx">Slide</a><br>
  <p class="item_desc"></p>
  
  
<span style="font-weight: bold;"> 👨‍🎓 B.Sc., School of Physics & Yuanpei College, Peking University, Jul.2018.<br>
</span>


I worked as an RA at the LCDM group@UIUC. I used to work on cosmology gravitational lensing in Prof.  and Ultracold atom during my undergrad research.
-->
