<p align="center"><img src="asset/header.png"></p>

# 🔥 Lending Club Project
## 개요

- 랜딩 클럽 고객 데이터를 회귀 분석한 후, 고객의 부도 확률을 예측하는 모델을 설계한다.
- 설계한 모델을 바탕으로 대출 여부를 결정하는 적절한 전략을 기획한다.


## 세부 내용

### Data preprocessing

- 더미변수 처리
- 다중공선성 예방
- 이상치 제거
- 데이터 정규화

### Variable Selection

- 사용 모델: `Lasso` `ElasticNet`
- 파라미터 alpha값 선택 기준 : MSE (최소값)

### Measurement of Expected Default Frequency

- 절차
  1. Optimal threshold 설정
  2. 이익/손실 비교
  3. 가중치 채택
  4. 최적 모델 선정
- 사용 모델: `Logistic Regression` `Decision Tree` `Random Forest`

### 최종 모델 : `Logistic Regression`
