<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:191919,100:333333&height=200&section=header&text=Back%20to%20the%20logic,%20back%20to%20the%20basics%20🧠&fontColor=ffffff&fontSize=40&animation=fadeIn" />
</div>


---

## 🧑‍💻 Who Am I?
<p align="center">
  <img src="https://github.com/user-attachments/assets/9ecdf061-1de1-4d8d-86e3-f0a089a94785" width="320"/>
</p><br>

기능보다 설계를 먼저 생각하는 백엔드 개발자입니다.<br>
기본기를 바탕으로 구조적인 코드를 지향합니다.

---
## 🛠️ Tech Stacks
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=Figma&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white)
![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=Slack&logoColor=white)


![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=Linux&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white)



![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=Java&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=Spring&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=Spring%20Boot&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white)


---

## 🚀 Projects


### 🏷️ 학사 관리 프로그램  
<img src="https://github.com/user-attachments/assets/c7e0c6e3-f6d9-44a7-a954-601f07c74818" width="720"/>  

> Stream API와 Lambda를 활용한 Java 기반 학사 관리 프로그램입니다. 성능과 안정성, 가독성을 고려한 함수형 설계에 집중했습니다.

- 🔗 [GitHub 바로가기](https://github.com/minhyeokshin/managements_program/tree/main/src/student)
- 🛠 **주요 기술**: Java (Stream, Lambda), JSON, GitHub
- 🧩 **핵심 구현**
  - 학번 검색 최적화 (findFirst + orElse 처리)
  - 최고/최저 점수 검색, 범위 검색, 등급 검색 등 다양한 필터 기능
  - 함수형 인터페이스 기반 확장성 있는 설계
- 🙋 **내 역할**
  - Stream API 도입 및 반복문 최적화 설계  
  - Null 안전성 향상 및 예외 방지 구조화  
  - Output 로직을 고려한 가독성 있는 설계 방식 적용  

---

### 🏷️ 직원 관리 CLI 프로그램  
<img src="https://github.com/user-attachments/assets/5a20f9ea-d528-442a-89b3-026f4e4d4c84" width="720"/>  

> Java + MySQL 기반 CLI 시스템으로, 기존 시스템을 통합하고 구조를 정리하며 유지보수성과 흐름 개선에 중점을 둔 프로젝트입니다.

- 🔗 [GitHub 바로가기](https://github.com/minhyeokshin/managements_program)
- 🛠 **주요 기술**: Java, MySQL, JDBC, MVC 구조
- 🧩 **핵심 구현**
  - 기존 학생관리 시스템과 직원관리 시스템 기능 통합
  - 컨트롤러 계층 재정비 및 역할 분기 흐름 정리
  - 공통 유틸(Validator, PrintUtil) 구조 재사용 및 의존성 간소화
- 🙋 **내 역할**
  - 컨트롤러 중심 흐름 설계 및 기능 분기 처리  
  - 중복 메서드/로직 제거 및 유지보수 관점 개선  
  - 유틸 클래스 구조 정리 → 이후 WMS 구조 설계 기반 확보  

---

### 🏷️ 창고관리(WMS) 시스템  - CLI
<img src="https://github.com/user-attachments/assets/76ef8c91-da9e-43e7-ba94-903c49774e99" width="720"/>  <br>
> 실무형 구조 설계에 집중한 CLI 기반 WMS 시스템. 기능보다 “흐름” 중심의 설계와 예외 방지 전략을 도입한 프로젝트입니다.

- 🔗 [GitHub 바로가기](https://github.com/minhyeokshin/Buildify_Phase-1)
- 🛠 **주요 기술**: Java, MySQL, JDBC, Validator, Cloud DB (Railway)
- 🧩 **핵심 구현**
  - 8개 Table 기반 입출고 흐름 설계 (입·출고 → 재고 자동 반영)
  - Cloud DB + 프로시저 기반 예외방지 구조 설계
  - 비전공자 대상 전파형 협업 구조 도입 (1명→1명 전달 방식)
- 🙋 **내 역할**
  - 초기 구조 설계 및 DB 환경 구축 전담  
  - Validator 클래스 및 Scanner static 구조 설계  
  - 구조 중심 발표 주도 → 수강생/강사 피드백 최상위 획득  

---
### 🏷️ 창고관리(WMS) 시스템  - WEB
<img src="https://github.com/user-attachments/assets/7862f68b-5813-478f-b783-52cc18ee08d4" width="720"/>  <br>

> **입·출고 요청부터 계약 관리·재고 모니터링까지**  
물류 창고 전체 흐름을 자동화하는 **웹 기반 WMS(창고 관리 시스템)**입니다.  
1차 CLI 버전 구조를 확장하여, 실무 수준의 웹 서비스 구조와 데이터 흐름을 직접 설계/구현했습니다.

- 🔗 [GitHub 바로가기](https://github.com/minhyeokshin/Buildify_Phase-2)
- 🛠 **주요 기술**: Java 17, Spring, MyBatis, Spring Security, MySQL, JSP, Gradle, AWS RDS
  
- 🧩 **핵심 구현**
  - 8개 이상 테이블 기반의 입·출고/재고 흐름 설계
  - 입고 → 재고 증가 / 출고 → 재고 감소 자동 연동
  - 출고 수량 초과 방지 → **Validator 기반 예외 처리 구조**
  - **Excel 보고서 출력, 계약기간 자동 필터** 등 관리자 기능 포함
  - Spring 단일 인스턴스 캐시 구조 적용 (조회 성능 개선)
    
- 🙋 **내 역할**
  - 전체 프로젝트 구조 설계 및 업무 흐름 정의 주도
  - Validator 및 Controller 예외 분기 처리 설계
  - 커밋/PR/이슈 컨벤션 설계 및 팀 협업 프로세스 정착
    
📌 **한 줄 요약**  
> 단순 CRUD를 넘어, **현업 WMS 프로세스를 웹으로 실전 설계한 프로젝트**입니다.

---
## 🗓️ Planus (협업 일정 관리 플랫폼) – 실무 지향 구조 설계 프로젝트
<img src="https://github.com/user-attachments/assets/f4817792-4d75-43f4-9127-7264dfe1bdf1" width="720"/>  

> **실제 협업 시나리오를 고려한 Spring 기반 그룹 일정·게시판·GitHub 연동 플랫폼.**  
단순 기능보다 “보안, 인증, 연동 흐름”에 집중한 **실무형 구조 설계 중심**의 개인 프로젝트입니다.


🔗 [GitHub 바로가기](https://github.com/shinminhyeok/planus)  
🔗 [홈페이지 바로가기(실서비스중)](https://planus.site)  
🛠 **주요 기술**: Java 17, Spring Boot, Spring Security, MyBatis, MySQL, AWS EC2, Nginx, GitHub API  


### 🧩 핵심 구현
- 그룹 일정 등록 → 관리자 메일 전송 자동 반영 구조
- 게시판 페이지네이션 + 검색 캐시 → 사용자 경험 최적화
- GitHub 커밋/PR 수집 자동화 → 활동 기반 협업 추적 구조 설계
- HTTPS + BCrypt + 세션 보안 → 실무 대비 인증 구조 설계
- 스프링 시큐리티 커스텀 + 이메일/일정 비동기 처리

### 🙋 내 역할
- 전체 시스템 기획 및 구조 설계 **100% 단독 구현**
- 인증/세션/메일/캐시 연동 흐름 직접 구성
- GitHub API 분석 → DTO 구조 정의 및 통신 처리
- 서버 배포 (EC2 + Nginx + SSL) 및 `systemd` 기반 자동 실행 구성
- 사용자 흐름 + 예외 처리 기반 구조 발표 경험 (기획 → 설계 → 시연)

📌 **한 줄 요약**  
> 기능 나열이 아닌, **협업 흐름과 신뢰성 중심으로 설계된 실무 지향 백엔드 프로젝트입니다.**

---

## 📫 Contact me
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=Gmail&logoColor=white)](mailto:sinminhyeok@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=LinkedIn&logoColor=white)](https://www.linkedin.com/in/minhyeok-shin-0bba66304/)<br>
[![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white)](http://devshin.info)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white)](https://github.com/minhyeokshin)
---

## 🏅 Stats
[![trophy](https://github-profile-trophy.vercel.app/?username=minhyeokshin&theme=darkhub&margin-w=10&row=1)](https://github.com/ryo-ma/github-profile-trophy)

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=minhyeokshin&show_icons=true&theme=dark)

[![minhyeokshin's github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=minhyeokshin&theme=react-dark)](https://github.com/ashutosh00710/github-readme-activity-graph)

---

<p align="center">
  Thank you for visiting!  
  <br/>  
  <img src="https://komarev.com/ghpvc/?username=minhyeokshin&style=flat-square" alt="Profile Views" />
</p>
