# css-cursors 0.0.7

Css module of single purpose classes for cursors

#### Stats

781 | 136 | 136
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-cursors
```

#### With Git

```
git clone https://github.com/mrmrs/css-cursors
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-cursors";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/mrmrs/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-cursors">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   CURSORS
*/
.cursor-auto { cursor: auto; }
.cursor-default { cursor: default; }
.cursor-none { cursor: none; }
.cursor-context-menu { cursor: context-menu; }
.cursor-help { cursor: help; }
.cursor-pointer { cursor: pointer; }
.cursor-progress { cursor: progress; }
.cursor-wait { cursor: wait; }
.cursor-cell { cursor: cell; }
.cursor-crosshair { cursor: crosshair; }
.cursor-text { cursor: text; }
.cursor-vertical-text { cursor: vertical-text; }
.cursor-alias { cursor: alias; }
.cursor-copy { cursor: copy; }
.cursor-move { cursor: move; }
.cursor-no-drop { cursor: no-drop; }
.cursor-not-allowed { cursor: not-allowed; }
.cursor-e-resize { cursor: e-resize; }
.cursor-n-resize { cursor: n-resize; }
.cursor-ne-resize { cursor: ne-resize; }
.cursor-nw-resize { cursor: nw-resize; }
.cursor-s-resize { cursor: s-resize; }
.cursor-se-resize { cursor: se-resize; }
.cursor-sw-resize { cursor: sw-resize; }
.cursor-w-resize { cursor: w-resize; }
.cursor-ew-resize { cursor: ew-resize; }
.cursor-ns-resize { cursor: ns-resize; }
.cursor-nesw-resize { cursor: nesw-resize; }
.cursor-nwse-resize { cursor: nwse-resize; }
.cursor-col-resize { cursor: col-resize; }
.cursor-row-resize { cursor: row-resize; }
.cursor-all-scroll { cursor: all-scroll; }
.cursor-zoom-in { cursor: zoom-in; }
.cursor-zoom-out { cursor: zoom-out; }
@media screen and (min-width: 48em) {
 .cursor-auto-ns { cursor: auto; }
 .cursor-default-ns { cursor: default; }
 .cursor-none-ns { cursor: none; }
 .cursor-context-menu-ns { cursor: context-menu; }
 .cursor-help-ns { cursor: help; }
 .cursor-pointer-ns { cursor: pointer; }
 .cursor-progress-ns { cursor: progress; }
 .cursor-wait-ns { cursor: wait; }
 .cursor-cell-ns { cursor: cell; }
 .cursor-crosshair-ns { cursor: crosshair; }
 .cursor-text-ns { cursor: text; }
 .cursor-vertical-text-ns { cursor: vertical-text; }
 .cursor-alias-ns { cursor: alias; }
 .cursor-copy-ns { cursor: copy; }
 .cursor-move-ns { cursor: move; }
 .cursor-no-drop-ns { cursor: no-drop; }
 .cursor-not-allowed-ns { cursor: not-allowed; }
 .cursor-e-resize-ns { cursor: e-resize; }
 .cursor-n-resize-ns { cursor: n-resize; }
 .cursor-ne-resize-ns { cursor: ne-resize; }
 .cursor-nw-resize-ns { cursor: nw-resize; }
 .cursor-s-resize-ns { cursor: s-resize; }
 .cursor-se-resize-ns { cursor: se-resize; }
 .cursor-sw-resize-ns { cursor: sw-resize; }
 .cursor-w-resize-ns { cursor: w-resize; }
 .cursor-ew-resize-ns { cursor: ew-resize; }
 .cursor-ns-resize-ns { cursor: ns-resize; }
 .cursor-nesw-resize-ns { cursor: nesw-resize; }
 .cursor-nwse-resize-ns { cursor: nwse-resize; }
 .cursor-col-resize-ns { cursor: col-resize; }
 .cursor-row-resize-ns { cursor: row-resize; }
 .cursor-all-scroll-ns { cursor: all-scroll; }
 .cursor-zoom-in-ns { cursor: zoom-in; }
 .cursor-zoom-out-ns { cursor: zoom-out; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .cursor-auto-m { cursor: auto; }
 .cursor-default-m { cursor: default; }
 .cursor-none-m { cursor: none; }
 .cursor-context-menu-m { cursor: context-menu; }
 .cursor-help-m { cursor: help; }
 .cursor-pointer-m { cursor: pointer; }
 .cursor-progress-m { cursor: progress; }
 .cursor-wait-m { cursor: wait; }
 .cursor-cell-m { cursor: cell; }
 .cursor-crosshair-m { cursor: crosshair; }
 .cursor-text-m { cursor: text; }
 .cursor-vertical-text-m { cursor: vertical-text; }
 .cursor-alias-m { cursor: alias; }
 .cursor-copy-m { cursor: copy; }
 .cursor-move-m { cursor: move; }
 .cursor-no-drop-m { cursor: no-drop; }
 .cursor-not-allowed-m { cursor: not-allowed; }
 .cursor-e-resize-m { cursor: e-resize; }
 .cursor-n-resize-m { cursor: n-resize; }
 .cursor-ne-resize-m { cursor: ne-resize; }
 .cursor-nw-resize-m { cursor: nw-resize; }
 .cursor-s-resize-m { cursor: s-resize; }
 .cursor-se-resize-m { cursor: se-resize; }
 .cursor-sw-resize-m { cursor: sw-resize; }
 .cursor-w-resize-m { cursor: w-resize; }
 .cursor-ew-resize-m { cursor: ew-resize; }
 .cursor-ns-resize-m { cursor: ns-resize; }
 .cursor-nesw-resize-m { cursor: nesw-resize; }
 .cursor-nwse-resize-m { cursor: nwse-resize; }
 .cursor-col-resize-m { cursor: col-resize; }
 .cursor-row-resize-m { cursor: row-resize; }
 .cursor-all-scroll-m { cursor: all-scroll; }
 .cursor-zoom-in-m { cursor: zoom-in; }
 .cursor-zoom-out-m { cursor: zoom-out; }
}
@media screen and (min-width: 64em) {
 .cursor-auto-l { cursor: auto; }
 .cursor-default-l { cursor: default; }
 .cursor-none-l { cursor: none; }
 .cursor-context-menu-l { cursor: context-menu; }
 .cursor-help-l { cursor: help; }
 .cursor-pointer-l { cursor: pointer; }
 .cursor-progress-l { cursor: progress; }
 .cursor-wait-l { cursor: wait; }
 .cursor-cell-l { cursor: cell; }
 .cursor-crosshair-l { cursor: crosshair; }
 .cursor-text-l { cursor: text; }
 .cursor-vertical-text-l { cursor: vertical-text; }
 .cursor-alias-l { cursor: alias; }
 .cursor-copy-l { cursor: copy; }
 .cursor-move-l { cursor: move; }
 .cursor-no-drop-l { cursor: no-drop; }
 .cursor-not-allowed-l { cursor: not-allowed; }
 .cursor-e-resize-l { cursor: e-resize; }
 .cursor-n-resize-l { cursor: n-resize; }
 .cursor-ne-resize-l { cursor: ne-resize; }
 .cursor-nw-resize-l { cursor: nw-resize; }
 .cursor-s-resize-l { cursor: s-resize; }
 .cursor-se-resize-l { cursor: se-resize; }
 .cursor-sw-resize-l { cursor: sw-resize; }
 .cursor-w-resize-l { cursor: w-resize; }
 .cursor-ew-resize-l { cursor: ew-resize; }
 .cursor-ns-resize-l { cursor: ns-resize; }
 .cursor-nesw-resize-l { cursor: nesw-resize; }
 .cursor-nwse-resize-l { cursor: nwse-resize; }
 .cursor-col-resize-l { cursor: col-resize; }
 .cursor-row-resize-l { cursor: row-resize; }
 .cursor-all-scroll-l { cursor: all-scroll; }
 .cursor-zoom-in-l { cursor: zoom-in; }
 .cursor-zoom-out-l { cursor: zoom-out; }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

ISC
