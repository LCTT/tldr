# cargo

> Rust 包管理器
> 管理 Rust 项目及其模块依赖性（crate）

- 查找 crate：

`cargo search {{search_string}}`

- 安装 crate：

`cargo install {{crate_name}}`

- 列出已安装的 crate：

`cargo install --list`

- 在当前目录下新建二进制程序（binary）或库文件（library）的 Rust 项目：

`cargo init --{{bin|lib}}`

- 在指定目录下新建二进制程序（binary）或库文件（library）的 Rust 项目：

`cargo new {{path/to/directory}} --{{bin|lib}}`

- 在当前目录中构建 Rust 项目：

`cargo build`

- 使用多个并行作业生成：

`cargo build -j {{jobs}}`

[#]: contributors: ([琳小梁]，[玉叶]，[isaced])