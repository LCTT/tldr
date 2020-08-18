# aws

> AWS 官方命令行工具

- 列出所有的 IAM 用户：

`aws iam list-users`

- 列出指定区域 us-east-1 所有的 EC2 实例（instanced）：

`aws ec2 describe-instances --region {{us-east-1}}`

- 从指定的 SQS 队列中接收消息：

`aws sqs receive-message --queue-url {{https://queue.amazonaws.com/546123/Test}}`

- 向指定的 SNS 主题中添加消息：

`aws sns publish --topic-arn {{arn:aws:sns:us-east-1:54633:testTopic}} --message "Message"`

- 调用 AWS 命令为 command 的帮助文件：

`aws {{command}} help`

[#]: contributors: ([潘潘]，[一只特立独行的猪])