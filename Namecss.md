# CSS

1. 목록
  - SMASS
  - OOCSS
  - BEM

## SMASS

 CSS를 비슷한 5가지 종류로 나눈다. Base,Layout,Module,State, Theme 로 나눈다 .  Base는 말 그대로 기본 스타일이다. Reset,Variable 등을 포함하지만
 !important를 쓰지 않고 Layout은 suffix "l-"을 붙인다. Layout은 ID 선택자를 사용해도 된다. Module은 table, icon,box같이 재사용성이 높은 요소를 정의 한다. State는 상태를 나타난다. active나 disable등이며 suffix "is-"나 "s-"를 붙인다.
 Theme는 전반적인 Look and feel을 정의하며 suffix "theme-"를 붙인다.

 ## BEM

화면에 보여질 블록을 기준으로 첫번째 순서의 네이밍을 작성한다.
그 다음에 블록 안의 요소(elements)들을"__" (언더바 2개) 으로 연결해서 네이밍을 작성한다.
그 다음에 수식어(모양이나 상태)를 "-"으로 연결한 뒤 네이밍을 작성한다.
수식어는 boolean이나 key-value형태로 넣을 수 있다.(-isable,-color-red)이렇게 쓸 수 있고 예를 들면 .header__logo 또는 .form__button-disabled과 같은 식이다. 클래스명이 용도와 형태를 의미하므로 직관적인 것이 장점, 길고 복잡해지는 것이 단점이다.

## OOCSS

BEM이 역할-요소-상태 순으로 정리한다면, OOCSS는 구조와 스타일을 분리한다. 중복되는 디자인 요소를 따로 빼내어 반복적으로 사용한다.(공통 스타일 추상화)
컨테이너와 콘텐츠를 분리하고 위치에 의존적인 스타일을 정의하지 않고 코드 재사용성이 높아져 코드량이 줄고 성능이 향상되며 유지보수성도 높아지는 장점이 있지만 마크업에서 동일한 클래스를 여러 곳에 사용하므로 코드가 지저분해지는 단점이 있다. 이 단점을 보완한 것이 OOSass로, 마크업의 복잡함을 프리프로세서 내에서 대신 처리한다.