# IR2: Implicit Rendezvous for Robotic Exploration Teams under Sparse Intermittent Connectivity

Accepted for oral presentation at the IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS 2024).
<!--more-->
{{< figure src="/images/IROS2024/cover_image_final.jpg">}}
## 摘要
信息共享对于时间敏感且现实的多机器人探索至关重要，特别是对于连接可能稀疏且间歇性的大规模环境中的小型机器人团队而言。现有方法经常通过假设不切实际的全球连接来忽略此类通信限制。其他工作考虑了限制通信范围的现实硬件限制，要求机器人保持近距离或视线以实现稳定的连接。例如，预先计划的交会方法通常效率低下，因为交会时机不佳会导致不必要的绕道，而基于追踪的方法由于其贪婪的性质，在当前状态下往往是短视的。我们提出 **$IR^2$**，一种用于多机器人探索的信息共享的深度强化学习方法。利用通过强化和课程学习训练的基于注意力的神经网络，**$IR^2$** 允许机器人推理当前决策对未来的影响。此外，我们提出了一种分层图公式来维护稀疏但信息丰富的图，使我们的方法能够扩展到大规模环境。我们在三个大型 Gazebo 环境中展示了模拟结果，表明与最先进的基线相比，我们的方法产生的探索路径缩短了 $8.6 - 34.1\%$，并显着提高了机器人之间的地图一致性。
