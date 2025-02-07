# Prediction and Statistical Analysis of Birth Rate through National Development Indicators
[건국대학교 응용통계학과 제 4회 추계학술대회] 국가 개발 지표를 통한 출생률 예측 및 통계 분석

# 🏨 국가 개발 지표를 통한 출생률 예측 및 통계 분석
### [🔗프로젝트 결과 보고서](https://github.com/sseoyun/Prediction-and-Statistical-Analysis-of-Birth-Rate/blob/main/%EA%B5%AD%EA%B0%80%20%EA%B0%9C%EB%B0%9C%20%EC%A7%80%ED%91%9C%EB%A5%BC%20%ED%86%B5%ED%95%9C%20%EC%B6%9C%EC%82%B0%EC%9C%A8%20%EC%98%88%EC%B8%A1%20%EB%B0%8F%20%ED%86%B5%EA%B3%84%20%EB%B6%84%EC%84%9D_%EA%B9%80%EB%AF%B8%EA%B9%80%EB%AF%B8.pdf)

<br>

## 📅 진행 일정
### 2023.9.8 ~ 2023.10.15


<br>

## ✍ 프로젝트 소개 및 진행 방법
### 패널데이터인 국가 개발 지표 데이터를 이용해 저출산 문제가 심각한 한국의 출산률을 예측하고 클러스터링을 통해 다른 국가의 사례를 벤치마킹하고자 함
* 출생률에 영향을 미치는 요인 파악
* 출생률 추이에 따른 클러스터링
* 출생률 예측 모형 개발 및 예측

### 방법론
1. 데이터 전처리: 결측치 처리(시계열 보간법), 변수 생성 및 삭제, 스케일링
2. 탐색적 데이터 분석 (EDA): 변수 간 상관관계 분석 및 시각화
3. 시계열 클러스터링: K-means 클러스터링, Elbow Method 및 Silhouette Score를 통한 적절한 군집 개수 선택
4. 단변량 시계열 모델링: ARIMA 모델을 사용한 예측
5. 다변량 시계열 모델링: VAR 모델을 사용한 클러스터별 출생률 예측
  
<br>

## 🛠 기술 스택

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white">
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=Jupyter&logoColor=white">
  <img src="https://img.shields.io/badge/Numpy-013243?style=for-the-badge&logo=Numpy&logoColor=white">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=Pandas&logoColor=white">
  <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white">
  <img src="https://img.shields.io/badge/Statsmodels-6B2EAF?style=for-the-badge&logo=Statsmodels&logoColor=white">
</p>



<br>

## 🔎 진행하면서 아쉬웠던 점 및 배웠던 점
* ML 모델과 Statistic 모델을 함께 사용함으로써 클러스터링으로 유사한 출생률 특성을 가진 그룹을 식별하고, 각 클러스터에 최적화된 통계 모델을 적용하여 예측 정확도를 높임
* 결측치가 매우 많아 정확한 분석과 예측에 어려움을 겪음
* Features의 스케일링의 한계로 변수 선택 과정에 있어 어려움 겪음
