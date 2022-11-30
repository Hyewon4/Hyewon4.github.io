---
layout: post
title: "How To Solve Errors"
---

## jekyll serve
<br/>
**Bundler::GemNotFound오류**

* bundle install

**사용자 이름이 한글일 때**

* 사용자 이름과 사용자 폴더의 이름 변경

## git add
<br/>
**does not have a commit chekced out**

* .git파일이 중복되었을 때
* 숨김 파일 보기를 체크한 후 중복된 .git 파일 제거

**LF will be replaced by CRLF the next time Git touches it**

* git config --global core.autocrlf true

## git push
<br/>
**fatal: 'origin' does not appear to be a git repository**
**fatal: Could not read from remote repository**

* 원격 저장소가 연결되지 않았을 때 발생
* git remote add origin [git 저장소 url]