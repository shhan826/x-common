다음과 같은 행렬이 있습니다:

```plain
    0  1  2
  |---------
0 | 9  8  7
1 | 5  3  2     <--- (1,0)에 saddle point
2 | 6  6  7
```

이 행렬에서는 (1, 0)에 saddle point(안장점(鞍裝點))가 있습니다. 

여기서 "saddle pont"란, 같은 행 안에서는 모든 원소들보다 값이 같거나 크고, 같은 열 안에서는 값이 같거나 작은 경우를 말합니다.

행렬 안에는 saddle point가 없을 수도, 여러개가 있을 수도 있습니다.

코딩을 통해서 주어진 행렬에 대해 모든 saddle point의 목록을 만들어내세요. (없는 경우도 포함)


행렬의 saddle points에 대한 다른 정의도 있지만, 이 문제에서는 위에서 내린 정의에 한정지어 풀면 됩니다.

