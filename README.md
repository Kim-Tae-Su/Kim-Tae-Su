<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rounded&color=gradient&height=120&section=header&text=Backend%20%2F%20Platform%20Engineer&fontSize=36&fontAlignY=50" />
</p>

<p align="center">
  <b>운영 안정성 · 데이터 정합성 · 성능 개선에 집중하는 개발자</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Backend-Flask%20%7C%20FastAPI-blue" />
  <img src="https://img.shields.io/badge/Database-MySQL-orange" />
  <img src="https://img.shields.io/badge/Infra%20%2F%20Ops-Docker%20%7C%20ELK-green" />
  <img src="https://img.shields.io/badge/Data%20%2F%20AI-TensorFlow%20%7C%20scikit--learn%20%7C%20LangChain-6B46C1" />

</p>

---

## About Me

테스트 자동화 플랫폼을 개발하고 있는 백엔드 개발자입니다.

비동기 테스트 실행, 결과 수집, 대용량 로그 처리 등
자동화 서비스의 핵심 백엔드를 담당하며
운영 안정성, 데이터 정합성, 성능 개선을 중심으로 시스템을 설계해 왔습니다.

장애를 단순 대응이 아닌 구조적 원인 분석으로 해결하고,
재발을 방지하는 시스템을 설계하는 것을 지향합니다.



---

## Tech Stack

### Backend
![Flask](https://img.shields.io/badge/Flask-black?logo=flask)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi)

### Database
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql)

### Infra / Ops
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![ELK](https://img.shields.io/badge/ELK-005571?logo=elastic)

### Data / AI
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-6B46C1?logo=chainlink&logoColor=white)

### System / Native (Windows)
![C++](https://img.shields.io/badge/C++-00599C?logo=cplusplus)
![Visual%20Studio](https://img.shields.io/badge/Visual%20Studio-5C2D91?logo=visualstudio)
![MFC](https://img.shields.io/badge/MFC-0078D4)

---


## Experience

### 고영테크놀러지 (2023.01 ~ 2025.04)
**제어 / SW 엔지니어**
- C/C++ 기반 Windows 제어 애플리케이션 설계 및 개발
- TCP/IP 소켓 통신 및 맞춤형 통신 프로토콜 구현을 통한 데이터 송수신 처리
- 멀티스레드 기반 데이터 처리 로직 설계 및 성능 최적화
- 자동화 시스템 운영 시퀀스 개발 및 유지보수
- Python 기반 데이터 수집·처리 자동화, 분석 및 AI 모델 파이프라인 개발

**주요 프로젝트**
- **DDS 기반 실시간 데이터 수집·처리 파이프라인 구축**
  - 실시간 생산 데이터 수집 및 분산 처리 구조 설계·구현
  - 👉 [프로젝트 상세](https://github.com/Kim-Tae-Su/KohYoung-DDS)
- **Selenium 기반 CRM 웹 자동화 시스템 구축**
  - 웹 UI 자동화를 통해 내부 CRM 데이터 수집·처리 파이프라인 구현  
  - 👉 [프로젝트 상세](https://github.com/Kim-Tae-Su/Web-Crawling)
- **딥러닝 기반 Super Resolution 모델 설계 및 실무 적용**
  - 저해상도 이미지 복원 모델 설계로 이미지 처리 파이프라인 성능 개선  
  - 👉 [프로젝트 상세](https://github.com/Kim-Tae-Su/super-resolution-project)

---

### 앱테스트에이아이 (2025.09 ~ 재직 중)
**개발 1팀 / Backend Engineer**
- Flask 기반 백엔드 서비스의 API 설계·구현 및 운영
- SQLAlchemy ORM 기반 데이터 모델링 및 트랜잭션 범위·에러 처리를 고려한 데이터 접근 계층 설계
- 서비스 사용량 통계 API를 설계·구현하여 운영 지표 집계, 데이터 정합성 확보 및 비즈니스 의사결정 지원
- 재귀 CTE 및 윈도우 함수 기반 쿼리 최적화를 통해 대용량 통계 데이터 조회 성능 개선
- Docker 기반 ELK Stack 환경을 표준화하고 로그 수집·분석 파이프라인의 보안 설정 및 운영 자동화

**주요 프로젝트**
- **ELK Stack 도커 이미지 빌드 및 보안·운영 자동화**
  - elk
  - 👉 [프로젝트 상세](https://github.com/Kim-Tae-Su/ApptestAI-ELK)

---


## Core Engineering Areas

### Backend / API Development

- Flask / FastAPI 기반 REST API를 설계·구현하며, 대용량 데이터 처리 시 스트리밍 방식 적용으로 메모리 효율과 서비스 안정성 확보
- CRUD API 설계 과정에서 응답 스펙 표준화, 공용 로직 추상화, 예외 처리 일관화를 통해 유지보수성과 확장성 개선
- 운영 환경에서 발생한 API 장애를 분석하고 재발 방지를 고려한 구조로 개선

---

### Database Design & Data Integrity
- 트랜잭션 범위와 격리 수준을 고려한 데이터 처리 로직 설계로 동시성 환경에서의 데이터 일관성 확보
- 주요 조회 패턴을 기준으로 인덱스를 설계하고 실행 계획 분석을 통해 쿼리 성능 개선
- JSON 컬럼 기반 구조의 한계를 분석하고 M:N 관계를 매핑 테이블로 분리하여 정규화된 스키마로 개선
- Foreign Key 및 ON DELETE CASCADE 적용으로 데이터 정합성과 운영 안정성 확보

---

### DevOps / CI & Operations

- Docker 기반 서비스 환경에서 SaaS 및 온프레미스 환경 모두에 대한 배포·운영 경험
- ELK Stack 기반 로그 수집·분석 파이프라인을 구성하여 운영 환경에서 서비스 상태 모니터링 및 장애 원인 추적 지원
- uWSGI graceful reload를 활용한 무중단 배포 경험
- Shell Script를 작성해 서비스 배포, 로그 정리, 환경 초기화 등을 자동화하며 반복 작업의 효율성과 운영 안정성 향상


---

### Distributed Data Service (DDS)

- DDS 기반 실시간 데이터 수집·처리 파이프라인을 구축하며 대규모 데이터 흐름을 안정적으로 관리
- 수집 데이터를 저장·가공하여 분석 및 모델 학습에 활용 가능한 구조로 설계
- 실시간성과 데이터 정합성을 고려한 데이터 흐름 제어 경험
---

### ML / DL Experience

- 데이터 전처리부터 모델 학습·평가까지 ML/DL 전체 파이프라인 경험
- TensorFlow 기반 딥러닝 모델 설계 및 성능 개선 수행
- 도메인 특성을 반영한 Super Resolution CNN 모델을 실제 서비스 문제 해결에 적용

---

### LLM

- LangChain 기반 RAG 시스템을 구현하여 내부 데이터 활용 및 응답 품질 개선 경험


---

## Contact

**Email**: kts8421@naver.com

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer"/>
</p>
