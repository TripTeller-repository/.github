# 🌸TripTeller (트립텔러)

> **"당신의 여행이 우리의 이야기가 되는 공간"**

> "여러분의 여행을 흥미로운 이야기로 바꿀 준비가 되셨나요?<br>
> 지금 여행을 시작하고, 트립텔러와 이야기를 공유하세요."

> <b>https://www.trip-teller.com/</b>

![리드미최상단](https://github.com/TripTeller-repository/TripTeller_BE/assets/127278410/b352ffe2-4031-4e95-91e8-544906929139)

<details>
<summary><b>유튜브 시연 영상</b></summary>
<div markdown="1">

[![Video Label](http://img.youtube.com/vi/IOLBQCbE9PY/0.jpg)](https://youtu.be/IOLBQCbE9PY)

</div>
</details>

---

## 바로가기

- [서비스 소개](#서비스-소개)<br>
- [프로젝트 개요](#프로젝트-개요)<br>
- [스토리보드](#스토리보드)<br>
- [페이지 구성](#페이지-구성)<br>
- [기능 설명](#기능-설명)<br>
- [참고 링크](#참고-링크)<br>

---

## 서비스 소개

- <b>요약</b> : 나만의 여행 일지를 기록하고 다른 사람들과 공유하는 서비스

- <b>기획 의도</b> : 기존 여행 관련 서비스<i>(야놀자, 여기핫태)</i>와 다르게 <u>이미지를 통해 감성을 불러일으키는 데 초점</u>을 맞춘 여행 플랫폼을 만들고자 함.

- 여행 전 여행을 계획하고, 다녀온 여행을 기록하는 <b>'나의 여행'</b>과 다른 사람이 공유한 여행을 감상할 수 있는 <b>'우리의 여행'</b> 서비스가 있음.<br>
  - **나의 여행**<br>
    - 요일, 장소, 시간별로 여행을 계획
    - 지출 예산을 설정하고 항목별 지출을 관리
    - 계획을 바탕으로 여행 이야기를 작성
    - ‘**지난 여행**’ : 본인이 작성한 게시물이 있는 카테고리
  - **우리의 여행**<br>
    - 작성한 여행 이야기를 다른 사람들과 공유

- <b>페르소나</b> :
  - <b>김 재현 / 20대 후반 남성 / 서울 거주 마케터</b>
    - 해외 여행지보다 다양한 국내 여행지를 탐방하는 것을 더 선호함.
    - 소셜 미디어에서 다양한 여행 경험을 공유하고 다른 사람들의 이야기에 몰입하는 것을 원함.
    - 숙박 예약이나 비용 같은 표준화된 지표보다는 이미지를 통해 전달되는 감성적인 이야기에 초점을 맞춘 여행 커뮤니티 플랫폼을 추구함.
      
<details>
<summary><b>페르소나 이미지 파일</b></summary>
<div markdown="1">

![image](https://github.com/TripTeller-repository/TripTeller_BE/assets/127278410/da54b605-99ad-4902-a9ee-08e886cf333e)

</div>
</details>

---

## 프로젝트 개요

- ### 진행 기간 <br>

  - <b>1차</b> : 기획 및 개발 (24.04.01 ~ 24.04.19) [3주]<br>
  - <b>2차</b> : 리팩토링 (24.06.01 ~24.06.15) [2주]<br>
    - (주)엘리스가 보유하고 있는 프라이빗 GitLab 저장소에서 1차 개발을 마침.
    - 이후 개별적으로 Github Organization 생성하여 2차 리팩토링을 진행함.

- ### 진행 인원 및 역할 <br>

  - 6명 (프론트엔드 4명, 백엔드 2명)<br>
    | 이름 | 역할 | 포지션 | 담당 업무 |
    |----------------------------|---------------------------|---------------------------|--------------------------|
    | 이가린 | 팀장 | Backend | • User, Authentication, Feed, Scrap 스키마 및 API 생성<br> • 클라이언트 및 서버 배포 |
    | 문채영 | 팀원 | Backend | • DailyPlan, DailySchedule, Expense, TravelLog 스키마 및 API 생성 |
    | 손민혁 | 팀원 | FrontEnd | • 로그인 및 회원가입, 회원정보수정, 예산/지출페이지 |
    | 이보미 | 팀원 | FrontEnd | • 우리의여행, 여행로그 상세페이지, 여행로그 작성페이지 |
    | 이유림 | 팀원 | FrontEnd | • 메인페이지, 나의 여행 페이지 |
    | 임기택 | 팀원 | FrontEnd | • 일정/관리 페이지, Kakao지도 API 활용 |

- ### 관련 링크

  - <b>노션 페이지</b> : https://night-softball-75b.notion.site/TripTeller-7-fb8597f05d9b49fabcc86e4b6c3535ec?pvs=4<br>
  - <b>피그마</b> : https://www.figma.com/design/succJjTiEnDzypCZ3s5s0n/%EC%99%80%EC%9D%B4%EC%96%B4%ED%94%84%EB%A0%88%EC%9E%84-%EC%9E%91%EC%97%85?node-id=0-1
  - <b>Swagger 배포 문서</b> : https://api.trip-teller.com/api
  - <b>포지션별 Github 저장소</b>
    - 프론트엔드 : https://github.com/TripTeller-repository/TripTeller_FE
    - 백엔드 : https://github.com/TripTeller-repository/TripTeller_BE

- ### 기술 스택
  - <b>프론트엔드</b> : ReactJS, Vite, JavaScript
  - <b>백엔드</b> : NestJS, MongoDB, TypeScript
  - <b>배포</b> : AWS S3, Route53, Cloudfront, EC2

---

## 스토리보드

## ![스토리보드](https://github.com/TripTeller-repository/.github/assets/127278410/46332d56-dc87-4407-8094-dd8923af8c46)

## ![스토리보드](https://github.com/TripTeller-repository/.github/assets/127278410/bb426e8c-15d9-44e9-b111-243b1bf96a7e)

## 페이지 구성

|                                                                                    메인화면<br>(/)                                                                                    |                                                                               나의여행<br>(/mytrip)                                                                                |
| :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|          <div style="text-align: center;">[![Main screen](https://github.com/TripTeller-repository/.github/assets/127278410/80408008-ed98-47ee-897d-32ee115a09b9)](#)</div>           |           <div style="text-align: center;">[![My Trip](https://github.com/TripTeller-repository/.github/assets/127278410/7418df7b-7844-4d7f-a8b3-f8dc44062966)](#)</div>           |
|                                                  <b><div style="text-align: center;">나의 여행 [일정관리] <br>(/maketrip)</div></b>                                                   |                                                  <b><div style="text-align: center;">나의 여행 [예산/지출]<br>(/mytrip)</div></b>                                                  |
| <div style="text-align: center;">[![My Travel-Itinerary Management](https://github.com/TripTeller-repository/.github/assets/127278410/0d89000b-be41-46c6-a13f-e7db5d60731a)](#)</div> | <div style="text-align: center;">[![My Trip - Budget Management](https://github.com/TripTeller-repository/.github/assets/127278410/9f4e5bf4-cdf4-4d17-acbb-46690ee840b1)](#)</div> |
|                                                   <b><div style="text-align: center;">나의 여행[여행로그]<br>(/maketrip)</div></b>                                                    |                                                      <b><div style="text-align: center;">우리의 여행<br>(/ourtrip)</div></b>                                                       |
|      <div style="text-align: center;">[![My Travel-Travel Log](https://github.com/TripTeller-repository/.github/assets/127278410/a5d343df-3b49-401e-8cde-32343b4cf830)](#)</div>      |          <div style="text-align: center;">[![Our Trip](https://github.com/TripTeller-repository/.github/assets/127278410/669a96c4-e73a-4511-836f-2e99019734d7)](#)</div>           |
|                                                           <b><div style="text-align: center;">로그인<br>(/login)</div></b>                                                            |                                                        <b><div style="text-align: center;">회원가입<br>(/signup)</div></b>                                                         |
|             <div style="text-align: center;">[![Login](https://github.com/TripTeller-repository/.github/assets/127278410/8ea939ce-1d1c-4ba4-970f-853ed7d3f172)](#)</div>              |           <div style="text-align: center;">[![Sign up](https://github.com/TripTeller-repository/.github/assets/127278410/cd37ac9d-8c71-42bf-bd27-6b1a5813be07)](#)</div>           |

---

## 기능 설명

### ✅ 기본적인 회원 인증 시스템

- '나의여행' 서비스는 로그인이 필요한 서비스임.
- <u>회원가입, 로그인, 로그아웃, 소셜로그인(카카오)</u>이 가능함.

<details>
<summary><b>회원가입</b> (시연 GIF)</summary>
<div markdown="1">

![회원가입(배)](https://github.com/TripTeller-repository/TripTeller_BE/assets/127278410/c57e7fd3-5e9a-4f5c-9031-ed2ed8c97767)

</div>
</details>
<details>
<summary><b>로그인</b> (시연 GIF)</summary>
<div markdown="1">

![로그인(배)](https://github.com/TripTeller-repository/TripTeller_BE/assets/127278410/dbdb50c7-4ab3-496b-8882-febbc8f46510)

</div>
</details>
<details>
<summary><b>카카오 로그인</b> (시연 GIF)</summary>
<div markdown="1">

![카카오로그인(배)](https://github.com/TripTeller-repository/TripTeller_BE/assets/127278410/4a798db6-0792-43cd-9b06-4a441cef2347)

</div>
</details>

<details>
<summary><b>로그아웃</b> (시연 GIF)</summary>
<div markdown="1">

![로그아웃(배)](https://github.com/TripTeller-repository/TripTeller_BE/assets/127278410/5edc9b52-7373-4cdb-9fae-cdedfc961a61)

</div>
</details>
<br>

### ✅ '나의 여행'에서 새로운 여행기록 작성하기

- '새로 만들기' 버튼을 누르면 모달 창에 입력된 여행 시작일과 종료일을 기준으로 <u>날짜별 UI 카드가 동적으로 생성</u>됨.<br>
  - ex) 6월 1일부터 6월 5일까지 여행하는 경우 일일 UI 카드 5개가 화면에 렌더링됨.
- 하나의 여행기록을 세 가지 카테고리(<u>'일정관리', '예산/지출', '여행로그'</u>)에서 관리할 수 있음.

<details>
<summary><b>신규여행 만들기</b> (시연 GIF)</summary>
<div markdown="1">

![신규여행만들기1(배)](https://github.com/TripTeller-repository/TripTeller_BE/assets/127278410/50f57dff-9304-4030-a8c6-f40d8c36950d)

![신규여행만들기2(배)](https://github.com/TripTeller-repository/TripTeller_BE/assets/127278410/08734179-7efe-4527-8461-0d69aad8e563)

</div>
</details>
<br>

### ✅ '나의 여행'의 '일정관리'

- <b>일일 UI 카드</b> : 각 카드를 사용하면 해당 날짜의 시간별 계획과 위치를 입력할 수 있음.<br>
- <b>주소 검색</b> : 카카오맵 API를 이용하여 주소를 검색할 수 있음. 장소 이름이 등록된 경우 표시됨. 그렇지 않으면 주소가 표시됨.<br>
- <b>메모</b> : 해당 일정에 대한 메모를 작성할 수 있으며 최대 10자까지 가능함.

<details>
<summary><b>일정관리 - 시간계획표 카드 생성</b> (시연 GIF)</summary>
<div markdown="1">

![일정관리-생성(배)](https://github.com/TripTeller-repository/TripTeller_BE/assets/127278410/c2c63c05-a303-4a55-94e7-c2f158e790aa)

</div>
</details>
<details>
<summary><b>일정관리 - 시간계획표 카드 삭제</b> (시연 GIF)</summary>
<div markdown="1">

![일정관리-삭제(배)](https://github.com/TripTeller-repository/TripTeller_BE/assets/127278410/3ed6e72e-7872-42b0-b00e-e78dc7c52fd5)

</div>
</details>
<br>

### ✅ '나의 여행'의 '예산/지출'

- 입력한 여행 시작 및 종료일에 맞춰 날짜별 지출을 입력할 수 있음.
- 막대 그래프는 입력된 총 예산과 총 비용을 기준으로 동적으로 채워짐.

<details>
<summary><b>예산/지출 - 지출 내역 생성</b> (시연 GIF)</summary>
<div markdown="1">

![지출내역-생성(배)](https://github.com/TripTeller-repository/TripTeller_BE/assets/127278410/a7030b19-ef32-4f47-8e0d-ff340eb31be2)

</div>
</details>
<details>
<summary><b>예산/지출 - 지출 내역 삭제</b> (시연 GIF)</summary>
<div markdown="1">

![지출내역-바(배)](https://github.com/TripTeller-repository/TripTeller_BE/assets/127278410/62ac9d32-2974-481a-bcda-58571726caad)

</div>
</details>
<br>

### ✅ '나의 여행'의 '여행로그'

- 날짜별로 텍스트(최대 100자)와 사진 1개를 삽입할 수 있음.
- 사용자 프로필 아래 일일 시간 계획 카드를 클릭하면 해당 여행 기록으로 이동함(1:1 하이퍼링크).

<details>
<summary><b>여행로그 - 하나의 여행에 대한 기록 작성</b> (시연 GIF)</summary>
<div markdown="1">

![여행로그-작성(배)](https://github.com/TripTeller-repository/TripTeller_BE/assets/127278410/c9dc6376-f1e6-48dc-8ec1-0c0055b85bd6)

</div>
</details>
<details>
<summary><b>여행로그 - 게시물 공개/비공개 전환</b> (시연 GIF)</summary>
<div markdown="1">

![공개비공개](https://github.com/TripTeller-repository/TripTeller_BE/assets/127278410/4bfb1d44-1e38-4ca3-8474-334696f19155)

</div>
</details>
<br>

### ✅ '우리의 여행'에서 공개된 게시물 조회

- 사용자 프로필 아래 일일 시간 계획 카드를 클릭하면 해당 여행 기록으로 이동함(1:1 하이퍼링크).
- 게시물 상세 페이지에서 글 오른쪽 공유 버튼을 누르면 클립보드에 링크가 복사됨.

<details>
<summary><b>일정 카드를 누르면 해당 여행로그로 이동</b> (시연 GIF)</summary>
<div markdown="1">

![우리의여행-일대일](https://github.com/TripTeller-repository/TripTeller_BE/assets/127278410/3907884a-d7c8-4984-96d3-b67007563940)

</div>
</details>

<details>
<summary><b>클립보드 링크 복사 후 붙여넣기</b> (시연 GIF)</summary>
<div markdown="1">

![클립보드링크(배)](https://github.com/TripTeller-repository/TripTeller_BE/assets/127278410/b9dee598-8d6a-4e68-95a4-3c9bf68139bc)

</div>
</details>
<br>

### ✅ 사용자 경험을 높이기 위한 기능

<details>
<summary><b>메인화면 캐러셀로 이미지 슬라이더 구현</b> (시연 GIF)</summary>
<div markdown="1">

![메인화면-캐러셀(배)](https://github.com/TripTeller-repository/TripTeller_BE/assets/127278410/c31ae84c-efc2-4bf4-89ad-66ec72f25087)

</div>
</details>
<details>
<summary><b>화면 우측 하단 버튼 클릭시 스크롤 상단이동</b> (시연 GIF)</summary>
<div markdown="1">

![상단이동(배)](https://github.com/TripTeller-repository/TripTeller_BE/assets/127278410/0730a48d-2830-41ff-99df-f91e33cd0565)

</div>
</details>
<br>

### ✅ 회원정보를 이용한 사용자 기능<br>

- 프로필 이미지 변경
- 닉네임 변경
- 닉네임이 중복된 경우 순차적으로 번호가 추가됨.<br>
  ex) '길동'이라는 닉네임의 회원이 존재할 경우, 다음 회원은 '길동1'이 됨.
- 회원 탈퇴

<details>
<summary><b>닉네임 변경</b> (시연 GIF)</summary>
<div markdown="1">

![닉네임변경(배)](https://github.com/TripTeller-repository/TripTeller_BE/assets/127278410/c9988ef1-2960-4b7a-a18e-bca28fb4d66d)

</div>
</details>

<details>
<summary><b>프로필 사진 변경</b> (시연 GIF)</summary>
<div markdown="1">

![프로필사진변경(배)](https://github.com/TripTeller-repository/TripTeller_BE/assets/127278410/743a9c5c-cab9-4ec1-b2a3-b6f6a406cec1)

</div>
</details>

---

## 참고 링크

<details>
<summary>Mock Data 세팅</summary>
<div markdown="1">

- https://blog.naver.com/r_sense/221351078989
- https://korean.visitkorea.or.kr/detail/rem_detail.do?cotid=e2631a7f-1730-42de-bf2c-d91428d4d606
- https://ddojorica.tistory.com/entry/2305%EC%A0%84%EC%A3%BC%EC%97%AC%ED%96%891%EB%B0%952%EC%9D%BC2%ED%8E%B8
- https://blog.naver.com/nsacseobeo16_/223392729473
- https://blog.naver.com/yunah0218/221242116968
- https://blog.naver.com/ddscsw311/220362985827
- https://hanok.jeonju.go.kr/contents/alleyway3
- https://blog.naver.com/putpleat99/222596287924
- https://blog.naver.com/putpleat99/222603116459
- https://blog.naver.com/r_sense/221351078989

</div>
</details>
<details>
<summary>사이트 제작시 참고한 레퍼런스</summary>
<div markdown="1">

- FLOG : https://github.com/code-bootcamp/Flog_server

- TRIPLE : https://triple.guide/

- Trip Adviser : https://www.tripadvisor.co.kr/

</div>
</details>
<details>
<summary>메인화면 이미지 슬라이더의 벚꽃 GIF</summary>
<div markdown="1">

- 네이버 메인 페이지의 흩날리는 벚꽃 GIF파일을 사용함.

</div>
</details>
