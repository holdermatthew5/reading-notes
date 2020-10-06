- clear - shows that element (in the same conataining element) shall touch the specified side of the specified box. none means any side of any box (in the same container) can touch. both means neither side shall touch.
- floated element overflows from containing element so to fix the problem you can add:

```
overflow: auto;
width: 100%;
```

- use div and float to set columns then adjust width and margin to keep them side by side. or by applying the same float to each div
- there are pros and cons to both liquid and fixed width layouts
- fixed width body stays the same no matter how the browser expands or contracts. liquid body grow and shrink to fit the browser window snuggly as the window shrinks and grows.
- setting width to a percent allows the page to leave a gap between the edges of the body and the edges of the window
- not sure what they mean b y grid layout but it's supposed to help collaboration and make it easier to design a good looking page. Oh I guess it's just columns then? 389 says 12 column grid and doesn't show any row lines which doesn't really make sense considering elements can grow, shrink and move up and down just as easily as left and right. I guess scrolls have something to do with it? meaning sites don't often scroll right and left but they do scroll up and down leaving potentially infinite room for growth so the number of rows could be infinite but even then like code works the same way. as we add code it adds lines so why change it then?
- grid layout stylesheets can be found at:
  - www.960.gs
  - blueprintcss.org
  - lessframework.com
  - developer.yahoo.com/yui/grids/

- uses class names to stretch boxes to meet grid patterns as desired
- some developers use different files for certain aspects (color, font, etc.) of styling. they can be connected to eachother with: `@import url(css/style.css)` in the main css page. You then only need to link one css page to the html page.
- width and height work for images too
- for rules that apply to several elements use classes to reuse css code blocks. meaning all elements needing to float left can have an attribute `class="float-left"` then css can have a single block that says `.float-left {float: left;}`. you can't use more than one class per element tho so use this wisely.
- `text-align: center;` and `margin: auto;` can both center things in the containing element