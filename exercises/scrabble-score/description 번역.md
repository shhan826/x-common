## 글자와 숫자

다음 조건을 사용하세요:

```plain
글자                                숫자
A, E, I, O, U, L, N, R, S, T       1
D, G                               2
B, C, M, P                         3
F, H, V, W, Y                      4
K                                  5
J, X                               8
Q, Z                               10
```

## 예시
"cabbage"는 14점의 값이 메겨집니다.

- C에 3점
- A에 1점 (두 번)
- B에 3점 (두 번)
- G에 2점
- E에 1점

모두 더해서:

- `3 + 2*1 + 2*3 + 2 + 1`
- = `3 + 2 + 6 + 3`
- = `5 + 9`
- = 14

## 추가
- `:double`이나 `:triple` 형식의 글자를 다뤄보세요.
- `:double`이나 `:triple` 형식의 단어를 다뤄보세요.
