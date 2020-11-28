# redshift

> 根据周围环境调节显示器的色温

- 打开 Redshift，白天设置为 5700K 色温，夜间设置为 3600K 色温：

`redshift -t {{5700}}:{{3600}}`

- 打开 Redshift，手动指定地理位置：

`redshift -l {{latitude}}:{{longitude}}`

- 打开 Redshift，白天设置为 70% 亮度，夜间设置为 40% 亮度：

`redshift -b {{0.7}}:{{0.4}}`

- 打开 Redshift，指定 gamma 级别（0 - 1）：

`redshift -g {{red}}:{{green}}:{{blue}}`

- 打开 Redshift，固定为一个不变的色温：

`redshift -O {{temperature}}`

[#]: contributors: ([王興與·璃霓思硬核]，[Mr. Ren])