<div id="top">

<!-- HEADER STYLE: CLASSIC -->
<div align="center">


# A.S.M.R
(Article Sentiment Map Research)

<em>AI 기반 뉴스 분석 및 지리정보 시각화 플랫폼</em>

<!-- BADGES -->
<img src="https://img.shields.io/github/last-commit/leegitae00/Search_FE?style=flat&logo=git&logoColor=white&color=0080ff" alt="last-commit">
<img src="https://img.shields.io/github/languages/count/leegitae00/Search_FE?style=flat&color=0080ff" alt="repo-language-count">

<em>Built with the tools and technologies:</em>

<img src="https://img.shields.io/badge/Flask-000000.svg?style=flat&logo=Flask&logoColor=white" alt="Flask">
<img src="https://img.shields.io/badge/Python-3776AB.svg?style=flat&logo=Python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/OpenAI-412991.svg?style=flat&logo=OpenAI&logoColor=white" alt="OpenAI">
<img src="https://img.shields.io/badge/JSON-000000.svg?style=flat&logo=JSON&logoColor=white" alt="JSON">
<img src="https://img.shields.io/badge/npm-CB3837.svg?style=flat&logo=npm&logoColor=white" alt="npm">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=flat&logo=JavaScript&logoColor=black" alt="JavaScript">
<img src="https://img.shields.io/badge/React-61DAFB.svg?style=flat&logo=React&logoColor=black" alt="React">
<img src="https://img.shields.io/badge/Axios-5A29E4.svg?style=flat&logo=Axios&logoColor=white" alt="Axios">
<img src="https://img.shields.io/badge/Chart.js-FF6384.svg?style=flat&logo=chartdotjs&logoColor=white" alt="Chart.js">
<img src="https://img.shields.io/badge/pandas-150458.svg?style=flat&logo=pandas&logoColor=white" alt="pandas">
<img src="https://img.shields.io/badge/NumPy-013243.svg?style=flat&logo=NumPy&logoColor=white" alt="NumPy">
<img src="https://img.shields.io/badge/Gunicorn-499848.svg?style=flat&logo=Gunicorn&logoColor=white" alt="Gunicorn">
<img src="https://img.shields.io/badge/Markdown-000000.svg?style=flat&logo=Markdown&logoColor=white" alt="Markdown">

</div>
<br>

---

## Overview

**ASMR (AI-based Sentiment-aware Map & Retrieval)**는 뉴스 검색, 감성 분석, 요약 및 위치 기반 시각화를 통해 사용자가 지역 기반의 뉴스 정보를 풍부하게 이해할 수 있도록 돕는 통합 플랫폼입니다.

**Key Features**

- 🔍 **뉴스 수집**: Naver API 기반 뉴스 크롤링
- 🧠 **AI 요약 및 감정 분석**: GPT-3.5를 활용한 자연어 요약 및 감정 분류
- 📍 **위치 인식 및 시각화**: 뉴스 본문에서 장소명 추출 → 지도에 시각화 (Kakao Map)
- 🚉 **길찾기 기능**: 두 지점 간의 대중교통 경로 탐색
- 📊 **시각화**: Chart.js, FusionCharts를 활용한 인터랙티브 시각화
- 💬 **UI/UX**: React 기반 단일 페이지 애플리케이션(SPA)


---

## Features

|      | Component       | Details                                                                                     |
| :--- | :-------------- | :------------------------------------------------------------------------------------------ |
| ⚙️  | **Architecture**  | <ul><li>RESTful API built with Flask</li><li>Separation of concerns between routes and services</li><li>Environment-based configuration management</li></ul> |
| 🔩 | **Code Quality**  | <ul><li>Consistent code style following PEP 8</li><li>Modular structure with dedicated directories for routes, services, and utils</li><li>Use of environment variables for sensitive info</li></ul> |
| 📄 | **Documentation** | <ul><li>Basic README with setup instructions</li><li>API endpoints documented via docstrings</li><li>Minimal external docs; potential for Swagger/OpenAPI integration</li></ul> |
| 🔌 | **Integrations**  | <ul><li>OpenAI API for AI functionalities</li><li>Requests library for HTTP calls</li><li>Flask-CORS for cross-origin support</li></ul> |
| 🧩 | **Modularity**    | <ul><li>Separate modules for API routes, services, and environment config</li><li>Reusable utility functions</li></ul> |
| 🧪 | **Testing**       | <ul><li>Limited testing; potential for unit tests using pytest</li><li>Test coverage not explicitly shown in codebase</li></ul> |
| ⚡️  | **Performance**   | <ul><li>Basic Flask server; no explicit performance optimizations</li><li>Potential bottlenecks in external API calls</li></ul> |
| 🛡️ | **Security**      | <ul><li>Uses environment variables for sensitive data</li><li>Basic CORS setup; no advanced security measures observed</li></ul> |
| 📦 | **Dependencies**  | <ul><li>Managed via `requirements.txt`</li><li>Key dependencies include `flask`, `requests`, `python-dotenv`, `openai`, `flask-cors`</li></ul> |

---


