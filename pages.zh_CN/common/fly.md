# fly

> concourse-ci命令行工具

- 使用并保存concourse目标进行身份验证：

`fly --target {{target_name}} login --team-name {{team_name}} -c {{https://ci.example.com}}`

- 列出目标：

`fly targets`

- 列表管道：

`fly -t {{target_name}} pipelines`

- 上传或更新 pipeline：

`fly -t {{target_name}} set-pipeline --config {{pipeline.yml}} --pipeline {{pipeline_name}}`

- Unpause管道：

`fly -t {{target_name}} unpause-pipeline --pipeline {{pipeline_name}}`

- 显示管道配置：

`fly -t {{target_name}} get-pipeline --pipeline {{pipeline_name}}`

- 更新fly的本地副本：

`fly -t {{target_name}} sync`

- 破坏管道：

`fly -t {{target_name}} destroy-pipeline --pipeline {{pipeline_name}}`

[#]: contributors: ([仁人]，[玉叶])