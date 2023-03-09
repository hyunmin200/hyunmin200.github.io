---
title: Don't Clear (첫 프로젝트)

date: 2023-03-02 01:02:00 +09:00
categories: [MyProject]
tag: [project]

toc: true
toc_sticky: true
future: true
---

# Don't Clear
---
저번 년도에 **동아리**에서 만들었던 `Don't Clear`라는 **프로젝트**를 소개하기 위한 글을 적어 봅니다.
## 메인 화면
![메인 화면](/assets/post/DonC/DonCMainScene.png){: width="700" class="normal"}  

메인 화면의 UI는 게임 시작과 게임 종료 그리고 `Bonus 버튼`이 존재하고  
`Don't Clear`의 직역 `못 깬다`라는 텍스트와 **자신이 죽은 횟수**를 알려주는 UI도 존재합니다.  
죽은 횟수 측정은 **PlayerPrefs**을 사용하여 저장하였습니다.

여기서 Bouns버튼을 누르면

# 보너스 화면
![보너스 화면](/assets/post/DonC/DonCBonusScene.png){: width="700" class="normal"}  
여기서 `냠냠냠` 버튼을 누르게 된다면 아래 사진처럼 나옵니다.
![보너스 화면2](/assets/post/DonC/DonCBonusScene2.png){: width="700" class="normal"}  
말 그대로 심심해서 만든 보너스 입니다.

# 게임 화면
---
![게임 화면](/assets/post/DonC/DonCGameScene.png){: width="700" class="normal"}  
**게임 화면**입니다.  
일단 중간에 **플레이어**가 있습니다.  
`조작키`는 ↑, ↓, ←, → 대쉬는 **X**입니다. 
  
## 깃발
![깃발](/assets/post/DonC/DonCPlag.png){: width="350" class="normal"}  
만약 이 깃발에 닿는다면 **세이브**가 됩니다.  
**세이브**는 **JSON**을 사용하여 데이터를 저장하였습니다.  
  
## 탈출구
![탈출구](/assets/post/DonC/DonCExit.png){: width="350" class="normal"}  
이건 **탈출구**이다.   
**탈출구**에 닿으면 `다음 스테이지`로 넘어가거나 `클리어`하게 만들어 놨습니다  
`※주의※`**FakeExit가 존재합니다.**

## ON|OFF 장애물
![ONOFF](/assets/post/DonC/DonCON.png){: width="350" class="normal"}  
![ONOFF](/assets/post/DonC/DonCOFF.png){: width="350" class="normal"}  
이런식으로 `ON|OFF`되는 장애물이 있습니다.

## 죽는 지점들
![죽는 지점](/assets/post/DonC/rrr.png){: width="350" class="normal"}  
이 게임에 이름에 맞게 **죽는 지점**은 `죽으면서` 찾아야 합니다.  
한번 **잘**찾아보길 바랍니다!

# 기술
`기술은 대쉬가 끝!`

## 대쉬
![대쉬](/assets/post/DonC/DonCDash.png){: width="350" class="normal"}  
`뒤에서 흰색 이펙트가 나오면서 순식간에 이동하는 기술!!!`  
쿨타임은 `2초`입니다.
  
### 대쉬 사용 가능 UI
![대쉬 사용 가능](/assets/post/DonC/DonCTrueDash.png){: width="350" class="normal"}  
`대쉬가 사용 가능`하다면 이렇게 UI가 **파란색**으로 `활성화`가 됩니다.

### 대쉬 사용 불가 UI (쿨타임)
![대쉬 사용 가능](/assets/post/DonC/DonCFalseDash.png){: width="350" class="normal"}  
`대쉬 불가 상태`가 된다면 이렇게 UI가 **빨간색**으로 `비활성화`가 됩니다.   
그리고 **쿨타임**을 알려줍니다.

# 넥스트 스테이지 (Next Stage)  
![게임 오버](/assets/post/DonC/DonCNextStage.png){: width="700" class="normal"}  
이런 화면이 뜨면서 `다음 스테이지`로 넘어가게 됩니다.

# 게임 오버 (Game Over)  
![게임 오버](/assets/post/DonC/DonCGameOver.png){: width="700" class="normal"}  
`게임 오버 상태`가 되면 이런 화면이 뜨면서  
`다시 시작`과 `로비`창이 뜹니다.

# 게임 클리어 (Game Clear)
![게임 클리어](/assets/post/DonC/DonCClear.png){: width="700" class="normal"}  
게임을 **클리어**하면 이러한 화면이 나오고 
![게임 클리어](/assets/post/DonC/DonCClear2.png){: width="700" class="normal"}  
`네모`를 **조종**할 수 있는 장소에 오게 됩니다.  
이 장소에서 네모를 움직여 `Bye!`로 간다면 **게임종료**가 되고  
이 장소에서 네모를 움직여 `로비`로 간다면 **로비로 이동**이 됩니다.

이상으로 TMHD 교내 동아리에서 만든  
간단한 플랫포머 게임인 `Don't Clear`의 소개를 마치겠습니다.

<details>
<summary>접힌 말</summary>
<div markdown="1">
  
이번 프로젝트하면서 `팀원들과 어떤 식으로 기획`을 할 줄 몰라서 *막무가내*로 했던 경험  
개발을 하면서 `협업을 어떤식으로 할 줄 잘 몰라서` 코드가 꼬인 경험  
실수로 `변수의 이름을 잘못 적어버린 경험` 등등
이번 프로젝트를 하면서 많은 **힘든 일**들이 있었지만  
이것을 `계기이자 경험`으로 삼아 더 나은 내가 되도록 **노력**을 해야 할 것 같다.
이번 프로젝트를 열심히 해 준 팀원들에게 **감사의 말**을 전하고 마친다.
  
</div>
</details>