# heroku

> 从命令行创建和管理 Heroku 应用程序

- 登录你的 heroku 帐户：

`heroku login`

- 创建一个 heroku 应用程序：

`heroku create`

- 显示应用程序的日志：

`heroku logs --app {{app_name}}`

- 在 dyno（ Heroku 虚拟机 ）中运行一次性过程：

`heroku run {{process_name}} --app {{app_name}}`

- 列出应用程序的 dynos（ Heroku 虚拟机）：

`heroku ps --app {{app_name}}`

- 永久销毁一个应用：

`heroku destroy --app {{app_name}}`

[#]: contributors: ([潘潘])