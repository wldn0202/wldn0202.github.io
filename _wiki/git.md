---
layout: wiki
title: github
categories: Git
description: Github upload 방법
keywords: Git
---

## git 명령어를 이용하는 방법
***
1.  깃 저장소를 초기화한다. 이미 연결하려고 하는 깃repo가 있다면 두 번째 명령어를 실행한다.
~~~
git init
git clone https://github.com/GND123/gnd123.github.io.git
~~~

2. 깃 local에 변경할 파일을 추가한다.
~~~
git add fileName
~~~

3. git local에 커밋한다.
~~~
git commit -m "commit-message"
~~~

4. git init을 썻을 경우 github repo와 연결시킨다.
~~~
git remote add origin https://github.com/GND123/gnd123.github.io.git
~~~

5. github에 push한다.
~~~
git push origin master
~~~

## eclipse를 이용하는 방법
***
1. eclipse를 다운로드 한다.

2. window - perspective - open Perspective - other .. - Git 추가

3. 거기서 repo를 잘 추가하도록 한다

4. synchronize -- 비교하기 용이

5. 이게 사진이 있어야 되는데 사진 넣는 법을 몰라서 업데이트 할게요
그냥 인터넷 쳐도 잘 나옴

6. git을 gui로 이용할 수 있다!

## git cherry-pick 커밋 한번에 여러개 찍기
**
1. .. 명령을 이용한다.

2. 앞에 나오는 커밋이 더 이전의 커밋이어야한다.

3. ex) git cherry-pick br1~5..br1

4. 이렇게 찍으면 br1 브랜치의 앞 5개 커밋이 cherry-pick 된다.
