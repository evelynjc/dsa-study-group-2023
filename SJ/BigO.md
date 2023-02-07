# BigO

## 알고리즘

### 개념

유한한 단계를 통해 문제를 해결하기 위한 절차나 방법

컴퓨터 언어로 작성되며, 컴퓨터가 일을 수행하기 위한 단계적 접근 방법

### 표현방법

1. 의사코드(슈도코드)
   
   <img src="file:///Users/leesojeong/Desktop/스크린샷%202023-02-05%20오후%205.42.03.png" title="" alt="스크린샷 2023-02-05 오후 5.42.03.png" width="300">

2. 순서도
   
   <img src="file:///Users/leesojeong/Desktop/스크린샷%202023-02-05%20오후%205.42.11.png" title="" alt="스크린샷 2023-02-05 오후 5.42.11.png" width="299">

### 성능 측정

1. 정확성 : 정확한 동작

2. 작업량 : 결과를 얻기 위한 연산의 횟수

3. 메모리 : 메모리 사용량

4. 단순성 : 코드가 단순한 정도

5. 최적성 : 개선할 여지

## Big O 개념

주어진 문제를 해결하기 위한 다양한 알고리즘의 효율성을 비교하기 위한 표기법

## 알고리즘 복잡도

1. 시간복잡도
   
   알고리즘의 작업량을 표현하는 방법
   
   실제 걸리는 시간을 측정
   
   실행되는 명령문의 개수를 계산
   
   Big O에서는 시간 복잡도 함수 중 가장 크게 영향을 받는 최고차항을 비교하며, 계수는 생략

2. 공간복잡도
   
   알고리즘이 사용하는 메모리 효율성
   
   크기가 n인 배열의 공간 복잡도는 O(n) 형식으로 계산
   
   재귀 함수의 경우 스택 공간을 고려한 계산 필요

## 점근 표기법

- Big-Ω : 빅오메가
  
  최선의 경우 시간의 하한 계산, 빅오와 반대되는 개념
  
  이 알고리즘이 빅오메가 값보다 더 빠를 수 없음을 의미

- Big-θ : 빅세타
  
  평균, 딱 맞는 수행시간으로 정확한 값
  
  빅오, 빅오메가를 합친 것과 같음

- Big-O : 빅오 
  
  최악의 경우 시간의 상한 계산
  
  이 알고리즘은 빅오 값보다 더 오래걸릴 수 없음을 의미

- 현실에서는 최악의 경우를 반영하기 위한 빅오가 자주 쓰임