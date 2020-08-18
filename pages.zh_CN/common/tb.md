# tb

> 用于跨多个板管理任务和注释的 CLI 

- 向板中添加新任务：

`tb --task {{task description}} @{{board_name}}`

- 向板中添加新注释：

`tb --note {{note description}} @{{board_name}}`

- 编辑项目的优先级：

`tb --priority @{{item_id}} {{priority}}`

- 选中/取消选中的项：

`tb --check {{item_id}}`

- 存档所有选中的项目：

`tb --clear`

- 将项目移动到板：

`tb --move @{{item_id}} {{board_name}}`

[#]: contributors: ([󠀀])