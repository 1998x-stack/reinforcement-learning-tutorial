# 🤖 强化学习 · 从入门到精通

> 🧠 28章 系统体系

一套完整的 **强化学习 · 从入门到精通** 全中文实战课程体系，共 **28 章**。本课程以 HTML 可视化的形式呈现，从基础原理到工程实践循序渐进，适合系统性学习与复习。

## 🚀 快速开始

无需安装任何依赖，直接用浏览器打开 `index.html` 即可在线阅读全部章节：

```bash
open index.html   # macOS
# 或在浏览器中直接打开 index.html
```

## 📖 章节目录

| # | 章节 | 核心主题 |
|---|------|----------|
| 01 | 强化学习是什么 | RL核心概念、学习范式对比、发展里程碑、应用场景 |
| 02 | 必备数学工具箱 | 概率与期望、线性代数、梯度下降、数学到RL的桥梁 |
| 03 | 马尔可夫决策过程 | MDP五元组、马尔可夫性质、转移与奖励、GridWorld建模 |
| 04 | 贝尔曼方程 | V(s)与Q(s,a)、期望方程、最优方程、备份图 |
| 05 | 动态规划 | 策略评估、策略改进、策略迭代、价值迭代 |
| 06 | 蒙特卡洛方法 | MC预测、MC控制、ε-贪心、MC vs DP vs TD |
| 07 | 时序差分学习 | TD(0)预测、SARSA、Q-Learning、TD(λ)资格迹 |
| 08 | 值函数逼近 | 维度诅咒、线性逼近、非线性逼近、半梯度方法 |
| 09 | 深度Q网络(DQN) | 经验回放、目标网络、Atari突破、DQN算法流程 |
| 10 | DQN改进家族 | Double DQN、Dueling DQN、优先经验回放、Rainbow |
| 11 | 策略梯度方法 | 策略参数化、梯度定理、REINFORCE、基线技巧 |
| 12 | Actor-Critic方法 | AC架构、优势函数、A2C/A3C、GAE |
| 13 | PPO与TRPO | 信任域、TRPO约束、PPO-Clip、PPO实现细节 |
| 14 | 连续动作空间算法 | DDPG、TD3、SAC、最大熵框架 |
| 15 | 探索与利用策略 | ε-贪心变体、UCB、汤普森采样、深度RL探索 |
| 16 | 奖励设计与塑形 | 奖励函数设计、稀疏奖励、奖励塑形、课程学习 |
| 17 | 训练稳定性与调参 | Deadly Triad、稳定性技巧、调参方法论、网络初始化 |
| 18 | 安全强化学习 | 约束MDP、安全层、安全探索、工业部署 |
| 19 | 基于模型的强化学习 | Dyna-Q、世界模型、MBPO、Dreamer |
| 20 | 离线强化学习 | 分布偏移、CQL、IQL、Decision Transformer |
| 21 | 多智能体强化学习 | CTDE、MADDPG、QMIX、自博弈 |
| 22 | 逆强化学习与模仿学习 | 行为克隆、MaxEnt IRL、学徒学习、GAIL |
| 23 | Gymnasium环境实战 | Gymnasium API、经典环境、自定义环境、Wrapper |
| 24 | Stable-Baselines3入门 | SB3架构、训练脚本、回调系统、超参数调优 |
| 25 | 调试与可视化 | TensorBoard、WandB、奖励曲线诊断、常见Bug |
| 26 | 强化学习前沿方向 | LLM+RL、RLHF、元RL、Foundation Agent |
| 27 | 从零实现DQN | PyTorch实现、经验回放、训练循环、评估与分析 |
| 28 | 综合实战：Atari智能体 | Atari环境、CNN架构、完整Pipeline、结果分析 |

## 📂 项目结构

```text
reinforcement-learning-tutorial/
├── index.html      # 课程主入口（在线阅读全部章节）
├── 01.html ~ 28.html   # 各章节正文
├── courses.json    # 课程元数据（标题/章节/主题）
└── theme.css       # 统一主题样式
```

## ✨ 课程特色

- **全中文实战体系**：面向中文读者，由浅入深，覆盖原理与工程实践
- **28 章完整内容**：系统化章节编排，形成完整知识闭环
- **可视化呈现**：HTML 图文并茂，适合快速浏览与重点回顾
- **即开即用**：无需构建、无需服务器，纯静态页面随开随看

---
*本课程由 `reinforcement-learning-tutorial/` 项目维护。*