# 코로나 확진자 예측 및 확진자 대비 사망자 수 예측 프로젝트 (선진국과 비교)
---
## 주제 및 목표
* 코로나 확진자, 코로나 확진자 대비 사망자의 수를 예측을 정확도 높게 예측 모델을 만든다.
---
## 목적 및 기획의도
* 2년동안 이어진 코로나 기간동안 확진자 수의 많은 변화가 있었습니다. 그에 따른 사망자 수 또한 많은 변화가 있었는데 그 지표를 예측하고자 합니다.

![코로나 확진자](https://user-images.githubusercontent.com/98293593/167098390-4e973209-91a0-480c-981a-b9dbbf1b6359.PNG)

## 예측 모델을 만드는데 있어서 의문점
* 단순히 코로나 확진자 수에 따라 예측이 가능할까?
  * 연령별, 성별, 혹은 유행하는 바이러스 종류, 나라에 따라서 비율이 다르지 않을까? 라는 의문이 들었습니다.

## 데이터 수집
* [공식 사이트](http://ncov.mohw.go.kr/index.jsp, '코로나 확진자 공식 사이트') 

## 사용할 Library or Tool

1. Python
- matplotlob.pyplot
- pandas 
- selenium
- Beautiful Soup
- sklearn
  * Decision Tree, train_test_split

2. Tableau
- 시각화를 위한 Tool
