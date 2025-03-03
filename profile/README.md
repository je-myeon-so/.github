# 📝 제면소 (제대로 된 면접 소개합니다)

## 🚀 개요
LLM 기반 대화형 모의 면접 시스템

AI 기능을 활용하여 사용자의 **이력서를 분석하고 맞춤형 면접 질문을 생성**하는 시스템입니다.  
사용자의 답변을 고려하여 **구체적인 피드백과 개선 사항을 제공**하며,  
**모의 면접을 통해 실전 대비 훈련**을 지원합니다.

## 🎯 주요 기능

### 🎤 AI 기반 모의 면접 시스템

- **경력에 맞춘 면접 질문 생성**
- **TTS(텍스트 음성 변환)로 질문 제공**
- **STT(음성 텍스트 변환)로 사용자의 답변 기록**
- **답변 분석 및 피드백 제공** (문법, 전문성, 발음 분석 포함)
- **구체적인 개선 방안 제안 및 후속 질문 생성**

### 🔍 답변 분석 기능

- **문법 오류 감지 및 교정 제안**
- **전문적인 표현 여부 평가 (구어체, 비격식 표현 감지)**
- **발음 및 유창성 평가 (불필요한 추임새, 발음 오류 감지)**

## 🛠️ 시스템 동작 방식

1. **사용자가 이력서를 업로드** (`PDF` 형식)
2. **AI가 이력서를 분석**
3. **직무에 맞춘 맞춤형 기술 면접 질문을 생성**
4. **TTS를 활용하여 면접 질문을 제공**
5. **사용자가 음성으로 답변하고 STT로 텍스트 변환**
6. **AI가 답변을 분석하여 피드백 제공 및 후속 질문 생성**
7. **최종 평가 및 개선 사항 제공**

## 🏗️ 기술 스택

- **AI 모델**: OpenAI GPT (텍스트 분석 및 질문 생성)
- **음성 처리**: Whisper (STT), Google TTS
- **자연어 처리**: kiwipiepy
- **백엔드**: FastAPI, MySQL
- **프론트엔드**: React.js
- **클라우드**: AWS, Jenkins, Docker

## 🏆 해커톤 정보

- **해커톤 이름**: 카카오테크 판교 해커톤
- **진행 기간**: 3일 (02.26.2025 ~ 02.28.2025)
- **제출 마감일**: 02.28.2025

## 🙋‍♂️ 팀원

- **풀스택**: Maeve.Ji (지연우), Dia.Yoon (윤소윤)
- **인공지능**: Timmy.Park (박정민), Lillian.Rhee (이채언)
- **클라우드**: Sophie.Kim (김민경), Trent.Kwak (곽용우)

## 📌 사용 방법

### 1️⃣ 설치 및 실행

#### 필수 조건

- Python 3.12.7
- OpenAI API, Google Cloud API, AWS 키
- 가상 환경 설정 (`venv` 또는 `conda` 사용 권장)

#### 설치 방법

```bash
git clone https://github.com/je-myeon-so.git
cd je-myeon-so
pip install -r requirements.txt
```
### API 키 설정 + 배포 성공 이후: 

```
open -a "Google Chrome" --args --disable-features=BlockInsecurePrivateNetworkRequests --unsafely-treat-insecure-origin-as-secure=http://your-link-goes-here/ 
```
- 샘플 이력서는 materials 폴더 아래에 있습니다. 예시 데이터와 같이 이력서 구성을 하실 필요는 없습니다. 
## 📷 스크린샷 + 자료
홈 화면
![Welcome Page](je-myeon-so/.github/materials/WelcomeScreen.png)

인터뷰 페이지
![Interview Page](je-myeon-so/.github/materials/Interview.png)

결과 + 분석 페이지
![Results Page](je-myeon-so/.github/materials/Resultspage.png)

### [발표 자료 ppt](https://drive.google.com/file/d/1_XMY_YlbMH5o22Gf_6rNLmscqKlPkvne/view?usp=sharing)
### [시연 동영상](https://drive.google.com/file/d/1iF0lrO08n_0wkf1KT4mlqYLqkHvn1FU6/view?usp=sharing)
