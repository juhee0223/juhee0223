# 박주희 (Juhee Park)

**이메일:** pjuhee23@dankook.ac.kr  
**GitHub:** [github.com/juhee0223](https://github.com/juhee0223)  
**전공:** 단국대학교 소프트웨어학과 (졸업 예정: 2026년 2월)  
**관심 분야:** 시스템 소프트웨어 · 스토리지 성능 최적화 · AI 기반 운영 효율화  

---

## 지원 직무 목표
저는 **시스템 소프트웨어와 AI 기술을 융합하여 스토리지 및 백엔드 시스템의 성능을 최적화하는 엔지니어**를 목표로 하고 있습니다.  
특히 RocksDB·FTL(Flash Translation Layer)·Compaction과 같은 **저수준 데이터 경로 분석**을 기반으로,  
AI 모델을 활용해 **성능 병목을 조기 감지하고 자동으로 자원 사용을 최적화하는 시스템**을 설계하고자 합니다.  
이러한 목표는 제가 수행해온 연구 및 프로젝트 경험을 통해 구체적으로 발전해왔습니다.

---

## 학력
**단국대학교 소프트웨어학과 (B.S.)**  
(2022.03 – 2026.02 예정)  
- 전공 학점 4.34 / 4.5 
- 시스템소프트웨어 연구실(SSLAB) 학부연구생  

---

## 주요 프로젝트 및 연구 경험

### RocksDB Compaction Analyzer (2025.1 ~ 2025.8)
**주요 역할:** 시스템 성능 분석 및 자동화 파이프라인 개발  
**관련 기술:** C++, Bash, Python, RocksDB, fio, 데이터 시각화  

- RocksDB의 **Leveled / Universal / FIFO Compaction** 방식을 실험적으로 비교하여  
  Write Amplification Factor(WAF)와 읽기 지연(p99 latency)의 상관관계를 정량적으로 측정함.  
- **Bash 스크립트 + Python 분석 모듈**을 연동하여 수백 회의 벤치마크 실험을 자동화하고,  
  결과를 그래프로 시각화하여 성능 추세를 분석함.  
- Compaction 구조 내 데이터 재배치에 따른 병목 구간을 탐색하고,  
  최적의 Compaction 정책 설계 인사이트를 도출함.  
- **KCC 2025 논문(제1저자)** 으로 발표되어, 실제 환경에서의 읽기 효율성과 쓰기 증폭의 트레이드오프를 정량적으로 제시함.

**① 의미 있는 이유:**  
시스템 내부 구조를 직접 조작하며 성능을 **수치적으로 검증한 첫 실험 기반 연구**임.  

**② 노력한 과정과 결과:**  
로그 파싱 및 스크립트 불안정성을 해결하며 **10만 건 이상의 데이터를 자동 처리**하는 파이프라인을 완성함.  

**③ 입사 후 기여점:**  
로그 기반 성능 진단 및 자동화 역량을 활용해, **DB/Storage 운영 환경에서 실시간 병목 감지 시스템** 개발에 기여할 수 있음.

---

### AI Bird Repeller (KHUTHON 2025 해커톤, 2025.05)
**주요 역할:** 실시간 AI 인식 및 리소스 최적화 설계  
**관련 기술:** Python, Threading, PyTorch, YOLOv5, 실시간 추론  

- **YOLOv5 + BirdNET**을 결합하여 조류 인식 후, 새별 싫어하는 주파수의 소리를 자동 재생.  
- **CPU/GPU 제한 환경에서 스레드 기반 병렬 처리 + 메모리 버퍼 최적화**로 실시간 추론 확보.  
- **KHUTHON 2025 해커톤 우수상(2위)** 수상.  

**① 의미 있는 이유:**  
AI 시스템을 단순 모델 수준이 아닌 **운영 체계 수준에서 최적화**한 실시간 시스템 구현 경험.  

**② 노력한 과정과 결과:**  
Thread 기반 구조를 직접 설계하여 **2.3배 빠른 추론**과 **메모리 사용량 30% 감소** 달성.  

**③ 입사 후 기여점:**  
엣지 AI, IoT 환경에서의 **실시간 처리 및 자원 최적화 설계** 역량 보유.

---

### DACON – 고객 지원 등급 분류 (2025.9 – 2025.10)
**주요 역할:** 데이터 분석 및 모델링  
**관련 기술:** Python, scikit-learn, TensorFlow, XGBoost  

- 고객 데이터를 기반으로 지원 필요도 등급 분류 모델 개발.  
- Feature Engineering, Cross Validation, 모델 성능 비교(XGBoost, TensorFlow) 수행.  
- 자동화된 전처리 및 모델 평가 파이프라인 구축으로 **F1 Score 상위 10% 달성.**

**① 의미 있는 이유:**  
AI 모델링을 비즈니스 의사결정과 연결된 **데이터 기반 문제 해결 과정**으로 접근함.  

**② 노력한 과정과 결과:**  
Feature Selection + Grid Search를 통해 반복 실험 효율 **40% 향상.**  

**③ 입사 후 기여점:**  
운영 로그 및 성능 데이터 기반 **예측/분석 시스템 구축 역량** 확보.

---

### FTL Simulator (GameGC) (2025.10 – 현재)
**주요 역할:** Garbage Collection 정책 구현 및 성능 분석  
**관련 기술:** C, File I/O, Linux, 시스템 로그 분석  

- NAND Flash 기반 스토리지 시뮬레이터를 직접 설계하여  
  **Greedy / Cost-Benefit / CAT GC 정책**을 구현하고 성능 비교 수행.  
- GC 수행 시 invalid 페이지 수, valid 복사량, 블록 교체 비용 등을 분석함.  
- **Latency 스파이크 현상 및 점진적 회수 패턴**을 정량화하여 안정성 향상 방향 제시.  

**① 의미 있는 이유:**  
스토리지 내부 알고리즘의 동작 원리를 **하드웨어 수준에서 소프트웨어로 재현**한 경험.  

**② 노력한 과정과 결과:**  
정량 분석 모듈 추가 및 시각화를 통해 **Greedy 대비 14% 낮은 성능 스파이크 달성.**  

**③ 입사 후 기여점:**  
SSD/FTL 및 파일시스템 개발 과정에서 **성능 예측 및 검증 자동화 도구** 설계로 기여 가능.

---

## 기술 역량

<p align="center">
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white"/> 
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/> 
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
  <img src="https://img.shields.io/badge/RocksDB-4479A1?style=for-the-badge&logo=rocksdb&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
</p>

- **프로그래밍 언어:** C/C++, Python, Java, Bash  
- **시스템 분석:** Linux, fio, strace, RocksDB 내부 구조 이해  
- **AI/분석 도구:** PyTorch, TensorFlow, scikit-learn, pandas, matplotlib  
- **환경 구성:** Docker, Git, Shell Script, Jupyter Notebook  

---

## 성과 및 수상
| 연도 | 구분 | 내용 |
|:--:|:--|:--|
| 2025 | 학회 발표 | **KCC 2025 논문 (제1저자)**: *RocksDB에서 Compaction Style에 따른 성능 변화 분석* |
| 2025 | 수상 | **KHUTHON 2025 해커톤 우수상 (2위)** – 실시간 AI 시스템 개발 |
| 2025 | 논문상 | **WDSC 2025 우수논문상** – OSTEP 기반 벡터 임베딩 구조 시각화 연구 |

---

## 대외활동
**단국대학교 SW 서포터즈 (2025.09 – 2026.02 예정)**  
- SW중심대학사업단 주관 행사(캡스톤 경진대회, AI톤 등) 기획 및 운영 지원  
- Cosmos+ OpenSSD 장비 관리 및 FTL 실습 환경 구축 지원  
- 학부 연구생 및 실습생을 위한 시스템 소프트웨어 교육 보조  

---

## 자기소개 및 향후 목표
저는 시스템 소프트웨어의 구조를 단순히 사용하는 수준이 아니라, **내부 동작을 직접 분석하고 개선하는 엔지니어**로 성장하고자 합니다.  
AI 기술을 단순 응용 도구가 아닌, **시스템 성능을 수치적으로 이해하고 예측하는 분석 엔진**으로 활용하는 것이 제 목표입니다.  

향후에는 RocksDB 및 FTL 환경에서 수집되는 실시간 로그를 기반으로,  
AI 모델이 Compaction 또는 Garbage Collection 정책을 **동적으로 조정하는 시스템 프로토타입**을 개발하고자 합니다.  
이를 통해 AI와 시스템 소프트웨어가 **서로를 이해하고 협력하는 지능형 운영 환경**을 구현하는 것이 제 장기적인 방향입니다.

---

*최종 수정일: 2025년 11월*
