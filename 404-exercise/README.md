# 404 Page Exercise
Create a 404 page with HTML and pure CSS (no Javascript required).

## Tips
- Try to match the example as closely as possible — play with colors, sizing, fonts, margins/padding, etc. Inspect the example for guidance.
- Google is your friend!

## Instructions

### Requirements:
- Change the background to #05092b
- Import a Google Font called Roboto! It comes pre-loaded with 2 font weights: 500 (regular) and 900 (bold). Place the following tag in the <head> of your html doc:
  `<link href="https://fonts.googleapis.com/css?family=Roboto:500,900&display=swap" rel="stylesheet">`
- Reference it in your CSS by adding the following to the body element, like so:
```
  body {
    font-family: 'Roboto', sans-serif;
  }
```
- Add an `<h1>` with the text "404"
- Add an `<h2>` with the text "You look super lost, space cadet."
- Add the space cadet image to the top-right of the page
- Make scrolling impossible
- Add the planet image to the bottom-left of the page
- Add a button with the text "Return to Earth" that links to a *new tab* that opens "https://solarsystem.nasa.gov/planets/earth/overview/"

### Bonus:
- Change the background color of the button to #2f2ffc on hover (Extra points for a smooth transition between colors)
- Make your space cadet spin in place (Hint: you can do this with CSS animation @keyframes)