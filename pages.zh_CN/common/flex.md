# flex

> 词法分析器生成器，基于 lex 
> 给定词汇分析器的规范，生成实现它的C代码

- 从 flex 文件中生成词法分析器：

`flex {{analyser.l}}`

- 指定输出文件：

`flex {{analyser.l}} --outfile {{analyser.c}}`

- 编译由 flex 生成的 .c 文件：

`cc {{path/to/lex.yy.c}} --output {{executable}}`

[#]: contributors: ([潘潘]，[胖鱼]，[6 °分离]，[玉叶])