# PermMissingElem
https://app.codility.com/programmers/lessons/3-time_complexity/perm_missing_elem/

---
An array A consisting of N different integers is given. The array contains integers in the range [1..(N + 1)], which means that exactly one element is missing.

Your goal is to find that missing element.

Write a function:

function solution(A);

that, given an array A, returns the value of the missing element.

For example, given array A such that:

  A[0] = 2
  A[1] = 3
  A[2] = 1
  A[3] = 5
the function should return 4, as it is the missing element.

Assume that:

N is an integer within the range [0..100,000];
the elements of A are all distinct;
each element of array A is an integer within the range [1..(N + 1)].
Complexity:

expected worst-case time complexity is O(N);
expected worst-case space complexity is O(1), beyond input storage (not counting the storage required for input arguments).

---
N 개의 서로 다른 정수로 구성된 배열 A가 주어집니다. 이 배열에는 [1 .. (N + 1)] 범위의 정수가 포함되어있어 정확히 하나의 요소가 누락되었음을 의미합니다.

귀하의 목표는 누락 된 요소를 찾는 것입니다.

함수를 작성하십시오.

함수 용액 (A);

주어진 배열 A는 누락 된 요소의 값을 반환합니다.

예를 들어, 주어진 배열 A는 다음과 같습니다.

  A [0] = 2
  A [1] = 3
  A [2] = 1
  A [3] = 5
함수는 누락 된 요소이기 때문에 4를 반환해야합니다.

가정하자면 :

N은 [0..100,000] 범위의 정수입니다.
A의 요소들은 모두 구별된다;
배열 A의 각 요소는 [1 .. (N + 1)] 범위의 정수입니다.
복잡성:

기대 최악의 경우의 시간 복잡도는 O (N)이다.
예상되는 최악의 경우의 공간 복잡도는 입력 저장소 (입력 인수에 필요한 저장소를 계산하지 않음) 이상으로 O (1)입니다.

---


# TapeEquilibrium
https://app.codility.com/programmers/lessons/3-time_complexity/tape_equilibrium/

---
A non-empty array A consisting of N integers is given. Array A represents numbers on a tape.

Any integer P, such that 0 < P < N, splits this tape into two non-empty parts: A[0], A[1], ..., A[P − 1] and A[P], A[P + 1], ..., A[N − 1].

The difference between the two parts is the value of: |(A[0] + A[1] + ... + A[P − 1]) − (A[P] + A[P + 1] + ... + A[N − 1])|

In other words, it is the absolute difference between the sum of the first part and the sum of the second part.

For example, consider array A such that:

  A[0] = 3
  A[1] = 1
  A[2] = 2
  A[3] = 4
  A[4] = 3
We can split this tape in four places:

P = 1, difference = |3 − 10| = 7
P = 2, difference = |4 − 9| = 5
P = 3, difference = |6 − 7| = 1
P = 4, difference = |10 − 3| = 7
Write a function:

function solution(A);

that, given a non-empty array A of N integers, returns the minimal difference that can be achieved.

For example, given:

  A[0] = 3
  A[1] = 1
  A[2] = 2
  A[3] = 4
  A[4] = 3
the function should return 1, as explained above.

Assume that:

N is an integer within the range [2..100,000];
each element of array A is an integer within the range [−1,000..1,000].
Complexity:

expected worst-case time complexity is O(N);
expected worst-case space complexity is O(N), beyond input storage (not counting the storage required for input arguments).

---

N 개의 정수로 구성된 비어 있지 않은 배열 A가 주어진다. 배열 A는 테이프의 숫자를 나타냅니다.

0 <P <N 인 모든 정수 P는이 테이프를 두 개의 비어 있지 않은 부분으로 나눕니다. A [0], A [1], ..., A [P - 1] 및 A [P] P + 1], ..., A [N-1]이다.

두 부분의 차이는 | (A [0] + A [1] + ... + A [P - 1]) - (A [P] + A [P + 1] + .. + A [N-1]) |

즉, 첫 번째 부분의 합과 두 번째 부분의 합 사이의 절대 차이입니다.

예를 들어, 배열 A를 다음과 같이 고려하십시오.

  A [0] = 3
  A [1] = 1
  A [2] = 2
  A [3] = 4
  A [4] = 3
이 테이프는 네 군데로 나눌 수 있습니다.

P = 1, 차이 = | 3 - 10 | = 7
P = 2, 차분 = | 4 - 9 | = 5
P = 3, 차분 = | 6 - 7 | = 1
P = 4, 차분 = | 10-3 | = 7
함수를 작성하십시오.

함수 용액 (A);

N 개의 정수 중 비어 있지 않은 배열 A가 주어지면 달성 할 수있는 최소한의 차이를 리턴합니다.

예를 들어, 주어진 :

  A [0] = 3
  A [1] = 1
  A [2] = 2
  A [3] = 4
  A [4] = 3
함수는 위에서 설명한대로 1을 반환해야합니다.

가정하자면 :

N은 [2..100,000] 범위의 정수입니다.
배열 A의 각 요소는 [-1,000..1,000] 범위의 정수입니다.
복잡성:

기대 최악의 경우의 시간 복잡도는 O (N)이다.
기대 최악의 경우의 공간 복잡도는 O (N)이며, 입력 저장소를 초과합니다 (입력 인수에 필요한 저장소를 계산하지 않음).


# FrogJmp
https://app.codility.com/programmers/lessons/3-time_complexity/frog_jmp/

---
A small frog wants to get to the other side of the road. The frog is currently located at position X and wants to get to a position greater than or equal to Y. The small frog always jumps a fixed distance, D.

Count the minimal number of jumps that the small frog must perform to reach its target.

Write a function:

function solution(X, Y, D);

that, given three integers X, Y and D, returns the minimal number of jumps from position X to a position equal to or greater than Y.

For example, given:

  X = 10
  Y = 85
  D = 30
the function should return 3, because the frog will be positioned as follows:

after the first jump, at position 10 + 30 = 40
after the second jump, at position 10 + 30 + 30 = 70
after the third jump, at position 10 + 30 + 30 + 30 = 100
Assume that:

X, Y and D are integers within the range [1..1,000,000,000];
X ≤ Y.
Complexity:

expected worst-case time complexity is O(1);
expected worst-case space complexity is O(1).

---

작은 개구리가 길 건너편으로 가고 싶어합니다. 개구리는 현재 X 위치에 있으며 Y보다 크거나 같은 위치로 가고 싶어합니다. 작은 개구리는 항상 고정 된 거리 D를 점프합니다.

작은 개구리가 표적에 도달하기 위해 수행해야하는 최소 점프 수를 세십시오.

함수를 작성하십시오.

함수 솔루션 (X, Y, D);

3 개의 정수 X, Y, D가 주어지면, X 위치로부터 Y 이상의 위치까지 점프의 최소 회수를 돌려줍니다.

예를 들어, 주어진 :

  X = 10
  Y = 85
  D = 30
개구리는 다음과 같이 위치 할 것이므로 함수는 3을 반환해야합니다.

첫 번째 점프 후, 위치 10 + 30 = 40
두 번째 점프 후 위치 10 + 30 + 30 = 70
세 번째 점프 후, 위치 10 + 30 + 30 + 30 = 100
가정하자면 :

X, Y 및 D는 [1..1,000,000,000] 범위의 정수입니다.
X ≤Y.
복잡성:

기대 최악의 경우의 시간 복잡도는 O (1)이다.
예상 최악의 공간 복잡도는 O (1)입니다.