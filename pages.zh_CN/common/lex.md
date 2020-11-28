# lex

> 词汇分析器生成器
> 给定词汇分析器的规范，生成实现它的C代码

- 从 Lex 文件生成分析器：

`lex {{analyser.l}}`

- 指定输出文件：

`lex {{analyser.l}} --outfile {{analyser.c}}`

- 编译 Lex 生成的 C 文件：

`cc {{path/to/lex.yy.c}} --output {{executable}}`

[#]: contributors: ([潘潘]，[Judie])