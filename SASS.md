# Learning SASS

## Preprocessor

- Additional steps before CSS
- Language on top of CSS such as SCSS
- Why we use SCSS instead of CSS
  - Is more powerful for reusing color, theme color throughout
  - Use variables throughout the code, it make readable and more flexible
  - Can use nested selected
  - Mixins can be defined, help reuse the code much more effectively, various frameworks and libraries for you so you don't have to build your own mixin
- Better code readability
- Powerful frameworks and libraries such as bootstrap right from inside SCSS code
- Understanding how CSS generation works

## SASS

- Syntactically Awesome Style-Sheets

```sass
.container
  float: left
  width: 100%
  p
    color: #333
```

## SCSS

- Sassy CSS
- Close to CSS language for people who already familiar with CSS
- In lecture we are using SCSS syntax

```scss
.container {
  float: left;
  width: 100%;
  p {
    color: #333;
  }
}
```
