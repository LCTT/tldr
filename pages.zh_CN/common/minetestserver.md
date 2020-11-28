# minetestserver

> 我的世界服务器
> 参阅 `minetest`，图形客户端

- 开始服务器：

`minetestserver`

- 列出可用的世界：

`minetestserver --world list`

- 指定世界名称去加载：

`minetestserver --world {{world_name}}`

- 列出可用的游戏 ID：

`minetestserver --gameid list`

- 使用指定的游戏：

`minetestserver --gameid {{game_id}}`

- 监听指定端口：

`minetestserver --port {{34567}}`

- 迁移到不同的数据后端：

`minetestserver --migrate {{sqlite3|leveldb|redis}}`

- 启动服务器后启动交互式终端：

`minetestserver --terminal`

[#]: contributors: ([jim.大团结])