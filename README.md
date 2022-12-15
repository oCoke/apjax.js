# APjax.js

> A pure no-refresh tool.

> For a Chinese document, see => [README_CN.md](https://github.com/oCoke/apjax.js/blob/master/README_CN.md)

## How to use

### Convert Links

When the page finishes loading, you should try to convert links on the page to `apjax();`.

**This is important!!**

```js
$apjax.cvt(..options); // true

options = {
  // elements with links, default is 'body'
  elements: ".app",
  // convert the link with hash(#), default is false.
  cvtHash: false,
  // match RegExp, default is null,
  reg: /blog/,
}
```
