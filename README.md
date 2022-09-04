# Mockups to Code

## Part 1 Setup & HTML

A big and normal struggle is to take a mockup and turn it into a website.

This site is inspired by: Hullo https://hullopillow.com

## Prerequisits

- HTML fundamentals
- CSS fundamentals (box model, selectors)
- CSS flexbox basics

If you want to try it yourself you will also need:

- Terminal/command line basics
- Text editor basics
- Git/GitHub basics

## Getting started

If you want to code along, you can

- fork and clone this repository
- navigate to the folder and type `open index.html` to open the file in the browser

## Start with the Mockup

![](./assets/mockups/mockup.png)

## Determine our Components and the Elements they are Made Up of

![](./assets/mockups/pillow-talk-marked-up.png)

## Start Coding

- `cd build`
- open `index.html` and `main.css` in your text editor
- open `index.html` in the browser, check that background color is set.

###### Important to Note

The website will be going through an awkward phase. It won't look good with just HTML, but as long as there is good structure and a plan it will come together!

## Add CSS Helpers and General styles

### CSS Helpers

### On the first line:

```CSS
@import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400&family=Raleway:wght@400;700&display=swap");
```

```CSS

/*********************************
* Build Helpers
*********************************/
/* give each element a border */
* {
  border: 1px solid mediumvioletred5;
}

/* shrink images for placement */
img {
  width: 100px;
}
```

```CSS
/*********************************
* General
*********************************/

body {
  background-color: snow;
  color: slategrey;
  margin: 20px 0;
  font-family: 'Baloo 2', cursive;
  text-align: center;
}

h1, h2, h3, h4, h5, h6 {
  margin: 0;
}


```

## Add Outer Containers

In the body

- `header`
- `div` with a class of `container` in that div
- `aside`
- `main`
- `footer`
