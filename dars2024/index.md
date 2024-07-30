# Privileged Reinforcement and Communication Learning for Distributed, Bandwidth-limited Multi-robot Exploration

Springer's Distributed Autonomous Robotic Systems 2024 (DARS 2024).
<!--more-->
{{< figure src="/images/DARS2024/cover.jpg">}}
## Abstract
Communication bandwidth is an important consideration in multi-robot
exploration, where information exchange among robots is critical. While
existing methods typically aim to reduce communication throughput, they
either require significant computation or significantly compromise
exploration efficiency. In this work, we propose a deep reinforcement
learning framework based on communication and privileged reinforcement
learning to achieve a significant reduction in bandwidth consumption,
while minimally sacrificing exploration efficiency. Specifically, our
approach allows robots to learn to embed the most salient information
from their individual belief (partial map) over the environment into
fixed-sized messages. Robots then reason about their own belief as well
as received messages to distributedly explore the environment while
avoiding redundant work. In doing so, we employ privileged learning and
learned attention mechanisms to endow the critic (i.e., teacher) network
with ground truth map knowledge to effectively guide the policy (i.e.,
student) network during training. Compared to relevant baselines, our
model allows the team to reduce communication by up to two orders of
magnitude, while only sacrificing a marginal 2.4% in total travel
distance, paving the way for efficient, distributed multi-robot
exploration in bandwidth-limited scenarios. We open-sourced our <a href="https://github.com/marmotlab/Bandwidth-Limited-Multi-Robot-Exploration">full code</a>.

## Demo
{{< figure src="/images/DARS2024/0.gif">}}

## Paper
<a href="https://arxiv.org/abs/2407.20203">arxiv</a>.
