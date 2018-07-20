## bearideas 페이지 구축

### url
~~~
http://bearideas.fr/
~~~

### 목표
~~~
bearideas 페이지 
~~~

## 반응형
~~~
<meta name="viewport" content="width=device-width, initial-scale=1.0">
~~~

### 크로스브라우징
~~~
 ie9/ie10/ie11, Chrome, Firefox 크로스브라우징
    <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
~~~

### DTD
~~~

~~~

### language TYPE
~~~
<link rel="alternate" href="http://bearideas.fr/en/" hreflang="en" />
<link rel="alternate" href="http://bearideas.fr/fr/" hreflang="fr" />
<link rel="alternate" href="http://bearideas.fr/" hreflang="x-default" />
~~~

### Encoding
~~~

~~~

### META TAG
~~~
    <meta name="description" content="genuine ideas &amp; creation for brands">

    <!-- resp -->
    <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!--[if lte IE 9]>
        <meta http-equiv="refresh" content="1; url=http://browsehappy.com/?locale=en">
    <![endif]-->

~~~

### 특징
~~~
- 다국어 지원 ( en / fr )
- 구글 지도 연동(?)
- 반응형
- 워드프레스 
- 두가지 스타일의 색상 지원
- 페이지 로더 
~~~

### 필요한 기술 + 배워야할 기술
~~~
HTML
CSS Transitions 
CSS Animation
CSS Transform
tweenmax
slider
scrollmagic  *scrollmagic 공부 필요 
전체 화면 동영상 재생
svg
~~~
 
 
### js 작성 규칙
~~~

~~~

### ui library
~~~
(scrollmagic)

(mCustomScrollbar)


~~~

## css 작성 규칙
~~~

~~~


### bearideas 메뉴 구성도 
~~~
1. 메인페이지


일단 메인페이지에서 해야할 것들 정리 및 공부 중...^^ 


- SVG는 무엇이며 어떻게 써야하는 걸까? > 다른 보통의 페이지와는 다르게 logo부터 svg다....그냥 갖다 붙여놓으면 나오긴 하는데....? 


- 프리로딩 페이지는 어떤 식으로 해야 할까?
( 프리로딩 쪽에 beardots는 어떤식으로 한 걸까? 자동화툴 같은게 있나?)


-bezier-curve 는 무엇이며 어떻게 쓸 수 있을까? 

https://apes0113.postype.com/post/2620   * 좋은 글/ 기본 개념과 원리를 설명하고 있다
https://blog.coderifleman.com/2017/01/02/bezier-curves-for-frontend-engineer-1/


- 전체화면 동영상 재생은 어떻게 ? > video 태그 활용 > 동영상 재생의 문제...ㅠㅠ
http://bearideas.fr/wp-content/themes/bear/assets/videos/polar.mp4?v4
http://bearideas.fr/wp-content/themes/bear/assets/videos/black.mp4?v4


- 스크롤바 디자인 변경은 어떻게 ? 바꾼다고 해도 이슈는 없을 까? > 스크롤바 커스텀 가능한 플러그인(mCustomScrollbar)을 사용해볼 까 하는데 외부에 또 다른 스크롤이 생길 뿐... ㅠㅠ 


- 스크롤매직 플러그인 > 스크롤 시 컨텐츠의 움직임을 봐서 필요한 플러그인 일듯, 이 플러그인을 써보고 싶습니당 ㅎㅎ > 플러그인 활용 할 때 먼저 공부해야 할 것은? > 관련 문서를 봐도 애매....? ㅠㅠ



2. who we are
3. what we do
4. projects
5. get in touch

~~~

### ui 핸들링 및 기능구현을 위한 jquery

### 폰트

### color 

### 버튼