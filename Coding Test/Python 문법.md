# Python 문법 정리

round()

나누기연산자(/) - 기본적으로 실수 처리

몫 연산자(//)

나머지 연산자(%)

### 리스트 자료형

[ ]

빈 리스트 선언 a = list() , a = []

a = [-1] 뒤에서 첫번째 원소

a[1:4] 두번째 원소부터 네 번쨰 원소까지

초기화 예시 array = [i for i in range(20) if i%2 == 1]

2차원 배열 초기화 array = [[0]*m for _ in range(n)]

append()  원소 삽입

sort() 오름차순 정렬

sort(reverse=True) 내림차순 정렬

reverse() 원소 순서 뒤집음

insert(삽입할 위치 인덱스, 삽입할 값) 특정 인덱스 위치에 값 삽입

count(특정 값) 특정한 값 가지는 데이터 개수 셀 때

remove(특정 값) 특정 값 제거, 값이 여러개면 하나만 제거

### 튜플 자료형

한번 선언된 값 변경 X

() 이용

그래프 알고리즘에 주로 사용

### 사전 자료형

key, value 값을 쌍으로 가지는 자료형

data = dict()

### 집합 자료형

중복 허용 X

순서가 없다.

{}

특정한 데이터가 이미 등장한 적이 있는 지 여부 체크 할 떄 효과적

### 입출력

list(map(int, input().split())) - 공백

int(input()) - 줄바꿈

data = list(map(int, input().split())

속도 빠르게 입력 받는 방법

import sys

sys.stdin.readline().rstrip()

### 알아야할 라이브러리 문법

- 내장 함수
- itertools - 순열 과 조합 라이브러리 제공
- heapq - 힙 기능 제공
- bisect - 이진 탐색 기능 제공
- collections - 덱, 카운터 등의 자료구조 포함
- math: 필수적인 수학적 기능을 제공하는 라이브러리이다. 팩토리얼, 제곱근, 최대공약수, 삼각함수 관련 함수부터 파이(pi)와 같은 상수를 포함하고 있다.