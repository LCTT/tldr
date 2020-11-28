# beep

> 一个实用程序，使 PC 扬声器蜂鸣

- 发出蜂鸣：

`beep`

- 重复蜂鸣：

`beep -r {{repetitions}}`

- 按指定频率（Hz）和持续时间（毫秒）蜂鸣：

`beep -f {{frequency}} -l {{duration}}`

- 以每一个新的频率和持续时间蜂鸣：

`beep -f {{frequency}} -l {{duration}} -n -f {{frequency}} -l {{duration}}`

- 演奏 C 大调音阶：

`beep -f 262 -n -f 294 -n -f 330 -n -f 349 -n -f 392 -n -f 440 -n -f 494 -n -f 523`

[#]: contributors: ([王兴宇，Linux 中國]，[启威])