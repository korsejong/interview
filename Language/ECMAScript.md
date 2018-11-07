
ECMAScript
=========

## Index

#### 1. ECMAScript 5
#### 2. ECMAScript 6 (ES2015)
#### 3. ECMAScript 7 (ES2016)
#### 4. ECMAScript 8 (ES2017)

***

### 1. ECMAScript 5

#### "use strict"
* strict mode 사용
#### String.trim()
* String 공백 제거
#### Array.isArray()
* Object가 Array인지 확인
#### Array.forEach()
```
var list = [1,2,3,4,5]
list.forEach(printList);
function printList(value){
  console.log(value);
}
```  
#### Array.map()
```
var list = [1,2,3,4,5]
var list2 = list.map(plusOne);
function plusOne(value){
  return value+1;
}
```
#### JSON.stringify()
* JSON to String
#### JSON.parse()
* String to JSON
***

### 2. ECMAScript 6 (ES2015)

#### Arrow Function
```
var plusOne = e => { return e + 1; };
var plus = (n1, n2) => { return n1 + n2; };
```

#### Class
```
class Shape {
  constructor(){
    // ...
  }
}
class Circle extends Shape{
  constructor(){
    super();
    // ...
  }
}
```

#### Let, Const
* var를 대체하는 키워드
* Block Scope
* const의 경우 immutable

#### Iterators
* for-in
* for-of

#### Promise

#### Module

#### Map

#### Set

***

### 3. ECMAScript 7 (ES2016)

***

### 4. ECMAScript 8 (ES2017)

***

