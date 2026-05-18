<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/heodongun/heodongun/986b7f63d708f81d6f96d59283d0f6f6dce11851/assets/header-dark.svg">
  <img alt="Heo Dongun's GitHub Profile Header" src="https://raw.githubusercontent.com/heodongun/heodongun/986b7f63d708f81d6f96d59283d0f6f6dce11851/assets/header-light.svg">
</picture>

</div>

---

## About

필요하다면 무엇이든 합니다. 백엔드 개발을 중심으로 AI, 인프라, 자동화 등 다양한 영역을 넘나들며 문제를 해결합니다. 단순한 기능 구현을 넘어, 서비스의 지속 가능성과 사용자 경험을 고민하는 개발자가 되는 것을 목표로 합니다.

- 🎓 부산소프트웨어마이스터고등학교 수석입학 (2024.03.10)
- 💼 플레이버니즈 AI/서버 개발 인턴 (2025.07 ~ 2025.08)
- 💼 온더룩 개발팀 인턴 근무 (2026.01 ~ 2026.03)
- 📞 010-5132-8318
- ✉️ heodongun08@gmail.com

---

## GitHub Stats

<div align="center">

<table>
  <tr>
    <td>
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=heodongun&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9">
        <img src="https://github-readme-stats.vercel.app/api?username=heodongun&show_icons=true&theme=default&hide_border=true&bg_color=ffffff&title_color=0969da&icon_color=0969da&text_color=1f2328" alt="GitHub stats">
      </picture>
    </td>
    <td>
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=heodongun&theme=github-dark-blue&hide_border=true&background=0d1117&ring=58a6ff&fire=f85149&currStreakLabel=c9d1d9&sideLabels=c9d1d9&dates=8b949e">
        <img src="https://streak-stats.demolab.com?user=heodongun&theme=default&hide_border=true&background=ffffff&ring=0969da&fire=cf222e&currStreakLabel=1f2328&sideLabels=1f2328&dates=656d76" alt="GitHub streak">
      </picture>
    </td>
  </tr>
</table>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=heodongun&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=heodongun&layout=compact&theme=default&hide_border=true&bg_color=ffffff&title_color=0969da&text_color=1f2328" alt="Top languages">
</picture>

</div>

---

## Tech Stack

<div align="center">

**Languages**

![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)

**Frameworks**

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Ktor](https://img.shields.io/badge/Ktor-000000?style=flat-square&logo=ktor&logoColor=white)
![Express.js](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)

**Database & Infra**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**DevOps & Tools**

![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

</div>

---

## Projects

### Cotor
> 사이드 프로젝트를 혼자 운영하는 한계를 줄이기 위해 만든, 24시간 돌아가는 로컬 우선 AI 회사

개발, 테스트, 문서, 홍보, 유지보수처럼 계속 밀리는 일을 AI 직원들이 역할을 나눠 처리하고, 사용자는 방향과 기준을 정하는 데 집중할 수 있게 만든 시스템입니다. 비용 문제는 Gemma 4 같은 로컬 모델과 무료/저비용 모델을 우선 쓰는 방식으로 해결했습니다.

- **핵심 기술:** Kotlin, Coroutines, DAG 실행 엔진, Ktor, SwiftUI, Git worktree/branch isolation
- **GitHub:** [bssm-oss/cotor](https://github.com/bssm-oss/cotor)

### Allergic
> 음식 사진 한 장으로 알레르기 성분을 확인해주는 서비스

사용자가 음식 사진을 찍으면 ChatGPT API와 연동하여 음식 성분을 분석하고, 사용자가 등록한 알레르기 정보와 비교해 알레르기 유발 성분 포함 여부를 판단하고 경고해주는 앱입니다.

- **핵심 기술:** Node.js, Express.js, MongoDB, ChatGPT API, YoloV5, Google Cloud Storage
- **성과:** 교내 AI 공모전 2등🥈, AI KOREA 2024 학교 대표 프로젝트, 행복한교육 겨울호 게재
- **GitHub:** [allergicyujin](https://github.com/allergicyujin)

---

## Awards

**2025**
- 🥉 소마고 연합 해커톤 장려상 (2025.11.06)
- 🏆 부경대 우수토론자
- 🥉 조정 3등
- 🥉 산호세 주립대학교 AI캠프 장려상 (2025.02.11)

**2024**
- 🥉 교내 네트워크 대회 장려상 (2024.12.24)
- 🥈 교내 디자인 대회 2등 (2024.12.10)
- 🥉 영어 말하기 대회 장려상
- 🥉 독후감 대회 장려상
- 🥉 PKNU AISW 부우산 지역문제대회 장려상 (2024.11.27)
- 🥈 2024 교내 AI SW 공모전 2등 (2024.09.05)
- 🥇 부산소프트웨어마이스터고등학교 수석입학 (2024.03.10)

---

## Certifications

- TOPCIT 3수준 (2024.11.11)
- SQLD (2025.06.27)
- 정보처리산업기사 (2025.07.16)

---

## Activities

- AI KOREA 2024 학교 대표 프로젝트 BEXCO 부스 운영 (2024.09.10 ~ 2024.09.12)
- 대한민국 SW 교육 페스티벌 학교 대표 부스 운영 (2024.11.03 ~ 2024.11.07)
- PKNU AISW 부우산 지역문제대회 부경대 부스 운영 (2024.11.27)
- 교내 지식 봉사 동아리 플로이테크코스 팀장 (2024.12.19 ~)
- 교내 기술 컨퍼런스 부마콘 2025 주최 및 연사 — "자기의심을 극복하는 방법" (2025.01.08)
- Elice AI Spark Camp 수료 (2025.02 ~ 2025.03)
- 부산소프트웨어마이스터고 학생회 마이스터부 차장 (2025.03.13 ~ 2025) → 부장 (2026)
- NDIE 비영리단체 지원 프로젝트 팀장 (2025.03.13 ~)
- 산호세 주립대학 프로젝트 팀FOCUS 팀장 (2025.05.01 ~ 2025.05.30)
- 비디아 학교 대표 전시 부스 운영 (2025.09.09)
- 지스타 학교 대표 전시 부스 운영 (2025.11.13 ~ 2025.11.16)
- 학교 공식 오픈소스 단체 [BSSM-OSS](https://github.com/bssm-oss) 운영 (2026.03.04 ~)

---

## Experience

- **플레이버니즈** AI/서버 개발 인턴 (2025.07 ~ 2025.08)
- **온더룩** 개발팀 인턴 근무 (2026.01 ~ 2026.03)

---

<div align="center">

📄 **[전체 포트폴리오 보기](https://mint-middle-1e5.notion.site/2b7655e8316980ad9422d96a6f3947de)**

</div>
