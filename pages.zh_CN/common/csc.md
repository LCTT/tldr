# csc

> 微软 C# 编译器

- 将一个或多个 C＃文件编译为 CIL 可执行文件：

`csc {{path/to/input_file_a.cs}} {{path/to/input_file_b.cs}}`

- 指定输出文件名：

`csc /out:{{path/to/filename}} {{path/to/input_file.cs}}`

- 编译 '.dll' 库代替可执行文件：

`csc /target:library {{path/to/input_file.cs}}`

- 参考另一个组件：

`csc /reference:{{path/to/library.dll}} {{path/to/input_file.cs}}`

- 嵌入一个资源：

`csc /resource:{{path/to/target_file.cs}},{{namespace.string.name}} {{path/to/input_file.cs}}`

- 自动生成 XML 文档：

`csc /doc:{{path/to/output.xml}} {{path/to/input_file.cs}}`

- 指定一个图标：

`csc /win32icon:{{path/to/icon.ico}} {{path/to/input_file.cs}}`

- 使用密钥文件强调命名结果程序集：

`csc /keyfile:{{path/to/keyfile}} {{path/to/input_file.cs}}`

[#]: contributors: ([潘潘]，[蔚然]，[jim.大团结])