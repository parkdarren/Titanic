# Titanic Survival Prediction

타이타닉 승객의 객실 등급과 나이 구분 및 성별 정보를 이용해 생존 여부를 예측한 분류 프로젝트입니다. 많이 알려진 예제 데이터지만 단순히 정확도만 보는 대신 생존 클래스의 recall과 F1-score까지 함께 확인하는 방식으로 정리했습니다.

## 문제 정의

주어진 승객 정보로 `survived` 값을 예측합니다.

- Train: 1800 rows
- Test: 401 rows
- Features: `status`·`age`·`sex`
- Target: `survived` (`yes`·`no`)

## 분석 흐름

- 생존 여부와 성별 및 객실 등급별 분포 확인
- 범주형 변수 One-Hot Encoding
- Decision Tree와 앙상블 모델 비교
- Accuracy·precision·recall·F1-score 확인
- Confusion matrix로 오분류 패턴 확인

## 사용 모델

- Decision Tree
- Random Forest
- AdaBoost
- Gradient Boosting

## 사용 기술

* Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## 파일 구성

```text
titanic_survival_prediction.ipynb
data/
  titanic_train.csv
  titanic_test.csv
```

## 정리

이 프로젝트는 입문형 분류 문제를 통해 전처리와 파이프라인 구성 및 모델 비교와 분류 지표 해석을 연습한 작업입니다. 대표 프로젝트라기보다 머신러닝 기본기를 보여주는 보조 프로젝트로 두는 것이 적합합니다.
