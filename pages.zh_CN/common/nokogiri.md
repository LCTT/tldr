# nokogiri

> HTML、XML、SAX 和 Reader 解析器

- 解析 URL 或文件的内容：

`nokogiri {{url|path/to/file}}`

- 以指定类型来解析：

`nokogiri {{url|path/to/file}} --type {{xml|html}}`

- 在解析前载入指定的初始化文件：

`nokogiri {{url|path/to/file}} -C {{path/to/config_file}}`

- 使用指定的编码解析：

`nokogiri {{url|path/to/file}} --encoding {{encoding}}`

- 使用 RELAX NG 文件验证：

`nokogiri {{url|path/to/file}} --rng {{url|path/to/file}}`

[#]: contributors: ([王興與])