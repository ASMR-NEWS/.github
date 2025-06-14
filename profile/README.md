<div id="top">

<!-- HEADER STYLE: CLASSIC -->
<div align="center">


# A.S.M.R (Article Sentiment Map Research)

<em style="font-size: 2em;">AI 기반 뉴스 분석 및 지리정보 시각화 플랫폼</em>

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

ASMR (Article Sentiment Map Research)는 뉴스 검색, 감성 분석, 요약 및 위치 기반 시각화를 통해 사용자가 지역 기반의 뉴스 정보를 풍부하게 이해할 수 있도록 돕는 통합 플랫폼입니다.
기존의 뉴스 서비스는 지역 기반, 감정 기반, 요약 기반 탐색 기능이 부족하여 사용자가 원하는 정보에 빠르게 접근하기 어렵습니다. ASMR은 이러한 문제를 해결하고자 다음과 같은 목표를 갖고 설계되었습니다:
- 뉴스에서 지리적 맥락을 자동으로 추출하고 시각화
- 감정 분석을 통해 다양한 시각 제공 (긍정/중립/부정)
- 뉴스 요약을 통해 핵심 정보만 빠르게 파악
- 지역별 뉴스 흐름과 여론 동향을 한눈에 파악
- 경로 탐색 기능을 통해 뉴스 속 사건/장소를 실생활에 연결

ASMR은 뉴스의 요약, 감정 분석, 지명 인식을 자동으로 수행하여 사용자가 뉴스의 핵심 내용과 여론 흐름을 직관적으로 이해할 수 있도록 돕습니다. 지도 기반 시각화와 길찾기 기능을 통해 뉴스에 대한 공간적 맥락까지 제공하며, 이는 정보의 몰입도와 이해도를 높이고, 지역 기반 행동 유도까지 가능하게 합니다. 나아가 트렌드 분석, 신뢰도 평가 등 다양한 지능형 서비스로의 확장이 기대됩니다.


## Key Features

- 🔍 **뉴스 수집**: Naver API 기반 뉴스 크롤링
- 🧠 **AI 요약 및 감정 분석**: GPT-3.5를 활용한 자연어 요약 및 감정 분류
- 📍 **위치 인식 및 시각화**: 뉴스 본문에서 장소명 추출 → 지도에 시각화 (Kakao & Naver Map API)
- 📺 **Youtube 영상 제공**: 사용자가 검색한 지역 및 키워드와 관련된 영상을 자동으로 제공 
- 🌦️ **날씨 위젯**: OpenWeatherMap API를 활용한 검색 지역 날씨 정보 제공
- 💬 **UI/UX**: React 기반 단일 페이지 애플리케이션(SPA)


---

## Features

| Type      | Feature           | Description                      |
| --------- | ----------------- | -------------------------------- |
| 💡 AI 분석  | 뉴스 요약 및 감정 분석     | OpenAI API를 활용한 GPT 기반 요약/감정 분류  |
| 🗺️ 지도 기능 | 위치 자동 추출 및 지도 시각화 | 뉴스 본문에서 지명을 추출해 Kakao 지도에 표시     |
| 🔎 검색     | 키워드 기반 뉴스 검색      | Naver API를 활용한 실시간 뉴스 크롤링        |
| 🔌 아키텍처   | Front-Back 분리형 구조 | Flask REST API + React SPA 구성    |


---


