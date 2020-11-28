# rustup

> Rust 工具链安装程序
> 安装，管理和更新 Rust 工具链

- 为你的系统安装夜间工具链：

`rustup install nightly`

- 将默认工具链切换到每晚，以便 cargo 和 rustc 命令将使用它：

`rustup default nightly`

- 在当前项目内使用每夜工具链，但是不动全局设置：

`rustup override set nightly`

- 升级所有工具链：

`rustup update`

- 列出已安装工具链：

`rustup show`

- 以合适的工具链运行 cargo 构建：

`rustup run {{toolchain_name}} cargo build`

[#]: contributors: ([王興與]，[潘潘]，[AilCil对瓶吹])