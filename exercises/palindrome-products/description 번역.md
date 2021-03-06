대칭수(palindromic number)는 그 수를 뒤집어도 똑같은 수를 말합니다. 예를 들어 `121`는 대칭수이며, `112`는 대칭수가 아닙니다.

대칭수의 정의처럼, 우리는 회문곱(palindrome product)을 정의할 수 있습니다.

회문곱은 정수 `a`와 `b`의 곱셉으로, 그 결과는 대칭수 `c`입니다. 즉 `a * b = c`이고, 그 결과인 `c`가 대칭수인 것입니다.(이때 `a`와 `b` 가 꼭 대칭수일 필요는 _없습니다_)

예를 들어, 대칭수 9009을 회문곱으로 나타내면: `91 * 99 = 9009`.

회문곱은 보통(그리고 아주 흔히) 여러 쌍으로 표현할 수 있습니다. 예를 들어, 대칭수 `9`는 `(1, 9)`, `(3, 3)`, 그리고 `(9, 1)` 3가지 요소로 표현됩니다.

정수 범위가 주어지면, 범위 내에서 최소 / 최대 회문곱과 모든 요소들을 출력하는 프로그램을 작성해주세요.

## 예시 1

범위 `[1, 9]`가 주어진 경우 (두 수 모두 포함)...

최솟값은 `1`이며, 그 요소는 `(1, 1)`입니다.
최댓값은 `9`이며, 그 요소들은 `(1, 9)`, `(3, 3)`, `(9, 1)` 입니다.

## 예시 2

범위 `[10, 99]`가 주어진 경우 (두 수 모두 포함)...

최솟값은 `121`이며, 그 요소는 `(11, 11)`입니다.
최댓값은 `9009`이며, 그 요소들은 `(91, 99)` 와 `(99, 91)` 입니다.
