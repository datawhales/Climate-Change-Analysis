# Climate-Change-Analysis
다양한 기후 데이터를 이용하여 지구의 기후 변화 패턴에 대한 분석을 진행한 프로젝트입니다. (2021.09)

## Goal
현재 기후 변화와 지구 온난화는 세계적으로 큰 문제라고 할 수 있습니다.

지구 온난화가 정말로 심각해지고 있는지, 지구 온난화에 영향을 주는 요인으로 알려져 있는 이산화탄소 농도는 어떻게 변화하고 있는지 등을 데이터를 통해 직접 확인하고자 합니다.

또한, 지구 온난화와 관련이 있다고 알려져 있는 요인들 사이의 상관 관계를 분석하여 실제로 이들이 관련이 있는지 알아내고자 합니다.

## Data
분석에 사용한 데이터의 종류는 다음과 같습니다.
- 지구 표면 온도 데이터 ([Link](https://www.kaggle.com/datasets/berkeleyearth/climate-change-earth-surface-temperature-data))
- 지구 평균 CO_{2} 농도 데이터 ([Link](https://gml.noaa.gov/ccgg/trends/gl_data.html))
- CO_{2} 방출량 데이터 ([Link](https://github.com/owid/co2-data))
- 자연 재해 데이터 ([Link](https://www.kaggle.com/datasets/dataenergy/natural-disaster-data))

## Summary
지구 온난화와 관련된 데이터를 수집하고, 가공하여 분석을 진행하였습니다.

지구의 평균 CO_{2} 농도를 통해 지구 평균 온도 예측 모델을 학습하였고, 이를 통해 지구 평균 온도가 5도 이상 상승하여 위험해지는 시점을 예측해 보았습니다.