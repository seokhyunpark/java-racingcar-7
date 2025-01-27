# java-racingcar-precourse

## 기능 요구 사항
1. 사용자가 경주할 자동차 이름을 입력
   - 이름은 쉼표`,`로 구분
   - 이름은 5자 이하만 가능
2. 사용자가 몇 번의 이동을 할 것인지 입력
3. 2번에서 입력 받은만큼 시도
   - 0~9 사이의 랜덤 값을 구하고 4 이상인 경우 자동차 전진
   - 자동차의 전진은 `-`로 표기
4. 자동차 경주 완료 후 우승자를 출력
   - 우승자가 여러 명일 경우 `,`로 구분

## 구현할 기능 목록
### 자동차 이름 입력
- [x] 자동차 이름 입력 안내 문구를 출력하는 기능
- [x] 자동차 이름을 입력받는 기능
- [x] 입력된 자동차 이름들을 `,`로 구분하는 기능
- [x] 잘못된 자동차 이름에 대해 예외 처리를 하는 기능
  - [x] 각 자동차 이름의 길이가 5 이하인지 확인하는 기능

### 이동할 횟수 입력
- [x] 이동할 횟수 입력 안내 문구를 출력하는 기능
- [x] 이동할 횟수를 입력받는 기능
- [x] 잘못된 이동 횟수에 대해 예외 처리를 하는 기능
  - [x] 이동 횟수가 자연수인지 확인하는 기능

### 자동차 경주 게임 진행
- [x] 실행 결과 문구를 출력하는 기능
- [x] 이동할 횟수만큼 반복하는 기능
- [x] 0에서 9 사이의 무작위 값을 구하는 기능
- [x] 무작위 값이 4 이상인지 확인하는 기능
- [x] 무작위 값이 4 이상이면 전진하는 기능
- [x] 진행 과정을 출력하는 기능

### 자동차 경주 게임 결과
- [x] 최종 우승자를 판단하는 기능

### 최종 우승자 출력
- [x] 최종 우승자를 출력하는 기능
  - [x] 우승자가 한 명일 경우 출력하는 기능
  - [x] 우승자가 여러 명일 경우 `,`를 사용해 출력하는 기능
