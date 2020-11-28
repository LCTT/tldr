# sqlite3

> SQLite 3 的命令行界面，这是一个自包含式且基于文件的嵌入式 SQL 引擎

- 新建一个数据库，并进入交互模式：

`sqlite3`

- 打开已有的数据库，并进入交互模式：

`sqlite3 {{path/to/database.sqlite3}}`

- 在数据库中执行一条 SQL 语句并退出：

`sqlite3 {{path/to/database.sqlite3}} '{{SELECT * FROM some_table;}}'`

[#]: contributors: ([Nonamev]，[infinite])