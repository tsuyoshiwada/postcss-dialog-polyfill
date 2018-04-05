# @tsuyoshiwada/postcss-dialog-polyfill

> PostCSS plugin which add selector needed by [dialog-polyfill](https://github.com/GoogleChrome/dialog-polyfill)

---

> **This is the [postcss-dialog-polyfill](https://github.com/komachi/postcss-dialog-polyfill) Fork project.**

Bug fix included in the original package.  
This package is unnecessary when PR ([#1](https://github.com/komachi/postcss-dialog-polyfill/pull/2)) is merged :+1:

---

```css
/* Input */
.test1::backdrop {
  background-color: #fff;
}
```

```css
/* Output */
.test1::backdrop {
  background-color: #fff;
}
.test1 + .backdrop {
  background-color: #fff;
}
```

## Installation

```bash
$ npm i @tsuyoshiwada/postcss-dialog-polyfill -D
```

## Usage

Check out [PostCSS documentation](https://github.com/postcss/postcss#usage) on how to use PostCSS plugins.
