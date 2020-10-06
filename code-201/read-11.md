- background-repeat - says how you want a background image or pattern to repeat if at all.
  - repeat (default) - repeats image/pattern horizontaly and vertically for length of page and width of window.
  - repeat-x - repeats horizontally for width of window.
  - repeat-y - repeats vertically for the length of the page.
  - no repeat - only shows image/pattern once.
- background-attatchment - says whether the backgroundimage/pattern will scroll with the page (scroll) or stay in its original position (fixed).
- background-position - says where the image will appear onscreen when the image is not repeated.
  - left top - appears at top left of window.
  - left center - appears centered on the left side of the screen.
  - left bottom - appears on the bottom left of the window.
  - center top, right top ...
- background - combines all above rules into a 1:4 property to value.

```
body {
  background: black url("images/imag.jpg") no-repeat top right;
}
```

- sprites are images/buttons that change style or position when hovered over or clicked on (achieved through :hover or : active as a selector addition).
- css3 will have the ability to specify gradient with the background image property. What is a gradient?
- high contrast = more colorful?
- search engines look at what's on the page how many pages link to yours and their relevency plus some.
- on-page - things like url and text in code tells the browser what your site is about. think long and hard about these and put key words in:
  - title
  - url
  - h1,h2,h3...
  - text
  - link text
  - image alt tags
  - meta tags in head tags
- off-page - who links to your page, who your page links to and in-code text on links.
- google can help you track your pages analytics by giving you a piece of code to put on every page of your site.
  - it tracks when each page is loaded and allows you to view how your site is being used. It goes inside the head tags at the bottom.
  - it tracks total visits, visits by new people, views per page, pages per visit, ave time on site, date selector and can export the results for your use.
  - it tracks which pages are most used (visits/length), which pages people come in on, how often people leave from that page, and which pages people usually leave from the top.
  - it tracks references. meaning which pages link to you how many there are and how much traffic you get from those links.
- getElementByTagName exists in js. tag goes in single quotes in the parenthesis.