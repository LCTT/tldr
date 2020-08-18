# web-ext

> 用于管理 web 扩展开发的命令行工具
> 主页: <https://wwwnpmjscom/package/web-ext> 

- 在 Firefox 中的当前目录中运行 Web 扩展：

`web-ext run`

- 从 Firefox 中的特定目录运行 Web 扩展：

`web-ext run --source-dir {{path/to/directory}}`

- 显示详细的执行输出：

`web-ext run --verbose`

- 在 Firefox Android 中运行 Web 扩展：

`web-ext run --target firefox-android`

- 提示清单和源文件是否有错误：

`web-ext lint`

- 构建并打包扩展：

`web-ext build`

- 显示详细的构建输出：

`web-ext build --verbose`

- 签署一个自助托管包：

`web-ext sign --api-key {{api_key}} --api-secret {{api_secret}}`

[#]: contributors: ([潘潘]，[jim.大团结])