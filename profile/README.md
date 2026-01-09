# 🎬 Review Tag Project

> **"콘텐츠를 즐기는 새로운 방법, Review Tag"**  
> 영화/TV 프로그램 정보를 기반으로 리뷰, 퀴즈, 커뮤니티, 그리고 나만의 프로필 꾸미기까지 결합된 **올인원 게이미피케이션 플랫폼**입니다.

---

## 📋 Project Overview

**Review Tag**는 단순한 정보 전달을 넘어, 사용자가 콘텐츠를 능동적으로 소비하고 재생산하는 선순환 구조를 지향합니다.
TMDB API를 활용한 방대한 콘텐츠 정보 위에 **사용자 제작 퀴즈**, **포인트 경제 시스템**, **아이템 상점** 등의 요소를 도입하여 사용자가 머물고 싶은 즐거운 커뮤니티 환경을 구축했습니다.

---

## 🛠️ Tech Stack

### Backend
![Java](https://img.shields.io/badge/Java_21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot_3.5-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=spring-security&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle_DB-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![MyBatis](https://img.shields.io/badge/MyBatis-000000?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHBhdGggZD0iTTEyIDJMMTMuMDkgOC4yNkwyMSA5TDEzLjA5IDE1Ljc0TDEyIDIyTDEwLjkxIDE1Ljc0TDMgOUwxMC45MSA4LjI2TDEyIDJaIiBmaWxsPSIjMDAwMDAwIi8+Cjwvc3ZnPgo=&logoColor=white)

### Frontend
![React](https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Jotai](https://img.shields.io/badge/Jotai-State_Management-000000?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSJjdXJyZW50Q29sb3IiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIj48cGF0aCBkPSJNMi41IDEyaDNtMi41LTMuNWwxLjUgM2wzLTEwbDMgMTBsMS41LTNtMi41IDMuNWgzIiAvPjwvc3ZnPg==&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap_5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

### Infrastructure & Tools
![JWT](https://img.shields.io/badge/JWT-Auth-000000?style=for-the-badge&logo=json-web-tokens&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

## 🚀 Key Features

### 🎬 1. TMDB 기반 콘텐츠 시스템
- **데이터 연동:** TMDB API를 활용하여 영화/TV 프로그램의 상세 정보, 캐스팅, 예고편 데이터 실시간 제공
- **검색 및 랭킹:** 제목 기반 검색 및 평점/인기도 기반의 콘텐츠 랭킹 시스템
- **시청목록(Watchlist):** 관심 콘텐츠 저장 및 관리

### 🎮 2. 고도화된 퀴즈 게이미피케이션
- **하트(Heart) 시스템:** 퀴즈 참여를 위한 피로도 시스템 구현 (자동 리필 및 상점 구매)
- **사용자 제작 퀴즈:** 사용자가 직접 영화별 퀴즈를 출제하고 공유하는 참여형 콘텐츠
- **랜덤 출제 로직:** 이미 푼 문제를 제외하고 랜덤하게 5문제를 출제하는 알고리즘 적용

### 💰 3. 포인트 경제 및 상점 시스템
- **포인트 획득:** 퀴즈 정답, 리뷰 작성, 일일 퀘스트, 출석 체크, 룰렛 게임을 통한 보상 획득
- **아이템 상점:** 획득한 포인트로 **프로필 아이콘** 구매 및 선물하기 기능
- **인벤토리 & 커스텀:** 구매한 아이콘을 장착하여 나만의 프로필을 꾸미는 기능 (랜덤 뽑기 포함)

### 🛡️ 4. 보안 및 커뮤니티 관리
- **JWT 인증:** Access/Refresh Token 기반의 안전한 로그인 및 자동 갱신 처리
- **신고 시스템:** 부적절한 리뷰, 게시글, 퀴즈에 대한 신고 접수 및 관리자 제재 기능
- **관리자 대시보드:** 회원 현황, 신고 내역 처리, 콘텐츠 관리 기능 제공

---
---

## ⭐️ My Tech Contributions

**Role: Backend Core Developer**
<br>
사용자 참여를 유도하는 **게이미피케이션 핵심 로직**과, 플랫폼의 안정적인 운영을 위한 **관리자 및 신고 시스템**을 전담하여 구현했습니다.

### 🎮 1. 고도화된 퀴즈 게이미피케이션 로직
- **구현 내용:** 사용자가 지루함을 느끼지 않도록 '매번 새로운 문제'를 제공하고, 피로도(하트) 시스템을 관리하는 로직 구현.
- **기술적 해결:**
    - **중복 방지 알고리즘:** MyBatis 동적 쿼리를 활용하여 '사용자가 이미 맞춘 문제'를 제외하고, 해당 콘텐츠의 문제 풀(Pool)에서 **랜덤으로 5문제를 추출**하는 효율적인 조회 로직을 구현했습니다.
    - **재화(하트) 관리:** 퀴즈 참여 시 하트 차감 및 시간 경과에 따른 자동 리필 로직을 스케줄러와 연동하여 안정적으로 처리했습니다.

### 🚨 2. 통합 신고 및 제재 시스템 설계
- **구현 내용:** 리뷰, 게시글, 퀴즈 등 다양한 유형의 콘텐츠에서 발생하는 신고를 통합적으로 처리하는 프로세스 구축.
- **기술적 해결:**
    - **다형성 고려한 DB 설계:** 신고 대상이 '리뷰', '게시글', '퀴즈' 등 다양함을 고려하여, 확장성 있는 신고 테이블 구조를 설계했습니다.
    - **제재 로직 자동화:** 관리자가 신고를 승인할 경우, 대상 유저의 등급 하락이나 활동 정지(Ban)가 즉시 적용되도록 **트랜잭션 기반의 제재 처리 로직**을 구현했습니다.

### 📊 3. 관리자(Admin) 대시보드 API
- **구현 내용:** 서비스 현황을 한눈에 파악하고 운영 관리를 할 수 있는 백오피스 기능 구현.
- **기술적 해결:**
    - **효율적인 데이터 집계:** 전체 회원 현황, 미처리 신고 내역 등을 빠르게 조회할 수 있도록 집계 쿼리를 최적화했습니다.
    - **운영 워크플로우:** '신고 접수 → 검토 → 처리(기각/승인)'로 이어지는 관리자 작업 상태(Status) 흐름을 명확하게 API로 정의하여 프론트엔드 연동 효율을 높였습니다.

---

## 🏗️ Architecture & Repositories

이 프로젝트는 유지보수성과 확장성을 위해 **Frontend(React)**와 **Backend(Spring Boot)**가 분리된 아키텍처로 설계되었습니다.
각 파트의 상세 코드는 아래 레포지토리에서 확인하실 수 있습니다.

| 파트 (Part) | 기술 스택 (Tech Stack) | 저장소 링크 (Repository) |
| :--- | :--- | :--- |
| **🖥️ Frontend** | React 19, Jotai, Vite | [👉 ReviewTag-Frontend 바로가기](https://github.com/ReviewTag-Project/ReviewTag-Frontend) |
| **⚙️ Backend** | Spring Boot 3.5, Oracle, MyBatis | [👉 ReviewTag-Backend 바로가기](https://github.com/ReviewTag-Project/ReviewTag-Backend) |

---

## 📚 Documentation

프로젝트의 상세한 기술 문서와 API 명세서는 각 레포지토리의 README 파일에서 확인하실 수 있습니다.

- [Organization 페이지](https://github.com/ReviewTag-Project)
- [Backend Repository](https://github.com/ReviewTag-Project/ReviewTag-Backend)
- [Frontend Repository](https://github.com/ReviewTag-Project/ReviewTag-Frontend)

---

<div align="center">

**Review Tag Project** - Gamified Content Community Platform

</div>
