# ReserchMaterials2023

## Favorate Papers

- Intrinsic Motivation and Automatic Curricula via Asymmetric Self-Play, ICLR 2018, "https://arxiv.org/pdf/1703.05407.pdf"

    > This paper and ["go-explore"](https://arxiv.org/pdf/1901.10995) represent one direction for reward-sparse environment exploration: create curriculum task ("near-goal" to "far-from-goal") for RL training. The curriculum is controlled by a clever teacher-student technology.

- Neural Lyapunov Control, NIPS 2019, "https://proceedings.neurips.cc/paper/2019/file/2647c1dba23bc0e0f9cdf75339e120d2-Paper.pdf"

    > One of the earliest works on deep learning for Lyapunov functions. By introducing neural network as a fexible function families for Lyapunov functions, it provides strong tools of stability certificate for non-linear systems.

- iSDF: Real-Time Neural Signed Distance Fields for Robot Perception, RSS 2022, "https://arxiv.org/pdf/2204.02296"

    > Propose SDF learning for robot learning. This can be a good starting point for vision-based safety.

- Multi-agent Reinforcement Learning in Sequential Social Dilemmas, AAMAS 2017, "https://arxiv.org/pdf/1702.03037"

    > Apply reinforcement learning to some classic games. It shows how reinforcement learning can be used as a computational tools for social science and game theory.

- Interesting object, curious agent: Learning task-agnostic exploration, NIPS 2021, "https://proceedings.neurips.cc/paper/2021/file/abe8e03e3ac71c2ec3bfb0de042638d8-Paper.pdf"

    > This paper proposes to pretrain an exploration strategy in a set of training tasks with task-agnostic rewards to gain some prior knowledge. It raises an interesting and promising direction for RL pretraining.



## Presentation Slides

> ./presentation_slides

- "FXP.pdf": about paper "Fictitious Cross-Play: Learning Global Nash Equilibria in Mixed Cooperative-Competitive Games", Zelai Xu, Yancheng Liang, Chao Yu, Yu Wang, Yi Wu, AAMAS 2023

- "DeRisk.pdf": about paper "DeRisk: An Effective Deep Learning Framework for Credit Risk Prediction", Yancheng Liang, Jiajie Zhang, Hui Li, Xiaochen Liu, Yi Hu, Yong Wu, Jinyao Zhang, Yongyan Liu, Yi Wu, In submission

- "LowSwitchRL.pdf, LowSwitchRL.pptx": about paper "Beyond Information Gain: An Empirical Benchmark for Low-Switching-Cost Reinforcement Learning", Shusheng Xu, Yancheng Liang, Yunfei Li, Simon Shaolei Du, Yi Wu, TMLR 2023

- "SystemIdentification.pdf", reading group on RSS 2022 paper "Bridging Model-based Safety and Model-free Reinforcement Learning through System Identification of Low Dimensional Linear Models"

- "iSDF.pdf", reading group on RSS 2022 paper "iSDF: Real-Time Neural Signed Distance Fields for Robot Perception"

- "SafeVision.pdf", reading group on RSS 2022 paper "Failure Prediction with Statistical Guarantees for Vision-Based Robot Control"

- "PSRO.pdf", reading group on game-theoretic RL, policy space response oracle



## Code

> ./compactDRL

Implementation of several popular deep reinforcement learning algorithms.



## Proofs

> ./proofs/MESA_climb.pdf

Main theorems of paper "MESA: Cooperative Meta-Exploration in Multi-Agent Learning through Exploiting State-Action Space Structure" to show the efficiency of different exploration strategies.