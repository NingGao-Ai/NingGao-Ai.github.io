---
permalink: /
title: "Ning Gao 高宁"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I’m a second year master student from Beihang University(BUAA). My research interest includes Computer Vision, Reinforcement Learning and Large Language Models.

Please click the publication button to view my current articles and work.

Contact me: 

Email: gaoning_ai@buaa.edu.cn / aoyama7hai@gmail.com

Wechat: gn18811126103 / QQ: 1439096226

X: @Aoyama7Hai / Ins: aoyama7hai

# Works and Publications

## Reinforcement Learning & LLMs

### RL4LLM (RL Post Training)

**面向多轮用户交互智能体的多粒度强化学习范式**

**Reinforcing Real-world Service Agents: Balancing Utility and Cost in Task-oriented Dialogue** [ [PDF] ](https://arxiv.org/pdf/2602.22697)
* **Conference:** arXiv (under review), first author
* **Authors:** **Ning Gao**, ...
* **Abstract:** This work targets a key real-world challenge in multi-turn task-oriented dialogue agents: balancing user experience (utility) against the operational cost of invoking business tools/actions. We propose **InteractCS**, a cost-aware reinforcement learning framework with a **Cost-aware Multi-granularity Policy Optimization (CMPO)** algorithm. By integrating **session-level outcome utility**, **process-level credit assignment**, and a **PID Lagrangian cost controller**, the agent is guided to explore the Pareto frontier between user satisfaction and global cost constraints. Experiments in a real commercial setting and on benchmark evaluations show substantial improvements over strong SOTA baselines (e.g., **GPT-4.1**), achieving about **25%** higher utility while meeting a specified action-constraint rate.

**自进化多轮对话智能体**

**SEAD: Self-Evolving Agent for Multi-Turn Service Dialogue** [ [PDF] ](https://arxiv.org/pdf/2602.03548)
* **Conference:** arXiv (under review), co-first author
* **Authors:** ..., **Ning Gao**, ...
* **Abstract:** This work addresses the scarcity of high-quality training data for proactive multi-turn service dialogue agents. We propose **SEAD**, a self-evolving training framework in which a persona/profile controller actively adjusts the user distribution and is continuously optimized along with reinforcement learning. This self-evolution process yields stronger agents and improves task success rate by **20%** compared with other closed-source models.

### LLM4RL (RL Reward Design)

**基于LLM与树搜索构建的强化学习奖励函数设计智能体**

**RF-Agent: Automated Reward Function Design via Language Agent Tree Search** [ [PDF] ](/files/NeurIPS2025Review_RewardFunctionAgent.pdf)
* **Conference:** NeurIPS 2025 Spotlight
* **Authors:** **Ning Gao**, Xiuhui Zhang, Xingyu Jiang, Mukang You, Mohan Zhang, Yue Deng
* **Abstract:** This article addresses the difficulty of manually designing reward functions in reinforcement learning and proposes the use of an intelligent agent that combines LLM and tree search framework to achieve automatic design and optimization of reward functions. This framework further improves the quality of the generated reward function by utilizing the contextual reasoning ability brought by LLM testing and combining it with the actual performance of the generated reward function.

**LLM协助的强化学习进度奖励模型设计**

**Progress Reward Model for Reinforcement Learning via Large Language Models** [ [PDF] ](/files/NeurIPS2025Review_PRMinRLwithLLM.pdf)
* **Conference:** NeurIPS 2025 Poster
* **Authors:** Xiuhui Zhang, **Ning Gao**, Xingyu Jiang, Yihui Chen, Yuheng Pan, Mohan Zhang, Yue Deng
* **Abstract:** This article addresses the difficult optimization problem of long-range tasks in reinforcement learning, proposing the use of LLM's world knowledge for task planning and decomposition, further writing functions to judge subtask progress, and shaping a progress reward model to guide strategy learning, in order to improve strategy performance.

### DeepRL (Offline RL Method)

**基于价值对齐的离线强化学习**

**Value-aligned Behavior Cloning for Offline Reinforcement Learning via Bi-level Optimization** [ [PDF] ](/files/ICLR2025_OfflineRL.pdf)
* **Conference:** ICLR 2025 Poster
* **Authors:** Xingyu Jiang, **Ning Gao**, Xiuhui Zhang, Hongkun Dou, Yue Deng
* **Abstract:** This article aims at the problem of the lack of value alignment process in offline reinforcement learning methods such as behavior cloning, thus, a two-layer optimization design is proposed to implement a weighted behavior cloning strategy learning process, fully utilizing the value information of offline samples.

## Computer Vision (mainly Image Restoration)

**基于频率域启发的高效图像复原研究**

**Efficient Frequency-Domain Image Deraining with Contrastive Regularization** [ [PDF] ](/files/ECCV2024_Deraining.pdf)
* **Conference:** ECCV 2024 Poster
* **Authors**:**Ning Gao**, Xingyu Jiang, Xiuhui Zhang, Yue Deng
* **Abstract:** This article innovatively explores the aggregation and separability of frequency domain transformation for rain line noise, and relies on the global feature extraction inherent in the transformation to replace visual attention in achieving a more efficient Transformer architecture for rain removal tasks.

**When Fast Fourier Transform Meets Transformer for Image Restoration** [ [PDF] ](/files/ECCV2024_ImageRestoration.pdf)
* **Conference:** ECCV 2024 Poster
* **Authors:** Xingyu Jiang, Xiuhui Zhang, **Ning Gao**, Yue Deng
* **Abstract:** This article innovatively explores the prior separation of different types of degraded noise by frequency domain transformation, and uses this as an efficient feature extraction method to design an image restoration network backbone that combines frequency domain and spatial domain features.

**基于时空联合退化的3DGS的真实水下场景重建**

**Spatiotemporal Degradation-Aware 3D Gaussian Splatting for Realistic Underwater Scene Reconstruction** [ [PDF] ](/files/ACMMM2025Review_Underwater3DGS.pdf)
* **Conference:** ACMMM 2025 Poster
* **Authors:** Shaohua Liu, **Ning Gao**, Z Gu, H Dou, Y Deng, H Li
* **Abstract:** This article proposes a coupling scheme between 3DGS and physical degradation formula for underwater 3D scene reconstruction and restoration tasks. It mainly focuses on physical parameter modeling and perceptual modeling for different noises, and uses depth geometric information training to achieve new perspective synthesis of underwater and waterless scenes.
