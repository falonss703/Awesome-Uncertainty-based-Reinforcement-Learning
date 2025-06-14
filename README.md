# Awesome Entropy-based RL 

<div align="center">

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![GitHub stars](https://img.shields.io/github/stars/falonss703/Awesome-Entropy-based-RL?style=social)](https://github.com/falonss703/Awesome-Entropy-based-RL/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/falonss703/Awesome-Entropy-based-RL?style=social)](https://github.com/falonss703/Awesome-Entropy-based-RL/network/members)
[![GitHub issues](https://img.shields.io/github/issues/falonss703/Awesome-Entropy-based-RL)](https://github.com/falonss703/Awesome-Entropy-based-RL/issues)
[![GitHub license](https://img.shields.io/github/license/falonss703/Awesome-Entropy-based-RL?color=blue)](https://github.com/falonss703/Awesome-Entropy-based-RL/blob/main/LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/falonss703/Awesome-Entropy-based-RL/pulls)

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png">

<h1>A Curated Collection of Uncertainty-based Reinforcement Learning Resources</h1>

<p>This repository contains a comprehensive list of papers, projects, and resources related to uncertainty-based reinforcement learning, with a focus on entropy-based methods.</p>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png">

</div>

## 📋 Table of Contents

- [Awesome Entropy-based RL](#awesome-entropy-based-rl)
  - [📋 Table of Contents](#-table-of-contents)
  - [Introduction](#introduction)
  - [How to use Uncertainty in RL?](#how-to-use-uncertainty-in-rl)
    - [🎯 Uncertainty as Optimization Objective](#-uncertainty-as-optimization-objective)
    - [💰 Uncertainty as Reward Signal](#-uncertainty-as-reward-signal)
    - [🧭 Uncertainty as Optimization Guide](#-uncertainty-as-optimization-guide)
  - [Contributing](#contributing)
  - [🌟 Star History](#-star-history)

## Introduction

Uncertainty plays a crucial role in reinforcement learning (RL), particularly when applied to language models and reasoning tasks. This repository categorizes research papers based on how they utilize uncertainty in RL frameworks, providing a valuable resource for researchers and practitioners in the field.

## How to use Uncertainty in RL?

### 🎯 Uncertainty as Optimization Objective

<div align="center">

| Title | Method | Date | Metric | Task Domain | Code | Venue |
|-------|--------|------|--------|------------|------|-------|
| [**Right Question is Already Half the Answer: Fully Unsupervised LLM Reasoning Incentivization**](https://arxiv.org/abs/2504.05812) | EMPO | 04/2025 | Semantic Entropy | Math & General | [code](https://github.com/QingyangZhang/EMPO) | arXiv |
| [**SLOT: Sample-specific Language Model Optimization at Test-time**](https://arxiv.org/abs/2505.12392) | SLOT | 05/2025 | Token Entropy | Math | [code](https://github.com/maple-research-lab/SLOT) | arXiv |
| [**The Unreasonable Effectiveness of Entropy Minimization in LLM Reasoning**](https://arxiv.org/abs/2505.15134) | EM-FT, EM-INF | 05/2025 | Trajectory/Token Entropy | Math & Code | [code](https://github.com/shivamag125/EM_PT) | arXiv |
| [**One-shot Entropy Minimization**](https://arxiv.org/abs/2505.20282) | EM | 05/2025 | Token Entropy | Math | [code](https://github.com/zitian-gao/one-shot-em) | arXiv |
| [**Maximizing Confidence Alone Improves Reasoning**](https://arxiv.org/abs/2505.22660) | RENT | 05/2025 | Token Entropy | Math | [project page](https://rent-rl.github.io/) | arXiv |
| [**Verbalized Confidence Triggers Self-Verification: Emergent Behavior Without Explicit Reasoning Supervision**](https://www.arxiv.org/abs/2506.03723) | CSFT | 06/2025 | Self-Confidence | Math | - | arXiv |

</div>

### 💰 Uncertainty as Reward Signal

<div align="center">

| Title | Method | Date | Metric | Task Domain | Code | Venue |
|-------|--------|------|--------|------------|------|-------|
| [**The Unreasonable Effectiveness of Entropy Minimization in LLM Reasoning**](https://arxiv.org/abs/2505.15134) | EM-RL | 05/2025 | Trajectory/Token Entropy | Math & Code | [code](https://github.com/shivamag125/EM_PT) | arXiv |
| [**Learning to Reason without External Rewards**](https://arxiv.org/abs/2505.19590) | INTUITOR | 05/2025 | Self-Certainty | Math & Code | [code](https://github.com/sunblaze-ucb/Intuitor) | arXiv |
| [**Consistent Paths Lead to Truth Self-Rewarding Reinforcement Learning for LLM Reasoning**](https://arxiv.org/abs/2506.08745) | CoVo | 06/2025 | Trajectory Features | Math | [code](https://github.com/sastpg/CoVo) | arXiv |

</div>

### 🧭 Uncertainty as Optimization Guide

<div align="center">

| Title | Method | Date | Metric | Task Domain | Code | Venue |
|-------|--------|------|--------|------------|------|-------|
| [**SEED-GRPO: Semantic entropy enhanced GRPO for uncertainty-aware policy optimization**](https://arxiv.org/abs/2505.12346) | SEED-GRPO | 05/2025 | Semantic Entropy | Math | - | arXiv |
| [**The Entropy Mechanism of Reinforcement Learning for Reasoning Language Models**](https://arxiv.org/abs/2505.22617) | Clip-Cov, KL-Cov | 05/2025 | Policy Entropy | Math | [code](https://github.com/PRIME-RL/Entropy-Mechanism-of-RL) | arXiv |
| [**Reinforcing Video Reasoning with Focused Thinking**](https://arxiv.org/abs/2505.24718) | TW-GRPO | 05/2025 | Intra-Group Information Entropy | Video | [code](https://github.com/longmalongma/TW-GRPO) | arXiv |
| [**Beyond the 80/20 Rule: High-Entropy Minority Tokens Drive Effective Reinforcement Learning for LLM Reasoning**](https://arxiv.org/abs/2506.01939) | Forking Tokens | 06/2025 | Token Entropy | Math | [project page](https://shenzhi-wang.github.io/high-entropy-minority-tokens-rlvr/) | arXiv |

</div>

## Contributing

We welcome everyone to contribute to this repository and help improve it. You can submit pull requests to add new papers, projects, and helpful materials, or to correct any errors that you may find. Please make sure that your pull requests follow the format in the tables above. Thank you for your valuable contributions!

## 🌟 Star History

<div align="center">
  <a href="https://www.star-history.com/#falonss703/Awesome-Entropy-based-RL&Date">
    <img src="https://api.star-history.com/svg?repos=falonss703/Awesome-Entropy-based-RL&type=Date" alt="Star History Chart" width="600">
  </a>
</div>