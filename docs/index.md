---
layout: default
title: MULTIPOLAR
---

# MULTIPOLAR: Multi-Source Policy Aggregation for Transfer Reinforcement Learning between Diverse Environmental Dynamics [IJCAI'20]

### [Mohammadamin Barekatain](http://barekatain.me/), [Ryo Yonetani](https://yonetaniro.github.io/), and [Masashi Hamaya](https://sites.google.com/view/masashihamaya/home) [(OMRON SINIC X)](https://www.omron.com/sinicx/)

### [Paper](https://arxiv.org/abs/1909.13111) \| [Code](https://github.com/Mohammadamin-Barekatain/multipolar)

## Overview
![overview](images/overview.png)

Transfer reinforcement learning (RL) aims at improving learning efficiency of an agent by exploiting knowledge from other source agents trained on relevant tasks. However, it remains challenging to transfer knowledge between different environmental dynamics without having access to the source environments. In this work, we explore a new challenge in transfer RL, where only a set of source policies collected under unknown diverse dynamics is available for learning a target task efficiently. To address this problem, the proposed approach, MULTI-source POLicy AggRegation (MULTIPOLAR), comprises two key techniques. We learn to aggregate the actions provided by the source policies adaptively to maximize the target task performance. Meanwhile, we learn an auxiliary network that predicts residuals around the aggregated actions, which ensures the target policy"s expressiveness even when some of the source policies perform poorly. We demonstrated the effectiveness of MULTIPOLAR through an extensive experimental evaluation across six simulated environments ranging from classic control problems to challenging robotics simulations, under both continuous and discrete action spaces.


---

## Video presentation at [ICLR 2020 BeTR-RL Workshop](http://www.betr-rl.ml/2020/abs/8/)

<div align="center"><iframe width="560" height="315" src="https://www.youtube.com/embed/JE5aeTqwo6o" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>

---

## Bibtex

```
# arXiv version
@article{barekatain2019multipolar,
title={MULTIPOLAR: Multi-Source Policy Aggregation for Transfer Reinforcement Learning between Diverse Environmental Dynamics},
author={Barekatain, Mohammadamin and Yonetani, Ryo and Hamaya, Masashi},
journal={arXiv preprint arXiv:1909.13111},
year={2019}
}

# IJCAI version (to appear)
@inproceedings{barekatain2020multipolar,
title={MULTIPOLAR: Multi-Source Policy Aggregation for Transfer Reinforcement Learning between Diverse Environmental Dynamics},
author={Barekatain, Mohammadamin and Yonetani, Ryo and Hamaya, Masashi},
booktitle={International Joint Conference on Artificial Intelligence (IJCAI)},
year={2020}
}
```

###### Last update: 05/18/2020 (c) 2020 OMRON SINIC X Corporation
