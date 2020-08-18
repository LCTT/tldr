# go

> 管理 go 源代码的工具

- 通过指定的导入路径来下载并安装一个包：

`go get {{package_path}}`

- 编译（不会保存编译出的文件）和运行一个源代码文件（它必须包含“main”包）：

`go run {{file}}.go`

- 编译一个源文件为一个命名的可执行文件：

`go build -o {{executable}} {{file}}.go`

- 编译当前目录里的包：

`go build`

- 执行当前包里的所有测试用例（文件必须以 `_test.go` 结尾）：

`go test`

- 编译并安装当前包：

`go install`

[#]: contributors: ([iO]，[公孙林]，[王兴宇，Linux 中國]，[holy4god])