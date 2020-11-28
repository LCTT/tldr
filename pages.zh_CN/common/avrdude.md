# avrdude

> Atmel AVR 微控制器编程驱动程序

- 读取 AVR 微控制器：

`avrdude -p {{AVR_device}} -c {{programmer}} -U flash:r:{{file.hex}}:i`

- 写 AVR 微控制器：

`avrdude -p {{AVR_device}} -c {{programmer}} -U flash:w:{{file.hex}}`

- 列出可用 AVR 设备：

`avrdude -p \?`

- 列出可用 AVR 编程器：

`avrdude -c \?`

[#]: contributors: ([琳小梁]，[东先生])