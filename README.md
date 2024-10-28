# java-racingcar-precourse
: 초간단 경주 게임 구현

</br>

## 기능 목록
- **사용자 문자열 입력1**  
   - `camp.nextstep.edu.missionutils.Console`의 `readLine()`을 활용해 경주할 자동차 이름 입력
   - 자동차 이름은 쉼표(,)로 구분. 
   - 자동차 이름은 5자 이하로만 가능.

- **사용자 문자열 입력2**
    - 시도할 횟수 입력

- **자동차 기능1**
    - `camp.nextstep.edu.missionutils.Randoms`의 `pickNumberInRange()`를 활용해 랜덤값 추출
    - 전진하는 조건 : 0에서 9사이 무작위 값을 구한 후, 값이 4이상일 경우. 
    

- **자동차 기능2**
    - `camp.nextstep.edu.missionutils.Randoms`의 `pickNumberInRange()`를 활용해 랜덤값 추출
    - 멈추는 조건 : 0에서 9사이 무작위 값 구한 후, 값이 4 미만일 경우. 

- **출력1**  
    - 차수별 실행 결과 출력 : 전진하면 '-'추가

- **출력2**
    - 경주 게임을 완료한 후, 우승자 출력
    - 이때, 우승자가 한 명 이상인 경우 쉼표(,)를 이용하여 구분

- **예외 처리: `IllegalArgumentException`**  
    - 자동차 이름이 5자 초과인 경우가 있을 경우
    - 자동차 이름이 동일한 경우
    - 자동차 이름이 공백으로 주어질 경우
    - 시도 횟수가 숫자가 아닌 경우
    - 시도 횟수가 양수가 아닌 경우

- **테스트 코드: 자동차**
    - 전진 기능이 제대로 작동하는지 여부
    - 출력 기능이 제대로 작동하는지 여부

- **테스트 코드: 메인**
    - 기본 기능 (우승자가 1명인 경우)
    - 기본 기능 (우승자가 여러 명인 경우)
    - 자동차 이름이 5자 초과인 경우
    - 자동차 이름이 동일한 경우
    - 자동차 이름에 공백이 있는 경우
    - 시도 횟수가 숫자가 아닌 경우
    - 시도 횟수가 양수가 아닌 경우