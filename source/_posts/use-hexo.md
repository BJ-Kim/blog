---
title: HEXO 를 이용한 블로그!!!
date: 2017-11-12 20:16:36
tags:
  - blog
  - hexo
categories:
  - blog
---

# hexo 설치방법!!

``` bash
$ npm install -g hexo-cli
```
명령어로 hexo 설치후


``` bash
$ hexo init 블로그명
$ cd 블로그명
$ npm install
```
으로 hexo 블로그를 초기화 시키고 npm install을 해준다.

이후 github repository에 등록해주면 된다.

(github repoistory 등록할때 repository 명을 본인 github 계정명으로 해야한다.)

# 새로운 포스트 등록하는 방법!!

``` bash
$ hexo new post [post_name]
```

명령어로 새로 포스트 할 이름을 입력한다

source 밑에  _posts  폴더를 보면
위에입력한 포스트 명으로 markdown 파일이 생성되게 된다.



# 포스트 작성후 GITHUB에 배포하는 방법!!

``` bash
$ hexo generate
```
명령어로 리소스를 생성한다
이후 "hexo deploy" 명령어로 배포를 진행한다.

(_config.yml 파일에 지정한 git 옵션에 적용받는다.)
("hexo deploy --generate" 명령으로 해도 된다)


# 로컬에서 포스팅 테스트 하는 방법!!!

``` bash
$ hexo server
```
커맨드를 이용하여 로컬에서 서버를 구동하는 것이 가능하다.

http://localhost:4000 으로 접속하면 블로그 접속이 가능하다.
