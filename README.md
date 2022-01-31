# 거위 시뮬레이터
> 몰입캠프 4주차 프로젝트

* 카이스트 오리연못에 서식하는 거위가 주인공인 게임입니다.
* 카이스트 캠퍼스를 탐험하며 거위 동료들을 모을 수 있습니다.
* 하지만 가짜 거위를 건드리면 큰일날지도?

![main](https://user-images.githubusercontent.com/68853120/151886756-dcad0325-2cb7-46cc-a830-6dc0a2b6726c.png)

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

![normal](https://user-images.githubusercontent.com/68853120/151887915-7b5f89a2-0d4a-46a9-a130-8fc9925d57af.png)

일반적인 거위입니다.

#### 스피드 거위

![speedduck](https://user-images.githubusercontent.com/68853120/151887964-df4b16a2-8e70-40ce-af13-db35d07826dd.png)

동료가 되면 플레이어의 이동 속도가 크게 증가합니다.

#### 밀리터리 거위

![milduck](https://user-images.githubusercontent.com/68853120/151888036-ca096de4-ec59-4afd-8b83-376ab892540f.png)

동료가 되면 플레이어가 미사일을 발사할 수 있습니다.

#### 가짜 거위

![badduck](https://user-images.githubusercontent.com/68853120/151888073-389c3286-8e71-49b7-91dd-36305cec2800.png)

거위를 속여서 잡기 위해 제작된 것으로 보이는 가짜 오리입니다. 가까이 가면 거위에 적대적인 필드 보스를 소환합니다.



#### 4. 필드 보스

가짜 거위가 소환하는 적대적인 거대 인공지능 로봇입니다.

![image](https://user-images.githubusercontent.com/68853120/151888101-7d35445b-3c69-43e9-a293-f20fbeee2b5b.png)



