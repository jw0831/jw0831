<h1 align="center">김진원 | KIM JIN WON</h1>
<p align="center">
  <a href="https://www.linkedin.com/in/jinwon0831kim/">
    <img src="https://img.shields.io/badge/LinkedIn-Jinwon_Kim-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <img src="https://img.shields.io/github/followers/jw0831?style=social" alt="GitHub followers">
</p>

<p align="center">
  LLM, RAG, Agent, GraphRAG, Korean NLP, Patent Intelligence, Battery Domain AI
</p>

<p align="center">
  <strong>Core Technologies</strong>
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?logo=langchain&logoColor=white" alt="LangChain">
  <img src="https://img.shields.io/badge/Neo4j-4581C3?logo=neo4j&logoColor=white" alt="Neo4j">
</p>
<p align="center">
  <strong>AI Engineering</strong>
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Vibe_Coding-6E56CF?logo=cursor&logoColor=white" alt="Vibe Coding">
  <img src="https://img.shields.io/badge/Agent_Harness-2D3748?logo=githubactions&logoColor=white" alt="Agent Harness">
  <img src="https://img.shields.io/badge/System_Architecture-0078D4?logo=diagramsdotnet&logoColor=white" alt="System Architecture">
  <img src="https://img.shields.io/badge/Agent_Orchestration-FF6B35?logo=probot&logoColor=white" alt="Agent Orchestration">
</p>

## About

IP전략센터의 단독 AI 개발자로 LLM, RAG, Agent 기반 업무 자동화 시스템을 기획부터 설계, 개발, 운영까지 엔드투엔드로 수행하고 있습니다. 특허, 이차전지 소재, 산업 뉴스처럼 구조화하기 어려운 도메인 데이터를 실제 업무에 쓰이는 AI 시스템으로 바꾸는 일을 해왔습니다.

기계·메카트로닉스 전공 배경 위에 NLP, 시계열, XAI, LLM 응용 경험을 쌓아왔고, 최근에는 멀티에이전트 특허분석, GraphRAG, 산업 인텔리전스, 특허 RAG 챗봇을 중심으로 일하고 있습니다.

## Career

| Company | Team / Role | Period |
|---|---|---|
| (주)포스코퓨처엠 | IP전략센터 / 대리 | 2023.08 ~ 재직 중 |
| (주)아일리스프런티어 | 선행연구팀 / 매니저 | 2021.03 ~ 2023.03 |

## Education

| School | Degree | Graduated |
|---|---|---|
| Asia Pacific University of Technology & Innovation (APU), Malaysia | BEng (Hons) in Mechatronic Engineering | 2019 |

- Final Year Project: ROS 기반 SLAM 실내 자율주행 음식 배달 로봇 (매핑 정확도 95%)
- 졸업 프로젝트, 과목별 보고서, 인턴십 기술 문서, 수료증: [academic-portfolio](https://github.com/jw0831/academic-portfolio)

## Impact Highlights

- 80건 이상의 특허를 자동 분석하는 LangChain 기반 Supervisor-Subagent 멀티에이전트 파이프라인 구축
- 일일 200~300건 이차전지 산업 뉴스를 자동 수집, 분류, 요약해 경영진과 유관부서에 1년 이상 정기 배포
- 프롬프트 엔지니어링만으로 음극재 특허 기술분류 정확도 76% -> 89%(+13%p) 개선
- FastAPI 28개 API, Next.js 16 기반 9개 페이지, Streamlit 7탭, Slack 봇 5채널로 부서 AI 플랫폼 구축
- GPT-4 출시 초기 ChatGPT + LangChain 기반 특허분석 자동화 PoC를 수행하고 LLM 특허분석 제품화 가능성 검증

## Representative Projects

### DeepAgents 기반 멀티에이전트 특허분석 시스템 (2026.04 ~ 진행 중)

LangChain 기반 Supervisor-Subagent 아키텍처로 80건 이상의 특허를 자동 분석하는 멀티에이전트 파이프라인을 설계하고 구현했습니다. 특허 본문 파싱, 청구항 분석, 기술 분류, 경쟁사 비교 단계를 Subagent로 모듈화하고 FastAPI로 API화해 내부 시스템과 연동했습니다.

현재는 GraphRAG 기반 경쟁사 특허 스펙 분석·추정 에이전트와 이종 혼합기술 아이디어 자동 도출 에이전트로 확장 개발 중입니다.

### News Intelligence System (2025.03 ~ 진행 중)

이차전지 산업의 일일 200~300건 비정형 뉴스를 자동 수집, 분류, 요약해 경영진과 유관부서에 정기 배포하는 인텔리전스 시스템을 단독 설계·개발·운영했습니다. 7개 카테고리 분류 체계, LLM 기반 SWOT 브리핑, 주간 -> 월간 -> 분기 -> 반기 -> 연간 5단계 누적 인사이트 로직을 구축했습니다.

FastAPI 백엔드, Next.js 프론트엔드, HTML 메일 템플릿, Slack 봇 5채널까지 구현해 1년 이상 운영 중인 의사결정 인프라로 활용되고 있습니다.

### 특허 기술분류 자동화 및 LMR 양극재 RAG 챗봇 (2024.06 ~ 2025.06)

이차전지 소재 도메인 특허 분석 자동화를 수행했습니다. 음극재 특허 기술분류에서는 Few-shot 설계, 구조화된 출력 스키마, Self-consistency 검증을 통해 추가 파인튜닝 없이 정확도 76% -> 89%(+13%p)를 달성했습니다.

LMR 양극재 영역에서는 BGE-M3 임베딩, Vector DB, LLM, ReAct Agent를 결합한 RAG 챗봇을 구축하고, 툴 호출로 특허 검색·조회·해석을 자동화했습니다.

### IP전략센터 AI 플랫폼 풀스택 구현 및 PoC 종합 (2023.08 ~ 진행 중)

부서 업무 효율화 과제를 입사 초기부터 직접 기획, 설계, 구현했습니다. FastAPI 28개 API, Next.js 16 기반 9개 페이지, Streamlit 7탭 대시보드, Slack 봇 5채널로 내부 AI 운영 기반을 만들었습니다.

인조흑연 바인더 선행문헌 NER, 구형흑연 함침 AI 선행문헌 조사, 발명자 환산점수 프로그램 재구성, 법규 제·개정 모니터링 솔루션, 이차전지 Ontology 구축, 부서 프롬프트 자산화와 교육까지 수행했습니다.

### ChatGPT + LangChain 특허분석 자동화 PoC (2023.04 ~ 2023.05)

GPT-4 출시 초기 시점에 ChatGPT와 LangChain으로 특허 요약 자동화, 주요 기술 도출, 특허 데이터 관리 툴의 개발 가능성을 PoC로 검증했습니다. 특허 문서 구조를 바탕으로 LangChain 체인을 설계하고, Hallucination 위험과 비용·속도 트레이드오프를 정량적으로 확인했습니다.

이 PoC는 이후 포스코퓨처엠 IP전략센터에서 LLM, RAG, Agent 시스템을 단독 구축하게 된 직접 계기가 되었습니다.

## Technical Stack

| Area | Tools |
|---|---|
| LLM / Agent | LangChain, DeepAgents, Supervisor-Subagent, ReAct Agent, GraphRAG, RAG, GPT-4, ChatGPT |
| Retrieval / NLP | BGE-M3, Vector DB, Korean NLP, NER, ELECTRA + CRF, Multi-Label Classification, STS-B |
| Backend / Frontend | FastAPI, Next.js 16, Streamlit, HTML mail automation |
| Data / ML | Python, PyTorch, TensorFlow, scikit-learn, pandas, NumPy, TabNet, Facebook Prophet |
| Operations | Slack Bot, GCP TPU, prompt asset management, internal AI education |
| Domains | Patent analysis, IP strategy, battery materials, cathode/anode materials, LMR, graphite, XAI |

## Selected Public Repositories

- [academic-search](https://github.com/jw0831/academic-search) - Academic paper search skill for scholarly APIs and citation-oriented workflows.
- [patent-search](https://github.com/jw0831/patent-search) - Patent search skill for IP workflows, CPC/IPC search, and battery/chemistry research.
- [pytorch-bert-crf-ner](https://github.com/jw0831/pytorch-bert-crf-ner) - Korean NER tagger using BERT + CRF.
- [GraphRAG_fastcampus](https://github.com/jw0831/GraphRAG_fastcampus) - Practice code around AI agents, RAG, FastAPI, and GraphRAG.
- [pansori-tedxkr-corpus](https://github.com/jw0831/pansori-tedxkr-corpus) - Korean ASR corpus reference with TEDxKR audio-transcript pairs.
- [hands-on-time-series-analylsis-python](https://github.com/jw0831/hands-on-time-series-analylsis-python) - Time-series analysis study repository.

## What I Build

I build practical AI systems that turn domain-heavy documents and noisy information streams into searchable, explainable, and reusable workflows. My strongest interest is in AI Agent systems that combine retrieval, tools, structured reasoning, and real operational feedback.

## Contact

- LinkedIn: [jinwon0831kim](https://www.linkedin.com/in/jinwon0831kim/)
- GitHub: [jw0831](https://github.com/jw0831)
