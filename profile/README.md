<div align="center">

# Counting Stars · 카운팅 스타

### ChatGPT와 Vibe Coding 이후, 개발자 생태계는 어떻게 변했는가?

**GitHub · Stack Overflow 데이터 기반 AI 개발 생태계 변화 정량 분석**

<br>

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Prophet](https://img.shields.io/badge/Prophet-4267B2?style=for-the-badge&logo=meta&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=plotly&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

<sub>한양대학교 ERICA · 스마트융합공학부 스마트ICT융합전공</sub>

</div>

---

## 프로젝트 개요

> 2022년 11월 ChatGPT 출시가 소프트웨어 개발 시장에 미친 영향을
> GitHub와 Stack Overflow 데이터로 정량 분석합니다.

AI 코드 생성 도구가 **프로젝트 생성량 · 언어별 사용 추세 · AI 분야별 성장 패턴**에
어떤 변화를 가져왔는지, 시계열 분석과 Prophet 예측 모델로 탐구합니다.
분석 기간은 ChatGPT 출시 전후를 비교할 수 있는 **2021–2025년**입니다.

---

## 연구 질문

| | 질문 |
|:--:|:--|
| **RQ1** | ChatGPT 출시 전후(2021–2022 vs 2023–2025) GitHub AI 프로젝트는 어떻게 변화했는가? |
| **RQ2** | GitHub 레포지토리가 2023년 이후 실제로 증가했는가? |
| **RQ3** | AI 분야별(LLM · 강화학습 · 컴퓨터비전 · NLP) 프로젝트 증가 양상이 다른가? |
| **RQ4** | Stack Overflow 질문 수와 GitHub 프로젝트 수 간 상관관계가 있는가? |

## 가설

- **H1** · ChatGPT 출시 이후 AI 레포지토리는 이전 대비 500% 이상 증가했을 것이다
- **H2** · Python이 2023년 이후 꾸준히 상승해 Jupyter Notebook을 추월했을 것이다
- **H3** · LLM 분야가 2023년 이후 가장 높은 성장률을 보일 것이다
- **H4** · GitHub 프로젝트 수와 Stack Overflow 질문 수 간 강한 상관관계(|r| > 0.7)가 존재할 것이다

---

## 주요 성과

| 발견 | 내용 |
|:--|:--|
| **LLM 분야 급부상** | ChatGPT 이후 25만 건 이상으로 폭증, 새로운 주류 카테고리 형성 |
| **개발 패러다임 전환** | 2023년 중반 Python이 Jupyter Notebook 추월 (연구 → 애플리케이션 개발) |
| **Stack Overflow 역상관** | GitHub 프로젝트 증가 시 Stack Overflow 질문 감소 (상관계수 −0.70) |
| **Prophet 예측 모델** | 장기 추세·계절성 분리, ChatGPT/Auto-GPT 이벤트 효과 정량화 |

---

## 기술 스택

| 분류 | 내용 |
|:--|:--|
| **데이터 수집** | GitHub API · Stack Overflow Data Dump |
| **전처리** | Pandas · NumPy |
| **시계열 · 예측** | Facebook Prophet (시계열 분해 · 이벤트 효과 분석) |
| **시각화** | Matplotlib · Seaborn (Log Scale 트렌드 · 상관관계 분석) |
| **분류 카테고리** | LLM · Deep Learning · Computer Vision · NLP · Reinforcement Learning |

---

## 팀 구성

| 역할 | 이름 | 담당 업무 |
|:--:|:--:|:--|
| **PM** | 윤태웅 | 프로젝트 관리 · 보고서 작성 |
| **Data Analyst** | 원준서 | 데이터 분석 · 시각화 |
| **Data Engineer** | 이라온 | Stack Overflow 데이터 수집 · 전처리 |
| **Data Collector** | 송민찬 | GitHub 데이터 수집 |

---

## 프로젝트 바로가기

<div align="center">

[![dataAnalysis](https://img.shields.io/badge/dataAnalysis-Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/TeamCountingStars/dataAnalysis)
[![Web](https://img.shields.io/badge/프로젝트_웹페이지-Visit-2b5bfe?style=for-the-badge)](https://teamcountingstars.github.io/dataAnalysis/)

</div>

---

<div align="center">

**Contact** · 윤태웅 (PM) · [taewoong25@hanyang.ac.kr](mailto:taewoong25@hanyang.ac.kr)

<sub>© 2026 Team Counting Stars · 한양대학교 ERICA</sub>

</div>
