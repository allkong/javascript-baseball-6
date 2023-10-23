# ⚾ 구현할 기능 목록

## 1️⃣ 게임 시작
- 게임 시작 문구 출력

## 2️⃣ 컴퓨터가 1에서 9까지 서로 다른 임의의 수 3개 선택
- `@woowacourse/mission-utils`의 `Random` 및 `Console` API를 사용하여 구현

## 3️⃣ 사용자 입력
- 입력값이 유효한지 확인
  - 1부터 9까지 서로 다른 수로 이루어진 3자리의 수
- 사용자가 잘못된 값을 입력하면 예외 발생시켜 애플리케이션 종료

## 4️⃣ 사용자가 입력한 숫자와 컴퓨터가 선택한 숫자를 비교
- 같은 수가 같은 자리에 있으면 스트라이크, 다른 자리에 있으면 볼, 같은 수가 전혀 없으면 낫싱
- `3스트라이크`면 정답, 그 외는 오답

## 5️⃣ 결과 출력
- 오답일 때
  - 사용자가 입력한 수에 대한 결과를 출력
  - 사용자가 숫자를 재입력 -> 3️⃣으로 돌아가기
- 정답일 때
  - 결과 및 정답 문구 출력

## 6️⃣ 게임 종료
- 사용자가 정답을 맞추면 게임 새로 시작/종료 중 선택 문구 출력
- 사용자가 1과 2 중 하나의 수를 입력
  - 게임 새로 시작(1) 선택 시 게임 시작으로 돌아감 -> 1️⃣로 돌아가기
  - 게임 종료(2) 선택 시 완전히 종료