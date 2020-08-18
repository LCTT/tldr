# npm

> Javascript 和 Nodejs 包管理器
> 管理 Nodejs 项目及其模块依赖项
> 主页: <https://wwwnpmjscom/>

- 下载并安装模块 (可以直接用模块名称运行模块)：

`npm install -g {{module_name}}`

- 下载package.json中引用的所有依赖项：

`npm install`

- 下载运行应用程序所需的给定依赖项，并将其添加到package.json中：

`npm install {{module_name}}@{{version}} --save`

- 为开发目的下载给定的依赖项，并将其添加到package.json：

`npm install {{module_name}}@{{version}} --save-dev`

- 卸载模块：

`npm uninstall {{module_name}}`

- 列出package.json中引用的已安装的模块：

`npm list`

- 列出全局安装的最高级模块：

`npm list -g --depth={{0}}`

- 以交互方式创建package.json文件：

`npm init`

[#]: contributors: ([公孙林]，[Datura stramonium L.])