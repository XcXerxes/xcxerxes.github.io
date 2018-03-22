---
tag: [Lunix]
categories: Lunix系统
title: 基本的Lunix命令
---
做为一个希望向全栈工程师方向发展的程序员，必须得懂一些Lunix方面的知识，这节简单介绍一些基础的命令，以供大家一起学习...

## 基本的Lunix命令：

### tree命令

***tree -d*** 只显示文件夹

***tree -L*** n 显示项目的层级。 *n* 表示层级数。比如想要显示项目三层级结构， 可以用

```
    tree -L 3  // 显示三层级目录结构
```

***tree -I pattern*** 用于过滤不想要显示的文件或者文件夹。比如想过滤掉 *node_moudles* 文件夹，可以使用

```
tree -I "node_modules"
```

***tree >tree.md*** 将项目结构输出到tree.md这个文件中,举个例子

```
tree -L 3 -I "node_modules" // 输出三级目录结构 不包含 node_modules 文件夹
```