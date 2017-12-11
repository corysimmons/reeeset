<h1 align="center">reeeset</h1>

<p align="center">
  A <i>slightly</i> opinionated CSS reset.
</p>

### Why?

[![Greenkeeper badge](https://badges.greenkeeper.io/corysimmons/reeeset.svg)](https://greenkeeper.io/)
Normalize is made to make browsers consistent. This is cool, but in the real world margins, padding, box-sizing, are all really annoying things. The easiest way to deal with it is to simply reset them all.

Sanitize.css does something similar and is fairly popular. I might assimilate Sanitize over Normalize in the future, but for now Normalize seems a bit more stable.

This is just my personal-preference layer on top of resets.

### "But I like building on top of browser defaults"
REEEEEEEEEEEEEE GET OUT NORMIE!!!!

<img src="https://i.imgur.com/fTtXSaF.jpg" height="120px">

### Features
- [Normalize.css](https://necolas.github.io/normalize.css)
- `*` to remove margin, padding, and inherit [box-sizing: border-box](http://www.paulirish.com/2012/box-sizing-border-box-ftw)
- Reset Normalize's sneaky margins/padding (`<h1>`, `<figure>`, and `<fieldset>`)
- `max-width: 100%` typically overflowing elements to [make them responsive](http://unstoppablerobotninja.com/entry/fluid-images)
- Add generic styles to [H5BP .browserupgrade](https://github.com/h5bp/html5-boilerplate/blob/master/dist/index.html#L18-L20)
- Basic/simple typography
  - Beautiful/fast [system fonts](https://www.smashingmagazine.com/2015/11/using-system-ui-fonts-practical-guide)
  - 1.666 `line-height` (not because I worship Satan, but because of some rule-of-thirds design thingy)
  - Generic heading sizes/line-height
  - Sized in rems for [easy responsive typography](http://webdesign.tutsplus.com/tutorials/the-lazy-persons-guide-to-responsive-typography--cms-22822)
  - **Protip** Use the 'Lobotomized Owl' technique on content areas. Example:

```css
article * + * {
  margin-top: 1rem;
}
```

### Installation

**HTTP2:**

```html
<link rel="stylesheet" href="https://unpkg.com/reeeset">
<link rel="stylesheet" href="css/your_styles.css">
```

**HTTP1:**

```css
@import 'https://unpkg.com/reeeset';

/* your styles... */
```

unpkg is legit (well-known OSS contributor backed by a large company), but if you don't trust the longevity of free CDNs on production work (you really shouldn't) just copy/paste the contents of [dist/reeeset.min.css](dist/reeeset.min.css) to your file-system.
