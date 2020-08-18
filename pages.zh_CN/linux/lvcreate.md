# lvcreate

> 在现有卷组中创建逻辑卷
> 卷组是逻辑卷和物理卷的集合

- 在卷组 vg1 中创建 10 GB 的逻辑卷：

`lvcreate -L {{10G}} {{vg1}}`

- 在卷组 vg1 中创建一个名为 mylv 的 1500 MB 线性逻辑卷：

`lvcreate -L {{1500}} -n {{mylv}} {{vg1}}`

- 创建一个名为 mylv 的逻辑卷，它使用卷组 vg1 中总空间的 60%：

`lvcreate -l {{60%VG}} -n {{mylv}} {{vg1}}`

- 创建一个名为 mylv 的逻辑卷，该卷使用卷组 vg1 中的所有未分配空间：

`lvcreate -l {{100%FREE}} -n {{mylv}} {{vg1}}`

[#]: contributors: ([潘潘]，[jim.大团结])