# Awesome-Uncertainty-based-RL [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<div align="center">
  <p>A curated list of uncertainty-based reinforcement learning resources</p>
</div>

## How to use Uncertainty in RL?

### 🕹️ Uncertainty as Optimization Objective

<table>
  <tr>
    <th width="40%">Title</th>
    <th width="8%">Method</th>
    <th width="7%">Date</th>
    <th width="15%">Metric</th>
    <th width="16%">Task Domain</th>
    <th width="7%">Code</th>
    <th width="7%">Venue</th>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/2504.05812"><b>Right Question is Already Half the Answer: Fully Unsupervised LLM Reasoning Incentivization</b></a></td>
    <td align="center">EMPO</td>
    <td align="center">04/2025</td>
    <td align="center">Semantic Entropy</td>
    <td align="center">Math & General</td>
    <td align="center"><a href="https://github.com/QingyangZhang/EMPO">code</a></td>
    <td align="center">arXiv</td>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/2505.12392"><b>SLOT: Sample-specific Language Model Optimization at Test-time</b></a></td>
    <td align="center">SLOT</td>
    <td align="center">05/2025</td>
    <td align="center">Token Entropy</td>
    <td align="center">Math</td>
    <td align="center"><a href="https://github.com/maple-research-lab/SLOT">code</a></td>
    <td align="center">arXiv</td>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/2505.15134"><b>The Unreasonable Effectiveness of Entropy Minimization in LLM Reasoning</b></a></td>
    <td align="center">EM-FT, EM-INF</td>
    <td align="center">05/2025</td>
    <td align="center">Trajectory/Token Entropy</td>
    <td align="center">Math & Code</td>
    <td align="center"><a href="https://github.com/shivamag125/EM_PT">-</a></td>
    <td align="center">arXiv</td>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/2505.20282"><b>One-shot Entropy Minimization</b></a></td>
    <td align="center">EM</td>
    <td align="center">05/2025</td>
    <td align="center">Token Entropy</td>
    <td align="center">Math</td>
    <td align="center"><a href="https://github.com/zitian-gao/one-shot-em">code</a></td>
    <td align="center">arXiv</td>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/2505.22660"><b>Maximizing Confidence Alone Improves Reasoning</b></a></td>
    <td align="center">RENT</td>
    <td align="center">05/2025</td>
    <td align="center">Token Entropy</td>
    <td align="center">Math</td>
    <td align="center"><a href="https://rent-rl.github.io/">project page</a></td>
    <td align="center">arXiv</td>
  </tr>
  <tr>
    <td><a href="https://www.arxiv.org/abs/2506.03723"><b>Verbalized Confidence Triggers Self-Verification: Emergent Behavior Without Explicit Reasoning Supervision</b></a></td>
    <td align="center">CSFT</td>
    <td align="center">06/2025</td>
    <td align="center">Self-Confidence</td>
    <td align="center">Math</td>
    <td align="center">-</td>
    <td align="center">arXiv</td>
  </tr>
</table>

### 🕹️ Uncertainty as Reward Signal

<table>
  <tr>
    <th width="40%">Title</th>
    <th width="8%">Method</th>
    <th width="7%">Date</th>
    <th width="15%">Metric</th>
    <th width="16%">Task Domain</th>
    <th width="7%">Code</th>
    <th width="7%">Venue</th>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/2505.15134"><b>The Unreasonable Effectiveness of Entropy Minimization in LLM Reasoning</b></a></td>
    <td align="center">EM-RL</td>
    <td align="center">05/2025</td>
    <td align="center">Trajectory/Token Entropy</td>
    <td align="center">Math & Code</td>
    <td align="center"><a href="https://github.com/shivamag125/EM_PT">-</a></td>
    <td align="center">arXiv</td>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/2505.19590"><b>Learning to Reason without External Rewards</b></a></td>
    <td align="center">INTUITOR</td>
    <td align="center">05/2025</td>
    <td align="center">Self-Certainty</td>
    <td align="center">Math & Code</td>
    <td align="center"><a href="https://github.com/sunblaze-ucb/Intuitor">code</a></td>
    <td align="center">arXiv</td>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/2506.08745"><b>Consistent Paths Lead to Truth Self-Rewarding Reinforcement Learning for LLM Reasoning</b></a></td>
    <td align="center">CoVo</td>
    <td align="center">06/2025</td>
    <td align="center">Trajectory Features</td>
    <td align="center">Math</td>
    <td align="center"><a href="https://github.com/sastpg/CoVo">code</a></td>
    <td align="center">arXiv</td>
  </tr>
</table>

### 🕹️ Uncertainty as Optimization Guide

<table>
  <tr>
    <th width="40%">Title</th>
    <th width="8%">Method</th>
    <th width="7%">Date</th>
    <th width="15%">Metric</th>
    <th width="16%">Task Domain</th>
    <th width="7%">Code</th>
    <th width="7%">Venue</th>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/2505.12346"><b>SEED-GRPO: Semantic entropy enhanced GRPO for uncertainty-aware policy optimization</b></a></td>
    <td align="center">SEED-GRPO</td>
    <td align="center">05/2025</td>
    <td align="center">Semantic Entropy</td>
    <td align="center">Math</td>
    <td align="center">-</td>
    <td align="center">arXiv</td>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/2505.22617"><b>The Entropy Mechanism of Reinforcement Learning for Reasoning Language Models</b></a></td>
    <td align="center">Clip-Cov, KL-Cov</td>
    <td align="center">05/2025</td>
    <td align="center">Policy Entropy</td>
    <td align="center">Math</td>
    <td align="center"><a href="https://github.com/PRIME-RL/Entropy-Mechanism-of-RL">code</a></td>
    <td align="center">arXiv</td>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/2505.24718"><b>Reinforcing Video Reasoning with Focused Thinking</b></a></td>
    <td align="center">TW-GRPO</td>
    <td align="center">05/2025</td>
    <td align="center">Intra-Group Information Entropy</td>
    <td align="center">Video</td>
    <td align="center"><a href="https://github.com/longmalongma/TW-GRPO">code</a></td>
    <td align="center">arXiv</td>
  </tr>
  <tr>
    <td><a href="https://arxiv.org/abs/2506.01939"><b>Beyond the 80/20 Rule: High-Entropy Minority Tokens Drive Effective Reinforcement Learning for LLM Reasoning</b></a></td>
    <td align="center">Forking Tokens</td>
    <td align="center">06/2025</td>
    <td align="center">Token Entropy</td>
    <td align="center">Math</td>
    <td align="center"><a href="https://shenzhi-wang.github.io/high-entropy-minority-tokens-rlvr/">project page</a></td>
    <td align="center">arXiv</td>
  </tr>
</table>

## Contributing

We welcome everyone to contribute to this repository and help improve it. You can submit pull requests to add new papers, projects, and helpful materials, or to correct any errors that you may find. Please make sure that your pull requests follow the format in the tables above. Thank you for your valuable contributions!

### 🌟 Star History

<div align="center">
  <a href="https://www.star-history.com/#falonss703/Awesome-Entropy-based-RL&Date">
    <img src="https://api.star-history.com/svg?repos=falonss703/Awesome-Entropy-based-RL&type=Date" alt="Star History Chart" width="600">
  </a>
</div>