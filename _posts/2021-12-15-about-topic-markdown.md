---
layout: post
title:  "about topic markdown !"
summary: "Getting Started postig about markdown"
author: Mun Jihwan
date: '2021-12-16 14:16:23 +0530'
category: Markdown
thumbnail: null
keywords: explain, markdown
permalink: /blog/welcome-to-devlopr-jekyll/
usemathjax: true
---

## Markdown이란?

- 일반 텍스트 기반의 경량 마크업 언어
- 특수기호와 문자를 이용한 매우 간단한 구조의 문법을 사용

  
## Markdown의 장단점

### 장점
- 간결하다.
- 별도의 도구없이 작성가능하다.
- 다양한 형태로 변환이 가능하다.
- 텍스트(Text)로 저장되기 때문에 용량이 적어 보관이 용이하다.
- 텍스트파일이기 때문에 버전관리시스템을 이용하여 변경이력을 관리할 수 있다.
- 지원하는 프로그램과 플랫폼이 다양하다.

### 단점
- 표준이 없다.
- 표준이 없기 때문에 도구에 따라서 변환방식이나 생성물이 다르다.
- 모든 HTML 마크업을 대신하지 못한다.
	
## Markdown의 사용

### 헤더의 사용
##### ```#```의 개수가 늘어날수록 글자의 크기가 작아짐
```
# This is a Biggest
## This is a middle
### This is a smallest
```
# This is a Biggest
## This is a middle
### This is a smallest


### 블럭인용 문자

```>```를 이용한다.
```
> This is markdown!!!!
>	> This is markdown!!!!
>	>	> This is markdown!!!!
```
> This is markdown!!!!
>	> This is markdown!!!!
>	>	> This is markdown!!!!
### 문자 강조

```
* Like italic*
__Bold message__
~~cancel~~
```

* *Like italic*
* __Bold message__
* ~~cancel~~
### 코드 블록 입력
###### 강의에서와는 달리 또다른 방법인 `<pre><code>{code}</code></pre>` 이용방식이 존재함
<pre>
<code>
```java
public class BootSpringBootApplication {
  public static void main(String[] args) {
    System.out.println("Hello, Honeymon");
  }
}
```
</code>
</pre>

```java
public class BootSpringBootApplication {
  public static void main(String[] args) {
    System.out.println("Hello, Honeymon");
  }
}
```

