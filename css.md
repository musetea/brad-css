## HTML

- content

- style
- vector graphics

### List

- ul
- ol
- dl
- Blod = <strong>Example Text </string>
- Italic = <em>Example Text</em>
- <div> : Block-level,
- <span> : Inline Level

- HTML Comments : 주석처리
<!-- this is where the main text of the article begins -->
- <section> : 챕터,

## CSS

### Selector

- Type Selectors
- Descendant Selectors : 자식을 통해 선택 header p
- Class selectors

31. Cascade

- Inheritance
- Specificity

32. Box Model
33. Layout

- `float` : layout

34. Navigation Menu
35. Overlapping Content

- 브라우저가 길이를 계산할때 글꼴 크기나 노퓨이 같은 것을 사용하는데 그게 정확하지 않는다. 그래서 이미지를
  `block` 레벨을 만든다.

36. Form

- text-shadow
  1. 수평값 설정.
  2. 텍스트의 좌측거리, 그림자의 세로 차이
  3. 흐릿한 반경

41. Web Font

- Hosted Font Solutions
- Self Hosted Fonts

42. Inspecting Element's
43. Backgroun Images

- background-position:
  1. 수평 위치
  2. 세로 위치
- background-image
- background-repeat
- background-position
- background-size
- background: #c2bbb1 url('../') center center no-repeat;
- linear-gradient
  1. 흐름방향
  2. 시작색상
  3. 끝나는 색상

45. CSS Sprites
46. Response Web Design

- @meadia query

49. Grid

- 12 열 격자 사용
  - columns 4 = 3\*4
  - columns 3 = 4\*3
  - columns 2 = 6\*2
- `xs`: Extra Smail (스마트폰) 480px
- `sm`: Small (테블릿) 768px
- `md`: Medium (노트북, 미디엄 모니터) 960px
- `lg`: Large (테스크탑, 라지모니터) 1024px

53. Box Shadow

- 그림자의 수평위치
- 그림자으 수직위치
- 그림자의 블러

54. border-radius
55. Transform

- Rotate : 회전

* rotate(25deg) - 시계방향으로 각도 지정

- SCale : 확대, 축소
- Skew : 기울기

* skewX(deg), skewY(deg)

- POsition
- transform-origin : 변환의 시작점 (x,y)

## SCSS

```sh
 npx sass --watch main.scss output.css
```

1. Variables
2. Nesting
3. Inheritance / @extend
4. Splitting up code into smaller files / @import
5. Mixins
6. Operators
