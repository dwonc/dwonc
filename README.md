# 안녕하세요! 백엔드 개발자 최동원입니다 👋

**Spring Boot · FastAPI · AI Recommendation · AWS**

12인 팀 리더 경험과 AI 추천 시스템 설계 능력을 갖춘 백엔드 개발자입니다.  
FastAPI 기반 AI 파이프라인 구축 및 AWS 배포 경험을 보유하고 있으며,  
문제 해결 중심 개발로 팀원들의 코드 디버깅과 기술 지원을 담당했습니다.

<br/>

## 🛠 Tech Stack

### Backend
- **Java**, Spring Boot, JPA/Hibernate, Spring Security
- **Python**, FastAPI
- MySQL, Redis

### AI & Data
- LightGBM, SVD (Collaborative Filtering)
- GPT API
- AI 추천 시스템 설계 및 최적화

### Frontend
- React, TypeScript
- React Query
- WebSocket (STOMP)

### DevOps & Infra
- AWS (EC2, RDS, ELB)
- Docker, Redis
- SSL/TLS 인증서 관리

<br/>

## 🚀 Projects

### [IT-DA - AI 추천 회의 플랫폼](https://github.com/dwonc/itda)
> AI 기반 회의 장소 추천 및 실시간 채팅 서비스

**Tech**: Spring Boot, FastAPI, React, LightGBM, SVD, GPT API  
**Role**: 백엔드 개발, AI 추천 시스템 설계, 팀 리더 (12인)  

**Highlights**:
- FastAPI 기반 End-to-End AI 추천 파이프라인 구현
- LightGBM 만족도 예측(45%) + SVD 협업 필터링(30%) + GPT Intent 분석(25%)
- Feature Scaling 및 Intent 가중치 재설계로 추천 점수 분포 정상화
- 실시간 채팅 (WebSocket) 및 세션 관리 구현
- 팀 리더로 프로젝트 기획부터 최종 발표까지 진행

**Key Achievements**:
- 추천 점수 차별화: Match Score 40~60% 집중 → 전체 범위 고르게 분포
- API 안정성: FastAPI 422 Validation Error 100% 해결 (Pydantic AliasGenerator 활용)

<br/>

### [GUGU Market - 중고거래 플랫폼](https://github.com/dwonc/gugumarket)
> 실시간 채팅 및 결제 통합 중고거래 서비스

**Tech**: Spring Boot, React, WebSocket, AWS  
**Role**: 풀스택 개발, AWS 배포 및 운영  

**Highlights**:
- WebSocket (STOMP) 기반 1:1 실시간 채팅 구현
- Spring Security + JWT 인증 시스템 구축
- AWS EC2 + RDS + Let's Encrypt SSL 배포
- 페이징 및 정렬 로직 구현으로 대용량 데이터 처리 최적화

**Key Achievements**:
- HTTP 4xx 오류 96% 감소: 422 Validation Error 해결 (DTO 양방향 변환 통일)
- AWS 배포 장애 대응: Environment Health Severe → Ok 복구 (API prefix 및 재배포 전략)
- 실시간 채팅 안정성 확보: JWT 기반 connect 인증 및 destination 동적 생성

<br/>

## 💡 Problem Solving

### AI 추천 점수 차별화 문제
**문제**: Match Score가 40~60%에 집중되어 추천 품질 저하  
**해결**: Feature Scaling 조정 + Intent 가중치 재설계  
**결과**: 점수 분포 0~100% 전체 범위로 정상화, 추천 정확도 개선

### FastAPI - Spring Boot 통신 422 Error
**문제**: Spring ↔ FastAPI 간 API 호출 시 422 Unprocessable Entity 에러  
**해결**: Pydantic AliasGenerator로 snake_case ↔ camelCase 자동 변환  
**결과**: API 요청 성공률 100%, 데이터 변환 로직 단순화

### AWS 배포 환경 Health Severe 장애
**문제**: AWS Elastic Beanstalk 배포 후 HTTP 4xx 에러 96% 발생  
**해결**: API prefix 중복(/api/api) 제거, 구조 수정 후 재배포  
**결과**: Environment Health: Ok, 서비스 정상 운영

<br/>

## 🌱 Currently Learning

**AI 심화 과정 수강 중** (2026.03 ~ 2026.05)
- LangChain, RAG (Retrieval-Augmented Generation)
- 생성형 AI 서비스 개발
- Vector Database 활용 (Pinecone, Chroma)

**학습 목표**:
- IT-DA AI 추천 시스템에 RAG 적용
- 회의록 자동 생성 및 검색 기능 고도화

<br/>

## 📫 Contact

- **Email**: dwonc2@naver.com
- **Portfolio**: [포트폴리오 PDF](https://drive.google.com/file/d/1Bf077GlO2zrz9Rs6Az2itggm1Vf7QXOI/view?usp=drive_link)
- **GitHub**: [@dwonc](https://github.com/dwonc)

<br/>

## 🎯 Career Goal

**Backend Engineer 성장 로드맵**

1. **문제 정의 중심 사고 강화**: 단순 기능 구현이 아닌 "확장 가능한 구조 설계"
2. **클라우드·컨테이너 환경 심화**: AWS 아키텍처 설계 및 Kubernetes 오케스트레이션 이해
3. **성능 및 안정성 최적화**: 캐싱 전략(Redis), DB 쿼리 튜닝, 비동기 처리
4. **AI를 활용하는 백엔드 엔지니어**: 추천 시스템, 데이터 기반 서비스 개선 역량 강화

---

<div align="center">

**"확장 가능한 구조"로 문제를 해결하는 백엔드 개발자가 되겠습니다.**

</div>
