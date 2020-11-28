# notify-send

> 使用当前桌面环境的通知系统来创建一个通知

- 显示一个通知，标题为 "Test"，内容为 "This is a test"：

`notify-send {{"Test"}} {{"This is a test"}}`

- 显示一个带自定义图标的通知：

`notify-send -i {{icon.png}} {{"Test"}} {{"This is a test"}}`

- 展示一个提示 5 秒钟：

`notify-send -t 5000 {{"Test"}} {{"This is a test"}}`

[#]: contributors: ([庄秋彬]，[王兴宇，Linux 中國])