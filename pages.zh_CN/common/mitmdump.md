# mitmdump

> 查看，记录和以编程方式转换 HTTP 流量
> mitmproxy 的命令行对应物

- 启动代理并将所有输出保存到文件中：

`mitmdump -w {{filename}}`

- 将保存的流量文件过滤为 POST 请求：

`mitmdump -nr {{input_filename}} -w {{output_filename}} {{"~m post"}}`

- 重播已保存的流量文件：

`mitmdump -nc {{filename}}`

[#]: contributors: ([潘潘])