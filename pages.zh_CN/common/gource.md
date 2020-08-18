# gource

> 呈现 Git，SVN，Mercurial 和 Bazaar 存储库的动画树形图
> 它显示了随时间创建，修改或删除的文件和文件夹

- 在目录中运行 gource（如果它不是存储库的根目录，则从那里搜索根目录）：

`gource {{path/to/repository}}`

- 使用自定义输出分辨率在当前目录中运行 gource ：

`gource -{{width}}x{{height}}`

- 为动画设置自定义时间刻度：

`gource -c {{time_scale_multiplier}}`

- 设置动画中每天应该有多长时间（这与 -c 组合，如​​果提供的话）：

`gource -s {{seconds}}`

- 设置全屏模式和自定义背景颜色：

`gource -f -b {{hex_color_code}}`

- 设置动画的标题：

`gource --title {{title}}`

[#]: contributors: ([潘潘])