# 
![header](https://capsule-render.vercel.app/api?type=wave&color=auto&height=300&section=header&text=🍒Membery&fontSize=90)

## 목차
- [프로젝트명](#프로젝트명)
- [개요](#프로젝트-개요)
- [사용 기술](#기술)
- [링크](#링크)
- [프로젝트 소개](#프로젝트-소개)
- [담당 기능 구현](#담당-기능-구현)
- [회고](#회고)

## 프로젝트명
---
#### 🍒Membery
memory + bery의 합성어로 기억 + 작고 달콤한 것이라는 의미입니다.
반려동물과의 추억을 간직하자라는 뜻을 담고 있습니다.
<br>

## 🖥프로젝트 개요
---
<img src="https://github.com/hyejin202/-/assets/123609520/cd52780a-7c5b-43ef-9049-e814ab3a46ad" width="700" height="370">

반려동물 SNS + 펫시터 구인사이트로 반려동물과의 추억을 기록하고 반려동물을 관리할 수 있는 플랫폼입니다.
<br>
깃허브 주소        : <https://github.com/hyejin202/Membery> <br>
멤버 인원          : 6명 <br>
프로젝트 진행 기간 : 23.05.18 ~ 23.06.25
<br>

## 🔨기술🔨
---
<img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=OpenJDK&logoColor=white"/><img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=black"><img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=Spring&logoColor=white"><img src="https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jQuery&logoColor=black"><img src="https://img.shields.io/badge/GitHub-660099?style=for-the-badge&logo=GitHub&logoColor=white"><img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white"><img src="https://img.shields.io/badge/AWS-000000?style=for-the-badge&logo=AWS&logoColor=white">
<br>

## 🔗링크
---
[Membery 링크](http://43.201.54.228:8082/)

<br>

## 🖥프로젝트 소개
### 1. 회원가입 및 소셜 로그인
  ![회원가입 및 소셜 로그인](https://github.com/hyejin202/-/assets/123609520/9bcffb00-94df-4923-903d-d7adbf54d053)
### 2. 반려동물 등록 및 프로필 설정
  ![네브바, 반려동물 등록 및 프로필 설정](https://github.com/hyejin202/-/assets/123609520/8d94f82e-fc6b-4af8-abfb-d1fadc0c06ac)
### 3. SNS
  ![sns파트](https://github.com/hyejin202/-/assets/123609520/f4af2c31-ee06-4bcf-a79e-44afea1a5ddb)
-  홈피드, 마이피드, 게시물 crud
-  댓글, 좋아요, 팔로우 기능
-  캘린더, 알림, 서치 기능
### 4. 함께가개
  ![함께가개](https://github.com/hyejin202/-/assets/123609520/4551eefc-bb79-4329-91fc-aa7e06186b72)
  - 지도 구현, 장소 찜하기 기능
### 5. 펫시터 
  ##### 5-1 펫시터 목록 및 상세페이지
  ![펫시터1](https://github.com/hyejin202/-/assets/123609520/8ada182b-9d5a-44e2-a65f-31a180cb54f7)
  ##### 5-2 예약
  ![펫시터2](https://github.com/hyejin202/-/assets/123609520/a77dd622-4eee-489a-97ce-171c8b7cafc8)
- 펫시터 예약, 승인, 거절, 결제 기능
- 댓글(사용 후기) 기능
### 6. QnA 게시판, 관리자 권한
  ![QnA, 관리자권한](https://github.com/hyejin202/-/assets/123609520/28482f5e-99b1-432a-88e5-7926782e85f3)

<br>

## 🙋🏻‍♀️담당 기능 구현
### 1. 홈페이지 기능
  ![홈피드 기능](https://github.com/hyejin202/-/assets/123609520/88a5a486-e327-4312-a328-7fc61ec40a5c)
  - semantic ui를 이용한 피드 형식 구현
  - bxslider로 사진 넘기기
  - 피드 클릭 시 해당 게시물 보기로 이동
  - 유저 닉네임 클릭 시 해당 유저의 마이피드로 이동
  - 게시물 등록 시간 '~전'으로 구현
### 2. 댓글 기능
  ![댓글기능](https://github.com/hyejin202/-/assets/123609520/89da2c89-dc63-497c-afac-65629be1c438)
  -  홈페이지 - 모달창으로 구현
  -  게시물 보기 - 목록형식으로 구현, 수정 및 삭제 시 확인 모달창 구현
### 3. 알림 기능
  ![알림기능](https://github.com/hyejin202/-/assets/123609520/d138092d-c05b-4af6-93c5-750ce09ee87a)
  - sns와 펫시터 페이지의 모든 알림을 네브바에서 확인할 수 있도록 구현
    알림 이모티콘 클릭시 알림창 뜸
  - 알림 확인/미확인 표시
    - 네브바 : 미확인 알림 1개 이상일 경우 빨간 뱃지로 표시
    - 알림창 : 확인한 알림의 회색 글씨로 변경돼 미확인한 알림과 구분됨
  - 알림창의 알림 메세지 클릭시 알림이 일어난 해당 위치로 이동
<br>

## 회고
---
- 알림 소켓 사용 X
- 캘린더 기능 구현 X - full calendar  api 가져오기만 함
- 단순 댓글 기능 구현 아쉬움 - 대댓글 기능 구현해보면 좋을 거 같음



  
