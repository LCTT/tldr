# odps func

> 管理 ODPS（开放数据处理服务）中的功能

- 在当前项目中显示函数：

`list functions;`

- 使用 .jar 资源创建 Java 函数：

`create function {{func_name}} as {{path.to.package.Func}} using '{{package.jar}}';`

- 使用 .py 资源创建 Python 函数：

`create function {{func_name}} as {{script.Func}} using '{{script.py}}';`

- 删除一个函数：

`drop function {{func_name}};`

[#]: contributors: ([潘潘])