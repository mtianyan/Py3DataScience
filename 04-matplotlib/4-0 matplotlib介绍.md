## Matplotlib

与matlab中的画图功能类似。

### 为什么要用python 画图

- GUI太复杂(安装，gui的)
- excel太头疼，复杂图操作复杂
- python简单，免费

### 什么是Matplotlib

- 一个python包
- 用于2d绘图
- 非常强大和流行
- 有很多扩展(下一章的seaborn也是它的扩展)

### hello world in Matplotlib

```python
import matplotlib.pyplot as plt
import numpy as np
%matplotlib inline
x = np.linspace(0,2*np.pi,100)
y = np.sin(x)
plt.plot(x,y)
```

linspace 生成0到100，间隔为2π。

向sin函数传入该值。有x，y

向plot传入x，y

### Matplotlib Architecture

- Backend: 主要处理把图形显示到哪里和画到哪里(qt,jupter notebook)
- Artist: 图形显示成什么样
- Scripting: pyplot python语法和api

- Matplotlib的官方网站。Matplotlib的两本书。

