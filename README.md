# 2021 년도 빅데이터 분석 전문가 고급과정 제출 과제

## 프로젝트 설명
본 프로젝트는 한국데이터산업진흥원 주체 2021 년도 빅데이터 분석 전문가 고급과정의 제출 과제입니다.
Python Anaconda 의 Jupyter notebook 으로 작성하였으며,

데이터 분석 방식은 통계적 분석 기법과 더불어 관련 머신러닝, 딥러닝을 종합한 앙상블 모델을 구축하였고,<br>

데이터 전처리시 고려한 점으로는 75 : 25 비율의 불균형한 데이터 특성에 맞추어 언더 샘플링, 오버 샘플링 등을 고려하여 적용하였습니다.<br>

파라미터 학습시 고려한 점으로는 머신러닝 알고리즘의 경우는 그리드 서치 방식을 적용하여 파라미터를 최적으로 탐색하는 작업을 자동화 하였습니다.<br>

과제의 주제는 보험 사기 탐지(빅데이터 이상 데이터 탐지) 및 XAI(Explainable AI) 구축입니다.

## 성과 설명
Kaggle 보험 사기 감지 데이터셋 활용.
기존 랭킹상 97% 정확도를 기록한 모델을 기준으로,
평균 정확도 96%, 최고 정확도 98.7% 의 성능을 달성하였습니다.

# 코드 샘플
### 데이터 시각화
![화면 캡처 2025-04-02 133558](https://github.com/user-attachments/assets/8ea5c6e0-288c-49d1-82dd-95c889b0179b)


### 데이터 전처리
![화면 캡처 2025-04-02 133640](https://github.com/user-attachments/assets/a6a8fc3d-1889-421a-bffc-b444eee0f028)


### 데이터 불균형 파악 및 샘플링을 통한 해소
![화면 캡처 2025-04-02 133715](https://github.com/user-attachments/assets/5f0ea07d-202d-4522-a065-ec74d967ddd1)
![화면 캡처 2025-04-02 133945](https://github.com/user-attachments/assets/f81b9c50-4833-44bf-a939-c055a0a7d1a2)


### 상관도 분석을 통한 데이터 특징 선별
![화면 캡처 2025-04-02 133840](https://github.com/user-attachments/assets/641d3317-16e2-46e1-be18-8b54c62a0c13)


### 그리드 서치를 통한 최적 파라미터 탐색 자동화
![화면 캡처 2025-04-02 134041](https://github.com/user-attachments/assets/c08b3dac-8896-4da9-934a-debe21d7daa0)


### 결과에 영항을 끼치는 특징 시각화, 선별, 분석
![화면 캡처 2025-04-02 134133](https://github.com/user-attachments/assets/c71dd6c3-a1e7-4dce-8fc4-2d2a5526425b)
