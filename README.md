# AI-Expert-RL

[인천대학교 (INU)](https://www.inu.ac.kr) AI-Expert 강화학습 실습 코드

## Member

* 박진영 - [DevSlem (Github)](https://github.com/DevSlem)
* 박혜인 - [Hyeeein (Github)](https://github.com/Hyeeein)
* 진성원 - [miner58 (Github)](https://github.com/miner58)
* 이승관 - [SeungGwan123](https://github.com/SeungGwan123)
* 성치웅

## 강화학습 알고리즘

아래 알고리즘의 Reference는 읽을 수 있으면 좋으나 난이도가 높으니 안읽어도 상관 없음.

|Algorithm|Reference|
|---|---|
|[DQN](dqn.ipynb)|[Playing Atari with Deep Reinforcement Learning](https://arxiv.org/abs/1312.5602)|
|[REINFORCE](reinforce.ipynb)|[Reinforcement Learning: An Introduction; 2nd Edition. 2020. Sec 13.3 (326p)](http://www.incompleteideas.net/book/the-book-2nd.html)|
|A2C|[Understanding Actor Critic Methods and A2C](https://towardsdatascience.com/understanding-actor-critic-methods-931b97b6df3f)|

## 읽어보면 좋은 자료

아래 자료 역시 읽을 수 있으면 좋으나 난이도가 높으니 안읽어도 상관 없음.

* DevSlem. [On-policy Prediction with Approximation](https://devslem.github.io/reinforcement-learning/rl-fundamental/on-policy-prediction-with-approximation/).
* DevSlem. [Policy Gradient Methods](https://devslem.github.io/reinforcement-learning/rl-fundamental/policy-gradient-methods/).

## Setup

설치해야하는 라이브러리 목록:

* Python 3.7.15
* PyTorch 1.11.0 - CUDA 11.3
* Tensorboard 2.10.0
* Gym 0.26.2
* IPython Kernel 6.15.0
* Pandas 1.3.5

아래 command를 사용해 한번에 설치:

```
$ conda env create -f conda_env.yaml
$ conda activate ai-expert-rl
```