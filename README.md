This repository contains the Minecart environment as presented in our paper "Dynamic Weights in Multi-Objective Deep Reinforcement Learning", published at ICML 2019. If you use this code in your own research, please cite this paper:

```
@inproceedings{abels2019dynamic,
  title={Dynamic Weights in Multi-Objective Deep Reinforcement Learning},
  author={Abels, Axel and Roijers, Diederik M. and Lenaerts, Tom and Now{\'e}, Ann and Steckelmacher, Denis},
  booktitle={Proceedings of the 36th International Conference on Machine Learning},
  pages={TBA},
  year={2019}
}
```

https://arxiv.org/abs/1809.07803v2


---------------------------------------
#### Abstract
Many real-world decision problems are characterized by multiple conflicting objectives which must be balanced based on their relative importance. In the dynamic weights setting the relative importance changes over time and specialized algorithms that deal with such change, such as a tabular Reinforcement Learning (RL) algorithm by Natarajan and Tadepalli (2005), are required. However, this earlier work is not feasible for RL settings that necessitate the use of function approximators. We generalize across weight changes and high-dimensional inputs by proposing a multi-objective Q-network whose outputs are conditioned on the relative importance of objectives and we introduce Diverse Experience Replay (DER) to counter the inherent non-stationarity of the Dynamic Weights setting. We perform an extensive experimental evaluation and compare our methods to adapted algorithms from Deep Multi-Task/Multi-Objective Reinforcement Learning and show that our proposed network in combination with DER dominates these adapted algorithms across weight change scenarios and problem domains.

You can find the complete code for this paper in the [DynMORL repository](https://github.com/axelabels/DynMORL).
