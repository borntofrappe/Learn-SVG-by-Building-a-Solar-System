# Size the `svg` element

In the previous challenge you included an `<svg>` element, but nothing seemed to change on the page. However, if you were to analyse the DOM in the developer console you'd already find a rectangle making up the SVG canvas.

Note: we've added a class of `highlight` to highlight the element with a simple CSS animation.

By default, the `<svg>` element has a width of `300` pixels and a height of `100` pixels, but you can change these values with the `width` and `height` attributes.

Attributes are included in SVG elements like any other HTML element.

```HTML
<svg attributeName="attributeValue">

</svg>
```

## Task

Add the `width` and `height` attributes to make the `<svg>` element a square `100` pixels wide and `100` pixels tall.

## Notes

- the stylesheet includes a basic animation to highlight the `<svg>` element. This animation is based on a class, included by default to immediately visualize the SVG canvas.

- pixel values (as in `width="100px`) can be accepted as well as unitless values (as in `width="100"`). The difference will be highlighted in a later challenge discussing the `viewBox` attribute.
