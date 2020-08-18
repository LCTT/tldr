# decaffeinate

> 把你的 CoffeeScript 源代码转换为现 JavaScript

- 转换 CoffeeScript 文件为 JavaScript：

`decaffeinate {{path/to/file.coffee}}`

- 转换第 2 版本的 CoffeeScript 文件为 JavaScript：

`decaffeinate --use-cs2 {{path/to/file.coffee}}`

- 将 require 和 module.exports 转换为 import 和export：

`decaffeinate --use-js-modules {{path/to/file.coffee}}`

- 转换 CoffeeScript 允许命名输出：

`decaffeinate --loose-js-modules {{path/to/file.coffee}}`

[#]: contributors: ([王兴宇，Linux & BC])