# gpg

> GNU 私密护卫

- 在没有加密的情况下签署 doc.txt（将输出写入 doc.txt.asc ）：

`gpg --clearsign {{doc.txt}}`

- 加密 alice@example.com 的 doc.txt（ 输出到doc.txt.gpg ）：

`gpg --encrypt --recipient {{alice@example.com}} {{doc.txt}}`

- 仅使用密码加密 doc.txt（ 输出到 doc.txt.gpg ）：

`gpg --symmetric {{doc.txt}}`

- 解密 doc.txt.gpg（ 输出到 STDOUT ）：

`gpg --decrypt {{doc.txt.gpg}}`

- 导入公钥：

`gpg --import {{public.gpg}}`

- 导出 alice@example.com 的公钥（ 输出到STDOUT ）：

`gpg --export --armor {{alice@example.com}}`

- 导出 alice@example.com的私钥（输出到STDOUT）：

`gpg --export-secret-keys --armor {{alice@example.com}}`

[#]: contributors: ([潘潘])