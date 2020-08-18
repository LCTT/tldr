# trans

> Translate Shell 是一个命令行翻译器

- 翻译一个单词 (自动检测语言)：

`trans "{{word_or_sentence_to_translate}}"`

- 得到一个简短的翻译：

`trans --brief "{{word_or_sentence_to_translate}}"`

- 翻译一个单词到法语：

`trans :{{fr}} {{word}}`

- 翻译一个单词从德语到英语：

`trans {{de}}:{{en}} {{Schmetterling}}`

- 表现的像词典一样去得到一个单词的含义：

`trans -d {{word}}`

[#]: contributors: ([jim.大团结])