### <span id="top">🧋Starbucks Store Rebuilding🧋</span>
<br>
<img width="827" alt="스크린샷" src="https://github.com/user-attachments/assets/7f1989e0-3a48-4945-9b52-c9ec9751d84c">


## 소개 및 개요

- 프로젝트 기간 : 2025.03.11. ~ 2025.4.25.
- 배포 URL : [🔗 Starbucks Store](https://starbucks-store.shop/)

- Test ID / PW : abcde@naver.com / qwerty1234!

### [프로젝트 설명]
* 기존 운영되고 있는 스타벅스 스토어 앱을 리빌딩 하는 프로젝트 입니다. 
* 추후 MSA 기반 구조 전환을 위한 도메인 중심 설계(Domain-Driven Design)학습
* 실제 운영 상황을 가정한 설계 및 성능 테스트 기반 개선
* 대용량 데이터를 다루기 위한 학습

<br/>

<details>
<summary>목차</summary>
<div markdown="1">

1. [팀 소개](#teamintro)
2. [기술 및 개발 환경](#stack)
3. [개발 기간 및 작업 문화](#task)
4. [주요 기능](#mainfeat)
5. [역할분담](#role)
6. [UI](#ui)
7. [페이지 기능](#pageinfo)
8. [핵심 기능](#issue)
9. [느낀점](#impression)
</div>
</details>
<br/>

## <span id="teamintro">1. 팀 소개</span>
### 🚀 자바칩 프라푸치노 팀을 소개합니다!
안녕하세요, 저희는 2명의 Front-end, 3명의 Back-end 개발자로 구성된 **자바칩 프라푸치노**팀입니다. </br>
프라푸치노처럼 부드럽지만 강력하게 → 유연한 협업과 탄탄한 개발 실력을 갖춘 팀! 🚀🔥 
</br>
(신세계 스파로스 아카데미 6기 4조 입니다.)

|                                                                   **✨ 박수현**                                                                   |                                                                  **✨ 윤채영**                                                                   |                                                                    **👑 김민조**                                                                     |                                                              **✨ 정동섭**                                                              |                                                               **✨ 조현재**                                                               |
| :-----------------------------------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------: |
|                               <img src="https://github.com/user-attachments/assets/f4f4d1c2-4a89-48a3-b149-3f0b77227de8" height=180 width=180>                               |     <img src="https://github.com/user-attachments/assets/5ead1689-afcf-4c31-a87e-5732f110639e" height=180 width=180>      |       <img src="https://github.com/user-attachments/assets/e4b4af5e-00c8-48db-aeea-447860adcc1f" height=180 width=180>        | <img src="https://github.com/user-attachments/assets/57365efd-3ce3-4233-85c8-344bd440eca8" height=180 width=180> | <img src="https://github.com/user-attachments/assets/867c6c7b-8fa8-4f6c-b3eb-632904a07dcd" height=180 width=180> |
|                 **github**: [Sutaenghhh](https://github.com/Sutaenghhh)                 |      **github**: [yunchyn](https://github.com/yunchyn)       |                 **github**: [Mongjo](https://github.com/Mongjo)                  |       **github**: [JungDongSeop](https://github.com/JungDongSeop)        |     **blog**: [HyeonProG](https://guswo3443.tistory.com/) </br> **github**: [HyeonProG](https://github.com/HyeonProG)     |
| ![FrontEnd](https://img.shields.io/badge/FrontEnd-3f97fb) | ![FrontEnd](https://img.shields.io/badge/FrontEnd-3f97fb) | ![Team%20Leader](https://img.shields.io/badge/-Team%20leader-yellow)</br> ![BackEnd](https://img.shields.io/badge/BackEnd-000000) | ![BackEnd](https://img.shields.io/badge/BackEnd-000000)| ![BackEnd](https://img.shields.io/badge/BackEnd-000000) |


<br/>
<p align="right"><a href="#top">(⬆️ Top)</a></p>

## <span id="stack">2. 기술 및 개발 환경</span>
### [사용 기술]
- Front-end : <img src="https://img.shields.io/badge/React-06B6D4?style=flat-square&logo=React&logoColor=white"> <img src="https://img.shields.io/badge/next.js-DB7093?style=flat-square&logo=nextdotjs&logoColor=white"> <img src="https://img.shields.io/badge/tailwindcss-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white"> <img src="https://img.shields.io/badge/shadcn/ui-000000?style=flat-square&logo=shadcn/ui&logoColor=white"> <img src="https://img.shields.io/badge/zod-3E67B1?style=flat-square&logo=zod&logoColor=white">

- Back-end :  <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=Java&logoColor=white"> <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=flat-square&logo=SpringBoot&logoColor=white"> <img src="https://img.shields.io/badge/Spring Security-6DB33F?style=flat-square&logo=SpringSecurity&logoColor=white"> <img src="https://img.shields.io/badge/mysql-4479A1?style=flat-square&logo=mysql&logoColor=white"> <img src="https://img.shields.io/badge/redis-FF4438?style=flat-square&logo=redis&logoColor=white">

-  Infra : <img src="https://img.shields.io/badge/Amazon Ec2-FF9900?style=flat-square&logoColor=white"> <img src="https://img.shields.io/badge/Amazon S3-569A31?style=flat-square&logoColor=white"> <img src="https://img.shields.io/badge/Github Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"> <img src="https://img.shields.io/badge/NginX-009639?style=flat-square&logo=nginx&logoColor=white"> <img src="https://img.shields.io/badge/Cloud Flare DNS-F38020?style=flat-square&logo=cloudflare&logoColor=white">
<br/>

### [개발 환경]
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=Git&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white"/> <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=Figma&logoColor=white"/> <img src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=Notion&logoColor=white"/> <img src="https://img.shields.io/badge/Discord-5865F2?style=flat-square&logo=Discord&logoColor=white"/> <img src="https://img.shields.io/badge/KakaoTalk-FFCD00?style=flat-square&logo=kakaotalk&logoColor=white"/> 
- [Notion](https://www.notion.so/1b35039f7f1780c798d9d1a1d7916d4d) : 진행 상황 및 회의, 전반적인 일정관리 회고록 등을 노션을 활용해서 진행했습니다.
- [Figma](https://www.figma.com/board/p4eRRybDqjLkhLdZBhkRiJ/%EC%9E%90%EB%B0%94%EC%B9%A9-%ED%94%84%EB%9D%BC%ED%91%B8%EC%B9%98%EB%85%B8-4%EC%A1%B0--Event-Storming?node-id=0-1&t=1P6YNWfEOYuh5MUl-1) : 동시 접속하여 함께 이벤트 스토밍을 진행했습니다.
- `Kakao Talk` : 카카오톡을 통해 원활한 소통을 진행하였습니다.
- `Discord` : 디스코드를 통해 배포 성공, 실패 여부를 확인할 수 있도록 활용했습니다.
<br/>

 ### [Git 흐름 전략]
각각의 기능을 담당하여 프로젝트를 진행하고자 [ Git Flow 방식 ] 을 사용했습니다.
페이지 별/ 기능 별 브랜치를 만들고 각자 작업 브랜치를 따로 생성하여, PR 및 Merge를 진행합니다.
<br/>
<br/>

 ### [커밋 컨벤션]
 [🔗 커밋 컨벤션 ](https://www.notion.so/git-conventions-1bb5039f7f17803286f6ccf8359b2b73)
 
```
- feat: 새로운 기능 구현
- fix: 오류 수정
- docs: 문서 수정 (예 : readme.md, json 파일 등 수정/ 문서 관련 라이브러리 설치 등)
- design: 마크업 및 style 작업
- style: 코드에 변화가 없는 수정 (예 : prettier, 세미콜론 등)
- refactor: 코드 리팩토링
- comment: 주석 추가
- chore: 빌드 부분 혹은 패키지 매니저 수정사항
- rename: 파일 혹은 폴더명 수정 or 옮기기
- remove: 파일 삭제
```
<br/>

 ### [코드 컨벤션]
 통일성 있는 코드 작성을 위해 다양한 [🔗 백엔드 코드 컨벤션 ](https://www.notion.so/Back-End-conventions-1bb5039f7f1780ac933ecce1e6ac6470), [🔗 프론트엔드 코드 컨벤션 ](https://www.notion.so/Front-End-conventions-1bb5039f7f1780fc9f72f827028ebd8b)을 정해 사용했습니다.
 
 <br/>
 <p align="right"><a href="#top">(⬆️ Top)</a></p>

## <span id='task'>3. 개발 기간 및 작업 문화 </span>
### [프로젝트 기간] : 2025.03.11. ~ 2025.4.25.
<br/>

### [작업 문화]
#### 📍 Google Docs
프로젝트의 전반적인 내용과 작업 과정등을 google docs에 담아서 관리했습니다.
![Google Docs](https://docs.google.com/spreadsheets/d/1cz6tOv7gIxSM5QyFZ38rE_gv14Fgrxe004PtK6xNupc/edit?usp=sharing)
<br/>

#### 📍 Notion 회고
- 팀 노션에 동시 접속하여 [🔗 일일 회고](https://www.notion.so/1b65039f7f178083850ed3821f6e37ee)를 진행하고 진행사항을 파악했습니다.

<img width="600" alt="front" src="https://github.com/user-attachments/assets/87a78479-00dc-4ad2-b519-a1b52be2adf8">
<br/>

<p align="right"><a href="#top">(⬆️ Top)</a></p>

## <span id='mainfeat'>4. 주요 기능</span>
### 🔒 사용자
 * 로그인
 * 회원가입
 * 소셜 로그인(google, kakao)
 * 유효성 검사
 * 토큰 검증
 * 회원 탈퇴 / 복구
### 📦 상품
* 카테고리별 상품 조회
* 기획전 상품 조회
* 베스트 상품 조회
* 시즌별 상품 조회
* 정렬 조회(최신순, 가격순, 추천순)
* 무한 스크롤
* 최근 본 상품
* 찜하기
### 🔍 검색
* 상품 키워드 검색
### 💬 리뷰
* 리뷰 등록
* 리뷰 수정
* 리뷰 삭제
### 💳 결제
* 카드 결제
* 계좌 이체
### 🚚 배송지
* 배송지 등록
* 배송지 수정
* 배송지 삭제
* 기본 배송지 설정
### 🛒 장바구니
* 장바구니 등록
* 장바구니 수정
* 장바구니 삭제

<br/>
<p align="right"><a href="#top">(⬆️ Top)</a></p>

## <span id="role">5. 역할 분담</span>
<img width="800" alt="front" src="https://github.com/user-attachments/assets/e947c6a2-f750-40ec-90ca-484180065b99">
<img width="800" alt="back" src="https://github.com/user-attachments/assets/36af7137-e7bd-4016-858b-53366b3099f2">

<br/>
<p align="right"><a href="#top">(⬆️ Top)</a></p>

## <span id="ui">6. UI</span>
<img width="500" alt="ui" src="https://github.com/user-attachments/assets/b7b7c8c8-af55-47cb-8e30-1877aeb32eb1">
<img width="500" alt="ui" src="https://github.com/user-attachments/assets/45929637-d527-4ef5-8bcb-cceaa619b02f">
<img width="500" alt="ui" src="https://github.com/user-attachments/assets/ab956da6-23b6-4493-bf3c-fe570892689b">
<img width="500" alt="ui" src="https://github.com/user-attachments/assets/c45c3702-2e3f-4bb7-bb7e-8be6ddf9e2ef">
<img width="500" alt="ui" src="https://github.com/user-attachments/assets/63d7579f-b479-4b79-9a42-c05874ca5b9d">

<br/>
<p align="right"><a href="#top">(⬆️ Top)</a></p>

## <span id="pageinfo">7. 페이지 기능</span>

### 1) 페이지 기능
|[기능1]()| [기능2]()|[기능3]()|
|:-:|:-:|:-:|
|<img width="390px;" alt="기능1" src=""> |<img width="390px;" alt="기능2" src="">|<img width="390px;" alt="기능3" src="">|

|[기능4]()|[기능5]()|
|:-:|:-:|
|<img width="390px;" alt="기능4" src="">|<img width="390px;" alt="기능5" src="">|

<br/>

<br/>
<p align="right"><a href="#top">(⬆️ Top)</a></p>

## <span id="issue">8. 핵심 기능</span>

### [핵심 1]
내용 1
<br/>

### [핵심 2]

내용 2
<br/>

### [핵심 3]

내용 3
<br/>

### [핵심 4]

내용 4
<br/>
<p align="right"><a href="#top">(⬆️ Top)</a></p>


## <span id="impression">9. 느낀 점</span>

### 🐱 수현 
- 느낀점

### 🐶 채영 
- 느낀점

### 🐹 민조 
- 느낀점
### 🐰 동섭 
- 느낀점

### 🦁 현재
- 느낀점

<br/>

<br/>
<p align="right"><a href="#top">(⬆️ Top)</a></p>
