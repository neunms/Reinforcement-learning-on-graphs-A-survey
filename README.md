# Reinforcement learning on graphs: A survey

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

# Datasets

## Yelp

[[Dataset](https://www.kaggle.com/datasets/yelp-dataset/yelp-dataset), [Paper](https://ojs.aaai.org/index.php/ICWSM/article/view/14389/14238)]

This is collected from the internal dataset published by Yelp.com, the largest business reviewing site in the United States. This dataset is a subset of Yelp's businesses, reviews, and user data. It was originally put together for the Yelp Dataset Challenge which is a chance for students to conduct research or analysis on Yelp's data and share their discoveries. In the most recent dataset you'll find information about businesses across 8 metropolitan areas in the USA and Canada.

## Amazon

[[Dataset](http://snap.stanford.edu/data/#amazon), [Paper](https://dl.acm.org/doi/abs/10.1145/2488388.2488466)]

A product co-purchasing network, where nodes represent products and edges link the products that are often purchased together. This network has a ground-truth community defined by the categories of products. In our experiment, we consider the top-500 communities, which consist of 4,259 nodes and 13,474 edges.

## Cora

[[Dataset](https://linqs-data.soe.ucsc.edu/public/datasets/cora/cora.zip), [Paper](https://ojs.aaai.org/index.php/aimagazine/article/view/2157)]

The Cora dataset consists of 2708 scientific publications classified into one of seven classes. The citation network consists of 5429 links. Each publication in the dataset is described by a 0/1-valued word vector indicating the absence/presence of the corresponding word from the dictionary. The dictionary consists of 1433 unique words.

## CiteSeer

[[Dataset](https://linqs-data.soe.ucsc.edu/public/datasets/citeseer-doc-classification/), [Paper](https://ojs.aaai.org/index.php/aimagazine/article/view/2157)]

The CiteSeer dataset consists of 3312 scientific publications classified into one of six classes. The citation network consists of 4732 links. Each publication in the dataset is described by a 0/1-valued word vector indicating the absence/presence of the corresponding word from the dictionary. The dictionary consists of 3703 unique words. 

## PubMed

[[Dataset](https://linqs-data.soe.ucsc.edu/public/datasets/pubmed-diabetes/), [Paper](https://ojs.aaai.org/index.php/aimagazine/article/view/2157)]

The Pubmed Diabetes dataset consists of 19717 scientific publications from PubMed database pertaining to diabetes classified into one of three classes. The citation network consists of 44338 links. Each publication in the dataset is described by a TF/IDF weighted word vector from a dictionary which consists of 500 unique words.

## Twitter

[[Dataset](https://snap.stanford.edu/data/ego-Twitter.html), [Paper](http://i.stanford.edu/~julian/pdfs/nips2012.pdf)]

This dataset consists of 'circles' (or 'lists') from Twitter. Twitter data was crawled from public sources. The dataset includes node features (profiles), circles, and ego networks.

## Facebook

[[Dataset](https://snap.stanford.edu/data/ego-Facebook.html), [Paper](http://i.stanford.edu/~julian/pdfs/nips2012.pdf)]

This dataset consists of 'circles' (or 'friends lists') from Facebook. Facebook data was collected from survey participants using this Facebook app. The dataset includes node features (profiles), circles, and ego networks. Facebook data has been anonymized by replacing the Facebook-internal ids for each user with a new value. Also, while feature vectors from this dataset have been provided, the interpretation of those features has been obscured. For instance, where the original dataset may have contained a feature "political=Democratic Party", the new data would simply contain "political=anonymized feature 1". Thus, using the anonymized data it is possible to determine whether two users have the same political affiliations, but not what their individual political affiliations represent.

## YouTube

[[Dataset](https://snap.stanford.edu/data/com-Youtube.html), [Paper](https://arxiv.org/abs/1205.6233)]

Youtube is a video-sharing web site that includes a social network. In the Youtube social network, users form friendship each other and users can create groups which other users can join. We consider such user-defined groups as ground-truth communities. 



## NELL-995

[[Dataset](https://github.com/wenhuchen/KB-Reasoning-Data/tree/master/NELL-995), [Paper](https://arxiv.org/abs/1808.10568)]

NELL is a dataset built from the Web via an intelligent agent called Never-Ending Language Learner. This agent attempts to learn over time to read the web. NELL has accumulated over 50 million candidate beliefs by reading the web, and it is considering these at different levels of confidence. NELL has high confidence in 2,810,379 of these beliefs. NELL-995 is a dataset constructed from high-confidence facts of NELL, a system constantly extracting facts from the web.

## WN18RR

[[Dataset](https://deepai.org/dataset/wn18), [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/11573)]

The WN18 dataset included the full 18 relations scraped from WordNet for roughly 41,000 synsets. Similar to FB15K, This dataset was found to suffer from test leakage by Dettmers et al. introduced the WN18RR.

As a way to overcome this problem, Dettmers et al. introduced the WN18RR dataset, derived from WN18, which features 11 relations only, no pair of which is reciprocal (but still include four internally-symmetric relations like *verb_group*, allowing the rule-based system to reach 35 on all three metrics).

## FB15K-237

[[Dataset](https://deepai.org/dataset/fb15k-237), [Paper](https://aclanthology.org/D15-1174.pdf)]

The FB15K dataset is a subset of Freebase which contains about 14,951 entities with 1,345 different relations. This dataset was found to suffer from major test leakage through inverse relations and a large number of test triples can be obtained simply by inverting triples in the training set initially by Toutanova et al.. To create a dataset without this property, Toutanova et al. introduced FB15k-237 – a subset of FB15k where inverse relations are removed.

## MUTAG

[[Dataset](https://www.chrsmrrs.com/graphkerneldatasets/MUTAG.zip), [Paper](https://pubs.acs.org/doi/pdf/10.1021/jm00106a046)]

MUTAG is a commonly used dataset for evaluating graph classification algorithms.

Each graph in the dataset represents a chemical compound and graph labels represent "their mutagenic effect on a specific gram negative bacterium". The dataset includes 188 graphs with 18 nodes and 20 edges on average for each graph. Graph nodes have 7 labels and each graph is labelled as belonging to 1 of 2 classes.

## PTC

[[Dataset](https://www.chrsmrrs.com/graphkerneldatasets/PTC_MR.zip), [Paper](https://academic.oup.com/bioinformatics/article/19/10/1183/184239)]

PTC is a collection of 344 chemical compounds represented as graphs that report carcinogenicity for rats. There are 19 node labels for each node.

## PROTEINS

[[Dataset](https://www.chrsmrrs.com/graphkerneldatasets/PROTEINS_full.zip), [Paper](https://academic.oup.com/bioinformatics/article/21/suppl_1/i47/202991)]

PROTEINS is a dataset of proteins that are classified as enzymes or non-enzymes. Nodes represent the amino acids and two nodes are connected by an edge if they are less than 6 Angstroms apart.



## NCI1 & NCI109

[[Dataset-NCI1](https://www.chrsmrrs.com/graphkerneldatasets/NCI1.zip), [Dataset-NCI109](https://www.chrsmrrs.com/graphkerneldatasets/NCI109.zip) ,[Paper](https://link.springer.com/article/10.1007/s10115-007-0103-5)]

Are two balanced subsets of the National Cancer Institute (NCI) database, consisting of graphs representing chemical compounds screened for activity against non-small cell lung cancer and ovarian cancer cell line, respectively. The graphs in each subset are labelled as active or inactive. All graphs are undirected and unweighted.

## BBBP

[[Dataset](https://github.com/kamran-haider/bbbp_ml_study/blob/master/data/BBBP.csv), [Paper](https://pubs.rsc.org/en/content/articlehtml/2018/sc/c7sc02664a)]

The Blood-brain barrier penetration (BBBP) dataset comes from a recent study on the modeling and prediction of barrier permeability. As a membrane separating circulating blood and brain extracellular fluid, the blood-brain barrier blocks most drugs, hormones, and neurotransmitters. Thus penetration of the barrier forms a long-standing issue in the development of drugs targeting the central nervous system. This dataset includes binary labels for over 2000 compounds on their permeability properties. Scaffold splitting is also recommended for this well-defined target.
