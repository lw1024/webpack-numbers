# webpack-numbers

Webpack library 学习示例。可以将数字 1 到 5 转换为文本表示，反之亦然，例如将 2 转换为 'two'。

# 该 library 的使用方式如下：

```js
// ES2015 模块引入
import * as webpackNumbers from 'webpack-numbers'
// CommonJS 模块引入
var webpackNumbers = require('webpack-numbers')
// ...
// ES2015 和 CommonJS 模块调用
webpackNumbers.wordToNum('Two')
// ...
// AMD 模块引入
require(['webpackNumbers'], function(webpackNumbers) {
  // ...
  // AMD 模块调用
  webpackNumbers.wordToNum('Two')
  // ...
})
```

# 用户还可以通过 script 标签来加载和使用此 library：

```html
<!DOCTYPE html>
<html>
  ...
  <script src="https://unpkg.com/webpack-numbers"></script>
  <script>
    // ...
    // 全局变量
    webpackNumbers.wordToNum('Five')
    // window 对象中的属性
    window.webpackNumbers.wordToNum('Five')
    // ...
  </script>
</html>
```
