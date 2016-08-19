# css-word-wrap 0.0.6

Css module of single purpose classes for word wrap

#### Stats

183 | 12 | 12
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-word-wrap
```

#### With Git

```
git clone https://github.com/tachyons-css/css-word-wrap
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-word-wrap";
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
<link rel="stylesheet" href="path/to/module/css/css-word-wrap">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   WORD WRAP
*/
.wwn { word-wrap: normal; }
.wwbw { word-wrap: break-word; }
.wwi { word-wrap: inherit; }
@media screen and (min-width: 48em) {
 .wwn-ns { word-wrap: normal; }
 .wwbw-ns { word-wrap: break-word; }
 .wwi-ns { word-wrap: inherit; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .wwn-m { word-wrap: normal; }
 .wwbw-m { word-wrap: break-word; }
 .wwi-m { word-wrap: inherit; }
}
@media screen and (min-width: 64em) {
 .wwn-l { word-wrap: normal; }
 .wwbw-l { word-wrap: break-word; }
 .wwi-l { word-wrap: inherit; }
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
