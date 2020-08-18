# tput

> 查看和修改终端的设置和功能

- 移动光标到指定的屏幕位置：

`tput cup {{y_coordinate}} {{x_coordinate}}`

- 设置文字 (af) 或者背景 (ab) 的颜色：

`tput {{setaf|setab}} {{ansi_color_code}}`

- 显示[终端的]列、行以及颜色的数值：

`tput {{cols|lines|colors}}`

- 在终端发出响铃声：

`tput bel`

- 重置终端的所有属性：

`tput sgr0`

- 允许 / 禁止在词中间换号：

`tput {{smam|rmam}}`

[#]: contributors: ([毕玮])