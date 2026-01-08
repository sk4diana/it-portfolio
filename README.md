<div align="center">
# **WOO JIN LEE**
### *Backend / IT Engineer Portfolio*

서버 로직과 데이터 흐름을 기반으로,  
서비스가 **실제 환경에서 안정적으로 동작**하도록 만드는 데 집중합니다.

[![GitHub](https://img.shields.io/badge/GitHub-sk4diana-181717?style=for-the-badge&logo=github)](https://github.com/sk4diana)
![Email](https://img.shields.io/badge/Email-sk4diana@gmail.com-7c3aed?style=for-the-badge)
![Location](https://img.shields.io/badge/Location-Gwangju,%20KR-6b7280?style=for-the-badge)

- Portfolio Link : https://sk4diana.github.io/it-portfolio/
</div>

---

## ✨ ABOUT
백엔드 개발과 시스템 운영 관점에서 서비스를 바라보는 **IT 엔지니어 지망생**입니다.  
전공과 프로젝트를 통해 서버 로직, 데이터 처리 흐름, 실행 환경을 함께 고려하는 개발 경험을 쌓아왔습니다.

- 기능 구현보다 **요청 → 처리 → 저장 → 응답**의 흐름을 우선으로 봅니다.
- “잘 돌아가는 코드”를 넘어, 운영에서 문제를 줄이는 **구조와 기준**을 중요하게 생각합니다.
- 이슈 발생 시 **재현 → 원인 분석 → 재발 방지**로 접근합니다.

---

## 🧩 SKILLS
> 포트폴리오 페이지 구성에 맞춘 기술 분류입니다.

### **[ LANGUAGE ]**
- **Java**: OOP 기반 구현 / Spring 서버 로직 경험 / DB 연동 흐름 이해  
- **JavaScript**: 비동기 처리 흐름 이해 / 클라이언트–서버 연동 구조 이해  
- **Python**: 크롤링·전처리 / 데이터 분석·시각화 / 기본 모델링 실습

### **[ BACKEND / FRAMEWORK ]**
- **Spring Boot / Spring MVC**
  - REST API 설계 및 Controller–Service 계층 구성
  - 요청–응답 흐름 기반 기능 구현

- **Build**
  - **Maven / Gradle** 기반 의존성 관리 및 빌드 환경 일관화

### **[ DBMS ]**
- **MySQL / Oracle**
  - 기본 SQL(조회/삽입/수정/삭제) 작성 및 CRUD 구현
  - 테이블 설계 관점에서 데이터 구조 정의 경험

### **[ DEVOPS / INFRA ]**
- **Linux**: 가상환경에서 서비스 실행 / 기본 명령어 활용  
- **Docker**: 컨테이너 구성 / 다중 컨테이너 실행 및 구성 실습  
- **Cloud (AWS / NCP)**: 클라우드 환경에서 배포/실행 경험(프로젝트 기준)

### **[ MONITORING ]**
- **Prometheus / Grafana / cAdvisor**
  - CPU·Memory·Network 지표 수집 및 시각화
  - 실행 환경별 자원 사용 특성 비교 및 관찰

### **[ TOOL ]**
- **Git / GitHub**: 브랜치 기반 협업 / 커밋 이력 관리  
- **Notion / Teams / Slack**: 이슈·일정 공유 중심 커뮤니케이션

---

## 🚀 TEAMPROJECT I — LG Regen
### **동남아 이슬람 국가 맞춤 ThinQ 활용 솔루션**
- **Period**: Nov 2025 – Dec 2025  
- **Keywords**: Flutter · Spring Boot · MySQL · REST API · ESP32/LCD · NCP(기준)

#### ✅ Overview
동남아(인도네시아·말레이시아) 무슬림 가정의 생활 패턴을 반영해  
가전 제어 경험을 재구성한 **스마트홈 솔루션**입니다.  
Flutter 앱–Spring Boot–MySQL 기반으로 기능을 구현하고,  
ESP32 + LCD 연동까지 고려해 **앱 ↔ 서버 ↔ 디바이스** 전체 흐름을 설계했습니다.

#### 🏗 Architecture
- **Client**: Flutter 기반 화면 구성 및 사용자 흐름 설계  
- **Back-end**: Spring Boot REST API + 비즈니스 로직 구성  
- **DB**: MySQL 기반 CRUD(저장/조회) 구현  
- **Build**: Gradle 기반 의존성/빌드 관리  
- **Cloud**: NCP 기준 배포/운영 흐름 고려  
- **Hardware**: ESP32 + LCD 연동 데이터/명령 흐름 정리

#### 🙋 Role
- REST API 설계 및 서버 비즈니스 로직 구현
- MySQL 데이터 모델 설계 및 CRUD 흐름 구성
- “앱 ↔ 서버 ↔ 디바이스” 연동 흐름 정리(ESP32/LCD)
- 배포/운영 관점에서 실행 구조 정리(NCP 기준)

#### 🔗 Links
- Demo Video: (YouTube 링크)
- Docs: (산출문서 링크)
- Repository: (GitHub 링크)

---

## 📊 TEAMPROJECT II — Docker Container Monitoring System
### **cAdvisor · Prometheus · Grafana 기반 컨테이너 모니터링**
- **Period**: Nov 2024 – Feb 2025  
- **Keywords**: Docker Compose · cAdvisor · Prometheus · Grafana · Monitoring

#### ✅ Overview
Docker 환경에서 실행되는 컨테이너의 **CPU · Memory · Network** 사용량을  
실시간으로 수집·저장·시각화하는 모니터링 시스템입니다.  
**cAdvisor → Prometheus → Grafana** 파이프라인을 Docker Compose로 구성해  
실행 환경을 일관되게 유지하고, 대시보드에서 변화 추이를 빠르게 확인할 수 있도록 했습니다.

#### 🏗 Architecture
- **cAdvisor**: 컨테이너 단위 리소스 메트릭 수집
- **Prometheus**: 메트릭 스크래핑 및 시계열 데이터 저장
- **Grafana**: 대시보드 구성 및 실시간 시각화
- **Docker Compose**: 모니터링 스택 구성/실행 자동화

#### 🙋 Role
- 모니터링 스택 설계(수집→저장→시각화 데이터 흐름 정의)
- Docker Compose 기반 실행 환경 표준화
- Prometheus 스크래핑 타깃/주기 설정 구성
- Grafana 대시보드 설계(CPU/Memory/Network 중심)
- 부하 상황에서 지표 변화 검증(단일/다중 컨테이너)

#### 🔗 Links
- Presentation: (발표자료 PDF 링크)
- Thesis: (논문 PDF 링크)
- Repository: (GitHub 링크)

---

## 🧭 Development Philosophy
- **구조와 기준**을 먼저 정리한 뒤 구현합니다.
- 운영 관점에서 “어디서 문제가 날지”를 생각하며 설계합니다.
- 이슈를 해결할 때는 **원인을 이해하고 재발 방지 기준**을 남깁니다.

---

## 📬 CONTACT
- GitHub: https://github.com/sk4diana  
- E-mail: sk4diana@gmail.com
