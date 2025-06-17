### <span id="top">🧋Starbucks Store Rebuilding🧋</span>
<br>
<img width="827" alt="스크린샷" src="https://github.com/user-attachments/assets/7f1989e0-3a48-4945-9b52-c9ec9751d84c">


## 소개 및 개요

- 프로젝트 기간 : 2025.03.11. ~ 2025.04.25.
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
7. [기능](#pageinfo)
8. [느낀점](#impression)
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

- Back-end :  <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=Java&logoColor=white"> <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=flat-square&logo=SpringBoot&logoColor=white"> <img src="https://img.shields.io/badge/Spring Security-6DB33F?style=flat-square&logo=SpringSecurity&logoColor=white"> <img src="https://img.shields.io/badge/mysql-4479A1?style=flat-square&logo=mysql&logoColor=white"> <img src="https://img.shields.io/badge/redis-FF4438?style=flat-square&logo=redis&logoColor=white"> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">

-  Infra : <img src="https://img.shields.io/badge/Amazon Ec2-FF9900?style=flat-square&logoColor=white"> <img src="https://img.shields.io/badge/Amazon S3-569A31?style=flat-square&logoColor=white"> <img src="https://img.shields.io/badge/Github Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"> <img src="https://img.shields.io/badge/NginX-009639?style=flat-square&logo=nginx&logoColor=white"> <img src="https://img.shields.io/badge/Cloud Flare DNS-F38020?style=flat-square&logo=cloudflare&logoColor=white">
<br/>

### [개발 환경]
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=Git&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white"/> <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=Figma&logoColor=white"/> <img src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=Notion&logoColor=white"/> <img src="https://img.shields.io/badge/Discord-5865F2?style=flat-square&logo=Discord&logoColor=white"/> <img src="https://img.shields.io/badge/KakaoTalk-FFCD00?style=flat-square&logo=kakaotalk&logoColor=white"/> 
- [Notion](https://www.notion.so/1b35039f7f1780c798d9d1a1d7916d4d) : 진행 상황 및 회의, 전반적인 일정관리 회고록 등을 노션을 활용해서 진행했습니다.
- [Figma](https://www.figma.com/board/p4eRRybDqjLkhLdZBhkRiJ/%EC%9E%90%EB%B0%94%EC%B9%A9-%ED%94%84%EB%9D%BC%ED%91%B8%EC%B9%98%EB%85%B8-4%EC%A1%B0--Event-Storming?node-id=0-1&t=1P6YNWfEOYuh5MUl-1) : 동시 접속하여 함께 이벤트 스토밍을 진행했습니다.
- `Kakao Talk` : 카카오톡을 통해 원활한 소통을 진행하였습니다.
- `Discord` : 디스코드를 통해 배포 성공, 실패 여부를 확인할 수 있도록 활용했습니다.
<br/>

### [IDE 및 테스트]
<img src="https://img.shields.io/badge/IntelliJ-000000?style=flat-square&logo=intellijidea&logoColor=white"/> <img src="https://img.shields.io/badge/Visual Studio Code-40AEF0?style=flat-square&logoColor=white"/> <img src="https://img.shields.io/badge/PostMan-FF6C37?style=flat-square&logo=postman&logoColor=white"/> <img src="https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=white"/>
- `IntelliJ` : IntelliJ를 활용하여 백엔드 작업을 진행했습니다.
- `Visual Studio Code` : Visual Studio Code를 활용하여 프론트엔드 작업을 진행했습니다.
- `PostMan`, `Swagger` : PostMan 과 Swagger를 활용하여 api 통신 테스트 및 문서화 작업을 진행했습니다.

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
### 작업물 관리

#### 📍 Google Docs
 프로젝트의 전반적인 내용과 작업 과정등을 google docs에 담아서 관리했습니다.
 [🔗 Google Docs](https://github.com/user-attachments/files/19932522/6.1.4.pdf)
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
<img width="800" alt="front" src="https://github.com/user-attachments/assets/52bd60a9-95d5-4de3-80d0-66bcf169685e">
<img width="800" alt="back" src="https://github.com/user-attachments/assets/208912aa-30cb-4d75-9024-1e78ecda177a">

<br/>
<p align="right"><a href="#top">(⬆️ Top)</a></p>

## <span id="ui">6. UI</span>
<img width="500" alt="ui" src="https://github.com/user-attachments/assets/b7b7c8c8-af55-47cb-8e30-1877aeb32eb1">
<img width="500" alt="ui" src="https://github.com/user-attachments/assets/45929637-d527-4ef5-8bcb-cceaa619b02f">
<img width="500" alt="ui" src="https://github.com/user-attachments/assets/ab956da6-23b6-4493-bf3c-fe570892689b">
<img width="500" alt="ui" src="https://github.com/user-attachments/assets/c45c3702-2e3f-4bb7-bb7e-8be6ddf9e2ef">
<img width="500" alt="ui" src="https://github.com/user-attachments/assets/63d7579f-b479-4b79-9a42-c05874ca5b9d">
<img width="500" alt="ui" src="https://github.com/user-attachments/assets/6ea9f7a1-8e87-42e8-8152-0eadb12f16a9">
<img width="500" alt="ui" src="https://github.com/user-attachments/assets/4d930112-c1e7-46ce-84ab-2de775ec598f">
<img width="500" alt="ui" src="https://github.com/user-attachments/assets/5f34b22c-1c4d-4151-b440-06608756cb58">
<img width="500" alt="ui" src="https://github.com/user-attachments/assets/8e12ecd9-0674-4ba3-b3f3-0ddf7352fdbb">
<img width="500" alt="ui" src="https://github.com/user-attachments/assets/4116c48d-af9f-4e45-bfdd-d71cce46e71b">
<img width="500" alt="ui" src="https://github.com/user-attachments/assets/ce335678-f8d5-40d9-b6ab-1a50a3fec1a1">
<img width="500" alt="ui" src="https://github.com/user-attachments/assets/9e8bbf20-5b59-4092-aa99-7b25cc27054f">

<br/>
<p align="right"><a href="#top">(⬆️ Top)</a></p>

## <span id="pageinfo">7. 기능 소개</span>

### 1) 페이지 기능
|[회원가입]()|[소셜 로그인]()|
|:-:|:-:|
|<img width="390px" alt="회원가입" src="https://github.com/user-attachments/assets/7bc244f6-20c5-4243-8818-b90a4616701e">|<img width="390px" alt="소셜 로그인" src="https://github.com/user-attachments/assets/d6bd6c8b-b736-45d5-824d-bc7869a812b2">|
|회원가입은 로컬, 소셜 회원가입이 가능합니다.|소셜 로그인 시 간편하게 로그인이 가능합니다.|

|[상품 검색]()|[상품 카테고리, 무한 스크롤]()|[상품 정렬]()
|:-:|:-:|:-:|
|<img width="300px" alt="상품검색" src="https://github.com/user-attachments/assets/0a27c976-c0db-4435-b079-2bdb06d5736e">|<img width="300px" alt="상품 카테고리 무한스크롤" src="https://github.com/user-attachments/assets/26817beb-539c-4bac-a14c-85fb6da5500d">|<img width="300px" alt="상품 정렬" src="https://github.com/user-attachments/assets/a4aa0846-630c-4c08-933b-aa83bc5abd47">|
|키워드를 통해 상품을 검색할 수 있습니다.|카테고리별로 상품을 조회할 수 있고, 사용자 경험을 위해 무한 스크롤을 적용했습니다.|최신순, 가격순, 추천순으로 상품 필터링이 가능합니다.|

|[상품 상세 & 리뷰]()|[리뷰 등록]()|
|:-:|:-:|
|<img width="390px" alt="리뷰" src="https://github.com/user-attachments/assets/24c43c1f-180b-48c6-b007-2b8dd27d31bd">|<img width="390px" alt="리뷰" src="https://github.com/user-attachments/assets/28fa7eb8-e985-4662-8691-d9d953de01fc">|
|상품 상세 셜명과 해당 상품의 리뷰를 확인할 수 있습니다.|사용자가 구매한 상품에 대한 리뷰를 등록할 수 있습니다.|

|[찜하기]()|[장바구니]()|
|:-:|:-:|
|<img width="390px" alt="찜" src="https://github.com/user-attachments/assets/b817a6aa-fc83-4c5a-853a-2912b12139fe">|<img width="390px" alt="장바구니" src="https://github.com/user-attachments/assets/724dd1f1-4791-4828-83a2-d14a6dff4bbd">|
|원하는 상품을 찜 기능을 통해 내가 찜한 상품들을 볼 수 있습니다.|구매하고 싶은 상품들을 장바구니에 담아서 관리 할 수 있습니다.|

|[배송지]()|[주문&결제]()|
|:-:|:-:|
|<img width="390px" alt="배송지" src="https://github.com/user-attachments/assets/645c0fd7-3e3c-4eb7-b99b-ff26dbdf62f0">|<img width="390px" alt="주문결제" src="https://github.com/user-attachments/assets/9927f26f-2105-44b6-b582-ad1a105efb5c">|
|배송지 설정 및 관리를 할 수 있습니다.|상품을 주문 하고 Toss Payments를 통해 결제를 할 수 있습니다.|

<br/>

<p align="right"><a href="#top">(⬆️ Top)</a></p>


## <span id="impression">8. 느낀 점</span>

### 🐱 수현 
- 처음 next.js와 ts 를 사용하면서 어려운 점도 많고 부족한 점도 많았지만 많이 성장 할 수 있는 기회가 되었습니다.
- 기한이 짧아서 원하는 만큼의 퀄리티가 나오지 않아 아쉬워서 추후에 리펙토링을 하고 싶습니다.

### 🐶 채영 
- 협업 경험이 많이 없었는데, 팀원들과의 소통으로 배운 점이 많았습니다.
- 기한이 짧아 제대로 마무리하지 못한 것이 아쉬워서 추후에 꼭 리팩토링을 거치고 싶습니다.

### 🐹 민조 
- DDD, Layered Architecture에 대한 이해로 추후 MSA를 도입할 때 도움이 될 것 같습니다.
- 개발 이전에 설계 단계에 시간을 적지 않게 쓰면서 고려해야 할 사항이 굉장히 많았는데 서비스 설계 자체에 대한 이해력과 유저 입장에서의 생각이 많이 향상된 것 같습니다.
- 실제로 몇만개의 데이터들을 주입해서 서비스를 운영하여, 성능적인 부분을 고려한 코드 작성의 중요성을 알게되었습니다.
- 인프라, CI/CD를 담당하면서 배포에 대한 이해, 특히 Docker에 대한 이해가 앞으로의 프로젝트에서도 큰 도움이 될 것 같습니다.

### 🐰 동섭 
- order, payment, cart 등 복잡한 도메인을 유기적으로 연결하며,  DDD와 Layered Architecture에 대한 이해도를 높일 수 있었습니다.
- 도메인 간 복잡도가 높아지며 차후 MSA 도입의 필요성을 이해할 수 있었습니다.
- 대용량 데이터 처리의 필요성과, 이를 고려한 CQRS 패턴의 필요성을 체감할 수 있었습니다.
- 이번 프로젝트의 경험과 배운 점을 살려서 다음 프로젝트는 더 엄밀하고 실무적인 관점으로 진행하고 싶습니다.

### 🦁 현재
- MSA 도입을 위한 전 단계로 DDD + Layered Architecture에 대한 이해를 할 수 있는 좋은 기회였습니다.
- 프론트엔드와 백엔드의 협업 과정을 경험할 수있어서 좋았습니다.
- 또한 실제 운영환경을 예상한 코드 작성과 대용량 데이터 처리에 대한 학습을 할 수있는 뜻깊은 경험이었습니다.

<br/>

<br/>
<p align="right"><a href="#top">(⬆️ Top)</a></p>
