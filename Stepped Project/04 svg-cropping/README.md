# Understand the `<svg>` element: cropping

In the previous challenge you were tasked to draw a circle with specific attributes. If you tried different values for the size or position of the shape, you migth have experienced something exotic: as the shape moves outside of the `<svg>` element, it gets cropped.

This is to be expected: _anything_ falling outside of the region described bythe `<svg>` element is literally cropped from view.

## Task

Modify the radius or the coordinates of the circle so that the shape is cropped by the canvas.

## Notes

- accept any value which crops the shape (any radius greater than 50 for instance).

- the class of `.highlight` is re-introduced to highlight the `<svg>` element and how the circle gets cropped.