# 안녕하세요! AI의 이론과 구현, 그리고 서비스화를 연결하는 엔지니어입니다. 👋

<br>

저는 딥러닝 논문의 핵심 아이디어를 직접 구현하고(Transformer, ViT, SAM2 등), 실제 서비스로 만들어내는 End-to-End 개발 경험을 보유한 AI 엔지니어입니다.

- 💡 **Modular RAG**와 **`LangGraph`** 등 최신 LLM 아키텍처를 활용한 문제 해결에 관심이 많습니다.
- 🚀 **CV(OCR)**와 **NLP(RAG)** 기술을 융합하여 복잡한 도메인의 문제를 해결하는 프로젝트를 주도했습니다.
- 📈 이론에 그치지 않고, `FastAPI`, `Docker`, `AWS`를 통해 실제 사용 가능한 서비스로 배포하고 운영한 경험을 중요하게 생각합니다.

<br>

## 🛠️ Tech Stack

### AI / ML
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-000000?style=for-the-badge&logo=langchain&logoColor=white)
![Llama3](https://img.shields.io/badge/Llama3-010000?style=for-the-badge&logo=meta&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![YOLO](https://img.shields.io/badge/YOLO-00FFFF?style=for-the-badge&logo=yolo&logoColor=black)

### Backend & DevOps
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

### Database
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![ChromaDB](https://img.shields.io/badge/Chroma-5B23EC?style=for-the-badge&logo=chroma&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-4B309A?style=for-the-badge&logo=facebook&logoColor=white)

### Frontend
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

<br>

## 🚀 Key Projects

### 1. LawAI: 법률 도메인 특화 RAG 서비스
> 법률 문서(판례, 법령)를 기반으로 정확한 답변을 제공하는 AI 서비스
> 
- **[RAG]** `Llama3` 기반, `Langchain`과 `Langgraph`를 활용한 **모듈형 RAG(Modular RAG)** 아키텍처를 기획하고 구현하여 복잡한 질의에 대한 답변 성능을 고도화했습니다.
- **[CV]** `ViT`와 `Transformer`를 결합한 OCR 모델을 구현하여, 스캔된 법률 문서의 텍스트 인식 정확도를 높이고 RAG 시스템의 입력 데이터로 활용했습니다.
- **[Infra]** `FastAPI`로 모델 서빙 API를 구축하고 `Docker`, `AWS EC2` 환경에 배포하여 서비스 운영 경험을 쌓았습니다.
- **[DB]** `ChromaDB`와 `FAISS`를 활용하여 법률 문서 임베딩 및 벡터 검색 시스템을 구축했습니다.

### 2. AI 딥러닝 논문 리뷰 및 구현
> 주요 AI 논문의 핵심 아키텍처를 리뷰하고 PyTorch/TensorFlow로 직접 구현
> 
- `Transformer`: Multi-Head Attention, Encoder-Decoder 구조 구현
- `Vision Transformer (ViT)`: Patch Embedding, Transformer Encoder 구현
- `YOLO (v8, v11)`: C2f 모듈, PANet 구조 등 리뷰
- `Segment Anything Model (SAM2)`: Promptable Segmentation 아키텍처 리뷰
- `2-Stage Detector (e.g., Faster R-CNN)`: RPN, RoI Align 구현

### 3. 커스텀 객체 탐지 모델 (YOLO)
> YOLO 모델을 활용하여 특정 도메인의 객체 탐지 모델을 학습 및 구현
> 
- **[Use Case]** `YOLOv11` 기반 친구 얼굴 인식, `YOLOv8` 기반 군함/일반 선박 식별
- **[Data]** LabelMe(JSON) 형식의 어노테이션 데이터를 `YOLO(.txt)` 포맷으로 변환하는 전처리 파이프라인을 구축했습니다.

<br>

## 💼 Experience

### AIMMO (2023.04 ~ 2025.03)
**AI 데이터 구축 프로젝트 리더 (PM)**
- 자율주행, 스마트팩토리 등 도메인의 AI 학습 데이터 구축 프로젝트 10여 개 리딩
- 프로젝트 일정, 인력(10~100명) 및 품질 관리(QA) 총괄
- 데이터 라벨링 실무자 대상 기술 교육 및 가이드라인 제작

<br>

## 🏆 Activities & Competitions

- 퀀텀 AI 경진대회
- AI 신약 개발 경진 대회
- 동원 X 카이스트 AI Competition

<br>

## 📊 GitHub Stats

![[YOUR_GITHUB_USERNAME]'s GitHub stats](https://github-readme-stats.vercel.app/api?username=[YOUR_GITHUB_USERNAME]&show_icons=true&theme=radical)
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=[YOUR_GITHUB_USERNAME]&layout=compact&theme=radical)](https://github.com/anuraghazra/github-readme-stats)

<br>

## 📫 Contact

- **Email:** `your-email@gmail.com`
- **Blog:** `https://your-blog.io`
- **Portfolio:** `https://[YOUR_GITHUB_USERNAME].github.io`
