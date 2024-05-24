###### noColored.md

<h1 align="center">NoColored</h1>
<img alt="게임 시작 화면" src="https://github.com/NoColored/.github/blob/main/profile/docs/images/main/view/landing_fullScreen.png" width="100%" height="100%"/>

### 🍀 Deploy URL
https://nocolored.world

----- 

### 📁 Repository
- [BACKEND REPOSITORY](https://github.com/NoColored/NoColored-fe)
- [FRONTEND REPOSITORY](https://github.com/NoColored/NoColored-be)


-----

## 목차
- [Member](#-member)
- [Specification](#-specification)
- [Introduction](#-introduction)
- [Service Layout](#-Service-Layout)
- [개발 환경](#-개발-환경)
- [개발 기간 및 작업 관리](#-개발-기간-및-작업-관리)


-----

### 🧑‍🤝‍🧑 Member
|            👑[이담비](https://github.com/damdam6)             |           🍪[김세진](https://github.com/nijesmik)            |             🎰[박은수](https://github.com/Gardener-soul)             |                            🏰[손의성](https://github.com/gabalja)                             |            💟[전민정](https://github.com/dolmeengii)             |                           🚗[차우열](https://github.com/dtdtdz)                           |
|:----------------------------------------------------------:|:---------------------------------------------------------:|:-----------------------------------------------------------------:|:------------------------------------------------------------------------------------------:|:-------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| <img alt="이담비" src="https://github.com/damdam6.png"/> | <img alt="김세진" src="https://github.com/celin.png" /> | <img alt="gardener" src="https://github.com/gardener.png" /> | <img alt="gabalja" src="https://github.com/gabalja.png" width="230px" height="full" > | <img alt="oree" src="https://github.com/oree_egg.png" /> | <img alt="dtdtdz" src="https://github.com/dtdtdz.png" width="230" height="100%"/> |

-----

### 📝 Specification

- Notion : https://rb.gy/l1mz73
 : 요구사항 정의서 : https://t.ly/K1OZe
 : 기능명세서 (FE) : https://t.ly/7qerL
 : 기능명세서 (BE) : https://t.ly/bnTDN

- Figma : https://t.ly/P3fog

**시스템 아키텍쳐**
 <img alt="아키텍쳐" src="https://github.com/NoColored/.github/blob/main/profile/docs/images/main/view/architecture.png" />

-----

### 📢 Introduction

#### main-service
- **숨바꼭질 대전 웹 게임**
- NoColored는 2~4인 경쟁 기반 2D 캐쥬얼 게임입니다.
- NPC 사이 숨은 플레이어를 찾아 점수를 획득하는 방식의 게임입니다.
- 경쟁전을 통해 유사한 성적의 플레이어들과 대전을 펼칠 수 있습니다.
- 비공개/공개방을 생성하여 친선전 플레이가 가능합니다.

#### sub-service

- 게임의 진행상황을 통해 스킨, 칭호, 업적 보상을 얻을 수 있습니다.
- 전체 플레이어의 랭킹을 제공하여 자신의 티어와 점수를 확인할 수 있습니다.

---
### ✨ Service Layout

|                                     메인 페이지                                      |                                     컬렉션(스킨,칭호,업적)                                      |
|:-------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| <img alt="메인" src="https://github.com/NoColored/.github/blob/main/profile/docs/images/main/view/home.gif" width="100%" height="100%" > | <img alt="컬렉션" src="https://github.com/NoColored/.github/blob/main/profile/docs/images/main/view/collection.gif" width="100%" height="100%" > |

|                                      친선전 로비                                       |                                      친선전 대기실                                      |
|:---------------------------------------------------------------------------------:|:---------------------------------------------------------------------------------:|
| <img alt="로비" src="https://github.com/NoColored/.github/blob/main/profile/docs/images/main/view/finder.gif" width="100%" height="100%" > | <img alt="대기실" src="https://github.com/NoColored/.github/blob/main/profile/docs/images/main/view/foody.gif" width="100%" height="100%" > |

|                                      랭킹전 매칭/로딩                                      |                                       게임                                        |
|:-----------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------:|
| <img alt="매칭" src="https://github.com/NoColored/.github/blob/main/profile/docs/images/main/view/matching.gif" width="100%" height="100%" > | <img alt="게임" src="https://github.com/NoColored/.github/blob/main/profile/docs/images/main/view/game.gif" width="100%" height="100%" > |


---

### 💻 개발 환경

<div style="margin-bottom: 20px;">
    <h3>⚙ Management Tool</h3>
    <div style="display: flex; gap: 10px;">
<img src="https://img.shields.io/badge/Mattermost-003545.svg?style=for-the-badge&logo=Mattermost&logoColor=white" alt="Jira">
        <img src="https://img.shields.io/badge/jira-%230A0FFF.svg?style=for-the-badge&logo=jira&logoColor=white" alt="Jira">
        <img src="https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white" alt="Notion">
        <img src="https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white" alt="Figma">
        <img src="https://img.shields.io/badge/gitlab-FC6D26.svg?style=for-the-badge&logo=gitlab&logoColor=white" alt="GitLab">
    </div>
</div>

<div style="margin-bottom: 20px;">
    <h3>🎨 FrontEnd</h3>
    <div style="display: flex; gap: 10px;">
        <img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" alt="React">
        <img src="https://img.shields.io/badge/Vite-646CFF.svg?style=for-the-badge&logo=Vite&logoColor=%2361DAFB" alt="Vite">
        <img src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
        <img src="https://img.shields.io/badge/vanilla_extract_css-DB7093.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" alt="Vanilla"/>
        <img src="https://img.shields.io/badge/zustand-66595C.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" alt="Zustand"/>
        <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=Node.js&logoColor=white" alt="Node"/>
</div>

<div style="margin-bottom: 20px;">
    <h3>💻 BackEnd</h3>
    <div style="display: flex; gap: 10px;">
        <img src="https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white" alt="Spring">
        <img src="https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java">
        <img src="https://img.shields.io/badge/Gradle-02303A.svg?style=for-the-badge&logo=Gradle&logoColor=white" alt="Gradle">
        <img src="https://img.shields.io/badge/Web_Socket-010101.svg?style=for-the-badge&logo=Socket.io&logoColor=white" alt="Gradle">
        <img src="https://img.shields.io/badge/JPA-339933.svg?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java">
</div>

<div style="margin-bottom: 20px;">
    <h3>🔐 DB</h3>
    <div style="display: flex; gap: 10px;">
        <img src="https://img.shields.io/badge/Redis-DC382D.svg?style=for-the-badge&logo=Redis&logoColor=white" alt="AWS">
        <img src="https://img.shields.io/badge/MariaDB-003545.svg?style=for-the-badge&logo=MariaDB&logoColor=white" alt="Docker">
        <img src="https://img.shields.io/badge/MonGoDB-47A248.svg?style=for-the-badge&logo=MongoDB&logoColor=white" alt="Jenkins">
    </div>
</div>

<div style="margin-bottom: 20px;">
    <h3>🧲 Infra </h3>
    <div style="display: flex; gap: 10px;">
        <img src="https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white" alt="AWS">
        <img src="https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white" alt="Nginx">
        <img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
        <img src="https://img.shields.io/badge/Jenkins-D24939.svg?style=for-the-badge&logo=Jenkins&logoColor=white" alt="Jenkins">
    </div>
</div>

<div style="margin-bottom: 20px;">
    <h3>🛠 IDE</h3>
    <div style="display: flex; gap: 10px;">
        <img src="https://img.shields.io/badge/webstorm-143?style=for-the-badge&logo=webstorm&logoColor=white&color=black" alt="WebStorm">
        <img src="https://img.shields.io/badge/IntelliJIDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white" alt="IntelliJ IDEA">
    </div>
</div>

---

### 🕙 개발 기간 및 작업 관리

#### **개발 기간**
- 전체 개발 기간 : 2024-02-19 ~ 2024-04-04
- 기획 및 정책 설계 : 2024-02-19 ~ 2024-02-26
- ERD 작성 및 피그마 디자인 : 2024-02-27 ~ 2024-03-06
- UI 구현 (Front-End) : 2024-03-07 ~ 2024-03-31
- 기능 구현 (Back-End) : 2022-03-07 ~ 2024-03-31
- 산출물 관리 : 2024-04-01 ~ 2024-04-04


---

### 📌 More About TEAM-NoColored
- [브랜치/커밋 전략](https://github.com/NoColored/.github/wiki/%F0%9F%96%87%E2%80%8D-%EB%B8%8C%EB%9E%9C%EC%B9%98-%EC%A0%84%EB%9E%B5)
- [프로젝트 후기](https://github.com/NoColored/.github/wiki/%F0%9F%A5%B0-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%ED%9B%84%EA%B8%B0)


