# 서울 아파트 고가주택 여부 예측용 머신 러닝 모델 제작

## :one: 프로젝트 소개

2017년부터 2021년 서울 부동산 실거래가 데이터를 통해 향후의 서울 아파트 고가주택 여부 예측을 위한 머신 러닝 모델 제작

- Pandas를 이용하여 데이터 전처리 및 Matplotlib, Seaborn을 이용하여 데이터 시각화
- Scikit-Learn을 이용하여 아파트 가격에 대한 다양한 회귀, 분류 모델 제작, 튜닝 및 평가를 통해 최상의 모델 채택
- 채택한 모델을 통해 서울 아파트 고가주택 여부 예측 진행
- 사용 기술
  - Pandas 1.3.5, Scikit-Learn 1.0.2, Seaborn 0.11.2

<br/>

## :two: 프로젝트 결과물

- 결과물 : https://github.com/seahahn/ml/blob/main/seoul_apartment_price.ipynb
- 발표 영상 : https://youtu.be/BUYdITwkobY

<br/>

## :three: 학습 내용

- ### 1. 머신 러닝 모델

  - Linear Regression
  - Ridge Regression
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - Boosting

- ### 2. 모델 튜닝

  - RandomizedSearchCV
  - GridSearchCV

- ### 3. 모델 해석

  - 특성/순열 중요도
  - PDP
  - SHAP
