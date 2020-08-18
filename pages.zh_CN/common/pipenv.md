# pipenv

> 简单且统一的 Python 开发工作框架
> 管理项目的包和虚拟环境
> 项目主页：
<https://pypiorg/project/pipenv>

- 创建一个新项目：

`pipenv`

- 创建一个 Python 3 的新项目：

`pipenv --three`

- 安装一个包：

`pipenv install {{package_name}}`

- 安装一个项目的所有依赖（包含dev）：

`pipenv install --dev`

- 卸载一个包：

`pipenv uninstall {{package_name}}`

- 运行一个在创建的虚拟环境中的命令行：

`pipenv shell`

- 为一个项目生成 requirements.txt 文件（包含项目运行所需要的包）：

`pipenv lock --requirements`

[#]: contributors: ([jim.大团结]，[盛曦 姜])