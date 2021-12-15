---
layout: post
title:  "노마드코더 - Zoom 클론코딩"
date:   2021-11-10 21:03:36 +0530
categories: NodeJS
---

**프로젝트 생성**

```shell
npm init -y
```

```text
Wrote to /Users/e/Documents/project/2021/zoom/package.json:

{
  "name": "zoom",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "keywords": [],
  "author": "",
  "license": "ISC"
}


```



**package.json 정리**

```json
{
  "name": "zoom",
  "version": "1.0.0",
  "description": "Zoom Clone using WebRTC and Websockets",
  "license": "MIT"
}
```



**README.md 생성**

```shell
touch README.md
```



**Nodemon 설치**

```shell
npm i nodemon -D
```

코드 변경 시 서버 자동 재시작



**바벨 설치**

```shell
npm i @babel/core @babel/cli @babel/node @babel/preset-env -D
```



