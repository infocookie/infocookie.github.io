---
layout : default
title : jekyll 정적 페이지 블로그 테스트 마크다운 글쓰기 장점
date : 2018-02-19 01:00
description : 마크다운을 이용한 정적 사이트 생성기 중 하나인 jekyll을 이용해서 블로그를 운영하게 되었습니다. Markdown의 장점과 단점에 대해서 간략하게 알아보고 제가 왜 워드프레스(Wordpress)대신 깃헙의 제킬로 오게 되었는지에 대해서 간략하게 정리해봤습니다.
---

# jekyll 블로그 정적 페이지 테스트
지금 visual studio code를 통해서 작성하고 있습니다. 마크다운으로 페이지를 작성해본 경험이 거의 없어서 인지 굉장히 어색하군요. 잘 만들어진 마크다운 포스팅들을 보면 저도 어서 익숙해져야겠다는 생각이 듭니다. 이 페이지는 그냥 막 써갈기는 거라서 읽지 않으셔도 됩니다.

***

## 마크다운 글쓰기의 장점은?
* **쉽다.**(물론 처음에 배우는데 시간이 걸리겠지만 제가 벌써 이렇게 글을 쓰는 것을 보면 배우기 배우 쉬운것이 분명합니다.)
* **간결하고 보기 좋다.**(이 부분이 제가 마크다운으로 글쓰는 것을 시작한 이유 입니다. 구조가 명확 간결해서 쓰는 사람도 글을 쓸때 생각을 정리하면서 쓰기 좋고, 읽는 사람 입장에서도 볼거 보고 넘길거 넘기고 정보를 취득하기 용이합니다.)
* **별다른 도구가 필요없다.** 몇번 글을 쓰면서 익히고 나면 **메모장**으로도 글쓰는 것이 가능합니다. 

***

## 마크다운 단점은?
* 이렇다할 표준이 정해지지 않은점인데 초보인 저로서는 아직 체감하지 못하겠습니다. 뭐 나중에 슬슬 좋아지겠죠.
* 쉽고 편하게 이미지를 올릴 수 없다는 단점이 있습니다. 하지만 마크다운으로 글을 작성하시는 분들 중 대부분이 텍스트 위주일것이고, 또 어느정도 컴퓨터를 잘 다루시는 분들일테니.. 큰 단점이 아닐수도 있겠습니다.(그래도 아쉬워요)
    * 유튜브 등 동영상 입력하실때는 그냥 소스 붙여넣기 그대로 하시면 됩니다. Image파일만 좀 더 까다로울 뿐이죠.

***

## Jekyll 블로그를 선택한 이유는?
* 깃헙(Github)에서 무료 호스팅을 이용할 수 있다. (깃허브가 5년안에 사라지진 않겠죠? ㅜㅜ)
* 새로운 것에 대한 호기심
* 워드프레스(Wordpress) 편한점
    * 코어 업데이트가 필요 없다.
        * 테마 업데이트도 할필요없다!!
    * 고로 보안 업데이트를 할 필요도 없다.
    * 그렇게 때문에 페이지를 그냥 만들어놓으면 신경쓸게 별로 없다.
    * PHP, JS(자바스크립트) 같은 요소들이 거의 없기 때문에 속도도 빠르다.
    * 용량이 적기 때문에 호스팅 비용도 적게 들어간다.
        * 각 페이지별 용량이 적기 때문에 많은 사람이 몰려도 서버에 부하가 거의 없다.

## 워드프레스와 비교해서 제킬 블로그의 단점은?
* 아무래도 접근성에 있어 불리함이 있다.(깃헙에 대한 이해도 있어야하고..)
* 간결한 반면에 기능이 없다.
* 기능을 추가하기 힘들다.
* 컨텐츠를 만들기 쉽고 편하다.

뭐 좀 불편한 단점이 있다.. 이정도.

***

## Jekyll을 시작하기 위해서 필요한 것은?
* Github 아이디를 가입하신 후 사용법을 익히면 됩니다.(사람에 따라서 하루에서 3~4일 걸릴수도..)
* 마크다운으로 글을 작성하기 위해 필요한 프로그램은 무료가 상당히 많습니다. 처음에는 연습으로 메모장을 사용하셔도 좋고.. 글작성을 쉽게 도와주는 무료 에디터들을 고르셔도 좋습니다.(Atom, 비주얼스튜디오코드 같은것 이외에도 마크다운 전용 에디터들도 꽤 있습니다.)
* 깃헙이 언제 망할지 모르잖아! 라고 생각하시는 분은 본인의 서버에 올리셔도 됩니다.
* 장기적으로 오래 하실거라면 저렴한 VPS(가상클라우드 서버)도 좋은 방법 입니다.(웹호스팅은 제가 못해서 그런지 안되더라구요.. sudo를 써야하는데..)

일단 테스트 페이지는 이정도로 마무리.
