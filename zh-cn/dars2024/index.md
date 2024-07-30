# Privileged Reinforcement and Communication Learning for Distributed, Bandwidth-limited Multi-robot Exploration

Springer's Distributed Autonomous Robotic Systems 2024 (DARS 2024).
<!--more-->
{{< figure src="/images/DARS2024/cover.jpg">}}
## 摘要
通信带宽是多机器人探索中的一个重要考虑因素，其中机器人之间的信息交换至关重要。虽然现有方法通常旨在降低通信吞吐量，但它们要么需要大量计算，要么显着降低探索效率。在这项工作中，我们提出了一种基于通信和特权强化学习的深度强化学习框架，以实现带宽消耗的显着减少，同时最小化地牺牲探索效率。具体来说，我们的方法允许机器人学习将环境中的个人信念（部分地图）中最显着的信息嵌入到固定大小的消息中。然后，机器人推理自己的信念并接收消息，以分布式探索环境，同时避免冗余工作。在此过程中，我们采用特权学习和学习注意机制为批评家（即教师）网络赋予地面实况图知识，以在训练期间有效指导政策（即学生）网络。与相关基线相比，我们的模型允许团队将通信减少多达两个数量级，同时仅牺牲总行进距离的边际 2.4%，为带宽有限场景中高效、分布式多机器人探索铺平了道路。同时我们开源了完整的<a href="https://github.com/marmotlab/Bandwidth-Limited-Multi-Robot-Exploration">代码</a>.。

## Demo
{{< figure src="/images/DARS2024/0.gif">}}

## 论文
<a href="https://arxiv.org/abs/2407.20203">arxiv</a>.
