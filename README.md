# 미션 - 자동차 경주 게임
## 🏎 구현 기능 목록
### Game System
- [ ] 게임에 참여하는 `Car`들의 이름을 입력받는 기능
  - [ ] [예외] (이름이 5글자 이내가 아닐 경우) 에러 메시지 출력 후 입력을 다시 받는 기능
- [ ] 게임에 참여하는 `Car Entry`를 생성하는 기능
- [ ] `Car`들을 몇 회 이동시킬 것인지 입력받는 기능
  - [ ] [예외] (입력이 음이 아닌 정수가 아닐 경우) 에러 메시지 출력 후 입력을 다시 받는 기능
- [ ] `Car`들이 1회 이동할 때마다, 진행 상황을 콘솔에 출력하는 기능
- [ ] 게임 종료 후 최종 우승자를 콘솔에 출력하는 기능
  - [ ] 우승자가 여러 명일 경우, 쉼표(,)를 이용하여 구분함
### Car
- [x] 임의의 수를 생성하여 그 결과에 따라 전진, 또는 정지하는 기능
- [ ] 현재 위치를 콘솔에 출력하는 기능
### Car Entry
- [x] 게임에 참여하는 `Car`들을 저장하는 기능
- [x] 저장된 `Car`들에게 일괄적으로 임의의 전진/정지를 명령하는 기능
  - [x] 이 때, 전진/정지는 각각의 `Car` 객체가 결정함.
- [ ] `Car`들의 현재 위치를 콘솔에 차례로 출력하는 기능
- [ ] 가장 많이 이동한 `Car`(들)을 출력(output)하는 기능