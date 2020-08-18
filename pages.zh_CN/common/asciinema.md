# asciinema

> 记录和重放终端会话，并可以选择在 asciinemaorg 上共享它们

- 将 `asciinema` 的本地安装与 asciinema.org 帐户关联：

`asciinema auth`

- 开始新的录制任务（完成后，将提示用户上载或本地保存）：

`asciinema rec`

- 开始新的终端录制并将其保存到本地文件：

`asciinema rec {{path/to/file}}.cast`

- 从本地文件重播终端录制：

`asciinema play {{path/to/file}}.cast`

- 重播在 asciinema.org 上托管的终端录制：

`asciinema play https://asciinema.org/a/{{cast_id}}`

- 进行新的录制，将任何空闲时间限制为最多 2.5 秒：

`asciinema rec -i {{2.5}}`

- 打印本地保存的录制的完整输出：

`asciinema cat {{path/to/file}}.cast`

- 上传本地保存的终端会话录制到 asciinema.org：

`asciinema upload {{path/to/file}}.cast`

[#]: contributors: ([琳小梁]，[Datura stramonium L.])