# 👶 Safe13Baby: 질식사 방지 AI

> 영유아의 질식 사고를 사전에 감지하는 객체 탐지 기반 AI 모델

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![YOLOv5](https://img.shields.io/badge/YOLOv5-FFBF00?style=flat-square&logo=yolo&logoColor=black)
![AzureML](https://img.shields.io/badge/Azure_ML-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)

---

## 📂 프로젝트 개요

Safe13Baby는 영유아가 자는 자세나 환경에서 발생할 수 있는 **질식 위험 상황을 사전에 감지**하는  
AI 모델을 개발하기 위한 프로젝트입니다.  
실시간 객체 탐지 기반으로 위험 자세를 판별하고, 추후에는 알림 시스템과도 연동할 수 있도록 설계되었습니다.

---

## ✅ 주요 기능

- 위험 자세(엎드림, 가림 등) 탐지
- 객체 탐지 기반 모델 (YOLOv5)
- Azure ML을 활용한 모델 배포 파이프라인

---

## 🧠 사용 기술

| 범주 | 기술 |
|------|------|
| 딥러닝 | PyTorch, YOLOv5 |
| 클라우드 | Azure Machine Learning |
| 데이터 | Roboflow (Augmentation + 관리) |
| 기타 | OpenCV, GitHub, VS Code |

---

## 🧪 폴더 구조 예시

```bash
MakeModel/
│
├── dataset/           # 데이터셋 및 전처리
├── training/          # 모델 학습 코드
├── inference/         # 실시간 추론 코드
├── images/            # 시각화용 예시 이미지
├── README.md
└── requirements.txt
