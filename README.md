<h1 align="center">reeeset</h1>

<p align="center">
  A slightly opinionated CSS reset.
</p>

### Why?
Normalize is made to make browsers consistent. This is cool, but in the real world margins, padding, box-sizing, are all really annoying things. The easiest way to deal with it is to simply reset them all.

### "But I like building on top of browser defaults"
REEEEEEEEEEEEEE GET OUT NORMIE!!!!

<img src="https://i.imgur.com/fTtXSaF.jpg" height="120px">

### Features
- [Normalize.css](https://necolas.github.io/normalize.css)
- `*` to remove margin, padding, and add [box-sizing: border-box](http://www.paulirish.com/2012/box-sizing-border-box-ftw)
- Reset Normalize margins/padding (`<h1>`, `<figure>`, and `<fieldset>` only)
- Eliminate [page bounce](https://css-tricks.com/eliminate-jumps-in-horizontal-centering-by-forcing-a-scroll-bar) with `overflow-y: scroll`
- Clearfix `<body>`
- `max-width: 100%` typically overflowing elements to [make them responsive](http://unstoppablerobotninja.com/entry/fluid-images)
- Add generic styles to [H5BP .browserupgrade](https://github.com/h5bp/html5-boilerplate/blob/master/dist/index.html#L18-L20)
- Very basic typography
  - Beautiful [system fonts](https://www.smashingmagazine.com/2015/11/using-system-ui-fonts-practical-guide)
  - 1.5 `line-height`
  - `margin-bottom` on block elements
  - Generic heading sizes/line-height
  - IE9+ sized in rems for [easy responsive typography](http://webdesign.tutsplus.com/tutorials/the-lazy-persons-guide-to-responsive-typography--cms-22822)

### Installation

##### Bower
`bower install --save-dev reeeset`

##### Node
`npm install --save-dev reeeset`

### Usage
Put `@import 'reeeset.min.css';` at the top of the first stylesheet you're loading (the first one to appear in `<head>`). If you want sourcemap support just dump reeeset.min.css.map into the same directory.

### Browser Support
- IE8+

### Contribute
If you notice I'm doing anything insanely wrong, please make an issue so we can discuss it and I can fix it. Resetting margins/padding/border-box isn't up for debate.
