---
title: '机器学习知识点总结'
date: 2024-05-25
permalink: /posts/2024/05/mlknowledge/
tags:
  - 机器学习
  - 人工智能
  - 八股文
---

# 概述

## 分类
一般来说，机器学习算法有三类。
- 监督式学习算法
- 非监督式学习算法
- 强化学习算法

代码测试：
```python
from sklean import svm
module = svm.SVC()
module.fit(x, y)
module.score(x, y)
module.predict(test)
module.predict_proba(test)
```

公式测试：

$F(w)=\frac{1}{T}\int_{0}^{T}f(t)\cdot e^{jwt}dt$

<img src="https://zjueducn-my.sharepoint.com/personal/3180102937_zju_edu_cn/Documents/%E5%9B%BE%E7%89%87/hymn8/230623-4.jpg" style="width: 50%;">
