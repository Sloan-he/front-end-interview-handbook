# JS 질문

* [이벤트 위임에 대해 설명하세요.](#이벤트-위임에-대해-설명하세요)
* [`this`가 JavaScript 에서 어떻게 작동하는지 설명하세요.](#this가-javascript에서-어떻게-작동하는지-설명하세요)
* [프로토타입 상속이 어떻게 작동하는지 설명하세요.](#프로토타입-상속이-어떻게-작동하는지-설명하세요)
* [AMD 대 CommonJS 에 대해 어떻게 생각하십니까?](#amd-대-commonjs에-대해-어떻게-생각하십니까)
* [다음 내용이 IIFE 로 작동하지 않는 이유를 설명하세요: `function foo(){ }();`를 IIFE 로 만들기 위해서는 무엇이 바뀌어야 할까요?](#다음-내용이-iife로-작동하지-않는-이유를-설명하세요-function-foo-를-iife로-만들기-위해서는-무엇이-바뀌어야-할까요)
* [`null`, `undefined`, `선언되지 않은 변수` 의 차이점은 무엇입니까? 당신은 어떻게 이 상태들에 대한 점검을 할 것입니까?](#null-undefined-선언되지-않은-변수-의-차이점은-무엇입니까-당신은-어떻게-이-상태들에-대한-점검을-할-것입니까)
* [클로저는 무엇이며, 어떻게/왜 사용합니까?](#클로저는-무엇이며-어떻게-왜-사용합니까)
* [`.forEach` 루프와 `.map()` 루프 사이의 주요 차이점을 설명할 수 있습니까? 왜 둘중 하나를 선택하겠습니까?](#forEach-루프와-map-루프-사이의-주요-차이점을-설명할-수-있습니까-왜-둘중-하나를-선택하겠습니까)
* [익명 함수의 일반적인 사용 사례는 무엇입니까?](#익명-함수의-일반적인-사용-사례는-무엇입니까)
* [코드를 어떻게 구성합니까? (모듈 패턴, 고전적인 상속?)](#코드를-어떻게-구성합니까-모듈-패턴-고전적인-상속)
* [What's the difference between host objects and native objects?](#whats-the-difference-between-host-objects-and-native-objects)
* [Difference between: function `Person(){}`, `var person = Person()`, and `var person = new Person()`?](#difference-between-function-person-var-person--person-and-var-person--new-person)
* [What's the difference between `.call` and `.apply`?](#whats-the-difference-between-call-and-apply)
* [Explain `Function.prototype.bind`.](#explain-functionprototypebind)
* [When would you use `document.write()`?](#when-would-you-use-documentwrite)
* [What's the difference between feature detection, feature inference, and using the UA string?](#whats-the-difference-between-feature-detection-feature-inference-and-using-the-ua-string)
* [Explain Ajax in as much detail as possible.](#explain-ajax-in-as-much-detail-as-possible)
* [What are the advantages and disadvantages of using Ajax?](#what-are-the-advantages-and-disadvantages-of-using-ajax)
* [Explain how JSONP works (and how it's not really Ajax).](#explain-how-jsonp-works-and-how-its-not-really-ajax)
* [Have you ever used JavaScript templating? If so, what libraries have you used?](#have-you-ever-used-javascript-templating-if-so-what-libraries-have-you-used)
* [Explain "hoisting".](#explain-hoisting)
* [Describe event bubbling.](#describe-event-bubbling)
* [What's the difference between an "attribute" and a "property"?](#whats-the-difference-between-an-attribute-and-a-property)
* [Why is extending built-in JavaScript objects not a good idea?](#why-is-extending-built-in-javascript-objects-not-a-good-idea)
* [Difference between document `load` event and document `DOMContentLoaded` event?](#difference-between-document-load-event-and-document-domcontentloaded-event)
* [What is the difference between `==` and `===`?](#what-is-the-difference-between--and-)
* [Explain the same-origin policy with regards to JavaScript.](#explain-the-same-origin-policy-with-regards-to-javascript)
* [Make this work: `duplicate([1,2,3,4,5]); // [1,2,3,4,5,1,2,3,4,5]`](#make-this-work)
* [Why is it called a Ternary expression, what does the word "Ternary" indicate?](#why-is-it-called-a-ternary-expression-what-does-the-word-ternary-indicate)
* [What is "use strict";? what are the advantages and disadvantages to using it?](#what-is-use-strict-what-are-the-advantages-and-disadvantages-to-using-it)
* [Create a for loop that iterates up to 100 while outputting "fizz" at multiples of 3, "buzz" at multiples of 5 and "fizzbuzz" at multiples of 3 and 5](#create-a-for-loop-that-iterates-up-to-100-while-outputting-fizz-at-multiples-of-3-buzz-at-multiples-of-5-and-fizzbuzz-at-multiples-of-3-and-5)
* [Why is it, in general, a good idea to leave the global scope of a website as-is and never touch it?](#why-is-it-in-general-a-good-idea-to-leave-the-global-scope-of-a-website-as-is-and-never-touch-it)
* [Why would you use something like the `load` event? Does this event have disadvantages? Do you know any alternatives, and why would you use those?](#why-would-you-use-something-like-the-load-event-does-this-event-have-disadvantages-do-you-know-any-alternatives-and-why-would-you-use-those)
* [Explain what a single page app is and how to make one SEO-friendly.](#explain-what-a-single-page-app-is-and-how-to-make-one-seo-friendly)
* [What is the extent of your experience with Promises and/or their polyfills?](#what-is-the-extent-of-your-experience-with-promises-andor-their-polyfills)
* [What are the pros and cons of using Promises instead of callbacks?](#what-are-the-pros-and-cons-of-using-promises-instead-of-callbacks)
* [What are some of the advantages/disadvantages of writing JavaScript code in a language that compiles to JavaScript?](#what-are-some-of-the-advantagesdisadvantages-of-writing-javascript-code-in-a-language-that-compiles-to-javascript)
* [What tools and techniques do you use debugging JavaScript code?](#what-tools-and-techniques-do-you-use-for-debugging-javascript-code)
* [What language constructions do you use for iterating over object properties and array items?](#what-language-constructions-do-you-use-for-iterating-over-object-properties-and-array-items)
* [Explain the difference between mutable and immutable objects.](#explain-the-difference-between-mutable-and-immutable-objects)
* [Explain the difference between synchronous and asynchronous functions.](#explain-the-difference-between-synchronous-and-asynchronous-functions)
* [What is event loop? What is the difference between call stack and task queue?](#what-is-event-loop-what-is-the-difference-between-call-stack-and-task-queue)
* [Explain the differences on the usage of `foo` between `function foo() {}` and `var foo = function() {}`](#explain-the-differences-on-the-usage-of-foo-between-function-foo--and-var-foo--function-)
* [What are the differences between variables created using `let`, `var` or `const`?](#what-are-the-differences-between-variables-created-using-let-var-or-const)
* [What are the differences between ES6 class and ES5 function constructors?](#what-are-the-differences-between-es6-class-and-es5-function-constructors)
* [Can you offer a use case for the new arrow => function syntax? How does this new syntax differ from other functions?](#can-you-offer-a-use-case-for-the-new-arrow--function-syntax-how-does-this-new-syntax-differ-from-other-functions)
* [What advantage is there for using the arrow syntax for a method in a constructor?](#what-advantage-is-there-for-using-the-arrow-syntax-for-a-method-in-a-constructor)
* [What is the definition of a higher-order function?](#what-is-the-definition-of-a-higher-order-function)
* [Can you give an example for destructuring an object or an array?](#can-you-give-an-example-for-destructuring-an-object-or-an-array)
* [ES6 Template Literals offer a lot of flexibility in generating strings, can you give an example?](#es6-template-literals-offer-a-lot-of-flexibility-in-generating-strings-can-you-give-an-example)
* [Can you give an example of a curry function and why this syntax offers an advantage?](#can-you-give-an-example-of-a-curry-function-and-why-this-syntax-offers-an-advantage)
* [What are the benefits of using spread syntax and how is it different from rest syntax?](#what-are-the-benefits-of-using-spread-syntax-and-how-is-it-different-from-rest-syntax)
* [How can you share code between files?](#how-can-you-share-code-between-files)
* [Why you might want to create static class members?](#why-you-might-want-to-create-static-class-members)

---

## JS 질문

[프론트엔드 면접 질문 - JS 질문](https://github.com/h5bp/Front-end-Developer-Interview-Questions#html-questions)에 대한 해설입니다.
Pull Request 를 통한 제안 및 수정 요청을 환영합니다.

### 이벤트 위임에 대해 설명하세요.

이벤트 위임은 이벤트 리스너를 하위 요소에 추가하는 대신 상위 요소에 추가하는 기법입니다. 리스너는 DOM 의 버블링된 이벤트로 인해 하위 요소에서 이벤트가 발생될 때마다 실행됩니다. 이 기술의 이점은 다음과 같습니다.

* 각 하위 항목에 이벤트 핸들러를 연결하지 않고 상위 요소에 하나의 단일 핸들러만 필요하기 때문에 메모리 사용 공간이 줄어 듭니다.
* 제거된 요소에서 핸들러를 해제하고 새 요소에 대해 이벤트를 바인딩할 필요가 없습니다.

###### 참고자료

* <https://davidwalsh.name/event-delegate>
* <https://stackoverflow.com/questions/1687296/what-is-dom-event-delegation>

### `this`가 JavaScript 에서 어떻게 작동하는지 설명하세요.

`this`는 간단하게 설명하기 어렵습니다. JavaScript 에서 가장 혼란스러운 개념 중 하나입니다. 대략 설명하면 `this`의 값은 함수가 호출되는 방식에 따라 달라집니다.
온라인에 많은 설명이 있는데 [Arnav Aggrawal](https://medium.com/@arnav_aggarwal)의 설명이 가장 명확했습니다.
다음 규칙과 같습니다.

1.  함수를 호출할 때 `new` 키워드를 사용하는 경우 함수 내부에 있는 `this`는 완전히 새로운 객체입니다.
2.  `apply`, `call`, `bind`가 함수의 호출 / 작성에 사용되는 경우 함수 내의 `this`는 인수로 전달된 객체입니다.
3.  `obj.method()`와 같이 함수를 메서드로 호출하는 경우 `this`는 함수가 프로퍼티인 객체입니다.
4.  함수가 자유함수로 호출되는 경우 즉 위의 조건없이 호출되는 경우 `this`는 전역 객체입니다. 브라우저에서는 `window` 객체입니다. 엄격 모드(`'use strict'`) 일 경우 `this`는 전역 객체 대신 `undefined`가 됩니다.
5.  위의 규칙 중 다수가 적용되면 더 높은 규칙이 승리하고 `this`값을 설정합니다.
6.  함수가 ES2015 화살표 함수인 경우 위의 모든 규칙을 무시하고 생성된 시점에서 주변 스코프의 `this`값을 받습니다.

상세한 설명은 [Medium 의 글](https://codeburst.io/the-simple-rules-to-this-in-javascript-35d97f31bde3)를 참조하세요.

###### 참고자료

* <https://codeburst.io/the-simple-rules-to-this-in-javascript-35d97f31bde3>
* <https://stackoverflow.com/a/3127440/1751946>

### 프로토타입 상속이 어떻게 작동하는지 설명하세요.

이것은 매우 일반적인 JavaScript 인터뷰 질문입니다. 모든 JavaScript 객체는 다른 객체에 대한 참조인 `prototype` 프로퍼티를 가지고 있습니다. 객체의 프로퍼티에 접근할 때 해당 객체에 해당 프로퍼티가 없으면 JavaScript 엔진은 객체의 `prototype`과 `prototype`의 `prototype`등을 보고 프로퍼티가 정의될 때까지 찾고 만약 객체의 프로퍼티에 접근할 때 해당 객체에 해당 프로퍼티가 없으면 프로토타입 체인 중 하나에 있거나 프로토타입 체인의 끝에 도달 할 때까지 찾습니다. 이 동작은 고전적인 상속을 흉내내지만 실제로 [상속보다 위임](https://davidwalsh.name/javascript-objects)에 더 가깝습니다.

###### 참고자료

* <https://www.quora.com/What-is-prototypal-inheritance/answer/Kyle-Simpson>
* <https://davidwalsh.name/javascript-objects>

### AMD 대 CommonJS 에 대해 어떻게 생각하십니까?

두 가지 모두 ES2015 가 등장할 때까지 JavaScript 에 기본적으로 존재하지 않는 모듈 시스템을 구현하는 방법입니다. CommonJS 는 동기식인 반면 AMD (Asynchronous Module Definition - 비동기식 모듈 정의)는 분명히 비동기식입니다. CommonJS 는 서버-사이드 개발을 염두에 두고 설계되었으며 AMD 는 모듈의 비동기 로딩을 지원하므로 브라우저용으로 더 많이 사용됩니다.

AMD 은 구문이 매우 장황하고 CommonJS 은 다른 언어로 된 import 문을 작성하는 스타일에 더 가깝습니다. 대부분의 경우 AMD 를 필요로 하지 않습니다. 모든 JavaScript 를 연결된 하나의 번들 파일로 제공하면 비동기 로딩 속성의 이점을 누릴 수 없기 때문입니다. 또한 CommonJS 구문은 모듈 작성의 노드 스타일에 가깝고 클라이언트-사이드과 서버-사이드 JavaScript 개발 사이를 전환할 때 문맥 전환 오버 헤드가 적습니다.

ES2015 모듈이 동기식 및 비동기식 로딩을 모두 지원하는 것이 반가운 것은 마침내 하나의 접근 방식만 고수할 수 있다는 점입니다. 브라우저와 노드에서 완전히 작동되지는 않았지만 언제나 트랜스파일러를 사용하여 코드를 변환할 수 있습니다.

###### 참고자료

* <https://auth0.com/blog/javascript-module-systems-showdown/>
* <https://stackoverflow.com/questions/16521471/relation-between-commonjs-amd-and-requirejs>

### 다음 내용이 IIFE 로 작동하지 않는 이유를 설명하세요: `function foo(){ }();`를 IIFE 로 만들기 위해서는 무엇이 바뀌어야 할까요?

IIFE 는 즉시 함수 호출 표현식을 의미합니다. JavaScript 파서는 `function foo(){ }();`을 `function foo(){ }`와 `();` 같이 읽습니다. 전자는 함수 선언이며 후자 ( 한 쌍의 괄호 )는 함수를 호출하려고 시도했지만 이름이 지정되지 않았기 때문에 `Uncaught SyntaxError : Unexpected token`)을 던집니다.

추가로 괄호를 추가하는 두 가지 방법이 있습니다: `(function foo(){ })()` 그리고 `(function foo(){ }())`.

JavaScript 파서는 `function foo () {} ();`를`function foo () {}`와 `();`로 읽습니다. 이러한 함수는 전역 스코프에서 노출되지 않으며 본문 내에서 자체를 참조할 필요가 없는 경우 해당 함수의 이름을 생략할 수도 있습니다.

###### 참고자료

* <http://lucybain.com/blog/2014/immediately-invoked-function-expression/>

### `null`, `undefined`, `선언되지 않은 변수` 의 차이점은 무엇입니까? 당신은 어떻게 이 상태들에 대한 점검을 할 것입니까?

**선언되지 않은 변수** 변수는 이전에 `var`, `let`, `const` 를 사용하여 생성되지 않은 식별자에 값을 할당 할 때 생성됩니다. `선언되지 않은 변수` 는 현재 범위 외부에서 전역으로 정의됩니다. strict 모드에서는 `선언되지 않은 변수` 에 할당하려고 할 때 `ReferenceError` 가 throw 됩니다. `선언되지 않은 변수` 는 전역 변수처럼 좋지 않은 것입니다. 그것들은 모두 피하세요! 이들을 검사하기 위해 사용할 때 `try` / `catch` 블록에 감싸십시오.

```js
function foo() {
  x = 1; // strict 모드에서 ReferenceError를 발생시킵니다.
}

foo();
console.log(x); // 1
```

`undefined` 변수는 선언되었지만 값이 할당되지 않은 변수입니다. 이것은 `undefined` 타입입니다. 함수가 실행 결과에 따라 값을 반환하지 않으면 변수에 할당되며, 변수가 `undefined` 값을 갖습니다. 이것을 검사하기 위해, 엄격한 (`===`) 연산자 또는 `typeof` 에 `undefined` 문자열을 사용하여 비교하십시오. 확인을 위해 추상 평등 연산자(`==`)를 사용해서는 안되며, 이는 값이 `null` 이면 `true` 를 반환합니다.

```js
var foo;
console.log(foo); // undefined
console.log(foo === undefined); // true
console.log(typeof foo === 'undefined'); // true

console.log(foo == null); // true. Wrong, don't use this to check!

function bar() {}
var baz = bar();
console.log(baz); // undefined
```

`null` 인 변수는 `null` 값에 명시적으로 할당될 것입니다. 그것은 값을 나타내지 않으며 명시적으로 할당된다는 점에서 `undefined`와 다릅니다. `null`을 체크하기 위해서 단순히 완전 항등 연산자(`===`)를 사용하여 비교하면 됩니다. 위와 같이, 추상 평등 연산자 (`==`)를 사용해서는 안되며, 값이 `undefined`이면 `true`를 반환합니다.

```js
var foo = null;
console.log(foo === null); // true

console.log(foo == undefined); // true. Wrong, don't use this to check!
```

개인적 습관으로, 저는 변수를 선언하지 않거나 할당하지 않은 상태로 두지 않습니다. 아직 사용하지 않으려는 경우, 선언한 후에 명시적으로 `null` 을 할당할 것입니다.

###### 참고자료

* <https://stackoverflow.com/questions/15985875/effect-of-declared-and-undeclared-variables>
* <https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Global_Objects/undefined>

### 클로저는 무엇이며, 어떻게/왜 사용합니까?

클로저는 함수와 그 함수가 선언된 렉시컬 환경의 조합입니다. "렉시컬"은 렉시컬 범위 지정이 변수가 사용 가능한 위치를 결정하기 위해 소스 코드 내에서 변수가 선언된 위치를 사용한다는 사실을 나타냅니다. 클로저는 외부 함수가 반환된 후에도 외부 함수의 변수 범위 체인에 접근할 수 있는 함수입니다.

**왜 클로저를 사용합니까?**

* 데이터 프라이버시 / 클로저로 private method 를 모방. 일반적으로 [모듈 패턴](https://addyosmani.com/resources/essentialjsdesignpatterns/book/#modulepatternjavascript)에 사용됩니다.
* [부분적인 응용 프로그램 또는 currying](https://medium.com/javascript-scene/curry-or-partial-application-8150044c78b8#.l4b6l1i3x).

###### 참고자료

* <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Closures>
* <https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-closure-b2f0d2152b36>

### `.forEach` 루프와 `.map()` 루프 사이의 주요 차이점을 설명할 수 있습니까? 왜 둘중 하나를 선택하겠습니까?

이 두 함수의 차이점을 이해하기 위해 각 함수가 무엇을 하는지 살펴보겠습니다.

**`forEach`**

* 배열의 요소를 반복합니다.
* 각 요소에 대한 콜백을 실행합니다.
* 값을 반환하지 않습니다.

```js
const a = [1, 2, 3];
const doubled = a.forEach((num, index) => {
  // Do something with num and/or index.
});

// doubled = undefined
```

**`map`**

* 배열의 요소를 반복합니다.
* 각 요소에서 함수를 호출하여 결과로 새 배열을 작성하여 각 요소를 새 요소에 맵핑합니다.

```js
const a = [1, 2, 3];
const doubled = a.map(num => {
  return num * 2;
});

// doubled = [2, 4, 6]
```

`.forEach` 와 `.map()` 의 주된 차이점은 `.map()` 이 새로운 배열을 반환한다는 것입니다. 결과가 필요하지만 원본 배열을 변경하고 싶지 않으면 `.map()` 이 확실한 선택입니다. 단순히 배열을 반복할 필요가 있다면, forEach 가 좋은 선택입니다.

###### 참고자료

* <https://codeburst.io/javascript-map-vs-foreach-f38111822c0f>

### 익명 함수의 일반적인 사용 사례는 무엇입니까?

익명함수는 IIFE 로 사용되어 지역 범위 내에서 일부 코드를 캡슐화하므로 선언된 변수가 전역 범위로 누출되지 않습니다.

```js
(function() {
  // Some code here.
})();
```

한 번 사용되며 다른 곳에서는 사용할 필요가 없는 콜백으로 사용됩니다. 함수 본체를 찾기 위해 다른 곳을 찾아볼 필요없이 코드를 호출하는 코드 바로 안에 핸들러가 정의되어 있으면 코드가 보다 독립적이고 읽기 쉽게 보일 것입니다.

```js
setTimeout(function() {
  console.log('Hello world!');
}, 1000);
```

함수형 프로그래밍 또는 Lodash 에 대한 인수(콜백과 유사).

```js
const arr = [1, 2, 3];
const double = arr.map(function(el) {
  return el * 2;
});
console.log(double); // [2, 4, 6]
```

###### 참고자료

* <https://www.quora.com/What-is-a-typical-usecase-for-anonymous-functions>
* <https://stackoverflow.com/questions/10273185/what-are-the-benefits-to-using-anonymous-functions-instead-of-named-functions-fo>

### 코드를 어떻게 구성합니까? (모듈 패턴, 고전적인 상속?)

과거에는 Backbone 모델을 만들고 그 모델에 메소드를 연결하는 등 OOP 접근 방식을 장려하는 모델에 Backbone 을 사용했습니다.

모듈 패턴은 여전히 ​​ 훌륭하지만, 요즘에는 React/Redux 기반의 Flux 아키텍처를 사용합니다. 이 아키텍처는 단방향 프로그래밍 방식을 권장합니다. 저는 평범한 객체를 사용하여 응용 프로그램의 모델을 표현하고 이러한 객체를 조작하는 유틸리티 순수 함수를 작성합니다. 상태는 다른 Redux 응용 프로그램에서와 마찬가지로 action 및 reducer 를 사용하여 조작됩니다.

가능한 경우 고전적인 상속을 사용하지 않습니다. 저는 [이 규칙들](https://medium.com/@dan_abramov/how-to-use-classes-and-sleep-at-night-9af8de78ccb4)을 유지합니다.

### What's the difference between host objects and native objects?

Native objects are objects that are part of the JavaScript language defined by the ECMAScript specification, such as `String`, `Math`, `RegExp`, `Object`, `Function`, etc.

Host objects are provided by the runtime environment (browser or Node), such as `window`, `XMLHTTPRequest`, etc.

###### References

* <https://stackoverflow.com/questions/7614317/what-is-the-difference-between-native-objects-and-host-objects>

### Difference between: `function Person(){}`, `var person = Person()`, and `var person = new Person()`?

This question is pretty vague. My best guess at its intention is that it is asking about constructors in JavaScript. Technically speaking, `function Person(){}` is just a normal function declaration. The convention is use PascalCase for functions that are intended to be used as constructors.

`var person = Person()` invokes the `Person` as a function, and not as a constructor. Invoking as such is a common mistake if it the function is intended to be used as a constructor. Typically, the constructor does not return anything, hence invoking the constructor like a normal function will return `undefined` and that gets assigned to the variable intended as the instance.

`var person = new Person()` creates an instance of the `Person` object using the `new` operator, which inherits from `Person.prototype`. An alternative would be to use `Object.create`, such as: `Object.create(Person.prototype)`.

```js
function Person(name) {
  this.name = name;
}

var person = Person('John');
console.log(person); // undefined
console.log(person.name); // Uncaught TypeError: Cannot read property 'name' of undefined

var person = new Person('John');
console.log(person); // Person { name: "John" }
console.log(person.name); // "john"
```

###### References

* <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/new>

### What's the difference between `.call` and `.apply`?

Both `.call` and `.apply` are used to invoke functions and the first parameter will be used as the value of `this` within the function. However, `.call` takes in a comma-separated arguments as the next arguments while `.apply` takes in an array of arguments as the next argument. An easy way to remember this is C for `call` and comma-separated and A for `apply` and array of arguments.

```js
function add(a, b) {
  return a + b;
}

console.log(add.call(null, 1, 2)); // 3
console.log(add.apply(null, [1, 2])); // 3
```

### Explain `Function.prototype.bind`.

Taken word-for-word from [MDN](https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Global_objects/Function/bind):

> The `bind()` method creates a new function that, when called, has its this keyword set to the provided value, with a given sequence of arguments preceding any provided when the new function is called.

In my experience, it is most useful for binding the value of `this` in methods of classes that you want to pass into other functions. This is frequently done in React components.

###### References

* <https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Global_objects/Function/bind>

### When would you use `document.write()`?

`document.write()` writes a string of text to a document stream opened by `document.open()`. When `document.write()` is executed after the page has loaded, it will call `document.open` which clears the whole document (`<head>` and `<body>` removed!) and replaces the contents with the given parameter value in string. Hence it is usually considered dangerous and prone to misuse.

There are some answers online that explain `document.write()` is being used in analytics code or [when you want to include styles that should only work if JavaScript is enabled](https://www.quirksmode.org/blog/archives/2005/06/three_javascrip_1.html). It is even being used in HTML5 boilerplate to [load scripts in parallel and preserve execution order](https://github.com/paulirish/html5-boilerplate/wiki/Script-Loading-Techniques#documentwrite-script-tag)! However, I suspect those reasons might be outdated and in the modern day, they can be achieved without using `document.write()`. Please do correct me if I'm wrong about this.

###### References

* <https://www.quirksmode.org/blog/archives/2005/06/three_javascrip_1.html>
* <https://github.com/h5bp/html5-boilerplate/wiki/Script-Loading-Techniques#documentwrite-script-tag>

### What's the difference between feature detection, feature inference, and using the UA string?

**Feature Detection**

Feature detection involves working out whether a browser supports a certain block of code, and running different code dependent on whether it does (or doesn't), so that the browser can always provide a working experience rather crashing/erroring in some browsers. For example:

```js
if ('geolocation' in navigator) {
  // Can use navigator.geolocation
} else {
  // Handle lack of feature
}
```

[Modernizr](https://modernizr.com/) is a great library to handle feature detection.

**Feature Inference**

Feature inference checks for a feature just like feature detection, but uses another function because it assumes it will also exist, e.g.:

```js
if (document.getElementsByTagName) {
  element = document.getElementById(id);
}
```

This is not really recommended. Feature detection is more foolproof.

**UA String**

This is a browser-reported string that allows the network protocol peers to identify the application type, operating system, software vendor or software version of the requesting software user agent. It can be accessed via `navigator.userAgent`. However, the string is tricky to parse and can be spoofed. For example, Chrome reports both as Chrome and Safari. So to detect Safari you have to check for the Safari string and the absence of the Chrome string. Avoid this method.

###### References

* <https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Cross_browser_testing/Feature_detection>
* <https://stackoverflow.com/questions/20104930/whats-the-difference-between-feature-detection-feature-inference-and-using-th>
* <https://developer.mozilla.org/en-US/docs/Web/HTTP/Browser_detection_using_the_user_agent>

### Explain Ajax in as much detail as possible.

Ajax (asynchronous JavaScript and XML) is a set of web development techniques using many web technologies on the client side to create asynchronous web applications. With Ajax, web applications can send data to and retrieve from a server asynchronously (in the background) without interfering with the display and behavior of the existing page. By decoupling the data interchange layer from the presentation layer, Ajax allows for web pages, and by extension web applications, to change content dynamically without the need to reload the entire page. In practice, modern implementations commonly substitute JSON for XML due to the advantages of being native to JavaScript.

The `XMLHttpRequest` API is frequently used for the asynchronous communication or these days, the `fetch` API.

###### References

* <https://en.wikipedia.org/wiki/Ajax_(programming>)
* <https://developer.mozilla.org/en-US/docs/AJAX>

### What are the advantages and disadvantages of using Ajax?

**Advantages**

* Better interactivity. New content from the server can be changed dynamically without the need to reload the entire page.
* Reduce connections to the server since scripts and stylesheets only have to be requested once.
* State can be maintained on a page. JavaScript variables and DOM state will persist because the main container page was not reloaded.
* Basically most of the advantages of an SPA.

**Disadvantages**

* Dynamic webpages are harder to bookmark.
* Does not work if JavaScript has been disabled in the browser.
* Some webcrawlers do not execute JavaScript and would not see content that has been loaded by JavaScript.
* Basically most of the disadvantages of an SPA.

### Explain how JSONP works (and how it's not really Ajax).

JSONP (JSON with Padding) is a method commonly used to bypass the cross-domain policies in web browsers because Ajax requests from the current page to a cross-origin domain is not allowed.

JSONP works by making a request to a cross-origin domain via a `<script>` tag and usually with a `callback` query parameter, for example: `https://example.com?callback=printData`. The server will then wrap the data within a function called `printData` and return it to the client.

```html
<!-- https://mydomain.com -->
<script>
function printData(data) {
  console.log(`My name is ${data.name}!`);
}
</script>

<script src="https://example.com?callback=printData"></script>
```

```js
// File loaded from https://example.com?callback=printData
printData({ name: 'Yang Shun' });
```

The client has to have the `printData` function in its global scope and the function will be executed by the client when the response from the cross-origin domain is received.

JSONP can be unsafe and has some security implications. As JSONP is really JavaScript, it can do everything else JavaScript can do, so you need to trust the provider of the JSONP data.

These days, [CORS](http://en.wikipedia.org/wiki/Cross-origin_resource_sharing) is the recommended approach and JSONP is seen as a hack.

###### References

* <https://stackoverflow.com/a/2067584/1751946>

### Have you ever used JavaScript templating? If so, what libraries have you used?

Yes. Handlebars, Underscore, Lodash, AngularJS and JSX. I disliked templating in AngularJS because it made heavy use of strings in the directives and typos would go uncaught. JSX is my new favourite as it is closer to JavaScript and there is barely any syntax to learn. Nowadays, you can even use ES2015 template string literals as a quick way for creating templates without relying on third-party code.

```js
const template = `<div>My name is: ${name}</div>`;
```

However, do be aware of a potential XSS in the above approach as the contents are not escaped for you, unlike in templating libraries.

### Explain "hoisting".

Hoisting is a term used to explain the behavior of variable declarations in your code. Variables declared or initialized with the `var` keyword will have their declaration "hoisted" up to the top of the current scope. However, only the declaration is hoisted, the assignment (if there is one), will stay where it is. Let's explain with a few examples.

```js
// var declarations are hoisted.
console.log(foo); // undefined
var foo = 1;
console.log(foo); // 1

// let/const declarations are NOT hoisted.
console.log(bar); // ReferenceError: bar is not defined
let bar = 2;
console.log(bar); // 2
```

Function declarations have the body hoisted while the function expressions (written in the form of variable declarations) only has the variable declaration hoisted.

```js
// Function Declaration
console.log(foo); // [Function: foo]
foo(); // 'FOOOOO'
function foo() {
  console.log('FOOOOO');
}
console.log(foo); // [Function: foo]

// Function Expression
console.log(bar); // undefined
bar(); // Uncaught TypeError: bar is not a function
var bar = function() {
  console.log('BARRRR');
};
console.log(bar); // [Function: bar]
```

### Describe event bubbling.

When an event triggers on a DOM element, it will attempt to handle the event if there is a listener attached, then the event is bubbled up to its parent and the same thing happens. This bubbling occurs up the element's ancestors all the way to the `document`. Event bubbling is the mechanism behind event delegation.

### What's the difference between an "attribute" and a "property"?

Attributes are defined on the HTML markup but properties are defined on the DOM. To illustrate the difference, imagine we have this text field in our HTML: `<input type="text" value="Hello">`.

```js
const input = document.querySelector('input');
console.log(input.getAttribute('value')); // Hello
console.log(input.value); // Hello
```

But after you change the value of the text field by adding "World!" to it, this becomes:

```js
console.log(input.getAttribute('value')); // Hello
console.log(input.value); // Hello World!
```

###### References

* <https://stackoverflow.com/questions/6003819/properties-and-attributes-in-html>

### Why is extending built-in JavaScript objects not a good idea?

Extending a built-in/native JavaScript object means adding properties/functions to its `prototype`. While this may seem like a good idea at first, it is dangerous in practice. Imagine your code uses a few libraries that both extend the `Array.prototype` by adding the same `contains` method, the implementations will overwrite each other and your code will break if the behavior of these two methods are not the same.

The only time you may want to extend a native object is when you want to create a polyfill, essentially providing your own implementation for a method that is part of the JavaScript specification but might not exist in the user's browser due to it being an older browser.

###### References

* <http://lucybain.com/blog/2014/js-extending-built-in-objects/>

### Difference between document `load` event and document `DOMContentLoaded` event?

The `DOMContentLoaded` event is fired when the initial HTML document has been completely loaded and parsed, without waiting for stylesheets, images, and subframes to finish loading.

`window`'s `load` event is only fired after the DOM and all dependent resources and assets have loaded.

###### References

* <https://developer.mozilla.org/en-US/docs/Web/Events/DOMContentLoaded>
* <https://developer.mozilla.org/en-US/docs/Web/Events/load>

### What is the difference between `==` and `===`?

`==` is the abstract equality operator while `===` is the strict equality operator. The `==` operator will compare for equality after doing any necessary type conversions. The `===` operator will not do type conversion, so if two values are not the same type `===` will simply return `false`. When using `==`, funky things can happen, such as:

```js
1 == '1'; // true
1 == [1]; // true
1 == true; // true
0 == ''; // true
0 == '0'; // true
0 == false; // true
```

My advice is never to use the `==` operator, except for convenience when comparing against `null` or `undefined`, where `a == null` will return `true` if `a` is `null` or `undefined`.

```js
var a = null;
console.log(a == null); // true
console.log(a == undefined); // true
```

###### References

* <https://stackoverflow.com/questions/359494/which-equals-operator-vs-should-be-used-in-javascript-comparisons>

### Explain the same-origin policy with regards to JavaScript.

The same-origin policy prevents JavaScript from making requests across domain boundaries. An origin is defined as a combination of URI scheme, hostname, and port number. This policy prevents a malicious script on one page from obtaining access to sensitive data on another web page through that page's Document Object Model.

###### References

* <https://en.wikipedia.org/wiki/Same-origin_policy>

### Make this work:

```js
duplicate([1, 2, 3, 4, 5]); // [1,2,3,4,5,1,2,3,4,5]
```

```js
function duplicate(arr) {
  return arr.concat(arr);
}

duplicate([1, 2, 3, 4, 5]); // [1,2,3,4,5,1,2,3,4,5]
```

### Why is it called a Ternary expression, what does the word "Ternary" indicate?

"Ternary" indicates three, and a ternary expression accepts three operands, the test condition, the "then" expression and the "else" expression. Ternary expressions are not specific to JavaScript and I'm not sure why it is even in this list.

###### References

* <https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Operators/Conditional_Operator>

### What is `"use strict";`? What are the advantages and disadvantages to using it?

'use strict' is a statement used to enable strict mode to entire scripts or individual functions. Strict mode is a way to opt in to a restricted variant of JavaScript.

Advantages:

* Makes it impossible to accidentally create global variables.
* Makes assignments which would otherwise silently fail to throw an exception.
* Makes attempts to delete undeletable properties throw (where before the attempt would simply have no effect).
* Requires that function parameter names be unique.
* `this` is undefined in the global context.
* It catches some common coding bloopers, throwing exceptions.
* It disables features that are confusing or poorly thought out.

Disadvantages:

* Many missing features that some developers might be used to.
* No more access to `function.caller` and `function.arguments`.
* Concatenation of scripts written in different strict modes might cause issues.

Overall, I think the benefits outweigh the disadvantages, and I never had to rely on the features that strict mode blocks. I would recommend using strict mode.

###### References

* <http://2ality.com/2011/10/strict-mode-hatred.html>
* <http://lucybain.com/blog/2014/js-use-strict/>

### Create a for loop that iterates up to `100` while outputting **"fizz"** at multiples of `3`, **"buzz"** at multiples of `5` and **"fizzbuzz"** at multiples of `3` and `5`.

Check out this version of FizzBuzz by [Paul Irish](https://gist.github.com/jaysonrowe/1592432#gistcomment-790724).

```js
for (let i = 1; i <= 100; i++) {
  let f = i % 3 == 0,
    b = i % 5 == 0;
  console.log(f ? (b ? 'FizzBuzz' : 'Fizz') : b ? 'Buzz' : i);
}
```

I would not advise you to write the above during interviews though. Just stick with the long but clear approach. For more wacky versions of FizzBuzz, check out the reference link below.

###### References

* <https://gist.github.com/jaysonrowe/1592432>

### Why is it, in general, a good idea to leave the global scope of a website as-is and never touch it?

Every script has access to the global scope, and if everyone is using the global namespace to define their own variables, there will bound to be collisions. Use the module pattern (IIFEs) to encapsulate your variables within a local namespace.

### Why would you use something like the `load` event? Does this event have disadvantages? Do you know any alternatives, and why would you use those?

The `load` event fires at the end of the document loading process. At this point, all of the objects in the document are in the DOM, and all the images, scripts, links and sub-frames have finished loading.

The DOM event `DOMContentLoaded` will fire after the DOM for the page has been constructed, but do not wait for other resources to finish loading. This is preferred in certain cases when you do not need the full page to be loaded before initializing.

TODO.

###### References

* <https://developer.mozilla.org/en-US/docs/Web/API/GlobalEventHandlers/onload>

### Explain what a single page app is and how to make one SEO-friendly.

The below is taken from the awesome [Grab Front End Guide](https://github.com/grab/front-end-guide), which coincidentally, is written by me!

Web developers these days refer to the products they build as web apps, rather than websites. While there is no strict difference between the two terms, web apps tend to be highly interactive and dynamic, allowing the user to perform actions and receive a response for their action. Traditionally, the browser receives HTML from the server and renders it. When the user navigates to another URL, a full-page refresh is required and the server sends fresh new HTML for the new page. This is called server-side rendering.

However in modern SPAs, client-side rendering is used instead. The browser loads the initial page from the server, along with the scripts (frameworks, libraries, app code) and stylesheets required for the whole app. When the user navigates to other pages, a page refresh is not triggered. The URL of the page is updated via the [HTML5 History API](https://developer.mozilla.org/en-US/docs/Web/API/History_API). New data required for the new page, usually in JSON format, is retrieved by the browser via [AJAX](https://developer.mozilla.org/en-US/docs/AJAX/Getting_Started) requests to the server. The SPA then dynamically updates the page with the data via JavaScript, which it has already downloaded in the initial page load. This model is similar to how native mobile apps work.

The benefits:

* The app feels more responsive and users do not see the flash between page navigations due to full-page refreshes.
* Fewer HTTP requests are made to the server, as the same assets do not have to be downloaded again for each page load.
* Clear separation of the concerns between the client and the server; you can easily build new clients for different platforms (e.g. mobile, chatbots, smart watches) without having to modify the server code. You can also modify the technology stack on the client and server independently, as long as the API contract is not broken.

The downsides:

* Heavier initial page load due to loading of framework, app code, and assets required for multiple pages.
* There's an additional step to be done on your server which is to configure it to route all requests to a single entry point and allow client-side routing to take over from there.
* SPAs are reliant on JavaScript to render content, but not all search engines execute JavaScript during crawling, and they may see empty content on your page. This inadvertently hurts the Search Engine Optimization (SEO) of your app. However, most of the time, when you are building apps, SEO is not the most important factor, as not all the content needs to be indexable by search engines. To overcome this, you can either server-side render your app or use services such as [Prerender](https://prerender.io/) to "render your javascript in a browser, save the static HTML, and return that to the crawlers".

###### References

* <https://github.com/grab/front-end-guide#single-page-apps-spas>
* <http://stackoverflow.com/questions/21862054/single-page-app-advantages-and-disadvantages>
* <http://blog.isquaredsoftware.com/presentations/2016-10-revolution-of-web-dev/>
* <https://medium.freecodecamp.com/heres-why-client-side-rendering-won-46a349fadb52>

### What is the extent of your experience with Promises and/or their polyfills?

Possess working knowledge of it. A promise is an object that may produce a single value some time in the future: either a resolved value, or a reason that it's not resolved (e.g., a network error occurred). A promise may be in one of 3 possible states: fulfilled, rejected, or pending. Promise users can attach callbacks to handle the fulfilled value or the reason for rejection.

Some common polyfills are `$.deferred`, Q and Bluebird but not all of them comply to the specification. ES2015 supports Promises out of the box and polyfills are typically not needed these days.

###### References

* <https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-promise-27fc71e77261>

### What are the pros and cons of using Promises instead of callbacks?

**Pros**

* Avoid callback hell which can be unreadable.
* Makes it easy to write sequential asynchronous code that is readable with `.then()`.
* Makes it easy to write parallel asynchronous code with `Promise.all()`.

**Cons**

* Slightly more complex code (debatable).
* In older browsers where ES2015 is not supported, you need to load a polyfill in order to use it.

### What are some of the advantages/disadvantages of writing JavaScript code in a language that compiles to JavaScript?

Some examples of languages that compile to JavaScript include CoffeeScript, Elm, ClojureScript, PureScript and TypeScript.

Advantages:

* Fixes some of the longstanding problems in JavaScript and discourages JavaScript anti-patterns.
* Enables you to write shorter code, by providing some syntactic sugar on top of JavaScript, which I think ES5 lacks, but ES2015 is awesome.
* Static types are awesome (in the case of TypeScript) for large projects that need to be maintained over time.

Disadvantages:

* Require a build/compile process as browsers only run JavaScript and your code will need to be compiled into JavaScript before being served to browsers.
* Debugging can be a pain if your source maps do not map nicely to your pre-compiled source.
* Most developers are not familiar with these languages and will need to learn it. There's a ramp up cost involved for your team if you use it for your projects.
* Smaller community (depends on the language), which means resources, tutorials, libraries and tooling would be harder to find.
* IDE/editor support might be lacking.
* These languages will always be behind the latest JavaScript standard.
* Developers should be cognizant of what their code is being compiled to — because that is what would actually be running, and that is what matters in the end.

Practically, ES2015 has vastly improved JavaScript and made it much nicer to write. I don't really see the need for CoffeeScript these days.

###### References

* <https://softwareengineering.stackexchange.com/questions/72569/what-are-the-pros-and-cons-of-coffeescript>

### What tools and techniques do you use for debugging JavaScript code?

* React and Redux
  * [React Devtools](https://github.com/facebook/react-devtools)
  * [Redux Devtools](https://github.com/gaearon/redux-devtools)
* JavaScript
  * [Chrome Devtools](https://hackernoon.com/twelve-fancy-chrome-devtools-tips-dc1e39d10d9d)
  * `debugger` statement
  * Good old `console.log` debugging

###### References

* <https://hackernoon.com/twelve-fancy-chrome-devtools-tips-dc1e39d10d9d>
* <https://raygun.com/blog/javascript-debugging/>

### What language constructions do you use for iterating over object properties and array items?

For objects:

* `for` loops - `for (var property in obj) { console.log(property); }`. However, this will also iterate through its inherited properties, and you will add an `obj.hasOwnProperty(property)` check before using it.
* `Object.keys()` - `Object.keys(obj).forEach(function (property) { ... })`. `Object.keys()` is a static method that will lists all enumerable properties of the object that you pass it.
* `Object.getOwnPropertyNames()` - `Object.getOwnPropertyNames(obj).forEach(function (property) { ... })`. `Object.getOwnPropertyNames()` is a static method that will lists all enumerable and non-enumerable properties of the object that you pass it.

For arrays:

* `for` loops - `for (var i = 0; i < arr.length; i++)`. The common pitfall here is that `var` is in the function scope and not the block scope and most of the time you would want block scoped iterator variable. ES2015 introduces `let` which has block scope and it is recommended to use that instead. So this becomes: `for (let i = 0; i < arr.length; i++)`.
* `forEach` - `arr.forEach(function (el, index) { ... })`. This construct can be more convenient at times because you do not have to use the `index` if all you need is the array elements. There are also the `every` and `some` methods which will allow you to terminate the iteration early.

Most of the time, I would prefer the `.forEach` method, but it really depends on what you are trying to do. `for` loops allow more flexibility, such as prematurely terminate the loop using `break` or incrementing the iterator more than once per loop.

### Explain the difference between mutable and immutable objects.

* What is an example of an immutable object in JavaScript?
* What are the pros and cons of immutability?
* How can you achieve immutability in your own code?

TODO

### Explain the difference between synchronous and asynchronous functions.

Synchronous functions are blocking while asynchronous functions are not. In synchronous functions, statements complete before the next statement is run. In this case the program is evaluated exactly in order of the statements and execution of the program is paused if one of the statements take a very long time.

Asynchronous functions usually accept a callback as a parameter and execution continues on the next line immediately after the asynchronous function is invoked. The callback is only invoked when the asynchronous operation is complete and the call stack is empty. Heavy duty operations such as loading data from a web server or querying a database should be done asynchronously so that the main thread can continue executing other operations instead of blocking until that long operation to complete (in the case of browsers, the UI will freeze).

### What is event loop? What is the difference between call stack and task queue?

The event loop is a single-threaded loop that monitors the call stack and checks if there is any work to be done in the task queue. If the call stack is empty and there are callback functions in the task queue, a function is dequeued and pushed onto the call stack to be executed.

If you haven't already checked out Philip Robert's [talk on the Event Loop](https://2014.jsconf.eu/speakers/philip-roberts-what-the-heck-is-the-event-loop-anyway.html), you should. It is one of the most viewed videos on JavaScript.

###### References

* <https://2014.jsconf.eu/speakers/philip-roberts-what-the-heck-is-the-event-loop-anyway.html>
* <http://theproactiveprogrammer.com/javascript/the-javascript-event-loop-a-stack-and-a-queue/>

### Explain the differences on the usage of `foo` between `function foo() {}` and `var foo = function() {}`

The former is a function declaration while the latter is a function expression. The key difference is that function declarations have its body hoisted but the bodies of function expressions are not (they have the same hoisting behaviour as variables). For more explanation on hoisting, refer to the question above on hoisting. If you try to invoke a function expression before it is defined, you will get an `Uncaught TypeError: XXX is not a function` error.

**Function Declaration**

```js
foo(); // 'FOOOOO'
function foo() {
  console.log('FOOOOO');
}
```

**Function Expression**

```js
foo(); // Uncaught TypeError: foo is not a function
var foo = function() {
  console.log('FOOOOO');
};
```

###### References

* <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/function>

### What are the differences between variables created using `let`, `var` or `const`?

Variables declared using the `var` keyword are scoped to the function in which they are created, or if created outside of any function, to the global object. `let` and `const` are _block scoped_, meaning they are only accessible within the nearest set of curly braces (function, if-else block, or for-loop).

```js
function foo() {
  // All variables are accessible within functions
  var bar = 'bar';
  let baz = 'baz';
  const qux = 'qux';

  console.log(bar); // "bar"
  console.log(baz); // "baz"
  console.log(qux); // "qux"
}

console.log(bar); // ReferenceError: bar is not defined
console.log(baz); // ReferenceError: baz is not defined
console.log(qux); // ReferenceError: qux is not defined
```

```js
if (true) {
  var bar = 'bar';
  let baz = 'baz';
  const qux = 'qux';
}

// var declared variables are accessible anywhere in the function scope
console.log(bar); // "bar"
// let and const defined variables are not accessible outside of the block they were defined in
console.log(baz); // ReferenceError: baz is not defined
console.log(qux); // ReferenceError: qux is not defined
```

`var` allows variables to be hoisted, meaning they can be referenced in code before they are declared. `let` and `const` will not allow this, instead throwing an error.

```js
console.log(foo); // undefined

var foo = 'foo';

console.log(baz); // ReferenceError: can't access lexical declaration `baz' before initialization

let baz = 'baz';

console.log(bar); // ReferenceError: can't access lexical declaration `bar' before initialization

const bar = 'bar';
```

Redeclaring a variable with `var` will not throw an error, but 'let' and 'const' will.

```js
var foo = 'foo';
var foo = 'bar';
console.log(foo); // "bar"

let baz = 'baz';
let baz = 'qux'; // SyntaxError: redeclaration of let baz
```

`let` and `const` differ in that `let` allows reassigning the variable's value while `const` does not.

```js
// this is fine
let foo = 'foo';
foo = 'bar';

// this causes an exception
const baz = 'baz';
baz = 'qux';
```

###### References

* <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/let>
* <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/var>
* <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/const>

### What are the differences between ES6 class and ES5 function constructors?

TODO

### Can you offer a use case for the new arrow => function syntax? How does this new syntax differ from other functions?

TODO

### What advantage is there for using the arrow syntax for a method in a constructor?

TODO

### What is the definition of a higher-order function?

A higher-order function is any function that takes another function as a parameter, which it uses to operate on some data, or returns a function as a result. Higher-order functions are meant to abstract some operation that is performed repeatedly. The classic example of this is `map`, which takes an array and a function as arguments. `map` then uses this function to transform each item in the array, returning a new array with the transformed data. Other popular examples in JavaScript are `forEach`, `filter`, and `reduce`. A higher-order function doesn't just need to be manipulating arrays as there are many use cases for returning a function from another function. `Array.prototype.bind` is one such example in JavaScript.

##### Map

Let say we have an array of names which we need to transform each element to uppercase string.

`const names = ['irish', 'daisy', 'anna']`;

The imperative way will be like:

```js
const transformNamesToUppercase = names => {
  const results = [];
  for (let i = 0; i < names.length; i++) {
    results.push(names[i].toUpperCase());
  }
  return results;
};
transformNamesToUppercase(names); // ['IRISH', 'DAISY', 'ANNA']
```

Use `.map(transformerFn)` to become more simplified, easy to reason about and declarative.

```js
const transformNamesToUppercase = names =>
  names.map(name => name.toUpperCase());
transformNamesToUppercase(names); // ['IRISH', 'DAISY', 'ANNA']
```

##### Filter

We want to filter all names which their initial character starts with **i**.

The imperative way will be like:

```js
const filterNames = names => {
  const results = [];
  for (let i = 0; i < names.length; i++) {
    const name = names[i];
    if (name.startsWith('i')) {
      results.push(name);
    }
  }
  return results;
};
filterNames(names); // ['IRISH']
```

Instead using `for loop`, use `.filter(predicateFn)` to look more declarative.

```js
const filterNames = names => names.filter(name => name.startsWith('i'));
filterNames(names); // ['IRISH']
```

##### Reduce

Sum all the values of an array

`const numbers = [1,2,3,4,5];`

Imperative way:

```js
const sumOfNumbers = numbers => {
  let sum = 0;
  for (let i = 0; i < numbers.length; i++) {
    sum += numbers[i];
  }
  return sum;
};
sumOfNumbers(numbers); // 15
```

More declarative using `.reduce(reducerFn)`:

```js
const sumOfNumbers = numbers =>
  numbers.reduce((total, number) => (total += number), 0);
sumOfNumbers(numbers); // 15
```

Use **higher-order function** to make your code easy to reason about and improve the quality of your code. This became your code more **declarative** instead imperative, say **what you want done** not **how to do it**.

###### References

* <https://medium.com/javascript-scene/higher-order-functions-composing-software-5365cf2cbe99>
* <https://hackernoon.com/effective-functional-javascript-first-class-and-higher-order-functions-713fde8df50a>
* <https://eloquentjavascript.net/05_higher_order.html>

### Can you give an example for destructuring an object or an array?

TODO

### ES6 Template Literals offer a lot of flexibility in generating strings, can you give an example?

TODO

### Can you give an example of a curry function and why this syntax offers an advantage?

Currying is a pattern where a function with more than one parameter is broken into multiple functions that, when called in series, will accumulate all of the required parameters one at a time. This technique can be useful for making code written in a functional style easier to read and compose. It's important to note that for a function to be curried, it needs to start out as one function, then broken out into a sequence of functions that each take one parameter.

```js
function curry(fn) {
  if (fn.length === 0) {
    return fn;
  }

  function _curried(depth, args) {
    return function(newArgument) {
      if (depth - 1 === 0) {
        return fn(...args, newArgument);
      }
      return _curried(depth - 1, [...args, newArgument]);
    };
  }

  return _curried(fn.length, []);
}

function add(a, b) {
  return a + b;
}

var curriedAdd = curry(add);
var addFive = curriedAdd(5);

var result = [0, 1, 2, 3, 4, 5].map(addFive); // [5, 6, 7, 8, 9, 10]
```

###### References

* <https://hackernoon.com/currying-in-js-d9ddc64f162e>

### What are the benefits of using spread syntax and how is it different from rest syntax?

ES6's spread syntax is very useful when coding in a functional paradigm as we can easily create copies of arrays or objects without resorting to `Object.create`, `slice`, or a library function. This language feature gets a lot of use in projects using Redux or RX.js.

```js
function putDookieInAnyArray(arr) {
  return [...arr, 'dookie'];
}

var result = putDookieInAnyArray(['I', 'really', "don't", 'like']); // ["I", "really", "don't", "like", "dookie"]

var person = {
  name: 'Todd',
  age: 29
};

var copyOfTodd = { ...person };
```

ES6's rest syntax offers a shorthand for including an arbitrary number of arguments to be passed to a function. It is like an inverse of the spread syntax, taking data and stuffing it into an array rather than upacking an array of data, but it only works in function arguments.

```js
function addFiveToABunchOfNumbers(...numbers) {
  return numbers.map(x => x + 5);
}

var result = addFiveToABunchOfNumbers(4, 5, 6, 7, 8, 9, 10); // [9, 10, 11, 12, 13, 14, 15]
```

###### References

* <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax>
* <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/rest_parameters>

### How can you share code between files?

TODO

### Why you might want to create static class members?

TODO

### Other Answers

* <http://flowerszhong.github.io/2013/11/20/javascript-questions.html>

## Related

If you are interested in how data structures are implemented, check out [Lago](https://github.com/yangshun/lago), a Data Structures and Algorithms library for JavaScript. It is pretty much still WIP but I intend to make it into a library that is able to be used in production and also a reference resource for revising Data Structures and Algorithms.

## Contributing

Feel free to make pull requests to correct any mistakes in the answers or suggest new questions.
