# modernizr-framed

The extension detects if page loaded inside frame and if it does AND there is an global option `NO_FRAMED` is set to `true` 
then script loads the page inside root window.

## Instalation

```bash
npm install modernizr-framed --save
```

or 

```bash
yarn add modernizr-framed
```

or

```bash
bower install modernizr-framed
```

## Usage

```html
<script>
window.NO_FRAMED = true;
</script>

<script src="path/to/modernizr.js"></script>
<script src="https://unpkg.com/modernizr-framed@1.0.2/modernizr-framed.js"></script>
```


## License

modernizr-framed is released under the Apache-2.0 license.

## Donate

[![](https://img.shields.io/badge/patreon-donate-yellow.svg)](https://www.patreon.com/red_rabbit)
[![](https://img.shields.io/badge/flattr-donate-yellow.svg)](https://flattr.com/profile/red_rabbit)
