# odps auth

> ODPS（开放数据处理服务）中的用户权限

- 将用户添加到当前项目：

`add user {{user_name}};`

- 向用户授予一组权限：

`grant {{action_list}} on {{object_type}} {{object_name}} to user {{user_name}};`

- 显示用户的权限：

`show grants for {{user_name}};`

- 创建用户任务：

`create role {{role_name}};`

- 为角色授予一组权限：

`grant {{action_list}} on {{object_type}} {{object_name}} to role {{role_name}};`

- 描述（查看）任务的权限：

`desc role {{role_name}};`

- 授予用户一个任务：

`grant {{role_name}} to {{user_name}};`

[#]: contributors: ([种噫🎈])