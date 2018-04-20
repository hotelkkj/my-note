# CyclicRotation
https://app.codility.com/programmers/lessons/2-arrays/cyclic_rotation/

---

A zero-indexed array A consisting of N integers is given. Rotation of the array means that each element is shifted right by one index, and the last element of the array is moved to the first place. For example, the rotation of array A = [3, 8, 9, 7, 6] is [6, 3, 8, 9, 7] (elements are shifted right by one index and 6 is moved to the first place).

The goal is to rotate array A K times; that is, each element of A will be shifted to the right K times.

Write a function:

function solution(A, K);

that, given a zero-indexed array A consisting of N integers and an integer K, returns the array A rotated K times.

For example, given

    A = [3, 8, 9, 7, 6]
    K = 3
the function should return [9, 7, 6, 3, 8]. Three rotations were made:

    [3, 8, 9, 7, 6] -> [6, 3, 8, 9, 7]
    [6, 3, 8, 9, 7] -> [7, 6, 3, 8, 9]
    [7, 6, 3, 8, 9] -> [9, 7, 6, 3, 8]
For another example, given

    A = [0, 0, 0]
    K = 1
the function should return [0, 0, 0]

Given

    A = [1, 2, 3, 4]
    K = 4
the function should return [1, 2, 3, 4]

Assume that:

N and K are integers within the range [0..100];
each element of array A is an integer within the range [−1,000..1,000].
In your solution, focus on correctness. The performance of your solution will not be the focus of the assessment.

---

N 개의 정수로 구성된 0 인덱스 배열 A가 제공됩니다. 배열을 회전하면 각 요소가 하나의 인덱스만큼 오른쪽으로 이동하고 배열의 마지막 요소가 첫 번째 위치로 이동합니다. 예를 들어, 배열 A = [3, 8, 9, 7, 6]의 회전은 [6, 3, 8, 9, 7]입니다 (요소는 하나의 인덱스만큼 오른쪽으로 이동하고 6은 첫 번째 위치로 이동 됨).

목표는 배열 A를 K 번 회전시키는 것입니다. 즉, A의 각 요소는 오른쪽 K 번으로 이동합니다.

함수를 작성하십시오.

함수 솔루션 (A, K);

N 개의 정수와 정수 K로 구성된 인덱스가 0 인 배열 A가 주어지면 배열 A를 K 회 회전시킨 값을 반환합니다.

예를 들어, 주어진

    A = [3, 8, 9, 7, 6]
    K = 3
함수는 [9, 7, 6, 3, 8]을 반환해야합니다. 세 가지 회전이 이루어졌다.

    [3, 8, 9, 7, 6] → [6, 3, 8, 9, 7]
    [6, 3, 8, 9, 7] → [7, 6, 3, 8, 9]
    [7, 6, 3, 8, 9] → [9, 7, 6, 3, 8]
또 다른 예를 들면 다음과 같습니다.

    A = [0, 0, 0]
    K = 1
함수는 [0, 0, 0]을 반환해야합니다.

주어진

    A = [1, 2, 3, 4]
    K = 4
함수는 [1, 2, 3, 4]를 반환해야합니다.

가정하자면 :

N과 K는 [0..100] 범위의 정수입니다.
배열 A의 각 요소는 [-1,000..1,000] 범위의 정수입니다.
솔루션에서 정확성에 중점을 둡니다. 솔루션의 성능은 평가의 초점이되지 않습니다.



# OddOccurrencesInArray

https://app.codility.com/programmers/lessons/2-arrays/odd_occurrences_in_array/

---
A non-empty zero-indexed array A consisting of N integers is given. The array contains an odd number of elements, and each element of the array can be paired with another element that has the same value, except for one element that is left unpaired.

For example, in array A such that:

  A[0] = 9  A[1] = 3  A[2] = 9
  A[3] = 3  A[4] = 9  A[5] = 7
  A[6] = 9
the elements at indexes 0 and 2 have value 9,
the elements at indexes 1 and 3 have value 3,
the elements at indexes 4 and 6 have value 9,
the element at index 5 has value 7 and is unpaired.
Write a function:

function solution(A);

that, given an array A consisting of N integers fulfilling the above conditions, returns the value of the unpaired element.

For example, given array A such that:

  A[0] = 9  A[1] = 3  A[2] = 9
  A[3] = 3  A[4] = 9  A[5] = 7
  A[6] = 9
the function should return 7, as explained in the example above.

Assume that:

N is an odd integer within the range [1..1,000,000];
each element of array A is an integer within the range [1..1,000,000,000];
all but one of the values in A occur an even number of times.
Complexity:

expected worst-case time complexity is O(N);
expected worst-case space complexity is O(1), beyond input storage (not counting the storage required for input arguments).

---
N 개의 정수로 구성된 비어 있지 않은 제로 색인 배열 A가 주어진다. 배열에는 홀수 개의 요소가 포함되어 있으며 배열의 각 요소는 동일한 값을 가진 다른 요소와 쌍을 이룰 수 있습니다 (단 하나의 요소는 쌍을 이루지 않음).

예를 들어 다음과 같은 배열 A에서 :

  A [0] = 9 A [1] = 3 A [2] = 9
  A [3] = 3 A [4] = 9 A [5] = 7
  A [6] = 9
인덱스 0과 2의 요소는 값 9를 가지고,
인덱스 1과 3의 요소는 값 3을 가지고,
인덱스 4와 6의 요소는 값 9를 가지며,
인덱스 5의 요소는 값 7을 가지며 대응되지 않습니다.
함수를 작성하십시오.

함수 용액 (A);

위의 조건을 충족하는 N 개의 정수로 구성된 배열 A가 주어지면, 비 대응 요소의 값을 반환합니다.

예를 들어, 주어진 배열 A는 다음과 같습니다.

  A [0] = 9 A [1] = 3 A [2] = 9
  A [3] = 3 A [4] = 9 A [5] = 7
  A [6] = 9
함수는 위의 예제에서 설명한 것처럼 7을 반환해야합니다.

가정하자면 :

N은 [1..1,000,000] 범위 내의 홀수 정수입니다.
배열 A의 각 요소는 [1..1,000,000,000] 범위의 정수입니다.
A의 값 중 하나를 제외하고 모두 짝수 번 발생합니다.
복잡성:

기대 최악의 경우의 시간 복잡도는 O (N)이다.
예상되는 최악의 경우의 공간 복잡도는 입력 저장소 (입력 인수에 필요한 저장소를 계산하지 않음) 이상으로 O (1)입니다.