# gofmt

> Go 语言源代码格式工具

- 格式化指定文件并在控制台打印出来：

`gofmt {{source.go}}`

- 格式化指定文件并替换掉原文件：

`gofmt -w {{source.go}}`

- 格式化、简化指定文件，并替换原文：

`gofmt -s -w {{source.go}}`

- 打印所有（包括虚假）错误：

`gofmt -e {{source.go}}`

[#]: contributors: ([潘潘]，[李峰])