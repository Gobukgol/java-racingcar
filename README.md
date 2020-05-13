# 자동차 경주 게임
## 진행 방법
* 자동차 경주 게임 요구사항을 파악한다.
* 요구사항에 대한 구현을 완료한 후 자신의 github 아이디에 해당하는 브랜치에 Pull Request(이하 PR)를 통해 코드 리뷰 요청을 한다.
* 코드 리뷰 피드백에 대한 개선 작업을 하고 다시 PUSH한다.
* 모든 피드백을 완료하면 다음 단계를 도전하고 앞의 과정을 반복한다.

## 온라인 코드 리뷰 과정
* [텍스트와 이미지로 살펴보는 온라인 코드 리뷰 과정](https://github.com/next-step/nextstep-docs/tree/master/codereview)



## 기능 구현 목록

1. 자동차 대수와 시도할 회수를 입력받는 Input 뷰 클래스
2. 실행 결과를 받아 출력하는 Output 뷰 클래스
3. 자신의 위치를 가지고 있는 Car 클래스
4. 경주에 참여하는 Car를 관리하는 ParticipateCars 클래스
5. 각 시도 결과를 관리하는 PhaseResult 클래스
6. 전체 게임 결과를 관리하는 GameResult 클래스
7. Input으로 받은 정보로 게임을 시작하는 RacingGame 클래스
8. Input으로 받은 정보를 Game을 진행하기 위해 맞는 타입으로 변환하고 validate까지 하는 InputValueDto 클래스

