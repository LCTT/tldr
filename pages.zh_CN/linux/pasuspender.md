# pasuspender

> 当其它命令运行时临时休眠 `pulseaudio` 以允许其访问 alsa 设备

- 当运行  `jackd` 时休眠 pulseaudio：

`pasuspender -- {{jackd -d alsa --device hw:0}}`

[#]: contributors: ([王興與])