# tail

> 显示文件最后的部分

- 显示文件最后的 'num' 行：

`tail -n {{num}} {{file}}`

- 从'num'行开始显示文件的全部内容：

`tail -n +{{num}} {{file}}`

- 显示文件最后的'num'个字节：

`tail -c {{num}} {{file}}`

- 保持查看文件内容， `Ctrl + C` 结束：

`tail -f {{file}}`

- 持续显示阅读文件的内容，直到按住 'Ctrl + C' ，即使文件在翻滚（翻页）：

`tail -F {{file}}`

[#]: contributors: ([烦烦]，[󠀀]，[　]，[王兴宇]，[蜂子🐝ℋ]，[Johnny.Li])