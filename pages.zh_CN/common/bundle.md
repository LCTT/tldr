# bundle

> Ruby 编程语言的依赖管理器

- 在当前目录安装定义在 gemfile 的所有 gem 包：

`bundle install`

- 升级所有定义在 gemfile 中的 gem 包并生成 gemfile.lock 文件：

`bundle update`

- 升级定义在 gemfile 中的某个特定 gem 包：

`bundle update --source {{gemname}}`

- 创建一个新的 gem 支架：

`bundle gem {{gemname}}`

[#]: contributors: ([lc])