# Awesome Uncertainty-based RL Papers[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

This repository targets researchers exploring recent advances in reinforcement learning that utilize uncertainty to improve the reasoning capabilities of large language models.

## 📋 Table of Contents

- [Awesome Uncertainty-based RL Papers](#awesome-uncertainty-based-rl-papers)
  - [📋 Table of Contents](#-table-of-contents)
  - [📜 History](#-history)
    - [Recent Updates](#recent-updates)
  - [How is Uncertainty used in RL?](#how-is-uncertainty-used-in-rl)
    - [🎯 Uncertainty as an Optimization Objective](#-uncertainty-as-an-optimization-objective)
    - [💰 Uncertainty as a Reward Signal](#-uncertainty-as-a-reward-signal)
    - [🧭 Uncertainty as a Optimization Guide](#-uncertainty-as-a-optimization-guide)
  - [Contributing](#contributing)
  - [🌟 Star History](#-star-history)
  
## 📜 History

### Recent Updates

- **2025-07-01**: Added "SRFT: A Single-Stage Method with Supervised and Reinforcement Fine-Tuning for Reasoning"
- **2025-06-20**: Added “Reasoning with Exploration: An Entropy Perspective”
- **2025-06-20**: Added “Demystifying Reasoning Dynamics with Mutual Information: Thinking Tokens are Information Peaks in LLM Reasoning”
- **2025-06-18**: Added “Confidence Is All You Need: Few-Shot RL Fine-Tuning of Language Models”
- **2025-06-14**: Repository made public with comprehensive collection of uncertainty-based RL papers

## How is Uncertainty used in RL?

### 🎯 Uncertainty as an Optimization Objective

<div align="center">

| Title | Method | Date | Metric | Task Domain | Code | Venue |
|-----|:------:|:----:|:------:|:----------:|:----:|:-----:|
| [**Right Question is Already Half the Answer: Fully Unsupervised LLM Reasoning Incentivization**](https://arxiv.org/abs/2504.05812) | EMPO | 04/2025 | Semantic Entropy | Math & General | [code](https://github.com/QingyangZhang/EMPO) | arXiv |
| [**SLOT: Sample-specific Language Model Optimization at Test-time**](https://arxiv.org/abs/2505.12392) | SLOT | 05/2025 | Token Entropy | Math | [code](https://github.com/maple-research-lab/SLOT) | arXiv |
| [**The Unreasonable Effectiveness of Entropy Minimization in LLM Reasoning**](https://arxiv.org/abs/2505.15134) | EM-FT, EM-INF | 05/2025 | Trajectory/Token Entropy | Math & Code | [code](https://github.com/shivamag125/EM_PT) | arXiv |
| [**One-shot Entropy Minimization**](https://arxiv.org/abs/2505.20282) | EM | 05/2025 | Token Entropy | Math | [code](https://github.com/zitian-gao/one-shot-em) | arXiv |
| [**Maximizing Confidence Alone Improves Reasoning**](https://arxiv.org/abs/2505.22660) | RENT | 05/2025 | Token Entropy | Math | [project page](https://rent-rl.github.io/) | arXiv |
| [**Verbalized Confidence Triggers Self-Verification: Emergent Behavior Without Explicit Reasoning Supervision**](https://www.arxiv.org/abs/2506.03723) | CSFT | 06/2025 | Self-Confidence | Math | - | arXiv |

</div>

### 💰 Uncertainty as a Reward Signal

<div align="center">

| Title | Method | Date | Metric | Task Domain | Code | Venue |
|-----|:------:|:----:|:------:|:----------:|:----:|:-----:|
| [**The Unreasonable Effectiveness of Entropy Minimization in LLM Reasoning**](https://arxiv.org/abs/2505.15134) | EM-RL | 05/2025 | Trajectory/Token Entropy | Math & Code | [code](https://github.com/shivamag125/EM_PT) | arXiv |
| [**Learning to Reason without External Rewards**](https://arxiv.org/abs/2505.19590) | INTUITOR | 05/2025 | Self-Certainty | Math & Code | [code](https://github.com/sunblaze-ucb/Intuitor) | arXiv |
| [**Confidence Is All You Need: Few-Shot RL Fine-Tuning of Language Models**](https://arxiv.org/abs/2506.06395) | RLSC | 06/2025 | Self-Confidence | Math | - | arXiv |
| [**Consistent Paths Lead to Truth Self-Rewarding Reinforcement Learning for LLM Reasoning**](https://arxiv.org/abs/2506.08745) | CoVo | 06/2025 | Trajectory Features | Math | [code](https://github.com/sastpg/CoVo) | arXiv |

</div>

### 🧭 Uncertainty as a Optimization Guide

<div align="center">

| Title | Method | Date | Metric | Task Domain | Code | Venue |
|-----|:------:|:----:|:------:|:----------:|:----:|:-----:|
| [**SEED-GRPO: Semantic entropy enhanced GRPO for uncertainty-aware policy optimization**](https://arxiv.org/abs/2505.12346) | SEED-GRPO | 05/2025 | Semantic Entropy | Math | - | arXiv |
| [**The Entropy Mechanism of Reinforcement Learning for Reasoning Language Models**](https://arxiv.org/abs/2505.22617) | Clip-Cov, KL-Cov | 05/2025 | Policy Entropy | Math | [code](https://github.com/PRIME-RL/Entropy-Mechanism-of-RL) | arXiv |
| [**Reinforcing Video Reasoning with Focused Thinking**](https://arxiv.org/abs/2505.24718) | TW-GRPO | 05/2025 | Intra-Group Information Entropy | Video | [code](https://github.com/longmalongma/TW-GRPO) | arXiv |
| [**Beyond the 80/20 Rule: High-Entropy Minority Tokens Drive Effective Reinforcement Learning for LLM Reasoning**](https://arxiv.org/abs/2506.01939) | Forking Tokens | 06/2025 | Token Entropy | Math | [project page](https://shenzhi-wang.github.io/high-entropy-minority-tokens-rlvr/) | arXiv |
| [**Demystifying Reasoning Dynamics with Mutual Information: Thinking Tokens are Information Peaks in LLM Reasoning**](https://arxiv.org/abs/2506.02867) | MI peaks  | 06/2025 | Mutual Information | Math | [code](https://github.com/ChnQ/MI-Peaks) | arXiv |
| [**Reasoning with Exploration: An Entropy Perspective**](https://arxiv.org/abs/2506.14758) | Entropy-Based Advantage Shaping | 06/2025 | Token Entropy | Math | - | arXiv |
| [**SRFT: A Single-Stage Method with Supervised and Reinforcement Fine-Tuning for Reasoning**](https://arxiv.org/abs/2506.19767) | SRFT | 06/2025 | Token Entropy | Math | [poject page](https://anonymous.4open.science/w/SRFT2025) | arXiv |

</div>

## Contributing

We welcome everyone to contribute to this repository and help improve it. You can submit pull requests to add new papers, projects, and helpful materials, or to correct any errors that you may find. Please make sure that your pull requests follow the format in the tables above. Thank you for your valuable contributions!

<div align="center">

**🌟 Star this repo if you find it helpful! 🌟**

</div>

## 🌟 Star History

[![Star History Chart](https://api.star-history.com/svg?repos=falonss703/Awesome-Uncertainty-based-Reinforcement-Learning&type=Date)](https://www.star-history.com/#falonss703/Awesome-Uncertainty-based-Reinforcement-Learning&Date)