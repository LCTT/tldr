# vegeta

> Vegeta 是 HTTP 负载测试的命令行工具，同时可作为程序库使用
> 参考命令 `ab` 

- 对指定网址发起攻击，时间持续30秒：

`echo "{{GET https://example.com}}" | vegeta attack -duration={{30s}}`

- 对指定主机攻击，使用自签署 https 证书：

`echo "{{GET https://example.com}}" | vegeta attack -insecure -duration={{30s}}`

- 每秒10次请求的节奏向指定地址发起攻击：

`echo "{{GET https://example.com}}" | vegeta attack -duration={{30s}} -rate={{10}}`

- 发起攻击并显示报告：

`echo "{{GET https://example.com}}" | vegeta attack -duration={{30s}} | vegeta report`

- 发起进攻，将结果绘制成图表（时延）：

`echo "{{GET https://example.com}}" | vegeta attack -duration={{30s}} | vegeta plot > {{path/to/results.html}}`

- 向指定文件里的多个地址发起进攻：

`vegeta attack -duration={{30s}} -targets=requests.txt | vegeta report`

[#]: contributors: ([李峰])