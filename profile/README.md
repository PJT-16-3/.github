
# 🏠 지비(ZIBI) — 청약 정보 웹앱
![zibi_logo](assets/logo.png)


## 📌서비스 소개
- 청약 정보를 한눈에 확인하고 가점 계산·선호 설정·맞춤 추천·계좌 연동·지도/상세 조회까지 제공하는 올인원 웹앱입니다.
- 계좌 연동 및 예치금 현황 시각화(이번 달 납입 여부, 총 납입 횟수, 예치금 달성률)
- 단계형 청약 가점 계산기(쉬운 질문 흐름 · 항목별 점수 미리보기)
- 사용자 선호 기반 맞춤형 청약 추천(지역/평수/가격/유형)
- 청약 목록/상세/즐겨찾기, 당첨 가능성(예측 %) 표시
- 지도에서 청약 단지 확인(마커 클릭 시 하단 카드)
- AQ(공지) 아코디언 UI
- 이메일 가입/인증 + 카카오 로그인
P- WA 지원(오프라인/자동 업데이트)


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


## 시스템 아키텍처
![시스템아키텍처](assets/architecture.png)


## ✨ 기능 설명
<details>
<summary><b>계좌 등록 기능</b></summary>
<div markdown="1">
<br>
<p><i>메인 페이지에서 실제 청약 계좌를 등록할 수 있습니다.</i></p>
<p><i>예치금 충족률에 따라 캐릭터가 바뀌며, 원하는 평수대에 따른 예치금 충족률을 한 눈에 파악할 수 있습니다..</i></p>
  
![image]()
</div>
</details>

<details>
<summary><b>가점 계산기 기능</b></summary>
<div>
<br>
<p><i>보다 쉬운 질문들을 통해 가점을 계산할 수 있습니다.</i></p>
<p><i>회원가입 때 받은 개인 정보들과, 간단한 6가지의 질문들을 통해 사용자의 가점을 계산할 수 있습니다.</i></p>
  
![image]() 
![image]()

</div>
</details>

<details>
<summary><b>선호 정보 설정 및 청약 추천 기능</b></summary>
<div markdown="1">
<br>
<p><i>사용자가 본인의 선호 정보를 설정하여 그 선호 정보에 맞는 청약을 청약 당첨 확률이 높은 순으로 추천해 줍니다.</i></p>

![image]()

</div>
</details>

<details>
<summary><b>당첨 확률 계산 기능</b></summary>
<div markdown="1">
<br>
<p><i>사용자의 계좌 정보, 가점 정보 등을 토대로 각 청약마다의 당첨 확률을 계산하여 제공합니다.</i></p>
<p><i>히스토그램과 KNN 모델을 합하여 당첨 확률을 계산하여 보여줍니다.</i></p>
  
![image]()

</div>
</details>

<details>
<summary><b>순위 계산 기능</b></summary>
<div markdown="1">
<br>
<p><i>특정 청약에 대한 사용자의 순위가 무엇인 지 계산하여 보여줍니다.</i></p>

![image]()

</div>
</details>

<details>
<summary><b>청약 공고 리스트 보기 기능</b></summary>
<div markdown="1">
<br>
<p><i>사용자들은 현재 올라와 있는 모든 청약 공고를 한 눈에 볼 수 있습니다.</i></p>
<p><i>특정 청약 공고 자세히 보기 버튼을 누르면, 해당 청약 공고의 평수, 가격, 위치, 즐겨찾기 수, 조회 수, 당첨 확률, 순위 계산, 청약일정, 주변 인프라 정보 등 해당 청약에 관련된 모든 정보들을 볼 수 있습니다.</i></p>

![image]()

</div>
</details>

<details>
<summary><b>지도 기능</b></summary>
<div markdown="1">
<br>
<p><i>지도 기능을 통해 현재 올라온 모든 청약 공고에 대한 위치를 바로 알 수 있습니다.</i></p>
<p><i>필터 기능을 통해 원하는 지역의 공고를 바로 볼 수 있습니다.</i></p>

![image]()

</div>
</details>

<details>
<summary><b>달력 기능</b></summary>
<div markdown="1">
<br>
<p><i>달력에 즐겨찾기 한 공고들의 청약 공고 일정을 바로 확인할 수 있습니다.</i></p>

![image]()

</div>
</details>

<details>
<summary><b>즐겨찾기 기능</b></summary>
<div markdown="1">
<br>
<p><i>청약 공고를 보며 관심있는 공고에 즐겨찾기를 하여 즐겨찾기 한 공고를 모아 볼 수 있습니다.</i></p>

![image]()

</div>
</details>

<details>
<summary><b>달력 기능</b></summary>
<div markdown="1">
<br>
<p><i>달력에 즐겨찾기 한 공고들의 청약 공고 일정을 바로 확인할 수 있습니다.</i></p>

![image]()

</div>
</details>

## ✨ 최종발표 자료 
<a href = "https://www.miricanvas.com/"> 지비 최종발표 자료 </a> -> 링크 다시 걸기
  
## 📱 시연 영상
<i>클릭 시 유튜브로 이동</i>

[![Video Label](http://img.youtube.com/vi/HifUM1FGUK8/0.jpg)](https://youtu.be/HifUM1FGUK8?t=0s) -> 올리고 수정


## Etc
<details>
<summary>Figma</summary>
<div markdown="1">
<br>
  
![image](assets/ZIBI_Figma.png)

</div>
</details>

<details>
<summary>ERD</summary>
<div markdown="1">
<br>
  
![image](assets/16반_3팀_ZIBI_ERD_Diagram.png)

</div>
</details>


