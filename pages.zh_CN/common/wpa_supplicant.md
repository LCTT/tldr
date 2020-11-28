# wpa_supplicant

> 管理受保护的无线网络

- 加入一个受保护的无线网络：

`wpa_supplicant -i {{interface}} -c {{path/to/wpa_supplicant_conf.conf}}`

- 加入受保护的无线网络，并在守护进程中运行它：

`wpa_supplicant -B -i {{interface}} -c {{path/to/wpa_supplicant_conf.conf}}`

[#]: contributors: ([玉叶]，[jim.大团结])