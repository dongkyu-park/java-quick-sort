# QuickSort(퀵정렬)

퀵정렬은 분할정복을 이용하여 정렬을 수행하는 알고리즘 이다.

## 과정

- 기준 값(=pivot)을 정한다.
- L은 기준 값보다 작아야하며, R은 기준 값보다 커야한다.
- L과 R이 만나는 자리가 기준 값의 자리이다.

![image](https://user-images.githubusercontent.com/81552729/150113164-97caf455-8621-47e4-9b4d-acfe2f2129df.png)

영상자료 : https://www.youtube.com/watch?v=S2c4zAGgVgI&t=169s

## 시간 복잡도

결론부터 이야기 하면, 퀵정렬의 시간복잡도는
평균복잡도는 nlogn 이지만 최악의 경우엔 n2이므로,
빅오표기법으로 표현한다면 시간복잡도는 O(n2)이다.

시간복잡도 계산법 -> https://velog.io/@kyu/%EC%BD%94%EB%93%9C%EC%8A%A4%EC%BF%BC%EB%93%9C-3%EC%A3%BC%EC%B0%A8-3
