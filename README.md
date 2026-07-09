# 👋 안녕하세요, 김종윤입니다

![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&duration=3000&pause=1000&color=FE428E&center=true&vCenter=true&width=560&lines=System+Ops+%26+QA+%E2%86%92+Dev;%EA%B5%AC%EC%A1%B0%EC%A0%81%EC%9C%BC%EB%A1%9C+%EB%AC%B8%EC%A0%9C%EB%A5%BC+%ED%92%80%EC%96%B4%EA%B0%80%EB%8A%94+%EC%82%AC%EB%9E%8C)

시스템 운영과 QA를 하면서 "왜 이 문제가 반복되는가"를 구조적으로 파고드는 걸 좋아하다 보니, 자연스럽게 직접 도구를 만들고 개발 영역으로 넘어오게 됐습니다. 반복되는 QA 업무를 서버 없는 로컬 툴로 먼저 자동화해보고(`QA_tool`), 이를 FastAPI + React 기반의 정식 웹 서비스(`QASingle`)로 발전시키는 식으로, 문제를 직접 코드로 풀어내며 확장하는 과정을 즐깁니다. 최근에는 Java/Spring Boot와 Python/FastAPI를 함께 쓰는 멀티 백엔드 구조(`Quantum Studio`)까지 다루며 백엔드·풀스택 영역을 넓히는 중입니다.

- 📧 **연락처**: oomg4297@gmail.com
- 🔗 **GitHub**: [KIMjongYoun1](https://github.com/KIMjongYoun1)

---

## 🚀 프로젝트

### [Quantum Studio](https://github.com/KIMjongYoun1/3D_Model)
비정형 데이터(JSON, 로그, PDF/Excel)를 AI로 분석해 3D 노드·관계로 시각화하는 풀스택 플랫폼.
- Next.js 14 + Three.js(React Three Fiber) 프론트, Java 21/Spring Boot 3.2 + Python/FastAPI로 역할을 분리한 멀티 백엔드(인증·결제 / 회원·매출 관리 / AI 매핑)
- JWT + OAuth2(네이버) 인증, 플랜/약관 관리, 결제 시뮬레이션, 매출 대시보드(기간별 차트, 전기 대비 비교)
- Ollama(로컬) → Gemini(클라우드) 폴백 구조의 AI 데이터 매핑, Open Redirect 방지 등 보안 처리

### [Single QA Tools (QASingle)](https://github.com/KIMjongYoun1/QASingle)
QA 업무 전체(케이스 설계 → 자동 실행 → 결과 문서화 → 배포 점검)를 하나의 웹 서비스로 통합한 도구.
- FastAPI + React/TypeScript + PostgreSQL, 테스트 스위트/플로우 단위 관리, Assertion 기반 자동 Pass/Fail 판정
- 실행 결과는 불변(immutable) 저장으로 감사 가능, Discord/Slack 알림 연동(엑셀 첨부 포함)
- 결과서에 LLM 분석 기능(Ollama 로컬 모델 / Claude API 중 실시간 선택) 추가

### [QA_tool](https://github.com/KIMjongYoun1/QA_tool)
서버·DB 없이 HTML + Python 파일만으로 동작하는 경량 QA 관리 툴. `QASingle`의 프로토타입 성격으로, 데이터는 브라우저 localStorage와 엑셀로만 관리하고 배포 히스토리는 Python 스크립트로 집계.

### [PokeAPI](https://github.com/KIMjongYoun1/PokeAPI)
Spring Boot + React + PostgreSQL로 만든 포켓몬 정보 관리 및 이상형 월드컵 서비스. REST API 15개, React 컴포넌트 25개로 검색·진화체인·토너먼트·통계 기능 구현.

### [Annual_leave_management](https://github.com/KIMjongYoun1/Annual_leave_management)
TypeScript 기반 연차 관리 시스템.

---

## 🛠 기술 스택

**Backend**: Java · Spring Boot · Python · FastAPI · Node.js
**Frontend**: TypeScript · React · Next.js · Three.js · Tailwind CSS
**Database/Infra**: PostgreSQL · Alembic

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=KIMjongYoun1&show_icons=true&theme=radical&hide_border=true" alt="GitHub Stats" />
</p>
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=KIMjongYoun1&layout=compact&theme=radical&hide_border=true" alt="Top Languages" />
</p>
<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=KIMjongYoun1&theme=radical&hide_border=true" alt="GitHub Streak" />
</p>
