<p align="center"> 
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:8EC5FC,100:E0C3FC&height=180&section=header&text=Juhee%20Park🌱&fontSize=50&fontColor=2F4F4F&animation=fadeIn&desc=Software%20Engineer&descAlignY=62&descAlign=50" /> 
</p>

<div align="center">
  
| Name | Juhee Park (박주희) |
|------|----------------------|
| Student ID | 32221902 |
| Major | 단국대학교 소프트웨어학과 (3학년) |
| Email | pjuhee23@dankook.ac.kr |
| GitHub | [github.com/juhee0223](https://github.com/juhee0223) |
| Lab | [System Software Laboratory (SSLAB)](https://sslab.dankook.ac.kr/) |
| GPA | 누적 학점 4.34 / 4.5 |

</div>

---

### About Me
**시스템 소프트웨어와 AI를 연결하는 백엔드·스토리지 엔지니어** 박주희입니다.  
저는 **데이터 경로의 최하단(FTL, GC)** 부터 **AI 기반 성능 분석과 최적화** 까지 다루며,  
시스템의 동작 원리를 정량적으로 이해하고 개선하는 일을 할 수 있습니다.

최근에는 **RocksDB Compaction (Leveled / Universal / FIFO)** 을 분석해서
**WAF–Latency 트레이드오프를 수치화**했고, 이를 **KCC 2025 논문(1저자)** 으로 발표했습니다.  
또한 **YOLOv5 + BirdNET 기반 실시간 AI 시스템**을 개발해 **KHUTHON 2025 해커톤 우수상**을 수상하며,  
**리소스 제약 환경에서의 AI 모델 최적화 및 병렬 처리 효율화**를 경험했습니다.

이처럼 저는 **AI 기술을 시스템 성능 분석과 운영 효율 향상에 접목**하는  
**‘AI-aware System Engineer’** 로 성장하고자 합니다.  

> 관심 분야 키워드: **WAF 최소화 · Compaction Budget · AI-driven Profiling · Resource-efficient Inference**

---

### Research Interests
- Operating Systems Internals (스케줄링, 메모리 관리, I/O 서브시스템)  
- Storage System Optimization (FTL, RocksDB 등)  
- Data-driven System Analysis (성능 로그 기반 이상 탐지 및 시각화)  
- Software Reliability Engineering (WAF 최소화 연구)  

---

### Projects

<div align="center">

| 프로젝트 | 기간 | 설명 | 기술 | 성과 / 링크 |
|:----------:|:------|:------|:------|:------|
| **FTL Simulator (GameGC)** | 2025.10 – Ongoing | 다양한 GC 정책(Greedy, Cost-Benefit)을 C로 구현하고, Incremental GC를 모방한 Pipeline 기반 **GameGC** 방식의 성능 비교 실험 수행 | C, File I/O, Visualization | **Ongoing Research Project**<br/>GC latency의 **스파이크 vs 점진적 회수 패턴** 분석 중<br/>[🔗 GitHub](https://github.com/day-e0n/ssp_team_project.git) |
| **DACON – 고객 지원 등급 분류** | 2025.09 – 2025.10 | 고객 데이터를 기반으로 지원 필요 수준을 분류하는 AI 모델 개발<br/>Feature Engineering 및 모델 성능 비교 실험 수행 | Python, scikit-learn, TensorFlow, XGBoost | F1 Score 상위 10% 달성<br/>[🔗 GitHub](https://github.com/juhee0223/DACON-Customer-Support-Classification) |
| **AI Bird Repeller** | 2025.05.09 – 2025.05.10 <br/> *(무박 2일 해커톤)* | (대회 주제: 농업의 기술화) <br/> YOLOv5 + BirdNET으로 농작물에 피해를 입히는 조류를 인식하고, 각 새가 싫어하는 소리를 자동 재생하는 지능형 퇴치 시스템 | Python, Threading, YOLOv5, BirdNET | 🏆 **KHUTHON 2025 해커톤 우수상 수상**<br/>→ 실시간 AI 인퍼런스 환경에서의 리소스 최적화 경험으로 스토리지·OS 성능 튜닝 역량 강화에 기여<br/>[🔗 GitHub](https://github.com/JustYOLO/Getout_Bird) |
| **RocksDB Compaction Analyzer** | 2025.01 – 2025.05 | RocksDB의 Compaction Style(Leveled, Universal, FIFO) 간 성능 차이를 자동 측정·분석 및 시각화 | RocksDB DBBench, Bash, Python | **KCC 2025 논문(1저자)** 발표<br/>→ 실제 스토리지 엔진의 데이터 경로 구조 분석 및 성능 병목 추적 경험 |
| **Sun(善)-Date** | 2025.11.22 – 2025.11.22 <br/> *(해커톤)* | (대회 주제: 사회적 문제 해결 또는 일상 속 작은 불편함 개선) <br/> 봉사활동을 함께 하며 서로를 알아볼수있는 소개팅 서비스. <br/> 만남에 대한 수요가 늘어나가는 청년들의 니즈를 활용하여 봉사활동을 함께 하며, 선한 목적을 가진 경험이 만남으로 이어지도록 한다. | django, flutter, java | 🏆 **EASYTHON 2025 해커톤 우수상 수상**<br/> <br/>[🔗 GitHub](https://github.com/day-e0n/sun_date) |


</div>


---

### Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/> 
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white"/> 
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/> <br/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/> 
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/> 
</p>

#### 기술적 강점

**시스템 소프트웨어 분석 및 성능 최적화**
- C/C++ 기반의 **운영체제·스토리지 내부 구조(FTL, Compaction, GC)** 분석 및 튜닝 경험  
- Linux 환경에서 **fio, strace** 등을 활용한 병목 추적 및 성능 분석  
- RocksDB, NAND FTL 시뮬레이터 등 **실제 스토리지 워크로드 재현 환경 구축 및 최적화**

**AI 기반 분석 및 실험 자동화**
- Python 기반으로 **성능 로그 분석·시각화 파이프라인** 구축  
- scikit-learn, Keras를 활용한 **모델 기반 성능 예측·이상 탐지 실험** 수행  
- **Bash + Python 스크립트**로 수십 회의 실험 반복을 자동화하고 결과를 구조화

**데이터 중심 문제 해결**
- 실험 결과를 기반으로 **WAF, p99 latency, throughput** 등 지표를 수치화하여 원인 분석  
- **AI 모델의 효율적 추론(리소스 사용률 감소)** 및 **시스템 성능 향상**을 동시에 고려한 설계 경험  
- 연구·프로젝트 전반에 **측정 → 분석 → 시각화 → 개선**의 정량적 접근을 적용

**협업 및 확장성**
- GitHub 기반 협업 및 버전 관리
- 논문(KCC 2025, WDSC 2025) 및 해커톤 프로젝트를 통해 **연구·개발·성과 발표까지 전주기 과정 수행해본 경험**

---

### Publications

| 제목 | 학회 / 연도 | 개요 | 비고 |
|:------|:-------------|:------|:------|
| **RocksDB에서 Compaction Style에 따른 성능 변화 분석**<br/>박주희, 신호진, Guangxun Zhao, 최종무 | [**KCC 2025 (한국컴퓨터종합학술대회)**](https://www.kiise.or.kr/conference/kcc/2025/) | RocksDB의 Leveled / Universal / FIFO 컴팩션 스타일 간 Write Amplification–Read Efficiency 트레이드오프를 정량적으로 분석 | <br/>NRF 중견연구자지원사업 (No. 2022R1A2C1006050)<br/>SW중심대학사업 (2024-0-00035) |
| **Visualization and Semantic Interpretation of Vector Space Structures: A Case Study Based on OSTEP**<br/>Bo-seung Kim, Juhee Park, Si-hwan Yoo, Jongmoo Choi, Min-kyu Park, Kwang-il Jeon. | [**WDSC 2025 (정보보안 및 고신뢰컴퓨팅 하계워크샵)**](https://sites.google.com/view/wdsc2025/) | OSTEP 교재 텍스트를 임베딩하여 벡터 공간 구조를 시각화하고 의미론적 군집을 분석한 연구 | 🏆 **WDSC 2025 우수논문상 수상** |

---

### 🏆 Awards & Honors

| 연도 | 수상명 | 주최 / 기관 | 비고 |
|:--:|:--|:--|:--|
| **2025** | 🏆 KHUTHON 2025 해커톤 우수상 (대회 주제: 농업의 기술화) | (단국대, 경희대, 아주대, 경기대) SW중심사업단 | 프로젝트: *AI Bird Repeller (YOLOv5 + BirdNET)* |
| **2025** | 🥇 WDSC 2025 우수논문상 | 정보보안 및 고신뢰컴퓨팅 하계워크샵 | 논문: *Visualization and Semantic Interpretation of Vector Space Structures* |

---

### Career Vision (Learning Goals)
**단기 (0–6개월)**  
- **RocksDB × FTL 시뮬레이션 프레임워크** 구축  
- 워크로드별 컴팩션 예산 추천 리포트 자동화 + **AI 모델 기반 성능 예측 실험**  
- 목표: 동일 하드웨어에서 **WAF 감소**

**중기 (6–12개월)**  
- **AI 기반 스토리지 성능 분석 파이프라인** 구현 (로그 → 모델 예측 → 시각화)  
- **Hot/Cold 구분 자동화 및 Compaction Cost 예측 모델** 개발  
- 목표: **GC 빈도 감소**, **장애 예측 정확도 90% 이상**

**장기 (1–3년)**  
- **AI + System co-design 연구**로 확장 (Compaction scheduler, FTL policy adaptation)  
- 국제 학회 논문 및 오픈소스 기여  
- 목표: **AI-driven storage optimizer prototype** 완성

**학습 목표**  
- **AI 분석 기반 운영 효율화**: 문제 원인을 로그 수준에서 조기 탐지  
- **성능·비용 최적화**: WAF·GC·CPU 사용률을 동시에 줄이는 데이터 기반 의사결정  
- **확장성 향상**: AI 모델로 워크로드 특성을 자동 분류해 운영 자동화 실현

---

### Activities
**단국대학교 SW 서포터즈 (2025.09 ~ 2026.02 예정)**  
- SW중심대학사업단 주관 행사 운영 (캡스톤 대회, AI톤 등)  
- Cosmos+ OpenSSD 장비 관리 및 FTL 실습 지원  
- 연구 장비 운영 및 교육 지원을 통한 실무 경험 축적  

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=juhee0223&show_icons=true&theme=transparent&hide_border=true" width="48%"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=juhee0223&layout=compact&theme=transparent&hide_border=true" width="48%"/>
</p>

---

📧 **Email:** [pjuhee23@dankook.ac.kr](mailto:pjuhee23@dankook.ac.kr)  
🔗 **GitHub:** [github.com/juhee0223](https://github.com/juhee0223)


<br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/heejinnn/heejinnn/blob/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/heejinnn/heejinnn/blob/output/github-contribution-grid-snake.svg" />
 <img alt="github-snake" src="https://github.com/yanni13/yanni13/blob/output/github-contribution-grid-snake-dark.svg"/>
</picture>


</div>
