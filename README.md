# Hotel_Review

학번: 201604045

이름: 김 무 혁

### 중국문화데이터포트폴리오

## 호텔 리뷰 분석
**분석 배경**

최근 빅데이터(Big Data)를 활용하여 소비자에게 소비재 정보를 추천하거나 소비재를 이용한 다른 고객의 리뷰를 실시간으로 확인할 수 있는 등의 앱 기반의 비즈니스 시장의 변화가 빠르게 이루어지고 있는데, 호텔의 경우도 호텔의 시설이나 서비스 수준을 사전에 확인하는 것은 제한적이기 때문에 다른 사람의 온라인 리뷰에 대한 의존도가 높은 분야 중 하나임.

**분석 목적**

호텔 예약 사이트 내의 호텔 리뷰를 텍스트마이닝 방법을 통해 
만족과 불만족으로 강하게 나타난 단어들을 추출하고 분석해 
시설, 서비스, 입지 등 여러측면에서 호텔 만족도에 영향을 미치는
요인들을 다각도로 탐색해보고자 함. 이를 통해 최근 여행자들에게서 나타난 새로운 니즈가 무엇이고, 
호텔 만족도에 큰 영향을 미치는 요인이 무엇인지에 대해 파악하고자 함.

**분석 대상 및 방법**

+ 데이터 수집 대상 : 트립어드바이저(호텔예약사이트) 내 제주도 호텔 리뷰(2019.01-2020.10)

+ 총 수집 건수 : 2,014

+ 분석 대상에 관한 형태소 분석 진행

**데이터스키마**

![KakaoTalk_20201125_011933204](https://user-images.githubusercontent.com/74213615/100122164-6fd6a780-2ebc-11eb-98c5-94a1e7f1d441.png)

**형태소분석결과 피벗테이블 완성**

![KakaoTalk_20201201_211428205](https://user-images.githubusercontent.com/74213615/100739313-3f41c100-341a-11eb-8686-686bab0b76ae.png)

**데이터 분석 (품사별 형태소분석)**

명사/형용사/동사 별로 데이터 추출 진행


