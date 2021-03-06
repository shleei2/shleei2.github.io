---
layout: post
title: "[회고]인생리뷰 - 20대의 짱을 먹었다."
subtitle: "retrospect 2018"
categories: review
tags: event
comments: true
---

글을 쓴지 얼마만일까. 내 기억으로는 1년 반쯤 된 것 같다.

그 사이 많은 변화가 있었다. 회고를 남겨본 적이 없으니 내 소개부터 해보자.

## 박민

2019년 20대의 짱을 먹었다. 개발을 주로한다. 풀싸이클 개발자이며, 풀스택 개발자이다. 많은 풀스택 개발자들이 그러겠지만 모든걸 다 잘하지는 않는다.

19살에 문득 내가 세상을 너무 재미없게 산다는 생각이 들어 하고싶은것들을 리스트업한다. 리스트업된 내용은 8가지.

> 미술, 음악, 건축, 한의학, 연기, 모델, 개발, 선생님

그 리스트를 보면서 나는 나와 작은 게임을 하게 되는데 게임내용은 다음과 같다. `전부 하나씩 해보며 돈을 한푼이라도 벌어보기. 그리고 그것들 중에 가장 재밌는 것으로 진로를 정하기`

돈을 번다는건 누군가 나의 그 재능을 돈을 주고서라도 사고싶어한다는 반증이라고 생각했고, 그 때까지는 해야 중도포기가 아니라고 생각했다. 결과적으로는 3가지를 제외한 5가지로 돈을 벌어봤다.

근데 이 작은 게임이 끝나고 아주 큰 문제가 생겼는데. 그 문제는 정말 말도 안되게도 전부 `너무 재밌었다`는 것이다.

그렇게 대학에서 2년을 방황하다 공군 중앙전산소에서 프로그램 작성병으로 2년간 복무하게된다(중전소 714기 만세). 사연은 복잡하지만 나는 군대를 경험으로 개발자를 업으로 삼게 되었다.

## 개발자

제대하고 스타트업과 사이드프로젝트 등을 여러개 하게된다. 엎어진것도 많고, 완성해도 빛 발하지 못한 것들도 많지만. 2016년 3월 `리액트`를 만나면서 내 인생은 또 한번 달라진다. 

여태까지는 스프링을 기반한 자바 웹 프로그래밍이나 자바를 이용한 안드로이드를 개발해왔는데, 리액트를 만나면서 개발의 신세계를 맛봤다.

create-react-app 과 자바스크립트, css만으로 엄청난 속도로 개발을 할 수 있었다(이게 착각이라는건 머지않아 알게되었다.) 2016년 3월부터 리액트와 리액트 네이티브로 개발을 시작했고, 정말 즐거운 경험으로 당시에 하던 스타트업의 프로덕트를 개발했다. 

## 리액트

근데 리액트가 쉽다는건 정말 착각이었던게 뭐였냐면, 나는 브라우저나 웹, 앱서비스에 대한 이해도가 그렇게 높은 편이 아니었다. 거기다 백엔드는 미티어를 사용했는데, 개발에 대해서 별로 잘 알지도 못하는 놈이 프론트, 백을 다 하려니 머리 터지고. 심지어 자바스크립트도 자바스크립트라기보단 JQuery를 더 많이 다뤘다고 해야할까. 여튼 익숙하지 않은 상태였다.

그 상태에서 헬은 리액트의 상태관리. 리액트는 단방향으로 데이터를 전달한다. 쉽게 이야기하면 부모가 자식에게만 데이터를 전달한다. 이게 규모가 커지면, state와 prop만으로 다루기 엄청나게 어려운 상황에 도달하게 된다.

그래서 상태관리도구. 당시에는 Redux(이거 내 취향아님)라는걸 사용하게 되는데 이게 쉽게 이야기하면 전역 상태관리를 도와준다. 근데 그 과정에서 코드를 꽤 많이 작성하게 된다. 내가 불리언 하나를 변경하려고 몇개의 파일과 20줄정도 되는 코드를 작성해야 되는 것이다. (MobX 만세)

그 외에도 라우팅, 생명주기, HOC, 컴포넌트화, 디렉토리구조 등등 날 괴롭히는게 아주 많았고 재밌었지만 거의 1년동안 키보드보다 `머리털`을 붙잡고 있는 시간이 더 길었을 수도 있었겠다는 생각이든다.

## 백엔드

처음 프론트와 분리된 백엔드를 내가 손수 만든건 미티어를 이용해서였다. 미티어는 프론트와 백엔드를 한데 묶어놓은 프레임워크인데(나는 여기서 백엔드로써만 사용했다), 디폴트 디비가 몽고디비이고, 사용하기 쉽고 ws을 사용해서 재밌는 경험을 할 수있다. 한번쯤 해보는건 추천. 이건 내가 만들고 실제프로젝트에서도 쓰던 [깃헙레포](https://github.com/isme2n/react-redux-material-meteor). 2년이나 지났지만 참고정도는 되지 않을까.

그 외에도 익스프레스, 코아 등등 노드 기반의 백엔드를 몇개 만들어서 사용해봤다. 루비온레일즈도 해봤는데 너무 대규모 프로젝트였고, 아주 힘들었던 기억이 지배적이다.

실제 프로덕트에서 쓰인건 미티어, 코아, 루비온레일즈.

## 블로그

블로그는 네이버블로그, 티스토리, 지금의 깃헙블로그까지 3가지를 해봤다. 2015년부터 한것 같은데, 2017년 9월쯤부터 지금까지 약 1년 3개월은 블로깅을 하지 않았다.

1년 3개월이나 안했다고 생각해보니 충격적이다. 그래도 꽤 꾸준히 하던 편이었는데. 사는게 뭔지.

2012년 군대 입대날 시작한 일기부터 하면 2017년까지 5년간 거의 매일 조금씩 글을 썼던것 같다.

2019년을 어떻게 보낼지는 아직 플래닝하지 않았는데, `블로깅이나 유튜브 중 하나는 다시 해볼 생각`이다.

블로그 테마는 2017년에 맘에 들어서 테마를 받고 거의 1주일간 뜯어고쳐서 만든 테마이다. 내 블로그의 아주 많은 유입은 대부분 블로그 테마인데... 나도 베낀거다.

자유롭게 쓰세요.

## 강의 및 발표

2017년 5월 [리액트 강의](https://www.youtube.com/watch?v=r9fbXIaNxck&list=PLBrx45N7b6tkdisu8ZhKs02tEf5wDuk2W&index=1)는 태어나서 처음으로 공개적인 곳에 올린 강의였다. 그 뒤 여름에 GDG 캠퍼스에서 [자바스크립트](https://www.slideshare.net/MinPark48/ss-79004233)를 발표했다. 

2018년에는  

- 인프런에서 [블록체인강의](https://www.inflearn.com/course/%EB%B8%94%EB%A1%9D%EC%B2%B4%EC%9D%B8-blockchain/)
- [GDG 웹테크에서 주니어를 위한 커리어 개발](https://www.slideshare.net/MinPark48/devfest-webtech18min)
- 동덕여대에서 대학생을위한 블록체인 개발
- 한국외대에서 대학생을위한 블록체인

이렇게 강의와 발표를 한것 같다.

2019년에는 1월 7,8,9 동덕여대에서 `블록체인 개발`에 대한 강의를 하고, 추후 `재직자를 위한 강의`를 예정하고있다.

## 블록체인

나에게 2018년은 블록체인을 빼고 이야기 할 수가 없다. 2018년 1월 1일 `포장도 뜯지않은 17년형 맥북(현금박치기로 샀다)`을 들고 도쿄로 떠난 그 날부터 지금까지 블록체인과 관련된 일을 하고있다. 

사실은 블록체인쪽에서 일한건 2017년 9월부터였지만. 개념이 재밌고 일을 더 잘하고 싶어서 공부하던게 거의 내 모든 업의 중심이 되었다.

앞으로도 한동안은 블록체인과 함께 하지 않을까 싶다.

## 리모트워크

원격근무라고도 하는데, 내가 리모트워크를 원하게된건 대부분의 회사가 강남에 있고 나는 부천이라는 곳에 살았기 때문이다. 출퇴근에 걸리는 시간동안 개발을 하면 짧게는 3시간 길게는 하루에 4시간을 더 일할 수 있었다. 2017년 10월부터 리모트워크를 할 수 있게 됬고, 현재 다니는 회사도 리모트 워크를 하고있다.

리모트워크의 `장점은 시간과 커뮤니케이션이고, 단점은 커뮤니케이션과 시간`이다. 나는 아침에 일어나서 눈 뜨자마자 회사 데일리에 어제 무엇을했고 오늘 무엇을 할 것인지 알린다. 씨리얼이나 식사대용식을 먹으며 일을 하다가 점심시간이 되면 밥을 먹고 샤워를 하고 카페에 간다. 이게 일반적이지만 조금 틀어지면 바로 문제가 생긴다.

장점부터 이야기하자면, 출퇴근 시간을 줄이고 더 일할 수 있다. 그리고 시간을 어느 정도 조절해서 일을 할 수 있다. 오전에 못했다면 저녁에 좀 더 하면 된다. 커뮤니케이션을 글을 기반으로하기 때문에 검색이 용이하고, 좀 더 명확하게 전달하려고 노력한다.

단점은 그냥 한두마디면 될 일을 글로 이야기하려면 생각보다 길어지는 경우가 많아진다. 이런 경우는 오히려 좋은 경우인게, 시간이 좀 더 들지만 더 명확하게 의도를 전달할 수 있다. 진짜 문제는 글로 하다 `생략`되어버리는 경우도 생각보다 많다. 그럼 생략된 부분을 찾기 위해 서로 몇번의 커뮤니케이션이 더 왔다갔다하는 경우가 더러있다. 

이런 경우는 꽤나 문제이지만 리모트워크를 한다면 해결해야하는 숙명인 것 같다. 또 하나의 단점은 일상과 업무가 흐릿하다는 거다. 업무시간에 유튜브를 보고 `음.. 저녁에 더 하지 뭐.`와 같은 상황도 더러일어난다.

나는 집중력이 좋은편이라고 생각했는데, `엄청난 관리`에서 나온 집중력이라는걸 깨달았다. 나는 집중력을 잃을까봐 티비도 음악도 거의 보고 듣지 않는다. 일할때는 휴대폰도 멀리하고 연락이 늦어 친구들한테 혼나는 편이다. 근데 우리동생과 어머니가 한집에 사니 정신 없어지는 일이 아주 많아졌다. 

빠른시일내로 다시 독립을 할 예정이다.

## 여행

나는 운이 좋게도 2년마다 해외에 너무 짧지않은 시간동안 체류할 수 있는 기회들이 있었다.

2012년에는 `인도`에 3주정도있었고, 2016년에는 `연변`에 3주정도, 2018년에는 `일본`에 2주정도 있었다.(2014년엔 군대에 있었다.)

나는 이 경험들이 아주 많은 도움이 됬다. 인도에서의 경험으로 많은 영감을 얻고 잘 안풀리던 디자이너로써의 일을 풀어냈고, 연변에서 좋은 사람들과 재밌는 경험들을 많이 했다. 일본에서도 일본인들과, 그리고 동료들과 즐거운 추억을 많이 만들고왔다.

그 외에도 친구들과 국내여행, 해외여행 할 것없이 즐거운 기억들 투성이다. 2018년에는 처음으로 `혼자 여행`을 떠나봤다. 오사카에 일주일정도 머무르는 여정이었다. 좀 더 오래 있으려고 했는데 가장 친한 친구의 결혼식이 있어 예정보다 빠르게 돌아왔다.

난 부천에서도. 서울에서도. 부천과 서울을 떠난 어느곳에서도 너무나도 행복한 삶을 살고있다.

## 외국어

나는 외국어를 좋아하는데, 아주 못한다. 곤방와. 현재 관심있는 언어는 영어, 일어, 중국어이다. 아마 유튜브를 다시 시작하게 된다면 언어를 공부하는 컨텐츠가 되지 않을까 싶다.(아무도 안보겠네;;) 2019년에는 꼭 `영어와 일어`를 어느정도 구사해서 친구를 사귀고 이야기할 수 있게 되었으면 좋겠다.

## 팀장

나는 보통 스타트업에서 일을 해서 프로젝트를 리드하는 역할을 많이 했는데 고작해봐야 개발자가 한두명이어서 어쩔 수 없던 일이었다. 3명이 넘어가는 그룹에서 리드를 한건 대학교때 학생회장을 한 뒤론 처음인거 같다.

팀장의 역할을 맡게 된 후 내게 가장 감사했던건 내가 `귀기울일줄 알며, 풀스택, 풀싸이클 개발자`라는 것이었다. 나는 프론트부터 백엔드, 운영까지 다 어느정도의 지식이 있는 상태였고, 다른팀원들의 지식과 의견을 들었을때 그게 미칠 영향력을 판단하고 함께 고려할 수 있었다. 이건 내가 프론트만 했거나, 백엔드만 했다면 조금은 어려웠을 법한 일이었을 수도 있다고 생각한다.

무언가 하나를 딥따 잘하는 건 멋있지만, 잘하는 다른 사람들을 융화시키는 삶도 꽤 괜찮은 삶일 수 있겠다는 것을 느꼈다. 

당연히 자신의 몫을 해내는 팀구성원들에게도 감사하다.

## 책

나는 책읽는걸 꽤 좋아하는 편이다. 요즘엔 일반 문학은 거의 못읽고 있지만. 다들 그렇듯 군대에 있을때는 2년간 200권 정도 되는 책을 읽었다. 

책을 읽는 다는건 말그대로 읽는게 다가 아니라 `사유`라고 생각한다. 그런의미에서 개인적으로 속독은 써먹고 싶을 때 써먹는 스킬정도라고 생각하지 책을 읽고싶을때는 별로 좋지 않은 기술이라고 생각한다. 책을 읽다 어떤 문장에서 `나만의 세계 또는 작가와 나의 세계`에 빠져서 생각하는것이 책의 묘미아닐까. 

최근엔 개발서적에 치여 많은 책을 못읽었지만 2019년에는 좀 더 다양한 책을 읽어보려한다.

## 마무리

내 20대는 결국 개발이었다. 개발을 하다가 잠을 못자기도하고, 만들고 싶은것, 해내고싶은것들이 많아 많은 밤을 지새웠어도, 나는 개발을 하며 살아왔다. 개발을 조금씩 잘하게 되면서도 뿌듯하고, 앞으로 갈길이 멀었다는것에 아득하기도, 기쁘기도 하다. 난 `끊임없이 배우고, 재밌는 일들을 하면서` 행복하게 살거다. 
