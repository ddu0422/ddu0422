# Hello, I'm Duho Lee (이두호) 👋

## 🚀 Core Competencies

- **Architecture**
  - Monolith → MSA 전환 설계 주도 (배포 시간 **83% 단축** · 롤백 **93% 단축**, MAU 200만 서비스)
- **Performance**
  - Index 전략 및 쿼리 튜닝으로 P95 Latency **2~3초 → 0.01초** 달성
- **Stability**
  - Datadog 기반 Observability 구축으로 SLA **70% → 99.9%** 달성 및 손실 **1,400만원 대비**
- **Cost**
  - 로그 감사로 Datadog 비용 **월 2,600만원 → 1만원** 절감
  - ECS Rightsizing으로 **월 100만원 추가 절감**
- **Leadership**
  - PLE로서 개발 프로세스 재설계, 운영 예외처리 **0건** · 배포 사이클 **월 1회 → 주 1~2회** 단축
  - 우아한테크코스 4기·6기 리뷰어 (62명, 감동 리뷰어 수상, 평균 9.66/10)

<br/>

## 💼 Experience

### (주)콜로세움코퍼레이션 (2024.04 ~ 재직중)
- **조직 리딩**: 오퍼레이션/PM 요청이 기획 리뷰 없이 바로 개발로 이어져
  정책 충돌 기능 누적 및 운영 예외처리 지속 증가
  - 개인 권한 강화 대신 의사결정 프로세스 자체를 재설계
  - 운영 예외처리 **0건** 달성 · 배포 사이클 **월 1회 → 주 1~2회** 단축
  - [팀 자율 의사결정 기반의 개발 조직 체계 구축](https://dhistory.tistory.com/273)
- **안정성 개선**: 모니터링 부재로 장애를 사후에 인지하는 구조
  - DevOps 부재 환경에서 유지보수 비용 최소화를 위해 Datadog 선택
  - SLA **70% → 99.9%** 달성 · 장애 조기 인지로 손실 **1,400만원 대비**
- **비용 최적화**: Datadog 대시보드 구축 후 ECS 리소스 과도 할당 확인
  - 실제 사용량 기반 Rightsizing 진행
  - 인프라 비용 **월 100만원 절감**

### 비엔디알에스(주) (2023.11 ~ 2024.04)
- **성능 개선**: 데이터 누적에 따라 offset 전체 스캔 비용이 증가해 게시글 조회 응답시간 4초까지 늘어나는 문제 발생
  - 페이지 번호 기반 UX가 불필요한 서비스 특성상 cursor 기반으로 전환
  - 조회 성능 **85% 향상** (4초 → 0.6초)
- **쿼리 최적화**: 복잡한 연관관계로 fetch join 적용 시
  다른 API에 N+1 사이드 이펙트 전파 위험
  - QueryDSL로 영향 범위를 격리하여 N+1 **4건 해결**
- **안정성 개선**: ECS Rolling Update 기반 **24/7 무중단 서비스** 운영
  - 롤백 프로세스 최적화 **(15분 → 3분)**

### (주)클래스101 (2020.11 ~ 2023.07)
- **아키텍처 개선**: 회원 서비스를 MSA 첫 번째 분리 대상으로 선정
  - 상품·결제 전 도메인의 기준이 되는 회원이 SPOF라고 판단
  - 배포 시간 **83% 단축** (90분 → 15분)
- **배포 안정성**: EKS Pod 롤백 5분 문제 해결을 위해 Feature Flag 도입
  - 코드 배포 없이 **5초 이내 롤백** 가능한 구조로 전환
  - 롤백 시간 **93% 단축**
- **비용 최적화**: 로그 필터링 및 레벨 조정으로 불필요한 로그 제거
  - 운영 비용 **99% 절감** (월 2,600만원 → 1만원)
- **비즈니스 성과**: TV 환경 특성에 맞게 QR 기반 로그인 설계
  - 신규 매출 **월 1,000만원** 견인
- **대용량 처리**: @Scheduled 대비 메모리 안정성 확보를 위해 Spring Batch 선택
  - Chunk 기반으로 휴면 유저 **260만 건** 개인정보 파기 및 분리 보관

<br />

## 🌱 Activities

| 기간 | 활동 | 비고 |
|---|---|---|
| 2024.09 ~ 2025.01 | F-Lab Java BackEnd Deep-Dive | |
| 2024.02 ~ 2024.06 | 우아한테크코스 6기 리뷰어 | 30명 리뷰 · 평균 9.66/10 |
| 2022.02 ~ 2022.06 | 우아한테크코스 4기 리뷰어 | 32명 리뷰 · 감동 리뷰어 수상 |
| 2019.05 ~ 2019.12 | 우아한테크코스 1기 수료 | |


<br />

## 🏫 Education

| 기간 | 학교 | 전공 |
|---|---|---|
| 2019.03 ~ 2022.02 | 한국방송통신대학교 | 컴퓨터과학과 |
| 2014.03 ~ 2018.02 | 인하공업전문대학교 | 정보통신과 |

<br />

## 🎖 Certification

| 취득연도 | 자격증 |
|---|---|
| 2021 | 정보처리기사 |

<br />

## 🛠 Tech Stack

### ⚙️ Backend
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white) ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white) ![JPA](https://img.shields.io/badge/JPA-6DB33F?style=for-the-badge&logo=hibernate&logoColor=white) 
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white) ![JUnit5](https://img.shields.io/badge/JUnit5-25A162?style=for-the-badge&logo=junit5&logoColor=white) ![Rest Docs](https://img.shields.io/badge/REST_Docs-6DB33F?style=for-the-badge&logo=spring&logoColor=white)

<br/>

### ☁️ DevOps & Infrastructure
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Datadog](https://img.shields.io/badge/Datadog-632CA6?style=for-the-badge&logo=datadog&logoColor=white) ![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)

<br/>

## 📫 Contact
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dev.ddu0422@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/%EB%91%90%ED%98%B8-%EC%9D%B4-634a96245/)
