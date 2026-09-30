<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:8EC5FC,100:E0C3FC&height=170&section=header&text=Juhee%20Park&fontSize=44&fontColor=334155&desc=Software%20Engineer&descAlignY=66&descSize=16" alt="Juhee Park — Software Engineer" />
</p>

<p align="center">
  <b>현장의 요구를 구체화하고, 구현과 검증으로 서비스에 반영합니다.</b><br/>
  사용자와 운영자의 업무를 이해하고, AI를 활용해 만들고, 실제 사용 흐름에서 확인합니다.
</p>

<p align="center">
  <a href="mailto:pjuhee23@dankook.ac.kr">Email</a> &nbsp;·&nbsp;
  <a href="https://github.com/juhee0223/juhee0223/blob/main/Resume_JuheePark.md">이력서</a>
</p>

<br/>

<p align="center">
  단국대학교 소프트웨어학과 4학년 &nbsp;·&nbsp; 정보처리기사 (2026.09)
</p>

<p align="center">
  <a href="#projects">Projects</a> &nbsp;·&nbsp;
  <a href="#publications">Research</a> &nbsp;·&nbsp;
  <a href="#awards">Awards</a> &nbsp;·&nbsp;
  <a href="#case-studies">Case Studies</a> &nbsp;·&nbsp;
  <a href="#activities">Activities</a> &nbsp;·&nbsp;
  <a href="#tech-stack">Tech Stack</a>
</p>

<br/>

<a id="projects"></a>

## 🗂️ Projects

서비스 개발·운영, AI 응용, 시스템 성능 연구를 이어왔습니다. 각 프로젝트의 구현 내용과 결과를 소개합니다.

| 프로젝트 · 기간 | 구현·탐구한 내용 | 결과 · 자료 |
| :--- | :--- | :--- |
| **단짠**<br/>2025.12 – 진행 중 | 축제 티켓팅·관리자 서비스 개발과 운영. 가입 흐름, 이메일 기반 비밀번호 재설정, 외부 얼굴인증 입장 연계의 요구사항 조율<br/>`Spring Boot` `Redis` `Kafka` `Docker` `AWS` `React` | 팀 부하 테스트 **10,000 VU** 대상 정합성·순서 보장 확인<br/>[문제 해결 사례](#danzzan) · [GitHub](https://github.com/orgs/DKU-Dan-Zzan/repositories) |
| **Conquer Health**<br/>2026.08 | 의료 특화 모델 기반 건강 상담. 의료 RAG·MCP 검색 접근 실험과 응답 규칙·평가 하네스 개선<br/>`Python` `Docker` `Pydantic` `Async` `LLM / RAG` `HealthBench` | 🏆 **의료 특화 FM 해커톤 벤치마크상**<br/>[개선 과정](#conquer-health) · [GitHub](https://github.com/Hackathon-AIM/health-conquer-submission) |
| **OLLY**<br/>2026.05 – 2026.06 | LLM/RAG 서비스의 요청별 비용·토큰·지연·오류 추적. API 계측, 대시보드, SLM·Discord 알림을 연결한 관측성 MVP<br/>`FastAPI` `OpenTelemetry` `Prometheus` `Jaeger` `Grafana` `Kubernetes` `Ollama` | **5가지 시나리오 기반 관측·알림 검증**<br/>[설계와 검증](#olly) · [GitHub](https://github.com/lee-y-ch/olly) |
| **SketchToSpec** · 개인<br/>2025.11 – 2025.12 | 손그림 UI·기능·텍스트 입력에서 SRS 요구사항 명세와 ASCII 화면 흐름 생성. UI 요소 감지와 계획 수정 루프 구현<br/>`LangGraph` `Streamlit` `OpenCV` `PyTorch` `Qwen` | **멀티모달 ReAct Agent 파이프라인 구축**<br/>[GitHub](https://github.com/juhee0223/DEEPLEARNING_AI_AGENT) |
| **Sun(善)-Date**<br/>2025.11 | 봉사활동을 함께 하며 서로를 알아가는 소셜 네트워킹·소개팅 서비스<br/>`Django` `Flutter` `Java` | 🏆 **EASYTHON 2025 우수상**<br/>[GitHub](https://github.com/day-e0n/sun_date) |
| **FTL Simulator / GameGC**<br/>2025.10 – 2025.12 | Greedy·Cost-Benefit GC 정책과 Incremental GC를 모방한 Pipeline 기반 GameGC의 성능 비교. 지연 스파이크와 점진적 회수 패턴 분석<br/>`C` `File I/O` `Visualization` | **스토리지 GC 정책 비교 실험**<br/>[GitHub](https://github.com/day-e0n/ssp_team_project) |
| **DACON 고객 지원 등급 분류** · 개인<br/>2025.09 – 2025.10 | 고객 데이터로 지원 필요 수준 분류. Feature Engineering과 모델별 성능 비교<br/>`Python` `scikit-learn` `TensorFlow` `XGBoost` | **F1 Score 상위 10%**<br/>[GitHub](https://github.com/juhee0223/DACON-Customer-Support-Classification) |
| **AI Bird Repeller**<br/>2025.05 · 무박 2일 해커톤 | 농작물 피해 조류를 인식하고 기피음을 자동 재생하는 퇴치 시스템. 실시간 추론 환경의 리소스 최적화<br/>`Python` `Threading` `YOLOv5` `BirdNET` | 🏆 **KHUTHON 2025 우수상**<br/>[GitHub](https://github.com/JustYOLO/Getout_Bird) |
| **RocksDB Compaction Analyzer**<br/>2025.01 – 2025.05 | Leveled·Universal·FIFO 정책별 성능 자동 측정·분석·시각화. 스토리지 엔진의 데이터 경로 구조 분석<br/>`RocksDB DBBench` `Bash` `Python` | **KCC 2025 논문 제1저자 발표**<br/>[연구 내용](#publications) |

<br/>

---

<a id="publications"></a>

## 📚 Publications & Research

### 운영체제 교재기반 RAG시스템 구축

**공동저자 · 2026 · 글통**  
김보승, **박주희**, 최종무, 전광일, 박민규

운영체제 교재 텍스트를 바탕으로 RAG 시스템을 구축하는 과정을 다룬 교육용 저서입니다.

`비매품 단행본` &nbsp; `ISBN 979-11-94546-10-8`

### Visualization and Semantic Interpretation of Vector Space Structures: A Case Study Based on OSTEP

**공동저자 · WDSC 2025 · 🏆 우수논문상**  
Bo-seung Kim, **Juhee Park**, 외 4명

OSTEP 교재 텍스트를 임베딩하고, 벡터 공간의 구조를 시각화해 의미론적 군집을 분석한 연구입니다.

[학회](https://sites.google.com/view/wdsc2025/) · [연구 저장소](https://github.com/DKU-StarLab/OSTEP_RAG)

### RocksDB에서 Compaction Style에 따른 성능 변화 분석

**제1저자 · KCC 2025 발표**  
**박주희**, 신호진, Guangxun Zhao, 최종무

RocksDB의 Leveled·Universal·FIFO 컴팩션 정책에 따른 Write Amplification과 Read Efficiency의 트레이드오프를 정량적으로 분석했습니다.

[학회](https://www.kiise.or.kr/conference/kcc/2025/) · NRF 중견연구자지원사업 / SW중심대학사업

<br/>

---

<a id="awards"></a>

## 🏆 Awards & Honors

| 날짜 | 수상 | 기관 · 관련 결과물 |
| :--- | :--- | :--- |
| **2026.08.22** | **의료 특화 파운데이션 모델 해커톤 벤치마크상** | 루닛 · 과학기술정보통신부 · NIPA<br/>AIM팀 / Conquer Health · [공식 기사](https://www.lunit.io/ko/media-hub/%EB%A3%A8%EB%8B%9B-%EA%B5%AD%EA%B0%80%EA%B3%BC%EC%A0%9C-ai-%EB%AA%A8%EB%8D%B8-%ED%99%9C%EC%9A%A9-%EC%B2%AB-%ED%95%B4%EC%BB%A4%ED%86%A4-%EC%84%B1%EB%A3%8C-%EA%B0%9C%EB%B0%9C%EC%9E%90/) |
| **2025.11.22** | **EASYTHON 2025 해커톤 우수상** | 단국대 SW중심사업단 / Sun(善)-Date |
| **2025.08.20** | **WDSC 2025 우수논문상** | 정보보안 및 고신뢰컴퓨팅 하계워크샵 / OSTEP 벡터 공간 분석 연구 |
| **2025.05.10** | **KHUTHON 2025 해커톤 우수상** | SW중심사업단 (단국대 외 3개교) / AI Bird Repeller |

<br/>

---

<a id="case-studies"></a>

## 🔬 Case Studies

대표 프로젝트에서 요구사항을 정리하고, 구현 방향을 결정하고, 결과를 확인한 과정입니다.


| 🎟️ 서비스 개발·운영 | 🧪 AI 응답 개선 | 🔎 시스템 관측·검증 |
| :--- | :--- | :--- |
| [**단짠**](#danzzan) | [**Conquer Health**](#conquer-health) | [**OLLY**](#olly) |
| 요구사항을 가입·예매·현장 업무로 연결 | 평가 기준을 응답 규칙으로 구체화 | 요청 단위로 지연·오류 원인을 추적 |

<br/>

<a id="danzzan"></a>

## 01. 단짠
### 축제 예매와 현장 입장을 연결한 서비스 개발·운영

`2025.12 – 진행 중` &nbsp; `팀 프로젝트` &nbsp; `서비스 운영`

축제 정보 탐색부터 예매, 현장 입장과 팔찌 배부까지 연결하는 대학 축제 웹앱입니다. 총학생회·학교·협력사와 요구를 조율하고, AI 도구를 활용한 화면 구현과 사용자 검증, 운영 장애 복구에 참여했습니다.

> **팀 운영 성과** · 약 열흘 만에 가입자 약 **6,000명**, 티켓 **3,500장 1분 매진**. 얼굴인증 입장과 관리자 화면을 활용한 현장 배부를 운영했습니다.

```mermaid
flowchart LR
    A[가입 · 정보 수집] --> B[축제 정보 · 예매]
    B --> C[예매자 명단 전달]
    C --> D[외부 얼굴인증 입장]
    B --> E[관리자 조회 · 팔찌 배부]
    style A fill:#e0f2fe,stroke:#7dd3fc,color:#0f172a
    style B fill:#e0f2fe,stroke:#7dd3fc,color:#0f172a
    style C fill:#ede9fe,stroke:#c4b5fd,color:#0f172a
    style D fill:#ede9fe,stroke:#c4b5fd,color:#0f172a
    style E fill:#dcfce7,stroke:#86efac,color:#0f172a
```

**제가 맡은 문제와 해결**

| 문제 | 판단과 실행 |
| :--- | :--- |
| 같은 네이버 ID라도 날짜별 입장 권한이 다름 | 협력사에 날짜별 처리 기준을 질문하고, 수정분과 전체 명단 중 전달 범위를 확인해 전체 명단 대조 방식에 합의 |
| 외부 입장 연계에 필요한 정보를 가입 과정에서 수집해야 함 | 팀원과 단계 추가 여부를 비교해 기존 3단계를 유지. 마지막 단계에 안내·입력란을 배치하고 React/TypeScript 화면과 필수 동의 판정을 수정 |
| 베타테스트에서 SMS 인증 방식에 혼란이 생김 | 안내를 간결하게 고치고 SMS 딥링크로 문자 앱을 연결. 네이버 이메일 형식 입력은 협력사와 정제 담당을 별도로 합의 |

<details>
<summary><b>구현 근거 · 가입 흐름과 동의 판정</b></summary>

<br/>

- **설계 판단:** 입력 단계를 늘리는 대신 기존 마지막 단계에 네이버 ID 수집을 포함했습니다. 초기 흐름은 팀원과 공동으로 논의했습니다.
- **코드 변경:** 필수 동의 여부를 고정된 배열 인덱스로 확인하던 방식을 각 항목의 `required` 속성과 체크 여부에 따라 판정하도록 수정했습니다.
- **사용자 확인:** 서비스를 처음 사용하는 학생의 베타테스트에서 인증 방법의 혼란을 확인하고 안내와 문자 앱 연결을 개선했습니다.
- **남은 입력 문제:** 안내만으로 네이버 이메일 형식의 입력이 사라지지는 않았습니다. 개발팀의 정제 방안을 제안하고, 협의 후 네이버페이가 정제를 맡기로 했습니다.

[가입·동의 판정 변경 PR #65](https://github.com/DKU-Dan-Zzan/Danzzan-FE/pull/65)

PR은 입력 안내와 동의 판정 변경의 근거입니다. 최초 가입 구조와 SMS 연결의 전체 변경 이력을 의미하지는 않습니다.

</details>

<details>
<summary><b>운영 문제 해결 · 번역 누락과 반복 호출 복구</b></summary>

<br/>

**현상:** 영어 화면에서 일부 콘텐츠가 한국어로 남고, 새 공지의 자동 번역도 채워지지 않았습니다. 최초 구현 담당자와 협의한 뒤 복구를 맡았습니다.

| 단계 | 수행 내용 |
| :--- | :--- |
| 원인 확인 | 클라우드 서버의 Docker 로그를 확보하고 AI와 분석. MySQL 영문 컬럼 길이 초과로 회차 전체 저장이 롤백되어 같은 데이터를 반복 번역하는 구조를 확인 |
| 수정 | 영문 컬럼 확장, 저장 트랜잭션을 행별로 분리하는 수정본 배포, 번역 재개 후 공백 데이터 정리 |
| 검증 | 실제 번역 대상 조건으로 미번역 데이터 **0건** 확인. 신규 공지의 자동 번역·저장·영어 화면 표시까지 확인 |

저는 장애 발견, 로그 확보, AI를 활용한 분석·수정, 배포 후 확인을 맡았습니다. 번역 기능의 최초 구현은 팀원의 작업입니다.

[번역 복구 PR #70](https://github.com/DKU-Dan-Zzan/Danzzan-BE/pull/70) · [복구 확인 기록](https://github.com/DKU-Dan-Zzan/Danzzan-BE/pull/70#issuecomment-5473781220)

</details>

**사례에 사용한 기술** &nbsp; `React` `TypeScript` `Spring Boot` `MySQL` `Docker`

[프론트엔드 저장소 ↗](https://github.com/DKU-Dan-Zzan/Danzzan-FE) &nbsp;·&nbsp; [백엔드 저장소 ↗](https://github.com/DKU-Dan-Zzan/Danzzan-BE)

<br/>

---

<a id="conquer-health"></a>

## 02. Conquer Health
### 평가 기준을 응답 규칙으로 옮긴 의료 AI 개선

`2026.08` &nbsp; `팀 해커톤` &nbsp; `20시간`

루닛의 의료 특화 모델 **L2-preview**를 활용해 건강 상담 응답을 개선했습니다. 저는 개발 중 비교 결과를 근거로 집중할 방향을 제안하고, **HealthBench 평가 기준 분석과 팀의 하네스 공동 개선**에 참여했습니다.

> **팀 평가 성과** · 정식 평가 3라운드 평균 **46.51점**, 평가 참여 **14팀 중 1위** · 🏆 **벤치마크상**

**평가 관점을 구현으로 연결한 방식**

| 개선 관점 | 응답 규칙으로 구체화 |
| :--- | :--- |
| 답변의 누락 줄이기 | 질문에 포함된 모든 요구를 다루도록 지시 |
| 위험 신호 전달 | 주의해야 할 위험 신호를 답변에 포함하도록 지시 |
| 맥락에 맞는 답변 | 답을 바꿀 핵심 정보가 부족하면 질문하되, 제공할 수 있는 설명을 먼저 제시 |

<details>
<summary><b>구현 근거 · 기존 생성 요청에 응답 규칙 적용</b></summary>

<br/>

**접근 변경:** 검색 도구 중심 접근의 점수가 정체된 상황에서, 당시 대시보드 최고점 구현에 남은 시간을 집중하자고 제안했습니다. 이후 팀과 평가 기준을 응답 행동 규칙으로 구체화했습니다.

**구현 구조:** `ANSWER_INSTRUCTION`을 `_with_answer_instruction`에서 마지막 사용자 메시지에 덧붙여 기존 생성 요청에 반영했습니다. 이 규칙을 적용하기 위한 별도 LLM 호출은 추가하지 않았습니다.

**결과 해석:** 정식 평가 점수는 팀 전체 구현의 결과입니다. 개별 규칙 하나의 독립적인 점수 상승 효과나 실제 의료 현장에서의 성능을 의미하지 않습니다.

[팀의 응답 규칙 변경 커밋](https://github.com/Hackathon-AIM/health-conquer-submission/commit/52e79c8f5e2cb080466f9a299ee05b0afd9d0f69)

</details>

**사례에 사용한 기술** &nbsp; `Python` `LLM` `Prompt / Harness` `HealthBench`

[프로젝트 저장소 ↗](https://github.com/Hackathon-AIM/health-conquer-submission)

<br/>

---

<a id="olly"></a>

## 03. OLLY
### 느린 LLM 요청의 원인을 단계별로 확인하는 관측성 MVP

`2026.05 – 2026.06` &nbsp; `4인 팀` &nbsp; `로컬 MVP`

전체 응답 시간만으로 구분하기 어려운 검색·모델 호출·오류를 요청 단위로 추적하는 프로젝트입니다. 저는 **문제 정의, 로컬 SLM 선택과 개발 범위 판단, 검증 시나리오 설계**를 맡았으며 AI 에이전트를 활용했습니다.

> **검증 범위** · 정상·검색 지연·모델 지연·토큰 증가·오류, **5개 시나리오 × 10회**

**관측 흐름** &nbsp; Chat UI → `request_id / trace_id` → Dashboard · Jaeger → 오류 알림

| 확인하고 싶은 문제 | 관측 방법 |
| :--- | :--- |
| 검색과 모델 호출 중 어느 단계가 느린가 | 지연을 주입한 단계의 span과 소요 시간을 비교 |
| 토큰 증가가 요청에 어떻게 나타나는가 | 요청별 토큰·비용 지표를 확인 |
| 실패한 요청을 끝까지 추적할 수 있는가 | 오류 상태를 유지한 채 대시보드·Jaeger 추적과 Discord 알림을 연결 |

<details>
<summary><b>설계와 검증 · 반복 가능한 실험 범위 설정</b></summary>

<br/>

- **문제 정의:** 총 응답 시간만 보는 대신 한 요청 안의 실행 단계를 나누어 병목을 확인하도록 했습니다.
- **범위 선택:** 외부 API 비용과 호출 제한의 영향을 줄이기 위해 로컬 SLM으로 실험 범위를 정했습니다.
- **검증 설계:** 정상 흐름과 단계별 지연·토큰 증가·오류를 구분해 반복 실행하도록 설계했습니다.
- **팀의 확인 결과:** 시나리오별 span·지표의 차이를 관찰하고, 오류 요청의 추적과 Discord 알림 연결을 확인했습니다.

이 결과는 로컬 MVP의 관측 흐름 검증입니다. 운영 환경의 성능 개선율을 측정한 결과는 아닙니다.

</details>

**프로젝트 기술** &nbsp; `FastAPI` `OpenTelemetry` `Prometheus` `Jaeger` `Grafana` `Docker` `Kubernetes`

[프로젝트 저장소 ↗](https://github.com/lee-y-ch/olly)

<br/>

---

<a id="activities"></a>

## 🤝 Activities

**단국대학교 SW 서포터즈 (2026.03 ~ 2026.08)**  
- **홍보 및 마케팅 기획:** 신설된 홍보팀 소속으로 SW중심대학사업단 주요 행사 및 장학 정보를 알리는 인스타그램 카드뉴스 기획 및 디자인 제작.
- **행사 메인 진행(MC):** 교내 주요 경진대회 발표장 메인 진행자(MC) 담당 및 각종 SW 관련 행사 운영 전반 총괄 지원.

**단국대학교 SW 서포터즈 (2025.09 ~ 2026.02)**  
- **행사 운영 지원:** 캡스톤 대회, AI톤 등 SW중심대학사업단 주관 주요 행사 운영 보조.
- **실습 및 연구 지원:** Cosmos+ OpenSSD 장비 관리, FTL 실습 지원 및 연구 장비 교육 보조를 통한 실무 경험 축적.

<br/>

---

<a id="tech-stack"></a>

## 🛠️ Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/> <br/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/> 
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white"/> 
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/> <br/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/> 
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/> 
</p>

<br/>

<p align="center">
  <a href="mailto:pjuhee23@dankook.ac.kr">pjuhee23@dankook.ac.kr</a><br/>
  <sub>박주희 · Software Engineer</sub>
</p>
