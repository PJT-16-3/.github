
# 🏠 지비(ZIBI) — 청약 정보 웹앱
![zibi_logo] (assets/logo.png)


## 📌서비스 소개
청약 정보를 한눈에 확인하고 가점 계산·선호 설정·맞춤 추천·계좌 연동·지도/상세 조회까지 제공하는 올인원 웹앱입니다.

계좌 연동 및 예치금 현황 시각화(이번 달 납입 여부, 총 납입 횟수, 예치금 달성률)

단계형 청약 가점 계산기(쉬운 질문 흐름 · 항목별 점수 미리보기)

사용자 선호 기반 맞춤형 청약 추천(지역/평수/가격/유형)

청약 목록/상세/즐겨찾기, 당첨 가능성(예측 %) 표시

지도에서 청약 단지 확인(마커 클릭 시 하단 카드)

FAQ(공지) 아코디언 UI

이메일 가입/인증 + 카카오 로그인

PWA 지원(오프라인/자동 업데이트)

- 산의 날씨정보 및 옷차림, 등산로 정보 제공
- 등산 시 사용자의 등산정보 기록
- <b>사용자들이 많이 다닌 등산로</b> 정보 제공
- <b>긴급 신고 기능 서비스</b>
- <b>등산로 이상 신고 서비스</b>

## 💁 프로젝트 소개

### 프로젝트 기간
- 2025.07 ~ 2025.08

### 팀원 소개
|name|position|Github|
|------|---|---|
| 정성훈 | 프론트엔드 | <a href="https://github.com/seonghoon1201"><img alt="정성훈" src="https://github.com/seonghoon1201.png?size=100" width="90" height="90" /></a> |
| 염정우 | 프론트엔드 | <a href="https://github.com/yeomine"><img alt="염정우" src="https://github.com/yeomine.png?size=100" width="90" height="90" /></a> |
| 박준영 | 프론트엔드 | <a href="https://github.com/TTprotocol"><img alt="박준영" src="https://github.com/TTprotocol.png?size=100" width="90" height="90" /></a> |
| 김도현 | 백엔드 | <a href="https://github.com/bikdh1109"><img alt="김도현" src="https://github.com/bikdh1109.png?size=100" width="90" height="90" /></a> |
| 김지민 | 백엔드 | <a href="https://github.com/rlawlals119"><img alt="김지민" src="https://github.com/rlawlals119.png?size=100" width="90" height="90" /></a> |
| 유채현 | 백엔드 | <a href="https://github.com/chaeging"><img alt="유채현" src="https://github.com/chaeging.png?size=100" width="90" height="90" /></a> |
| 이동욱 | 백엔드 | <a href="https://github.com/Leedong-uk"><img alt="이동욱" src="https://github.com/Leedong-uk.png?size=100" width="90" height="90" /></a> |


## 서비스 아키텍처
![시스템구성도](https://github.com/user-attachments/assets/e5c05abe-e4a6-4ac7-9228-7f96d0e26707)


## ✨ 기능 설명
<details>
<summary><b>등산길 이상 신고 기능</b></summary>
<div markdown="1">
<br>
<p><i>등산 중 야생동물, 자연재해 등으로 인한 등산로 이상 발생 시, 사용자가 사진과 함께 등산로 이상 정보를 신고합니다다.</i></p>
<p><i>사용자들은 등산 시 지도에서 다른 사용자들이 신고한 내용을 확인할 수 있습니다.</i></p>
  
![image](https://github.com/Hiking-Planner/.github/assets/56792033/7196d0be-3d6f-4b71-a51a-698a63345180)

</div>
</details>
<details>
<summary><b>긴급 신고 기능</b></summary>
<div>
<br>
<p><i>등산 중 조난 사고 발생 시, 사용자가 sos 버튼을 클릭하면 위치정보와 함께 간편하게 119에 문자신고를 할 수 있습니다.</i></p>
<p><i>사용자 현재 위치에 해당하는 국가지점번호를 계산하여 신고내용에 포함하도록 한다. 구급대원들이 쉽게 위치를 찾을 수 있도록 합니다.</i></p>
  
![image](https://github.com/Hiking-Planner/.github/assets/56792033/d0c8a8bd-2408-4972-94e4-966f20677b24) 
![image](https://github.com/Hiking-Planner/.github/assets/56792033/d26d5cd2-479a-46cc-ab17-2f007cd55499)

</div>
</details>
<details>
<summary><b>많이 간 등산로 제공 기능</b></summary>
<div markdown="1">
<br>
<p><i>사용자들이 등산시작버튼을 누르면 위치정보가 수집되고, 등산종료 버튼을 누르면 경로 정보가 데이터베이스에 저장됩니다.</i></p>
<p><i>각 산 별 등산정보를 활용하여 사용자들이 가장 많이 이용한 등산로 정보를 <유저들이 많이 다닌 등산로>라는 이름으로 제공합니다.</i></p>
  
![image](https://github.com/Hiking-Planner/.github/assets/56792033/451bbcfa-4e76-4c8d-be63-f23fe6a433ab)

</div>
</details>
<details>
<summary>회원가입 및 로그인</summary>
<div markdown="1">
<br>
<p><i>사용자들은 이메일 인증을 통해 회원가입을 할 수 있습니다.</i></p>

![image](https://github.com/Hiking-Planner/.github/assets/56792033/43236185-0527-4e87-bc05-0dbffefd6fb6)

</div>
</details>
<details>
<summary>날씨 및 추천옷차림 정보</summary>
<div markdown="1">
<br>
<p><i>추후 구현</i></p>


</div>
</details>
<details>
<summary>커뮤니티</summary>
<div markdown="1">
<br>
<p><i>추후 구현</i></p>


</div>
</details>

## ✨ 최종발표 자료 
<a href = "https://www.miricanvas.com/v/13bl7xv"> 하이킹플래너 최종발표 자료 </a>
  
## 📱 시연 영상
<i>클릭 시 유튜브로 이동</i>

[![Video Label](http://img.youtube.com/vi/HifUM1FGUK8/0.jpg)](https://youtu.be/HifUM1FGUK8?t=0s)


## Etc
<details>
<summary>Figma</summary>
<div markdown="1">
<br>
  
![image](https://github.com/Hiking-Planner/.github/assets/56792033/e69f5011-870e-4c23-9259-b0680d374d75)
![image](https://github.com/Hiking-Planner/.github/assets/56792033/295d0376-86b2-40e4-b4c1-2c3238a50ef2)
![image](https://github.com/Hiking-Planner/.github/assets/56792033/9f5ecd09-6f65-45e9-8cc2-765dc411207b)

</div>
</details>

<details>
<summary>ERD</summary>
<div markdown="1">
<br>
  
![image](https://github.com/Hiking-Planner/.github/assets/56792033/2397cc7c-751a-442f-96de-97b9489e0c93)

</div>
</details>
<details>
<summary>기능명세서</summary>
<div markdown="1">
<br>
<a href="https://docs.google.com/spreadsheets/d/1uio1x40lJNK0rvMlclpTGyjlhik27eB5/edit?usp=sharing&ouid=117878540187699087371&rtpof=true&sd=true"> 하이킹플래너 기능명세서 바로가기 </a>
</div>
</details>
<details>
<summary>주요 기능 구현방식</summary>
<div markdown="1">
<br>
<a href="https://github.com/Hiking-Planner/HikingPlanner_BE"> 백엔드 레포지토리 readme 바로가기 </a>
<br>
<a href="https://github.com/Hiking-Planner/PythonClusteringSever"> 경로 클러스터링 파이썬 서버 readme 바로가기 </a>
</div>
</details>

