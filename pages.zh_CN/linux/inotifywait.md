# inotifywait

> 监控一个或多个文件的变化

- 指定文件变化后执行指定命令：

`while inotifywait {{path/to/file}}; do {{command}}; done`

- 监控时尽量少打印或不打印日志：

`while inotifywait --quiet {{path/to/file}}; do {{command}}; done`

- 以递归的方式监控指定目录文件变化：

`while inotifywait --recursive {{path/to/directory}}; do {{command}}; done`

- 排除监控名称匹配指定正则表达式的文件：

`while inotifywait --recursive {{path/to/directory}} --exlude '{{regex}}'; do {{command}}; done`

- 执行命令前至多等待30秒：

`while inotifywait --timeout {{30}} {{path/to/file}}; do {{command}}; done`

- 仅监控指定的文件变化事件：

`while inotifywait --event {{modify}} {{path/to/file}}; do {{command}}; done`

[#]: contributors: ([李峰])