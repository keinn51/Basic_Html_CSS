# 비전공자 HTML&CSS공부를 위한 정리😄

This repository includes Html & CSS

This is made easy to understand them for beginner like me.

<br>

I got the basic course at 

<a href="https://opentutorials.org/course/2039">Life coding</a>


<a href="https://www.youtube.com/watch?v=wcsVjmHrUQg&list=PLv2d7VI9OotTVOL4QmPfvJWPJvkmv6h-2">Dream Coding</a>

I recommend the website for beginner because they tell you the basics in an <b>easy-to-understand</b> manner.


****

## 🎁 HTML

<br><br>
이 글을 읽는 사람은 나와 같이 html과 CSS가 아예 생소한 사람일테다.
<br><br>
천천히 이 글을 읽다 보면 그래도 나름… 개념이 잡히지 않을까 한다.



기본적인 개발 환경 Setting은 서론에서 올려준 사이트를 참고하길 바란다.(Dream coding 추천!)

<br><br>

### ✅ HTML의 기본과 tag

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
<br><br>

- HTML 문서는 파일의 확장자가 html 혹은 htm으로 끝난다.
  <br>

- 최상위 태그로 <html>을 사용한다. 그 하위에 <head> 태그와 <body> 태그를 컨텐츠로 가지고 있다.
  <br>

- head 태그는 문서를 ‘설명하는 태그’로 제목이나 키워드와 같은 정보를 담는다. 여기에 담긴 속성들은 웹페이지를 <b>꾸며주는</b> 역할을 한다.

  <br>

- body 태그에는 ‘문서의 내용’이 위치한다. 여기에 담긴 속성들은 웹페이지의 <b>구조</b>를 만들어준다. 

  

  *이게 대체 무슨 말이지..?*

  <br><br>

<b>(2) Head와 Body</b>





<img width="557" alt="Untitled" src="https://user-images.githubusercontent.com/79993356/112407187-00cd6a80-8d59-11eb-929b-c9aa903a4487.png">



여기서 주황색 위가 Head, 밑이 Body인 것은 쉽게 알 수 있을 것이다.

title과 meta는 본문을 꾸며주는 역할이지, 사실상 h로 시작하는 부분부터 웹 화면에 나타나는 본문에 해당한다.

<img width="908" alt="스크린샷 2021-03-25 오전 11 00 40" src="https://user-images.githubusercontent.com/79993356/112407401-602b7a80-8d59-11eb-822f-b0a0f3fb867d.png">

이런 식으로 body에 있는 값이 html에서 나타난다. 

<br><br>

Head 안에서 쓰는 tag들(meta, link, style..)과 body 안에서 쓰는 tag들(div, a, p, input..)이 따로 있다.
<br>그 것도 MDN에서 친절히 알려주니 둘러보자!*

<br><br>

<b>(3) Doctype</b>
<br>

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

<br>이런 식으로 doctype이란 것이 있다!

<br><br>

문서의 타입 선언이라고 해석할 수 있다.

자신이 작성한 코드가 어떤 방식의 코드로 작성되었는지 선언하는 것이다. (컴퓨터에게 알려줌)

<br>

웹이 어떠한 표준을 따르고 있는 태그들이라고 브라우저에게 알려주는 것이다.

<br>

*(사실 몰라도 크게 상관 없다.. 그냥 시작할 때 Doctype과 HTML태그만 설정해주면 된다~)*

 <br><br>

<br>

### ✅ form을 만드는 법

<br><br>

### 로그인 폼을 만드는 법

<br>

기본적인 HTML틀을 이해했으니 이제 본격적으로 HTML을 만들어 볼 차례다.

<br>

![image](https://user-images.githubusercontent.com/79993356/112409929-ae427d00-8d5d-11eb-84a8-111ade84bfce.png)

<br>



왼쪽과 같이 코딩하면, 오른쪽 화면과 같은 form이 생긴다. 가장 기본적은 form이다!

<br>

**HTML `<form>` 요소**

정보를 제출하기 위한 대화형 컨트롤을 포함하는 문서 구획을 나타낸다.

우리가 입력한 정보가 어디로 전송되어야 하는지 알려주는 것이다.

action은 사용자가 입력한 정보를 ~로 보내주어라 할 때 사용한다.

<br>

**HTML `<input>` 요소**

웹 기반 양식에서 사용자의 데이터를 받을 수 있는 대화형 컨트롤을 생성한다.

사용자에게 정보를 입력 받아 사용하는 태그이다.

<br>

<br>

### name 설정해주기

<br>

![image](https://user-images.githubusercontent.com/79993356/112410588-c36bdb80-8d5e-11eb-8924-2acea9f3d15c.png)

그런데 타입만 정하면, 컴퓨터 입장에서는 뭐가 뭔지 당연히 헷갈릴 수밖에 없다.

그래서 우리가 하는 행동은, name으로 구분을 지어주는 것이다!

<br>

name으로 구분 지어, input을 통해 정보를 입력하면, 오른쪽 사진처럼 localhost라는 곳으로 정보가 이동한다.

**name을 지어주지 않으면, 어떤 정보를 전송하는 지 알아듣지 못하는 것이다!!!**

<br>

*여기서 localhost는 네이버, 다음, 카카오 등 여러 가지가 될 수 있다!*

<br>

<br>

### textarea 사용법

<br>

![image](https://user-images.githubusercontent.com/79993356/112410780-1e9dce00-8d5f-11eb-8ef3-3696d1bb4d09.png)

<br>

✓ **value** : 입력창 안에서의 기본값을 설정해 둘 수 있다.

✓ **textarea** = 기존의 상자(Text)는 한 줄만 쓸 수 있었는데, 얘는 몇 줄이고 설정한 대로 쓸 수 있다. **row, cols**를 설정해줄 수 있다.

<br>

<br>

### Select 사용법

![image](https://user-images.githubusercontent.com/79993356/112411028-8eac5400-8d5f-11eb-9ced-696f327506eb.png)

<br>

**HTML `<select>` 요소**

옵션 메뉴를 제공하는 컨트롤을 나타낸다.

select는 사진과 같이 선택할 수 있는 UI를 만들어주는 것이다.

세부적인 선택지는 <b>option</b>을 통해 만든다.

<b>multiple</b>을 사용하면 다중선택창도 띄울 수 있다,

<br>

✚ 중요한 것은 name과 value!를 정해주는 것. 

우리가 색상~, 붉은색~ 이렇게 적어 놓아봤자 컴퓨터는 무슨 말을 하는지 모른다. 

그러니까 name= "~", value = "~" 이런 식으로 지정을 해줘야 컴퓨터가 그제서야 알아 듣는다.

<br>

<br>

### radio & Checkbox

<br>

![image](https://user-images.githubusercontent.com/79993356/112411387-2ca01e80-8d60-11eb-9116-aebaef53ff6e.png)

<br>

input 타입 중에 radio와 checkbox가 있다..

<br>

<b>radio는 단수선택</b>

radio는 name이 같은 것들 끼리 그룹이 된다. 그룹 안에서 radio를 하나 선택하면, *그룹 내 다른 라디오는 선택이 해제된다.*

페이지를 시작할 때 초기 설정값을 해두고 싶으면, checked를 설정해 놓으면 된다.

<br>

<b>checkbox는 복수선택</b>

checkbox는 radio와 달리, *그룹 내 다른 선택지를 선택해도 모두 선택된다.*

<br>

<br>

### button

<br>

<img width="851" alt="무제" src="https://user-images.githubusercontent.com/79993356/112413413-8229fa80-8d63-11eb-9ce7-c092a4ac0f2e.png">

<br>

이런 식으로 버튼도 만들 수 있다. type에 button을 입력하고, value에 button에 삽입하고 싶은 문구를 넣는다.

<br>

<br>

### label

<br>

<img width="927" alt="스크린샷 2021-03-25 오후 12 17 05" src="https://user-images.githubusercontent.com/79993356/112413748-13996c80-8d64-11eb-8220-de4e05b9889e.png">

<br>

만약 label + input + checkbox를 쓴다고 한다면, 주황색 체크박스만 선택해도 checkbox가 선택이 된다.

<b>터치할 수 있는 범위가 넓어지게 만들어주는 것</b>이다.

<br>

`<label>` 을 `<input>` 요소와 연관시키려면, `<input>` 에 `id` 속성을 넣어야한다.

 그런 다음 `<label>` 에 `id` 와 같은 값의 `for` 속성을 넣어야 한다. 

<br>

<br>

<br>
****
## 🎁 Basic CSS

<br>

### Basic

<br>

<br>

### HTML과 CSS합쳐보기

<br>

<a href="https://aboooks.tistory.com/147">참고 홈페이지</a>

<br>

![image](https://user-images.githubusercontent.com/79993356/112421877-46972c80-8d73-11eb-9468-fa454c04c342.png)

<br>

이 두 친구들을 합쳐 보자! (왼쪽은 .html으로 저장오른쪽은 .css)

<br>

![image](https://user-images.githubusercontent.com/79993356/112421949-6fb7bd00-8d73-11eb-8cc1-f5f6ea1f0e0f.png)

HTML파일에다 이런 식으로 link 태그를 걸어준다.

<br>

`<link>`: 현재 문서와 외부 리소스의 관계를 명시한다. `<link>`는 [스타일 시트](https://developer.mozilla.org/en-US/docs/Glossary/CSS)를 연결할 때 제일 많이 사용한다.

<br>

`rel` :  관계(*rel*ationship)를 뜻하며, 현재 문서와 연결한 아이템의 관계가 어떻게 되는지 설명한다. 따라서 `<link>` 요소의 제일 중요한 기능 중 하나라고 볼 수 있다.

<br>

`type` : 링크된 외부 리소스의 미디어 타입을 명시한다.이 속성은 반드시 href 속성이 설정되어 있어야만 사용할 수 있다.

<br>

![image](https://user-images.githubusercontent.com/79993356/112422487-57946d80-8d74-11eb-8c26-1e874e647278.png)

<br>

 이렇게 된다!

<br><br>

### 선택자와 속성

<br>

<img width="306" alt="스크린샷 2021-03-25 오후 2 16 04" src="https://user-images.githubusercontent.com/79993356/112422833-dab5c380-8d74-11eb-96d0-c114c9ea92dc.png">



위에 body 라고 써있는 부분은 body 태그를 가리킨다. 

body 태그에 스타일을 주겠다는 뜻으로, 이 부분을 <b>'선택자(Selector)'</b>라고 부른다.

<br>

<img width="306" alt="스크린샷 2021-03-25 오후 2 16 04 복사본" src="https://user-images.githubusercontent.com/79993356/112422946-12bd0680-8d75-11eb-8eaf-3ceef1d3dd59.png">

<br>

그리고 {}이 괄호 사이에는 body 태그에 들어갈 스타일 들을 적는 것이다.

괄호 안에 'background-color:'와 같은 부분은 <b>'속성(Property)'</b>라고 부른다. 

<br>

 'color:'라고 적힌 부분은 'color 속성'인 것이다.

속성의 콜론(:) 오른쪽에는 해당 속성에 대한 값이 들어간다.

<br>

'#333333'이라는 것은 색상에 대한 코드이다.

'background-color' 속성에 '#333333'이라는 색상 코드를 할당한다고 생각하면 된다.

<br>

그리고 속성 값의 마지막에는 <b>세미 콜론(;)</b>이 붙어서 다음 속성 값과 구분한다.

그 다음 'color:white' 역시 글자 색 속성에 'white'라는 하얀색의 값을 할당한 것이다.

*(물론 #333333과 같이 색상 코드로도 쓸 수 있다. 하얀색의 색상 코드는 #ffffff이다.)*

<br>

<br>

![image](https://user-images.githubusercontent.com/79993356/112424446-c32c0a00-8d77-11eb-8163-19c20c74c348.png)

<br>

이런 식으로 p태그에 색을 입힐 수도 있다!

<br>

<br>

![image2](https://user-images.githubusercontent.com/79993356/112424471-d17a2600-8d77-11eb-8913-0afa4c63f634.png)

<br>

 그러면 이런 식이 된다. p태그 안의 글자들은 빨간색!

<br>

<br>

![image3](https://user-images.githubusercontent.com/79993356/112424490-ddfe7e80-8d77-11eb-8147-d942cc307d76.png)

<br>

 이걸 해보면 (font-weight는 굵기다!)

<br>

<br>

![image4](https://user-images.githubusercontent.com/79993356/112424511-ebb40400-8d77-11eb-9e95-6b29159c2607.png)
<br>

 이렇게 된다. h1태그 안에 있던 글자의 크기와 색깔이 달라졌음이 보인다.

<br>

<br>

![image5](https://user-images.githubusercontent.com/79993356/112424537-f66e9900-8d77-11eb-81ba-3ed37576414a.png)

<br>

p태그와 div 안의 p태그를 구분해서 색을 입혀주는 것도 가능하다.

<br>

<br>

![image6](https://user-images.githubusercontent.com/79993356/112424558-fff80100-8d77-11eb-91e3-502c2a0f21b6.png)

<br>

 이런 식으로 p태그 사이에서도 색이 다르게 나온다.

<br>

<br>

이렇게 간단하게 CSS를 훑어 보았으며, 이외에도 CSS에서 쓰이는 기술들이 있으나 이 개념을 이해한다면 따라가기 쉬울 것이다.

CSS의 다른 가술들에 대해서는 본 레퍼지토리 CSS파일을 참고해서 공부해보길 바란다.

<br><br>

HTML과 CSS를 더욱 공부하기 위해서 가장 좋은 방법은 Clone Coding! 이 레퍼지토리를 정독하고 연습했다면,

다음 주소의 레퍼지토리로 가서 나와 같이 Htmlr과 CSS만을 이용한 Clone Coding을 하러 가보자🙌
