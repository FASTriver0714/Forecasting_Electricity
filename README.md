# ⚡ NewJeanse

> 지능형 전력 에너지 예측 및 관리 플랫폼

전력 사용량과 요금 정보를 OCR로 인식하고, AI 기반 예측 모델을 통해 미래의 에너지 소비를 예측하는 플랫폼입니다.

## 📌 프로젝트 기간
2024.07 ~ 2024.08

## 🧑‍💻 팀 구성 및 역할
- 팀원: 5명 (FrontEnd 2, BackEnd 1, AI/ML 1, 팀장)
- 내 역할: **DA, AI/ML**

## 🌟 주요 기능
- 공공데이터 기반 전력/기상 데이터 수집
- OCR 기반 고지서 이미지 인식 (Clova API)
- AI 모델 (RandomForest, LGBM, LSTM 등) 앙상블 예측
- FastAPI로 모델 배포 및 예측값 출력

## 🧰 기술 스택
- Python, Google Colab
- Flask, FastAPI
- HTML, CSS, JavaScript
- MongoDB

## 🔧 내가 담당한 부분
- 전처리 및 분석 : 공공 데이터 정제 및 병합, 보간, 데이터 분석 및 시각화
- 모델: 다양한 알고리즘 앙상블 및 Stacking Regressor 구성
- FE : FE 로직 구성 

## 🔄 트러블슈팅
- Overfitting 문제 → 정규화, 교차검증, 메타 모델 구성으로 해결
- 예측 성능 개선: R², MAE 기준으로 모델 평가 및 성능 최적화

## 📎 관련 자료
- 📄 [보고서](https://drive.google.com/file/d/1BxhSisosWZmpgFkI6GUgSyyMtCxgVAzz/view)
- 🎥 [소개 영상](https://youtu.be/PrKwHrUoJ6k)
- 🖼️ [발표자료](https://drive.google.com/file/d/17LtDSpaJEBe0pcmoabOuH1aoc9mVJGlv/view)
