### mini Team Project<br>
# :star: 수원시 호흡권 개선을 위한 흡연부스 위치 선정 :star: 
<img src="img/home.jpg"/>
1. [main](https://github.com/MaestroYongseok/SmokingArea/blob/main/img/home.jpg) <br>
2. [ppt](https://github.com/MaestroYongseok/SmokingArea/blob/main/1st%20%ED%8C%80%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8(%ED%9D%A1%EC%97%B0%EA%B6%8C)%201%EC%A1%B0.pdf)

## 1. 프로젝트 기간 
- 2023.02.10 ~ 2023.2.22
## 2. 목적 
- 국민들의 건강증진
- 흡연권과 호흡권 보장
- 깨끗한 거리유지

## 3. 데이터
- 흡연부스 설치현황이 나와 있는 서울시 데이터
  - 종속변수 : 흡연구역
  - 독립변수 : 유동인구, 금연구역, 흡연자수, 면적

## 4. 팀구성
- 사용툴 
  - R-Studio / 엑셀(데이터정제)
  <img src="img/rstudio.png"/>
  <img src="img/excel.png"/>

- 팀원 
  - 장수경 / 임광현 / 권용석 / 주강희
- 주요업무 
  - R-Studio를 이용하여 변수간의 상관관계를 분석하여 흡연부스 설치의 최적의 입지조건을 찾음

## 5. 분석과정
- 정규성검정
- 상관분석
- 다중회귀분석
- 모델타당도

## 6. 각 요소별 점수 
- Score =  -7.747+0.00001 X 유동인구
           + 0.0002 X 흡연율
           + 0.2994 X 금연구역
           - 0.3555 X area
           - 0.00357 X 식당수

## 7. 참조
- 논문
  - 이근원, 김주연, "흡연자의행태분석을통한흡연위치및흡연공간의유형에관한연구", 2020.12.20 
  - 노진원, 이예진, "금연구역가이드라인및실외흡연실해외동향", 2020.8
  - 양근영, "흡연부스디자인의 선호도 조사 연구" , 2016.11.04
- 뉴스
  - 각종뉴스

