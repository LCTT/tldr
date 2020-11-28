# dokku

> Docker 技术驱动的迷你版 Heroku （Heroku 是一种平台即服务）
> 只需一条 `git-push` 命令，你就能很容易的在服务器上以不同语言部署多个应用

- 列出所有在运行的应用：

`dokku apps`

- 创建一个新的应用：

`dokku apps:create {{app_name}}`

- 移除一个应用：

`dokku apps:destroy {{app_name}}`

- 安装插件：

`dokku plugin:install {{full_repo_url}}`

- 把数据库链接到一个应用：

`dokku {{db}}:link {{db_name}} {{app_name}}`

[#]: contributors: ([王兴宇，Linux & BC]，[Mr. Ren])