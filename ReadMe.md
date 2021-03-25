# This page is a summary of html and css studies!

This repository includes Html & CSS

This is made easy to understand them for beginner like me.

<br>

I got the basic course at 

<a href="https://opentutorials.org/course/2039">Life coding</a>


<a href="https://www.youtube.com/watch?v=wcsVjmHrUQg&list=PLv2d7VI9OotTVOL4QmPfvJWPJvkmv6h-2">Dream Coding</a>

I recommend the website for beginner because they tell you the basics in an <b>easy-to-understand</b> manner.


****

## 🎁 HTML과 tag

<br><br>
이 글을 읽는 사람은 나와 같이 html과 CSS가 아예 생소한 사람일테다.
<br><br>
천천히 이 글을 읽다 보면 그래도 나름… 개념이 잡히지 않을까 한다.



기본적인 개발 환경 Setting은 서론에서 올려준 사이트를 참고하길 바란다.(Dream coding 추천!)

<br><br><br>

### HTML의 약자는 무엇인가

<br><br>
HT - HyperText, 문서와 문서가 링크로 연결되어 있다. ‘링크’라고 이해하면 쉽다.
<br><br>
M - Markup, 태그로 이루어져 있다.
<br><br>
L - Language, 언어다!
<br><br><br>


### HTML은 결국 ‘언어’이다.

<br><br>
웹페이지를 만드는 ‘언어’. 언어는 <b>소통</b>하기 위해 만드는 것이다.
<br><br>
사람과 컴퓨터, 시스템이 의사소통하기 위한 것이 언어이며, 언어에서는 약속이 정말 중요하다. 
<br><br>
단어가 어떤 의미인지를 서로 잘 정해놔야 얘기가 통하니까. 
<br><br>
그래서 HTML을 사용하기 위해서는, 우리도 그 <b>문법</b>을 알아놔야 하는 것이다.
<br><br>
언어 뼈대가 있으면 우리는 그 언어 뼈대를 바탕으로 코드를 넣어서 컴퓨터에게 보내준다. 
<br><br>
그러면 컴퓨터가 그 언어를 받아 그 것을 토대로 페이지를 구성해 주는 것이다.
<br><br>
<img width="647" alt="Untitled" src="https://user-images.githubusercontent.com/79993356/112347549-4dd62000-8d0a-11eb-8879-87a98bab0ab9.png">
<br><br>
위와 같은 사진의 형식이 기본적인 HTML의 틀이라고 할 수 있다. (좀 이따 자세히 다룬다)
<br><br><br>

### tag는 무엇인가.

<br><br>
우리의 옷에 붙어 있는 태그를 보면, 옷이라는 제품의 설명이 부가 되어 있지 않은가.
<br><br>
그 것이 <b>태그</b>이다. HTML에서의 태그도 이와 비슷한 역할을 한다.
<br><br>
<img src="https://pbs.twimg.com/media/Bk6ZHtVCUAElA3a.jpg">
<br><br><br>
tag가 어떤 것이 있는지 감이 안 올 것이다. 당연하다. 나도 그랬다!
<br><br>
그러기에 이 사이트를 추천한다.
<br><br>
<b><a href="https://developer.mozilla.org/ko/docs/Web/HTML/Element/a">MDN</a></b>
<br><br>
위 사이트에서 여러 tag들에 대한 설명을 보고 용법을 이해하면 도움이 많이 된다.



이 글에서는 tag들이 무엇인지 하나하나 설명해줄 필요가 없을 정도로 저 사이트가 친절하다👍

<br><br><br>

### tag 뼈대는 어떻게 이루어져 있는가?

<br><br>
<img width="768" alt="Untitled" src="https://user-images.githubusercontent.com/79993356/112349131-d30e0480-8d0b-11eb-8a93-ebd461b60d80.png">
<br><br>
<b>태그는 컨텐츠(전달하고자 하는 내용)을 감싸주는 역할을 한다.</b>
<br><br>
사진에서 보면 컨텐츠와 이를 감싸는 태그가 보인다.
<br><br>
<b>✚ a와 href는 무엇인가? </b>
<br><br>
href는 링크를 연결해주는 속성명이며, HTML <a> 요소(앵커 요소)는 href 특성을 통해
<br>
다른 페이지나 같은 페이지의 어느 위치, 파일, 이메일 주소와 그 외 다른 URL로 연결할 수 있는 하이퍼링크를 만든다. 
<br>
a tag 안의 콘텐츠는 '링크 목적지'의 설명을 나타내야 한다.
<br><br><br>

### HTML의 뼈대는 어떻게 이루어져 있는가?

<br><br>
<b>(1) 진짜! 기본적인 뼈대</b>
<br><br>

```
  <!DOCTYPE HTML>
  <html>
      <head>
         문서를 정의하는 데이터가 위치함
      </head>
      <body>
          문서에 표시되는 컨텐츠가 위치함
      </body>
  </html>
```

<br><br>
이해하기 쉽게 각자가 코딩하는 프로그램에서 파일 하나를 만들어서 해보면 좋다!
<br><br><br>

- HTML 문서는 파일의 확장자가 html 혹은 htm으로 끝난다.
  <br><br>

- 최상위 태그로 <html>을 사용한다. 그 하위에 <head> 태그와 <body> 태그를 컨텐츠로 가지고 있다.
  <br><br>

- head 태그는 문서를 ‘설명하는 태그’로 제목이나 키워드와 같은 정보를 담는다.

  여기에 담긴 속성들은 웹페이지를 <b>꾸며주는</b> 역할을 한다.

  <br><br>

- body 태그에는 ‘문서의 내용’이 위치한다.

  여기에 담긴 속성들은 웹페이지의 <b>구조</b>를 만들어준다. 

  

  *이게 대체 무슨 말이지..?*

  <br><br><br>

<b>(2) Head와 Body</b>





<img width="557" alt="Untitled" src="https://user-images.githubusercontent.com/79993356/112407187-00cd6a80-8d59-11eb-929b-c9aa903a4487.png">



여기서 주황색 위가 Head, 밑이 Body인 것은 쉽게 알 수 있을 것이다.

title과 meta는 본문을 꾸며주는 역할이지, 사실상 h로 시작하는 부분부터 웹 화면에 나타나는 본문에 해당한다.

<img width="908" alt="스크린샷 2021-03-25 오전 11 00 40" src="https://user-images.githubusercontent.com/79993356/112407401-602b7a80-8d59-11eb-822f-b0a0f3fb867d.png">

이런 식으로 body에 있는 값이 html에서 나타난다. 



<b>(3) Doctype</b>
<br><br>

```
<!DOCTYPE html>
<html>
    <head>
        <meta http-equiv="Content-Type" content="text/html;charset=utf-8" />
    </head>
    <body>
        <img alt="생활코딩 로고" src="https://opentutorials.org/user/course/1/94.png" />
        <br />
        <a href="http://opentutorials.org/course/1">생활코딩</a>
    </body>
</html>
```

<br><br>이런 식으로 doctype이란 것이 있다!



문서의 타입 선언이라고 해석할 수 있다.

자신이 작성한 코드가 어떤 방식의 코드로 작성되었는지 선언하는 것이다. (컴퓨터에게 알려줌)



웹이 어떠한 표준을 따르고 있는 태그들이라고 브라우저에게 알려주는 것이다.



*(사실 몰라도 크게 상관 없다.. 그냥 시작할 때 Doctype과 HTML태그만 설정해주면 된다~)*

 <br><br>
Head 안에서 쓰는 tag들(meta, link, style..)과 body 안에서 쓰는 tag들(div, a, p, input..)이 따로 있다.
<br><br>
*그 것도 MDN에서 친절히 알려주니 둘러보자!
