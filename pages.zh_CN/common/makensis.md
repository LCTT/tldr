# makensis

> NSIS 安装程序的跨平台编译器
> 它将 NSIS 脚本编译为 Windows 安装程序可执行文件

- 编译 NSIS 脚本：

`makensis {{path/to/file.nsi}}`

- 以严格模式编译 NSIS 脚本（将警告视为错误）：

`makensis -WX {{path/to/file.nsi}}`

- 打印某个命令的帮助文档：

`makensis -CMDHELP {{command}}`

[#]: contributors: ([潘潘]，[蔚然])