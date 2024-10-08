## 부분 집합
### 부분 집합
- 집합에 포함된 원소들을 선택하는 것
- 부분집합에는 아무것도 선택하지 않은 공집합도 포함된다.


### 집합에서 부분 집합을 찾아내는 구현 방법
1. 완전탐색
- 재귀호출을 이용한 완전탐색으로, 부분 집합을 구할 수 있다.
- 학습용으로 추천
2. Binary Counting
- 2진수 & 비트연산을 이용하여, 부분 집합을 구할 수 있다.
- 부분 집합이 필요할 때 사용하는 추천 방법
- **i & 1 << j**


## 조합
### 조합
- 서로 다른 n개의 원소 중 r개를 순서 없이 골라낸 것을 조합(combination)이라고 부른다.


### 순열과 조합 차이
- 순열 : 5명 중 1등, 2등, 3등 뽑기 (a, b, c) != (c, b, a)
- 조합 : 5중 3명 뽑기 (a, b, c) == (c, b, a)


## 그리디(Greedy)
- 그리디란 결정이 필요할 때, 현재 기준으로 가장 좋아보이는 선택지로 결정하여 답을 도출하는 알고리즘

### 대표적인 문제해결기법
1. 완전탐색(Brute-Force) : 답이 될 수 있는 모든 경우를 시도
2. Greedy : 결정이 필요할 때 가장 좋아보이는 선택지로 결정하는 알고리즘
3. DP : 과거의 데이터를 이용하여, 현재의 데이터를 만들어내는 문제해결기법
4. 분할정복 : 큰 문제를 작은 문제로 나누어 해결하는 문제해결기법