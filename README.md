# jwp-racingcar


## *DOMAIN*
 + CAR
    + 자동차 진행길이
    + 자동차 이름
      + 이름은 1자이상, 5자 이하.
      + 중복 X
    + 자동차 위치
      + 같은위치에서 출발.
      + 0이상의 위치
   + 자동자는 값에따라 이동
     + 4이상이면 전진
     + 3이하이면 멈춤


 + CarGame
   + 시도 횟수 존재
   + 숫자 생성 전략 존재(0~9사이의 값을 랜덤으로 생성)
   + 우승자 반환(1명 이상일수도 있음.)
  
  
 + Max
    + 최대진행길이 찾기
 
 + Winner
    + Max 길이에 대한 우승자 이름 리스트 반환

 



## *VIEW*


+ INPUT
   + 경주할 자동차 이름을 입력
   + 쉼표로 구분된 이름을 입력하는지 검증
      + 1대 이상 100대 이하의 자동차를 입력하는지 검증
      + 입력으로 들어온 이름의 앞,뒤 공백은 제거
  + 시도할 횟수를 입력 (1<=try<=100)
 
  
+ OUTPUT
   + 실행 결과 출력
   + 최종 우승자 출력



## *CONTROLLER*
+ GAMECONTROLLER
