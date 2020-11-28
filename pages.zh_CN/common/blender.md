# blender

> Blender 3D 计算机图形应用程序的命令行界面
> 参数按给定的顺序执行

- 在后台渲染动画的所有帧，而不加载 UI
（输出保存到 `/tmp` ）：

`blender -b {{filename}}.blend -a`

- 使用特定的图像命名模式，在 blend 文件的相对路径（ `//` ）中渲染动画：

`blender -b {{filename}}.blend -o //{{render/frame_###.png}} -a`

- 将动画的第 10 帧渲染为单个图像，保存到现有目录（绝对路径）：

`blender -b {{filename}}.blend -o {{/path/to/output_directory}} -f {{10}}`

- 将动画中的最后一帧渲染为保存到现有目录（相对路径）的 jpeg 图像：

`blender -b {{filename}}.blend -o //{{output_directory}} -F {{JPEG}} -f {{-2}}`

- 渲染特定场景的动画，从第 10 帧开始，到第 500 帧结束：

`blender -b {{filename}}.blend -S {{scene_name}} -s {{10}} -e {{500}} -a`

- 通过传递 python 表达式，以特定的分辨率渲染动画：

`blender -b {{filename}}.blend --python-expr '{{import bpy; bpy.data.scenes[0].render.resolution_percentage = 25}}' -a`

- 使用 python 控制台在终端中启动交互式搅拌机会话（启动后执行 `import bpy` ）：

`blender -b --python-console`

[#]: contributors: ([琳小梁]，[玉叶]，[　])