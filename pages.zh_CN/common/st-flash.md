# st-flash

> 刷入二进制文件到 STM32 ARM Cortex 微控制器

- 从 0x8000000 开始向设备读取 4096 字节：

`st-flash read {{firmware}}.bin {{0x8000000}} {{4096}}`

- 从 0x8000000 开始向设备写入：

`st-flash write {{firmware}}.bin {{0x8000000}}`

- 从设备擦除固件：

`st-flash erase`

[#]: contributors: ([好名字可以让你的朋友更容易记住你])