# tox

> 在多个 Python 版本间进行自动化测试
> 使用 toxini 来配置环境和测试命令

- 在所有的测试环境下运行测试：

`tox`

- 创建一个 tox.ini 配置文件：

`tox-quickstart`

- 列出可用的环境：

`tox --listenvs-all`

- 在特定的环境下(例如 python 3.6 版本)运行测试：

`tox -e {{py36}}`

- 强制重新创建一个虚拟环境：

`tox --recreate -e {{py27}}`

[#]: contributors: ([lc])