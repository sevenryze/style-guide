# Table of Content

- [Table of Content](#table-of-content)
- [Convention](#convention)
- [Rules](#rules)
  - [Display](#display)
  - [FlexBox](#flexbox)
  - [Positioning](#positioning)
  - [Table](#table)
  - [List](#list)
  - [Box model](#box-model)
    - [Size of box model](#size-of-box-model)
    - [Margin](#margin)
    - [Padding](#padding)
    - [Border](#border)
    - [Background](#background)
  - [Basic User Interface](#basic-user-interface)
  - [Text and Font](#text-and-font)
    - [Font](#font)
    - [Text](#text)
    - [Text Decoration](#text-decoration)
  - [Generated Content](#generated-content)
  - [Transition](#transition)
  - [Transform](#transform)
  - [Animations](#animations)

# Convention

1.  Only those properties listed below can be used. If you want to use sort of hacking techs that not listed, feel pleasure to open issue.
2.  Please write css properties by the order of the list strictly.
3.  We will use code quality checker to ensure those rules soon.

# Rules

## Display

> CSS Display is a module of CSS that defines how the CSS formatting box tree is generated from the document element tree and defines properties controlling it.

1.  display: 如何显示布局. 对比`display`与`position`和`float`的关系, [参见这里](https://drafts.csswg.org/css-position-3/#dis-pos-flo).

## FlexBox

* [x] Clarified and no ambiguity.
* [ ] Done?

> CSS Flexible Box Layout is a module of CSS that defines a CSS box model optimized for user interface design, and the layout of items in one dimension. In the flex layout model, the children of a flex container can be laid out in any direction, and can “flex” their sizes, either growing to fill unused space or shrinking to avoid overflowing the parent. Both horizontal and vertical alignment of the children can be easily manipulated.

1.  align-content:
2.  align-items:
3.  align-self:
4.  flex:
5.  flex-basis:
6.  flex-direction:
7.  flex-flow:
8.  flex-grow:
9.  flex-shrink:
10. flex-wrap:
11. justify-content:
12. order

## Positioning

* [x] Clarified and no ambiguity.
* [ ] Done?

> CSS Positioned Layout is a module of CSS that defines how to position elements on the page.

1.  position:
2.  top:
3.  right:
4.  bottom:
5.  left:
6.  z-index:
7.  float:
8.  clear:

## Table

* [x] Clarified and no ambiguity.
* [ ] Done?

> CSS Table is a CSS module that defines how to lay out table data.

1.  "table-layout",
2.  "empty-cells",
3.  "caption-side",
4.  "border-spacing"
5.  "border-collapse",
6.  vertical-align:

## List

* [x] Clarified and no ambiguity.
* [ ] Done?

> CSS Lists is a module of CSS that defines how lists can be laid out and styled.

1.  "list-style",
2.  "list-style-position",
3.  "list-style-type",
4.  "list-style-image"

## Box model

* [x] Clarified and no ambiguity.
* [ ] Done?

> CSS Basic Box Model is a module of CSS that defines the rectangular boxes—including their padding and margin—that are generated for elements and laid out according to the visual formatting model.

### Size of box model

1.  [`box-sizing`](https://www.w3schools.com/css/css3_box-sizing.asp): 确认采用哪种`box-sizing`计算方式. 推荐全局使用`boder-box`.
1.  `width`:
1.  `min-width`:
1.  `max-width`:
1.  `height`:
1.  `min-height`:
1.  `max-height`:
1.  `overflow`:
1.  `overflow-x`:
1.  `overflow-y`:
1.  `visibility`:

### Margin

2.  [`margin`](https://developer.mozilla.org/en-US/docs/Web/CSS/margin): 指定元素`margin`. 注意*margin collapsing*问题.
1.  `margin-top`:
1.  `margin-right`:
1.  `margin-bottom`:
1.  `margin-left`:

### Padding

1.  [`padding`](https://developer.mozilla.org/en-US/docs/Web/CSS/padding): 指定元素的`padding`.
1.  `padding-top`:
1.  `padding-right`:
1.  `padding-bottom`:
1.  `padding-left`:

### Border

4.  [`border`](): 指定元素的`border`.
1.  `border-width`:
1.  `border-style`:
1.  `border-color`:
1.  `border-top`:
1.  `border-top-width`:
1.  `border-top-style`:
1.  `border-top-color`:
1.  "border-right":
1.  "border-right-width":
1.  "border-right-style":
1.  "border-right-color":
1.  "border-bottom":
1.  "border-bottom-width":
1.  "border-bottom-style":
1.  "border-bottom-color":
1.  "border-left":
1.  "border-left-width":
1.  "border-left-style":
1.  "border-left-color":
1.  `border-radius`:
1.  `border-top-left-radius`:
1.  `border-top-right-radius`:
1.  `border-bottom-right-radius`:
1.  `border-bottom-left-radius`:
1.  `border-image`:
1.  `border-image-source`:
1.  `border-image-slice`:
1.  `border-image-width`:
1.  `border-image-outset`:
1.  `border-image-repeat`:

### Background

1.  `color`:
2.  `opacity`:
3.  "background",
4.  "background-color",
5.  "background-image",
6.  "background-repeat",
7.  "background-attachment",
8.  "background-position",
9.  "background-clip",
10. "background-origin",
11. "background-size"

## Basic User Interface

> How to classify those?

1.  caret-color:
2.  cursor:
3.  outline:
4.  outline-color:
5.  outline-offset:
6.  outline-style:
7.  outline-width:
8.  resize:
9.  text-overflow:

## Text and Font

* [x] Clarified and no ambiguity.
* [ ] Done?

### Font

> CSS Fonts is a module of CSS that defines font-related properties and how font resources are loaded. It lets you define the style of a font, such as its family, size and weight, line height, and the glyph variants to use when multiple are available for a single character.

1.  font:
2.  font-style:
3.  font-weight:
4.  font-size:
5.  font-size-adjust:
6.  line-height:
7.  font-family:
8.  font-variant:
9.  font-variant-caps:
10. font-variant-numeric:
11. font-variant-alternates:
12. font-variant-ligatures:
13. font-variant-east-asian:
14. font-stretch:

### Text

> CSS Text is a module of CSS that defines how to perform text manipulation, like line breaking, justification and alignment, white space handling, and text transformation.

1.  text-align:
2.  text-align-last:
3.  letter-spacing:
4.  text-indent:
5.  text-justify:
6.  text-transform:
7.  white-space:
8.  word-break:
9.  word-wrap:
10. word-spacing:

### Text Decoration

> CSS Text Decoration is a module of CSS that defines features relating to text decoration, such as underlines, text shadows, and emphasis marks.

1.  text-decoration:
2.  text-decoration-color:
3.  text-decoration-line:
4.  text-decoration-style:
5.  text-emphasis:
6.  text-emphasis-color:
7.  text-emphasis-position:
8.  text-emphasis-style:
9.  text-shadow:
10. text-underline-position:

## Generated Content

* [x] Clarified and no ambiguity.
* [ ] Done?
  > CSS Generated Content is a module of CSS that defines how to add content to an element.

1.  `content`:
2.  `quotes`:

## Transition

* [x] Clarified and no ambiguity.
* [ ] Done?

1.  "transition":
2.  "transition-delay",
3.  "transition-timing-function",
4.  "transition-duration",
5.  "transition-property",

## Transform

* [x] Clarified and no ambiguity.
* [ ] Done?
  > CSS Transforms is a module of CSS that defines how elements styled with CSS can be transformed in two-dimensional or three-dimensional space.

1.  transform

## Animations

* [x] Clarified and no ambiguity.
* [ ] Done?

1.  "animation",
2.  "animation-name",
3.  "animation-duration",
4.  "animation-play-state",
5.  "animation-timing-function",
6.  "animation-delay",
7.  "animation-iteration-count",
8.  "animation-direction"
