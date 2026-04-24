# 👨‍💻 이종욱 | Backend & Operations Engineer

<div align="center">
  <img src="https://avatars3.githubusercontent.com/u/60126161?s=460&v=4" width="150" style="border-radius: 50%; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"/>
  
  <h3>"데이터로 소통하고 자동화로 가치를 만드는 개발자"</h3>

  <p>
    <a href="mailto:dkfxnqlxmrkt@naver.com"><img src="https://img.shields.io/badge/Email-dkfxnqlxmrkt@naver.com-green?style=flat-square&logo=Gmail&logoColor=white"/></a>
    <a href="https://github.com/leejongwook1"><img src="https://img.shieldsio/badge/Github-leejongwook1-181717?style=flat-square&logo=Github&logoColor=white"/></a>
    <a href="https://leejongwook1.github.io/"><img src="https://img.shields.io/badge/Portfolio-Blog-blue?style=flat-square&logo=Telegram&logoColor=white"/></a>
  </p>
</div>

---

## 💼 Work Experience

### **휴머스온 (Humuson)**
> **운영개발팀 · 프로** | `2024.05 ~ 2026.04`

#### 💡 **① n8n 및 AI 활용 운영 효율 증진**
* **운영 프로세스 자동화** — n8n을 활용하여 MySQL 파티션 케이블의 정기적 관리(생성/삭제) 및 API 상태 정밀 점검 체계 구축.
* **지능형 알림 시스템** — 시스템 이상 징후 발생 시 MS Teams 및 이메일로 실시간 자동 전송하는 통합 관제 자동화.
* **AI 연동 리포트 분석** — 발송 리포트 자동 생성 및 AI 연동을 통해 주요 발송 지표의 심층 분석 결과를 도출하는 업무 워크플로우 구현.

#### 🚀 **② 멀티 채널 메시징 엔진 고도화**
* **통합 발송 로직 구현** — Kakao(알림톡/친구톡/브랜드메시지), Push(FCM/APNS), Email(SMTP) 등 멀티 채널 엔진 개발.
* **리소스 최적화** — 대용량 데이터 처리 시 리소스 병목을 방지하기 위해 단계별 수행 로직을 적용하여 처리 성능 및 안정성 최적화.
* **보안 및 가용성** — 화이트리스트 기능 추가 및 대규모 트래픽 부하 분산 처리를 통해 무중단 서비스 환경 구축.

#### ⚙️ **③ 비즈니스 온보딩 및 마이그레이션 자동화**
* **온보딩 리소스 Zero화** — 신규 고객 유입 시 발생하는 운영 업무를 완전 자동화하여 휴먼 에러 방지 및 리소스 제로 달성.
* **표준화 마이그레이션** — 신규 계약 시 필요한 데이터 마이그레이션 규격을 표준화하고, 규격화된 데이터를 기반으로 자동 마이그레이션 로직 구현.

#### 🧠 **④ 지능형 연구 및 사업 전략 수립**
* **AI 기반 전략 수립** — NotebookLM과 Genspark를 활용하여 시장 조사 및 내부 데이터 분석, 팀의 업셀링 전략 및 미래 로드맵 수립 지원.

#### 📊 **⑤ 시스템 통합 모니터링 체계 구축 및 고도화**
* **지표 시각화 및 관제** — Prometheus & Grafana를 연동하여 엔진 상태 및 주요 발송 지표를 실시간 시각화하고 맞춤형 대시보드 구축.
* **인프라 모니터링** — Zabbix를 활용하여 서버 리소스(CPU, Memory, Disk) 및 네트워크 상태를 전방위적으로 모니터링하는 환경 구성.
* **장애 대응 최적화** — 임계치 기반의 알람 체계를 세분화하여 장애 발생 시 즉각적인 인지 및 조치가 가능한 통합 알림 시스템 운영.

---

### **날리지포인트 (Knowledge Point)**
> **플랫폼본부 1팀 · 대리** | `2021.03 ~ 2023.12`

#### 🛠️ **① KT RCS 중계사 SM** `2021.03 ~ 2023.12`
* **시스템 유지보수 및 기능 고도화** — 고객사 요구사항 분석 및 메시지 전송, 응답 처리, 웹훅 전송 등 핵심 기능 추가 개발 및 에러 대응.
* **안정성 및 품질 확보** — 스팸 및 이통사 필터링 로직을 연동하여 발송 성공률을 개선하고, Postman/Jmeter를 통한 꼼꼼한 사전 테스트 수행.
* **<mark>주요 성과</mark>** — 상용 환경의 주요 에러 케이스 해소 및 메시지 전송 지연 문제 해결.

#### 🗄️ **② KT RCS DB 대개체** `2023.04 ~ 2023.11`
* **DB 아키텍처 개선** — 대용량 트래픽 처리 시 병목이 발생하는 MySQL 구간을 성능이 우수한 **Altibase(In-Memory DB)**로 대체.
* **마이그레이션 및 튜닝** — DB 변경에 따른 코드 및 SQL 쿼리를 전면 수정하고, Jmeter 부하 테스트를 통한 성능 검증 및 최적화 진행.
* **<mark>주요 성과</mark>** — DB 처리 병목 구간 해소를 통한 전체적인 시스템 응답 성능 대폭 개선.

#### 🌐 **③ KT RCS 중계사 및 홀세일 국사 이원화** `2022.10 ~ 2023.03`
* **Active-Active 이원화 구축** — 기존 분당 국사의 장애(SPOF)에 대비해 대전 국사를 신규 구축하고 트래픽을 분산 처리할 수 있는 이원화 아키텍처 설계.
* **메시징 코어 및 스케줄러 개발** — 메시지 전송/응답 API 개발 및 대용량 성공/실패/에러 데이터를 집계하는 통계 스케줄러 신규 구축.
* **<mark>주요 성과</mark>** — 코드 리팩토링을 통한 레거시 소스 복잡도 개선 및 안정적인 무중단 서비스 환경 확보.

#### 🔄 **④ 헤르메스 양방향 SI** `2022.01 ~ 2022.06`
* **양방향 통신 시스템 구축** — 사용자의 응답을 수신하고 후속 액션을 처리하는 양방향 메시징 서버 설계 및 구현.
* **과금 및 권한 관리** — 양방향 서비스 전용 권한 체크 로직과 통계/과금 처리를 위한 배치 스케줄러 개발.

---

## 🛠 Technical Skills

### **Backend & Messaging**
<p>
  <img src="https://img.shields.io/badge/Java 8-007396?style=flat-square&logo=java&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white"/>
  <img src="https://img.shields.io/badge/MyBatis-000000?style=flat-square&logo=Fluentd&logoColor=white"/>
  <img src="https://img.shields.io/badge/JPA-59666C?style=flat-square&logo=Hibernate&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white"/>
</p>
<p>
  <img src="https://img.shields.io/badge/Kakao API-FFCD00?style=flat-square&logo=Kakao&logoColor=black"/>
  <img src="https://img.shields.io/badge/Firebase FCM-FFCA28?style=flat-square&logo=firebase&logoColor=black"/>
  <img src="https://img.shields.io/badge/ActiveMQ-99CC00?style=flat-square&logo=Apache-ActiveMQ&logoColor=white"/>
</p>

### **Data & Middleware**
<p>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white"/>
  <img src="https://img.shields.io/badge/Altibase-00599C?style=flat-square&logo=database&logoColor=white"/>
  <img src="https://img.shields.io/badge/MS SQL Server-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white"/>
</p>

### **DevOps & Monitoring**
<p>
  <img src="https://img.shields.io/badge/n8n-FF6C37?style=flat-square&logo=n8n&logoColor=white"/>
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white"/>
  <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white"/>
  <img src="https://img.shields.io/badge/Zabbix-CC0000?style=flat-square&logo=zabbix&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black"/>
</p>

### **AI-Powered Research**
<p>
  <img src="https://img.shields.io/badge/NotebookLM-4285F4?style=flat-square&logo=google&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white"/>
  <img src="https://img.shields.io/badge/Claude-7F3FBF?style=flat-square&logo=anthropic&logoColor=white"/>
</p>

---

## 🚀 Projects (Personal)

| 프로젝트명 | 기간 | 핵심 기술 | 링크 |
| :--- | :---: | :--- | :---: |
| **교수-학생 일정조율 웹** | `20.02 ~ 20.11` | Django, TOAST UI | [<img src="https://img.shields.io/badge/Github-181717?style=flat-square&logo=Github&logoColor=white"/>](https://github.com/leejongwook1/Calendar) |
| **React & Firebase Twitter 클론** | `21.01 ~ 21.01` | React, Firebase | [<img src="https://img.shields.io/badge/Github-181717?style=flat-square&logo=Github&logoColor=white"/>](https://github.com/leejongwook1/lwitter) |
| **React 영화 정보 검색 앱** | `21.01 ~ 21.01` | React, Axios | [<img src="https://img.shields.io/badge/Github-181717?style=flat-square&logo=Github&logoColor=white"/>](https://github.com/leejongwook1/leejongwook_movie_app_2021) |

---

## 🎓 Education
* 🌐 **한신대학교** 컴퓨터공학과 졸업 (`2014.03 ~ 2021.02`)
* 🏫 **안산 선부고등학교** 졸업 (`2011.03 ~ 2014.02`)
