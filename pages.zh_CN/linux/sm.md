# sm

> 全屏显示短信

- 全屏显示消息：

`sm {{Hello World!}}`

- 显示反色的消息：

`sm -i {{Hello World!}}`

- 显示前景色的消息：

`sm -f {{blue}} {{Hello World!}}`

- 显示指定背景色的消息：

`sm -b {{#008888}} {{Hello World!}}`

- 将消息旋转 n 次90度：

`sm -r {{3}} {{Hello World!}}`

- 通过管道将消息传递给 sm：

`{{echo Hello World!}} | sm -`

[#]: contributors: ([李峰])