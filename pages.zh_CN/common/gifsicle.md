# gifsicle

> 创建 GIF 文件

- 优化 GIF ：

`gifsicle --batch --optimize=3 {{amin.gif}}`

- 使用 gifsicle 制作 GIF 动画：

`gifsicle --delay={{10}} --loop *.gif > {{anim.gif}}`

- 从动画中提取帧：

`gifsicle {{anim.gif}} '#0' > {{firstframe.gif}}`

- 通过替换，删除或插入帧来编辑动画：

`gifsicle -b {{anim.gif}} --replace '#0' {{new.gif}}`

[#]: contributors: ([潘潘])