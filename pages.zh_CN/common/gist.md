# gist

> 将代码上传到 https://gistgithubcom 

- 在此计算机上登录 gist ：

`gist --login`

- 从任意数量的文本文件创建一个要点：

`gist {{file.txt}} {{file2.txt}}`

- 创建一个包含描述的私人要点：

`gist -p -d {{"A meaningful description"}} {{file.txt}} `

- 从 STDIN 读取内容并从中创建一个要点：

`{{echo "hello world"}} | gist`

- 列出你的公共和私人要点：

`gist -l`

- 列出当前登录用户的所有要点：

`gist -l {{user_name}}`

- 使用 gist URL 中的 id 修改或包含文件：

`gist -u {{GIST_ID}} {{file.txt}}`

[#]: contributors: ([潘潘])