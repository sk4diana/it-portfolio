# WOO JIN LEE | IT Engineer Portfolio

백엔드 개발과 시스템 운영 관점에서 서비스를 바라보는 **IT 엔지니어 지망생**입니다.  
서버 로직과 데이터 처리 흐름을 이해하는 것을 바탕으로, 서비스가 실제 환경에서 **안정적으로 동작**하도록 만드는 데 관심이 있습니다.

---

## ABOUT
- **관점**: 기능 구현뿐 아니라 “요청 → 처리 → 저장 → 응답”의 흐름과 운영 환경까지 함께 고려합니다.
- **지향점**: 구조/기준을 세워 재사용 가능한 방식으로 구현하고, 문제 상황에서는 원인 분석–재발 방지를 우선합니다.

---

## SKILLS
### [ LANGUAGE ]
- Java / JavaScript / Python  
- 객체지향 기반 구현, 비동기 흐름 이해, 크롤링·전처리·분석 실습 경험

### [ BACKEND / FRAMEWORK ]
- Spring Boot / Spring MVC  
- REST API 설계, Controller–Service 계층 구성, 요청–응답 기반 기능 구현

### [ DBMS ]
- MySQL / Oracle  
- 기본 SQL 작성 및 CRUD 구현, 테이블 설계 관점의 데이터 구조 정의

### [ DEVOPS / INFRA ]
- Linux / Docker / (AWS, NCP)  
- 실행 환경 구성, 컨테이너 기반 서비스 운영 관점 이해

### [ MONITORING ]
- Prometheus / Grafana / cAdvisor  
- CPU·Memory·Network 지표 수집 및 시각화, 실행 환경별 자원 사용 특성 비교

### [ TOOL ]
- Git / GitHub / Notion / Teams / Slack  
- 협업 및 이슈/일정 공유 중심의 커뮤니케이션 경험

---

## TEAMPROJECT I
## LG Regen
**동남아 이슬람 국가 맞춤 ThinQ 활용 솔루션**  
- 기간: **Nov 2025 – Dec 2025**
- 키워드: **Flutter · Spring Boot · MySQL · REST API · ESP32/LCD · NCP(기준)**

### 요약
동남아(인도네시아·말레이시아) 무슬림 가정의 생활 패턴을 반영해 가전 제어 경험을 재구성한 **스마트홈 솔루션**입니다.  
Flutter 앱–Spring Boot–MySQL을 기반으로 기능을 구현하고, ESP32+LCD 연동까지 고려해 **앱 ↔ 서버 ↔ 디바이스** 데이터 흐름을 설계했습니다.

### 개발/아키텍처
- **Client**: Flutter 화면 구성 및 사용자 흐름 설계
- **Back-end**: Spring Boot REST API, 비즈니스 로직 구성
- **DB**: MySQL CRUD(저장/조회) 중심 구현
- **Build**: Gradle 기반 의존성/빌드 관리
- **Cloud**: NCP 기준 배포·운영 흐름 고려
- **Hardware**: ESP32 + LCD 연동 데이터/명령 흐름 정리

### 담당 역할
- REST API 설계 및 백엔드 비즈니스 로직 구현
- MySQL 기반 데이터 모델 설계 및 CRUD 흐름 구성
- 앱 ↔ 서버 ↔ 디바이스(ESP32/LCD) 연동 흐름 정리
- 배포/운영 관점에서 실행 구조 정리(NCP 기준)

### Links
- Demo Video: (YouTube 링크)
- Docs: (산출문서 링크)
- Repository: (GitHub 링크)

---

## TEAMPROJECT II
## Docker Container Monitoring System
**cAdvisor · Prometheus · Grafana 기반 컨테이너 모니터링**  
- 기간: **Nov 2024 – Feb 2025**
- 키워드: **Docker Compose · cAdvisor · Prometheus · Grafana · Monitoring**

### 요약
Docker 환경에서 실행되는 컨테이너의 **CPU · Memory · Network** 사용량을 실시간으로 수집·저장·시각화하는 모니터링 시스템입니다.  
**cAdvisor → Prometheus → Grafana** 파이프라인을 Docker Compose로 구성해 실행 환경을 일관되게 유지하고, 대시보드에서 변화 추이를 빠르게 확인할 수 있도록 했습니다.

### 개발/아키텍처
- **cAdvisor**: 컨테이너 리소스 메트릭 수집
- **Prometheus**: cAdvisor 엔드포인트 스크래핑, 시계열 데이터 저장
- **Grafana**: 대시보드 구성 및 실시간 시각화
- **Docker Compose**: 모니터링 스택 구성/실행 자동화

### 담당 역할
- 모니터링 스택 설계(수집→저장→시각화 데이터 흐름 정의)
- Docker Compose 기반 실행 환경 표준화
- Prometheus 스크래핑 타깃/주기 설정 구성
- Grafana 대시보드 설계(CPU/Memory/Network 중심)
- 단일/다중 컨테이너 및 부하 상황에서 지표 변화 검증

### Links
- Presentation: (발표자료 PDF 링크)
- Thesis: (논문 PDF 링크)
- Repository: (GitHub 링크)

---

## CONTACT
- GitHub: https://github.com/sk4diana
- E-mail: sk4diana@gmail.com
