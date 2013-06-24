# connect-fonts-londrinasketch

Londrina Sketch fontpack for [connect-fonts](https://github.com/shane-tomlinson/connect-fonts).

## Usage

1. Include [connect-fonts](https://github.com/shane-tomlinson/connect-fonts) in a node module.
```js
const font_middleware = require("connect-fonts");
```

2. Include the font packs that you want to serve.
```js
const font_pack  = require("connect-fonts-londrinasketch");
```

3. Add a middleware by calling the `setup` function.
```js
    app.use(font_middleware.setup({
      fonts: [ font_pack ],
      allow_origin: "https://exampledomain.com"
    }));
```

4. Add a link tag to include the font CSS.
```html
<link href="/londrinasketch-regular/fonts.css" type="text/css" rel="stylesheet"/ >
```


Available fonts:
* londrinasketch-regular

Locale-optimised font sets can be served by specifying the locale in the fonts.css URL.
```html
<link href="/latin/londrinasketch-regular/fonts.css" type="text/css" rel="stylesheet"/ >
```

Available subsets:
* latin

5. Set your CSS up to use the new font by using the "Londrina Sketch" font-family.
```
    body {
      font-family: 'Londrina Sketch', 'sans-serif', 'serif';
    }
```

## Font Info
Londrina Sketch

* Copyright: Copyright (c) 2011 by Marcelo Magalhaes (marcelomagalhaes.net), with Reserved Font Name "Londrina"
* Trademark: Londrina is a trademark of Marcelo Magalhaes.
* Designer: Marcelo Magalhaes
* Designer URL: www.marcelomagalhaes.net 
* Vendor: Marcelo Magalhaes
* Vendor URL: www.tipospereira.com

## Development Info
* Homepage: https://github.com/shane-tomlinson/connect-fonts-londrinasketch
* Repo: https://github.com/shane-tomlinson/connect-fonts-londrinasketch

## Author
* Shane Tomlinson
* shane@shanetomlinson.com
* stomlinson@mozilla.com
* set117@yahoo.com
* https://shanetomlinson.com
* https://github.com/shane-tomlinson
* https://github.com/stomlinson
* @shane_tomlinson


## License

Software: Licenced under version 2.0 of the MPL

  https://www.mozilla.org/MPL/

Fonts: Licensed under version 1.1 of the SIL Open Font License

  http://scripts.sil.org/OFL

