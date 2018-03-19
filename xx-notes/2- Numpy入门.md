2- Numpy入门

## 数据科学领域5个最佳Python库

Numpy / Scipy / Pandas / Matplotlib / Scikit-learn

### Numpy

类比成高数，线性代数，是学习其他高级专业课程的基础。

- N维数组(矩阵), 快速高效, 矢量数学运算
- 高效的Index，不需要循环
- 开源免费跨平台，运行效率足以和c/matlab媲美。底层c实现

![mark](http://myphoto.mtianyan.cn/blog/180201/E30d94JJL3.png?imageslim)

### Scipy

- 依赖于Numpy 专为科学和工程设计

- 实现了多种常用科学计算: 线性代数，傅里叶变换，信号和图像处理。

### Pandas

- 结构化数据分析利器(依赖于Numpy)
- 提供了多种高级数据结构: Time-Series, DataFrame, Panel
- 强大的数据索引和处理能力

![mark](http://myphoto.mtianyan.cn/blog/180201/e1Ib5DG9dC.png?imageslim)

>可以方便的读取数据，处理数据。

### Matplotlib

- Python 2D绘图领域使用最广泛的套件
- 基本能取代Matlab的绘图功能(散点，曲线，柱形等)
- 通过mplot3d 可以绘制精美的3d图。

![mark](http://myphoto.mtianyan.cn/blog/180201/22Jh12kh1c.png?imageslim)

左边2d，右边3d。

### Scikit-learn

- 机器学习的Python模块
- 建立在Scipy之上，提供了常用的机器学习算法: 聚类, 回归。
- 简单易学的api接口

![mark](http://myphoto.mtianyan.cn/blog/180201/2l3Cjjj42L.png?imageslim)

## 线性代数: 矩阵运算

Numpy里有大量的矩阵相关的知识。

基本概念：

矩阵: 矩阵的数组，就是二维数组。其中向量和标量都是矩阵的特例。

向量: 是指1xn 或者 nx1 的矩阵。

标量: 1 x 1 的矩阵

数组: N维的数组，是矩阵的延伸。

### 特殊矩阵

- 全0全1矩阵
- 单位矩阵

![mark](http://myphoto.mtianyan.cn/blog/180201/H2eeKJie7I.png?imageslim)

n x n 对角线上值全为1. 因为任何矩阵乘以单位矩阵，等于他本身。

### 矩阵加减运算

- 相加相减的两个矩阵必须要有相同的行和列
- 行和列对应位置元素相加减

![mark](http://myphoto.mtianyan.cn/blog/180201/1Bb7d20JLi.png?imageslim)

### 数组乘法(点乘)

- 数组乘法(点乘) 是对应元素之间的乘法。

![mark](http://myphoto.mtianyan.cn/blog/180201/BDA0eG6dj8.png?imageslim)

### 矩阵乘法

![mark](http://myphoto.mtianyan.cn/blog/180201/IdD0be2DcC.png?imageslim)

![mark](http://myphoto.mtianyan.cn/blog/180201/A8Eh6gKB0d.png?imageslim)

其他线性代数知识看线性代数书。

## Numpy 中Array的创建和访问。









