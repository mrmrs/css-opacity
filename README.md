# css-opacity 0.0.6

Css module of single purpose classes for opacity

#### Stats

275 | 40 | 40
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-opacity
```

#### With Git

```
git clone https://github.com/tachyons-css/css-opacity
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-opacity";
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
<link rel="stylesheet" href="path/to/module/css/css-opacity">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
  OPACITY
*/
.o-10 { opacity: .1; }
.o-20 { opacity: .2; }
.o-30 { opacity: .3; }
.o-40 { opacity: .4; }
.o-50 { opacity: .5; }
.o-60 { opacity: .6; }
.o-70 { opacity: .7; }
.o-80 { opacity: .8; }
.o-90 { opacity: .9; }
.o-full { opacity: 1; }
@media screen and (min-width: 48em) {
 .o-10-ns { opacity: .1; }
 .o-20-ns { opacity: .2; }
 .o-30-ns { opacity: .3; }
 .o-40-ns { opacity: .4; }
 .o-50-ns { opacity: .5; }
 .o-60-ns { opacity: .6; }
 .o-70-ns { opacity: .7; }
 .o-80-ns { opacity: .8; }
 .o-90-ns { opacity: .9; }
 .o-full-ns { opacity: 1; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .o-10-m { opacity: .1; }
 .o-20-m { opacity: .2; }
 .o-30-m { opacity: .3; }
 .o-40-m { opacity: .4; }
 .o-50-m { opacity: .5; }
 .o-60-m { opacity: .6; }
 .o-70-m { opacity: .7; }
 .o-80-m { opacity: .8; }
 .o-90-m { opacity: .9; }
 .o-full-m { opacity: 1; }
}
@media screen and (min-width: 64em) {
 .o-10-l { opacity: .1; }
 .o-20-l { opacity: .2; }
 .o-30-l { opacity: .3; }
 .o-40-l { opacity: .4; }
 .o-50-l { opacity: .5; }
 .o-60-l { opacity: .6; }
 .o-70-l { opacity: .7; }
 .o-80-l { opacity: .8; }
 .o-90-l { opacity: .9; }
 .o-full-l { opacity: 1; }
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

