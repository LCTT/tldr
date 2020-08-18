# erl

> 运行和管理 Erlang 语言程序

- 编译并运行指定 Erlang 程序作为公用脚本，然后退出：

`erlc {{files}} && erl -noshell '{{mymodule:myfunction(arguments)}}, init:stop().'`

- 连接到指定运行中的 Erlang 节点：

`erl -remsh {{nodename}}@{{hostname}} -sname {{custom_shortname}} -hidden -setcookie {{cookie_of_remote_node}}`

- 让 Erlang shell 加载指定目录的模块：

`erl -pa {{directory_with_beam_files}}`

[#]: contributors: ([李峰])