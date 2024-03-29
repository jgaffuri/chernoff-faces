# Chernoff faces

This repository proposes some predefined [Chernoff faces](https://en.wikipedia.org/wiki/Chernoff_face) images.

There is currently one set of images representing faces by age (3 classes), sex (2 classes) and satisfaction level (3 classes). Which makes 3*2*3=12 images in total:

[<img src="https://jgaffuri.github.io/chernoff-faces/src/chernoff_sex_age_happy.svg" height="500" />](src/chernoff_sex_age_happy.svg)

## API

The images are named according to this pattern: **sax.png**, where:
- **s** is the sex, among **f** for female and **m** for male.
- **a** is the age, among **y** for younger, **o** for older and **m** for middle age.
- **x** is a number representing satisfaction level (the smile), **0** is the lowest level and **2** the highest.

For example, **fy2.png** is for a young girl with a large smile. See here: https://jgaffuri.github.io/chernoff-faces/out/v1/fy2.png
