---
category1: 소화
created_dtm: 2026-01-21
template_version: v20260117-001
categories:
  - configuration
tags:
  - 참고형정보
  - tsconfig
  - module
  - moduleResolution
  - publish-blog
title: tsconfig.json > module
date: 2025-09-18T15:40:59.640Z
lastmod: 2026-01-20T17:00:08.713Z
---
***

* note\_refs:
* refs:

***

* **TypeScript 컴파일러가** JavaScript로 변환할 때 어떤 모듈 형식으로 코드를 생성할지 결정
* **컴파일 시점**에 영향

```json
{
	"module": "esnext" | "umd" | "commonjs" | "nodenext" | "preserve" ...
}
```
