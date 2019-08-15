# Understand the `<svg>` element: coordinate system

If you modified the `cx` and `cy` coordinates, you might have noticed another trait of SVG syntax:

- greater `cx` values push the circle towards the _right_ of the canvas;

- greater `cy` values push the circle towards the _bottom_ of the canvas;

This is because of the SVG coordinate system, which starts at (0, 0) in the top left corner of the `<svg>` element.

```text
(0, 0)            (1,0)

(0, 1)            (1, 1)
```

## Task

Modify the coordinates of the circle to highlight the coordinate system.

## Notes

- accept any `cx` or `cy` value different from the default `(50, 50)`