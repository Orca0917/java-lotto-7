# java-lotto-precourse

이 레포지토리는 간단한 로또 게임 시뮬레이션을 구현한 프로젝트입니다. 사용자가 구매 금액을 입력하면 로또 티켓을 생성하고, 당첨 번호와 비교하여 당첨 결과 및 수익을 계산해줍니다.

## 기능명세

1. 로또 구매
    - 사용자의 구매 금액 입력
    - 입력한 금액에 따라 로또 티켓 생성 (장당 1,000원)
    - 당첨 번호 입력

2. 로또 번호 생성
    - 1부터 45 사이의 숫자 중 중복되지 않는 6개의 번호를 임의로 선택
    - 당첨번호는 보너스 번호를 포함하여 생성

3. 당첨 금액 계산
    - 각 티켓을 당첨 번호와 비교하여 당첨 등수를 확인
    - 수령액 계산

4. 결과 출력
    - 등수별 당첨 횟수 계산
    - 당첨 금액을 계산하여 사용자의 수익율 또는 손실율 출력