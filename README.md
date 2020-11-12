# What is this?

invert.js is a function that will toggle invert on the colors of your whole page for a dummy dark/light mode switch.

# Installation w/ npm
with npm package manager:
`npm i toggleInvert`

with CDN, add this to the bottom of your html body:
`<script src="https://cdn.jsdelivr.net/gh/alexanderjarl91/invert@v4f7d7af/invert.js"</script`

then import `import { toggleInvert } from 'toggleInvert';` in your .js file

then add `.invert-mode {
  filter: invert() hue-rotate(180deg) brightness(105%) contrast(105%);
  -webkit-filter: invert() hue-rotate(180deg) brightness(105%) contrast(105%);
}` to your css

then make a button run toggleInvert() on click.




