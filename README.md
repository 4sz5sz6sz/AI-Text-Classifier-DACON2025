🤖 AI vs 사람 텍스트 분류
DACON 2025 SW중심대학 디지털 경진대회

한국어 AI 생성 텍스트 탐지 모델

📋 프로젝트 개요
DACON 2025 대회를 위한 AI 텍스트 분류 프로젝트입니다. AI가 생성한 글과 사람이 작성한 글을 구별합니다.

🚀 주요 기능
한국어 텍스트 분류 모델
성능 최적화 및 개선
다양한 특성 추출 기법
🏆 대회 정보
- **평가지표**: AUC
- **데이터**: 한국어 텍스트
- **목표**: AI vs 사람 텍스트 분류

## 📥 데이터 다운로드
대용량 데이터 파일(500MB+)은 GitHub에 포함되지 않습니다.
데이터는 [DACON 대회 페이지](https://dacon.io/competitions/official/236473/data)에서 다운로드하세요.

```
data/
├── train.csv (500MB+)
├── test.csv
└── sample_submission.csv
```

## 📁 프로젝트 구조

```
AI-Text-Classifier-DACON2025/
├── README.md                                        # 프로젝트 설명
├── train.csv, test.csv, sample_submission.csv       # 대회 데이터
├── [Baseline]_TF-IDF....ipynb                      # � 현재 작업용 노트북
│
├── baseline/                                        # 베이스라인 참고
│   └── [Baseline]_TF-IDF....ipynb
│
└── archive/                                         # 완료된 실험 아카이브
    ├── (예시)250701_juwon_xgboost/
    │   └── example.ipynb
    ├── (예시)250701_tfidf_xgboost_baseline/
    │   ├── experiment.ipynb                         # 실제 실험 노트북
    │   └── README.md                                # 실험 결과 정리
    └── (예시)250702_bert_korean/
```

## � 작업 방식
1. **실험 개발**: 최상위 노트북에서 작업
2. **실험 완료**: `archive/YYMMDD_실험명/` 폴더로 아카이브  
3. **결과 정리**: 각 폴더의 `README.md`에 AUC, 특징, 개선점 기록

## 📝 폴더명 규칙
`YYMMDD_모델명_특징` (예: `250701_tfidf_xgboost_baseline`)

---

> **"AI를 탐지하는 AI"** 🛡️