# Math객체
```Date```객체처럼 자바스크립트의 내장 객체 중 다양한 연산들을 유용하게 사용하기 위해 Math라는 객체가 있다.

## **절댓값 (Absolute Number)**
절댓값은 어떤 값의 '양수(positive number)'이다. 음수 -5의 절댓값은 양수 5고, 그냥 양수 5의 절댓값은 그대로 양수 5다.

```Math.abs(x)```를 하면 x의 절댓값이 리턴된다.
```javascript
console.log(Math.abs(-10));
console.log(Math.abs(10));
```
결과
```
10
10
```

## **최댓값 (Maximum)**
```Math.max``` 함수에 파라미터로 여러 수를 넘겨주면, 그중 가장 큰 값이 리턴된다.
```javascript
console.log(Math.max(2, -1, 4, 5, 0));
```
결과
```
5
```

## **최솟값 (Minimum)**
```Math.max``` 함수에 파라미터로 여러 수를 넘겨주면, 그중 가장 작은 값이 리턴된다.
```javascript
console.log(Math.max(2, -1, 4, 5, 0));
```
결과
```
-1
```

## **거듭제곱 (Exponentiation)**
자바스크립트에서 ```Math.pow(x, y)```를 하면 x의 y승의 결과값이 리턴된다.
```javascript
console.log(Math.pow(2, 3));
console.log(Math.pow(5, 2));
```
결과
```
8
25
```

## **제곱근 (Square Root)**
```Math.sqrt(x)```를 하면 x의 제곱근이 리턴됩니다.
```javascript
console.log(Math.sqrt(25));
console.log(Math.sqrt(49));
```
결과
```
5
7
```


## **반올림 (Round)**
```Math.round(x)```를 하면 x의 반올림된 값이 리턴된다. 소수점 부분이 0.5 이상이면 가장 가까운 정숫값으로 올라가고, 소수점 부분이 0.5 미만이면 가장 가까운 정숫값으로 내려간다.
```javascript
console.log(Math.round(2.3));
console.log(Math.round(2.4));
console.log(Math.round(2.49));
console.log(Math.round(2.5));
console.log(Math.round(2.6));
```
결과
```
2
2
2
3
3
```


## **버림과 올림 (Floor and Ceil)**
```Math.floor(x)```을 하면 x의 버림 값이, ```Math.ceil(x)```을 하면 x의 올림 값이 리턴된다. 이 경우, 반올림과 달리 소수 부분이 얼마 인지와는 상관이 없다.
```javascript
console.log(Math.floor(2.4));
console.log(Math.floor(2.49));
console.log(Math.floor(2.8));
console.log('-');
console.log(Math.ceil(2.4));
console.log(Math.ceil(2.49));
console.log(Math.ceil(2.8));
```
결과
```
2
2
2
-
3
3
3
```

## **난수 (Random)**
```Math.random```을 하면 0 이상 1 미만의 값이 랜덤으로 리턴된다.
```javascript
console.log(Math.random());
console.log(Math.random());
console.log(Math.random());
console.log(Math.random());
```
결과
```
0.21458369059793236
0.6622040803059857
0.785172717569619
0.9056556038884926
```