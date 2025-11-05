<p align="center"> <img src="https://capsule-render.vercel.app/api?type=waving&color=0:8EC5FC,100:E0C3FC&height=180&section=header&text=Juhee%20Park🌱&fontSize=50&fontColor=2F4F4F&animation=fadeIn&desc=Software%20Engineer&descAlignY=62&descAlign=50" /> </p>

<div align="center">
  
| Name | Juhee Park (박주희) |
|------|----------------------|
| Student ID | 32221902 |
| Major | 단국대학교 소프트웨어학과 (3학년) |
| Email | pjuhee23@dankook.ac.kr |
| GitHub | [github.com/juhee0223](https://github.com/juhee0223) |
| Lab | [System Software Laboratory (SSLAB)](https://sslab.dankook.ac.kr/) |

</div>

---

### About Me
안녕하세요, **운영체제와 스토리지 시스템을 연구하는 개발자 지망생 Juhee Park**입니다.  
데이터가 저장되고 이동하는 가장 밑단의 구조에 흥미를 가지고 있으며,  
**LSM-tree, FTL, RocksDB** 같은 스토리지 아키텍처를 분석하고 최적화하는 일을 즐깁니다.  

현재 **단국대학교 System Software Laboratory**에서  
**NAND Flash 기반 FTL 구조와 RocksDB의 컴팩션 정책 분석 연구**를 진행 중입니다.  
이 연구를 기반으로 **KCC 2025에서 논문을 발표**했습니다.  

> “데이터가 저장되는 가장 낮은 계층까지 이해하는 백엔드/스토리지 엔지니어”가 되는 것이 목표입니다.

---

### Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/> 
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white"/> 
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/> <br/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/> 
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/> </p>

#### 기술적 강점
- C/C++ 기반 시스템 소프트웨어 구조 분석 및 성능 튜닝 경험  
- Linux 환경에서의 디버깅·프로파일링 툴 사용 (perf, gprof, iostat 등)  
- FTL, Compaction, Garbage Collection 등 스토리지 내부 동작 실험  
- Python, Bash를 활용한 실험 자동화 및 시각화  

---

### Projects


<div align="center">

| 프로젝트 | 설명 | 기술 | 성과 / 링크 |
|:----------:|:------|:------|:------|
| **AI Bird Repeller** | YOLOv5 + BirdNET으로 조류를 인식하고, 각 새가 싫어하는 소리를 자동 재생하는 지능형 퇴치 시스템 | Python, Threading, YOLOv5, BirdNET | 🏆 KHUTHON 2025 해커톤 **우수상 수상**<br/>→ 실시간 AI 인퍼런스 환경에서의 리소스 최적화 경험으로 스토리지·OS 성능 튜닝 역량 강화에 기여<br/>[🔗 GitHub](https://github.com/JustYOLO/Getout_Bird) |
| **RocksDB Compaction Analyzer** | RocksDB의 Compaction Style(Leveled, Universal, FIFO) 간 성능 차이를 자동 측정·분석 및 시각화 | RocksDB DBBench, Bash, Python | **KCC 2025 논문(1저자)** 발표<br/>→ 실제 스토리지 엔진의 데이터 경로 구조 분석 및 성능 병목 추적 경험<br/> |
| **DACON – 고객 지원 등급 분류** | 고객 데이터를 기반으로 지원 필요 수준을 분류하는 AI 모델 개발<br/>Feature Engineering 및 모델 성능 비교 실험 수행 | Python, scikit-learn, TensorFlow, XGBoost | F1 Score 상위 10% 달성<br/>[🔗 GitHub](https://github.com/juhee0223/DACON-Customer-Support-Classification) |
| **FTL Simulator (GameGC)** | 다양한 GC 정책(Greedy, Cost-Benefit, CAT)을 C로 구현하고, Pipeline 기반 **GameGC** 방식의 성능 비교 실험 수행 | C, File I/O, Visualization | **Ongoing Research Project**<br/>GC latency의 **스파이크 vs 점진적 회수 패턴** 분석 중<br/>[🔗 GitHub](https://github.com/juhee0223/OpenSSD-GC) |

</div>


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
| **2025** | 🏆 KHUTHON 2025 해커톤 우수상 | (단국대, 경희대, 아주대, 경기대) SW중심사업단 | 프로젝트: *AI Bird Repeller (YOLOv5 + BirdNET)* |
| **2025** | 🥇 WDSC 2025 우수논문상 | 정보보안 및 고신뢰컴퓨팅 하계워크샵 | 논문: *Visualization and Semantic Interpretation of Vector Space Structures* |

---


### Research Interests
- Operating Systems Internals (스케줄링, 메모리 관리, I/O 서브시스템)  
- Storage System Optimization (FTL, RocksDB 등)  
- Data-driven System Analysis (성능 로그 기반 이상 탐지 및 시각화)  
- Software Reliability Engineering (WAF 최소화 연구)  

---

### Activities
**단국대학교 SW 서포터즈 (2025.09 ~ 2026.02 예정)**  
- SW중심대학사업단 주관 행사 운영 (캡스톤 대회, AI톤 등)  
- Cosmos+ OpenSSD 장비 관리 및 FTL 실습 지원  
- 연구 장비 운영 및 교육 지원을 통한 실무 경험 축적  

---

### Career Vision
시스템의 가장 낮은 레이어에서 문제를 이해하고 해결하는 엔지니어로 성장하고 싶습니다.  

**단기 목표 (1년 이내)**  
- RocksDB와 FTL Simulator를 통합한 분석 프레임워크 구축  
- C++ 기반의 저수준 성능 최적화 및 디버깅 역량 강화  

**중기 목표 (3년 내)**  
- 대용량 스토리지 엔진 및 백엔드 인프라 연구 참여  
- 국제 학회 논문 제출 및 오픈소스 기여  

**장기 목표 (5년 이상)**  
- Storage/Database/OS 커널 전문 엔지니어로 성장  
- 실험적 결과를 기반으로 산업용 DB 성능 최적화 연구 수행  

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=juhee0223&show_icons=true&theme=transparent&hide_border=true" width="48%"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=juhee0223&layout=compact&theme=transparent&hide_border=true" width="48%"/>
</p>

---

📧 **Email:** [pjuhee23@dankook.ac.kr](mailto:pjuhee23@dankook.ac.kr)  
🔗 **GitHub:** [github.com/juhee0223](https://github.com/juhee0223)
