# 안녕하세요, 백엔드 개발자 최동원입니다 👋

부트캠프에서 팀 리더를 맡아 6명과 함께 프로젝트를 진행했습니다.  
Spring Boot로 백엔드를 개발하고, FastAPI로 AI 추천 시스템을 구현했습니다.

<br/>

## 🛠 Tech Stack

**Backend**  
Java, Spring Boot, JPA, Python, FastAPI, MySQL, Redis

**AI & Data**  
LightGBM, SVD, GPT API

**Frontend**  
React, TypeScript, WebSocket

**DevOps**  
AWS (EC2, RDS, ELB), Docker, SSL

<br/>

## 🚀 Projects

### [IT-DA](https://github.com/dwonc/it-da) - AI 모임 추천 플랫폼
AI로 모임을 추천하고 실시간 채팅을 지원하는 서비스입니다.

**기술**: Spring Boot, FastAPI, React, LightGBM, GPT API  
**역할**: 백엔드 개발, AI 시스템 설계, 팀 리더

**주요 작업**
- FastAPI로 AI 추천 API 구현 (LightGBM + SVD + GPT)
- 추천 점수가 40~60%에 몰리는 문제를 Feature Scaling으로 개선
- Spring Boot와 FastAPI 간 422 에러를 Pydantic으로 해결
- WebSocket으로 실시간 채팅 구현

<br/>

### [GUGU Market](https://github.com/dwonc/gugumarket-frontend) - 중고거래 플랫폼
실시간 채팅과 결제 기능이 있는 중고거래 서비스입니다.

**기술**: Spring Boot, React, WebSocket, AWS  
**역할**: 풀스택 개발, AWS 배포

**주요 작업**
- WebSocket으로 1:1 실시간 채팅 구현
- Spring Security + JWT 인증 구현
- AWS EC2 + RDS로 배포하고 Let's Encrypt로 SSL 적용
- 배포 후 API 경로 중복 문제 해결

<br/>

## 💡 해결한 문제들

**추천 점수 차별화**  
추천 점수가 40~60%에만 나와서 추천된 모임 간의 차이가 안 보였습니다.  
Feature Scaling 방식을 바꾸고 Intent 가중치를 조정해서 점수 분포를 고르게 만들었습니다.

**FastAPI 422 에러**  
Spring Boot에서 FastAPI로 요청할 때 계속 422 에러가 났습니다.  
Pydantic의 AliasGenerator를 써서 snake_case와 camelCase를 자동 변환하게 했습니다.

**AWS 배포 장애**  
배포 후 HTTP 4xx 에러가 계속 발생했습니다.  
API 경로가 /api/api로 중복되는 걸 찾아서 수정하고 재배포했습니다.

<br/>

## 🌱 Currently Learning

**AI 심화 과정** (2026.03 ~ 2026.05)
- LangChain, RAG
- 생성형 AI 서비스 개발
- Vector Database

IT-DA에 RAG를 적용해서 회의록 검색 기능을 만들어볼 예정입니다.

<br/>

## 📫 Contact

- **Email**: dwonc2@naver.com
- **Portfolio**: [PDF 보기](https://drive.google.com/file/d/1Bf077GIO2zrz9Rs6Az2itggm1Vf7QXOl/view?usp=drive_link)

<br/>

---

**"문제를 제대로 정의하고 구조적으로 해결하는 개발자가 되고 싶습니다."**
