# [한 눈에 끝내는 Node.js](https://edu.goorm.io/lecture/557/한-눈에-끝내는-node-js)

## 객체지향 자바스크립트

**자바, C++은 클래스 기반의 언어, 자바스크립트는 프로토타입 기반의 언어이다.**

- 자바스크립트에 클래스라는 개념은 없다.
- 대신에 프로토타입(원형)이라는 개념이 있다.

**객체(인스턴스), 속성, 메소드**



**자바스크립트 언어 약속**

- 객체를 선언하는 함수의 첫 글자는 대문자
- 일반 함수의 첫 글자는 소문자

```js
var SoccerPlayer = function () { };

SoccerPlayer.prototype = { 
	name: String,
	age: Number,
	height: Number,
	weight: Number,
	position: String,
	team : String
};

var park_ji_sung = new SoccerPlayer(); 

park_ji_sung.name = "Park Ji Sung"; 
park_ji_sung.age = 31;
park_ji_sung.height = 178;
park_ji_sung.weight = 70;

console.log(park_ji_sung);
```



**캡슐화 (정보은닉Information Hiding)**

- 권한으로 가시성을 제한한다.
- ex. Java의 public, default, private, protected



**집합Aggregation (구성Composition)**

- 객체 여러 개를 하나의 새로운 것으로 구성하는 것.



**상속**

- 코드 재사용하는 방법이다.

```js
function Man() {
	this.name = "Anonymous";
	this.gender = "Man";
	this.Run = function () {
		return this.name + " is running!";
	}
	this.Sleep = function () {
		return this.name + " is sleeping!";
} }

function SoccerPlayer () { 
	this.base = new Man();
	this.name = "Anonymous Soccer Player"; 
	this.Run = function () {
		return this.base.Run();
	}
	this.Pass = function () {
		return this.name + "is passing to other player!";
} }

SoccerPlayer.prototype = new Man();
var player = new SoccerPlayer ();

console.log(player.name);
// "Anonymous Soccer Player"

console.log(player. gender);
// "Man"

console.log(player.Run());
// "Anonymous is running!"

console.log(player.Pass());
// "Anonymous Soccer Player is passing to other player!"

console.log(player.Sleep());
// "Anonymous Soccer Player is sleeping!"

// SoccerPlayer는 Man으로부터 상속받아 생성되었다
```



**생성자 함수(Constructor Function)**



**instanceof 연산자**



**컨스트럭터 속성(Constructor Property)**



**내장형 객체(Built-In Object)**

- Object, Number, Array, String, Boolean, Function
- **RegExp :** 정규식을 위한 객체입니다.
- **Math :** 수학과 관련된 각종 값과 메소드를 내장한 객체입니다.
- **Date :** 날짜와 시간에 관련된 메소드를 가진 객체입니다.
- **Error :** 자바스크립트에서 발생하는 에러를 처리하기 위한 객체입니다. 



**유효 범위(Scope)**

1. 전역 global: 어디서든지 참조 가능함.
2. 지역 local: 정의된 함수 내에서만 참조 가능함.

```js
var global_scope = 'global';  // 전역 스코프

var local_function = function() {
    var local_scope = 'goorm';  // 지역 스코프
    console.log(global_scope);  // 전역 스코프 참조 가능. global 출력
    console.log(local_scope);  // 함수 내이기 때문에 지역 스코프 참조 가능. goorm 출력
};

console.log(local_scope);  // name은 지역스코프이기 때문에 에러 발생.
```

- 전역 스코프가 편할지 몰라도 전역 스코프에 변수 선언 시 변수이름이 충돌될 수 있으므로 사용을 자제해야 한다.



**함수 레벨 스코프 Function-level scope: var**

- 블록 레벨 스코프Block-level scope 와 달리 함수 블록 내에서 선언된 변수는 그 안에서만 유효하고 함수 외부에서 참조 불가능. (== 함수 안이라면 중괄호 밖이라도 참조 가능하다.)
- 단, ES6부터 const, let을 이용하여 블록 레벨 스코프 지원함.



**유효 범위 체인(Scope Chain)**

- 스코프의 제한 단위가 함수인데, 만약 함수 안에 함수가 있다면?
- 안쪽 함수가 그 위쪽 함수의 범위까지 흡수한다.
- 내부 함수는 외부 함수에 변수를 사용할 수 있지만, 외부 함수는 내부 함수의 변수를 사용할 수 없다.

```js
var a = 1;

function outer() {
	var b = 2;
	console.log(a); // 1
	
	function inner() {
		var c = 3;
		console.log(b);
		console.log(a); 
	}
	
	inner();  // 2 1
}
outer();

console.log(c);  // c is not defined
```

- 내부함수에서 전역변수 a를 참조하는 과정
  1. 자기 자신의 스코프에서 a를 찾는다.
  2. 없으면 상위 스코프인 함수의 스코프에서 a를 찾는다.
  3. 없으면 그 상위 스코프인 전역범위에서 a를 찾는다.
  4. 최종적으로 전역 스코프에도 없으면 not defined 에러를 출력한다.



**정적 범위 Lexical scope**





**호이스팅(hoisting)**



## Node.js 소개

## Node.js 설치

## 기본 모듈과 Node.js 기초

## 확장모듈 - npm 활용하기

## 주요 확장 모듈 

### express

### express Pug

### socket.io

### mongoose

### Redis

## 실전 프로젝트

### 빙고 게임 만들기

### 간단한 SNS 개발