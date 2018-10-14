---
layout: post
title:  git 저장소 옮기기
date:   2018-10-14 14:44:46
categories: git
tags: git github
---

* content
{:toc}

 학교 수업에서 gitlab 서버를 이용해서 과제를 관리한다. 지금까지 올린 gitlab의 git을 github에 그대로 옮기려 한다. 직접 옮기기에는 너무 무식해보여서 일괄적으로 옮긴 방법을 찾아보았다.

---
# git bash 이용
---

`git clone --mirror : to clone every references(commit, tags, branches)`
`git push --mirror : to push everything`

```
git clone --mirror https://bitbucket.org/exampleuser/repository-to-mirror.git //원본 git clone

cd repository-to-mirror.git //clone한 git 경로 지정

git remote set-url --push origin https://github.com/exampleuser/mirrored //붙여넣을 git 경로 지정

git push --mirror //git push
```

출처: [GOOD to GREAT](http://goodtogreate.tistory.com/entry/%EC%A0%80%EC%9E%A5%EC%86%8C-%ED%86%B5%EC%B1%84%EB%A1%9C-%EB%B3%B5%EC%82%AC%ED%95%98%EA%B8%B0-bitbucket-to-github)

원리는 원본에서 모든 기록을 전부 clone한 다음에 원격 경로 지정해주고 push하는 것이다.

근데 다 옮기고 보니까 처음부터 github에서 repository 팔때 옮기는 옵션이 있다더라..

뻘짓하지 말고 제공해주는 옵션을 쓰자
