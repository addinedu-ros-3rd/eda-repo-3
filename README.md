# :tram: 서울시 지하철 이용인원 정보를 활용한 역별 특성 분석 및 승하차 인원 예측

## :train: 프로젝트 개요

### 작업 기간
2023.09.06 ~ 2023.9.13 (7일)

### 구성원 및 담당
- 강한얼(PM) : 데이터 수집 및 전처리 / 데이터 EDA / 머신러닝 모델 학습 / PPT 제작
- 조태상 : 데이터 전처리 / 데이터 EDA / PPT 제작 / crawling(not use)
### 주제 선정
 - 퇴근시간 가산디지털단지역에서 7호선을 타려면 1~2대의 지하철을 보내야 한다. 널널하게 지하철을 이용할 수 있는 시간대는?
 - 또한 모델 학습을 통해서 지하철 승하차 인원을 예측하면?
### 주요 내용
- 서울시 지하철 승하차 인원과 날씨 데이터를 이용하여 지하철 승하차에 영향을 미치는 원인을 분석하고, 미래 지하철 이용자 수를 예측해본다.
### 결론
- EDA를 통해 지하철 승하차 인원에 영향을 미치는 변수 탐색 
- 미래 지하철 이용자 수를 예측하는 머신러닝 모델 학습 결과 분석
## :station: 프로젝트 내용

### 개발 환경
- pandas 2.0.3
- numpy 1.23.5
- seaborn 0.12.2
- matplotlib 3.7.2
- koreanize matplotlib 0.1.1
- Southkorea
- lightbgm
- shap
### 데이터 수집
#### 데이터 출처 및 설명
 - 서울교통공사 연도별 일별 시간대별 역별 승하차 인원
   - [주소링크](https://data.seoul.go.kr/dataList/OA-12921/F/1/datasetView.do)
   - 수집 기간 2018 ~ 2022 (5년)
   - 서울 교통공사 관할 지하철 1 ~ 8 호선
   - 1시간 간격 승하차 인원 정보
   - 데이터 형태

![2](https://github.com/addinedu-amr-4th/eda-repo-3/assets/104709955/ead67793-8cd5-4d76-a940-b3a22babe6c9)
 - 서울교통공사 지하철역 주소 및 전화번호 정보
    - [주소링크](http://data.seoul.go.kr/dataList/OA-12035/A/1/datasetView.do)
    - 지하철역의 위치를 알아내기 위해 사용
    - 데이터 형태
 
 ![5](https://github.com/addinedu-amr-4th/eda-repo-3/assets/104709955/dc1af260-28e6-4bf4-8369-f0c4c9d26700)
 - 종관기상관측(ASOS)
   - [주소링크](https://data.kma.go.kr/data/grnd/selectAsosRltmList.do?pg) 
   - 수집 기간 2018 ~ 2022 (5년)
   - 서울 특별시 관측소 수집 기상 데이터
   - 날씨를 파악하기 위해 정해진 시각에 모든 관측소에서 관측을 같은 시각에 실시하는 지상관측
   - 데이터 형태
 
 ![7](https://github.com/addinedu-amr-4th/eda-repo-3/assets/104709955/4bbfbe74-0756-4538-bdbe-2838f9b32a3a)
#### DB 관계도


### 지하철 탑승 인원 EDA
- 실행 코드
- 결과 샘플

### 지하철 역별 군집화
- 실행 코드
- 결과 샘플

### 지하철 탑승 인원 예측
- 실행 코드
- 결과 샘플

## :train2: 결론
-
-
