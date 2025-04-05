# 👶 Safe13Baby: 질식사 방지 AI

> 영유아의 질식 사고를 사전에 감지하는 객체 탐지 기반 AI 모델

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![YOLOv5](https://img.shields.io/badge/YOLOv5-FFBF00?style=flat-square&logo=yolo&logoColor=black)
![AzureML](https://img.shields.io/badge/Azure_ML-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)

---

## 🧸 프로젝트 개요

<details>
<summary>클릭해서 전체 보기 👀</summary>

<br/>

### 📍 주제 및 기획의도

<!-- 1. 구조 -->
<p align="center">
  <img src="https://github.com/SafeBabyAI/main/raw/main/%EA%B5%AC%EC%A1%B0.jpg" alt="프로젝트 구조" width="100%"/>
</p>

<!-- 2. 기대효과 -->
<p align="center">
  <img src="https://github.com/SafeBabyAI/main/raw/main/%EA%B8%B0%EB%8C%80%ED%9A%A8%EA%B3%BC.jpg" alt="기대효과" width="100%"/>
</p>

<!-- 3. 기획의도 1 -->
<p align="center">
  <img src="https://github.com/SafeBabyAI/main/raw/main/%EA%B8%B0%ED%9A%8D%EC%9D%98%EB%8F%84%201.jpg" alt="기획의도 1" width="100%"/>
</p>

<!-- 4. 기획의도 2 -->
<p align="center">
  <img src="https://github.com/SafeBabyAI/main/raw/main/%EA%B8%B0%ED%9A%8D%EC%9D%98%EB%8F%84%202.jpg" alt="기획의도 2" width="100%"/>
</p>

<!-- 5. 내용 1 -->
<p align="center">
  <img src="https://github.com/SafeBabyAI/main/raw/main/%EB%82%B4%EC%9A%A9%201.jpg" alt="내용 1" width="100%"/>
</p>

<!-- 6. 내용 2 -->
<p align="center">
  <img src="https://github.com/SafeBabyAI/main/raw/main/%EB%82%B4%EC%9A%A9%202.jpg" alt="내용 2" width="100%"/>
</p>


</details>

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
