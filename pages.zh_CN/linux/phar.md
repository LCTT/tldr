# phar

> 创建、更新或提取PHP归档（包）(PHAR)

- 将空格分隔的文件或目录添加到Phar文件中：

`phar add -f {{path/to/phar_file}} {{files_or_directories}}`

- 显示Phar文件的内容：

`phar list -f {{path/to/phar_file}}`

- 从Phar文件中删除指定的文件或目录：

`phar delete -f {{path/to/phar_file}} -e {{file_or_directory}}`

- 显示完整的使用信息和可用的哈希/压缩算法：

`phar help`

- 压缩或解压Phar文件中的文件和目录：

`phar compress -f {{path/to/phar_file}} -c {{algorithm}}`

- 获取有关Phar文件的信息：

`phar info -f {{path/to/phar_file}}`

- 使用特定的哈希算法对Phar文件签名：

`phar sign -f {{path/to/phar_file}} -h {{algorithm}}`

- 使用OpenSSL私钥对Phar文件签名：

`phar sign -f {{path/to/phar_file}} -h openssl -y {{path/to/private_key}}`

[#]: contributors: ([启威])