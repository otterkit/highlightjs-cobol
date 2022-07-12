# COBOL - syntax highlighting for [highlight.js](https://highlightjs.org/)

![version](https://badgen.net/npm/v/highlightjs-cobol) ![license](https://badgen.net/badge/license/apache2.0)

COBOL is a statically typed, imperative, procedural programming language with support for object oriented programming. First released in 1959, it's still used today in many banking and financial companies due to it's decimal arithmetic, making it well suited for financial calculations. 

## Usage

Simply include the Highlight.js library in your webpage or Node app, then load this module.

### Static website or simple usage

Simply load the module after loading Highlight.js. You'll use the minified version found in the `dist` directory. This module is just a CDN build of the language, so it will register itself as the Javascript is loaded.

```html
<script type="text/javascript" src="/path/to/highlight.min.js"></script>
<script type="text/javascript" charset="UTF-8"
  src="/path/to/highlightjs-cobol/dist/cobol.min.js"></script>
<script type="text/javascript">
  hljs.highlightAll();
</script>
```

### Using directly from the UNPKG CDN

```html
<script type="text/javascript"
  src="https://unpkg.com/highlightjs-cobol/dist/cobol.min.js"></script>
```

- More info: <https://unpkg.com>

### With Node or another build system

If you're using Node / Webpack / Rollup / Browserify, etc, simply require the language module, then register it with Highlight.js.

```javascript
var hljs = require('highlightjs');
var hljsCOBOL = require('highlightjs-cobol');

hljs.registerLanguage("cobol", hljsCOBOL);
hljs.highlightAll();
```


## License

highlightjs-cobol is released under the Apache 2.0 License. See [LICENSE][1] file
for details.

### Author / Maintainer

Gabriel Gonçalves <ktsnowy@outlook.com>

## Links

- The official site for the Highlight.js library is <https://highlightjs.org/>.
- The Highlight.js GitHub project: <https://github.com/highlightjs/highlight.js>

[1]: https://github.com/otterkit/highlightjs-cobol/blob/master/LICENSE
