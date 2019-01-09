# SVG circle animation with CSS and JS, style awwwards.com data circles
This project shows how to create the circle animation shown in awwwards.com

## Important properties used for SVGs elements
**stroke-dasharray**: creates a patron of dashes and gaps (known as dash array) that fits this way:
  *-one value*: equal lengths values for dashes and gaps
  *-two values*: first value to dashes length, second to gaps length
  *-three values*: dash length, gap length, dash length and all alternates
  *-four values*: dash length, gap length, dash length and gap length

**stroke-dashoffset**: offsets the origin of the dash array. Very useful to hide some parts of the dashes. The staring offset point is located in (rectangular coordinates) (1, 0), or the left center of the element. To put it in the top, rotate the element -90 degrees.

**fill**: determines de color for a SVG element. The value none applies for no-color.

**stroke-width**: determines de stroke width for a SVG element. Numerical

**stroke-opacity**: determines de stroke opacity for a SVG element. Numerical

**stroke-linecap**: determines de stroke start and end shape for a SVG element. Values permitted are 'butt (default)', 'square' and 'round'.
