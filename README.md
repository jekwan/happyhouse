# HappyHouse

**삼성 청년 SW 아카데미**에서 진행한 프로젝트 입니다.

# 프로젝트 목적

## 새로운 집을 찾기위해 지도를 열면 고려해야 할 것이 생각보다 많습니다!

- 대충 저기쯤이 회사인데...
- 내가 다니는 치과는?
- 헬스장은 10개월이나 남았구나
- 자주 가는 쇼핑몰이 저기고
- 동물 병원은 여기고
- 부모님 집까지는 얼마나 멀지
- ...

매번 찾을 때 마다 이것 저것 따져보자니 너무 번거롭습니다.  
나의 `생활 영역`을 기반으로 알맞은 `매물 정보를 한 눈에` 볼 수 있었으면 좋겠다는 생각에 이 웹 어플리케이션을 만들게 되었습니다.

# 사용 기술 스택

<img src="https://img.shields.io/badge/Vue-blue?style=flat&logo=vue.js&logoColor=white" height="50"> 
<img src="https://img.shields.io/badge/SpringFramework-6DB33F?style=flat&logo=spring&logoColor=white" height="50">
<img src="https://img.shields.io/badge/MySql-F80000?style=flat&logo=mysql&logoColor=white" height="50">

# 프로젝트 구조

저장소는 `SpringBoot` 구조이며, `/vue/happyhouse`에 프론트엔드 프로젝트(`Vue`)가 위치하고 있습니다.

# 프로젝트 진행과 역할 분담

`프로젝트 팀원` : 김제관(팀장), 김영진(팀원)  
`프로젝트 진행 기간` : 2022-05-19(목) ~ 2022-05-26(목) 총 7일

프로젝트 진행에 앞서 구현해야 할 기능을 `기본 기능`과 `심화 기능`으로 나누었습니다.

| `기본 기능`               | `심화 기능`               |
| :------------------------ | :------------------------ |
| 로그인/회원가입/수정/탈퇴 | 유저 `생활 영역` 관리     |
| 공지사항                  | `생활 영역`기반 정보 제공 |
| 기본 검색                 | 심화 검색                 |
| 카카오 맵 연동            | 카카오 맵 활용            |

![기능별 일정](/images/img1.png)

그리고 `기본 기능`에 3일, `심화 기능`에 4일을 투자하도록 결정하였습니다.

![관통 방식의 기능 개발](/images/img2.png)

백엔드와 프론트엔드의 공통 기반을 먼저 함께 완성하고  
이후에 각각의 기능별로 Backend부터 Frontend까지 관통하는 방식으로 개발을 진행하였습니다.  
팀원 별 기능 구분은 아래와 같습니다.

| `김제관`                    | `김영진`                    |
| :-------------------------- | :-------------------------- |
| 공지 사항 기능              | 유저 관련 기능              |
| 카카오 맵 연동 및 활용      | 유저 생활 영역 관리 기능    |
| 생활 영역 과 카카오 맵 활용 | 생활 영역 과 카카오 맵 활용 |
| 기본 검색 및 심화 검색 기능 | 어드민 관련 기능            |

# 프로젝트 결과

핵심 기능에 대한 결과물입니다.

## `메인 화면`

![프로젝트 결과물](/images/img3.png)

### HappyHouse는 SPA 방식의 `지도앱`입니다.

## `생활 영역 추가하기`

![장소 기억하기](/images/img4.png)

### 지도를 클릭하면 마커가 생성되며 해당 장소를 나의 `생활 영역`에 등록할 수 있습니다.

## `생활 영역으로부터 거리 보기`

![생활 영역 거리 보기](/images/img5.png)

### 좌측 상단의 `자`모양 버튼을 활성화하면 선택한 지점으로 부터 나의 `생활 영역`까지의 거리를 알 수 있습니다.

## `맵 위에 영역을 그려 매물 검색하기`

![심화 검색](/images/img6.png)

### 좌측 상단의 `도형 그리기`버튼을 활성화 하면 지도에 영역을 그릴 수 있고, 영역 내의 매물 내역도 검색할 수 있습니다.
