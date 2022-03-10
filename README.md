# [ Dataton ]
2022.03.08 부터 2022.03.11 까지 강남 Aiffel에서 주최하는 Dataton에 참여하게 되었다.
- 강태원 : 데이터 원본 가공, 시각화(연령, 제품 분류)
- 민진원 (발표) : 전처리, 시각화,
- 박지호 : 데이터 전처리, 시각화 (색상, 연령, 뉴스 수신 여부)
- 이민선 (조장) : 전처리, 시각화 (우편번호, PCA, GMM)
## Introduction
현재 진행중인 Kaggle Competition에서 H&M이 제공하는 데이터를 선택했습니다.
Competiotion의 목적은 H&M 고객 맞춤형 추천시스템을 구축하는 것으로 저희조도 이에 부합하는 EDA를 진행했습니다.
해당 데이터셋을 선택한 이유는 제품정보, 고객정보, 거래정보 데이터 및 이미지 데이터를 제공 받아 다양한 EDA가 가능하기 때문입니다.

## Contents






## feature discussion
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
- age_segment:연령대(10대, 20대, 30대,...)
- month:주문 월
- year_month:년와 월만 표시(201810)
- season:계절(spring,summer, fall, winter)
- postal_code:암호화되어 있음
