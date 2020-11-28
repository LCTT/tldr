# webpack

> 打包一个 web 项目的 js 文件和其他资源，输出到一个单独的文件

- 由一个入口文件创建一个单独的输出：

`webpack {{app.js}} {{bundle.js}}`

- 从 js 文件中也会加载 css 文件(对 .css 文件使用 css loader 加载)：

`webpack {{app.js}} {{bundle.js}} --module-bind 'css=css'`

- 传递一个配置文件（例如项目脚本和输出文件名），并显示进度：

`webpack --config {{webpack.config.js}} --progress`

- 对项目文件的更改后自动重新编译：

`webpack --watch {{app.js}} {{bundle.js}}`

[#]: contributors: ([王興與·區塊鏈·Linux中國]，[张帅]，[Datura stramonium L.]，[周才樑])