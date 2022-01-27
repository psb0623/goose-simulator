# 거위 시뮬레이터
> 몰입캠프 4주차 프로젝트

* 카이스트 오리연못에 서식하는 거위가 주인공인 게임입니다.
* 카이스트 캠퍼스를 탐험하며 거위 동료들을 모을 수 있습니다.
* 하지만 가짜 거위를 건드리면 큰일날지도?

![main](https://user-images.githubusercontent.com/81062893/151349206-1f10a094-4b8a-43ba-b07e-9bc28e73daa5.PNG)
***

### A. 개발 팀원  
* POSTECH 컴퓨터공학과 19학번 [김민결](https://github.com/KimMingyeol) 
* KAIST 전산학부 19학번 [박수빈](https://github.com/psb0623)  
***

### B. 개발 환경  
* Window 10 64-bit
* Unreal Engine 4.23
* Sketchup Pro 2021
***

### C. 기능 소개

#### 1. 맵

실제 오리연못 주변 건물들을 1:1 스케일로 직접 3D 모델링하였습니다.

![image](https://user-images.githubusercontent.com/81062893/151122001-17812ba4-add1-42aa-b64a-85b6610162dd.png)

언리얼 엔진에서 지형과 식생을 추가하여 완성된 모습은 아래와 같습니다.

![전경](https://user-images.githubusercontent.com/81062893/151349243-c7987b2a-16db-4e14-b6aa-5579524965e7.PNG)

#### 2. 플레이어

- W, A, S, D를 눌러 이동합니다.
- Space Bar를 눌러 점프합니다.
- 마우스 좌클릭으로 총알을 발사합니다.


#### 3. 거위

필드에 등장하는 모든 거위는 동료가 되면 같이 움직이고 같이 공격합니다. 동료가 되면 플레이어에게 특수한 능력을 주는 거위들도 있습니다.

#### 일반 거위

![normal](https://user-images.githubusercontent.com/81062893/151349653-19cf9c7b-ff2f-4d7c-975f-91cc33e82508.PNG)

일반적인 거위입니다.

#### 스피드 거위

![speedduck](https://user-images.githubusercontent.com/81062893/151349670-47ea4645-37ae-4d75-b0cd-2b430e73db65.PNG)

동료가 되면 플레이어의 이동 속도가 크게 증가합니다.

#### 밀리터리 거위

![milduck](https://user-images.githubusercontent.com/81062893/151349717-f1ed7ef6-443d-4a3b-ab85-a9304cfedc8a.PNG)

동료가 되면 플레이어가 미사일을 발사할 수 있습니다.

#### 가짜 거위

![badduck](https://user-images.githubusercontent.com/81062893/151349741-9f8b05a5-2883-4a01-81df-c1ffce53b19c.PNG)

거위를 속여서 잡기 위해 제작된 것으로 보이는 가짜 오리입니다. 가까이 가면 거위에 적대적인 필드 보스를 소환합니다.



#### 4. 필드 보스

가짜 거위가 소환하는 적대적인 거대 인공지능 로봇입니다.

![image](https://user-images.githubusercontent.com/81062893/151123807-3345eb97-dda8-4623-92cb-2ff4e123aee8.png)




