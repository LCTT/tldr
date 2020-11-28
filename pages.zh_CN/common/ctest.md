# ctest

> CMake 测试驱动程序

- 运行 CMake 项目中定义的所有测试，一次并发执行 4  个任务：

`ctest -j{{4}} --output-on-failure`

- 显示可用测试的列表：

`ctest -N`

- 运行一个基于名字或正则表达式过滤器的单个测试：

`ctest --output-on-failure -R '^{{test_name}}$'`

[#]: contributors: ([东先生])