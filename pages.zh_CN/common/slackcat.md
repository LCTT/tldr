# slackcat

> 用于传递文件和命令输出到 Slack 的实用程序

- 传文件到 Slack：

`slackcat --channel {{channel_name}} {{path/to/file}}`

- 以定制的文件名传文件到 Slack：

`slackcat --channel {{channel_name}} --filename={{filename}} {{path/to/file}}`

- 以文本片段的形式通过管道将命令输出发送到 Slack：

`{{command}} | slackcat --channel {{channel_name}} --filename={{snippet_name}}`

- 持续地以流式发送命令输出到 Slack：

`{{command}} | slackcat --channel {{channel_name}} --stream`

[#]: contributors: ([王興與·區塊鏈·Linux中國])