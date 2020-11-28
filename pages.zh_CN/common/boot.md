# boot

> Clojure 编程语言构建工具

- 使用项目或独立启动 REPL 会话：

`boot repl`

- 建立一个单一的 “ uberjar ”：

`boot jar`

- 了解命令：

`boot cljs --help`

- 基于模板为新项目生成 scaffolding：

`boot --dependencies boot/new new --template {{template_name}} --name {{project_name}}`

- 为开发环境构建（使用 boot/new 模板）：

`boot dev`

- 为生产环境构建（使用 boot/new 模板）：

`boot prod`

[#]: contributors: ([潘潘]，[Datura stramonium L.])