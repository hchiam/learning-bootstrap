# Learning Bootstrap 4 (+SCSS)

Just one of the things I'm learning. <https://github.com/hchiam/learning>

<https://www.youtube.com/watch?v=hnCmSXCZEpU>

<https://coursetro.com/posts/code/130/Learn-Bootstrap-4-Final-in-2018-with-our-Free-Crash-Course>

```bash
node --version
npm init -y
npm install gulp@3.9.1 browser-sync gulp-sass --save-dev
# note: gulp v4 is very different!
npm install bootstrap jquery popper.js --save
mkdir src src/assets src/css src/js src/scss
touch src/index.html
touch src/scss/styles.scss
touch gulpfile.js
gulp
```

## Notes

- Bootstrap has cool utility classes to avoid creating repetitive CSS.
- Using npm and SCSS, you include only what you need; avoid getting the whole kitchen sink Bootstrap loaded onto your site.
- The YouTube tutorial also uses SCSS to customize beyond the cookie cutter Bootstrap styling.
- Just learn to use the documentation! There's so many elements, style customizations, and listeners that already exist to cover many use cases. I didn't know about the utility classes and `data-` attributes that you can simply add in HTML! Examples: <https://getbootstrap.com/docs/4.4/utilities/spacing/> or <https://getbootstrap.com/docs/4.4/getting-started/theming/>

## Example dropdown and table

<https://codepen.io/hchiam/pen/NWGPwPy>
