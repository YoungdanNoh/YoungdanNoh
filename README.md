![header](https://capsule-render.vercel.app/api?type=waving&color=0:90EE90,100:90EE90&height=250&section=header&text=Hi%20there%20👋&fontSize=90&fontAlignY=40)


## About me
### 🎓 Major
- `2022.02 ~ 2024.02` 인하대학교 전기컴퓨터공학과, 석사 (Dept. of Electrical and Computer Engineering, Graduate School, Inha University, Incheon, Korea)
- `2018.03 ~ 2022.02` 인하공업전문대학 컴퓨터정보공학과, 학사 (Dept. of Computer Science, Inha Technical College, Incheon, Korea)

### 💼 Experiences
- `2024.07 ~` SSAFY 12기
- `2019.09 ~ 2022.02` 모죽 (교내 웹 전공 동아리)

### 🏆 Awards
- `2021.08` 전문기술인재장학생 선정 (주관처: 한국장학재단, 교육부)
- `2019.10` 하나장학생 선정 (주관처: 하나금융나눔재단)

<br>

## 팀 프로젝트
## 1. [🔗 Confy](https://github.com/Setto1044/Confy)
- WebRTC 기반 화상회의 & STT 데이터를 활용한 자동 회의 요약 서비스
- 인원: 총 6인

### ✨ **주요 기능**
- 🎞️ WebRTC를 기반으로 한 화상회의 기능을 지원
- 📊 화상회의에서 생성된 STT 데이터를 활용한 회의 자동 요약을 제공

### 🔧 **담당 역할**
- **화상회의 환경 구축** – OpenVidu3 기반으로 화상회의 기능 구현 및 AWS EC2에 배포
- **회의방 관리** – 각 회의방을 구분할 수 있도록 UUID를 활용한 시스템 개발
- **Azure를 활용한 STT 기능 개발** – 각 클라이언트별 음성 데이터를 실시간 텍스트로 변환
- **실시간 회의 요약 기능 개발** – 회의 중 생성된 STT 데이터를 Redis에 저장하고, 이 데이터를 실시간 회의 요약 기능에 활용
- **UX 개선** – 무한 스크롤을 적용하여 회의 리스트를 편리하게 조회 가능하도록 구현

## 2. [🔗 PaletteMe](https://github.com/yooniqlo-kim/PaletteMe)
- hadoop, Spark, Airflow를 활용한 빅데이터 수집으로 제공하는 미술 감상 서비스
- 인원: 총 6인

### ✨ **주요 기능**
- 🌐 hadoop, Spark, Airflow로 세계 주요 5개의 미술관 데이터 수집
- 🔍 elasticsearch, Logstash, Kibana를 활용한 검색 기능 제공
- 🎨 사용자 맞춤 작품 추천 및 감상문 작성 기능

### 🔧 **담당 역할**
- **검색 기능 최적화** – 기존 MySQL을 활용한 검색을 elasticsearch, Logstash, Kibana를 도입하여 85%의 성능 개선
- **배포** - Docker compose로 AWS EC2에 프론트엔드와 백엔드를 배포
- **아키텍처 설계** - 전체 프로젝트 구조 설계
- **DB 설계** - 프로젝트에서 사용할 테이블 설계
- **API 구현** - 마이뮤지업 탭의 캘린더 및 조회 기능 API 구현

## 3. [🔗 Spico](https://github.com/YoungdanNoh/Spico)
- 안드로이드 앱을 통한 AI 기반 발표 코칭 서비스
- 인원: 총 6인

### ✨ **주요 기능**
- 🗣️ 코칭 모드 – 실시간 STT 및 성량·속도 분석 피드백 제공 → 연습 종료 후 휴지 횟수, 성량, 속도에 대한 리포트 제공
- 🎯 파이널 모드 – 사용자가 설정한 시간만큼 연습 후, GPT API로 질문을 생성하고 사용자의 답변(STT 기록 포함)을 기록. 그 후 발표 내용을 분석하여 발음, 휴지, 성량, 속도, 대본 일치도에 대한 점수와 피드백 제공
- 🌍 랜덤 스피치 – 주제를 선택하면 뉴스 기사를 제공하고, 발표 후 GPT API로 질문을 생성. 그 후 사용자의 발표 내용과 전체 스피치에 대한 피드백을 GPT API로 제공.
- 🧠 모든 모드에서 사용자 음성을 STT화 하여 처리

### 🔧 **담당 역할**
- **API 구현** – 코칭 모드와 파이널 모드의 백엔드 API 전반 구현 및 GPT 기반 질문 생성 로직 개발
- **실시간 피드백 처리** – 안드로이드에서 실시간 STT 및 성량 분석, 발표 속도 평가 기능 개발
- **DB 및 API 설계** – 전반적인 데이터베이스 테이블 구조 설계 및 API 설계

<br>

## Skills & Tools
<div style="display: flex; gap: 10px;">
  <strong>Programming Languages</strong><br/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white">
  <img src="https://img.shields.io/badge/JAVA-000000?style=for-the-badge&logo=IntelliJ%20IDEA&logoColor=white">
  <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=C&logoColor=white">
  <img src="https://img.shields.io/badge/C%23-A8B9CC?style=for-the-badge&logo=Csharp&logoColor=white">
</div>

<div style="display: flex; gap: 10px;">
  <strong>Back-End</strong><br/>
  <img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=Spring&logoColor=white">
  <img src="https://img.shields.io/badge/SpringBoot-6DB33F?style=for-the-badge&logo=SpringBoot&logoColor=white">
  <img src="https://img.shields.io/badge/JSP-2C2255?style=for-the-badge&logo=eclipseide&logoColor=white">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white">
</div>

<div style="display: flex; gap: 10px;">
  <strong>Front-End</strong><br/>
  <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=Vue.js&logoColor=white">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white">
  <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
  <img src="https://img.shields.io/badge/css3-1572B6?style=for-the-badge&logo=css3&logoColor=white"> 
</div>

<div style="display: flex; gap: 10px;">
  <strong>Data Science & Analytics</strong><br/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white">
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge">
</div>

<div style="display: flex; gap: 10px;">
  <strong>DevOps & Tools</strong><br/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
</div>

<br/>

## Algorithm
[![Solved.ac
프로필](http://mazassumnida.wtf/api/v2/generate_badge?boj=yddan7052)](https://solved.ac/yddan7052)
![mazandi profile](http://mazandi.herokuapp.com/api?handle=yddan7052&theme=warm)

<br/>

## Stats
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=YoungdanNoh&layout=donut-vertical)](https://github.com/YoungdanNoh/github-readme-stats)

<br/>

## More
<div style="display: flex; gap: 10px;">
  <a href="https://velog.io/@noh_level0/posts" rel="noopener noreferrer" target="_blank">
    <img src="https://img.shields.io/badge/velog-20C997?style=for-the-badge&logo=velog&logoColor=white" style="max-width: 100%;"/>
  </a>
  <a href="mailto:shdbwjd705270@gmail.com">
    <img src="https://img.shields.io/badge/shdbwjd705270@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white"
        alt="email"
    />
  </a>
</div>
<!--
**YoungdanNoh/YoungdanNoh** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
