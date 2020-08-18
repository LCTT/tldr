# aws s3

> AWS S3 命令行接口，通过 web 服务接口提供存储

- 显示 bucket 中的文件：

`aws s3 ls {{bucket_name}}`

- 从本地同步文件和文件夹到 bucket：

`aws s3 sync {{path/to/files}} s3://{{bucket_name}}`

- 从 bucket 同步文件和文件夹到本地：

`aws s3 sync s3://{{bucket_name}} {{path/to/target}}`

- 从本地同步文件夹到 S3 back，指定除了本地的文件 path/to/file 和本地的文件夹 path/to/folder：

`aws s3 sync {{path/to/files}} s3://{{bucket_name}} --exclude {{path/to/file}} --exclude {{path/to/folder}}/*`

- 从 bucket 中删除文件 path/to/file：

`aws s3 rm s3://{{bucket}}/{{path/to/file}}`

- 预演命令的运行结果，不真实操作：

`aws s3 {{any_command}} --dryrun`

[#]: contributors: ([琳小梁]，[潘潘]，[东先生])