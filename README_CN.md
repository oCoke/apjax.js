# APjax.js

> 纯粹的无刷新工具。

## 如何使用

### 转换链接

当页面完成加载时，您应该尝试将页面上的链接转换为 `apjax();`。

**这个很重要！！**

```js
$apjax.cvt(..options); // true

options = {
  // 需要转换链接的元素, default is 'body'
  elements: ".app",
  // 是否转换带 # 的链接, default is false.
  cvtHash: false,
  // 需要匹配的正则, default is null,
  reg: /blog/,
}
```
