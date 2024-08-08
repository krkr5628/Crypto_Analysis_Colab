**# 설명**
- 최종 학습 모델 : TCN, TRANSFORMER
- 최대 RAM 24GB 이하 구동하도록 모델 축약 필요(지표 분석 xgboost 제외)
- 예측을 위해 5 ~ 6개월 데이터 필요
- 모델 예측 확률 기반 시간 분석 1 : KST(02:30 ~ 04:30, 07:00 ~ 08:00)
- 모델 예측 확률 기반 시간 분석 2 : KST(13:30 ~ 15:00, 17:30 ~ 21:00)
- 기준 시점에서 60분 이내에 1.1% 이상 상승하는 경우가 3% 미만 발생
  => 시간을 180분으로 증가, 수익 1.1% 이상, 매매 횟수 유지
  => 시간을 60분으로 유지, 수익 0.6% 이상, 매매 횟수 유지
  => 시간을 60분으로 유지, 수익 0.6% 이상, 매매 횟수 2배 증가

**# 목적과 도구**
1. 목적
- 특정 상품에 특화된 모델 제작
- 특정 상품의 레버리지 진입으로 수익 실현(20x, 1%, 1.1%)
- 전략 시간 파악
- 전략 지표 파악

2. 테스트 모델
a) TCN(단일 학습)
b) Transformer(추가 학습)

3. 테스트 도구
a) Colab TPU
b) Kaggle TPU
c) ChatGPT 4o

**# 기본 태스트 결과**
![image](https://github.com/user-attachments/assets/5ce58ace-419f-4447-8d00-27b9ee45bf05)

**# 분석(FULL VERSION)**
- DATA : 1/1 SIZE
- Colab TPU : MAX 

**#지표**

![image](https://github.com/user-attachments/assets/4f39bf82-eb18-487a-8b38-c6b28ed25850)
