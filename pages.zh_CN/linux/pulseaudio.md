# pulseaudio

> pulseaudio 声音系统守护和管理器

- 检查 pulsesound 是否正在运行（非 0 返回值表示未运行）：

`pulseaudio --check`

- 在后台启动 pulseaudio 守护：

`pulseaudio --start`

- 终止正在运行的 pulseaudio 守护：

`pulseaudio --kill`

- 列出可用模块：

`pulseaudio --dump-modules`

- 使用指定参数将一个模块载入当前正在运行的守护进程：

`pulseaudio --load="{{module_name}} {{arguments}}"`

[#]: contributors: ([东先生])