# <img src="https://avatars.githubusercontent.com/u/129720335?s=200&v=4" width=30px height=30px> **MatchBox Project**

<br>

## 0. 목차

-   [1. Introduce](#1-Introduce)
-   [2. 링크](#2-Link)
-   [3. stacks](#3-Stacks)
-   [4. 프로젝트 구조](#4-Diagram)
-   [5. 팀 소개](#5-MatchBox-Team)

<br>

## 1. Introduce

-   ### MatchBox?
    `과기부 산하 이노베이션아카데미 42서울의 교육생들이 간단한 게임을 즐기고 소통을 할 수 있는 채팅 웹 애플리케이션 입니다. 42서울 공통과정 졸업 프로젝트로 풀스택으로 백엔드 프론트엔드 모두 담당하여 제작하였습니다.`
-   ### User

-   > **42Cadets/Members** : 친구 관리, 채팅, 게임 <br>

## 2. Link

-   Docs : [MatchBox Docs](https://github.com/Match-Box-Team/Docs/wiki) <br>
-   Frontend Repo : [MatchBox Front](https://github.com/Match-Box-Team/FrontEnd) <br>
-   Backend Repo : [MatchBox Back](https://github.com/Match-Box-Team/BackEnd) <br>
    <br>
    

## 3. Stacks

<table border="1" align="center">
  <th align="center">파트</th>
  <th align="center">기술스택</th>
  <th align="center">선정이유</th>
  <tr>
    <td rowspan="3" align="center">Common</td>
    <td><img src="https://static-00.iconduck.com/assets.00/typescript-icon-icon-1024x1024-vh3pfez8.png" width="15px" alt="typescript_icon" /> TypeScript</td>
    <td>Type 안정성을 보장하여 런타임 에러 방지</td>
  </tr>
  <tr>
    <td><img src="https://prettier.io/icon.png" width="15px" alt="prettier_icon" /> Prettier</td>
    <td>코드 스타일 정형화를 통한 협업 능률 향상</td>
  </tr>
  <tr>
    <td><img src="https://p1.hiclipart.com/preview/609/87/646/react-logo-socketio-javascript-expressjs-github-html5-nodejs-network-socket-png-clipart.jpg" width="15px" alt="socket.io_icon" /> Socket.io</td>
    <td>실시간 채팅 및 게임 기능 구현을 위해 HTTP 통신이 아닌 소켓 통신 필요</td>
  </tr>
  <tr>
    <td rowspan="3" align="center">Backend</td>
    <td><img src="https://docs.nestjs.com/assets/logo-small.svg" width="15px" alt="nestjs_icon" /> NestJS</td>
    <td> <code>DI</code> : 의존관계를 분리하여 수정 및 재사용이 용이함 <br/> <code>IoC</code> : 컴포넌트와 모듈에 집중한 프로그래밍 가능, 유지보수 또는 확장시 편리</td>
  </tr>
  <tr>
    <td><img src="https://w7.pngwing.com/pngs/396/90/png-transparent-postgresql-database-logo-computer-icons-replication-software-developer-miscellaneous-blue-mammal-thumbnail.png" width="15px" alt="postgresql_icon" /> PostgreSQL</td>
    <td>영구 무료인 오픈소스, 참고할 자료가 많고 다양함</td>
  </tr>
  <tr>
    <td><img src="https://icons-for-free.com/iconfiles/png/512/vscode+icons+type+light+prisma-1324451365475006031.png" width="15px" alt="prisma_icon" /> Prisma</td>
    <td>RDBMS의 데이터 구조와 객체지향 모델 사이의 간격을 줄여 생산성 증가</td>
  </tr>
  <tr>
    <td rowspan="3" align="center">Frontend</td>
    <td><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/React-icon.svg/2300px-React-icon.svg.png" width="15px" alt="react_icon" /> React</td>
    <td>컴포넌트 기반 아키텍처를 통해 모듈화와 재사용성을 높여 개발 생산성을 향상</td>
  </tr>
  <tr>
    <td><img src="https://blog.kakaocdn.net/dn/l92lK/btqFNFi2V2k/kIYdVhPlhlvoG8ULF0uy61/img.png" width="15px" alt="styled_components_icon" /> styled-components</td>
    <td>컴포넌트 기반 디자인을 강화하고 재사용성을 향상</td>
  </tr>
  <tr>
    <td><img src="https://blog.kakaocdn.net/dn/14SHN/btsg1tFqmtp/VGLOZLfWKOuFVqGbsqTfnK/img.png" width="15px" alt="recoil_icon" /> Recoil</td>
    <td>React 상태 관리를 간단하게 처리하여 코드 유지보수와 개발 생산성을 향상</td>
  </tr>
  <tr>
    <td rowspan="1" align="center">Infra</td>
    <td><img src="https://techstack-generator.vercel.app/docker-icon.svg" width="15px" alt="docker-compose_icon" /> Docker-compose</td>
    <td> 컨테이너를 이용한 가상환경 구성 및 빌드 자동화</td>
  </tr>
</table>


## 4. Diagram

-   ### WireFrame <br>
    <img src="https://github.com/Match-Box-Team/Docs/assets/89024499/d1c2dda7-a670-49bb-9467-f7173d091a3a"> <br>
-   ### ERD <br>
    <img src="https://user-images.githubusercontent.com/89024499/231075910-0779571f-ec9c-4706-b182-db78b11338ad.png" /> <br>
    <br>


## 5. MatchBox Team

백엔드/프론트엔드 구분 없이 총 4명이서 디자인/설계/백엔드/프론트까지 진행했습니다. <br>
https://github.com/orgs/Match-Box-Team/people <br>


## 기타

-   docker-compose.yml에서 env는 backend/frontend 각각 필요
-   env 설정시 42OAuth id/secret 설정 필요
