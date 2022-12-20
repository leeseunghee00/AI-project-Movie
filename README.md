# 2021 천안 AI중급과정 Final Project

### 1. 프로젝트 주제
영화산업의 흥행요소 데이터 분석

### 2. 프로젝트 내용
영화 흥행요소로 배우, 감독, 장르, 배급사, 스크린수를 변수로 정해서 분석을 진행한다.
장르별 배우에 따른 매출액과 스크린수, 배급사 파워, 영화 개봉시기 등의 분석을 통해 가중치를 설정한다.
가중치 설정에 추가 요소로 영화 평점을 하는데, 이때 각 영화의 평점은 크롤링을 통해 데이터를 가져와 사용한다.
이러한 데이터 분석을 통한 흥행요소의 관계성을 알아보고자 한다.

### 3. 데이터 출처
|사이트|사용한 데이터|주소|
|---|---|---|
|KOBIS|2004 ~ 2020년 영화목록|https://www.kobis.or.kr/kobis/business/main/main.do|
|NAVER Movie|각 영화당 평점 크롤링|https://movie.naver.com/|
|NAVER News|영화 개봉 일주일 전 기사수 크롤링|https://news.naver.com/|

### 4. Language & Modeling
- Language : Python
- Modeling
  - Module : pandas, folium, json, matplotlib, seaborn
  - Model : Heat-map, Polynomial Regression, Q-Q plot, AIC, Stepwise
