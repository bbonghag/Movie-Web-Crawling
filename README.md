## 코로나 이전 이후의 국내영화 시장 분석🎞🎬📽

### 영화 데이터 웹크롤링 및 분석 프로젝트

-------------

### 🎬Team
- 5명(조장:박한빈, 조원:박재현, 손보영, 전영욱, 이봉학)


### 🎬Introduction
- 영화산업이 코로나로 인해 어떤 변화를 겪었는지, 또는 전체적으로 데이터를 분석했을 때 어떤 요소가 나올지 알고자 영화 산업 웹크롤링 및 분석으로 주제를 선정하였다.
- 영화의 매출과 개봉수, 관객수 등 영화산업의 추이를 알아보고자 크롤링을 통해 데이터를 수집하고 분석하여 인사이트를 도출하는 프로젝트를 진행하였다.


<br/>

### 🎬Data
- [KOBIS 영화관 입장권 통합 전산망](https://www.kobis.or.kr/kobis/business/stat/them/findMonthlyTotalList.do) 
- 년월, 개봉/상영 편수, 매출액, 관객수, 해외 국내 구분 등에 대한 수치 데이터를 크롤링을 통해 수집.

<br/>

### 🎬Methods

#### Progress
- 데이터를 수집할 사이트 선정 
- BeautifulSoup을 사용하여 웹 크롤링, 데이터 수집
- Pandas를 통해 데이터 가공
- Matplotlib, Seaborn, Plotly를 통해 데이터를 시각화 및 인사이트 도출

#### Visualization - 발표자료 참고.
- 연도별 매출액 변화 추이
- 영화 가격 변화
- 연월별 관객수 분포도
- 17~21년 5년간 월별 관객 분포도
- 17~21년 전체 영화 년도/요일별 개봉편수와 매출액
- 17~21년 국내/해외 영화 개봉 편수 비교
- 연도별 상위 50개 영화의 국가별 영화수 비교 및 장르 분석
- 영화 시장의 연도별 국내외 영화 점유율 추이

<br/>


### 🎬Insight
1. 개봉 시기는 목요일이나 금요일을 노리는 것이 좋다
2. 상업적 성과를 위해선 액션과 드라마 위주의 장르로 영화를 만드는 것이 좋다
3. OTT 시장 진출을 통해 수익의 극대화를 노려야 하며, 기존 극장 시장과는 다른 전략을 취해야 한다.


<br/>


### 🎬Discussion
- 

<br/>

### 🎬Requirements and Tools
- Colab, Python 
- BeautifulSoup, Pandas, Matplotlib, Seaborn, Plotly

<br/>

### 🎬References





<!--
연도별 매출액 변화 추이<br/> 
<img src = 'https://user-images.githubusercontent.com/103362361/197702554-eceb496e-6b39-4f41-bad3-f95e44538807.png' width = 40%, height = 40%>

영화 가격 변화<br/>
<img src = 'https://user-images.githubusercontent.com/103362361/197703188-d96108c6-4251-40d2-9e2e-e2e4d7958c47.png' width = 300, height = 200>

연월별 관객수 분포도
<img src = '' width = 40%, height = 40%>

-->
