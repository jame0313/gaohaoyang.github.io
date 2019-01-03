---
layout: post
title:  "포스트 가이드"
date:   2018-10-14 12:16:13
categories: jekyll
tags: jekyll
mathjax: true
---
* content
{:toc}
# 헤더 양식
---
```
---
layout: post //레이아웃 칸, 웬만하면 post 쓰면 된다.
title:  제목
date:   yyyy-mm-dd hh:mm:ss
categories: 카테고리로 카테고리에서 분류할 때 쓴다.
tags: 태그로 태그로 분류할 때 쓴다.
excerpt: 요약, 미리보기 볼때 이 글만 보인다.
mathjax: true or false //수식 쓰면 true 적으면 된다.
---
```

# 뒤에 써야할 것
---
```
* content
{:toc}
```
내가 fork한 블로그에서 만든 기능 중에 우측 메뉴가 있다.  
보면 "헤더 양식"부터 여러 링크가 있는 것을 볼 수 있다.  
그 메뉴에 이 글의 헤더 목록을 추가할지의 여부를 toc attribute의 유무로 따진다.  
그래서 임시 list 요소 하나 넣고 거기에 toc attribute를 붙인다.  
요소 text가 content가 아니여도 된다.

# jekyll 문법
---
`kramdown`이다.


[kramdown](https://kramdown.gettalong.org/index.html)


이후에 문법 정리한 거 가져올 것이다.
