# Awesome Architecture Search [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
<p align="center">
  <img width="250" src="https://camo.githubusercontent.com/1131548cf666e1150ebd2a52f44776d539f06324/68747470733a2f2f63646e2e7261776769742e636f6d2f73696e647265736f726875732f617765736f6d652f6d61737465722f6d656469612f6c6f676f2e737667" "Awesome!">
</p>

A curated list of awesome architecture search and hyper-parameter optimization resources. Inspired by [awesome-deep-vision](https://github.com/kjw0612/awesome-deep-vision), [awesome-adversarial-machine-learning](https://github.com/yenchenlin/awesome-adversarial-machine-learning) and [awesome-deep-learning-papers](https://github.com/terryum/awesome-deep-learning-papers).

Hyper-parameter optimization has always been a popular field in the Machine Learning community, architecture search just emerges as a rising star in recent years. These are some of the awesome resources!

## Table of Contents

- [Architecture Search](#architecture-search)
  - [Reinforcement Learning](#reinforcement-learning)
  - [Evolutionary Algorithm](#evolutionary-algorithm)
  - [Others](#others)
- [Hyper-parameter Search](#hyper-parameter-search)

## Architecture Search

### Reinforcement Learning
- Neural Architecture Search with Reinforcement Learning [[pdf]](https://arxiv.org/abs/1611.01578)
  - Barret Zoph and Quoc V. Le. *ICLR'17*
- Designing Neural Network Architectures Using Reinforcement Learning [[pdf]](https://arxiv.org/abs/1611.02167) [[code]](https://github.com/bowenbaker/metaqnn)
  - Bowen Baker, Otkrist Gupta, Nikhil Naik, Ramesh Raskar. *ICLR'17*
- Efficient Architecture Search by Network Transformation [[pdf]](https://arxiv.org/abs/1707.04873) [[code]](https://github.com/han-cai/EAS)
  - Han Cai, Tianyao Chen, Weinan Zhang, Yong Yu, Jun Wang. *AAAI'18*
- Learning Transferable Architectures for Scalable Image Recognition [[pdf]](https://arxiv.org/abs/1707.07012) [[nasnet]](https://github.com/tensorflow/models/tree/master/research/slim/nets/nasnet)
  - Barret Zoph, Vijay Vasudevan, Jonathan Shlens, Quoc V. Le. *Arxiv 1707*
- Practical Network Blocks Design with Q-Learning [[pdf]](https://arxiv.org/abs/1708.05552)
  - Zhao Zhong, Junjie Yan, Cheng-Lin Liu. *CVPR'18*
- Efficient Neural Architecture Search via Parameter Sharing [[pdf]](https://arxiv.org/abs/1802.03268) [[code (not official)]](https://github.com/carpedm20/ENAS-pytorch) [[code (official)]](https://github.com/melodyguan/enas)
  - Hieu Pham, Melody Y. Guan, Barret Zoph, Quoc V. Le, Jeff Dean. *Arxiv 1802*
- Path-Level Network Transformation for Efficient Architecture Search [[pdf]](https://arxiv.org/abs/1806.02639) [[code]](https://github.com/han-cai/PathLevel-EAS)
  - Han Cai, Jiacheng Yang, Weinan Zhang, Song Han, Yong Yu. *ICML'18*

### Evolutionary Algorithm
- Large-Scale Evolution of Image Classifiers [[pdf]](https://arxiv.org/abs/1703.01041)
  - Esteban Real, Sherry Moore, Andrew Selle, Saurabh Saxena, Yutaka Leon Suematsu, Jie Tan, Quoc Le, Alex Kurakin. *ICML'17*
- Genetic CNN [[pdf]](https://arxiv.org/abs/1703.01513) [[code]](https://github.com/aqibsaeed/Genetic-CNN)
  - Lingxi Xie and Alan Yuille. *ICCV'17*
- Hierarchical Representations for Efficient Architecture Search [[pdf]](https://arxiv.org/abs/1711.00436)
  - Hanxiao Liu, Karen Simonyan, Oriol Vinyals, Chrisantha Fernando, Koray Kavukcuoglu. *ICLR'18*
- Regularized Evolution for Image Classifier Architecture Search [[pdf]](https://arxiv.org/abs/1802.01548)
  - Esteban Real, Alok Aggarwal, Yanping Huang, Quoc V Le. *Arxiv 1802*

### Others
- Neural Architecture Optimization [[pdf]](https://arxiv.org/abs/1808.07233) [[code]](https://github.com/renqianluo/NAO)
  - Renqian Luo, Fei Tian, Tao Qin, Enhong Chen, Tie-Yan Liu. *Arxiv 1808*
- DeepArchitect: Automatically Designing and Training Deep Architectures [[pdf]](https://arxiv.org/abs/1704.08792) [[code]](https://github.com/negrinho/deep_architect)
  - Renato Negrinho and Geoff Gordon. *Arxiv 1704*
- SMASH: One-Shot Model Architecture Search through HyperNetworks [[pdf]](https://arxiv.org/abs/1708.05344) [[code]](https://github.com/ajbrock/SMASH)
  - Andrew Brock, Theodore Lim, J.M. Ritchie, Nick Weston. *ICLR'18*
- Simple and efficient architecture search for Convolutional Neural Networks [[pdf]](https://arxiv.org/abs/1711.04528)
  - Thomas Elsken, Jan-Hendrik Metzen, Frank Hutter. *ICLR'18 Workshop*
- Progressive Neural Architecture Search [[pdf]](https://arxiv.org/abs/1712.00559)
  - Chenxi Liu, Barret Zoph, Jonathon Shlens, Wei Hua, Li-Jia Li, Li Fei-Fei, Alan Yuille, Jonathan Huang, Kevin Murphy. *Arxiv 1712*
- DPP-Net: Device-aware Progressive Search for Pareto-optimal Neural Architectures [[pdf]](https://arxiv.org/abs/1806.08198)
  - [Jin-Dong Dong](https://markdtw.github.io), An-Chieh Cheng, Da-Cheng Juan, Wei Wei, Min Sun. *ECCV'18*
- Neural Architecture Search with Bayesian Optimisation and Optimal Transport [[pdf]](https://arxiv.org/abs/1802.07191)
  - Kirthevasan Kandasamy, Willie Neiswanger, Jeff Schneider, Barnabas Poczos, Eric Xing. *Arxiv 1802*
- Effective Building Block Design for Deep Convolutional Neural Networks using Search [[pdf]](https://arxiv.org/abs/1801.08577)
  - Jayanta K Dutta, Jiayi Liu, Unmesh Kurup, Mohak Shah. *Arxiv 1801*
- DARTS: Differentiable Architecture Search [[pdf]](https://arxiv.org/abs/1806.09055) [[code]](https://github.com/quark0/darts)
  - Hanxiao Liu, Karen Simonyan, Yiming Yang. *Arxiv 1806*
- Efficient Neural Architecture Search with Network Morphism [[pdf]](https://arxiv.org/abs/1806.10282) [[code]](https://github.com/jhfjhfj1/autokeras)
  - Haifeng Jin, Qingquan Song, Xia Hu. *Arxiv 1806*
- Searching for Efficient Multi-Scale Architectures for Dense Image Prediction [[pdf]](https://arxiv.org/abs/1809.04184) 
  - Liang-Chieh Chen, Maxwell D. Collins, Yukun Zhu, George Papandreou, Barret Zoph, Florian Schroff, Hartwig Adam, Jonathon Shlens. *Arxiv 1809*


## Hyper-Parameter Search
- Speeding up Automatic Hyperparameter Optimization of Deep Neural Networksby Extrapolation of Learning Curves [[pdf]](http://ml.informatik.uni-freiburg.de/papers/15-IJCAI-Extrapolation_of_Learning_Curves.pdf) [[code]](https://github.com/automl/pylearningcurvepredictor)
  - Tobias Domhan, Jost Tobias Springenberg, Frank Hutter. *IJCAI'15*
- Hyperband: A Novel Bandit-Based Approach to Hyperparameter Optimization [[pdf]](https://arxiv.org/abs/1603.06560)
  - Lisha Li, Kevin Jamieson, Giulia DeSalvo, Afshin Rostamizadeh, Ameet Talwalkar. *ICLR'17*
- Learning Curve Prediction with Bayesian Neural Networks [[pdf]](http://ml.informatik.uni-freiburg.de/papers/17-ICLR-LCNet.pdf)
  - Aaron Klein, Stefan Falkner, Jost Tobias Springenberg, Frank Hutter. *ICLR'17*
- Accelerating Neural Architecture Search using Performance Prediction [[pdf]](https://arxiv.org/abs/1705.10823)
  - Bowen Baker, Otkrist Gupta, Ramesh Raskar, Nikhil Naik. *ICLR'18 Workshop*
- Hyperparameter Optimization: A Spectral Approach [[pdf]](https://arxiv.org/abs/1706.00764) [[code]](https://github.com/callowbird/Harmonica)
  - Elad Hazan, Adam Klivans, Yang Yuan. *NIPS DLTP Workshop 2017*
- Population Based Training of Neural Networks [[pdf]](https://arxiv.org/abs/1711.09846)
  - Max Jaderberg, Valentin Dalibard, Simon Osindero, Wojciech M. Czarnecki, Jeff Donahue, Ali Razavi, Oriol Vinyals, Tim Green, Iain Dunning, Karen Simonyan, Chrisantha Fernando, Koray Kavukcuoglu. *Arxiv 1711*


## Contributing
<p align="center">
  <img src="http://cdn1.sportngin.com/attachments/news_article/7269/5172/needyou_small.jpg" alt="We Need You!">
</p>

Please help contribute this list by contacting [me](https://markdtw.github.io/) or add [pull request](https://github.com/markdtw/awesome-architecture-search/pulls)

Markdown format:
```markdown
- Paper Name [[pdf]](link) [[code]](link)
  - Author 1, Author 2, Author 3. *Conference'Year*
```


## License

[![PDM](https://licensebuttons.net/p/mark/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Mark Dong](https://markdtw.github.io/) has waived all copyright and related or neighboring rights to this work.
