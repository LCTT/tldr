# csslint

> CSS 代码检查工具

- 检查单个 CSS 文件：

`csslint {{file.css}}`

- 检查多个 CSS 文件：

`csslint {{file1.css}} {{file2.css}} {{file3.css}}`

- 列出所有样式规则：

`csslint --list-rules`

- 检查时指定规则不符则视为错误（检查进程已非0失败码退出）：

`csslint --errors={{errors,universal-selector,imports}} {{file.css}}`

- 若指定规则不符则显示警告：

`csslint --warnings={{box-sizing,selector-max,floats}} {{file.css}}`

- 忽略指定规则不符：

`csslint --ignore={{ids,rules-count,shorthand}} {{file.css}}`

[#]: contributors: ([李峰])