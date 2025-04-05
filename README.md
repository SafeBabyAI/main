#  # <img src="https://github.com/SafeBabyAI/main/raw/main/safebaby_logo.png" width="60" style="vertical-align: middle;"/> SafeBaby: 영유아 질식사 방지 AI


> 영유아의 질식 사고를 사전에 감지하는 객체 탐지 기반 AI 모델

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![YOLOv5](https://img.shields.io/badge/YOLOv5-FFBF00?style=flat-square&logo=yolo&logoColor=black)
![AzureML](https://img.shields.io/badge/Azure_ML-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)

---

## ✨ 프로젝트 요약

- 🙋 **역할**: 모델 설계, 데이터 전처리, 추론 파이프라인 개발
- 🎯 **목표**: 영유아의 질식 위험 상황을 사전에 감지해 생명을 보호하는 AI 솔루션 구축
- 🛠 **기술 스택**: PyTorch, YOLOv5, Roboflow, Azure Machine Learning

---

## 🧸 프로젝트 개요

> 바쁜 사람을 위한 한 줄 요약:  
> **객체 탐지를 활용하여 위험 자세를 실시간 인식하고, 질식사 가능성을 줄이기 위한 AI 솔루션입니다.**

<details>
<summary>클릭해서 전체 보기 👀</summary>

<br/>

### 📍 주제 및 기획의도

<!-- 이미지들 -->
<p align="center">
  <img src="https://github.com/SafeBabyAI/main/raw/main/%EA%B5%AC%EC%A1%B0.jpg" alt="프로젝트 구조" width="100%"/>
  <img src="https://github.com/SafeBabyAI/main/raw/main/%EA%B8%B0%EB%8C%80%ED%9A%A8%EA%B3%BC.jpg" alt="기대효과" width="100%"/>
  <img src="https://github.com/SafeBabyAI/main/raw/main/%EA%B8%B0%ED%9A%8D%EC%9D%98%EB%8F%84%201.jpg" alt="기획의도 1" width="100%"/>
  <img src="https://github.com/SafeBabyAI/main/raw/main/%EA%B8%B0%ED%9A%8D%EC%9D%98%EB%8F%84%202.jpg" alt="기획의도 2" width="100%"/>
  <img src="https://github.com/SafeBabyAI/main/raw/main/%EB%82%B4%EC%9A%A9%201.jpg" alt="내용 1" width="100%"/>
  <img src="https://github.com/SafeBabyAI/main/raw/main/%EB%82%B4%EC%9A%A9%202.jpg" alt="내용 2" width="100%"/>
</p>

</details>

---

## 🎬 시연 영상

[YOLOv5 시연 영상 보기](https://drive.google.com/file/d/1rIH-W9RkA5G87RwHsfuTyewCOeKCIqxq/view?usp=sharing)  
[Gradio 웹 데모 보기](https://drive.google.com/file/d/1KEVt9QPiLnpfwkzKy35ioaZOl2VyqNc2/view?usp=sharing)


## 📜 라이선스

본 프로젝트는 학습 및 포트폴리오 공유 목적의 팀 프로젝트입니다.  
코드와 자료를 사용할 경우 반드시 **출처를 표기**해 주세요.  
상업적 이용은 금지됩니다.

본 프로젝트는 [MIT 라이선스](LICENSE)를 따릅니다.

---

## ✅ 주요 기능

- ✅ YOLOv5 기반의 위험 자세 객체 탐지
- ✅ Azure ML을 통한 클라우드 학습 및 배포
- ✅ Roboflow로 라벨링 및 Augmentation 자동화
- ✅ 실시간 테스트 환경 구성 (Webcam 기반)

---

## 🧠 사용 기술

| 범주 | 기술 |
|------|------|
| 언어 | Python |
| 딥러닝 | PyTorch, YOLOv5 |
| 데이터 | Roboflow |
| 클라우드 | Azure Machine Learning |
| 기타 | OpenCV, GitHub, VS Code |

---

## 🧪 폴더 구조 예시

```bash
MakeModel/
├── dataset/           # 데이터셋 및 전처리
├── training/          # 모델 학습 코드
├── inference/         # 실시간 추론 코드
├── images/            # 결과 시각화 이미지
├── README.md
└── requirements.txt
