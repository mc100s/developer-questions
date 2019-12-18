# Frontend

These questions takes inspiration from this: https://roadmap.sh/frontend/latest

## HTML
### What is the difference between `<div>` and `<h1>`?
Both of them, by default, are blocks, but h1 has a semantic meaning. It makes the developer experience eaiser and the same for the search engine robots, that will understand it is the main content of the page.

### True or false: A `<div>` can have more than one class.
### What are some of the semantic elements added with HTML 5 and how do they work?

## CSS
### How does this selector mean: `foo bar`?
```html
<foo>
    ...
        <bar>
```
### How does this selector mean: `foo.bar.toto`?
```html
<foo class="bar">
```
### How does this selector mean: `foo .bar`?
```html
<foo>
    ...
        <tag class="bar">
```
### How does this selector mean: `foo > .bar`?
```html
<foo>
    <tag class="bar">
```
### What is the difference between `rem` and `em`?
2rem = 2 * font-size of the html
2em = 2 * font-size of the parent

### How does block-elements and inline-elements differ?

## Basics of JavaScript
### In JS, how can you select the elemet with the id `root`?
```js
document.getElementById("root")
document.querySelector('#hr_v2')
```
### In JS, how can you select all elements with the class `apple`?
```js
document.getElementsByClassName("apple") // => collection
document.querySelectorAll('.apple') // => list
```
### In JS, how can you select the 1st element with the class `apple`?
```js
document.getElementsByClassName("apple")[0] // => 1 element
document.querySelector('.apple') // => 1 element
```

### In JS, how can you toggle the class `visible` of all elements with the class `banana`?
```js
document.querySelectorAll('.banana')
    .forEach(element => element.classList.toggle('visible'))
```

## CSS Pre-processors
### How to declare a variable with SCSS?

## CSS Frameworks
### With Bootstrap, how to create a grid with 3 column the same size?

## CSS Architecture
### By following the BEM convention, how can how create a search component composed of an input and an image of a magnifier glass?
```html
<div class="search search--dark">
    <input class="search__input" />
    <img class="search__img" />
</div>
```
More info: http://getbem.com/naming/

## Build Tools
### Can you create a React project with Prettier and ES Lint configured?

## Frontend Framework
### Can you give me the list of the main lifecycles method in a React component?

## Testing your Apps
### What are the different kind of tests?
[](https://miro.medium.com/max/2400/1*S-WQ9KwM7kkmwKWy41SPYw.png)
Explanation here: https://medium.com/@Colin_But/define-testing-strategy-using-the-testing-pyramid-1dabee37e823

## Extra
### What JavaScript library is required to implement JavaScript widgets such as Carousel, Collapse and Scrollspy

