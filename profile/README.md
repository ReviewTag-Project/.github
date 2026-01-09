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

### 🎮 1. 고도화된 퀴즈 게이미피케이션 로직 (Full-Stack)
- **구현 내용:** 사용자가 지루함을 느끼지 않도록 '매번 새로운 문제'를 제공하고, 피로도(하트) 시스템을 관리하는 로직 구현.
- **기술적 해결:**
    - **Frontend (Interactive UX & State Management):**
        - **전역 상태 동기화:** `Jotai`를 활용하여 재화(하트)와 로그인 상태를 전역으로 관리했습니다. 퀴즈 제출 시 API 응답을 기다리지 않고 UI 상에서 하트를 즉시 차감하는 **Optimistic UI** 패턴을 일부 적용하여 반응 속도를 높였습니다.
        - **동적 모달 시스템:** `SweetAlert2`를 `React` 컴포넌트와 결합하여, 단순 알림을 넘어 **신고 폼(Form)이 포함된 인터랙티브 모달**을 구현했습니다. 퀴즈 유형(OX/4지선다)에 따라 입력 필드가 동적으로 변경되는 유연한 UI를 설계했습니다.
        - **접근성 및 예외 처리:** 키보드 이벤트(ESC) 바인딩을 통한 모달 제어와, 데이터 로딩 중 중복 클릭 방지(Loading State) 처리를 통해 안정적인 사용자 경험을 제공했습니다.
    - **Backend (구현 방식):**
        - **중복 방지 동적 쿼리:** MyBatis의 `<if>`와 서브쿼리를 활용한 동적 쿼리로 API를 구현했습니다. 사용자가 문제를 요청할 때, `QUIZ_LOG` 테이블에서 해당 유저가 이미 맞춘 문제 번호(`quiz_no`) 리스트를 조회하여, 이를 `NOT IN` 조건으로 제외한 새로운 문제만 선택하도록 쿼리를 동적으로 생성합니다.
        - **랜덤 문제 추출:** 중복이 제거된 문제 풀(Pool) 내에서 효율적인 랜덤 추출을 위해 데이터베이스가 제공하는 네이티브 함수(`DBMS_RANDOM.VALUE`)를 사용하고, `LIMIT 5`를 통해 요청된 개수만큼만 반환하여 DB 부하를 최소화했습니다.
        - **재화(하트) 관리 최적화 (Lazy Refill 전략):**
            - **문제점:** 전 유저를 대상으로 매일 정해진 시간에 스케줄러(Batch)를 돌릴 경우, 유저 수 증가 시 **DB 부하가 집중(Spike)되어 시스템이 다운될 위험**이 있음을 인지했습니다.
            - **해결:** 사용자가 퀴즈 서비스에 **접근하는 시점**에 마지막 충전 날짜를 비교하여 하트를 충전하는 **On-Demand(Lazy) 방식**으로 변경했습니다. 이를 통해 DB 트래픽을 하루 전체로 자연스럽게 분산시켰으며, `@Transactional`을 통해 동시성 이슈를 방지했습니다.

### 🏆 2. 다차원 실시간 랭킹 대시보드 (Full-Stack)
- **구현 내용:** 퀴즈왕, 리뷰왕, 인기 콘텐츠, 실시간 퀴즈 현황 등 4가지 지표를 시각화한 종합 대시보드 구축.
- **기술적 해결:**
    - **Frontend (성능 최적화):**
        - **병렬 데이터 처리:** `Promise.all`을 활용하여 4개의 독립적인 랭킹 API(퀴즈, 리뷰, 핫컨텐츠, 실시간)를 **병렬로 호출**함으로써, 순차 호출 대비 로딩 속도를 대폭 단축했습니다.
        - **실시간 데이터 동기화:** `setInterval`을 활용한 **폴링(Polling)** 방식을 적용하여 30초 주기로 데이터를 자동 갱신, 사용자가 새로고침 없이도 최신 랭킹 변동을 확인할 수 있도록 구현했습니다.
    - **Backend (Advanced SQL):**
        - **윈도우 함수 활용 (Deduplication):** 실시간 퀴즈 피드 구현 시, 특정 콘텐츠의 퀴즈가 도배되는 것을 방지하기 위해 `row_number() over(partition by c.contents_id order by q.quiz_created_at desc) as rn` 윈도우 함수를 사용하여 **콘텐츠별 최신 퀴즈를 1건씩만 효율적으로 추출**했습니다.
        - **DB 레벨의 집계 최적화:** 애플리케이션 레벨에서 필터링하지 않고, Oracle의 `TRUNC(SYSDATE, 'MM')` 및 `ADD_MONTHS` 함수를 활용하여 **'월간/최근 30일'** 데이터를 DB에서 미리 집계하여 네트워크 전송량을 최소화했습니다.
        - **효율적인 페이징:** `ROWNUM`을 활용한 인라인 뷰(Inline View) 방식으로 Top-N 쿼리를 작성하여 불필요한 전체 데이터 스캔을 방지했습니다.

### 🚨 3. 통합 신고 및 제재 시스템 (Full-Stack)
- **구현 내용:** 리뷰, 게시글, 퀴즈 등 다양한 콘텐츠의 신고를 통합 관리하고, 즉각적인 제재(Blind/Ban) 처리가 가능한 운영 시스템 구축.
- **기술적 해결:**
    - **Frontend (Admin UX Optimization):**
        - **무한 스크롤 & 스로틀링:** 신고 내역 리스트 렌더링 시 `Scroll Event`와 `Lodash Throttle(500ms)`을 결합한 커스텀 무한 스크롤을 구현하여, 대량의 데이터 조회 시 브라우저 성능 저하를 막았습니다.
        - **Lazy Loading:** 신고 상세 사유(기타 내용)는 사용자가 요청할 때만 비동기로 호출하는 **Lazy Loading** 패턴을 적용하여 초기 로딩 속도를 최적화했습니다.
    - **Backend (Transaction & Data Consistency):**
        - **원자성(Atomicity) 보장:** 신고 접수 시 `Report` 테이블 적재와 `Content` 테이블의 '신고 누적 횟수(`report_count`)' 증가가 동시에 이루어져야 합니다. 이를 `@Transactional`로 묶어 하나라도 실패 시 전체 롤백되도록 하여 **데이터 정합성**을 보장했습니다.
        - **중복 신고 방지 로직:** `checkHistory` 메서드를 통해 동일 사용자의 중복 신고를 DB 레벨에서 사전에 차단하여 악의적인 신고 어뷰징을 방지했습니다.
    

### 📊 4. 관리자(Admin) 대시보드 및 권한 관리 (Full-Stack)
- **구현 내용:** 회원 등급 관리, 강제 추방, 악성 콘텐츠 관리를 위한 백오피스 기능 전반 구현.
- **기술적 해결:**
    - **Frontend (Efficient Data Fetching):**
        - **복합 필터링 & SPA 구조:** 아이디/닉네임/등급 등 다양한 조건의 검색을 지원하며, 탭(Tab) 전환 시 페이지 이동 없이 데이터를 교체하는 SPA 구조를 활용하여 관리 업무의 효율성을 높였습니다.
    - **Backend (Service Facade Pattern):**
        - **중앙 집중형 관리자 서비스:** `AdminService`를 별도로 두어 흩어져 있는 도메인(퀴즈, 게시글, 리뷰)의 통계 데이터를 집계하는 **Facade 역할**을 수행하게 했습니다.
        - **RBAC(Role-Based Access Control):** 모든 관리자 API의 진입점에서 `loginLevel`을 검사하여, URL 조작을 통한 비인가 사용자의 접근을 원천 차단하는 보안 로직을 공통화했습니다.
    
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
