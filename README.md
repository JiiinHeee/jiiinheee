# IT's B team - Shooting Game


### 1. 프로젝트 개요 및 목표
- JAVA를 활용한 고전적 슈팅게임 구현
- 기존의 슈팅 게임에 자유도를 높여 사용자 설정의 폭을 넓히고자 함



### 2. 프로젝트 기능 소개
#### 기능적
- 키패드로 기본 이동
- Space를 사용해 탄환 발사(적 처치) / 탄환에 부딪힐 시 게임 오버 구현
- 게임 진행에 필요한 장애물 구현
- 적이 발사한 탄환에 맞거나 장애물에 부딪혔을 때 게임이 종료됨.


#### 비기능적
- 사용자의 오류를 최소화 하기 위해 경고창 및 뒤로가기를 제공
- 팝업창 또는 웹사이트의 형태로 제작
- 배경음악 및 효과음 적용



### 3. 프로젝트 제작 기간
2021년 4월 ~ 2021년 11월



### 4. 참여한 부분 및 역할
- 게임 타이틀 및 이미지 제작
- 플레이어의 아이템 구현
- 참고자료 탐색
- 보고서 작성
<br>
<br>

![shooting_game_git](https://user-images.githubusercontent.com/115795005/210363465-f6d70f08-dc41-4e37-b75a-5f0780f97e90.png)
1. Enter키를 누르면 게임 설명단계로 이동한다
<br>
<br>
    

![shooting_game_explain](https://user-images.githubusercontent.com/115795005/210366111-97206da6-3ed4-482e-8a1a-bbedbafa54ce.png)
2. 게임설명창이 3초동안 유지 될 수 있도록 구현
<br>
<br>



![shooting_game_playing](https://user-images.githubusercontent.com/115795005/210367272-91386c06-f15f-4d7f-b1df-3f94cda80d74.png)
3. 공격수가 플레이어 방향으로 날아오도록 기능 적용. 'private int delay = 15;'의 함수가 쓰이며 값이 클수록 공격수의 움직임이 느려진다. <br>
4. 공격수가 날아옴과 동시에 탄환이 공격을 할 수 있도록 구현 <br>
5. 플레이어의 공격을 받을 시 녹색 게이지 바가 줄어든다 <br>
<br>



![shooting_game_playing2](https://user-images.githubusercontent.com/115795005/210369043-aed10cf9-2c14-4482-944c-6519f82ce19b.png)
6. 플레이어는 키보드(a-왼쪽, d-오른쪽, s-아래, w-위)를 이용하여 움직임이 가능하도록 구현 <br>
7. space바를 누를 시 장애물을 공격할 수 있는 무기 구현 <br>
8. 장애물 처치시 1000점씩 점수를 얻을 수 있다 <br>
9. 공격수에게 공격을 받았을 때 녹색 게이지 바가 줄어든다 <br>
<br>


![game_end](https://user-images.githubusercontent.com/115795005/210369091-467ffa41-6c18-472a-b0b2-a5cb7bc4e525.png)
10) 게이지 바가 모두 닳았을 때 'Press R to restart'라는 문구가 뜨며, 'R'키를 눌렀을 시 게임 재시작 <br>
