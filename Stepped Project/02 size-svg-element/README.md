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

Add the `width` and `height` attributes to make the `<svg>` element a rectangle `150` pixels wide and `100` tall.

## Notes

- CSS includes an animation to highlight the dimensions of the `<svg>` element.

- unit-less should be accepted, as they produce the same result, but they are also and better discussed with regards to the `viewBox` attribute. Given the intricacies of the attribute, it is convenient to first get the camper acclamated with the SVG syntax sans `viewBox`.
