# Portfolio

---

## 1. Parking
Spring FrameWork를 사용해 프로젝트를 진행
서울 열린데이터광장에서 주차장 API 정보를 받아 주소검색을 통해 주차장의 세부정보를 가져와 현재 주차할 수 있는 공간을 체크를 할 수있는 웹
(가상 결제도 가능 임의적으로 가상의 사업자DB를 만들어 사용) - 상용목적이 아닌 공부목적
DB서버는 AWS를 가용 현재는 프리웨어 만료로인해 사용중지

* [Parking pdf 링크](https://github.com/YoonYeoSong/YoonYeoSong.github.io/blob/master/pdf/Semi-Project.pdf)
* [github 주소](https://github.com/YoonYeoSong/ParkingSpring)

- 사용 기술 및 툴
  - JAVA, JS, HTML, Jquery, CSS, BootStrap4, JSP, SpringFrameWork, AWS(ubuntu), Tomcat 8.5, Git, Oracle, OpenAPI(REST or JS)
  - Ecripes, vsCode, git Bash, SQL Developer, window10
<img src="images/mainPage.png?raw=true"/>
<img src="images/searchPage.png?raw=true"/>
<img src="images/reviewPage.png?raw=true"/>
<img src="images/myPage1.png?raw=true"/>
<img src="images/myPage2.png?raw=true"/>

---


## 2. Food

Java, Java Swing을 사용하여 기본적인 어플리케이션 구현
* [github 주소](https://github.com/YoonYeoSong/food_KH)
<img src="images/food.gif?raw=true"/>

---
## 3. VR기반 모션인식을 이용한 실시간 전략체스 게임
VR콘텐츠를 즐기기 위해 HMD를 착용핛 경우, 실제 키보드와 맀우스를 볼 수 없어 조작이 불편하고 컨트롤이 제한적인 점을 보완하기 위해 모션인식 센서(LeapMotion)를 이용하여 VR콘텐츠의 핵심인 몰입도를 극대화 시킨 체스 게임을 개발하였습니다. 

- 중요 구현 기술
  - Photon Server를 이용하여 실시갂으로 체스게임을 할 수 있도록 구현하였고, 체스 말을 컨트롤 핛 수 있는 깃발을 제어하여 턴 방식으로 게임을 짂행 핛 수 있게 구현하였습니다.
  - Raycast를 이용하여 체스 말이 이동핛 수 있는 범위를 체크하고, LeapMotion으로 체스 말의 깃발을 잡아 컨트롤 할 수 있도록 구현하였습니다. 
 
  - OculusRift SDK를 연동하고,어지러움을 최소화하기 위해 부드러운 카메라 이동처리 구현과 화려한 캐릭터 애니메이션과 파티클을 사용해 몰입도를 향상시켰습니다. 
   - 체스 게임에 기본 적인 규칙들을 적용하여, 킹을 잡을 경우 승리하게 됩니다. 
- 사용 기술 및 툴
  - VS 2015, Unity3D, Photon Server, OculusRift, LeapMotion

<img src="images/c0.png?raw=true"/>
<img src="images/c1.png?raw=true"/>
<img src="images/c3.png?raw=true"/>
<img src="images/ccc.gif?raw=true"/>


---
## 4. VR 집현전
2015년 한글날 특전 세종문화회관 전시 작품
한글날 우리나라 한글이 위대하다는 것을 널리 알리는 목적으로 만들어진 어플리케이션
- 중요 구현 기술
  - 구글카드보드지를 이용하여, 유니티 사용하여 어플리케이션 개발 
  
<img src="images/vrPro1.png?raw=true"/>
<img src="images/vrPro2.png?raw=true"/>

---
## 5. Paint Girl
닌텐도 스플래툰과 모방하여 공부목적으로 만든 어플리케이션
페인트를 이용해 땅을 더 많이 칠한 사람이 승리하는 게임

- 중요 구현 기술
  - Singleton 패턴을 이용
  - Json파싱을 이용하여 각 몬스터와 HP, 공격력등 적용
  - 파티클을 이용하여 바닥이 칠해지는 파티클 생성
  - Git을 이용한 협업
- 사용 기술 및 툴
  - VS 2015, Unity3D, Json
  
<img src="images/p1.png?raw=true"/>
<img src="images/p2.png?raw=true"/>
<img src="images/p3.png?raw=true"/>
<img src="images/paintG.gif?raw=true"/>

---
## 6. Flee or Face
1인칭 3D 게임, 최대 8명, 전체 인원의 50%를 랜덤으로 뽑아서 좀비로 시작하고 주기적으로 좀비와 사람이 바뀌는 멀티 플레이 LAN 게임
키보드와 xbox컨트롤러 사용가능
킨텍스 R&D 대전 참가 기간 16/11/17 ~ 16/11/19
* [github 주소](https://github.com/OhRockInJourney/FleeOrFace)

- 중요 구현 기술
  - C# UDP 통신을 이용
  - Git을 이용한 협업
- 사용 기술 및 툴
  - VS 2015, Unity3D, OculusRift

<img src="images/f0.png?raw=true"/>
<img src="images/f1.png?raw=true"/>
<img src="images/fg.gif?raw=true"/>

---
# 7. 메탈슬러그(모작-학습목표)
SNK에서 제작한 횡스크롤 액션 아케이트 게임인 메탈슬러그를 WinAPI로 모작하였습니다(간단하게 모작하여 학습)
처음 접하는 winAPi이기 때문에 화면 깜빡임 해결이 가장 어려웠습니다. 이 과정에서 더블 버퍼링에 대해 공부하게 되었습니다.

- 중요 구현 기술
  - Singleton 패턴을 적용
  - 플레이어의 상체와 하체를 나누어 자연스러운 움직임을 구현
  - 2D WinAPI기반 윈도우 메시지 활용
  - 더블 버퍼링
  - Git을 이용한 협업
  
- 사용 기술 및 툴
  - VS 2015, WinAPI

<img src="images/metal.png?raw=true"/>
<img src="images/metal1.png?raw=true"/>

--
## 8. EBS 초목달(데모)
(주)스** 회사에서 국가에서 진행하는 국가근로장학생으로 4개월간 다니며 EBS 초등영어 어플리케이션 데모 버전을 개발

- 중요 구현 기술
  - Swipe와 Scoll을 부드럽게 구현
  - 원작이 플래쉬여서 모바일로 옮겨와 동영상으로 교체
- 사용 기술 및 툴
  - VS 2015, Unity3D


<img src="images/eng1.png?raw=true"/>
<img src="images/eng2.png?raw=true"/>

--
---
<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->
