# sn

> Mono StrongName 工具，用于签名和验证 IL 程序集

- 生成新的 StrongNaming 密钥：

`sn -k {{path/to/key.snk}}`

- 用指定私钥重新签名一个程序集：

`sn -R {{path/to/assembly.dll}} {{path/to/keypair.snk}}`

- 显示用于对程序集签名的私钥的公钥：

`sn -T {{path/to/assembly.exe}}`

- 将公钥提取到文件：

`sn -e {{path/to/assembly.dll}} {{path/to/output.pub}}`

[#]: contributors: ([硬核老王（📺Linux中国）]，[󠀀])