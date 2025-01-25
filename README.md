# Time-Series-Research

- **CKAIA(한국인공지능학회) 하계학술대회 포스터 발표 논문**
- **Ajou Softcon(아주대학교 SW융합교육원) 연구부문 장려상**

## 연구 주제
- 일반적으로 시계열 데이터 예측에는 하나의 긴 센서 데이터를 사
용하지만, 의료 데이터에서는 패턴의 유사성을 가지는 여러 환자
의 시계열 데이터를 사용함.
- 환자에 따라 signal data의 형태가 다르지만, 일반적으로 좋은
예측이 가능하도록 resolution의 guidance를 조정해 보고자 함.

## 연구 내용
- 96 time step의 time series sequence가 주어지면, 그 이후
24 time step만큼의 데이터를 예측하는 것이 목표 (forecasting
problem)

## 실험 결과
- 동일한 데이터를 어떤 resolution으로 학습하는지에 따라
학습 성능이 다름.
- 이를 일반화하여 데이터에 적절한 guidance를 알아서 부
여할 수 있다면, 통상적인 time series data에 모두 좋은
성능을 보이는 모델 개발이 가능할 것.
