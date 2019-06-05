# [Final Project](https://codepen.io/borntofrappe/full/gJpKxx)

This folder is meant to house the complete project **Learn SVG by Building a Solar System**. As the project is still in development however, it functions as a central location for what will _inevitably_ become the final version. Here you find the file(s) ultimately created by campers as they go through the SVG challenges.

## Project Structure

The idea is to have the project developed in steps. Ultimately, it is possible to distill the end result in three main files.

- `index.html` houses the final version of the project. It is developed in steps, with challenges introducing one concept at a time (or reinforcing an existing concept);

- `rocket.html` describes the SVG syntax for the rocket. It is developed independently of the main markup file, to explain the commands of the `d` attribute. Once complete, it is incorporated in `index.html` to furthermore highlight how `<svg>` elements can be nested;

- `style.css` details a few `property: value` pairs meant to center and scale the `<svg>` element. The markup file `index.html` will benefit from this stylesheet along the development of the project. `rocket.html`, given its limited scope, might not need the same reference.