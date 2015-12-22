# tachyons-font-style 1.1.0

Performance based css module.

#### Stats

162 | 8 | 8
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev tachyons-font-style
```

#### With Git

```
git clone https://github.com/tachyons-css/tachyons-font-style
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "tachyons-font-style";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/tachyons-font-style">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*

   FONT STYLE

*/
.fsn { font-style: normal; }
.i { font-style: italic; }
@media screen and (min-width: 48em) {
 .fsn-ns { font-style: normal; }
 .i-ns { font-style: italic; }
}
@media screen and (min-width: 48em) and (max-width: 64em) {
 .fsn-m { font-style: normal; }
 .i-m { font-style: italic; }
}
@media screen and (min-width: 64em) {
 .fsn-l { font-style: normal; }
 .i-l { font-style: italic; }
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

MIT

