# adduser

> 用户添加工具

- 以默认的家目录设置创建一个新用户，并提示用户设置其密码：

`adduser {{username}}`

- 新建一个没有家目录的用户：

`adduser --no-create-home {{username}}`

- 创建一个指定了家目录路径的新用户：

`adduser --home {{path/to/home}} {{username}}`

- 创建一个新用户，并指定其登录ｓｈｅｌｌ：

`adduser --shell {{path/to/shell}} {{username}}`

- 创建一个隶属于指定组的新用户：

`adduser --ingroup {{group}} {{username}}`

[#]: contributors: ([ ]，[王兴宇，Linux & BC]，[玉叶]，[东先生]，[jim.大团结])