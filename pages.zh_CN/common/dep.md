# dep

> 用于管理 Go 项目中依赖关系的工具

- 将当前目录初始化为 GO 项目的根目录：

`dep init`

- 安装所有缺少的依赖项（扫描 Gopkg.toml 和 .go 文件）：

`dep ensure`

- 报告项目依赖项的状态：

`dep status`

- 向项目添加依赖项：

`dep ensure -add {{package_url}}`

- 更新所有依赖项的锁定版本：

`dep ensure -update`

[#]: contributors: ([Datura stramonium L.])