# 🌸TripTeller (트립텔러)

> **"당신의 여행이 우리의 이야기가 되는 공간"**

> "여러분의 여행을 흥미로운 이야기로 바꿀 준비가 되셨나요?<br>
> 지금 여행을 시작하고, 트립텔러와 이야기를 공유하세요."

> <b>https://www.trip-teller.com/</b>

![리드미최상단](https://github.com/TripTeller-repository/TripTeller_BE/assets/127278410/b352ffe2-4031-4e95-91e8-544906929139)

---

## 🔷 바로가기

- [서비스 소개](#서비스-소개)<br>
- [프로젝트 개요](#프로젝트-개요)<br>
- [스토리보드](#스토리보드)<br>
- [페이지 구성](#페이지-구성)<br>
- [기능 설명](#기능-설명)<br>

---

## 🔷 서비스 소개

나만의 여행 일지를 기록하고 다른 사람들과 공유하는 서비스

- 여행 전 여행을 계획하고, 다녀온 여행을 기록하는 '나의 여행'과 다른 사람이 공유한 여행을 감상할 수 있는 '우리의 여행' 서비스가 있다.
  - **나의 여행**
    - 요일, 장소, 시간별로 여행을 계획할 수 있다.
    - 지출 예산을 설정하고 항목별 지출을 관리할 수 있다.
    - 계획을 바탕으로 여행 이야기를 작성할 수 있다.
    - ‘**지난 여행**’ : 본인이 작성한 게시물이 있는 카테고리
  - **우리의 여행**
    - 작성한 여행 이야기를 다른 사람들과 공유할 수 있다.

---

## 🔷 프로젝트 개요<br>

- <b>진행 기간</b><br>

  - 1차 : 기획 및 개발 (24.04.01 ~ 24.04.19) [3주]<br>
  - 2차 : 리팩토링 (24.06.01 ~24.06.15) [2주]<br>

- <b>진행 인원 및 역할</b><br>

  - 6명 (프론트엔드 4명, 백엔드 2명)<br>
  - 프론트엔드 : 이보미, 손민혁, 임기택, 이유림<br>
  - 백엔드 : 이가린, 문채영<br>

- <b>관련 링크</b>

  - 노션 페이지 :
  - Swagger 배포 문서 :
  - 포지션별 Github ReadMe
    - 프론트엔드 : https://github.com/TripTeller-repository/TripTeller_FE
    - 백엔드 : https://github.com/TripTeller-repository/TripTeller_BE

- <b>기술 스택</b>
  - 프론트엔드 : ReactJS, Vite, JavaScript
  - 백엔드 : NestJS, MongoDB, TypeScript
  - 배포 : AWS S3, Route53, Cloudfront, EC2

---

## 🔷 스토리보드

## ![스토리보드](https://github.com/TripTeller-repository/.github/assets/127278410/bb426e8c-15d9-44e9-b111-243b1bf96a7e)

## 🔷 페이지 구성

|                                                                                    메인화면<br>(/)                                                                                    |                                                                               나의여행<br>(/mytrip)                                                                                |
| :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|          <div style="text-align: center;">[![Main screen](https://github.com/TripTeller-repository/.github/assets/127278410/80408008-ed98-47ee-897d-32ee115a09b9)](#)</div>           |           <div style="text-align: center;">[![My Trip](https://github.com/TripTeller-repository/.github/assets/127278410/7418df7b-7844-4d7f-a8b3-f8dc44062966)](#)</div>           |
|                                                  <b><div style="text-align: center;">나의 여행 [일정관리] <br>(/maketrip)</div></b>                                                   |                                                  <b><div style="text-align: center;">나의 여행 [예산/지출]<br>(/mytrip)</div></b>                                                  |
| <div style="text-align: center;">[![My Travel-Itinerary Management](https://github.com/TripTeller-repository/.github/assets/127278410/0d89000b-be41-46c6-a13f-e7db5d60731a)](#)</div> | <div style="text-align: center;">[![My Trip - Budget Management](https://github.com/TripTeller-repository/.github/assets/127278410/9f4e5bf4-cdf4-4d17-acbb-46690ee840b1)](#)</div> |
|                                                   <b><div style="text-align: center;">나의 여행[여행로그]<br>(/maketrip)</div></b>                                                    |                                                        <b><div style="text-align: center;">Our Trip<br>(/ourtrip)</div></b>                                                        |
|      <div style="text-align: center;">[![My Travel-Travel Log](https://github.com/TripTeller-repository/.github/assets/127278410/a5d343df-3b49-401e-8cde-32343b4cf830)](#)</div>      |          <div style="text-align: center;">[![Our Trip](https://github.com/TripTeller-repository/.github/assets/127278410/669a96c4-e73a-4511-836f-2e99019734d7)](#)</div>           |
|                                                           <b><div style="text-align: center;">로그인<br>(/login)</div></b>                                                            |                                                        <b><div style="text-align: center;">회원가입<br>(/signup)</div></b>                                                         |
|             <div style="text-align: center;">[![Login](https://github.com/TripTeller-repository/.github/assets/127278410/8ea939ce-1d1c-4ba4-970f-853ed7d3f172)](#)</div>              |           <div style="text-align: center;">[![Sign up](https://github.com/TripTeller-repository/.github/assets/127278410/cd37ac9d-8c71-42bf-bd27-6b1a5813be07)](#)</div>           |

---

## 🔷 기능 설명

<details>
<summary>게시물 공개/비공개 전환</summary>
<div markdown="1">

![공개비공개](https://github.com/TripTeller-repository/TripTeller_BE/assets/127278410/4bfb1d44-1e38-4ca3-8474-334696f19155)

</div>
</details>
<details>
<summary>로그인</summary>
<div markdown="1">

![로그인(배)](https://github.com/TripTeller-repository/TripTeller_BE/assets/127278410/dbdb50c7-4ab3-496b-8882-febbc8f46510)

</div>
</details>
<details>
<summary>카카오로그인</summary>
<div markdown="1">

![카카오로그인(배)](https://github.com/TripTeller-repository/TripTeller_BE/assets/127278410/4a798db6-0792-43cd-9b06-4a441cef2347)

</div>
</details>
<details>
<summary>로그아웃</summary>
<div markdown="1">

![로그아웃(배)](https://github.com/TripTeller-repository/TripTeller_BE/assets/127278410/5edc9b52-7373-4cdb-9fae-cdedfc961a61)

</div>
</details>
<details>
<summary>회원가입</summary>
<div markdown="1">

![회원가입(배)](https://github.com/TripTeller-repository/TripTeller_BE/assets/127278410/c57e7fd3-5e9a-4f5c-9031-ed2ed8c97767)

</div>
</details>
<details>
<summary>신규여행 만들기</summary>
<div markdown="1">

![신규여행만들기1(배)](https://github.com/TripTeller-repository/TripTeller_BE/assets/127278410/50f57dff-9304-4030-a8c6-f40d8c36950d)

![신규여행만들기2(배)](https://github.com/TripTeller-repository/TripTeller_BE/assets/127278410/08734179-7efe-4527-8461-0d69aad8e563)

</div>
</details>
<details>
<summary>닉네임 변경</summary>
<div markdown="1">

![닉네임변경(배)](https://github.com/TripTeller-repository/TripTeller_BE/assets/127278410/c9988ef1-2960-4b7a-a18e-bca28fb4d66d)

</div>
</details>
<details>
<summary>메인화면 캐러셀</summary>
<div markdown="1">

![메인화면-캐러셀(배)](https://github.com/TripTeller-repository/TripTeller_BE/assets/127278410/c31ae84c-efc2-4bf4-89ad-66ec72f25087)

</div>
</details>
<details>
<summary>상단이동</summary>
<div markdown="1">

![상단이동(배)](https://github.com/TripTeller-repository/TripTeller_BE/assets/127278410/0730a48d-2830-41ff-99df-f91e33cd0565)

</div>
</details>
<details>
<summary>여행로그 작성</summary>
<div markdown="1">

![여행로그-작성(배)](https://github.com/TripTeller-repository/TripTeller_BE/assets/127278410/c9dc6376-f1e6-48dc-8ec1-0c0055b85bd6)

</div>
</details>
<details>
<summary>우리의여행 일대일</summary>
<div markdown="1">

![우리의여행-일대일](https://github.com/TripTeller-repository/TripTeller_BE/assets/127278410/3907884a-d7c8-4984-96d3-b67007563940)

</div>
</details>
<details>
<summary>일정관리 삭제</summary>
<div markdown="1">

![일정관리-삭제(배)](https://github.com/TripTeller-repository/TripTeller_BE/assets/127278410/3ed6e72e-7872-42b0-b00e-e78dc7c52fd5)

</div>
</details>
<details>
<summary>일정관리 생성</summary>
<div markdown="1">

![일정관리-생성(배)](https://github.com/TripTeller-repository/TripTeller_BE/assets/127278410/c2c63c05-a303-4a55-94e7-c2f158e790aa)

</div>
</details>
<details>
<summary>지출내역 바</summary>
<div markdown="1">

![지출내역-바(배)](https://github.com/TripTeller-repository/TripTeller_BE/assets/127278410/62ac9d32-2974-481a-bcda-58571726caad)

</div>
</details>
<details>
<summary>지출내역 생성</summary>
<div markdown="1">

![지출내역-생성(배)](https://github.com/TripTeller-repository/TripTeller_BE/assets/127278410/a7030b19-ef32-4f47-8e0d-ff340eb31be2)

</div>
</details>
<details>
<summary>클립보드 링크</summary>
<div markdown="1">

![클립보드링크(배)](https://github.com/TripTeller-repository/TripTeller_BE/assets/127278410/b9dee598-8d6a-4e68-95a4-3c9bf68139bc)

</div>
</details>
<details>
<summary>프사 변경</summary>
<div markdown="1">

![프로필사진변경(배)](https://github.com/TripTeller-repository/TripTeller_BE/assets/127278410/743a9c5c-cab9-4ec1-b2a3-b6f6a406cec1)

</div>
</details>
