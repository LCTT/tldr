# ghc

> 格拉斯哥 Haskell 编译器
> 编译并链接 Haskell 源文件

- 查找并编译当前目录中的所有模块：

`ghc Main`

- 编译单个文件：

`ghc {{file.hs}}`

- 使用额外优化进行编译：

`ghc -O {{file.hs}}`

- 生成目标文件后停止编译（.o）：

`ghc -c {{file.hs}}`

- 运行 Haskell 交互式解释器（REPL）：

`ghci`

- 评估单个表达式：

`ghc -e {{expression}}`

[#]: contributors: ([潘潘])