# sha256sum

> 计算 SHA256 加密校验值

- 计算文件的 SHA256 校验值：

`sha256sum {{filename1}}`

- 计算多个文件的 SHA256 校验值：

`sha256sum {{filename1}} {{filename2}}`

- 读取一个记录 SHA256 校验值的文件，并检查是否所有文件的 SHA256 校验值与记录一致：

`sha256sum -c {{filename.sha256}}`

[#]: contributors: ([󠀀]，[盛曦 姜]，[李桥])