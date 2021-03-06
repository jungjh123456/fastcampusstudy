#HTML&CSS 2일차 

1. 목차
  - 웹접근성과 웹표준
    - 웹접근성
    - 웹표준
  - WWW
  - HTML5에 대해서 Markup
  - CSS에 대해서
  - CSS 기초


## 웹 접근성과 웹 표준

### 웹 접근성
웹 접근성(Web accessibility)은 장애를 가진 사람과 장애를 가지지 않은 사람 모두가 웹 사이트를 이용할 수 있게 하는 방식을 가리킨다. 사이트가 올바르게 설계되어 개발되고 편집되어 있을 때 모든 사용자들은 정보와 기능에 동등하게 접근할 수 있다.
1. 웹 접근성을 높이는 두가지 방법
  - 적절한 링크 텍스트 제공하기(alt태그 제공하기)
  - 깜빡이거나 번쩍이는 콘텐츠 제공하지 않기

### 웹 표준
웹 표준은 WWW(World Wide Web)의 측면을 서술하고 정의하는 공식 표준이나 다른 기술 규격을 가리키는 일반적인 용어이다. 최근에 이 용어는 웹 사이트를 작성하는 데 
중요도가 높아지고 있으며 웹 디자인, 개발과 관계가 있다.

1. 웹표준의 장점
  - 소스의 통일화로 수정 및 운영관리가 용이하다.
  - 다양한 브라우저, 휴대폰 PDA, 장애인 지원용 프로그램에서도 대응이 가능하므로 접근성이 향상된다.
  - 검색봇을 통한 효율적 노출과 같은 검색엔진 최적화가 가능하다.
  - 효율적 소스를 통해 File Size 축소 및 서버 저장 공간을 절약할 수 있다.
  - CSS와 HTML 문서의 분리등을 통해 페이지 로딩속도 향상과 같은 효율적인 마크업이 가능하다.
  - 다양한 브라우저에서의 호환이 가능하다.

## WWW(World Wide Web)

WWW(World Wide Web)의 역사
who: Tim Berners-Lee라는 분이 만들었고 인터넷에 연결된 컴퓨터를 통해 사람들이 정보를 공유할 수 있는 전 세계적인 정보 공간을 말한다.
원레는 세계의 여러 대학과 연구기관에서 일하는 물리학자들 상호간의 신속한 정보교환과 공동연구를 위해 고안이 되었다. 


## HTML5에 대해서 Markup
HTML5가 탄생하기 이전까지 HTML의 최초 버전은 1993년에 최신 버전은 1999년에 발표가 되었다. W3C가 XHTML1.0을 구체화 하기 위해 XHTML2.0 작업을 진행 중이 었으나 하위 호환상에 치명적인 문제가 있었고 2004년 애플, 모질라 재단,오페라 소프트웨어가 공동으로 설립한 공개 그룹인 WHATWG가 W3C와 별개로 Web Application 1.0과 Web Forms2.0을 만들어 내고  2007년 3월 W3C가 공개적으로 XHTML 2.0의 실패를 인정한 후 새롭게 HTML을 개발하기로 결정하면서 WHATWG의 표준안을 대부분 수용하여 HTML5가 탄생하게 되었다.

### Markup이란 
'마크업'이란 어딘가에 Mark, 즉 표시를 해두는 것을 뜻합니다.
예를들어 일기를 쓸때 제목,내용,주소 라는 이름을 정하지 않고 쓰는 것 보다 제목 내용 주소를 구분해서 
쓰는 것이 보기 쉽습니다. 즉 많은 것들을 구조적으로 표현할 수 있는 것이고 
문서를 구조적으로 표시하기 위한 것이 마크업입니다.

## HTML4.01, XHTML1.0과 HTML5의 차이점
새롭게 등장한 콘텐츠 모델
 - 명확한 정보 구조 설계 및 구성을 위해 카테고리를 정의하여 각 요소별로 비슷한 성격을 가지고 있는 것 끼리 그룹화 하였는데, 이를 HTML5의 콘텐츠 모델 이라고 함
콘텐츠 모델의 카테고리
 - HTML5의 카테고리에는 Sectioning Root, Metadata Content, Flow Content, Sectioning Content, Heading Content, Phrasing Content, Embedded Content, Interactive Content, Palpable Content, Script-supporting Elements, Transparent Content 등의 그룹이 있으며 하나의 요소가 여러 그룹에 속해 있을 수도 있고, 그렇지 않을 수도 있다. 

## outline 알고리즘
HTML5 outline 알고리즘은 간결하게 추려 낸 주요 내용을 의미한다. HTML5 마크업이 문서의 개요를 사용자에게 전달하기 위해 어떤 방법을 사용하는지 이해 함으로써 낡은 브라우저와 최신 브라우저 그리고 화면 낭독기에 적절하게 대응 할 수 있다.

해당 알고리즘을 이해하기 위한 키워드는 헤딩, 섹셔닝 루트, 섹셔닝 콘텐츠, 명시적/암시적 세션, 유효하지 않은 섹셔닝, 어색한 섹셔닝을 알면 이해할 수 있는데 
결론은 유연한 개요를 형성하려면 헤딩과 함께 섹셔닝 콘텐츠(section,article,nav등)을 쓰고 문서의 구조를 명확하게 하기 위해 최상위 수준의 헤딩은 하나만 쓰자.

## sectioning Root
- 섹셔닝 루트에 속하는 요소는 ```<section>```이나 ```<aricle>```요소와 같이 장이나 절과 같은 계층 구조로 구분되지 않고 독립적인 콘텐츠로 분리되기 때문에 아웃라인에 영향을 주지 않음

## Metadata 콘텐츠
다른 컨텐츠의 표현과 행동을 설정 문서와 문서의 관계를 정할 때 사용 ```<base>,<link>,<meta>,<noscript>,<script></script>,<style>,<title></title>```이 있음

## 플로우 콘텐츠
메타데이터 콘텐츠 요소 중 일부를 제외하고 문서 본문에 해당하는 body요소에 들어가는 대부분의 요소들이 플로우 콘텐츠 모델에 속하며,
이중에서 ```<area>, <link>,<meta>,<style>``` 요소는 조건부로 플로우 콘텐츠가 됨.

## 섹셔닝 콘텐츠
HTML5에 새롭게 추가된 요소, Heading과 Footer의 범위를 결정  모든 Sectioning컨텐츠는 Heading 과 아웃라인을 가짐 ```<article></article>,<section></section><nav></nav>등```

## 헤딩 콘텐츠

헤딩 콘텐츠는 섹션의 제목을 나타냄 문서의 아웃라인을 고려하여 사용해야 함


## HTML5의 API
HTML5의 커다란 변화 중 하나로는 다양한 API의 추가를 들 수 있다.

1. Web Storage
  웹 스토리지 API는 기존 쿠키의 문제점을 극복하기 위해 웹 브라우저가 직접 데이터를 저장할 수 있게 해준다.
  HTML5이전에는 응용 프로그램이 데이터를 서버에게 요청할 때마다 매법 쿠키라는 곳에 그 정보를 저장했다. 하지만 웹 스토리지는 사용자 측에서 좀 더 많은 양의 
  정보를 안전하게 저장 할 수 있도록 해준다.

2. Web SQL DATABASE
  HTML5의 로컬 저장소는 Web Storage 이외에도 관계형 데이타베이스가 추가로 제공된다. 이것이 web sql database이다. 
  web storage의 경우 비교적 적은 양의 간단한 데이터를 저장하기에 적합한 로컬 저장소인 반면 Web SQL DATAbase는 보다 구조적이고 체계화된 관계형 데이터를 대량으로 저장하기에 적합하다. 마치 파일이라는 저장소와 MS SQL이나 Oracle 과 같은 관계형 데이터베이스의 차이라 하겠다.
  
3. indexed Database  
indexed Database는 색인이 포함된 JSON객체가 모여있는 트랜잭셔널 로컬 데이터베잇를 위해 W3C가 권고한 웹 브라우저 표준 인터페이스의 하나이다.
웹 사이트는 데이터베이스에서 영속적인 데이터를 모아서 저장할 수 있다.
W3C는 2015년 1월 8일 IndexedDB 인터페이스를 위한 최종 권고안을 발행하였다.
IndexedB는 Transaction Database를 사용하여 Key-value로 데이터를 관리하며, B-Tree데이터 구조를 가진다.

## css 기초
CSS(Cascading Style Sheet)는 마크업 언어가 실제 표시되는 방법을 기술하는 언어로, HTML 과 
XHTML에 주로 쓰이며, XML에서도 사용할 수 있습니다.
다시 말해, HTML 문서를 스타일링 하는 언어(W3C의 표준)로 HTML 문서에서 link요소를 사용해 CSS
파일을 읽어 들이면 HTML 문서의 구조를 CSS를 통해 스타일링 하게 됩니다.

### CSS를 사용해야 하는 이유
1. 명확환 구조적 디자인과 표현적 디자인을 분리할 수 있다.
2. 다양한 장치에서 접근이 좀 더 용이하게 할 수 있습니다.
3. 웹 사이트의 많은 수정사항을 보다 빠르게 수정함에 있어서 용이하고(모든 페이지를 수정하는 것이 아니라 한개의 CSS파일만 수정) 물론 CSS파일이 콘텐츠 성격에 나뉘어 작업하지만 다수의 페이지가 있더라도 공통된 스타일(디자인)이 있기 때문에 해당 CSS파일만 수정하면 작업에 용이
4. 또한 코드에 가독성, 성능 최적화, 그리고 사용자가 자신의 기호에 맞게 디자인을 커스텀하는데 좋습니다.
5. 그리고 사이트를 운영하는 자에게는 유지보수 측면, 즉 관리의 용이성이 좋습니다.

### CSS스타일 선언 방식

CSS를 사용해서 HTML문서를 스타일링하는 3가지 방법이 있다.

첫 번째로는 internal Style이고 head영역 내부에 스타일시트를 작성하는 것을 내부 스타일이라고
한다. 기본적으로 내부 스타일은 head 에서만 사용해야하며, body 내부에서는 사용하지 말아야 한다.
내부스타일은 대개 단발성 페이지의 css분량이 적은 경우에 사용한다.

두 번째로는 Inline style 이다  한 줄(라인)으로 요소 내부에 스타일 속성을 이용하여 CSS 코드를 작성하는 것을 인라인 스타일 이라고 부른다.(이 방식은 유지보수가 힘들어 지기 때문에 대도록 사용하지 말아야 한다.)

마지막으로 세 번째로는 external Style이다 가장 권장되고 일반적인 방법으로 css파일을 별도로 관리 하는 형태입니다.

### CSS 기술 문서에 대한 진행별 상태 코드
FPWD(First Public Working Draft) 첫번째 공식 초안 단계 -> WD(Working Draft) 권고되는 표준 후보 스펙 -> CR(Candidate Recommendation) 권고되는 표준 후보 스펙 -> PR(Proposed Recommendation) 표준에 제안된 상태 -> REC(Recommendation) 표준으로 체택된 상태 -> SPSD(Superseded Recommendation) -> 표준이 업데이트되면서 대체된 권고안(표준안)
!import는 맨 앞에 적어야한다.

## normalize.css

Normalize.css는 HTML요소의 기본 스타일을 브라우저 간 일관성을 유지하도록 돕는 CSS 파일이다. 이것은 Boilerplate밑 Bootstrap등 과 같은 크고 작은 프로젝트에서도 두루두루 사용되고 있다.

1. Normalize.css 특징

브라우저(모바일 브라우저를 포함하여)를 광범위하게 지원하며, HTML5 요소, 타이포그래피, 목록(lists), embeded 콘텐츠, 폼과 테이블을 일관성있게 통일시키는 CSS를 포함한다.

 - 다른 CSS reset 과는 달리 사용하기 좋은 기본값들은 유지한다.
 - HTML 요소의 다양한 스타일을 정규화한다.
 - 버그 및 브라우저 간 차이점을 수정한다.
 - 부분적인 개선과 가용성을 향상시킨다.
 - 코드에 대한 자세한 주석이 달려 이해를 돕는다.
 - normalize는 버전 1은 구형 IE(IE6)를 지원하지만 더이상 개발이나 수정이 이루어지지 않는다. 버전 3대가 현재 개발되고 애용되는 버전이다.


