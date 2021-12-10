# RDPG,PPO,A2C 앙상블 트레이더
 ## SP500 trading of SOTA reinforcement learning Ensemble Agent
 
- 도구

  [![파이썬 Badge](https://img.shields.io/badge/python-3776AB?style=flat-square&logo=python&logoColor=white&link=mailto:wjtls01@naver.com)](mailto:wjtls01@naver.com)

  [![파이토치 Badge](https://img.shields.io/badge/pytorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white&link=mailto:wjtls01@naver.com)](mailto:wjtls01@naver.com)

  [![주피터 Badge](https://img.shields.io/badge/jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white&link=mailto:wjtls01@naver.com)](mailto:wjtls01@naver.com)

- 목표: 앙상블을 사용함으로써 단일에이전트의 휴리스틱한 전략보다 하락장과 상승장에서 안정적으로 트레이딩

- 구현 이유: 강화학습 논문중 Deep Reinforcement Learning for Automated stock Trading :An Ensemble Strategy 라는 논문을 보게 됐고,
  이 프로젝트를 완료하게 된다면 A2C,RDPG,PPO 만 사용하는 것이 아니라 여러 SOTA 에이전트 사용 및 유동적인 팩터를 사용하는 트레이더를 구현할수 있을것이라 생각하여 진행
  
 
## 기능

- API와 csv를 사용하여 비트코인 또는 SP500데이터 호출
- Env 클래스 생성 (리워드 계산 및 전처리)
- A2C 에이전트 (강화학습)
- PPO 에이전트 (강화학습)
- DDPG 에이전트 (강화학습)
- optimize (over fitting 방지를 위한 clip gradient 사용)
- 에이전트 앙상블 (sharpe ratio 사용)


## 흐름




## 본론
Ddpg 고른이유
It is simple compared to other states of the arts (SOTA) algorithms and serves as a good example for the DRL algorithms in ElegantRL. Due to the simplicity, the user could focus more on the stock trading strategy, and selects the best algorithm from backtesting.
Unlike DQN, it is able to deal with continuous rather than discrete state and action space, thus can trade over a large stock set.

## 결론

## 한계 및 개선
