# COVID-19 감염으로 인한 사망자 수 예측 
---
## 주제 및 목표
* COVID-19관련 DATA(백신접종자 수, 주간 병원 수용 가능 환자 수, 양성환자 비율 등)를 통해 COVID-19감염으로 인한 사망자 수를 예측하고자 한다.
---
## 목적 및 기획의도
* COVID-19감염으로 인한 사망자 수 예측에 중요한 변수는 무엇인지 알아보고, 
 적합한 모델을 fitting 하여 한국, 일본, 미국, 유럽, 아시아 등의 COVID-19감염으로 인한 사망자 수를 예측

![코로나 확진자](https://user-images.githubusercontent.com/98293593/167098390-4e973209-91a0-480c-981a-b9dbbf1b6359.PNG)

---

## 데이터 수집
* [공식 사이트](https://ourworldindata.org/)![image](https://user-images.githubusercontent.com/102526342/169969687-e3837e23-607d-4d06-b380-2a3006f45b19.png)
)![Uploading image.png…]()

 * 전체 확진자 수, 위중증 환자 수, 1차 + 2차 + 부스터샷 누적 접종자 수, 엄격성지수(학교/직장 닫음, 여행금지 등, 0~100), 주간 병원 수용 가능 환자 수, 감염 재생산지수 등
 

## 사용할 Library or Tool

1. Python
    - matplotlob.pyplot
    - seaborn
    - pandas 
    - selenium
    - Beautiful Soup
    - sklearn


2. Tableau
    - 시각화를 위한 Tool
   
## 모델 선정 및 평가
- Linear Regression, GBM, XGboost를 통해 모델링
- r-squared, rmse를 통해 모델 평가

## 구현 및 시연
- ppt작성 및 발표 준비 
