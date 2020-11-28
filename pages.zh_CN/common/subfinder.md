# subfinder

> 子域发现工具，用于发现一个网站的有效子域
> 设计为被动式框架对 bug 悬赏和安全的脆弱性测试有用

- 发现一个特定域名的子域：

`subfinder -d {{example.com}}`

- 仅显示特定的子域：

`subfinder --silent -d {{example.com}}`

- 使用暴力破解方式来发现子域：

`subfinder -d {{example.com}} -b`

- 移除通配子域：

`subfinder -nW -d {{example.com}}`

- 使用给定的解析器列表（用逗号分隔）：

`subfinder -r {{8.8.8.8}},{{1.1.1.1}} -d {{example.com}}`

[#]: contributors: ([王興與·區塊鏈·Linux中國])