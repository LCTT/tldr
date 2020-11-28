# kubetail

> 同时跟踪多个kubernetes pod日志的实用程序

- 一次性将多个 pod（其名称以 “my_app” 开头）的日志尾部化：

`kubetail {{my_app}}`

- 从多个 pod 中尾部特定容器：

`kubetail {{my_app}} -c {{my_container}}`

- 从多个 pod 中拖出多个容器：

`kubetail {{my_app}} -c {{my_container_1}} -c {{my_container_2}}`

- 要同时拖尾多个应用程序，用逗号分隔它们：

`kubetail {{my_app_1}},{{my_app_2}}`

[#]: contributors: ([潘潘]，[Judie])