# rfkill

> 打开、关闭无线设备

- 列出设备：

`rfkill`

- 按照列匹配(过滤)：

`rfkill -o {{ID,TYPE,DEVICE}}`

- 按照设备类型禁用设备(例如 bluetooth wlan)：

`rfkill block {{bluetooth}}`

- 按照设备类型启用设备(例如 bluetooth wlan)：

`rfkill unblock {{wlan}}`

- 用 JSON 格式输出：

`rfkill -J`

[#]: contributors: ([梦还在继续]，[东先生])