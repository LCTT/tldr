# logstash

> ETL（提取，转换和加载）工具
> 通常用于将来自各种源（如数据库和日志文件）的数据加载到 elasticsearch 中

- 检查 logstash 配置的有效性：

`logstash --configtest --config {{logstash_config.conf}}`

- 使用配置运行 logstash ：

`sudo logstash --config {{logstash_config.conf}}`

- 使用最基本的内联配置字符串运行 logstash ：

`sudo logstash -e 'input {} filter {} output {}'`

[#]: contributors: ([潘潘])