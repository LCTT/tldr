# monodis

> Mono 通用中间语言（CIL）反汇编程序
> 主页：<https://wwwmono-projectcom/docs/tools+libraries/tools/monodis/>

- 将程序集拆分为文本 CIL ：

`monodis {{path/to/assembly.exe}}`

- 将输出保存到文件：

`monodis --output={{path/to/output.il}} {{path/to/assembly.exe}}`

- 显示有关装配的信息：

`monodis --assembly {{path/to/assembly.dll}}`

- 列出程序集的引用：

`monodis --assemblyref {{path/to/assembly.exe}}`

- 列出程序集中的所有方法：

`monodis --method {{path/to/assembly.exe}}`

- 显示程序集中嵌入的资源列表：

`monodis --manifest {{path/to/assembly.dll}}`

- 将所有嵌入资源提取到当前目录：

`monodis --mresources {{path/to/assembly.dll}}`

[#]: contributors: ([潘潘])