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
    - [DOMContentLoaded 이벤트](#domcontentloaded-이벤트)
    - [문서 객체 가져오기](#문서-객체-가져오기)
    - [글자 조작하기](#글자-조작하기)
    - [속성 조작하기](#속성-조작하기)
    - [스타일 조작하기](#스타일-조작하기)
    - [문서 객체 생성하기](#문서-객체-생성하기)
    - [문서 객체 이동하기](#문서-객체-이동하기)
    - [문서 객체 제거하기](#문서-객체-제거하기)
    - [이벤트 설정하기](#이벤트-설정하기)
    - [이벤트 제거하기](#이벤트-제거하기)
  - [07-2 이벤트 활용](#07-2-이벤트-활용)
    - [이벤트 모델](#이벤트-모델)
    - [키보드 이벤트](#키보드-이벤트)
    - [키보드 키 코드 사용하기](#키보드-키-코드-사용하기)
    - [이벤트 발생 객체](#이벤트-발생-객체)
    - [글자 입력 양식 이벤트](#글자-입력-양식-이벤트)
      - [드롭다운 목록 활용하기](#드롭다운-목록-활용하기)
      - [체크 박스](#체크-박스)
      - [라디오 버튼](#라디오-버튼)
    - [기본 이벤트 막기](#기본-이벤트-막기)
    - [입력 양식 초점](#입력-양식-초점)
    - [localStorage 객체](#localstorage-객체)
- [08 예외 처리](#08-예외-처리)
  - [08-1 구문 오류와 예외](#08-1-구문-오류와-예외)
    - [오류의 종류](#오류의-종류)
      - [구문 오류](#구문-오류)
      - [예외](#예외)
    - [기본 예외 처리](#기본-예외-처리)
    - [고급 예외 처리](#고급-예외-처리)
      - [finally 구문의 사용 이유](#finally-구문의-사용-이유)
  - [08-2 예외 처리 고급](#08-2-예외-처리-고급)
    - [예외 객체](#예외-객체)
    - [예외 강제 발생](#예외-강제-발생)
    - [예외를 강제로 발생시키는 이유](#예외를-강제로-발생시키는-이유)
- [09 클래스](#09-클래스)
  - [09-1 클래스의 기본 기능](#09-1-클래스의-기본-기능)
    - [추상화](#추상화)
    - [같은 형태의 객체 만들기](#같은-형태의-객체-만들기)
    - [객체를 처리하는 함수](#객체를-처리하는-함수)
    - [객체의 기능을 메소드로 추가하기](#객체의-기능을-메소드로-추가하기)
      - [객체 생성 함수](#객체-생성-함수)
    - [클래스 선언하기](#클래스-선언하기)
    - [생성자](#생성자)
    - [메소드](#메소드)
  - [09-2 클래스의 고급 기능](#09-2-클래스의-고급-기능)
    - [상속](#상속)
    - [private 속성과 메소드](#private-속성과-메소드)
    - [게터와 세터](#게터와-세터)
    - [static 속성과 메소드](#static-속성과-메소드)
    - [오버라이드](#오버라이드)
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

- DOMcontentLoaded 이벤트를 사용하는 이유를 이해합니다.
- 문서 객체를 가져오거나 생성하는 방법을 이해합니다.
- 문서 객체의 글자, 속성, 스타일을 조작하는 방법을 이해합니다.
- 다양한 이벤트의 사용 방법을 이해합니다.
- 화면에 보이는 애플리케이션을 만드는 방법을 이해합니다.

## 07-1 문서 객체 조작하기

HTML 언어에서 html, head, body 등을 **요소**(element)라고 합니다.

그리고 자바스크립트에서는 이를 **문서 객체**(document object)라고 부릅니다. 따라서 문서 객체를 조작한다는 말은 HTML 요소들을 조작한다는 의미입니다.

문서 객체를 조합해서 만든 전체적인 형태를 **문서 객체 모델**(DOM, Document Object Model)이라고 합니다. 

문서 객체를 조작하는 작업은 매우 복잡하기에 제이쿼라와 같은 라이브러리나 리액트와 같은 프레임 워크를 사용해 쉽게 조작할 수 있도록 발전했습니다.

### DOMContentLoaded 이벤트

문서 객체를 조작할 때는 DOMContentLoaded 이벤트를 사용합니다.

```
document.addEventListenr('DOMContentLoaded', () => { // 오탈자 주의
  문장
})
```

document.body.innerHTML은 문서(documnet)의 바디(body) 안에 있는 HTML 코드(innerHTML)를 자바스크립트로 조작할 수 있게 해주는 코드입니다.

```javascript
<!DOCTYPE html>
<html>
<head>
  <title>자바스크립트를 통해 HTML 코드 조작하기</title>
  <script>
    // HTMl 태그를 쉽게 만들 수 있는 콜백 함수를 선언합니다.
    const h1 = (text) => `<h1>${text}</h1>`
  </script>
  <script>
    // body 태그가 생성되기 이전에 script 태그로 body 태그를 조작하기에 에러가 발생하며 실행되지 않습니다.
    // Uncaught TypeError TypeError: Cannot read properties of null (reading 'innerHTML')
    document.body.innerHTML += h1('1번째 script 태그')
  </script>
</head>
<body>
  <script>
    document.body.innerHTML += h1('2번째 script 태그')
  </script>
  <h1>1번째 h1 태그</h1>
  <script>
    document.body.innerHTML += h1('3번째 script 태그')
  </script>
  <script>
    console.log(document.body.innerHTML);
  </script>
  <!-- 아래 <h1>태그는 log로 찍히지 않음 -->
  <h1>2번째 h1 태그</h1>
</body>
</html>
```

```
크롬 출력

2번째 script 태그
1번째 h1 태그
3번째 script 태그
2번째 h1 태그
```

```
콘솔 출력

  <script>
    document.body.innerHTML += h1('2번째 script 태그')
  </script><h1>2번째 script 태그</h1>
  <h1>1번째 h1 태그</h1>
  <script>
    document.body.innerHTML += h1('3번째 script 태그')
  </script><h1>3번째 script 태그</h1>
  <script>
    console.log(document.body.innerHTML);
  </script>
```

HTMl 페이지는 코드를 위에서 아래로 차례대로 실행합니다. 따라서 body태그가 생성되기 전에 body에 접근할 수 없습니다.

- DOMContentLoaded 방식

DOMContentLoaded 이벤트는 웹 브라우저가 문서 객체를 모두 읽고 나서 실행하는 이벤트입니다.

```html
<!DOCTYPE html>
<html>
<head>
  <title>DOMContentLoaded 이벤트 방식으로 HTML 문서 조작하기</title>
  <script>
    // DOMContentLoaded 이벤트를 연결합니다.
    document.addEventListener('DOMContentLoaded', () => {
      const h1 = (text) => `<h1>${text}</h1>`
      document.body.innerHTML += h1('DOMContentLoaded 이벤트 발생')
    })
  </script>
</head>
<body>

</body>
</html>
```

```
크롬 출력

DOMContentLoaded 이벤트 발생
```

문서를 다 읽어들인 후에 DOMContentLoaded 이벤트가 발생하기에 body 태그 이전에 작성해도 정상적으로 작동합니다.

### 문서 객체 가져오기

document.body 코드를 사용하면 문서의 body 요소를 읽어들일 수 있습니다. 이 외에도 head와 title 요소 등을 읽을 수 있습니다.

```
document.body
documnet.title
document.head
```

위의 방식은 자바스크립에서 "당연히 있겟지"에 전제하고 만든 속성이기에 다른 내부 요소에 접근하고자 한다면 별도의 메소드를 사용하여 접근해야 합니다.

```
document.querySelector(선택자)
document.querySelectorAll(선택자)
```

querySelector()는 하나의 요소를 querySelectorAll()메소드는 문서의 여러 객체를 추출합니다.
선택자 부분에는 **CSS 선택자**를 입력합니다.

|이름|선택자 형태|설명|
|---|---|---|
|태그 선택자|태그|특정 태그를 가진 요소를 추출합니다|
|아이디 선택자|#아이디|특정 id 속성을 가진 요소를 추출합니다|
|클래스 선택자|.클래스|특정 class 속성을 가진 요소를 추출합니다|
|속성 선택자|[속성=값]|특정 속성 값을 가지고 있는 요소를 추출합니다|
|후손 선택자|선택자_A 선택자_B|선택자_A아래에 있는 선택자_B를 선택합니다|

- querySelector()

```html
<script>
  document.addEventListener('DOMContentLoaded', () => {
    const header = document.querySelector('h1')

    header.textContent = '헤더'
    header.style.color = 'white'
    header.style.backgroundColor = 'black'
    header.style.padding = '20px'
  })
</script>
<body>
  <h1></h1>
</body>
```

실제 h1 태그에는 아무 내용도 어떤 스타일 변화도 주지 않았지만 script 태그 내부에서 조작하여 내용과 스타일을 변경할 수 있습니다.

- querySelectorAll()

```html
<script>
  document.addEventListener('DOMContentLoaded', () => {
    const headers = document.querySelectorAll('h1')
    console.log(headers)

    headers.forEach((header) => {
      header.textContent = '헤더'
      header.style.color = 'white'
      header.style.backgroundColor = 'black'
      header.style.padding = '20px'
    })
    headers[0].textContent = '헤더1'
  })
</script>
<body>
  <h1></h1>
  <h1></h1>
  <h1></h1>
  <h1></h1>
</body>
```

```
브라우저 출력

헤더1
헤더
헤더
헤더
```

```
콘솔 출력

NodeList(4) [h1, h1, h1, h1]
```

- NodeList
  - 웹 페이지의 HTML 문서 내에서 선택한 요소 객체뿐만 아니라 텍스트, 주석, 속성 등의 모든 노드를 문서 내 정렬된 순서대로 모아둔 집합입니다.
  - 흔히 DOM 컬렉션이라 말하는 이 집합은 노드를 배열의 항목처럼 유사하게 다룰 수 있으며, 웹 페이지의 노드를 쉽게 조작할 수 있게 하는 객체입니다.

### 글자 조작하기

innerHTML 속성과 textContent 속성을 사용해 문서 객체 내부의 글자를 조작했습니다.

|속성 이름|설명|
|---|---|
|문서 객체.textContent|입력된 문자열을 그대로 넣습니다|
|문서 객체.innerHTML|입력된 문자열을 HTML 형식으로 넣습니다|

```html
<script>
  document.addEventListener('DOMContentLoaded', () => {
    const a = document.querySelector('#a')
    const b = document.querySelector('#b')

    a.textContent = '<h1>textContent 속성</h1>'
    b.innerHTML = '<h1>innerHTML 속성</h1>'
  })
</script>
<body>
  <div id="a"></div>
  <div id="b"></div>
</body>
```

```
브라우저 출력

<h1>textContent 속성</h1>
innerHTML 속성
```

### 속성 조작하기

문서 객체의 속성을 조작할 때는 다음과 같은 메소드들을 사용합니다.

|메소드 이름|설명|
|---|---|
|문서 객체.getAttribute(속성 이름)|특정 속성의 값을 추출합니다|
|문서 객체.setAttribute(속성 이름, 값)|특정 속성의 값을 지정합니다|

`https://placecats.com/` 웹 사이트를 예시에서 활용합니다.

```html
<script>
  document.addEventListener('DOMContentLoaded', () => {
    const rects = document.querySelectorAll('.rect')

    rects.forEach((rect, index) => {
      const width = (index + 1) * 100
      const src = `https://placecats.com/${width}/250`
      rect.setAttribute('src', src)
      // src는 HTML 표준 속성이므로 온점으로 사용 가능
      // rect.src = src
    })
  })7
</script>
<body>
  <img class="rect">
  <img class="rect">
  <img class="rect">
  <img class="rect">
</body>
```

HTML 표준에 정의된 속성은 온점(.)을 사용하여 바로 사용 가능합니다.

### 스타일 조작하기

문서 객체의 스타일을 조작할 때는 style 속성을 사용합니다. style 속성은 객체이며, 내부에서는 속성으로 CSS를 사용해서 지정할 수 있는 스타일이 있습니다.

CSS에서 입력하는 속성이름과 자바스크립트에서도 같은 이름을 사용합니다. 다만 (\-)기호를 제외하고 캐멀 케이스를 사용합니다.

|CSS 속성 이름|자바스크립트 style 속성 이름|
|---|---|
|background-color|backgroundColor|
|text-align|textAlign|
|font-size|fontSize|

style 객체는 다음과 같은 방법으로도 조정할 수 있습니다.

```javascript
h1.style.backgroundColor // 가장 많이 사용함
h1.style['backgroundColor']
h1.style['background-color']
```

```html
<script>
  document.addEventListener('DOMContentLoaded', () => {
    const divs = document.querySelectorAll('body > div')

    divs.forEach((div, index) => {
      console.log(div, index);
      const val = index * 10
      div.style.height = `10px`
      div.style.backgroundColor = `rgba(${val}, ${val}, ${val})`
    })
  })
</script>
<body>
  <div></div><div></div><div></div><div></div><div></div>
  <div></div><div></div><div></div><div></div><div></div>
  <div></div><div></div><div></div><div></div><div></div>
  <div></div><div></div><div></div><div></div><div></div>
  <div></div><div></div><div></div><div></div><div></div>
</body>
```

### 문서 객체 생성하기

문서 객체를 생성하고 싶을 때 document.createElement() 메소드를 사용합니다.

`documnet.createElement(문서 객체 이름)`

문서 객체는 트리 구조가 있기에 부모와 자식을 설정할 수 있습니다. appendChild()메소드를 활용하여 트리 구조를 만들 수 있습니다.

`부모 객체.appendChild(자식 객체)`

```html
<script>
  document.addEventListener('DOMContentLoaded', () => {
    const header = document.createElement('h1') // h1 태그를 생성합니다

    header.textContent = '문서 객체 동적으로 생성하기'
    header.setAttribute('data-custom', '사용자 정의 속성')
    header.style.color = 'white'
    header.style.backgroundColor = 'pink'

    document.body.appendChild(header)
  })
</script>
<body>

</body>
```

### 문서 객체 이동하기

appenChild() 메소드는 문서 객체를 이동할 때도 있습니다. 문서 객체의 부모는 언제나 1개 이기에 다른 문서 객체에 추가하면 문서 객체가 이동하게 됩니다.

```html
<script>
  document.addEventListener('DOMContentLoaded', () => {
    const divA = document.querySelector('#first')
    const divB = document.querySelector('#second')
    const header = document.createElement('h1')
    header.textContent = '이동하는 h1 태그'

    const toFirst = () => {
      divA.appendChild(header)
      setTimeout(toSecond, 1000)
    }
    const toSecond = () => {
      divB.appendChild(header)
      setTimeout(toFirst, 1000)
    }
    toFirst()
  })
</script>
<body>
  <div id="first">
    <h1>첫 번째 div 태그 내부</h1>
  </div>
  <hr>
  <div id="second">
    <h1>두 번째 div 태그 내부</h1>
  </div>
</body>
```

### 문서 객체 제거하기

문서 객체를 제거할 때는 removeChild() 메소드를 사용한다

`부모 객체.removechild(자식 객체)`

appenChild() 메소드 등으로 부모 객체와 연결되어 있다면 parentNode 속성으로 부모 객체에 접근할 수 있으므로, 이 코드를 자주 사용합니다.

`문서 객체.parentNode.removeChild(문서 객체)`

```html
<script>
  document.addEventListener('DOMContentLoaded', () => {
    setTimeout(() => {
      const header = document.querySelector('h1')

      header.parentNode.removeChild(header)
      // document.body.removeChild(header) header의 부모 객체가 body이므로 이렇게도 가능
    }, 3000)
  })
</script>
<body>
  <hr>
  <h1>제거 대상 문서 객체</h1>
  <hr>
</body>
```

### 이벤트 설정하기

모든 문서 객체는 생성되거나 클릭되거나 마우스를 위에 올리거나 할 때 **이벤트**(event)라는 것이 발생합니다. 그리고 이 이벤트가 발생할 때 실행할 함수는 addEventListener()메소드를 활용합니다.

`문서 객체.addEventListener(이벤트 이름, 콜백 함수)`

이벤트가 발생할 때 실행할 함수, 콜백 함수를 이벤트 리스너, 이벤트 핸들러라고 합니다.

```html
<script>
  document.addEventListener('DOMContentLoaded', () => {
    let counter = 0
    const header = document.querySelector('h1')

    header.addEventListener('click', (event) =>{
      counter++
      header.textContent = `클릭 횟수: ${counter}`
    })
  })
</script>
<style>
  h1 {
    /*
    클릭을 여러 번 했을 때
    글자가 선택되는 것을 막기 위한 스타일(드래그를 막음)
    */
    user-select: none;
  }
</style>
<body>
  <h1>클릭 횟수: 0</h1>
</body>
```

### 이벤트 제거하기

이벤트를 제가헐 때는 removeEventListener() 메소드를 사용합니다.

`문서 객체.removeEventListener(이벤트 이름, 이벤트 리스너)`

```html
<script>
  document.addEventListener('DOMContentLoaded', () => {
    let counter = 0
    let isConnect = false

    const header = document.querySelector('h1')
    const p = document.querySelector('p')
    const connectbutton = document.querySelector('#connect')
    const disconnectButton = document.querySelector('#disconnect')
    const listener = (event) => {
      header.textContent = `클릭 횟수: ${counter++}`
    }

    connectbutton.addEventListener('click', () => {
      if (isConnect === false) {
        header.addEventListener('click', listener)
        p.textContent = '이벤트 연결 상태: 연결 중'
        isConnect = true
      }
    })
    disconnectButton.addEventListener('click', () => {
      if (isConnect === true) {
        header.removeEventListener('click', listener)
        p.textContent = '이벤트 연결 상태: 해제'
        isConnect = false
      }
    })
  })
</script>
<style>
  h1 {
    user-select: none;
  }
</style>
<body>
  <h1>클릭 횟수: 0</h1>
  <button id="connect">이벤트 연결</button>
  <button id="disconnect">이벤트 제거</button>
  <p>이벤트 연결: 해제</p>
</body>
```

## 07-2 이벤트 활용

이번 파트에서는 **입력 양식(form)**을 주로 다룹니다.

### 이벤트 모델

이벤트를 연결하는 방법을 **이벤트 모델**(event model)이라고 합니다.

addEventListener()메소드를 현재 표준으로 사용하고 있는 방법으로 **표준 이벤트 모델**이라고 합니다.

```html
document.addEventListenr('keyup', () => {
  
})
```

과거에는 문서 객체가 갖고 있는 on***으로 시작하는 속성에 함수를 할당해서 이벤트를 연결했고 이와 같은 방법을 **고전 이벤트 모델**이라고 부릅니다.

```html
document.body.onkeyup = (event) => {

}
```

고전 이벤트 모델처럼 on***으로 시작하는 속성을 HTML 요소에 직접 넣어서 이벤트를 연결하는 것을 **인라인 이벤트 모델**이라고 부릅니다.

```html
<script>
  const listner = (event) => {

  }
</script>
<body onekyuip="listener(event)">

</body>
```

인라인 이벤트 모델은 HTML 요소의 on*** 속성에 자바스크립트 코드를 넣는 것입니다. on*** 속성 내부에서 변수 event를 활용할 수 있고 이 변수는 listent() 함수의 매개변수로 전달됩니다.

모든 이벤트 모델의 이벤트 리스너의 첫 번째 매개변수로 **이벤트 객체**를 받습니다. 이벤트 객체에는 이벤트와 관련된 정보가 들어 있습니다.

표준 이벤트 모델이 등장하며 이벤트 리스너를 여러 개 연결할 수 있게 되며 고전 이벤트 모델을 사용하는 일이 줄어들었습니다. 하지만 최근 프론트엔트 프레임워크들이 인라인 이벤트 모델을 활용하는 코드를 작성해서 현재는 인라인 이벤트 모델과 표준 이벤트 모델 둘다 많이 사용하고 있습니다.

### 키보드 이벤트

키보드 이벤트는 다음과 같은 3가지 이벤트가 있습니다.

|이벤트|설명|
|---|---|
|keydown|키가 눌릴 때 실행됩니다. 키보드를 꾹 누르고 있을 때도, 입력될 때도 실행됩니다.|
|keypress|키가 입력되었을 때 실행됩니다. 하지만 웹 브라우저에 따라서 아시아권의 문자(한국어, 중국어, 일본어)를 제대로 처리하지 못하는 무제가 있습니다.|
|keyup|키보드에서 키가 떨어질 때 실행됩니다.|

keydown 이벤트와 keypress 이벤트는 웹 브라우저에 따라서 아시아권의 문자(한국어, 중국어, 일본어)를 제대로 처리하지 못하는 문제가 있어서 일반적으로 keyup 이벤트를 사용합니다.

```html
<script>
  document.addEventListener('DOMContentLoaded', () => {
    const textarea = document.querySelector('textarea')
    const header = document.querySelector('h1')

    textarea.addEventListener('keyup', (event) => {
      const length = textarea.value.length
      header.textContent = `글자 수 : ${length}`
    })
  })
</script>
<body>
  <h1></h1>
  <textarea></textarea>
</body>
```

### 키보드 키 코드 사용하기

키보드 이벤트가 발생할 때는 이벤트 객체로 어떤 키를 눌렀는지와 관련된 속성이 따라옵니다.

|이벤트 속성 이름|설명|
|---|---|
|code|입력한 키|
|keyCode|입력한 키를 나타내는 숫자|
|altKey|`Alt`키를 눌렀는지|
|cltKey|`Clt`키를 눌렀는지|
|shiftKey|`Shift`키를 눌렀는지|

```html
<script>
  document.addEventListener('DOMContentLoaded', () =>{
    const header = document.querySelector('h1')
    const print = (event) => {
      let output = ''
      output += `alt: ${event.altKey}<br>`
      output += `ctrl: ${event.cltKey}<br>`
      output += `shitf: ${event.shiftKey}<br>`
      output += `code: ${typeof(event.code) !== 'undefined' ? event.code : event.keyCode}<br>`
      header.innerHTML = output
    }

    document.addEventListener('keydown', print)
    document.addEventListener('keyup', print)
  })
</script>
<body>
  <h1></h1>
</body>
```

### 이벤트 발생 객체

지금까지는 이벤트 내부에서 문서 객체 변수를 사용해 문서 객체와 관련된 정보를 추출했습니다.

```html
<script>
  document.addEventListener('DOMContentLoaded', () => {
    const textarea = document.querySelector('textarea')
    const h1 = document.querySelector('h1')

    textarea.addEventListener('keyup', (event) => {
      const length = textarea.value.length
      h1.textarea = `글자 수 :${length}`
    })
  })
</script>
```

상황에 따라서는 이벤트 리스너 내부에서 변수에 접근할 수 없는 경우가 있습니다.

```html
<script>
  const listenr = (event) => {
    // 현재 블록에서는 textarea 변수를 사용할 수 없습니다.
    const length = textarea.value.length
    h1.textarea = `글자 수 :${length}`
  }

  document.addEventListener('DOMContentLoaded', () => { // 이벤트 리스너 외부로 분리
    const textarea = document.querySelector('textarea')
    const h1 = document.querySelector('h1')
    textarea.addEventListener('keyup', listener)
  })
</script>
```

규모가 커지면 이벤트 리스너를 외부로 분리하는 경우가 많습니다. 이런 상황에서 이벤트를 발생시킨 객체에 2가지 방법으로 접근합니다.

- event.currentTarget 속성

`() => {}`와 `function () {}` 2가지 형태 모두 사용 가능합니다.

```html
<script>
  const listenr = (event) => {
    // event.currentTarget 이 textarea가 됩니다.
    // const legnth = textarea.value.length
    const length = event.currentTarget.value.length
    h1.textarea = `글자 수 :${length}`
  }

  document.addEventListener('DOMContentLoaded', () => {
    const textarea = document.querySelector('textarea')
    const h1 = document.querySelector('h1')
    textarea.addEventListener('keyup', listener)
  })
</script>
```

- this 키워드

화살표 함수가 아닌 `function() {}`형태만 가능합니다.

```html
<script>
  const listenr = function(event) { // 화살표 함수 불가능
    // this가 textarea가 됩니다.
    // const length = textarea.value.length
    const length = this.value.length
    h1.textarea = `글자 수 :${length}`
  }

  document.addEventListener('DOMContentLoaded', () => {
    const textarea = document.querySelector('textarea')
    const h1 = document.querySelector('h1')
    textarea.addEventListener('keyup', listener)
  })
</script>
```

### 글자 입력 양식 이벤트

사용자로부터 어떠한 입력을 받을 때 사용하는 양식을 **입력 양식**(form) HTMl 태그에서는 **input** 태그, **textarea** 태그, **button** 태그, **select** 태그 등이 모두 입력 양식입니다.

```html
<script>
  document.addEventListener('DOMContentLoaded', () => {
    const input = document.querySelector('input')
    const button = document.querySelector('button')
    const p = document.querySelector('p')

    button.addEventListener('click', (event) => {
      // 입력을 숫자로 변환합니다.
      const inch = Number(input.value)
      // 숫자가 아니면 바로 리턴합니다.
      if (isNaN(inch)) {
        p.textContent = '숫자를 입력해주세요'
        return
      }
      // 변환해서 출력합니다.
      const cm = inch * 2.54
      p.textContent = `${inch}inch는 ${cm}cm 입니다.`
    })
  })
</script>
<body>
  <input type="text"> inch<br>
  <button>계산</button>
  <p></p>
</body>
```

입력하는 과정에서 이메일과 전화번호 유효성 등을 검사해보겠습니다.

```html
<script>
  document.addEventListener('DOMContentLoaded', () => {
    const input = document.querySelector('input')
    const p = document.querySelector('p')
    const isEmail = (value) => {
      // 골뱅이를 갖고 있고 && 골뱅이 뒤에 점이 있다면
      return (value.indexOf('@') > 1) && (value.split('@')[1].indexOf('.') > 1)
    }

    input.addEventListener('keyup', (event) => {
      const value = event.currentTarget.value
      if (isEmail(value)) {
        p.style.color = 'green'
        p.textContent = `이메일 형식입니다. : ${value}`
      } else {
        p.style.color = 'red'
        p.textContent = `이메일 형식이 아닙니다. : ${value}`
      }
    })
  })
</script>
<body>
  <input type="text">
  <p></p>
</body>
```

일반적으로 유효성 검사를 할 때는 **정규 표현식**(regular expression)을 사용합니다.

#### 드롭다운 목록 활용하기

드롭다운 목록은 기본적으로 **select** 태그를 활용합니다.

```html
<script>
  document.addEventListener('DOMContentLoaded', () => {
    const select = document.querySelector('select')
    const p = document.querySelector('p')

    select.addEventListener('change', (event) => {
      const options = event.currentTarget.options
      const index = event.currentTarget.options.selectedIndex

      p.textContent = `선택 : ${options[index].textContent}`
    })
  })
</script>
<body>
  <select>
    <option>떡볶이</option>
    <option>순대</option>
    <option>오징어</option>
    <option>튀김</option>
  </select>
  <p>선택 : 떡볶이</p>
</body>
```

select 태그에 multiple 속성을 부여하면 `ctrl`키 또는 `shift`키를 누르고 여러 항목을 선택할 수 있는 선택 상자가 나옵니다.

- multiple select 태그

```html
<script>
  document.addEventListener('DOMContentLoaded', () => {
    const select = document.querySelector('select')
    const p = document.querySelector('p')

    select.addEventListener('change', (event) => {
      const options = event.currentTarget.options
      const list = []
      for (const option of options) { // options 속성에는 forEach()메소드가 없습니다.
        if (option.selected) { // selected 속성을 확인합니다.
          list.push(option.textContent)
        }
      }
      p.textContent = `선택: ${list.join(', ')}`
    })
  })
</script>
<body>
  <select multiple>
    <option>떡볶이</option>
    <option>순대</option>
    <option>오징어</option>
    <option>튀김</option>
  </select>
  <p></p>
</body>
```

#### 체크 박스

체크 박스를 확인할 때는 입력 양식의 checked 속성을 사용합니다.

```html
<script>
  document.addEventListener('DOMContentLoaded', () => {
    let [timer, timerId] = [0, 0]
    const h1 = document.querySelector('h1')
    const checkbox = document.querySelector('input')

    checkbox.addEventListener('change', (event) => {
      if (event.currentTarget.checked) {
        // 체크 상태
        timerId = setInterval(() => {
          timer += 1
          h1.textContent = `${timer}초`
        }, 1000)
      } else {
        // 체크 해제 상태
        clearInterval(timerId)
      }
    })
  })
</script>
<body>
  <input type="checkbox">
  <span>타이머 활성화</span>
  <h1></h1>
</body>
```

#### 라디오 버튼

체크 박스와 비슷한 양식의 라디오 버튼 또한 선택된 경우 checked 속성을 사용합니다.

```html
<script>
  document.addEventListener('DOMContentLoaded', () => {
    // 문서 객체 추출
    const output = document.querySelector('#output')
    const radios = document.querySelectorAll('[name=pet]')

    // 모든 라디오 버튼에
    radios.forEach((radio) => {
      // 이벤트 연결
      radio.addEventListener('change', (event) => {
        const current = event.currentTarget
        if (current.checked) {
          output.textContent = `좋아하는 애완 동물은 ${current.value}이시군요!`
        }
      })
    })
  })
</script>
<body>
  <h3># 좋아하는 애완 동물을 선택해주세요</h3>
  <input type="radio" name="pet" value="강아지">
  <span>강아지</span>
  <input type="radio" name="pet" value="고양이">
  <span>고양이</span>
  <input type="radio" name="pet" value="햄스터">
  <span>햄스터</span>
  <input type="radio" name="pet" value="앵무새">
  <span>앵무새</span>
  <hr>
  <h3 id="output"></h3>
</body>
```

### 기본 이벤트 막기

웹 브라우저에서는 이미지에 마우스 오른쪽 버튼을 클릭하면 다음과 같은 **컨텍스트 메뉴**를 출력합니다. 이처럼 어떤 이베트가 발생했을 때 웹 브라우저가 기본적으로 처리해주는 것을 **기본 이벤트**라고 합니다.

링크를 클릭했을 때 이동하는 것, 제출 버튼을 클릭했을 때 이동하는 것들이 기본이벤트 입니다.

이런 기본 이벤트를 제거할 때는 event 객체의 preventDefault()메소드를 사용합니다.

- 마우스 우클릭 막기

```html
<script>
  document.addEventListener('DOMContentLoaded', () => {
    const imgs = document.querySelectorAll('img')

    imgs.forEach((img) => {
      img.addEventListener('contextmenu', (event) => {
        event.preventDefault()
      })
    })
  })
</script>
<body>
  <img src="https://placecats.com/300/300" alt="">
</body>
```

- 체크 때만 링크 활성화하기

```html
<script>
  document.addEventListener('DOMContentLoaded', () => {
    let status = false

    const checkbox = document.querySelector('input')
    checkbox.addEventListener('change', (event) => {
      status = event.currentTarget.checked
    })

    const link = document.querySelector('a')
    link.addEventListener('click', (event) => {
      if (!status) {
        event.preventDefault()
      }
    })
  })
</script>
<body>
  <input type="checkbox">
  <span>링크 활성화</span>
  <br>
  <a href="https://hanbit.co.kr">한빛 미디어</a>
</body>
```

### 입력 양식 초점

입력 양식에 초점이 있을 때는 `focus` 없을 때는 `blur`을 이용한다.

이전에 동양의 글자 수 측정 시에는 문제가 발생할 수 있다고 했는데 이를 이용하면 해결 할 수 있다.

```html
<script>
  document.addEventListener('DOMContentLoaded', () => {
    const textarea = document.querySelector('textarea')
    const h1 = document.querySelector('h1')
    let tiemrId

    textarea.addEventListener('focus', (event) => {
      tiemrId = setInterval(() => {
        const length = textarea.value.length
        h1.textContent = `글자 수 : ${length}`
      })
    }, 50)

    textarea.addEventListener('blur', (event) => {
      clearInterval(tiemrId)
    })
  })
</script>
<body>
  <textarea></textarea>
  <h1></h1>
</body>
```

### localStorage 객체

웹 브라우저가 제공해주는 기능을 **웹 API**라고 합니다. 이 중에서 웹 브라우저가 데이터를 저장하는 기능인 localStorage를 살펴보겠습니다.

**localStorage** 객체는 웹 브라우저가 기본적으로 제공하는 객체로 데이터를 저장하는 기능을 가지고 있습니다.

- localStorage.getItem(키) : 저장된 값을 추출합니다. 없으면 undefined가 나옵니다. 객체의 속성을 추출하는 일반적인 형태로 `localStorage.키`, `localStorage[키]` 형태로도 가능합니다.
- localStorage.setItem(키, 값) : 값을 저장합니다. 객체에 속성을 지정하는 일반적인 형태로도 사용할 수 있습니다.
- localStorage.removeItem(키) : 특정 키의 값을 제거합니다.
- localStorage.clear() : 저장된 모든 값을 제거합니다.

```html
<script>
  document.addEventListener('DOMContentLoaded', () => {
    const p = document.querySelector('p')
    const input = document.querySelector('input')
    const button = document.querySelector('button')

    // const savedValue = localStorage.input 도 가능
    const savedValue = localStorage.getItem('input')
    
    if (savedValue) {
      input.value = savedValue
      p.textContent = `이정 실행 때의 마지막 값 : ${savedValue}`
    }

    input.addEventListener('keyup', (event) => {
      const value = event.currentTarget.value
      localStorage.setItem('input', value)
      // localStorage.inpu = value 도 가능
    })

    button.addEventListener('click', (event) => {
      localStorage.clear() // 값을 모두 제거
      input.value = ''
    })
  })
</script>
<body>
  <p></p>
  <button>지우기</button>
  <input type="text">
</body>
```

---

# 08 예외 처리

- 구문 오류와 예외를 구분할 수 있습니다.
- 기본 예외 처리와 고급 예외 처리를 이해합니다.
- 예외를 왜 발생시켜야 하는지 이해합니다.
- 예외를 강제로 발생시키는 방법을 이해합니다.

## 08-1 구문 오류와 예외

문법적 오류로 코드가 실행조차 되지 않는 오류를 **구문 오류**(syntax error)라고 합니다.
코드 실행 중간에 발생하는 오류를 **예외**(exception)이라고 합니다.
그리고 이를 처리하는 것을 **예외 처리**(exception handling)이라고 합니다.

### 오류의 종류

프로그래밍의 오류에는 크게 2가지 종류가 있습니다.

- 프로그램 실행 전에 방생하는 오류
- 프로그램 실행 중에 발생하는 오류

두 가지 모두 '오류'이지만 프로그램 실행 전에 발생하는 오류를 **구문 오류**(syntax error)라고 부르며, 프로그램 실행 중에 발생하는 오류를 **예외**(exception) 또는 **런타임 오류**(runtime error)라고 부릅니다.

#### 구문 오류

구문 오류는 괄호의 짝이 맞지 않았다던가, 무나열을 열었는데 닫지 않았을 때 발생하는 오류 입니다. 이러한 구문 오류가 있을 경우 웹 브라우저가 코드를 분석조차 하지 못하므로 실행되지 않습니다.

```html
<script>
  console.log('# 프로그램이 시작되었습니다.!')

  console.log("괄호를 닫지 않는 실수를 했습니다."
</script>
```

코드를 실행하면 다음과 같은 Syntax Error이라는 오류가 발생합니다.
`Uncaught SyntaxError SyntaxError: missing ) after argument list`

#### 예외

예외 또는 런타임 에러는 프로그램 실행 중에 발생하는 오류를 의미합니다.

```html
<script>
  console.log('# 프로그램이 시작되었습니다.!')

  console.rog('log를 rog로 잘못 입력했브니다.')
</script>
```

```
# 프로그램이 시작되었습니다.!
Uncaught TypeError TypeError: console.rog is not a function
```

`'# 프로그램이 시작되었습니다.!'`가 출력되었음에 알 수 있듯이 일단 코드는 실행됩니다. 
하지만 rog라는 식별자가 없기에 `"console.rog"`는 함수가 아니라는 오류를 출력합니다.

### 기본 예외 처리

조건문을 사용해서 예외가 발생하지 않게 만드는 것을 **기본 예외 처리**라고 합니다.

```html
<script>
  document.addEventListener('DOMContentLoaded', () => {
    const h1 = document.querySelector('h1')
    if (h1) { // h1 태그가 있다면 true, 존재하지 않으면 false로 변환
      h1.textContent = '안녕하세요'
    } else {
      console.log('h1 태그를 출력할 수 없습니다.');
    }
  })
</script>
<body>
  <!-- h1 태그 없음 -->
</body>
```

### 고급 예외 처리

**try catch finally**구문을 사용해서 예외 처리하는 것을 **고급 예외 처리**라고 합니다.


```javascript
try {
  // 예외가 발생할 가능성이 있는 코드
} catch (exception) {
  // 예외가 발생했을 때 실행할 코드
} finally { // finally 구문은 필요한 경우에만 사용
  // 무조건 실행
}
```

try 구문 안에서 예외가 발생하면 catch 구문에서 처리합니다. fianlly 구문은 필수 사항은 아니지만 예외 발생 여부와 상관없이 수행해야하는 작업이 존재한다면 사용합니다.

- try catch 구문

```html
<script>
  try {
    없음.없음()
    console.log('try 구문의 마지막 줄')
  } catch (exception) {
    console.log('catch 구문의 마지막 줄');
  }
</script>
```

```
출력

catch 구문의 마지막 줄
```

- finally 구문

```html
<script>
  try {
    없음.없음()
    console.log('try 구문의 마지막 줄');
  } catch (exception) {
    console.log('catch 구문의 마지막 줄');
  } finally {
    console.log('finally 구문의 마지막 줄');
  }
</script>
```

```
출력

catch 구문의 마지막 줄
finally 구문의 마지막 줄
```

#### finally 구문의 사용 이유

```html
<script>
  function test() {
    try {
      alert('A 위치입니다.')
      throw "예외 강제 발생"
    } catch (exception) {
      alert('B 위치입니다.');
      return
    } finally {
      alert('C 위치입니다.');
    }
    alert('D 위치입니다.');
  }
</script>
<body>

</body>
```

```
출력

A 위치입니다.
B 위치입니다.
C 위치입니다.
```

- try catch 구문 내부에서 return 키워드를 만날 때
- try catch 구문 내부에서 break 또는 continue 키워드를 만날 때

위의 상황 때 결과가 달라집니다. 따라서 finally의 반드시 실행한다는 특성이 필요할 경우 사용합니다.

## 08-2 예외 처리 고급

예외가 발생된 정보를 확인할 수 있게 해주는 것이 **예외 객체**(exception object)입니다.

자바 스크립트에서는 다른 프로그래밍 언어와 비교해서 예외가 거의 발생하지 않는 프로그래밍 언어입니다. 그래서 개발자가 예외를 강제로 발생시켜줘야하는 경우가 많습니다. 이때 사용하는 키워드가 **throw**입니다.

### 예외 객체

try catch 구문에서 catch의 괄호 안에 입력하는 식별자가 **예외 객체**(exception object)입니다.

```javascript
try {

} catch (exception) { // 간단하게 e로 작성하기도 함
  
}
```

예외 객체가 갖고 있는 속성은 브라우저에 따라 조금씩 다릅니다.

공통 속성
|속성 이름|설명|
|---|---|
|name|예외 이름|
|message|예외 메시지|

```html
<script>
  try {
    // 자바스크립트 배열 크기 한도 초과
    const array = new Array(99999999999999999999999999)
  } catch (exception) {
    console.log(exception);
    console.log();
    console.log(`예외 이름 : ${exception.name}`);
    console.log(`예외 메시지 : ${exception.message}`);
  }
</script>
```

```
출력

RangeError: Invalid array length
    at file:///D:/study/book/hongongJavascript-book/ch8/2/1.html:9:19 {stack: 'RangeError: Invalid array length
    at file:…ch8/2/1.html:9:19', message: 'Invalid array length'}

예외 이름 : RangeError
예외 메시지 : Invalid array length
```

### 예외 강제 발생

상황에 따라 예외를 강제로 발생시켜야 하는 경우도 있습니다. 이때 **throw** 키워드를 사용합니다.

```javascript
// 단순하게 예외를 발생
throw 문자열

// 좀 더 자세하게 예외를 발생
throw new Error(문자열)
```

```javascript
> throw '문자열'
Uncaught 문자열

> throw new Error('문자열')
Uncaught Error: 문자열
    at 파일 이름:줄 번호
```

- 예외 강제 발생시키고 잡기

```html
<script>
  function divide(a, b) {
    if (b === 0) {
      throw '0으로는 나눌 수 없습니다.'
    }
    return a / b
  }

  console.log(divide(10, 2));
  console.log(divide(10, 0));
</script>
```

```
출력

5
Uncaught Error 0으로는 나눌 수 없습니다.
```

### 예외를 강제로 발생시키는 이유

내가 만든 함수는 내가 사용할 때 문제가 없지만, 내가 만든 함수를 다른 사람이 사용하는 경우 내가 의도치 않은 형태로 사용할 수 있기에 예외를 강제로 발생시킨다면 사용자에게 주의를 줄 수 있고 의도한 대로 처리하게 유도할 수 있습니다.


- 자바스크립트

일반적인 프로그래밍 언어와 달리 자바스크립트에서는 undefined와 NaN이 존재합니다. 따라서 다른 프로그래밍 언어에서 예외를 발생시키는 상황도 자바스크립트에서는 예외가 자연스럽게 발생하지 않습니다.


```html
<script>
  function test(object) {
    // object.a와 object.b 속성이 없지만 예외를 발생시키지 않음
    console.log(object.a + object.b);
    console.log('');
    
    if (object.a !== undefined && object.b !== undefined) {
      console.log(object.a + object.b);
    } else {
      throw new Error('a 속성과 b 속성을 지정하지 않았습니다.')
    }
  }

  test({})
</script>
```

```
출력

NaN

Uncaught Error Error: a 속성과 b 속성을 지정하지 않았습니다.
```

---

# 09 클래스

- 클래스를 왜 사용하는지 이해합니다.
- 클래스를 만드는 방법을 이해합니다.
- 클래스와 관련된 최신 표준을 이해합니다.

## 09-1 클래스의 기본 기능

세상에 있는 다양한 프로그래밍 언어들은 C언어를 제외하면 모두 **객체 지향**(Object Oriented)이라는 패러다임을 기반으로 만들어진 프로그래밍 언어입니다.

객체 지향 패러다임은 객체를 우선적으로 생각해서 프로그램을 만든다는 방법론으로 **클래스**(Class)라는 문법으로 **객체**(Object)를 효율적이고 안전하게 만들어 쉽게 프로그래밍에 적용할 수 있게 도와줍니다.

### 추상화

현재 만들어지는 대부분의 프로그램은 "우리가 어떤 데이터를 활용하는가?"라는 생각으로 시작됩니다.

현실의 객체(사물)에는 수많은 속성을 가지고 있고 이 속성들은 데이터가 될 수있습니다. 사람을 예로 들자면 머리카락 개수, 눈썹 길이, 눈 크기 등 엄청나게 많은 속성들이 존재합니다. 따라서 현실에 모든 정보를 컴퓨터 내부에 완벽하게 넣는 것은 불가능합니다.

다행히 프로그램을 만들 때 이 모든 정보가 필요하지는 않습니다. 만약 병원에서 사용하는 업무 프로그램을 만든다면 환자의 이름, 생년월일, 성별, 연락처 등의 정보만 있으면 됩니다.

이와 같이 프로그램에서 필요한 요소만 사용해서 객체를 표현하는 것을 **추상화**(abstraction)이라고 합니다. 포괄적인 사전적 의미로는 복잡한 자료, 모듈, 시스템 등으로부터 핵심적인 개념과 기능을 간추려내는 것을 추상화라고 합니다.


### 같은 형태의 객체 만들기

학생 성적 관리 프로그램을 만든다고 가정해봅시다. 학생이라는 개체가 필요하고, 학생들로부터 성정 관리에 필요한 공통사항을 추출하는데, 이를 추상화라고 합니다.

학생들이 여러 명이므로 추출한 요소는 배열을 활용합니다.

```html
<script>
  const students = []
  students.push({이름: "구름", 국어:88, 영어:89, 수학:79, 과학:90})
  students.push({이름: "겨울", 국어:85, 영어:79, 수학:72, 과학:99})
  students.push({이름: "햇살", 국어:92, 영어:88, 수학:73, 과학:97})
  students.push({이름: "달님", 국어:98, 영어:78, 수학:75, 과학:89})

  let ouput = '이름\t총점\t평균\n'
  for (const student of students) {
    const sum = student.국어 + student.영어 + student.수학 + student.과학
    const average = sum / 4
    ouput += `${student.이름}\t${sum}점\t${average}점\n`
  }
  console.log(ouput);
</script>
```

### 객체를 처리하는 함수

단순한 계산보다는 함수로 만들어 놓으면 확장성을 고려했을 때 더 좋은 방법이 됩니다.

```html
<script>
  // 객체 선언
  const students = []
  students.push({이름: "구름", 국어:88, 영어:89, 수학:79, 과학:90})
  students.push({이름: "겨울", 국어:85, 영어:79, 수학:72, 과학:99})
  students.push({이름: "햇살", 국어:92, 영어:88, 수학:73, 과학:97})
  students.push({이름: "달님", 국어:98, 영어:78, 수학:75, 과학:89})

  // 객체 처리 함수
  function getSumOf (student) {
    return student.국어 + student.영어 + student.수학 + student.과학
  }

  function getAverageOf (student) {
    return getSumOf(student) / 4
  }

  // 출력
  let ouput = '이름\t총점\t평균\n'
  for (const student of students) {
    ouput += `${student.이름}\t${getSumOf(student)}점\t${getAverageOf(student)}점\n`
  }
  console.log(ouput);
</script>
```

객체를 만드는 부분과 객체를 활용하는 부분으로 나누었습니다. 단순하게 코드가 길어졌다고 생각할 수 있지만 객체에 더 많은 기능을 추가하게 되었을 때 쉽게 유지보수 할 수 있으며 객체를 활용할 때도 더 간단한 코드로 작성할수 있습니다.

### 객체의 기능을 메소드로 추가하기

현재 코드에서는 객체가 학생 하나이기에 문제가 없지만 객체의 수가 늘어나면 함수 이름 충돌이 발생할 수 잇습니다. 또한 매개변수에 어떤 종류의 객체를 넣을 지 몰라 함수를 사용하는 데 혼동이 있을 수 잇습니다.

이런 문제들을 해결하기 위해 함수 이름을 getAverageOfStudent()와 같이 길게 작성할 수 있지만, 가독성의 이유로 추천하지 않습니다.

그래서 개발자들은 함수를 메소드로써 객체 내부에 넣어서 활용하는 방법을 사용합니다.

```html
<script>
  // 객체 선언
  const students = []
  students.push({이름: "구름", 국어:88, 영어:89, 수학:79, 과학:90})
  students.push({이름: "겨울", 국어:85, 영어:79, 수학:72, 과학:99})
  students.push({이름: "햇살", 국어:92, 영어:88, 수학:73, 과학:97})
  students.push({이름: "달님", 국어:98, 영어:78, 수학:75, 과학:89})

  // studends 배열 내부의 객체 모두에 메소드를 추가합니다.
  for (const student of students) {
    student.getSum = function () {
      return this.국어 + this.영어 + this.수학 + this.과학
    }
  
    student.getAverage = function () {
      return this.getSum() / 4
    }
  }
    

  // 출력
  let ouput = '이름\t총점\t평균\n'
  for (const student of students) {
    ouput += `${student.이름}\t${student.getSum()}점\t${student.getAverage()}점\n`
  }
  console.log(ouput);
</script>
```

#### 객체 생성 함수

지금까지는 객체의 키와 값을 하나하나 모두 입력해서 생성했지만 이번에는 함수를 사용해서 객체를 조금 더 쉽게 만들어 생성해보겠습니다.

```html
<script>
  function createStudent(이름, 국어, 영어, 수학, 과학) {
    return {
      // 속성을 선언합니다.
      이름: 이름,
      국어: 국어,
      영어: 영어,
      수학: 수학,
      과학: 과학,
      
      // 메소드를 선언합니다.
      getSum() {
        return this.국어 + this.영어 + this.수학 + this.과학
      },
      getAverage() {
        return this.getSum() / 4
      },
      toString() {
        return `${this.이름}\t${this.getSum()}점\t${this.getAverage()}점\n`
      }
    }
  }
  // 객체 선언
  const students = []
  students.push(createStudent("구름", 88, 89, 79, 90))
  students.push(createStudent("겨울", 85, 79, 72, 99))
  students.push(createStudent("햇살", 92, 88, 73, 97))
  students.push(createStudent("달님", 98, 78, 75, 89))

  // 출력
  let ouput = '이름\t총점\t평균\n'
  for (const student of students) {
    ouput += student.toString()
  }
  console.log(ouput);
</script>
```

이렇게 함수를 통해 객체를 만들면 여러가지 이득이 발생합니다.

- 오탈자의 위험이 줄어듭니다.
- 코드를 입력하는 양이 크게 줄어듭니다.
- 마지막으로 속성과 메소드를 한 함수 내부에서 관리할 수 있으므로 객체를 더 손쉽게 유지보수할 수 있습니다.

물론 아직 문제점이 있습니다. 객체별로 getSum(), getAverage(), toString() 메소드를 생성하므로 함수라는 기본 자료형보다 무거운 자료형이 여러 번 생성됩니다.

### 클래스 선언하기

객체들을 정의하고 객체를 활용하는 프로그램을 만드는 것을 **객체 지향 프로그래밍**(Object Oriented Programming)이라고 합니다. 이 패턴을 활용하고자 개발자들은 더 효율적인 문법을 추가하기 시작했습니다.

프로그래밍 언어 개발자들은 크게 **클래스**(class)와 **프로토타입**(prototype)이라는 2가지 문법으로 효율적으로 객체를 활용할 수 있게 만들었습니다.

현재 사용하는 대대분의 객체 지향 프로그래밍 언어는 클래스 문법을 기반으로 하지만 자바스크립트는 초기에 프로토타입 문법을 제공했습니다. 현재 최신 자바스크립트는 클래스 문법을 제공하기 시작했기에 이 책에서는 클래스 문법만 살펴봅니다.

- 클래스 생성

**클래스 이름**의 첫 글자는 대문자로 지정하는 것이 개발자들의 약속입니다.

```javascript
class 클래스 이름 {

}
```

- 인스턴스 생성

클래스를 기반으로 만든 객체를 **인스턴스**(instance)라고 부르지만 그냥 **객체**(object)라고 부르는 경우도 많습니다.

```
new 클래스 이름()
```

- 클래스 : 이전에 객체를 만드는 함수 비슷한 것
- 인스턴스(객체) : 이전에 만들었던 객체를 만드는 함수로 만든 객체와 비슷한 것

```html
<script>
  // 클라스를 선언
  class Student {

  }
  
  // 학생(인스턴스)를 선언
  const student = new Student()

  // 학생 리스트를 선언
  const students = [
    new Student(),
    new Student(),
    new Student(),
    new Student()
  ]
</script>
```

### 생성자

`new Student()` 코드를 보면 Student 뒤에 함수처럼 괄호를 여닫는 기호가 있습니다. 이는 객체가 생성될 때 호출되는 **생성자**(constructor)이라는 함수입니다.

```javascript
class 함수 이름{
  constructor () {
    // 생성자 코드
  }
}
```

메소드의 이름은 `constructor`이지만 `constructor()`이 아닌 `new Student()`처럼 클래스 이름으로 호출합니다.

```html
<script>
  class Student {
    constructor (이름, 국어, 영어, 수학, 과학) {
      this.이름 = 이름
      this.국어 = 국어
      this.영어 = 영어
      this.수학 = 수학
      this.과학 = 과학
    }
  }

  // 객체 선언
  const students = []
  students.push(new Student("구름", 88, 89, 79, 90))
  students.push(new Student("겨울", 85, 79, 72, 99))
  students.push(new Student("햇살", 92, 88, 73, 97))
  students.push(new Student("달님", 98, 78, 75, 89))
</script>
```

### 메소드

**메소드**(method)는 다음과 같은 형태로 추가합니다. 이렇게 메소드를 만들면 내부적으로 메소드가 중복되지 않고 하나만 생성되어 활용됩니다.

```html
<script>
  class Student {
    constructor (이름, 국어, 영어, 수학, 과학) {
      this.이름 = 이름
      this.국어 = 국어
      this.영어 = 영어
      this.수학 = 수학
      this.과학 = 과학
    }

    getSum() {
      return this.국어 + this.영어 + this.수학 + this.과학
    }
    getAverage() {
      return this.getSum() / 4
    }
    toString () {
      return `${this.이름}\t${this.getSum()}점\t${this.getAverage()}점\n`
    }
  }

  // 객체 선언
  const students = []
  students.push(new Student("구름", 88, 89, 79, 90))
  students.push(new Student("겨울", 85, 79, 72, 99))
  students.push(new Student("햇살", 92, 88, 73, 97))
  students.push(new Student("달님", 98, 78, 75, 89))

  //출력
  // 출력
  let ouput = '이름\t총점\t평균\n'
  for (const student of students) {
    ouput += student.toString()
  }
  console.log(ouput);
</script>
```

## 09-2 클래스의 고급 기능

클래스라는 문법은 객체를 더 안전하고 효율적으로 생성하기 위해 만들어진 문법입니다.
따라서 어떤 위험과 어떤 비효율이 있었는 지 이해해야 문법을 제대로 활용할 수 있습니다.

### 상속

**상속**은 클래스의 선언 코드를 중복해서 작성하지 않도록 함으로써 코드의 생산 효율을 올리는 문법입니다.

```javascript
class 클래스 이름 extends 부모클래스 이름{

}
```

상속은 어떤 클래스가 가지고 있는 유산(속성과 메소드)을 다른 클래스에게 물려주는 형태로 사용합니다.

이때 유산을 주는 클래스를 **부모 클래스**(parent class), 유산을 받는 클래스를 **자식 클래스**(child class)입니다.

```html
<script>
  // 사각형 클래스
  class Rectangle {
    constructor (width, height) {
      this.width = width
      this.height = height
    }
    // 사각형 둘레를 구하는 메소드
    getPerimeter() {
      return 2 * (this.width + this.height)
    }

    // 사각형의 넓이를 구하는 메소드
    getArea () {
      return this.width * this.height
    }
  }  

  // 정사각형 클래스
  class Square extends Rectangle {
    constructor (length) {
      super(length, length)
    }
    // 둘레, 넓이 구하는 메소드는 상속
  }

  // 클래스 사용하기
  const square = new Square(10)
  console.log(`정사각형의 둘레 : ${square.getPerimeter()}`);
  console.log(`정사각형의 넓이 : ${square.getArea()}`);
</script>
```

### private 속성과 메소드

private 속성과 메소드는 클래스 사용자가 클래스 속성(또는 메소드)을 의도하지 않은 방향으로 사용하는 것을 막아 클래스의 안정성을 확보하기 위해 사용합니다.

```javascript
class 클래스 이름 {
  #속성 이름
  #메소드 이름 () {

  }
}
```

```html
<script>
  class Square {
    // 이 위치에 해당 속성을 private 속성으로 사용하겠다고 미리 선언
    #length

    constructor(length) {
      if (length <= 0) {
        throw '길이는 0보다 커야 합니다.'
      }
      this.#length = length
    }

    getPerimeter() {return 4 * this.#length}
    getArea () {return this.#length * this.#length}
  }

  // 클래스 사용
  const square = new Square(10)
  console.log(`정사각형의 둘레 : ${square.getPerimeter()}`);
  console.log(`정사각형의 넓이 : ${square.getArea()}`);
  console.log('');

  // length 와 #length는 다른 속성이므로 영향을 주지 못함
  square.length = -10
  console.log(`정사각형의 둘레 : ${square.getPerimeter()}`);
  console.log(`정사각형의 넓이 : ${square.getArea()}`);

  // square.#length = -10 구문 오류 발생
</script>
```

```
출력

정사각형의 둘레 : 40
정사각형의 넓이 : 100

정사각형의 둘레 : 40
정사각형의 넓이 : 100
```

private 속성으로 변경하면 클래스 외부에서는 해당 속성에 접근할 수 없습니다.
만약 해당 속성에 접근하려고 하면 구문 오류를 발생시켜 사용자에게 알려줍니다.

### 게터와 세터

private 속성을 사용하면 외부에서는 #length 속성에 아예 접근할 수 없는 문제가 생깁니다. 현재 square 객체의 length 속성이 몇인지 확인할 수 없고, 변경도 할 수 없습니다.

```html
<script>
  class Square {
    // 이 위치에 해당 속성을 private 속성으로 사용하겠다고 미리 선언
    #length
    
    constructor(length) {
      this.setLength(length)
    }

    setLength(value) {
      if (value <= 0) {
        throw '길이는 0보다 커야 합니다.'
      }
      this.#length = value
    }
    
    getLength() {
      return this.#length
    }

    getPerimeter() {return 4 * this.#length}
    getArea () {return this.#length * this.#length}
  }

  // 클래스 사용
  const square = new Square(10)
  square.setLength(20)
  console.log(`한 변의 길이는 ${square.getLength()}입니다.`);

  // 예외 발생
  square.setLength(-10)
</script>
```

```
출력

한 변의 길이는 20입니다.
Uncaught Error 길이는 0보다 커야 합니다.
```

get속성() 메소드처럼 속성 값을 확인하는 메소드를 **게터**(getter)라고 하며, set속성() 메소드처럼 속성에 값을 지정할 때 사용하는 메소드를 **세터**(setter)라고 합니다.

게터와 세터는 필요한 경우에만 사용하기에, 사용자가 값을 읽는 것을 거부한다면 게터를 만들지 않고 값을 지정하는 것을 막는다면 세터를 만들지 않아도 됩니다.

- get, set 키워드

많은 프레임워크 개발자들이 코드를 사용하기에 개발자들이 더 쉽게 사용할 수 있도록 get, set 키워드 문법을 제공합니다.

```javascript
class 클래스 이름 {
  get 이름() {return 값}
  set 이름(value) {}
}
```

```html
<script>
  class Square {
    // 이 위치에 해당 속성을 private 속성으로 사용하겠다고 미리 선언
    #length
    
    constructor(length) {
      // this.length에 값을 지정하면, set length(length)메소드 부분이 호출됩니다.
      this.length = length
    }

    // 게터
    get length() {
      return this.#length
    }
    get perimeter() {
      return 4 * this.#length
    }

    get area () {
      return this.#length * this.#length
    }

    // 세터
    set length(length) {
      if (length <= 0) {
        throw '길이는 0보다 커야 합니다.'
      }
      this.#length = length
    }
  }

  // 클래스 사용
  const squareA = new Square(10)
  // 속성을 사용하는 형태로 사용하면 게터와 세터를 자동으로 호출합니다.
  squareA.length = 20
  console.log(`한 변의 길이는 ${squareA.length}입니다.`);
  console.log(`정사각형의 둘레 : ${squareA.perimeter}`);
  console.log(`정사각형의 넓이 : ${squareA.area}`);

  // 예외 발생
  const squareB = new Square(-10)
</script>
```

```
출력

한 변의 길이는 20입니다.
정사각형의 둘레 : 80
정사각형의 넓이 : 400
Uncaught Error 길이는 0보다 커야 합니다.
```

클래스를 활용하는 쪽에서 단순하게 속성을 사용하는 형태처럼 게터와 세터를 사용할 수 있게 됩니다.

### static 속성과 메소드

static 속성과 static 메소드는 정적 속성, 정적 메소드라고도 부릅니다.


```javascript
class 클래스 이름 {
  static 속성 = 값
  static 메소드 () {

  }
}
```

static 속성과 메소드는 인스턴스를 만들지 않고 사용할 수 있는 속성과 메소드로 클래스 이름 뒤에 점을 찍고 사용합니다.

```javascript
클래스 이름.속성
클래스 이름.메소드()
```

```html
<script>
  class Square {
    // 이 위치에 해당 속성을 private 속성으로 사용하겠다고 미리 선언
    #length
    // private 특성과 static 특성을 동시에 적용할 수 있습니다.
    static #counter = 0
    static get counter() {
      return Square.#counter
    }
    
    constructor(length) {
      this.length = length
      Square.#counter += 1
    }

    // static 메소드
    static perimeterOf(length) {
      return length * 4
    }

    static areaOf(length) {
      return length * length
    }

    // 게터
    get length() {
      return this.#length
    }
    get perimeter() {
      return 4 * this.#length
    }

    get area () {
      return this.#length * this.#length
    }

    // 세터
    set length(length) {
      if (length <= 0) {
        throw '길이는 0보다 커야 합니다.'
      }
      this.#length = length
    }
  }

  // static 속성 사용하기
  const squareA = new Square(10)
  const squareB = new Square(20)
  const squareC = new Square(30)
  console.log(`지금까지 생성된 Square 인스턴스는 ${Square.counter}개입니다.`);
  
  // static 메소드 사용하기
  console.log(`한 변의 길이가 20인 정사각형의 둘레는 ${Square.perimeterOf(20)}입니다.`);
  console.log(`한 변의 길이가 30인 정사각형의 넓이는 ${Square.areaOf(30)}입니다.`);
</script>
```

### 오버라이드

부모가 가지고 있는 함수를 자식에서 다시 선언하여 덮어쓰는 것을 **오버라이드**(override)라고 합니다.

만약 부모에 있던 메소드의 내용도 다시 사용하고 싶다면 `super.메소드()` 형태의 코드를 사용합니다.

```html
<script>
  // 클래스 선언
  class LifeCycle {
    call () {
      this.a()
      this.b()
      this.c()
    }
    a () {console.log('a() 메소드를 호출합니다.');}
    b () {console.log('b() 메소드를 호출합니다.');}
    c () {console.log('c() 메소드를 호출합니다.');}
  }

  class Child extends LifeCycle {
    a () {
      console.log('자식의 a() 메소드입니다.');
    }
    b () {
      super.b()
      console.log('자식의 b() 메소드입니다.');
    }
  }

  new Child().call()
</script>
```

```
출력

자식의 a() 메소드입니다.
b() 메소드를 호출합니다.
자식의 b() 메소드입니다.
c() 메소드를 호출합니다.
```

---

# 10 리액트 라이브러리

## 10-1 리액트의 기본

## 10-2 리액트와 데이터

# 부록 A 


## 정답 및 해설

## 찾아보기


---
