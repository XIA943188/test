# 项目描述

## 利欲驱人万火牛，江湖浪迹一沙鸥

`lì yù qū rén wàn huǒ niú, jiāng hú làng jì yī shā 'ōu.`

## 苟利国家生死以，岂因祸福趋避之

`gǒu lì guó jiā shēng sǐ yǐ, qǐ yīn huò fú qū bì zhī.`

# 使用说明

## 第一阶段测试代码

命令行运行`make main1`以编译第一阶段测试程序main1.

## 第二阶段测试代码

命令行运行`make main2`以编译第二阶段测试程序main2.

## 牛顿迭代法

命令行运行`make main3`以编译牛顿迭代法程序main3.

## `Tensor`对流运算符`<<`的重载

默认输出行数与`Tensor`第一个维度上的大小相同，并且采用类似`numpy`的输出格式，使用`[]`的嵌套来表示各个维度，如一个一维`Tensor`会表示为
	
```
[0 1 2 3 4 5 6 7]
```
	
`reshape`为`(2, 2, 2)`的三维`Tensor`后，输出变为
	
```
[[[0 1] [2 3]]
[[4 5] [6 7]]]
```

`reshape`为`(4, 2)`的二维`Tensor`后输出变为

```
[[0 1]
[2 3]
[4 5]
[6 7]]
```

## `Tensor`的各种改变形状的接口

`reshape(), concat(), transpose()`如之前所描述，新增加的接口有：`broadcast_div(), reduce_sum(), reduce_mul()`。
