# 혼자 공부하는 자바스크립트

![혼자 공부하는 C언어](https://www.hanbit.co.kr/data/books/B8393055290_l.jpg)

[한빛 미디어 - 혼자 공부하는 C언어](https://hongong.hanbit.co.kr/%ec%9e%90%eb%b0%94%ec%8a%a4%ed%81%ac%eb%a6%bd%ed%8a%b8/)

## 공부 목적 및 계획

- node.js를 다루기 위해 자바스크립트 공부가 필요하다 생각하여 공부를 시작함
- 자바 스크립트 기초 지식 학습
- 자바 스크립트 문법 공부
- 아는 내용은 건너 뛸 예정

## 책 선정 이유

- 혼공 시리즈 책을 선호하여 선택함

## 사용 도구

- GitHub
- GitKraken
- Git
- Visual Studio Code
- ChatGPT
- 제미나이

## 기간

2025.05.13 ~ 2025.05.15 예정

# 목차

<details>
  <summary><strong>📖 바로가기</strong></summary>

- [혼자 공부하는 자바스크립트](#혼자-공부하는-자바스크립트)
  - [공부 목적 및 계획](#공부-목적-및-계획)
  - [책 선정 이유](#책-선정-이유)
  - [사용 도구](#사용-도구)
  - [기간](#기간)
- [목차](#목차)
  - [공부 양식](#공부-양식)
    - [📌 핵심 개념](#-핵심-개념)
    - [💻 코드 및 예제](#-코드-및-예제)
    - [🎯 배운 점 \& 인사이트](#-배운-점--인사이트)
- [01 자바스크립트 개요와 개발환경 설정](#01-자바스크립트-개요와-개발환경-설정)
  - [01-1 자바스크립트의 활용](#01-1-자바스크립트의-활용)
  - [01-2 개발환경 설치와 코드 실행](#01-2-개발환경-설치와-코드-실행)
  - [01-3 알아두어야 할 기본 용어](#01-3-알아두어야-할-기본-용어)
    - [📌 핵심 개념](#-핵심-개념-1)
    - [💻 코드 및 예제](#-코드-및-예제-1)
      - [출력](#출력)
- [02 자료와 변수](#02-자료와-변수)
  - [02-1 기본 자료형](#02-1-기본-자료형)
    - [문자열 자료형](#문자열-자료형)
      - [문자열 연산자](#문자열-연산자)
    - [숫자 자료형](#숫자-자료형)
    - [불 자료형](#불-자료형)
    - [자료형 검사](#자료형-검사)
    - [템플릿 문자열](#템플릿-문자열)
    - [== === 비교 연산자](#--비교-연산자)
  - [02-2 상수와 변수](#02-2-상수와-변수)
    - [상수](#상수)
    - [변수](#변수)
      - [변수에 적용할 수 있는 연산자](#변수에-적용할-수-있는-연산자)
    - [undifined 자료형](#undifined-자료형)
  - [02-3 자료형 변환](#02-3-자료형-변환)
    - [문자열 입력](#문자열-입력)
    - [불 입력](#불-입력)
    - [숫자 자료형으로 변환하기](#숫자-자료형으로-변환하기)
      - [숫자 연산자를 사용하여 자료형 변환하기](#숫자-연산자를-사용하여-자료형-변환하기)
    - [문자열 자료형으로 변환하기](#문자열-자료형으로-변환하기)
      - [문자열 연산자를 사용하여 자료형 변환하기](#문자열-연산자를-사용하여-자료형-변환하기)
    - [불 자료형으로 변환하기](#불-자료형으로-변환하기)
      - [논리 부정 연산자를 사용해 자료형 변환하기](#논리-부정-연산자를-사용해-자료형-변환하기)
- [03 조건문](#03-조건문)
  - [03-1 if 조건문](#03-1-if-조건문)
  - [03-2 switch 조건문과 짧은 조건문](#03-2-switch-조건문과-짧은-조건문)
    - [switch 조건문의 기본 형태](#switch-조건문의-기본-형태)
    - [조건부 연산자](#조건부-연산자)
    - [짧은 조건문](#짧은-조건문)
      - [논리합 연산자를 사용한 짧은 조건문](#논리합-연산자를-사용한-짧은-조건문)
      - [논리곱 연산자를 사용한 짧은 조건문](#논리곱-연산자를-사용한-짧은-조건문)
- [04 반복문](#04-반복문)
  - [04-1 배열](#04-1-배열)
    - [배열](#배열)
    - [배열 요소에 접근하기](#배열-요소에-접근하기)
    - [배열 요소 개수 확인하기](#배열-요소-개수-확인하기)
    - [배열 뒷부분에 요소 추가하기](#배열-뒷부분에-요소-추가하기)
      - [push() 메소드](#push-메소드)
      - [인덱스를 사용해 배열 뒷 부분에 추가하기](#인덱스를-사용해-배열-뒷-부분에-추가하기)
    - [배열 요소 제거하기](#배열-요소-제거하기)
      - [인덱스로 요소 제거하기](#인덱스로-요소-제거하기)
      - [값으로 요소 제거하기](#값으로-요소-제거하기)
      - [문자열에서 indexOf()](#문자열에서-indexof)
    - [배열의 특정 위치에 요소 추가하기](#배열의-특정-위치에-요소-추가하기)
  - [04-2 반복문](#04-2-반복문)
    - [for in 반복문](#for-in-반복문)
    - [for of 반복문](#for-of-반복문)
    - [for 반복문](#for-반복문)
      - [for 반복문과 배열 함께 사용하기](#for-반복문과-배열-함께-사용하기)
    - [while 반복문](#while-반복문)
      - [배열과 함께 사용](#배열과-함께-사용)
    - [break 키워드](#break-키워드)
    - [continue 키워드](#continue-키워드)
- [05 함수](#05-함수)
  - [05-1 함수의 기본 형태](#05-1-함수의-기본-형태)
    - [익명 함수](#익명-함수)
    - [선언적 함수](#선언적-함수)
    - [매개변수와 리턴값](#매개변수와-리턴값)
    - [나머지 매개변수](#나머지-매개변수)
      - [나머지 매개변수와 일반 매개변수 조합하기](#나머지-매개변수와-일반-매개변수-조합하기)
      - [전개 연산자](#전개-연산자)
    - [기본 매개변수](#기본-매개변수)
  - [05-2 함수 고급](#05-2-함수-고급)
    - [콜백 함수](#콜백-함수)
      - [콜백 함수를 활용하는 함수들](#콜백-함수를-활용하는-함수들)
    - [화살표 함수](#화살표-함수)
    - [타이머 함수](#타이머-함수)
    - [좀 더 알아보기](#좀-더-알아보기)
      - [즉시 호출 함수](#즉시-호출-함수)
      - [즉시 호출 함수 문제 해결하기](#즉시-호출-함수-문제-해결하기)
      - [엄격 모드](#엄격-모드)
      - [익명 함수와 선언적 함수의 차이](#익명-함수와-선언적-함수의-차이)
      - [let 사용의 의미](#let-사용의-의미)
- [06 객체](#06-객체)
  - [06-1 객체의 기본](#06-1-객체의-기본)
    - [객체](#객체)
    - [속성과 메소드](#속성과-메소드)
      - [속성과 메소드 구분하기](#속성과-메소드-구분하기)
      - [메소드 내부에서 this 키워드 사용하기](#메소드-내부에서-this-키워드-사용하기)
    - [동적으로 객체 속성 추가/제거](#동적으로-객체-속성-추가제거)
      - [동적으로 객체 속성 추가하기](#동적으로-객체-속성-추가하기)
      - [동적으로 객체 속성 제거하기](#동적으로-객체-속성-제거하기)
    - [메소드 간단 선언 구문](#메소드-간단-선언-구문)
    - [화살표 함수를 사용한 메소드](#화살표-함수를-사용한-메소드)
  - [06-2 객체의 속성과 메소드 사용하기](#06-2-객체의-속성과-메소드-사용하기)
    - [객체 자료형](#객체-자료형)
    - [기본 자료형](#기본-자료형)
    - [기본 자료형을 객체로 선언하기](#기본-자료형을-객체로-선언하기)
    - [기본 자료형의 일시적 승급](#기본-자료형의-일시적-승급)
    - [프로토타입으로 메소드 추가하기](#프로토타입으로-메소드-추가하기)
    - [Number 객체](#number-객체)
      - [숫자 N번째 자릿수까지 출력하기 toFixed()](#숫자-n번째-자릿수까지-출력하기-tofixed)
      - [NaN과 Infinity 확인하기: isNaN(), isFinite()](#nan과-infinity-확인하기-isnan-isfinite)
    - [String 객체](#string-객체)
      - [문자열 양 끝의 공백 없애기: trim()](#문자열-양-끝의-공백-없애기-trim)
      - [문자열을 특정 기호로 자르기: split()](#문자열을-특정-기호로-자르기-split)
    - [JSON 객체](#json-객체)
      - [자바스크립트 객체를 JOSN 문자열로: JSON.stringify()](#자바스크립트-객체를-josn-문자열로-jsonstringify)
      - [JSON 문자열을 자바스크립트 객체로 전개: JSON.parse()](#json-문자열을-자바스크립트-객체로-전개-jsonparse)
    - [Math 객체](#math-객체)
      - [랜덤한 숫자를 생성할 때: Math.random()](#랜덤한-숫자를-생성할-때-mathrandom)
    - [외부 script 파일 읽어들이기](#외부-script-파일-읽어들이기)
    - [Lodash 라이브러리](#lodash-라이브러리)
      - [외부 라이브러리 적용 방법](#외부-라이브러리-적용-방법)
      - [CDN](#cdn)
      - [min 버전](#min-버전)
      - [\_ 메소드](#_-메소드)
  - [06-3 객체와 배열 고급](#06-3-객체와-배열-고급)
    - [속성 존재 여부 확인](#속성-존재-여부-확인)
      - [속성이 없다면 속성 지정해주기](#속성이-없다면-속성-지정해주기)
    - [배열 기반 다중 할당](#배열-기반-다중-할당)
    - [객체 기반 다중 할당](#객체-기반-다중-할당)
    - [배열 전개 연산자](#배열-전개-연산자)
    - [객체 전개 연산자](#객체-전개-연산자)
- [07 문서 객체 모델](#07-문서-객체-모델)
  - [07-1 문서 객체 조작하기](#07-1-문서-객체-조작하기)
  - [07-2 이벤트 활용](#07-2-이벤트-활용)
- [08 예외 처리](#08-예외-처리)
  - [08-1 구문 오류와 예외](#08-1-구문-오류와-예외)
  - [08-2 예외 처리 고급](#08-2-예외-처리-고급)
- [09 클래스](#09-클래스)
  - [09-1 클래스의 기본 기능](#09-1-클래스의-기본-기능)
  - [09-2 클래스의 고급 기능](#09-2-클래스의-고급-기능)
- [10 리액트 라이브러리](#10-리액트-라이브러리)
  - [10-1 리액트의 기본](#10-1-리액트의-기본)
  - [10-2 리액트와 데이터](#10-2-리액트와-데이터)
- [부록 A](#부록-a)
  - [정답 및 해설](#정답-및-해설)
  - [찾아보기](#찾아보기)


</details>

---

## 공부 양식

### 📌 핵심 개념
### 💻 코드 및 예제
### 🎯 배운 점 & 인사이트

---

# 01 자바스크립트 개요와 개발환경 설정

## 01-1 자바스크립트의 활용

- 자바스크립트란 웹 브라우저에서 작동하는 프로그래밍 언어다.
- ECMAScript란 유럽컴퓨터제조협회에서 표준화한 자바스크립트의 공식 명칭입니다.
- 웹 애플리케이션이란 기존 웹 페이지보다 더 많은 기능을 구현한 웹 페이지다.

## 01-2 개발환경 설치와 코드 실행

- 개발환경 : 개발 할 수 있는 환경
- 텍스트 에디터 : 코드를 작성할 수 있는 프로그램. 책에서는 Visual Studio Code를 사용
- 구글 크롬 개발자 도구 : 구글 크롬에서 개발자를 위해 제공하는 도구로 오류 확인과 같은 기능이 있음.

## 01-3 알아두어야 할 기본 용어

### 📌 핵심 개념

- 표현식 : 값을 만들어내는 간단한 코드
- 문장 : 하나 이상의 표현식이 모여 구성되는 것으로, 코드를 읽어 들이는 기본 단위
- 키워드 : 프로그래밍 언어가 만들어질 때 정해진 특별한 의미가 있는 단어
- 식별자 : 이름을 붙일 대 사용하는 단어
- 주석 : 프로그램 코드를 설명하는 문장으로 프로그램 진행에는 영향을 주지 않음

### 💻 코드 및 예제

#### 출력

- 표현식 확인하기
표현식은 간단하게 크롬 개발자 도구 콘솔에서 확인이 가능함
```
> 10 + 20
30
> 10 * 10
100
```

- 경고창에 출력하기
웹 브라우저에 경고창으로 띄우는 방식으로 출력할 수 있다
```html
<script>
  alert('Hello javaScript...!')
</script>
```

- 콘솔에 출력하기
alert() 함수로 많은 양을 출력하기에 곤란하니 개발자도구 `Console`창에 출력하도록 함
```html
<script>
  console.log('Hello JavaScript...!')
</script>
```

---

# 02 자료와 변수

- 자료형에 대해서 알아봅니다
- 상수와 변수에 대해서 알아봅니다
- 자료형 변환에 대해서 알아봅니다

## 02-1 기본 자료형

자료형 : 프로그램이 처리할 수 잇는 모든 것을 자료(data)라고 하며, 자료 형태에 따라 나눠 놓은 것을 자료형(data type)이라고 함

- 종류 : 숫자(number), 문자열(String), 불(Boolean)

### 문자열 자료형

자바스크립트에서는 문자가 하나든 여러개든 모두 문자열 자료형이라고 함

- 자바 스크립트에서는 문자 하나만 나타내는 문자 자료형(Charactor)이 없음
- 만드는 방법은 큰 따옴표(")와 작은 따옴표(') 둘 다 사용할 수 있다
```html
> '안녕하세요'
"안녕하세요" <- 콘솔 출력에서 큰따옴표로 감싸져 있으면 문자열을 의미한다
> "안녕하세요"
"안녕하세요"
```
#### 문자열 연산자

문자열 연산자 : 문자열에 연산 처리할 수 있도록 만들어주는 연산자

- 문자열 연결 연산자 : 문자열끼리 연결하여 새로운 문자열을 만들 때 사용하는 연산자로 `+` 덧셈 기호를 의미한다

`문자열 + 문자열 = 더해진 문자열`

```html
> '도레' + '미' + '파솔라시도'
"도레미파솔라시도"
```

- 문자 선택 연산자 : 문자열 내부의 문자 하나를 선택할 때 사용하는 연산자

`문자열[숫자(인덱스)]`

```html
> '안녕하세요'[0]
"안"
> '안녕하세요'[2]
"하"
```

- 문자열 길이 구하기 : 문자열의 길이(length)를 구할 때 사용

`문자열.length`

```html
> "안녕하세요".length
5
> "자바스크립트".length
6
> "".length
0 <- 빈 문자열도 문자열이다
```

### 숫자 자료형

자바스크립트는 소수점이 있는 숫자와 없는 숫자를 모두 같은 숫자 자료형으로 인식함

```html
> 273
273
> 52.12
52.12
```

- 숫자 연산자 : 기본적인 사칙 연산과 나머지 연산

|연산자|설명|
|---|---|
|+|더하기 연산자|
|-|빼기 연산자|
|*|곱하기 연산자|
|/|나누기 연산자|
|%|나머지 연산자|

### 불 자료형

자바스크립트에서는 참과 거짓을 표현할 때 불 자료형을 사용
true와 false 2가지가 잇음

- 만드는 방법
  - 단순하게 true false 입력
```html
> true
true
>false
false
```
- 비교 연산자 사용
  |연산자|설명|
  |---|---|
  |===|양쪽이 같고 자료형도 같다|
  |==|양쪽이 같지만 자료형은 검증하지 않는다|
  |!==|양쪽이 다르거나 자료형이 다르다|
  |!=|양쪽이 다르다|
  |<|왼쪽이 더 크다|
  |<=|왼쪽이 더 크거나 같다|
  |>|오른쪽이 더 크다|
  |>=|오른쪽이 더 크거나 같다|

```html
> 52 == "52"
true
> 52 === "52"
false
```

- 문자열에서 비교 연산자 : 문자열에서는 사전에서 앞쪽에서 나올수록 값이 작다
```html
> '가방' > '하마'
false <- 가방이 사전에서 더 먼저 나오므로 값이 작다
> apple < banana
true
```

- 불 부정연산자 : 문자열과 숫자열에 연산자를 적용할 수 있는 것처럼 불 자료형에도 적용할 수 있는 연산자로 불을 반대로 바꿈(!)

```
> !true
false
> !false
true
```

- 불 논리합/논리곱 연산자 : and(&&)와 or(||)의 의미로 사용한다

```
> true && false
false
> (10 === 10) || (10 === 12)
true
```
### 자료형 검사

자바스크립트에서 자료형을 확인할 때 사용하는 연산자는 typeof를 사용한다

`typeof(자료)`

```
> typeof('사과')
"string"
> typeof(3.14)
"number"
> typeof(true)
"boolean"
```
- 문자열 확인하는 사용법

```html
> typeof(10) === 'number'
true
```

### 템플릿 문자열

코드안에 문자열 연결 연산자(+)를 사용하여 문자열을 추가하면 코드가 복잡해지므로 이를 행결하기 위해 템플릿 문자열이라는 기능이 추가되었다

\`${문자열}\` 기호를 사용한다

```javascript
> console.log(`표현식 273 + 52의 값은 ${273 + 52}입니다...!`)
표현식 273 + 52의 값은 325입니다...!
```

작은 따옴표를 사용하면 문자열로 인식하므로 `(백틱)을 사용해야 한다

### == === 비교 연산자

`===` 연산자는 자료형까지 비교하고 `==` 연산자는 자료형은 비교하지 않는다.

```javascript
> 1 === "1"
false
> false == "0"
true
> "" == []
true
> 0 == []
true
> 0 === []
false
```
- `==` 연산자에서 빈 문자열("", []), 숫자 0은 false와 같은 false 취급을 받는다.
- 자바스크립트에서는 혹시 생길지 모르는 문제가 있기에 ===만 사용하는 것이 좋다.

## 02-2 상수와 변수

### 상수

변하지 않는 수를 만들고 싶을 때 선언하여 만듬

`const 이름 = 값`

```javascript
> const pi = 3.14
undefined
> pi
3.14

> const r = 10
undefined

>2 * pi * r
62.8
> pi * r * r
314
```

- 상수는 한 파일에 한 번만 선언할 수 있다.
- 상수는 한 번만 선언할 수 있으므로 반드시 값을 함께 선언해야한다.
- 한번 번 선언된 상수의 자료는 변경할 수 없다.

### 변수

변할 수 있는 수를 선언할 때 만듬

`let 이름 = 값`

```javascript
> let pi = 3.14
undefined
> pi
3.14

> let r = 10
undefined

> pi * r * r
314
```

- 변수는 한 파일에 한 번만 선언할 수 있다.

#### 변수에 적용할 수 있는 연산자

- 복합 대입 연산자

|복합 대입 연산자|설명|예시|의미|
|---|---|---|---|
|+=|기존 변수의 값에 값을 더합니다|a += 1|a = a + 1|
|-=|기존 변수의 값에 값을 뺍니다|a -= 1|a = a - 1|
|*=|기존 변수의 값에 값을 곱합니다|a *= 2|a = a * 2|
|/=|기존 변수의 값에 값을 나눕니다|a /= 2|a = a / 2|
|%=|기존 변수의 값에 값의 나머지를 구합니다|a %= 2|a = a %2 |

- 증감 연산자

|증감 연산자|설명|
|---|---|
|변수++|기존의 변수 값에 1을 더합니다.(후위)|
|++변수|기존의 변수 값에 1을 더합니다.(전위)|
|변수--|기존의 변수 값에 1을 뺍니다.(후위)|
|--변수|기존의 변수 값에 1을 뺍니다.(전위)|

### undifined 자료형

- 상수와 변수로 선언하지 않는 식별자

```javascript
> typeof(abc)
"undefined"

> typeof(아무한글)
"undefined"
```

- 값이 없는 변수

```javascript
> let a
undefined

> typeof(a)
"undefined"
```

## 02-3 자료형 변환

자바 스크립트 내부에서 자료형 변환이 자연스럽게 일어나지만 의도적으로 처리하는 것이 좋다.
```javascript
> "10" * 10
100
```

### 문자열 입력

문자열 입력을 받을 때 사용하는 함수는 prompt()

`prompt(메세지 문자열, 기본 입력 문자열)`

```javascript
  <script>
    // 상수 선언
    const input = prompt('이름을 입력해주세요', '홍길동')

    // 출력
    alert(input)
  </script>
```

### 불 입력

문자열 외에 불 자료형 값을 입력 받을 때 confirm()

`confirm(메시지 문자열)`\

```javascript
  <script>
    // 불 입력
    const input = confirm("성인입니까?")

    // 출력
    alert(input)
  </script>
```

### 숫자 자료형으로 변환하기

다른 자료형을 숫자 자료형으로 변환할 때 Number() 함수 사용

`Number(자료)`

```javascript
> Number("273")
273

> typeof(Number("273"))
"number"
```

만약 변환이 불가능한 자료형이 들어온다면 NaN(Not a Number)라는 값을 출력하지만 자료형 자체는 숫자형으로 나옴

```javascript
> Nubmer("$273")
NaN
> typeof(Number("$273"))
"number"
```

불 자료형은 true는 1, false는 0으로 변환
```javascript
> Number(true)
1
> Number(false)
0
```

#### 숫자 연산자를 사용하여 자료형 변환하기

숫자 연산자 -,*,/를 사용하면 다른 자료형을 숫자 자료형으로 변환할 수 있다. 보통 0을 빼거나 1을 곱하거나 1로 나누어 만든다.

```javascript
> "52" - 0
52
> typeof("52" - 0)
"number"

> true - 0
1
> typeof(true - 0)
"number"
```

불 자료형의 경우 +도 사용 가능하다

```javascript
> 1 + true
2
```

### 문자열 자료형으로 변환하기

다른 자료형을 문자열 자료형으로 변환할 때는 Stirng() 함수를 사용한다

`String(자료)`

```javascript
> String(3.14)
"3.14"
> String(true)
"true"
```

#### 문자열 연산자를 사용하여 자료형 변환하기

숫자로 변환할 때 -,/,*를 사용했다면 문자열에서는 +를 사용한다. 보통 "" 빈 문자열을 더하여 만든다.

```javascript
> 273 + ""
"273"
```

### 불 자료형으로 변환하기

다른 자료형을 불 자료형으로 변환할 때는 Boolean() 함수를 사용한다

`Boolean(자료)`

대부분의 자료는 불로 변환했을 때 true로 변환된다.

false로 변환되는 자료형

|값|결과|
|---|---|
|0|false|
|NaN|false|
|"..."(빈 문자열)|false|
|null|false|
|undefined|false|


```javascript
> Boolean(3.14)
true
> Boolean("문자")
true

> Boolean(0)
false
> Boolean(NaN)
false
> Boolean("")
false
> Boolean(Null
false

>let 변수
undefined
> Boolean(변수)
false
```

#### 논리 부정 연산자를 사용해 자료형 변환하기
논리 부정 연산자(!)를 사용하면 다른 자료형을 불 자료형으로 변환할 수 있다. 보통 !를 두번 사용하는 !!를 사용한다.

```javascript
> !!3.14
true
> !!""
false
```

---

# 03 조건문

- if 조건문의 사용법을 알아봅니다
- switch 조건문의 사용법을 알아봅니다
- 조건부 연산자의 짧은 조건문에 대하여 알아봅니다

## 03-1 if 조건문

다른 언어의 if 사용과 비슷하므로 훑고 지나가려고 한다

- 기본 if 문

```javascript
if (불 값이 나오는 표현식) {
  불 값이 참일 때 실행할 문장
}
```

- if - else 조건문

```javascript
if (불 값이 나오는 표션식) {
  불 값이 참일 때 실행할 문장
} else {
  불 값이 거짓일 때 실행할 문장
}
```

- if else if 조건문

```javascript
if (불 표현식) {
  문장
} else if (불 표현식) {
  문장
} else if (불 표현식) {
  문장
} else {
  문장
}
```

## 03-2 switch 조건문과 짧은 조건문

### switch 조건문의 기본 형태

```javascript
switch(자료) {
  case 조건A:
    break
  case 조건B:
    break
  default: // 생략 가능
    break
}
```

- switch 기본 예시 - 짝수/홀수 감별 프로그램

```javascript
<script>
    // 입력
    const input = Number(prompt('숫자를 입력하세요', '숫자'))

    // switch 조건문
    switch (input % 2) {
      case 0:
        alert('짝수입니다')
        break
      case 1:
        alert('홀수입니다')
        break
      default:
        alert('숫자를 입력해주세요')
        break
    }
  </script>
```

### 조건부 연산자

조건문과 비슷한 역할을 하는 연산자(삼항 연산자)

`불 표현식 ? 참일 때의 결과 : 거짓일 때의 결과`

### 짧은 조건문

논리 연산자의 특성으로 조건문을 만듬

#### 논리합 연산자를 사용한 짧은 조건문

`불 표현식 || 불 표현식이 거짓일 때 실행할 문장`

```javascript
> true || console.log('실행 안됨')
true // 좌변이 이미 참이므로 우변은 검증하지 않으므로 실행되지 않음

> false || console.log('실행 됨')
실행 됨 // 우변이 실행 됨
undefined
```

#### 논리곱 연산자를 사용한 짧은 조건문

`결과가 거짓인 불 표현식 && || 불 표현식이 참일 때 실행할 문장`

```javascript
> false && console.log('실행 안됨')
false // 좌변이 이미 거짓이므로 우변을 검증하지 않으므로 실행되지 않음

> true && console.log('실행 됨')
실행 됨 // 우변이 실행 됨
true
```

---

# 04 반복문

- 배열에 대해 알아봅니다
- 파괴적 처리와 비파과적 처리에 대해 알아봅니다
- for in 반복문, for of 반복문, for 반복문, while 반복문에 대해 알아봅니다  

## 04-1 배열

배열 : 여러 자료를 묶어서 활용할 수 있는 특수한 자료

```javascript
> const str = '안녕하세요'

> str[2]
하
> str[str.length-1]
요
```

### 배열

배열은 여러 개의 변수를 한 번에 선언해 다룰 수 있는 자료형

- 대괄호[...]를 사용해 생성하고 내부 값은 쉼표(,)로 구분.
- 배열 내부의 값은 요소(element)

`[요소, 요소, 요소 ...]`

```javascript
> const array = [273, 'String', true, function () {}, {}, [273, 103]]
undefined

> array
(6) [273, 'String', true, ƒ, {…}, Array(2)]
// (요소 개수) [요소, 요소, 요소]
```

### 배열 요소에 접근하기

배열안의 요소에 접근하는 방식은 인덱스(index)와 대괄호([])를 이용한다.

`배열[인덱스]`

```javascript
> const numbers = [3.14, 42, 23, 4]
undefined

> numbers[2]
23

> numbers[1 + 1]
23

> numbers[1 * 1]
42
```

### 배열 요소 개수 확인하기

배열 내부의 들어있는 요소의 개수를 확인하기 위해 length 속성을 사용한다

`배열.length`

```javascript
> const fruits = ['배', '바나나', '사과']
undefined

> fruits.length
3

> fruits[fruits.length - 1]
"사과"
```

- 배열의 마지막 요소에 접근할 때는 `배열[배열.length - 1]`를 사용한다

### 배열 뒷부분에 요소 추가하기

#### push() 메소드

`배열.push(요소)`

배열 마지막 요소 뒤에 요소를 추가한다

```javascript
> const fruits = ['배', '바나나', '사과']
undefined

> fruits.push('파인애플')
4 // 추가된 배열의 길이를 반환

> fruits
(4) ['배', '바나나', '사과', '파인애플']
```

####  인덱스를 사용해 배열 뒷 부분에 추가하기

- 인덱스를 활용하여 배열 뒷 부분에 요소를 추가하면 원하는 인덱스 위치에 요소를 추가할 수 있다
- 만약 뛰어넘은 인덱스가 있다면 아무것도 없는 empty로 채워진다

```javascript
> const fruits = ['배', '바나나', '사과']
undefined

> fruits[10] = '귤'
'귤' // 추가된 요소를 반환

> fruits
(11) ['배', '바나나', '사과', empty × 7, '귤']
```

- 마지막 요소 뒤에 추가하고 싶다면 length 속성을 사용한다

```javascript
> const fruits = ['배', '바나나', '사과']
undefined

> fruits[fruits.length] = '귤'
'귤' // 추가한 요소를 반환

> fruits
(4) ['배', '바나나', '사과', '귤']
```

### 배열 요소 제거하기

#### 인덱스로 요소 제거하기

인덱스를 이용하여 요소를 제거할 때는 splice() 함수를 사용한다.

`배열.splice(인덱스, 제거할 요소의 개수)`

```javascript
> const fruits = ['배', '바나나', '사과', '귤']
undefined

> fruits.splice(1, 2) // 1번 인덱스 부터 2개
(2) ['바나나', '사과'] // 제거된 요소를 배열로 반환

> fruits
(2) ['배', '귤']
```

#### 값으로 요소 제거하기

값을 기반으로 요소를 제거하기 위해서는 배열 내부에서 특정값의 위치를 찾는 indexOf() 함수를 사용해서 위치를 추출한 뒤 spice()함수를 사용한다

```
const 인덱스 = 배열.indexOf(요소)
배열.splice(인덱스, 1)
```

```javascript
> const fruits = ['배', '바나나', '사과', '귤']
undefined

> const index = fruits.indexOf('사과')
undefined

> index
2

> fruits.splice(index, 1)
['사과'] // 제거된 요소의 배열을 반환

> fruits
(3) ['배', '바나나', '귤']
```

#### 문자열에서 indexOf()

문자열에서도 값을 찾는 indexOf()함수를 사용할 수 있는데 문자열 자료형을 매개변수로 받는다.

```javascript
> const StringA = "동해물과 백두산이 마르고 닳도록"
undefined

> StringA.indexOf("백두산")
5 // 문자열 자료의 시작 위치를 반환한다
```

### 배열의 특정 위치에 요소 추가하기

원하는 위치(인덱스)에 요소를 추가할 때도 splice() 함수를 사용한다

`배열.splice(인덱스, 0, 요소)`

```javascript
> const fruits = ['배', '바나나', '사과', '귤']
undefined

> fruits.splice(2, 0, '파인애플')
[] // 제거된 요소가 없으니 빈 배열을 반환

> fruits[2]
"파인애플" // 내가 원하는 인덱스 위치에 요소가 삽입됨

> fruits
(5) ['배', '바나나', '파인애플', '사과', '귤'] // 원래 위치의 인덱스는 뒤로 밀려남

> fruits.splice(1, 2, '포도')
(2) ['바나나', '파인애플'] // 제거된 요소들의 배열 반환

> fruits
(4) ['배', '포도', '사과', '귤']
```

## 04-2 반복문

### for in 반복문

```
for (const 반복 변수 in 배열 또는 객채) {
  문장
}
```

- for 반복문의 **반복 변수**(아래 코드에서는 i)에는 요소의 인덱스들이 들어옴
- 반복 변수를 활용하여 배열[반복 변수]를 사용하여 배열 요소에 접근하는 방식으로 사용


```javascript
<script>
    const todos = ['우유 구매', '스케쥴러 확인', '헬스장 등록']

    for (const i  in todos) {
      console.log(`${i}번째 할 일: ${todos[i]}`)
    }
  </script>
```

### for of 반복문

- 반복 변수에 인덱스가 아닌 실제 요소의 값이 들어옴

```
for (const 반복 변수 in 배열 또는 객채) { // 형태는 같으나 반복 변수에 요소의 값이 들어감
  문장
}
```

```javascript
<script>
    const todos = ['우유 구매', '스케쥴러 확인', '헬스장 등록']

    for (const todo of todos) {
      console.log(`오늘 할 일 : ${todo}`)
    }
  </script>
```

### for 반복문

for 반복문은 특정 횟수만큼 반복하고 싶을때 사용함

```
for (let i = 0; i < 반복 횟수', i++) { // let을 사용해야함, const 사용시 i의 숫자가 변하지 않아서 문제 발생
  문장
}
```

```javascript
  <script>
    let output = 0;

    for (let i = 1; i <= 100; i++) {
      output += 1;
    }
    alert(`1~100까지의 숫자를 모두 더하면 ${output}입니다.`)
  </script>
```

#### for 반복문과 배열 함께 사용하기

- 순서대로 반복

```javascript
  <script>
    const todos = ['우유 구매', '스케쥴러 확인', '헬스장 등록']

    for (let i = 0; i < todos.length; i++) {
      console.log(`${i}번째 할 일 : ${todos[i]}`)
    }
  </script>
```

- 역순으로 반복
  
```javascript
  <script>
    const todos = ['우유 구매', '스케쥴러 확인', '헬스장 등록']

    for (let i = todos.length - 1; i >= 0; i--) {
      console.log(`${i}번째 할 일 : ${todos[i]}`)
    }
  </script>
```

### while 반복문

- 특정 조건이 만족되면 계속해서 반복하는 반복문으로 if 문과 유사하다
- 조건을 만족한다면 계속해서 반복하므로 **무한 루프**(infinite loop)를 만들 수 있다

```
while (불 표현식) {
  문장
}
```

```javascript
  <script>
    let i = 0;

    while (confirm('계속 진행하시겠습니까?')) {
      alert(`${i}번째 반복입니다`)
      i++;
    }
  </script>
```

#### 배열과 함께 사용

```javascript
  <script>
    let i = 0;
    const array = [1, 2, 3, 4, 5]

    while (i < array.length) {
      console.log(`인덱스 ${i}의 값 : ${array[i]}`)
      i++;
    }
  </script>
```

### break 키워드

switch 조건문에서 사용하는 것처럼 조건문이나 반복문에서 벗어날 때 사용할 수 있다

- 반복 여부를 사용자에게 확인받아 반복 횟수를 출력하는 프로그램

```javascript
  <script>
    let i = 0;
    
    while (true) {
      alert(`${i+1} 번째 반복입니다.`)

      // 진행 여부
      if (!confirm("계속 반복하시겠습니까?")) {
        break
      }
      i++;
    }

    alert("프로그램을 종료합니다.")
  </script>
```

### continue 키워드

continue 키워드를 사용하면 반복문 내 continue 뒤의 내용을 실행하지 않고 반복문의 처음으로 돌아와 반복작업을 진행합니다.

- 1~10까지 홀수만 출력하는 프로그램

```javascript
  <script>
    for (let i = 1; i <= 10; i ++) {
      if (i % 2 === 0) {
        continue
      }
      alert(`${i}는 홀수 입니다.`)
    }
  </script>
```

---

# 05 함수

- 함수를 만들고 사용하는 방법을 배웁니다
- 함수의 기본을 익히기 위한 다양한 예제를 다룹니다
- 함수를 매개변수로 전달하는 특성을 배웁니다

## 05-1 함수의 기본 형태

함수는 코드의 집합으로 사용한다

- 반복되는 코드를 한 번만 정의해놓고 필요할 때마다 호출하여 반복 작업 횟수를 줄임
- 긴 프로그램을 기능별로 나누어 작성하면 모듈화로 코드의 가독성이 좋아짐
- 기능별(함수별)로 수정이 가능하므로 유지보수에 유리함

### 익명 함수

- 함수 출력에서 ƒ로 보이는 것처럼 별다른 이름이 없는 함수를 익명 함수라고 한다

`function() {}`

```javascript
  <script>
    const 함수 = function () { // 익명 함수를 함수라는 상수에 할당함
      console.log('함수 내부의 코드입니다...1')
      console.log('함수 내부의 코드입니다...2')
      console.log('함수 내부의 코드입니다...3')
      console.log('')
    }

    // 함수 호출
    함수()
    함수()

    // 출력
    console.log(typeof(함수))
    console.log(함수)
  </script>
```


```javascript
출력

함수 내부의 코드입니다...1
함수 내부의 코드입니다...2
함수 내부의 코드입니다...3

함수 내부의 코드입니다...1
함수 내부의 코드입니다...2
함수 내부의 코드입니다...3

function
ƒ () { // 이름이 없음
      console.log('함수 내부의 코드입니다...1')
      console.log('함수 내부의 코드입니다...2')
      console.log('함수 내부의 코드입니다...3')
      console.log('')
    }
```

### 선언적 함수

- 이름이 있는 함수를 선언적 함수라고 한다

```
function 함수() {
  
}
```

`let 함수 = function () {}`

```javascript
  <script>
    function 함수 () { // 함수라는 이름으로 함수를 선언함
      console.log('함수 내부의 코드입니다...1')
      console.log('함수 내부의 코드입니다...2')
      console.log('함수 내부의 코드입니다...3')
      console.log('')
    }

    // 함수 호출
    함수()
    함수()

    // 출력
    console.log(typeof(함수))
    console.log(함수)
  </script>
```


```javascript
출력

함수 내부의 코드입니다...1
함수 내부의 코드입니다...2
함수 내부의 코드입니다...3

함수 내부의 코드입니다...1
함수 내부의 코드입니다...2
함수 내부의 코드입니다...3

function
ƒ 함수 () { // 함수 라는 이름이 있음
      console.log('함수 내부의 코드입니다...1')
      console.log('함수 내부의 코드입니다...2')
      console.log('함수 내부의 코드입니다...3')
      console.log('')
    }
```

### 매개변수와 리턴값

- 함수 호출할 때 괄호에 들어가는 값이 매개변수
- 함수 호출 후 최종 결과를 리턴값

```
function 함수(매개변수, 매개변수, 매개변수 ...) {
  문장
  문장
  return 리턴값
}
```

### 나머지 매개변수

- 함수에서 매개변수의 개수가 정해지지 않았을 때 사용하는 함수를 **가변 매개변수 함수**라고 한다

`function 함수 이름(...나머지 매개변수) {}`

```javascript
  <script>
    function sample(...items) {
      console.log(items)
      console.log('')
    }

    sample(1, 2)
    sample(1, 2, 3)
    sample("샘플")
  </script>
```

```
출력

[1, 2]
[1, 2, 3]
["샘플"]
```

- 최솟값 구하기

```javascript
  <script>
    // 최솟값 구하기 함수
    function 최솟값(...items) {
      let min = items[0]

      for (const item of items) {
        if (item < min) {
          min = item
        }
      }
      return min
    }

    console.log('최솟값(32, 45, 63, 39, 35, 88 ,54, 25)')
    console.log(`= ${최솟값(32, 45, 63, 39, 35, 88 ,54, 25)}`)
  </script>
```

#### 나머지 매개변수와 일반 매개변수 조합하기

나머지 매개변수와 일반 매개변수를 하나의 함수에서 동시에 사용 그낭하다

`function 함수 이름(매개변수, 매개변수, 매개변수, ...나머지 매개변수) {}`

- 숫자들 모음, 배열 2종류의 자료의 최솟값을 구해주는 프로그램

```javascript
  <script>
    function 최솟값(first, ...rests) {
      let output
      let items

      if (Array.isArray(first)) { // 첫 자료가 배열이라면 1개의 배열을 입력 받음
        output = first[0]
        items = first
      } else if (typeof(first) === 'number') { // 첫 자료가 숫자라면 숫자 자료들을 입력 받음
        output = first
        items = rests
      }

      for (const item of items) {
        if (output > item) {
          output = item
        }
      }
      return output
    }
    console.log(`숫자 최솟값(52, 232, 42, 55) = ${최솟값(52, 232, 42, 55)}`)
    console.log(`배열 최솟값([52, 232, 42, 55]) = ${최솟값([52, 232, 42, 55])}`)
  </script>
```

#### 전개 연산자

배열을 전개해서 함수의 매개변수로 전달해주는 연산자를 의미한다. 나머지 배열 처럼 마침표 3개(...)를 사용한다

`함수 이름(...배열)`

```javascript
  <script>
    function sample(...items) {
      console.log(items)
    }

    const arr = [1, 2, 3, 4, 5]
    console.log('# 전개 연산자를 사용하지 않는 경우')
    console.log(`sample(arr) = ${sample(arr)}`)
    console.log('# 전개 연산자를 사용한 경우')
    console.log(`sample(...arr) = ${sample(...arr)}`)
  </script>
```

```
출력

# 전개 연산자를 사용하지 않는 경우
[Array(5)] <- 5개의 요소가 들어있는 배열
# 전개 연산자를 사용한 경우
[1, 2, 3, 4, 5] <- 숫자 5개가 하나씩
```

### 기본 매개변수

함수의 매개변수에 기본값을 지정하고 싶을 때 사용

`function 함수 이름(매개변수, 매개변수 = 기본값, 매개변수 = 기본값)`

- 왼쪽 매개변수부터 입력을 받으므로 기본값이 있는 경우 오른쪽에 작성해야한다

`function 함수 이름(a=기본값, b)`의 경우 a에 항상 값이 들어가므로 b에 값까지 넣는다면 항상 기본값을 사용할 일이 없다.

- 기본 매개변수를 사용한 임금 계산 프로그램

```javascript
<script>
    function earnings (name, wage=9000, hours=40) {
      console.log(`# ${name}님의 급여 정보`)
      console.log(`- 시급 : ${wage}`)
      console.log(`- 근무 시간 : ${hours}`)
      console.log(`- 급여 : ${wage * hours}원`)
      console.log('')
    }

    // 최저 임금으로 일하는 경우
      earnings('홍길동')

      // 시급 1만원으로 일하는 경우
      earnings('철수', 10000)

      // 시급 1만원으로 32시간 일하는 경우
      earnings('영희', 10000, 32)
  </script>
```

## 05-2 함수 고급

### 콜백 함수

- 자바스크립트에서는 함수도 하나의 자료형이므로 매개변수로 전달할 수 있다
- 매개변수로 전달하는 함수를 콜백(callback) 함수라고 한다

- 선언적 함수 방법

```javascript
  <script>
    function callTreeTimes (callback) {
      for (let i = 0; i < 3; i++) {
        callback(i)
      }
    }

    function print(i) {
      console.log(`${i}번째 함수 호출`)
    }
    
    callTreeTimes(print)
  </script>
```

- 익명 함수 방법

```javascript
  <script>
    function callTreeTimes(callback) {
      for (let i = 0; i < 3; i++) {
        callback(i)
      }
    }

    callTreeTimes(function (i) {
      console.log(`${i}번째 함수 호출`)
    })
  </script>
```

#### 콜백 함수를 활용하는 함수들

- forEach()

배열 내부의 함수로써 배열 내부의 요소를 사용하여 콜백 함수 호출

`function (value, index, array) {}`

```javascript
  <script>
    const numbers = [32, 45, 657, 86, 97]

    numbers.forEach(function(value, index, array) {
      console.log(`${index}번째 요소 : ${value}`)
    })
  </script>
```

- map()

map() 메소드는 콜백 함수에서 리턴한 값들을 기반으로 새로운 배열을 만드는 함수

```javascript
  <script>
    let numbers = [32, 45, 657, 86, 97]

    // 배열의 모든 값을 제곱
    numbers = numbers.map(function (value, index, array) {
      return value * value
    })

    // 출력
    numbers.forEach(console.log) // 매개변수로 console.log 메소드를 넘김
  </script>
```

```
출력 - value index array가 나옴

1024 0 Array(5)
2025 1 Array(5)
431649 2 Array(5)
7396 3 Array(5)
9409 4 Array(5)
```

- filter()

콜백 함수에서 리턴하는 값이 true인 값만 모아서 새로운 배열을 만드는 함수

```javascript
  <script>
    let numbers = [0, 1, 2, 3, 4, 5, 6]
    let evenNumbers = numbers.filter(function (value) { // value 만 사용
      return value % 2 === 0
    })

    console.log(`원래 배열 numbers : ${numbers}`)
    console.log(`짝수만 추출한 배열 evenNumbers : ${evenNumbers}`)
  </script>
```

### 화살표 함수

단순한 형태의 콜백 함수를 수비게 입력하고자 화살표(arrow) 함수 생성 방법이 잇다

```
(매개변수) => {

} 불 표현식 || 불 표현식이 거짓일 때 실행할 문장
```

또는 간편한 형태로 사용할 수 있다

`(매개변수) => 리턴값`

```javascript
  <script>
    let numbser = [0, 1, 2, 3, 4, 5, 6, 7, 8]
    
    // 배열의 메소드를 연속적으로 사용
    numbser
      .filter((value) => value % 2 === 0) // 짝수만 필터
      .map((value) => value * value) // 값 제곱
      .forEach((value) => { // 출력
        console.log(value)
      })
  </script>
```

### 타이머 함수

자바 스크립트에서는 특정 시간 이후에 콜백 함수를 호출할 수 있는 타이머(timer) 함수들이 있다

- 타이머 걸기

|함수 이름|설명|
|---|---|
|setTimeout(함수, 시간)|특정 시간 이후로 함수를 한 번 호출합니다|
|setInterval(함수, 시간)|특정 시간마다 함수를 호출합니다|

```javascript
  <script>
    setTimeout(() => {
      console.log('1초 후에 실행됩니다')
    }, 1 * 1000) // ms 기준

    let count = 0
    setInterval(() => {
      console.log(`2초마다 실행됩니다(${count}번째)`)
      count++
    }, 2 * 1000)
  </script>
```

- 타이머 취소

타이머를 종료할 때 사용하는 함수로 타이머_Id는 setTimeout()함수와 setInterval()함수의 리턴값으로 나오는 숫자입니다

|함수 이름|설명|
|---|---|
|clearTimeout(타이머_ID)|setTimeout()함수로 설정한 타이머를 제거합니다|
|clearInterval(타이머_ID)|setInterval()함수로 설정한 타이머를 제거합니다|

```javascript
  <script>
    let id
    let count = 1

    id = setInterval(() => {
      console.log(`2초마다 반복합니다. ${count}번째 반복`)
      count++
    }, 2 * 1000)

    setTimeout(() => {
      console.log('타이머를 종료합니다')
      clearInterval(id)
    }, 10 * 1000)
  </script>
```

### 좀 더 알아보기

#### 즉시 호출 함수

자바스크립트는 익명 함수를 생성하고 곧바로 호출하는 패턴을 많이 사용합니다. 이유를 알아봅시다

`(function () {}) ()`

자바 스크립트는 많은 블록을 사용함에 따라 이름 충돌 문제가 발생할 여지가 높습니다

```javascript

  <!-- 다른 곳에서 가져온 자바스크립트 코드 -->
  <script>
    let pi = 3.14
    console.log(`파이 값음 ${pi}입니다.`)
  </script>

  <!-- 내가 작성한 자바스크립트 코드 -->
  <script>
    let pi = 3.14
    console.log(`파이 값음 ${pi}입니다.`)
    // Uncaught SyntaxError SyntaxError: Identifier 'pi' has already been declared 발생
  </script>
```

이런 충돌을 피하기 위해 블록과 함수 블록을 사용함

```javascript
  <script>
    let pi = 3.14
    console.log(`파이 값음 ${pi}입니다.`)

    {
      let pi = 3.141592
      console.log(`파이 값음 ${pi}입니다.`)
    }
    console.log(`파이 값음 ${pi}입니다.`)

    // 함수 블록을 사용한 스코프 생성
    function smaple() {
      let pi = 3.141592
      console.log(`파이 값음 ${pi}입니다.`)
    }
    smaple()
    console.log(`파이 값음 ${pi}입니다.`)
  </script>
```

- 변수가 존재하는 범위를 **스코프**(scope)
- 블록이 다른 경우 내부 변수가 외부 변수를 가리는 현상을 **섀도잉**(shadowing)

#### 즉시 호출 함수 문제 해결하기

함수 블록을 사용하되 바로 만들어진 함수를 즉시 호출하는 방식으로 문제를 해결합니다

`(function () {}) ()`

```javascript
  <!-- 다른 곳에서 가져온 자바스크립트 코드 -->
  <script>
    let pi = 3.14
    console.log(`파이 값음 ${pi}입니다.`)
  </script>

  <!-- 내가 작성한 자바스크립트 코드 -->
  <script>
    (function () {
      let pi = 3.141592
      console.log(`파이 값음 ${pi}입니다.`)
    })()
  </script>
```

#### 엄격 모드

자바스크립트는 오류를 어느정도 무시하고 넘어갈 수 있습니다. 초기에는 이런 점이 편하다고 느낄 수 있으나 실수로 이어지기도 합니다.
그렇기에 자바스크립트에서 **엄격 모드**(strict mode)라는 기능을 통해 코드를 엄격하게 검사할 수 있습니다

```
<script>
  'use strict'
  문장
  문장
</script>
```

```javascript
  <script>
    data = 10
    console.log(data) // 에러 발생하지 않음
  </script>

  <script>
    'use strict'
    data = 10 // let, const 등의 키워드를 통해 선언하지 않음
    console.log(data) // 에러 발생
  </script>
```

- 일반적인 사용법

즉시 호출 함수를 만들고, 함수 블록 가장 위 쪽에 엄격 모드를 적용하는 경우가 많습니다.

```javascript
<script>
  (function() {
    'use strict'
    문장
    문장
  })()
</script>
```

#### 익명 함수와 선언적 함수의 차이

자바스크립트에서는 다른 프로그램 언어와 달리 익명 함수를 선호합니다.

- 익명 함수의 사용

익명 함수는 순차적으로 코드가 실행되면서 생성됩니다.

```javascript
  <script>
    let 익명함수
    
    익명함수 = function () {
      console.log('1번째 익명 함수입니다.')
    }
    익명함수 = function () {
      console.log('2번째 익명 함수입니다.')
    }

    익명함수()
  </script>
```

```
출력

2번째 익명 함수입니다.
```

- 선언적 함수 사용

선언적 함수는 순차적인 코드 진행이 일어나기 전에 생성됩니다. 따라서 같은 블록이라면 어디에서 함수를 호출해도 상관없습니다.

선언적 함수도 입력한 순서대로 생성되기에 같은 이름이라면 뒤에 작성한 코드가 덮어씌웁니다.

```javascript
  <script>
    선언적함수() // 선언적 함수를 먼저 읽은 뒤에 코드 진행이 이루어지므로 함수 앞에 작성해도 상관없음

    function 선언적함수() {
      console.log('1번째 선언적 함수입니다.')
    }
    function 선언적함수() {
      console.log('2번째 선언적 함수입니다.')
    }
  </script>
```

```
출력

2번째 선언적 함수입니다.
```

- 선언적 함수와 익명 함수의 조합

```javascript
  <script>
    함수 = function() {
      console.log('익명 함수입니다.')
    }

    function 함수 () {
      console.log('선언적 함수입니다.')
    }

    함수()
  </script>
```

선언적 함수가 먼저 선언된 이후 코드가 진행되고, 코드가 진행됨에 따라 익명 함수로 덮어씌워지므로 익명함수를 호출합니다.

이처럼 선언한 함수를 이름이 같은 이유로 덮어씌워지는 일은 굉장히 위험한 일이므로 안전하게 사용할 수 있는 익명 함수를 더 선호합니다.

- 블록이 다른 경우에 선언적 함수의 사용

자바스크립트에서는 블록이 여러개로 나뉘어지는 경우가 많으므로 실행 흐름의 예측이 힘들어지는 경우가 많아 익명함수를 더 선호합니다.

```javascript
  <script>
    선언적함수()

    function 선언적함수() {
      console.log('1번째 선언적 함수입니다.')
    }
  </script>

  <script>
    선언적함수()

    function 선언적함수() {
      console.log('2번째 선언적 함수입니다.')
    }
  </script>
  <script>
    선언적함수()
  </script>
```

```
출력

1번째 선언적 함수입니다.
2번째 선언적 함수입니다.
2번째 선언적 함수입니다.
```

#### let 사용의 의미

과거 자바스크립트에서는 var 키워드를 사용했습니다. var는 선언하는 과정에서 종종 이전 코드를 덮어씌우는 문제가 있었습니다.

하지만 현대의 let, const 키워드는 같은 이름으로 선언하는 문제를 차단하기 위해 오류를 발생시킵니다.

```javascript
  <script>
    let 함수 = function() {
      console.log('익명 함수입니다.')
    }

    function 함수() {
      console.log('선언적 함수입니다.')
    }

    함수()
    // Uncaught SyntaxError SyntaxError: Identifier '함수' has already been declared
    // '함수'라는 이름으로 선언 불가
  </script>
```

---

# 06 객체

- 객체를 생성하고 관리하는 방법을 배웁니다.
- 객체와 관련된 기본적인 문법을 익힙니다.

## 06-1 객체의 기본

**객체**(object)란 추상적인 의미로 '실제로 존재하는 사물'에 가깝다. 이름과 값으로 이루어진 **속성**(porperty)를 가진 자바스크립트의 기본 데이터 타입이다.

### 객체

- 여러 자료를 다룰 때 사용한다.
- 배열 또한 객체의 한 종류로 여러 데이터를 다룰 수 있다.

```
> typeof([])
"object" <- 객체
```

배열에서는 인덱스와 요소를 이용했다면 객체에서는 키와 값을 이용한다.
객체는 중괄호({})와 생성하고 자료들은 쉼표(,)로 연결해서 입력한다.

```javascript
객체 = {
  키: 값,
  키: 값,
  ...
}
```

```
<script>
  const product = {
    제품명: '건조 망고',
    유형: '식품',
    가격: '3200'
  }
</script>
```

- 객체 요소 접근 방법은 배열처럼 대괄호([])를 이용하거나 온점(.)을 이용한다

```javscript
product[제품명] <- "건조 망고"
product.유형 <- "식품"
```

### 속성과 메소드

배열 내부의 값을 **요소**(element)라고 하면, 객체 내부의 값은 **속성**(property)라고 한다.

#### 속성과 메소드 구분하기

객체 내부의 값 속성 중에서도 함수 자류형을 **메소드**(method)라고 한다.

```javascript
<script>
  const pet = {
    name: '뚠뚠',
    eat: fucntion (food) {
      console.log(`${food}를 맛있게 먹습니다`)
    }
  }

  pet.eat()
</script>
```

#### 메소드 내부에서 this 키워드 사용하기

메소드 내에서 자기 자신이 가진 속성을 사용하고 싶을 때 자신의 속성임을 분명하게 표시해야 하기에 this 키워드를 사용합니다.

```javascript
  <script>
    const pet = {
      name: '나비',
      eat: function (food) {
        alert(this.name + '는 ' + food + '을 먹습니다.')
      }
    }

    pet.eat('간식')
  </script>
```

### 동적으로 객체 속성 추가/제거

객체를 처음 생성한 후 속성을 추가/제거 하는 것을 '동적으로 속성을 추가/제거'한다고 합니다.

#### 동적으로 객체 속성 추가하기

동적으로 속성을 추가하고 싶다면 객체 속성을 지정하고 값을 입력하면 된다.

`객체.속성 = 값`

```javascript
  <script>
    const student = {
      이름: '홍길동'
    }
    student.취미 = '축구'
    student.장래희망 = '프로그래머'

    console.log(JSON.stringify(student, null, 2))
  </script>
```

#### 동적으로 객체 속성 제거하기

동적으로 속성을 제거하고 싶다면 delete 함수와 속성을 사용하면 된다.

`delete 객체.속성`

```javascript
  <script>
    const student = {
      이름: '홍길동',
      취미: '축구',
      장래희망: '프로그래머'
    }

    delete student['이름']
    delete student.장래희망
    
    console.log(JSON.stringify(student, null, 2))
  </script>
```

### 메소드 간단 선언 구문

최신 버전의 자바스크립트에서는 메소드를 좀 더 쉽게 선언할 수 있는 전용 구문이 추가되었습니다.

```javascript
  <script>
    const pet = {
      name: '나비',
      // eat: function(food) { function 부분을 생략
      eat(food) {
        alert(this.name + '는 ' + food + '을 먹습니다.')
      }
    }
    
    pet.eat('간식')
  </script>
```

### 화살표 함수를 사용한 메소드

function() {} 형태로 선언하는 익명함수와 () => {} 형태로 선언하는 화살표 함수는 객체의 메소드로 사용될 때 **this** 키워드를 다루는 방식이 다릅니다.

- 익명 함수 this : 객체 본인
- 화살표 함수 this : 객체 생성 당시 상위 전역 객체

```javascript
  <script>
    const test = {
      a: function() { // 익명 함수
        console.log(this)
      },
      b: () => {
        console.log(this)
      }
    }
    
      test.a()
      // {a: ƒ, b: ƒ}
      // 코드에서 test 객체 출력
      test.b()
      // Window {window: Window, self: Window, document: #document, name: '', location: Location, …}
      // 윈도우 객체 출력
  </script>
```

## 06-2 객체의 속성과 메소드 사용하기

자바스브립트에서는 자료를 크게 **기본 자료형**(primitives)과 **객체 자료형**(object)로 구분할 수 있습니다.

자바스크립트는 매우 유연하기에 기본 자료형이 객체 자료형이 될 수 있습니다.

### 객체 자료형

속성과 메서드를 가질 수 있는 모든 것이 객체입니다.

- 배열도 객체이며 배열인지 확인하려면 **Array.isArray()**라는 메서드를 사용합니다.

```
> const a = []
undefined

> a.sample = 10
10

> a.sample
10

> typeof(a)
object

> Array.isArray(a)
true
```

- 함수 또한 객체이며 typeof() 메서드에서 'function'으로 나옵니다.

```
> function b () {}
undefined

> b.sample = 10
10

> b.sample
10

> typeof(b)
'function' <- 함수로 나오며 객체이다
```

### 기본 자료형

자바스크립트에서는 실체가 있는 것(undefined와 null등이 아닌 것) 중에 객체가 아닌 것을 **기본 자료형**(primitive types 또는 primitives)라고 합니다.

종류 : 숫자, 문자열, 불

```
> const a = 273
undefined

> a.sampel = 10
10 <- 속성이 생성된 것처럼 보이지만 실제로 속성은 만들어지지 않습니다.

> a.sample
undeifned

> const b = '샘플'
undeifned

> const c = true
undeifned

> b.smaple = 10
10

> c.smaple = 10
10

> b.smaple
undeifned

> c.sample
undeifned
```

### 기본 자료형을 객체로 선언하기

자바스크립트에서 기본 자료형을 객체로 선언하는 방법(Number, String, Boolean)을 제공합니다.

`const 객체 = new 객체 자료형 이름()`

```
new Number(10)
new Stirng('샘플')
new Boolean(true)
```

```javascript
> const a = new Number(55)
undeifned

> typeof a
'object'

> a.sample = 10
10

> a.sample
10

> a
Number {55, sample: 10}  <- 콘솔에서 간단하게 객체로 출력해준다.

> a + 10
20  <- 단순한 숫자처럼 사용할 수 있다.

> a.valueOf()
55  <- vaueOf()를 사용하면 값을 추출할 수 있다.

> const b = Number(22)  <- new 키워드를 작성하지 않으면 기본 자료형으로 자동 변환됩니다.
undefined

> typeof b
"number" 
```

### 기본 자료형의 일시적 승급

이전에 사용했던 '문자'.length처럼 사용가능한 메소드들이 있었다. 하지만 원칙적으로는 기본 자료형은 속성과 메소드를 가질 수 없다.

자바스크립트에서는 편리성을 위해 기본 자료형의 속성과 메소드를 호출할 때 일시적으로 기본 자료형을 객체로 승급시켜준다. 그래서 속성과 메소드를 사용할 수 있습니다.

이러한 승급은 일시적이기에 객체로 유지되지 않습니다.

```javascript
> const a = '안녕하세요'
undefined

> a.anchor('sample')
'<a name="sample">샘플</a>'

> a.length
2

> a.sample = 10
10

> a.sample
undefined
```

### 프로토타입으로 메소드 추가하기

기본 자료형에 속성과 메소드를 사용하기 위해 숫자 객체 또는 문자 객체와 같은 전체 객체의 속성과 메소드를 변경할 수 있습니다.

어떤 객체에 **prototype**이라는 속성이 바로 객체의 틀이라고 할 수 있습니다.
따라서 prototype 객체에 속성과 메소드를 변경하면 모든 객체(와 기본 자료형)에서 해당 속성과 메소드를 사용할 수 있습니다.

```
객체 자료형 이름.prototype.속성 = 값
객체 자료형 이름.prototype.메소드 이름 = function () {}
```

- 속성

```javascript
> Number.prototype.sample = 10
10

> const a = 55
undefined

> a.smaple // sample의 속성을 가지고 있습니다.
55
```

- 메소드

```javascript
  <script>
    Number.prototype.power = function (n = 2) {
      return this.valueOf() ** n
    }

    const a = 3
    console.log(a.power())
    console.log(a.power(3))
    console.log(a.power(4))
  </script>
```

숫자 자료형은 기본적으로 연산이 바로 가능하지만 valueOf() 메소드를 통해 값을 추출해서 사용하는 것을 선호합니다.

- 예제

보통 indexOf() 메소드를 사용하면 문자열과 배열 내부의 값의 위치의 인덱스 값을 반환합니다.

```javascript
> const a = '안녕하세요'
undefined

> a.indexOf('안녕')
0

> a.indexOf('하세')
2

> a.indexOf('샘플')
-1 // 문자열 내에 없는 문자열이라면 -1을 출력합니다.

> const b = [1, 2, 3]
undefined

> b.indexOf(2)
1

> b.indexOf(4)
-1
```

따라서 문자열 내부에 특정 값이 존재하다면 `문자열.indexOf(찾고자하는 문자열) >= 0`을 사용하면 true/false의 불 값을 받을 수 있습니다.

배열은 `배열.indexOf(찾고자하는 요소) >= 0`을 사용하면 됩니다.

```javascript
  <script>
    String.prototype.contain = function (data) {
      return this.indexOf(data) >= 0
    }

    Array.prototype.contain = function (data) {
      return this.indexOf(data) >= 0
    }

    const str = '안녕하세요'
    console.log(`${str}안에 '안녕'이 있습니까? : ${str.contain('안녕')}`)
    console.log(`${str}안에 '샘플'이 있습니까? : ${str.contain('샘플')}`)
    console.log('')

    const arr = [1, 2, 3, 4, 5]
    console.log(`${arr} 안에 5가 있습니까? : ${arr.contain(5)}`)
    console.log(`${arr} 안에 6가 있습니까? : ${arr.contain(6)}`)
  </script>
```

```
출력
안녕하세요안에 '안녕'이 있습니까? : true
안녕하세요안에 '샘플'이 있습니까? : false

1,2,3,4,5 안에 5가 있습니까? : true
1,2,3,4,5 안에 6가 있습니까? : false

```

### Number 객체

기본 자료형과 연결된 객체로 자주 사용하는 것들을 정리

#### 숫자 N번째 자릿수까지 출력하기 toFixed()

소수점 이하 몇 자리까지만 출력하고 싶을 때 사용합니다.

```javascript
> const pi = 3.141592
undefined

> pi.toFixed(2)
3.14

> pi.tofixed(3)
3.142 // 반올림 합니다.
```

#### NaN과 Infinity 확인하기: isNaN(), isFinite()

어떤 숫자가 NaN(Not a Number)인지 확인하거나 무한(Infinity)인지 확인할 때 사용합니다.
Number 객체 뒤에 점을 찍고 사용합니다.

```
Number.isNaN()
Number.isFinite()
```

```javascript
> const a = Number('숫자로 변환이 안되는 경우')
undefined

> a
NaN

> a === NaN
false // NaN과 비교 연산자 ===를 사용해서는 확인할 수 없습니다.

> Number.isNaN(a)
true
```

```javascript
> const a = 10 / 0
undefined
> a
Infinity // 양의 무한대를 생성

> const b = -10 / 0
undefined
> b
-Infinity // 음의 무한대를 생성

> a === Infinity
true // 비교 연산자로 비교 가능

> Number.isFinite(a)
false

> Number.isFinite(b)
false

> Number.isFinite(5)
true
```

### String 객체

String 객체의 기본 메서드

#### 문자열 양 끝의 공백 없애기: trim()

문자열 앞 뒤의 공백을 없애는 메소드로 사용자의 실수나 악의적인 목적을 방지하는데 주로 사용합니다.

`문자열.trim()`

```javascript
> const a = '   공백   '
undefined

> const b = `
줄바꿈   ` // 줄바꿈 입력시 '' 이 아닌 ``을 사용한다

> a.trim()
'공백'

> b.trim()
'줄바꿈'

> a
'   공백   ' // trim() 함수가 원본 데이터에 영향을 주지는 않는다.
```

#### 문자열을 특정 기호로 자르기: split()

문자를 특정 문자열을 기준으로 잘라 배열을 리턴받습니다.

`문자열.spit(특정 문자열)`

```javascript
> const input = '1,2,3,4,5'
undefined

> const arr = input.split(',')
undefined

> arr
(5) ['1', '2', '3', '4', '5']

> const numArr = arr.map((value) => Number(value))
undefined

> numArr
(5) [1, 2, 3, 4, 5]
```

### JSON 객체

기본 자료형 외 자바스크립트에서 제공하는 내장 객체중 하나입니다.

인터넷에서 문자열로 데이터를 주고 받을 때 사용되는 자료 표현 방식 중 CSV, SML, CSON 등이 있지만 JSON이 가장 많이 사용됩니다.

JSON은 JavaScript Object Notaion의 약자로 자바스크립트의 객체처럼 자료를 표현하는 방식입니다.

- 자료 예시

```
[{
  "name": "혼자 공부하는 자바스크립트",
  "price": 18000,
  "publisher": "한빛미디어"
}, {
  "name": "HTML5 웹 프로그래밍 입문",
  "price": 26000,
  "publisher": "한빛아카데미"
}]
```

하나의 자료는 중괄호({}) 여러 개의 자료는 대괄호([])로 표현한다.

JSON 규칙

- 값을 표현할 때는 문자열, 숫자, 불 자료형만 사용 가능하다.(함수 등은 사용 불가)
- 문자열은 반드시 큰따옴표("")로 만들어야 한다.
- 키(key)에도 반드시 따옴표를 붙여야 한다.

#### 자바스크립트 객체를 JOSN 문자열로: JSON.stringify()

자바스크립트 객체를 JSON 문자열로 변환

```javascript
JSON.stringify(데이터) // 매개변수 하나만 넣으면 한 줄로 변환해주는데 보통 이렇게 사용
`JSON.stringify(데이터, null(어떤 속성만 선택해서 추출할 때 사용하지만 대부분 null 사용), 숫자(들여쓰기 칸 갯수로 주로 2를 사용))
// 들여쓰기와 줄바꿈을 통해 사람이 보기 편하게 해줌
```

```javascript
  <script>
    const data = [{
      "name": "혼자 공부하는 자바스크립트",
      "price": 18000,
      "publisher": "한빛미디어"
    }, {
      "name": "HTML5 웹 프로그래밍 입문",
      "price": 26000,
      "publisher": "한빛아카데미"
    }]

    console.log(JSON.stringify(data)) // 한줄로 출력
    console.log(JSON.stringify(data, null, 2)) // 보기 좋게 포맷팅해서 출력
  </script>
```

```
출력

[{"name":"혼자 공부하는 자바스크립트","price":18000,"publisher":"한빛미디어"},{"name":"HTML5 웹 프로그래밍 입문","price":26000,"publisher":"한빛아카데미"}]
[
  {
    "name": "혼자 공부하는 자바스크립트",
    "price": 18000,
    "publisher": "한빛미디어"
  }스
  {
    "name": "HTML5 웹 프로그래밍 입문",
    "price": 26000,
    "publisher": "한빛아카데미"
  }
]
```

#### JSON 문자열을 자바스크립트 객체로 전개: JSON.parse()

`JSON.parse(json데이터)`

```javascript
  <script>
    const data = [{
      name: "혼자 공부하는 자바스크립트",
      price: 18000,
      publisher: "한빛미디어"
    }, {
      name: "HTML5 웹 프로그래밍 입문",
      price: 26000,
      publisher: "한빛아카데미"
    }]

    const json = JSON.stringify(data)
    console.log(json)

    console.log(JSON.parse(json))
  </script>
```

### Math 객체

수학과 관련된 연산을 수행할 때 Math객체를 사용합니다.

pi, e와 같은 과학 상수나 Math.sin(), Math.cos(), Math.tan()와 같은 삼각함수도 있습니다.

#### 랜덤한 숫자를 생성할 때: Math.random()

0이상 1미만(0<= 데이터 <1)의 랜덤한 숫자를 생성하여 여러 처리를 한 후 사용합니다.

`Math.random`

```javascript
  <script>
    const num = Math.random()

    console.log('# 랜덤한 숫자')
    console.log('0 ~ 1 사이의 랜덤한 숫자: ' , num)
    console.log('')

    console.log('# 랜덤한 숫자 범위 확대')
    console.log('0 ~ 10 사이 랜덤한 숫자: ' , num * 10)
    console.log('0 ~ 50 사이 랜덤한 숫자: ' , num * 50)
    console.log('')

    console.log('# 랜덤한 숫자 범위 이동')
    console.log('-5 ~ 5 사이 랜덤한 숫자: ' , num * 10 - 5)
    console.log('-25 ~ 25 사이 랜덤한 숫자: ' , num * 50 - 25)
    console.log('')

    console.log('# 랜덤한 정수 숫자')
    console.log('-5 ~ 5 사이 랜덤한 정수 숫자: ' , Math.floor(num * 10 - 5))
    console.log('-25 ~ 25 사이 랜덤한 정수 숫자: ' , Math.floor(num * 50 - 25))
  </script>
```

- 소수점 반올림: Math.round()
- 소수점 올림: Math.ceil()
- 소수점 내림: Math.floor()

### 외부 script 파일 읽어들이기

하나의 HTML 페이지 내부에 script 태그를 만들고 자바스크립트를 입력하는 방식으로 큰 규모를 진행하기 어려워집니다. 따라서 파일을 분리하는 게 좋습니다.

별도의 자바스크립트 파일을 생성한 후 \<script\> 태그를 사용합니다.

주의할 점은 HTML 파일은 위에서 아래로 태그를 읽으면서 차근차근 처리하기에 외부 스크립트의 데이터를 사용하고 싶다면 사용하고자 하는 문장보다 위에 작성해야 합니다.

- 메인 HTML

```javascript
  <script src="외부-JS.js"></script> <!-- 메인 HTML의 script 태그 위에 작성해야함 -->
  <script>
    console.log('# 메인 HTML의 script 태그')
    console.log('smaple의 값: ', smaple)
  </script>
```

- 외부 JS 파일

```javascript
console.log('# 외부-JS 파일')
const smaple = 10
```

- 출력

```
# 외부-JS 파일
# 메인 HTML의 script 태그
smaple의 값:  10
```

### Lodash 라이브러리

내가 만든 외부 자바스크립트 파일이 아닌, 다른 사람이 만든 외부 자바스크립트 파일도 사용할 수 있습니다. 이렇게 다른 사람들이 다양한 함수와 클래스를 묶어 제공해주는 것을 **외부 라이브러리**라고 합니다.

**유틸리티 라이브러리**는 개발할 때 보조적으로 사용하는 함수들을 제공해주는 라이브러리입니다.
종류로 underscore, Lodash 등 다양한 라이브러리가 있는데, 최근 많이 사용되는 **Lodash 라이브러리**를 살펴보겠습니다.

- 링크 : https://lodash.com

#### 외부 라이브러리 적용 방법

1. 위의 링크를 통해 직접 JS 파일을 다운받아 추가하기
2. CDN을 활용하기

#### CDN

CDN(Content Delivery Network)이란 컨텐츠 전송 네트워크란 의미입니다.

웹 콘텐츠를 전 세계에 분산 저장하고 사용장게ㅔ 가장 가까운 서버에서 제공하는 기술로, 웹 사이트의 로딩 속도를 빠르게 하고, 트패릭 부담을 줄이며 안정적인 서비스를 제공합니다.

#### min 버전

min 버전의 자바스크립트 파일은 자바스크립트 코드를 **집핑**(zipping)한 파일을 의미합니다.

코드 내부의 주석이나 줄바꿈이나 공백을 전부 제거하여 데이터의 용량을 줄여 프로그램을 가볍게 하는데 용이합니다.

#### _ 메소드

Lodash 라이브러리는 객체 이름을 **밑줄(_)**로 활용하여 많은 메소드를 담고 있습니다. 처음 사용할 경우 당황스러울 수 있으나 단순하게 _.메소드()로 생각하면 편합니다

`_.메소드()`

```javascript
  <script src="https://cdn.jsdelivr.net/npm/lodash@4.17.21/lodash.min.js"></script>
  <script>
    const books = [{
      name: "혼자 공부하는 자바스크립트",
      price: 18000,
      publisher: "한빛미디어"
    }, {
      name: "HTML5 웹 프로그래밍 입문",
      price: 26000,
      publisher: "한빛아카데미"
    }, {
      name: "머신러닝 딥러닝 실전 개발 입문",
      price: 30000,
      publisher: "위키북스"
    }, {
      name: "딥러닝을 위한 수학",
      price: 28000,
      publisher: "위키북스"
  }]

  const output = _.sortBy(books, (book) => book.price)
  console.log(JSON.stringify(output, null, 2))
  </script>
```

```
출력

[
  {
    "name": "혼자 공부하는 자바스크립트",
    "price": 18000,
    "publisher": "한빛미디어"
  },
  {
    "name": "HTML5 웹 프로그래밍 입문",
    "price": 26000,
    "publisher": "한빛아카데미"
  },
  {
    "name": "딥러닝을 위한 수학",
    "price": 28000,
    "publisher": "위키북스"
  },
  {
    "name": "머신러닝 딥러닝 실전 개발 입문",
    "price": 30000,
    "publisher": "위키북스"
  }
```

## 06-3 객체와 배열 고급

### 속성 존재 여부 확인

객체 내부에 어떤 속성이 있는지 확인해보기 위해 사용하는 코드로 없는 속성은 undefined 자료형이 나오기에 비교하는 조건문을 사용합니다.

```javascript
  <script>
    const book = {
      name: '혼자 공부하는 자바스크립트',
      price: 18000,
      publisher: '한빛미디어'
    }

    if (book.name !== undefined) {
      console.log('name 속성이 있습니다.')
    } else {
      console.log('name 속성이 없습니다.')
    }

    if (book.author !== undefined) {
      console.log('author 속성이 있습니다.');
    } else {
      console.log('author 속성이 없습니다.');
    }
  </script>
```

- 더 간략하게 사용하기

객체의 특정 속성이 false 로 변환될 수 있는 값(0, false, 빈 문자열)이 아닐 때 사용할 수 있는 코드입니다.

```javascript
  if (book.name) {
    console.log('name 속성이 있습니다.')
  } else {
    console.log('name 속성이 없습니다.')
  }

  if (book.author) {
    console.log('author 속성이 있습니다.');
  } else {
    console.log('author 속성이 없습니다.');
  }
```

책 제목의 경우 문자열 데이터이기에 빈 문자열('')이 될 가능성이 있지만, 책 제목이 빈 문자열이면 데이터가 없는 경우나 마찬가지기에 책 제목이 비어있지 않다는 원칙이 있다는 전제하에 안전하게 사용할 수 있습니다.

더 짧게 사용가능합니다.

```
book.name || console.log('name 속성이 있습니다.')
book.author ? console.log('author 속성이 있습니다.') : console.log('author 속성이 없습니다.')
```

#### 속성이 없다면 속성 지정해주기

```javascript
  <script>
    const book = {
      name: '혼자 공부하는 자바스크립트',
      price: 18000,
      publisher: '한빛미디어'
    }

    book.name = book.name !== undefined ? book.name : '제목 미정'
    book.author = book.author !== undefined ? book.author : '작자 미상'

    // 짧은 방식
    book.name = book.name || '제목 미정'
    book.author = book.author || '작자 미상'
    
    console.log(JSON.stringify(book, null, 2));
  </script>
```

### 배열 기반 다중 할당

최신 자바스크립트에서는 배열과 비슷한 방식으로 작성하여 여러 개의 변수에 값을 할당하는 다중 할당 기능이 추가되었습니다.

`[식별자, 식별자, 식별자, ...] = 배열`

```javascript
> let [a, b] = [1, 2] // a=1, b=2 할당
undefined
> console.log(a, b)
1 2
undefined

> [a, b] = [b, a] // a=b, b=a 할당
(2) [2, 1]
console.log(a, b)
2 1
undefined
```

- 배열의 크기가 같을 필요가 없다
- const 키워드도 사용 가능하다

```javascript
> let arrayA = [1, 2, 3, 4, 5]
undefined
> const [a, b, c] = arrayA
undefined
> console.log(a, b, c)
1 2 3
undefined
```

### 객체 기반 다중 할당

최신 자바스크립트에서는 객체 내부에 있는 속성을 꺼내서 변수로 할당할 때 사용할 수 있는 코드를 제공합니다.

```javascript
{ 속성 이름, 속성 이름} = 객체
{ 식별자=속성 이름, 식별자= 속성 이름} = 객체
```

```javascript
  <script>
    const book = {
      name: '혼자 공부하는 자바스크립트',
      price: 18000,
      publisher: '한빛미디어'
    }

    const {name, price} = book
    console.log('# 속성 이름 그대로 꺼내서 출력하기');
    console.log(name, price);
    console.log('');

    const {a=name, b=price} = book
    console.log('# 다른 이름으로 속성 꺼내서 출력하기');
    console.log(`a : ${a}, b: ${b}`);
  </script>
```

```
출력

# 속성 이름 그대로 꺼내서 출력하기
혼자 공부하는 자바스크립트 18000

# 다른 이름으로 속성 꺼내서 출력하기
a : 혼자 공부하는 자바스크립트, b: 18000
```

### 배열 전개 연산자

배열과 객체는 할당할 때 **얕은 복사**라는 것이 이루어집니다.

```javascript
  <script>
    const 물건_A = ['우유', '식빵']
    const 물건_B = 물건_A
    물건_A.push('고구마')
    물건_B.push('토마토')

    console.log(물건_A);
    console.log(물건_B);
  </script>
```

```
출력

(4) ['우유', '식빵', '고구마', '토마토']
(4) ['우유', '식빵', '고구마', '토마토']
```

배열을 복사해서 새로운 배열에 넣어준 것 같지만 실제로는 메모리를 참조하는 **참조 복사(얕은 복사)**만 일어납니다.

반대로 **깊은 복사**는 기존 배열과 똑같은 새로운 배열인 클론을 만드는 방법입니다. 
이때 사용하는 방법이 **전개 연산자**를 사용합니다.

`[...배열]`

```javascript
  <script>
    const 물건_A = ['우유', '식빵']
    const 물건_B = [...물건_A]
    const 물건_C = ['파인애플', ...물건_B, ...물건_A] // 요소를 추가하거나 여러개의 배열도 추가 가능
    물건_A.push('고구마')
    물건_B.push('토마토')

    console.log(물건_A);
    console.log(물건_B);
    console.log(물건_C);
  </script>
```

```
출력

(3) ['우유', '식빵', '고구마']
(3) ['우유', '식빵', '토마토']
(5) ['파인애플', '우유', '식빵', '우유', '식빵']
```

### 객체 전개 연산자

객체도 깊은 복사를 할 때 전개 연산자를 사용할 수 있습니다.

`{...객체}`

- 얕은 복사

```javascript
  <script>
    const 구름 = {
      이름: '구름',
      나이: 6,
      종족: '강아지'
    }

    const 별 = 구름
    별.이름 = '별'
    별.나이 = 1

    console.log(JSON.stringify(구름, null, 2));
    console.log(JSON.stringify(별, null, 2));
  </script>
```

```
출력

{
  "이름": "별",
  "나이": 1,
  "종족": "강아지"
}
{
  "이름": "별",
  "나이": 1,
  "종족": "강아지"
}
```

- 깊은 복사

```javascript
  <script>
    const 구름 = {
      이름: '구름',
      나이: 6,
      종족: '강아지'
    }

    const 별 = {...구름}
    별.이름 = '별'
    별.나이 = 1

    console.log(JSON.stringify(구름, null, 2));
    console.log(JSON.stringify(별, null, 2));
  </script>
```

```
출력

{
  "이름": "구름",
  "나이": 6,
  "종족": "강아지"
}
{
  "이름": "별",
  "나이": 1,
  "종족": "강아지"
}
```

- 전개 연산자를 사용하여 객체 요소 추가

```javascript
  <script>
    const 구름 = {
      이름: '구름',
      나이: 6,
      종족: '강아지'
    }

    const 별 = {
      ...구름,
      이름: '별', // 변경
      나이: '6',
      예방접종: true // 추가
    }

    const 달 = {
      이름: '달',
      종족: '고양이',
      ...구름 // 뒤에 작성하면 덮어씌워지므로 주의해야함
    }

    console.log(JSON.stringify(구름, null, 2));
    console.log(JSON.stringify(별, null, 2));
    console.log(JSON.stringify(달, null, 2));
  </script>
```

```
출력

{
  "이름": "구름",
  "나이": 6,
  "종족": "강아지"
}
{
  "이름": "별",
  "나이": "6",
  "종족": "강아지",
  "예방접종": true
}
{
  "이름": "구름",
  "종족": "강아지",
  "나이": 6
}
```

---

# 07 문서 객체 모델
## 07-1 문서 객체 조작하기

## 07-2 이벤트 활용

 

# 08 예외 처리
## 08-1 구문 오류와 예외

## 08-2 예외 처리 고급

 
# 09 클래스
## 09-1 클래스의 기본 기능

## 09-2 클래스의 고급 기능

# 10 리액트 라이브러리

## 10-1 리액트의 기본

## 10-2 리액트와 데이터

# 부록 A 


## 정답 및 해설

## 찾아보기


---
