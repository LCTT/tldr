# ansible-playbook

> 通过 SSH 执行远程机器上定义在 playbook 中的任务
> 主页: <https://docsansiblecom/ansible/latest/cli/ansible-playbookhtml>

- 运行 playbook 中的任务：

`ansible-playbook {{playbook}}`

- 使用自定义主机清单，运行 playbook 中的任务：

`ansible-playbook {{playbook}} -i {{inventory_file}}`

- 使用命令行中定义的外部参数，运行 playbook 中的任务：

`ansible-playbook {{playbook}} -e "{{variable1}}={{value1}} {{variable2}}={{value2}}"`

- 使用 json 文件中定义的外部参数，运行 playbook 中的任务：

`ansible-playbook {{playbook}} -e "@{{variables.json}}"`

[#]: contributors: ([东先生])