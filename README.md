# 📊 BigData-Practice-TIL (Today I Learned)

빅데이터 분석 이론을 넘어, 실제 데이터를 다루며 파이프라인을 구축해 보는 **실무형 빅데이터 분석 실습 저장소**입니다. 
매일 꾸준히 코드를 작성하며 데이터 수집부터 전처리, 머신러닝 예측 모델링까지의 전체 과정을 기록합니다.

## 🛠 Tech Stack
- **Language**: Python
- **Environment**: Jupyter Notebook (VS Code), macOS
- **Data Processing**: Pandas, NumPy
- **Machine Learning**: Scikit-Learn
- **Big Data / NLP (예정)**: PySpark, KoNLPy 등

---

## 📂 Directory Structure & Roadmap

진행할 실습의 큰 카테고리와 로드맵입니다. 각 폴더 안에는 일차별(`DAY01~`) 주피터 노트북 파일이 기록됩니다.

### [01_Data_Collection] 데이터 수집 및 적재
- 공공데이터포털 API 연동 및 대용량 데이터 수집
- 모바일 핀테크 앱 가상 사용자 로그 데이터 추출
- 웹 크롤링 및 NoSQL 연동 맛보기

### [02_BigData_Processing] 대용량 데이터 전처리 및 EDA
- Pandas를 활용한 결측치/이상치 처리 및 데이터 정제
- 앱 결함(Defect) 데이터 및 시계열 로그 데이터 변환 파이프라인 구축
- 탐색적 데이터 분석(EDA) 및 주요 통계량 시각화

### [03_Machine_Learning] 머신러닝 예측 모델링
- 지도학습(분류/회귀)을 활용한 고객 이탈 예측 모델 구축
- 비지도학습(군집화)을 활용한 사용자 세그먼테이션
- 평가지표(F1-Score, 혼동행렬 등)를 통한 모델 성능 검증 및 최적화

### [04_NLP_Text_Analysis] 비정형 텍스트 분석
- 서비스 리뷰 및 피드백 텍스트 데이터 전처리
- 형태소 분석 및 워드클라우드 시각화
- AI 긍정/부정 감성 분석 모델 구현
