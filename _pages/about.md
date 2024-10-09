---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

🚀 **Hi there!** I am Hao Sun, a final-year Ph.D. student at the University of Cambridge, supervised by [Prof. Mihaela van der Schaar](https://www.vanderschaar-lab.com/prof-mihaela-van-der-schaar/), working at the intersection of reinforcement learning (RL) and large language models (LLMs). During my M.Phil. study at [MMLab@CUHK](https://mmlab.ie.cuhk.edu.hk/), I was advised by [Prof. Dahua Lin](http://dahua.site/) and [Prof. Bolei Zhou](https://boleizhou.github.io/). I hold a B.Sc. in Physics from the Yuanpei College at Peking University, and a B.Sc. from the Guanghua School of Management. My undergraduate thesis was supervised by [Prof. Zhouchen Lin](https://zhouchenlin.github.io/).

<mark> I am seeking research scientist and academic positions starting in 2025. </mark>

# About My Research
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



News!
======
📄 (2024.09) Our [Data Centric Reward Modeling](https://openreview.net/forum?id=wg5y4AK6l7) paper is accepted by the Journal of Data-Centric Machine Learning Research (DMLR). <br>
📄 (2024.08) [InverseRLignment](https://openreview.net/pdf/97e8ef1506b4477fd9dc41a76ea3257f65c66c5e.pdf) is presented at the RL beyond reward workshop (accepted with score 9) at the 1-st RLC. <br>
📄 (2024.05) [InverseRLignment](https://openreview.net/pdf/97e8ef1506b4477fd9dc41a76ea3257f65c66c5e.pdf) is online, it **builds reward models from SFT data**. <br>
📄 (2024.05) Our [Dense Reward Model](https://arxiv.org/pdf/2402.00782.pdf) paper is accepted by ICML 2024. <br>
📄 (2024.03) I wrote <a href="https://arxiv.org/abs/2403.12017">an article </a> arguing that **Supervised Fine Tuning is Inverse Reinforcement Learning**! <br>
💬 (2024.03) **Prompt-OIRL** and **RATP** are featured at the [Inspiration Exchange](https://www.vanderschaar-lab.com/engagement-sessions/inspiration-exchange/), recording is <a href="https://www.youtube.com/watch?v=NYYYbQ_EN30&ab_channel=vanderSchaarLab"> online </a>. <br>
📄 (2024.02) **2 RL+LLM papers** are online! [ABC](https://arxiv.org/pdf/2402.00782.pdf) uses the attention mechanism to solve the credit assignment problem in RLHF; [RATP](https://arxiv.org/pdf/2402.07812.pdf) uses MCTS to enhance the reasoning ability of LLMs with external documents<br>
📄 (2024.01) **1 RL+LLM paper** is accepted by ICLR 2024! [Prompt-OIRL](https://arxiv.org/pdf/2309.06553.pdf) uses Inverse RL to Evaluate and Optimize Prompts for Reasoning.<br>
💬 (2024.01) Invited talk on **RLHF** at the [Intuit AI Research Forum](https://www.intuit.com/technology/). <a href="https://holarissun.github.io/files/RLHF_Dec.pdf"> slide </a> <br>
💬 (2023.12) Invited talk on **RLHF** at the [Likelihood Lab](http://www.maxlikelihood.cn/) <a href="https://holarissun.github.io/files/RLHF_Dec.pdf"> slide </a> <br>
💬 (2023.11) Invited talk on **RLHF** at the [CoAI group, THU.](https://huggingface.co/thu-coai). <a href="https://holarissun.github.io/files/RLHF_Nov.pdf"> slide  </a> <br>
📄 (2023.10) [Prompt-OIRL](https://arxiv.org/pdf/2309.06553.pdf) is selected as an **oral presentation** at the NeurIPS 2023 ENLSP workshop!<br>
📄 (2023.10) I wrote <a href="https://arxiv.org/abs/2310.06147">an article </a> on **RLHF** to share my thoughts as an RL researcher in the Era of LLMs. <br>
📄 (2023.9) **2 papers** on [Interpretable Offline RL](https://arxiv.org/abs/2310.07747) and [Interpretable Uncertainty Quantification](https://arxiv.org/abs/2207.05161) are accepted by NeurIPS 2023. <br>
💬 (2023.9) Invited talk on **"Reinforcement Learning in the Era of LLMs"** at [Kuaishou Research](https://usrdc.kuaishou.com/). <a href="https://holarissun.github.io/files/RLHF_Kuai_final.pdf"> slide is online </a>  <br>
📄 (2023.2) **2 papers** are accepted by AISTATS 2023. <br>
💬 (2022.11) Invited talk on value-based DRL at HW Cloud Research. <a href="https://sites.google.com/view/rewardshaping"> slide is online </a>  <br>
📄 (2022.9) **1 paper** on [Value-Based DeepRL](https://proceedings.neurips.cc/paper_files/paper/2022/file/f600d1a3f6a63f782680031f3ce241a7-Paper-Conference.pdf) is accepted by NeurIPS 2022. 2 papers are presented at the FMDM workshop, and 2 papers are presented at the DeepRL workshop. <br>
📄 (2022.1) **1 paper** on [Offline GCRL](https://arxiv.org/abs/2202.04478) is accepted by ICLR 2022. <be>



🙋 Me, in my life :) 
=====

In my spare time, I am passionate about embracing nature. I'm a climber🧗, a big mountain snowboarder🏂 and pow-hunter🏔️, an all mountain skier⛷️ (slope id = email). I find great fulfillment in exploring both the physical and intellectual worlds. 

![me in my life :) ](/images/meatlife.png)

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
