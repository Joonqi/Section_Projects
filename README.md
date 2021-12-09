## AIB Section Project
코드스테이츠 AI 부트캠프 3기로 공부하면서 진행한 프로젝트 결과물입니다.

# S1 Game Data Analysis

[Game Data Analysis](https://www.notion.so/S1_Game-Data-Analysis-ef398a08ea11459bbbd4043dc5b3d41d)

#### 1. 프로젝트 목적  
1990년 이후 발매된 게임들의 매출액 데이터를 바탕으로 **'다음 분기에는 어떤 게임을 개발해야 할까?'** 라는 질문에 답변을 구합니다.  
해당 데이터는 게임별 출시 플랫폼, 발매 연도, 장르, 북미/유럽/일본/기타 시장에서의 매출액 정보를 포함하고 있습니다.

#### 2. 프로젝트 가설
- 지역에 따라 선호하는 게임의 장르가 다르다.
- 연도에 따라 게임의 트렌드가 존재한다.

#### 3. 프로젝트 세부사항  
- Pandas를 통한 데이터 핸들링, EDA
- Scipy를 활용한 통계 검정 방식 활용 (카이제곱 검정, F 검정)
- Matplotlib & Seaborn을 활용한 데이터 시각화

#### 4. 프로젝트 결과  

**액션 장르**의 **닌텐도 계열 플랫폼** 게임을 개발하는 것이 가장 매출이 높을 것으로 기대  

---

# S2 Water Potability Classification

3276개 수원에서 채취된 물의 9가지 수질 측정 데이터를 바탕으로 해당 수원의 물이 식용수로 적절한지 여부를 추정합니다.  

[Water Potability Classification](https://www.notion.so/S2_Water-Potability-Classification-c90f9439a4324919a6492512b9b2e600)  

Data source : 🔗[Kaggle Water Potability dataset](https://www.kaggle.com/adityakadiwal/water-potability)

- pandas, matplotlib, seaborn을 이용한 EDA, 전처리
- 로지스틱 회귀모델, 의사결정나무, 랜덤포레스트, AdaBoost, XGBoost 모델을 만들고 성능확인
- 특성중요도, PDP plot을 통해 결과 시각화

캐글에 공개된 water-potability 데이터셋을 바탕으로 분석을 진행했습니다.

