# bower

> 优化前端网页开发的包管理工具
> 代码包可以是 GitHub 代码库简写地址、Gi 节点、URL 或已注册的包

- 为项目安装 bower.json 文件里列出的依赖包：

`bower install`

- 安装一个或多代码包，存放到 bower_components 目录：

`bower install {{package}} {{package}}`

- 卸载已安装代码包，从 bower_components 目录中移除：

`bower uninstall {{package}} {{package}}`

- 列出已安装到本地的包和可用更新：

`bower list`

- 显示指定 bower 命令的帮助信息：

`bower help {{command}}`

- 为你的代码包创建 bower.json 文件：

`bower init`

- 指定版本安装代码包，并记录在 bower.json 文件里：

`bower install {{local_name}}={{package}}#{{version}} --save`

[#]: contributors: ([李峰])