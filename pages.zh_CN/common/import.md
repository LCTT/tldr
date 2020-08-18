# import

> 捕获部分或全部 X server 的屏幕，并将图像保存
> ImageMagick库的一部分

- 捕获整个 X server 屏并以 PostScript 图像格式保存：

`import -window root {{output.postscript}}`

- 捕获远程 X server 屏幕的内容并以 PNG 图像格式保存：

`import -window root -display {{remote_host}}:{screen}.{display} {{output.png}}`

- 根据 “xwininfo” 显示的 ID ，将特定窗口捕获并保存为 jpeg 格式：

`import -window {{window_id}} {{output.jpg}}`

[#]: contributors: ([飞鸿影🌴]，[Datura stramonium L.])