---
layout:     post
title:      TensorFlow常用函数
subtitle:   初识笔记
date:       2019-10-17
author:     ZNH
header-img: img/post-bg-cook.jpg
catalog: true
tags:
    - AI
    - TensorFlow
    - 深度学习
---
### TensorFlow常用函数

##### 1.Session对象

- run(fetched, feed_dict=None, options=None, run_metadata=None)

  `fetches`: 表示数据流图中能接收的任意数据流图元素，各类Op/Tensor对象

  `feed_dict`:可选。给数据流图提供运行时数据。`feed_dict`的数据结构为python中的字典，其元素为各种键值对。

  `options`: