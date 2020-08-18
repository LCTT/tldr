# stack

> 用于管理Haskell项目的工具

- 创建一个新项目，名称为{{project_name}}：

`stack new {{project_name}}`

- 安装项目所需的所有依赖包：

`stack install`

- 编译项目：

`stack build`

- 在项目的内部运行测试：

`stack test`

- 编译项目并在每次文件更改时重新编译：

`stack build --file-watch`

- 编译项目并在编译后执行命令{{command}}：

`stack build --exec "{{command}}"`

- 运行程序{{program_name}}并向其传递一个参数{{argument}}：

`stack exec {{program_name}} -- {{argument}}`

[#]: contributors: ([情书寄山鬼.]，[骞树])