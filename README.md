# Hotel_Review

학번: 201604045

이름: 김무혁

### 중국문화데이터포트폴리오

## 호텔 리뷰 분석

호텔 예약 사이트 내의 호텔 리뷰를 텍스트마이닝 방법을 통해 
만족과 불만족으로 강하게 나타난 단어들을 추출하고 분석해 
시설, 서비스, 입지 등 여러측면에서 호텔 만족도에 영향을 미치는
요인들을 다각도로 탐색해보고자 함. 이를 통해 최근 여행자들에게서 나타난 새로운 니즈가 무엇이고, 
호텔 만족도에 큰 영향을 미치는 요인이 무엇인지에 대해 파악하고자 함.

+ 데이터 수집 대상 : 트립어드바이저 내 제주도 호텔 리뷰(2019.01-2020.10)

+ 총 수집 건수 : 2,014

**데이터스키마**

![KakaoTalk_20201125_011933204](https://user-images.githubusercontent.com/74213615/100122164-6fd6a780-2ebc-11eb-98c5-94a1e7f1d441.png)

**형태소분석결과 피벗테이블 완성 (명사 상대빈도 상위10)**

![KakaoTalk_20201201_211428205](https://user-images.githubusercontent.com/74213615/100739313-3f41c100-341a-11eb-8686-686bab0b76ae.png)

**데이터 코딩**

![데이터 코딩](https://user-images.githubusercontent.com/74213615/101506089-5f442800-39b8-11eb-8f8c-6060185d4240.png)

**상관관계 분석 결과**


각 변수간의 상관관계 분석을 통해 서로 영향을 미치는 변수가 있는지 확인함.  -평가, 종아요, 작성시간, 숙박시기가 서로 상관이 있음을 통계적으로 확인하였음.( .01 < P)
