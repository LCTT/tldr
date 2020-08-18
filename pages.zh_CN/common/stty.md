# stty

> 设置终端设备的选项

- 显示当前终端的所有设置：

`stty -a`

- 设置行数：

`stty rows {{rows}}`

- 设置列数：

`stty cols {{cols}}`

- 获取设备的实际传输速度：

`stty -f {{path/to/device_file}} speed`

- 将当前终端的所有模式重置为合理值：

`stty sane`

[#]: contributors: ([Datura stramonium L.])