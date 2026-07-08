<div align="center">

<!-- 방문자 카운터 -->
<img src="https://komarev.com/ghpvc/?username=K-ismyname&style=flat-square&color=58A6FF" alt="profile views" />


<br/>

<p>
  AI 에이전트·RAG 시스템을 설계하고 프로덕션까지 끌고 가는 엔지니어입니다.<br/>
  <b>"왜 이 답을 신뢰할 수 있는가"</b>를 증거와 함께 설명할 수 있는 시스템을 만듭니다.
</p>

</div>

---

## 🛠 Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-FF6B6B?style=flat-square&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?style=flat-square&logo=neo4j&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

</div>

---

## 🚀 Featured Project — JobGraph

채용공고를 수집·분석하고, 이력서를 올리면 직무 대비 부족한 기술과 개선 방향을 알려주는 **Agentic RAG 시스템**입니다.

- **LangGraph** 기반 Corrective RAG 루프 — "증거가 충분한가"를 에이전트가 스스로 판단해 부족하면 재검색
- **Neo4j** 그래프로 직무-기술 관계(REQUIRES/CO_OCCURS) 표현, 이력서·GitHub·포트폴리오·배포 URL 4개 소스 교차검증으로 신뢰도(confidence) 등급 산출
- 적합도(얼마나 잘하는가) ⊥ 신뢰도(그 주장을 얼마나 믿을 수 있는가)를 분리해 과장된 이력서 주장을 걸러냄

🔗 [라이브 데모](https://gaheelee-job-graph.hf.space) · [소스코드](https://github.com/K-ismyname/jobgraphPJ)

---

## 🚀 Featured Project — The Formula (팀 참여)

현업 개발자·디자이너로 구성된 팀에서 AI 실무 공식 커뮤니티 **The Formula** 개발에 참여했습니다.

- **매너온도 신뢰 등급 시스템** 설계·구현 (`trust.ts` 전체 소유) — 당근마켓식 감속곡선 온도 공식, 5단계 등급 체계, 어뷰징 방지 캡 설계
- **마이페이지 전면 개편** (PR #2) — 프로필 히어로 레이아웃, 북마크 기반 관심사 자동 추론, 활동이력 타임라인
- **GA4 연동** → 수집된 로그 데이터가 AI Data Team OS 분석 파이프라인의 입력 소스

🔗 [서비스](https://the-formula-silk.vercel.app)

---

## 🚀 Featured Project — AI Data Team OS

GA4로 수집한 웹사이트 데이터를 8개 AI 에이전트가 협업해 자동 분석하는 **데이터 분석 멀티 에이전트 시스템**입니다. 질문 한 줄을 입력하면 데이터 팀의 역할 분담(Planner → Analyst → Data Scientist → QA → Head of Data)을 그대로 반영한 파이프라인이 실행됩니다.

- **LangGraph** 기반 8-Agent 파이프라인 — Planner가 분석 전략을 세우고, QA Reviewer·Evaluator가 이중 검증한 결과만 최종 출력
- **환각 방지 설계** — 에이전트는 숫자를 추정하지 않고 BigQuery Mart를 tool calling으로 직접 조회, KPI 정의는 문서 하나(SSOT)에서만 런타임 주입
- **A/B 테스트 통계 검정 자동화** — CVR 유의성 검정(two-proportion z-test)을 Python으로 결정론적 계산해 LLM의 p-value 추정을 원천 차단

🔗 [라이브 데모](https://dashboard-leegahees-projects.vercel.app) · [소스코드](https://github.com/K-ismyname/da_agent)

---

## 📊 GitHub Stats

<div align="center">
  <img height="160" src="https://github-readme-stats-kismyname.vercel.app/api?username=K-ismyname&show_icons=true&theme=github_dark&hide_border=true&count_private=true" />
  <img height="160" src="https://github-readme-stats-kismyname.vercel.app/api/top-langs/?username=K-ismyname&layout=compact&theme=github_dark&hide_border=true&langs_count=6" />
</div>

<br/>

<!-- 스트릭 카드 -->
<div align="center">
  <img src="https://streak-stats.demolab.com?user=K-ismyname&theme=github-dark-blue&hide_border=true&date_format=Y.n.j" alt="GitHub Streak" />
</div>

---

## 📈 Activity Graph

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=K-ismyname&theme=github-compact&hide_border=true&area=true" alt="activity graph" />
</div>

---

## ⏱ WakaTime

<div align="center">
  <img src="https://github-readme-stats-kismyname.vercel.app/api/wakatime?username=1d15da8c-2fbe-4d75-9ff3-2704fe474ddb&theme=github_dark&hide_border=true&layout=compact" alt="wakatime stats" />
</div>

---

## 🐍 Contribution

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)"
            srcset="https://raw.githubusercontent.com/K-ismyname/K-ismyname/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)"
            srcset="https://raw.githubusercontent.com/K-ismyname/K-ismyname/output/github-contribution-grid-snake.svg">
    <img alt="snake animation"
         src="https://raw.githubusercontent.com/K-ismyname/K-ismyname/output/github-contribution-grid-snake.svg">
  </picture>
</div>
