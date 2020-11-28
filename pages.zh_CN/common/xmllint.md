# xmllint

> XML 文件解析器和语法检查器，支持 XPath - 一种用来导航 XML 树的语法

- 返回名称为 foo 的节点（标签）：

`xmllint --xpath "//{{foo}}" {{source_file.xml}}`

- 以字符串形式返回第一个名称为 foo 的节点的内容：

`xmllint --xpath "string(//{{foo}})" {{source_file.xml}}`

- 返回指定 html 文件里第二个锚点元素的 href 属性：

`xmllint --html --xpath "string(//a[2]/@href)" webpage.xhtml`

- 缩进指定 XML 文件方便阅读：

`xmllint --format {{source_file.xml}}`

- 检查指定 XML 文件是否符合其 DOCTYPE 声明：

`xmllint --valid {{source_file.xml}}`

- 检查指定 XML 文件是否符合线上的文档类型声明规范：

`xmllint --dtdvalid {{URL}} {{source_file.xml}}`

[#]: contributors: ([李峰])