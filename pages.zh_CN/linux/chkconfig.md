# chkconfig

> 在 CentOS 6 （及更低版本）系统中管理服务的运行级别

- 显示所有服务的运行级状态：

`chkconfig --list`

- 显示“ntpd”服务的运行级状态：

`chkconfig --list {{ntpd}}`

- 使“ssnd”服务在[2 3 4 5]之一的运行级启动：

`chkconfig {{sshd}} on`

- 在运行级 [2 3 4 5]之一启用一个服务（进入该运行级时启动）：

`chkconfig --level {{2345}} {{sshd}} on`

- 禁止指定服务随系统启动：

`chkconfig {{ntpd}} off`

- 在运行级 3 中禁用一个服务：

`chkconfig --level {{3}} {{ntpd}} off`

[#]: contributors: ([琳小梁]，[　]，[王兴宇，Linux & BC]，[陈绍华]，[游响停云]，[jim.大团结])