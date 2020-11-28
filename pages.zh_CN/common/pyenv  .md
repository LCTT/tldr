# pyenv  

> 方便的在多个 Python 版本间切换

- 列出所有命令：

`pyenv commands`

- 列出所有在 `${PYENV_ROOT}/versions` 目录下的 Python 版本：

`pyenv versions`

- 将一个 Python 版本安装到 `${PYENV_ROOT}/versions`目录下：

`pyenv install {{2.7.10}}`

- 卸载 `${PYENV_ROOT}/versions` 目录下的一个 Python 版本：

`pyenv uninstall {{2.7.10}}`

- 设置一个 Python 版本为当前机器的全局使用版本：

`pyenv global {{2.7.10}}`

- 设置一个在当前目录及其下目录所用的 Pythpn 版本：

`pyenv local {{2.7.10}}`

[#]: contributors: ([王兴宇，Linux & BC]，[森灵])