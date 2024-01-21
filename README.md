# [Reinforcement Learning on Graphs: A Survey](https://ieeexplore.ieee.org/document/10121200)

[![Travis](https://img.shields.io/badge/IEEE-TETCI-red)](https://ieeexplore.ieee.org/document/10121200/) <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/neunms/Reinforcement-learning-on-graphs-A-survey"> <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/neunms/Reinforcement-learning-on-graphs-A-survey"> <img alt="GitHub last commit" src="https://img.shields.io/badge/PRs-%20Welcome-orange">

**Published by IEEE Transactions on Emerging Topics in Computational Intelligence**

This collection of papers can be used to summarize research about graph reinforcement learning for the convenience of researchers.

Mingshuo Nie,

Northeastern University, China.

Email: niemingshuo@stumail.neu.edu.cn

# Abstract

> Graph mining tasks arise from many different application domains, including social networks, biological networks,  transportation, and E-commerce, which have been receiving great attention from the theoretical and algorithmic design communities in recent years, and there has been some pioneering work employing the research-rich Reinforcement Learning (RL) techniques to address graph mining tasks. However, these fusion works are dispersed in different research domains, which makes them difficult to compare. In this survey, we provide a comprehensive overview of these fusion works and generalize these works to Graph Reinforcement Learning (GRL) as a unified formulation. We further discuss the applications of GRL methods across various domains, and simultaneously propose the key challenges and advantages of integrating graph mining and RL methods. Furthermore, we propose important directions and challenges to be solved in the future. To our knowledge, this is the latest work on a comprehensive survey of GRL, this work provides a global view and a learning resource for scholars. Based on our review, we create a collection of papers for both interested scholars who want to enter this rapidly developing domain and experts who would like to compare GRL methods.

# Citation

If you find this work useful in your research, please consider citing:

```

@article{nie2023reinforcement,
  author={Nie, Mingshuo and Chen, Dongming and Wang, Dongqi},
  journal={IEEE Transactions on Emerging Topics in Computational Intelligence}, 
  title={Reinforcement Learning on Graphs: A Survey}, 
  year={2023},
  volume={7},
  number={4},
  pages={1065-1082},
  doi={10.1109/TETCI.2022.3222545}
}

```

------

# Awesome Graph Reinforcement Learning

<img src="https://github.com/neunms/Reinforcement-learning-on-graphs-A-survey/blob/main/Categorized/grl_wordcloud.png" width = "500" height = "300" alt="" align=center />

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=neunms/Reinforcement-learning-on-graphs-A-survey&type=Date)](https://star-history.com/#neunms/Reinforcement-learning-on-graphs-A-survey&Date)

## Quick Look

The papers in the collection are categorized:

- By [domain](Categorized/domain.md)
- By [year](Categorized/year.md)
- By [papers with code](Categorized/papers-with-code.md)

## RL method

All the reinforcement learning methods used in the literature are as follows.

| RL method                           | Abbr.      | Year | Paper                                                        |
| ----------------------------------- | ---------- | ---- | ------------------------------------------------------------ |
| Markov Decision Process             | MDP        | \    | \                                                            |
| Monte Carlo Tree Search             | MCTS       | \    | \                                                            |
| Q-learning                          | Q-learning | 1992 | [Paper](https://link.springer.com/article/10.1007/BF00992698) |
| REINFORCE                           | REINFORCE  | 1992 | [Paper](https://link.springer.com/article/10.1007/BF00992696) |
| Actor-Critic                        | AC         | 1999 | [Paper](https://proceedings.neurips.cc/paper/1999/hash/6449f44a102fde848669bdd9eb6b76fa-Abstract.html) |
| Bernoulli Multi-armed Bandit        | BMAB       | 2005 | [Paper](https://link.springer.com/chapter/10.1007/11564096_42) |
| Neural Fitted Q-iteration           | NFQI       | 2005 | [Paper](https://link.springer.com/chapter/10.1007/11564096_32) |
| Deep Q-learning Network             | DQN        | 2015 | [Paper](https://www.nature.com/articles/nature14236?wm=book_wap_0005) |
| Double DQN                          | DDQN       | 2016 | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/10295) |
| Advantage Actor-Critic              | A2C        | 2016 | [Paper](http://proceedings.mlr.press/v48/mniha16.html?ref=https://githubhelp.com) |
| Asynchronous Advantage Actor-Critic | A3C        | 2016 | [Paper](http://proceedings.mlr.press/v48/mniha16.html?ref=https://githubhelp.com) |
| Deep Deterministic Policy Gradient  | DDPG       | 2016 | [Paper](https://arxiv.org/pdf/1509.02971.pdf)                |
| Proximal Policy Optimization        | PPO        | 2017 | [Paper](https://arxiv.org/abs/1707.06347)                    |
| Cascaded DQN                        | CDQN       | 2019 | [Paper](http://proceedings.mlr.press/v97/chen19f.html)       |


