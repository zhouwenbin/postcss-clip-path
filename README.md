# PostCSS polygon
[![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url] [![Dependency Status][daviddm-image]][daviddm-url]

[PostCSS][PostCSS] PostCSS plugin that adds `clip-path` and `shape-outside` value from [clippy](http://bennettfeely.com/clippy/).

```css
.foo {
  clip-path: triangle;
  shape-outside: triangle;
}
```

```css
.foo {
  clip-path: polygon(50% 0%, 0% 100%, 100% 100%);
  shape-outside: polygon(50% 0%, 0% 100%, 100% 100%);
}
```

--

### Value

* `triangle`
* `trapezoid`
* `parallelogram`
* `rhombus`
* `pentagon`
* `hexagon`
* `heptagon`
* `octagon`
* `nonagon`
* `decagon`
* `bevel`
* `rabbet`
* `leftArrow`
* `rightArrow`
* `leftPoint`
* `rightPoint`
* `leftChevron`
* `rightChevron`
* `star`
* `cross`
* `message`
* `close`
* `frame`

--

### Usage

```js
postcss([ require('postcss-polygon') ])
```

See [PostCSS][PostCSS] docs for examples for your environment.

--

### License

MIT © [zhouwenbin](http://zhouwenbin.com)

--

### Thanks

[clippy](http://bennettfeely.com/clippy/)

[npm-image]: https://badge.fury.io/js/postcss-polygon.svg
[npm-url]: https://npmjs.org/package/postcss-polygon
[travis-image]: https://travis-ci.org/zhouwenbin/postcss-polygon.svg?branch=master
[travis-url]: https://travis-ci.org/zhouwenbin/postcss-polygon
[daviddm-image]: https://david-dm.org/zhouwenbin/postcss-polygon.svg?theme=shields.io
[daviddm-url]: https://david-dm.org/zhouwenbin/postcss-polygon
[PostCSS]: https://github.com/postcss/postcss
