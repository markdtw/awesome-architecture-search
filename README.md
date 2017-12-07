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
  - Bowen Baker, Otkrist Gupta, Nikhil Naik and Ramesh Raskar. *ICLR'17*
- Efficient Architecture Search by Network Transformation [[pdf]](https://arxiv.org/abs/1707.04873) [[code]](https://github.com/han-cai/EAS)
  - Han Cai, Tianyao Chen, Weinan Zhang, Yong Yu and Jun Wang. *AAAI'18*
- Learning Transferable Architectures for Scalable Image Recognition [[pdf]](https://arxiv.org/abs/1707.07012) [[nasnet]](https://github.com/tensorflow/models/tree/master/research/slim/nets/nasnet)
  - Barret Zoph, Vijay Vasudevan, Jonathan Shlens and Quoc V. Le. *Arxiv 1707*
- Practical Network Blocks Design with Q-Learning [[pdf]](https://arxiv.org/abs/1708.05552)
  - Zhao Zhong, Junjie Yan and Cheng-Lin Liu. *AAAI'18*

### Evolutionary Algorithm
- Large-Scale Evolution of Image Classifiers [[pdf]](https://arxiv.org/abs/1703.01041)
  - Esteban Real, Sherry Moore, Andrew Selle, Saurabh Saxena, Yutaka Leon Suematsu, Jie Tan, Quoc Le and Alex Kurakin. *ICML'17*
- Genetic CNN [[pdf]](https://arxiv.org/abs/1703.01513) [[code]](https://github.com/aqibsaeed/Genetic-CNN)
  - Lingxi Xie and Alan Yuille. *ICCV'17*
- Hierarchical Representations for Efficient Architecture Search [[pdf]](https://arxiv.org/abs/1711.00436)
  - Hanxiao Liu, Karen Simonyan, Oriol Vinyals, Chrisantha Fernando and Koray Kavukcuoglu. *Under review ICLR'18*

### Others
- DeepArchitect: Automatically Designing and Training Deep Architectures [[pdf]](https://arxiv.org/abs/1704.08792) [[code]](https://github.com/negrinho/deep_architect)
  - Renato Negrinho and Geoff Gordon. *Arxiv 1704*
- &ast;SMASH: One-Shot Model Architecture Search through HyperNetworks [[pdf]](https://arxiv.org/abs/1708.05344) [[code]](https://github.com/ajbrock/SMASH)
  - Andrew Brock, Theodore Lim, J.M. Ritchie and Nick Weston. *Under review ICLR'18*

## Hyper-Parameter Search
- Speeding up Automatic Hyperparameter Optimization of Deep Neural Networksby Extrapolation of Learning Curves [[pdf]](http://ml.informatik.uni-freiburg.de/papers/15-IJCAI-Extrapolation_of_Learning_Curves.pdf) [[code]](https://github.com/automl/pylearningcurvepredictor)
  - Tobias Domhan, Jost Tobias Springenberg and Frank Hutter. *IJCAI'15*
- Hyperband: A Novel Bandit-Based Approach to Hyperparameter Optimization [[pdf]](https://arxiv.org/abs/1603.06560)
  - Lisha Li, Kevin Jamieson, Giulia DeSalvo, Afshin Rostamizadeh and Ameet Talwalkar. *ICLR'17*
- Learning Curve Prediction with Bayesian Neural Networks [[pdf]](http://ml.informatik.uni-freiburg.de/papers/17-ICLR-LCNet.pdf)
  - Aaron Klein, Stefan Falkner, Jost Tobias Springenberg and Frank Hutter. *ICLR'17*
- Accelerating Neural Architecture Search using Performance Prediction [[pdf]](https://arxiv.org/abs/1705.10823)
  - Bowen Baker, Otkrist Gupta, Ramesh Raskar and Nikhil Naik. *Under review ICLR'18*
- Hyperparameter Optimization: A Spectral Approach [[pdf]](https://arxiv.org/abs/1706.00764) [[code]](https://github.com/callowbird/Harmonica)
  - Elad Hazan, Adam Klivans and Yang Yuan. *NIPS DLTP Workshop 2017*
- Population Based Training of Neural Networks [[pdf]](https://arxiv.org/abs/1711.09846)
  - Max Jaderberg, Valentin Dalibard, Simon Osindero, Wojciech M. Czarnecki, Jeff Donahue, Ali Razavi, Oriol Vinyals, Tim Green, Iain Dunning, Karen Simonyan, Chrisantha Fernando and Koray Kavukcuoglu. *Arxiv 1711*


## Contributing
<p align="center">
  <img src="http://cdn1.sportngin.com/attachments/news_article/7269/5172/needyou_small.jpg" alt="We Need You!">
</p>

Please help contribute this list by contacting [me](https://markdtw.github.io/) or add [pull request](https://github.com/markdtw/awesome-architecture-search/pulls)

Markdown format:
```markdown
- Paper Name [[pdf]](link) [[code]](link)
  - Author 1, Author 2 and Author 3. *Conference'Year*
```


## License

[![PDM](https://licensebuttons.net/p/mark/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Mark Dong](https://markdtw.github.io/) has waived all copyright and related or neighboring rights to this work.
