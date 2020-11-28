# lastb

> 显示最近登录的用户列表

- 显示所有最近登录的用户列表：

`sudo lastb`

- 显示指定时间之后所有最近登录的用户列表：

`sudo lastb --since {{YYYY-MM-DD}}`

- 显示指定时间之前所有最近登录的用户列表：

`sudo lastb --until {{YYYY-MM-DD}}`

- 显示指定时间所有登录的用户列表：

`sudo lastb --present {{hh:mm}}`

- 显示所有最近登录的用户列表，并将IP转换成主机名：

`sudo lastb --dns`

[#]: contributors: ([阿涛])