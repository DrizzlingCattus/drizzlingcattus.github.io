---
category1: 소화
created_dtm: 2026-01-21
template_version: v20260117-001
categories:
  - configuration
tags:
  - 참고형정보
  - tsconfig
  - publish-blog
title: tsconfig.json > target
date: 2025-09-18T15:48:22.623Z
lastmod: 2026-01-20T17:00:13.045Z
---
***

* note\_refs:
* refs:

***

target은 Typescript 컴파일러 옵션으로서, 생성할 Javascript 파일의 ECMAScript 버전을 지정한다.

```typescript
// TypeScript 소스코드
const greeting = (name: string) => `Hello, ${name}!`;
class Person {
  constructor(public name: string) {}
}
```

```javascript
// target: "ES5" 컴파일 결과
var greeting = function (name) { return "Hello, " + name + "!"; };
var Person = /** @class */ (function () {
    function Person(name) {
        this.name = name;
    }
    return Person;
}());
```

```javascript
// target: "ES2018" 컴파일 결과
const greeting = (name) => `Hello, ${name}!`;
class Person {
    constructor(name) {
        this.name = name;
    }
}
```
