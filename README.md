# 2020 제 1회 CAU 응용통계학과 분석 공모전

# 1. 개요
- 주제: TV 프로그램이 골목 상권에 미치는 영향 분석 및 예측
- 수상: 우수상 (16개 팀 중 3위)
- 기간: 2020.09 ~ 2020.11
- 팀원: 김성관, 박준근, 정서연, 황재원
- 사용 skill: Python, R

<img width="1232" alt="스크린샷 2021-11-03 오후 1 51 29" src="https://user-images.githubusercontent.com/79994991/140011472-e40ee2e1-63eb-47f2-9dfe-98cbf55d7dda.png">

# 2. 데이터 전처리 
- Raw Data
- 공공데이터 (서울시 열린 데이터 광장)
  - 서울시 우리마을가게 상권분석서비스(상권-추정매출) (https://data.seoul.go.kr/dataList/OA-15572/S/1/datasetView.do)
  - 서울시 우리마을가게 상권분석서비스(상권-추정유동인구) (https://data.seoul.go.kr/dataList/OA-15568/S/1/datasetView.do)    
- 크롤링: 골목식당 식당 상권별 출현 회차 크롤링

### 3. 데이터 전처리

**`기본 데이터 전처리`**

- **추정 매출 데이터 생성**
    
    데이터를 불러와 칼럼 이름을 통일해주고 데이터를 병합합니다. 병합 후 업종 구분 칼럼을 추가해주었습니다.
    
    이 후, 방송에 출연한 점포의 데이터를 추출하고 상권별로 데이터를 정리하였습니다.
        
- **추정 유동인구 데이터 생성**
    
    매출 데이터와 마찬가지로 데이터를 불러와 필요한 칼럼을 뽑고, 상권별 데이터로 정리해주었습니다.
    

  


# 3. 분석
