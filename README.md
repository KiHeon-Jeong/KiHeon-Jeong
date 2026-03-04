<h1 align="center">KiHeon-Jeong 포트폴리오</h1>
<p align="center"><b>KiHeon-Jeong</b> Portfolio</p>

---

## 🌝 Intro
안녕하세요, **"항상 새로운 것을 배우고 도전하는"** KiHeon-Jeong 입니다.

데이터 기반 문제 해결에 관심이 많고, 분석 결과를 실제 서비스 연결까지 완성하는 것을 지향합니다.

아래 섹션에서 프로젝트 내용을 확인하실 수 있습니다.

## 🔧 Tools
<p>
  <img src="https://img.shields.io/badge/RStudio-75AADB?style=flat-square&logo=RStudio&logoColor=white"/>&nbsp;
  <img src="https://img.shields.io/badge/SPSS-052FAD?style=flat-square&logo=IBM&logoColor=white"/>&nbsp;
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/>&nbsp;
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=MySQL&logoColor=white"/>&nbsp;
</p>

## 📧 Contact
<p>
  <a href="mailto:rlgjs19@gmail.com">
    <img src="https://img.shields.io/badge/contact%20me-rlgjs19%40gmail.com-EA4335?style=flat-square&logo=Gmail&logoColor=white"/>
  </a>
</p>

## 📋 Projects
진행했던 프로젝트입니다.

### 01. AI 기반 통합 면역·영양 맞춤 케어 서비스
> 데이터 기반 면역 취약도 예측과 영양 분석을 통해 요양원 입소자 관리를 위한 맞춤형 케어 가이드를 제공하는 통합 관리 플랫폼  
> 수행 기간: 2026.01.20 ~ 2026.02.27  
> 수행 역할: 팀장(PM), 프로젝트 기획 및 분석 총괄, Frontend 구현, Backend 연동

<details>
  <summary><strong>🛠 Tech Stack 보기</strong></summary>

  <br>

  #### **Frontend**
  React 18 · TypeScript · Vite 5 · Tailwind CSS · Radix UI

  #### **Backend (API / Serving)**
  FastAPI · Pydantic · joblib
  - 학습 모델 로드 및 추론 API 제공

  #### **Modeling (ML)**
  pandas · numpy · scikit-learn
  XGBoost · LightGBM · CatBoost · Optuna
  matplotlib · seaborn
  - 데이터 전처리, 학습, 파이프라인 구성, 검증

</details>

<details>
  <summary><strong>📌 핵심 내용 및 기대 효과 보기</strong></summary>

  <br>

  **핵심 내용**

  1. 면역 관리
     - MIMIC-IV 임상 지표 기반 면역 취약도 예측
     - 고위험군 조기 분류 모델 구현

  2. 영양 관리
     - 식품 영양 성분 데이터 연동
     - 결핍 요소 분석 및 맞춤 영양/식단 가이드 제공

  3. 감염병 대응
     - 유행성 질환 대응 매뉴얼 가이드 제공

  4. 서비스 구현
     - 대시보드 기반 통합 관리 UI
     - 관리자 전용 화면 및 상태 시각화 제공

  **기대 효과**

  - 데이터 기반 의사결정 지원
  - 고위험군 조기 관리로 감염 리스크 감소
  - 요양원 내 운영 효율 향상

</details>

### 🔗 Repositories

<p>
  <a href="https://github.com/KiHeon-Jeong/Immune_Project">
    <img src="https://img.shields.io/badge/Immune_Model-181717?style=flat-square&logo=github&logoColor=white"/>
  </a>
  <a href="https://github.com/KiHeon-Jeong/Nutrition_project">
    <img src="https://img.shields.io/badge/Nutrition_Model-181717?style=flat-square&logo=github&logoColor=white"/>
  </a>
  <a href="https://github.com/KiHeon-Jeong/Webservice_Project">
    <img src="https://img.shields.io/badge/Web_Service-181717?style=flat-square&logo=github&logoColor=white"/>
  </a>
</p>

---

### 02. MIMIC 기반 Sepsis 예측 프로젝트
> MIMIC-IV 코호트를 기반으로 패혈증/사망 위험을 예측하는 모델링 및 웹서비스 연동 프로젝트  
> 수행 기간: 2026.01 ~ 2026.02  
> 수행 역할: EDA, 모델링, API/Frontend 연동

<details>
  <summary><strong>🛠 Tech Stack 보기</strong></summary>

  <br>

  #### **Data / EDA**
  SQL (Oracle) · Python · pandas · numpy · Jupyter

  #### **Modeling (ML)**
  scikit-learn · LightGBM · (실험 기반) XGBoost

  #### **Web Integration**
  Flask · React · Vite
</details>

<details>
  <summary><strong>📌 핵심 내용 및 기대 효과 보기</strong></summary>

  <br>

  **핵심 내용**

  1. MIMIC-IV 기반 코호트 구성 및 임상 변수 전처리
  2. 패혈증/사망 예측 모델 학습 및 성능 검증
  3. Flask API와 React UI를 연동한 예측 서비스 구현

  **기대 효과**

  - 임상 의사결정 지원을 위한 위험도 정량화
  - 고위험군 조기 식별을 통한 대응 속도 향상
  - 분석 결과를 실제 서비스 화면까지 연결
</details>

### Repositories

<p>
  <a href="https://github.com/KiHeon-Jeong/Sepsis-detect-project">
    <img src="https://img.shields.io/badge/MIMIC_EDA%26Modeling-181717?style=flat-square&logo=github&logoColor=white"/>
  </a>
  <a href="https://github.com/KiHeon-Jeong/Sepsis-detect-project_Web-service">
    <img src="https://img.shields.io/badge/MIMIC_Web_Service-181717?style=flat-square&logo=github&logoColor=white"/>
  </a>
</p>

---

### 03. DR 기반 Diabetic Retinopathy 예측 프로젝트
> 안저 이미지 기반 당뇨망막병증 분류 모델 개발 및 웹 추론 서비스 구축 프로젝트  
> 수행 기간: 2026.01 ~ 2026.02  
> 수행 역할: EDA, 모델링, Streamlit 서비스 구현

<details>
  <summary><strong>🛠 Tech Stack 보기</strong></summary>

  <br>

  #### **Data / EDA**
  Python · pandas · numpy · Jupyter

  #### **Modeling (DL)**
  PyTorch · torchvision · ResNet50 · EfficientNet-B3

  #### **Web Integration**
  Streamlit · Pillow
</details>

<details>
  <summary><strong>📌 핵심 내용 및 기대 효과 보기</strong></summary>

  <br>

  **핵심 내용**

  1. 안저 이미지 데이터셋 EDA 및 라벨/품질 점검
  2. DR 분류 모델(ResNet50/ENB3) 실험 및 성능 비교
  3. Streamlit 기반 이미지 추론 서비스 구현

  **기대 효과**

  - 이미지 기반 DR 위험 판별 자동화
  - 모델 결과의 시각적 해석 지원(Grad-CAM 기반)
  - 분석-모델-서비스까지 일관된 파이프라인 확보
</details>

### Repositories

<p>
  <a href="https://github.com/KiHeon-Jeong/Diabetic-Retinopathy-detect-project">
    <img src="https://img.shields.io/badge/DR_EDA%26Modeling-181717?style=flat-square&logo=github&logoColor=white"/>
  </a>
  <a href="https://github.com/KiHeon-Jeong/Diabetic-Retinopathy-detect-project_Web-service">
    <img src="https://img.shields.io/badge/DR_Web_Service-181717?style=flat-square&logo=github&logoColor=white"/>
  </a>
</p>
