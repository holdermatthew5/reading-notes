## 404
- `transform: translate();` moves an element in a given direction. Looks like negatives go up and left while positives go right and down. since it targets all 3 h1s they move as a unit. this only takes affect while the animation is still being performed. This uses fixed positioning?
- `left:` and `right:` both move an element, but when they are moved there is a noticable effect on the other elements. I wounder if that's a property of animation or if it's a result of code changing in translation from readable code to 1s and 0s and into a visual effect.
- `animation` obviously causes the element to do something other than sit there on the page not moving from it's relative position.
- `4s` means 4 seconds (as in finish the animation in 4 seconds).
- `infinite` makes the animation start over everytime it ends and I'm assuming you can set a specific number of times.
- `range` and `size` are types of movement.
  - Range will force the element to change location as described in `@keyframes`.
  - size will keep the elment in its prescribed location while changing it's size as described in @keyframes.
- `0%`, `25%`, `50%`, `75%` and `100%` describe timing based on the length of time described in animation. changing these will make certain movements faster or slower, but does not affect the other parts of the animation (parts being stages in the animation, so moving down and left is 1 stage, moving up and right is a second stage, etc.). keeping these the same for each element ensures a coordinated appearance.
- changing `left` and `right` values in the curly braces next to the above properties determines where the element will land for any given stage. and `font-size` will do it's normal thing.
- I am curious as to how the body selector is taking affect at all given there are no body tags. Maybe it's a default of some sort for the site.
## transform
- has prefixes which are recommended for use by learners (-webkit-transform, -moz-transform, -o-transform).
- rotate - rotates an image by prescribed degrees in `rotate(20deg)`.
- scaleX - decimal representing percent original size in x axis.
- scaleY - scale x in y axis instead of x.
- scale(scaleX, scaleY).
- translate - moves element left/right in 'px' and up/down in % (`translateX(-10px);`, `translateY(25%);`, `translate(-10px, 25%);`).
- skew in same fassion as above italicizes an element (box to rhombus, equilateral to right).
- combining transforms (rotate, scale, etc.) is perfectly acceptable, but don't put a comma.
- transform origin describes a location on the element in x, y % to center any other transformative properties around (essentially creates a new center).
- perspective changes directional view of element, so it can look like you're viewing it from each side (spins like a top not a pinwheel). this is done with `perspective(200px)`. adding a rotate can make it look like it's leaning forward or backward. Does it actually just turn the element into a trapezoid to immitate canting? does it both turn it into a trapezoid and spin it? 
- adding perspective to a parent element will add perspective to each individual child element and not the parent element similar to `text-align: center;`
- perspective-origin makes an unaffected spot in the form of xy graph points.
- 3D rotating:
  - rotateX - put a bar throught the middle from side to side then push the top or bottom.
  - rotateY - put a bar through the middle from top to bottom then push either side.
  - rotateZ - stab a pole through the center and push the corners up/down and side (diagonally).
# notes on notes: alot of transform could be wrong. After looking at the actual css used in the example images I see that there are other properties affecting it that aren't described in the text, so until I figure out what each of those is doing none of this can be considered accurate.