# pm2

> Nodejs 进程管理工具
> 用来打管理日志，监控和配置 nodejs 进程

- 启动进程，给其命名方便后续操作：

`pm2 start {{app.js}} --name {{myapp}}`

- 列出进程：

`pm2 list`

- 监控所有进程：

`pm2 monit`

- 停用指定进程：

`pm2 stop {{myapp}}`

- 重启指定进程：

`pm2 restart {{myapp}}`

[#]: contributors: ([李峰])