# st-util

> 运行 GDB（GNU 调试器）服务器以与STM32 ARM Cortex 微控制器交互

- 在端口 4500 运行 GDB 服务器：

`st-util -p {{4500}}`

- 连接到 GDB 服务器：

`(gdb) target extended-remote {{localhost}}:{{4500}}`

- 写入固件到设备：

`(gdb) load {{firmware.elf}}`

[#]: contributors: ([王興與·區塊鏈·Linux中國])