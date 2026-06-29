# Titanic Survival Prediction

타이타닉 승객의 객실 등급, 나이 구분, 성별 정보를 이용해 생존 여부를 예측하는 분류 프로젝트입니다.

## Problem

승객의 기본 정보를 바탕으로 `survived` 값을 예측합니다. 단순히 전체 정확도만 높이는 것보다 실제 생존자(`yes`)를 얼마나 놓치지 않는지 recall/F1-score까지 함께 확인하는 데 초점을 두었습니다.

## Data

- Train: 1,800 rows
- Test: 401 rows
- Features: `status`, `age`, `sex`
- Target: `survived`

## Models

- Decision Tree
- Random Forest
- AdaBoost
- Gradient Boosting

## Evaluation

주요 평가지표는 다음과 같습니다.

- Accuracy
- Precision / Recall / F1-score
- Confusion Matrix

## What This Shows

- 범주형 데이터 전처리
- Pipeline 기반 모델링
- 단일 트리와 앙상블 모델 비교
- 클래스별 성능 해석

## Files

- `titanic_survival_prediction.ipynb`: 정리된 분석 노트북
- `data/titanic_train.csv`: 학습 데이터
- `data/titanic_test.csv`: 테스트 데이터
