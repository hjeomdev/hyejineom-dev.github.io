---
layout: post
title: JSP
author: Hyejin Eom
tag :
- WebProgramming
- JSP
date: 2020-12-27
---
JSP (Java Server Page)

JSP 개발환경
- 자바 개발환경: JDK [^JDK]
- JSP 운영환경(서블릿 컨테이너): 아파치 톰캣
- IDE: 인텔리제이, 이클립스

[^JDK]: Java Development Kit

Java SE 
Java EE

JRE


Maven
- 역할: 필요한 라이브러리를 pom.xml에 작성하면 자동으로 네트워크를 통해 다운 받아줌
- Build: 일련의 단계Phase에서 연계된 Goal을 실행하는 과정
- LifeCycle: 빌드 순서

- 표준 LifeCycle
    1. Clean : 빌드 시 생성되었던 Output을 지워준다.
    2. Default(Build) : 일반적인 빌드 프로세스를 위한 모델이다.
    3. Site : 프로젝트 문서와 사이트 작성을 수행한다.

