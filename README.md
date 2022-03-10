# [ &#128081; Dataton &#128081; ]
2022.03.08 부터 2022.03.11 까지 강남 Aiffel에서 주최하는 Dataton에 참여하게 되었습니다.

< H&M DATA EDA/Personalized-Fashion-Recommendation >
- 강태원 : 데이터 원본 가공, 시각화(연령, 제품 분류)
- 민진원 (발표) : 전처리, 시각화,
- 박지호 : 데이터 전처리, 시각화 (색상, 연령, 뉴스 수신 여부)
- 이민선 (조장) : 전처리, 시각화 (우편번호, PCA, GMM)
## &#128085; Introduction
현재 진행중인 Kaggle Competition에서 H&M이 제공하는 데이터를 선택했습니다.
Competiotion의 목적은 H&M 고객 맞춤형 추천시스템을 구축하는 것으로 저희조도 이에 부합하는 EDA를 진행했습니다.
해당 데이터셋을 선택한 이유는 제품정보, 고객정보, 거래정보 데이터 및 이미지 데이터를 제공 받아 다양한 EDA가 가능하기 때문입니다.

## &#128086; Contents
01. Gender 컬럼 생성

02. 월별 Top 10 이미지 파일 시각화

03. 기간별 매출

04. 계절별 매출

05. Customer Age

06. Color

07. sales_channel_id

08. Department_name

09. Garment Group Name

10. Index Goup Name

11. Club Member Status

12. Fashion_News_Frequency

13. Postal Code 

14. 계절성(seasonality)을 띄는 제품을 PCA와 Clustering을 활용한 시각화

15. PCA(Principal Component Analysis)

16. GMM(Gaussian Mixture Models)/가우시안 혼합 모델

17. EDA를 통한 인사이트

## &#128095; feature discussion
(original features)
- t_dat : 주문 날짜 ('2019-09-30' ~ '2018-10-01')
- customer_id : 고객 id (고객 수 : 974,367 명)
- article_id : 상품 id (상품 수 : 71,396 가지)
- price : 상품 가격 (0.000017 ~ 0.591525)
- sales_channel_id : 판매 루트 (1 또는 2 / 판매 루트에 대한 정확한 정보는 없음)
- colour_group_name : 컬러명
- perceived_colour_master_name: 채도명
- index_group_no : 상품 용도 분류 코드
- index_group_name : 상품 용도 분류 ('Ladieswear', 'Divided', 'Menswear', 'Sport', 'Baby/Children')
- department_name: 상품 세부 용도 분류
- garment_group_name : 상품 카테고리 분류명 (총 21개 / ex 'Skirts', 'Knitwear', 'Accessories')
- club_member_status : 멤버쉽 상태 ('ACTIVE', 'PRE-CREATE', 'LEFT CLUB')
- fashion_news_frequency : ('Regularly', 'NONE', 'Monthly')
- age : 나이 (16 ~ 99세)
-  postal_code:우편번호(암호화되어 있음)

(additional features)
- age_segment:연령대(10대, 20대, 30대,...)
- month:주문 월
- year_month:년와 월만 표시(201810)
- season:계절(spring,summer, fall, winter)
- postal_code:우편번호(암호화되어 있음)


## &#128140;
&#128147; 강태원 : 우리조의 단합력이 좋아 프로젝트 과정이 정말 즐거웠고 데이터 자체를 좀 깊게 이해해 보는 시간이 되었음

&#128153; 민진원 : 

&#128155; 박지호 : 이번 기회에 처음으로 큰 데이터로 깊게 프로젝트를 진행해 보았는데 전처리 과정과 EDA과정에 대해서 재미를 느끼고 많이 배우게 된 뜻깊은 시간이 되었음. 조원들 덕분에 많이 배우고 데이터 이해에 대한 시각도 넓어졌음. 우리조 커뮤니케이션 능력도 최고 !!

&#128156; 이민선 : 
