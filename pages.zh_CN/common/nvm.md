# nvm

> 安装、卸载 Nodejs 或切换其版本
> 支持版本号如 “012” 或 “v42” ，标签如 “stable”、“system” 等等
> 主页地址：<https://githubcom/creationix/nvm>

- 安装指定版本的 Node.js：

`nvm install {{node_version}}`

- 在当前 shell 环境下使用指定版本 Node.js：

`nvm use {{node_version}}`

- 设置默认 Node.js 版本：

`nvm alias default {{node_version}}`

- 列出可用的 Node.js 版本，高亮显示默认版本：

`nvm list`

- 卸载指定 Node.js 版本：

`nvm uninstall {{node_version}}`

- 启动指定版本的 Node.js 的 REPL（交互式解释）器：

`nvm run {{node_version}} --version`

- 以指定 Node.js 版本来执行指定脚本：

`nvm exec {{node_version}} node {{app.js}}`

[#]: contributors: ([王兴宇，Linux & BC]，[李峰])