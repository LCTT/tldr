# rsstail

> `tail` 版本的RSS 流

- 显示给定 URL 的 RSS 流，并等待将出现在底部的新项目：

`rsstail -u {{url}}`

- 以时间逆序显示 RSS 流（新项目出现在底部）：

`rsstail -r -u {{url}}`

- 包括发布时间和链接：

`rsstail -pl -u {{url}}`

- 设置更新间隔：

`rsstail -u {{url}} -i {{interval_in_seconds}}`

- 显示 RSS 流并退出：

`rsstail -1 -u {{url}}`

[#]: contributors: ([王興與·區塊鏈·Linux中國])