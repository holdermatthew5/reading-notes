## CSS Grid Garden

- `grid-column-start:` - decides which column the element starts in.
- `grid-column-end:` - decides which column the element ends in.
- `grid-columns: start end;`
- `grid-row-start:` - decides which row the element starts in.
- `grid-row-end:` - decides which row the element ends in.
- `grid-rows: start end;`
- `grid-area: row-start / column-start / row-end / column-end;`
- `grid-template-columns/rows:` - (columns or rows no '/') use below to decide size of columns/rows:
  - % - uses % of size of containing element to determine size.
  - em - I still don't know what exactly em is but it seems to be a consistent unit of measurement.
  - px - uses pixel count to determine size.
  - fr - divides remaining space between total sum of fr values and sizes columns/rows based on individual fr values.
- `grid-template: rows / columns;`
- `repeat(a, b)` function - (works with column and row) parens take value of:
  - a - how many times the size is to be repeated.
  - b - the size to be repeated.
- `order:` - takes 1, 0, or -1 to determine forward, original, or reverse ordering.
