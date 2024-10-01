# Walmart 데이터 분석

## 1. 프로젝트 개요
[Kaggle의 Wallmart 데이터셋](https://www.kaggle.com/datasets/devarajv88/walmart-sales-dataset)분석 프로젝트입니다. 데이터 전처리, 탐색적 데이터 분석(EDA)을 통한 데이터의 분포를 확인하고 VIP고객 도출 및 지역별 구매고객 특징을 파악하여 마케팅 전략을 도출합니다.
이 프로젝트의 목표는 주어진 데이터의 분포를 분석하여 주요 특징을 도출하고, 이를 바탕으로 마케팅 전략을 제시하는 것입니다.

## 2. 데이터 설명
- 데이터 출처:[Kaggle의 Wallmart 데이터셋](https://www.kaggle.com/datasets/devarajv88/walmart-sales-dataset)
- 데이터 상세: 약 55만개의 사용자 거래 내역과 10개의 컬럼(550068, 10)
  - `User_ID`: 사용자 ID
  - `Product_ID`: 구매품목 ID
  - `Gender`: 성별
  - `Age`: 나이대
  - `Occupation`: 직업(수치로 대체)
  - `City_Category`: 도시(A,B,C)
  - `StayInCurrentCityYears`: 도시에 거주한 기간
  - `Marital_Status`: 결혼여부
  - `ProductCategory`: 물건 카테고리(수치로 대체)
  - `Purchase`: 구매금액
 
## 3. 분석 과정
1) 탐색적 데이터 분석
   - 전반적 데이터 특징
   - 나이에 따른 매출액 차이
   - 제품카테고리 탐색
   - plotly 활용 데이터 시각화
  
## 4. 주요 결과 및 성과
- VIP 고객의 주요 특징 발굴 및 그에 따른 마케팅 전략 제언
- 지역별 소비 패턴 분석을 통한 매출 강화 전략 제언

## 5. 필요한 라이브러리
- pandas
- seaborn
- plotly

