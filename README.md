# DataAnalysis_Py

<br>

## NumPy 入门
1. 简介
2. 数据类型及基础操作
    1. [NumPy的数据类型表格图片](http://124.220.164.99:8090/archives/python拓展之numpy#2.1-ndarray-数据类型)
    2. Ndarray 对象
    3. 创建数组
    4. Numpy数组的属性
    5. 切片与索引
    6. NumPy 数组操作
3. [NumPy 常用函数](http://124.220.164.99:8090/archives/python拓展之numpy#三、numpy的函数与常用功能)
    - [字符串函数](http://124.220.164.99:8090/archives/python拓展之numpy#3.1-numpy-字符串函数)
    1. 数组的集合操作
    2. 数学函数
    3. 统计函数
    4. 线性代数
    5. 排序与取索引函数
    6. 副本与视图
4. NumPy 和 Matplotlib 数据可视化
    - [NumPy 和 Matplotlib](http://124.220.164.99:8090/archives/python拓展之numpy#四、numpy-matplotlib)
5. 使用数组进行面向数组编程
6. 使用数组进行文件输入和输出
7. 随机漫步
    - [随机漫步的模拟](https://en.wikipedia.org/wiki/Random_walk)


<br>

## Pandas 入门

- 官方文档中强调，Pandas 项目名称中的字母应全部小写，且导入程序库的语句为：`import pandas as pd`
- Pandas 起初是被作为金融数据分析工具开发出来的，其名称来源于面板数据(Panel Data)和Python 数据分析(Data Analysis)，Panel Data 是经济学中关于多维数据集的一个术语
- 支持绝大部分NumPy风格的数组计算，不同的是，NumPy用于处理同质性的数值类型数组数据，而pandas是用来处理表格型或异质型数据的

1. 数据结构     
    1. `pandas.Series(data, index, dtype, name, copy)`          -> 一维数组
    2. `pandas.DataFrame(data, index, colume, dtype, copy)`     -> 二维数组
    3. `pandas.Panel(data=None, items=None, major_axis=None, minor_axis=None, copy=False, dtype=None)`  -> 三维数组
2. 基本功能
    1. 重建索引
    2. 轴向上删除条目
    3. 索引、选择与过滤
    4. 运算、数据对齐
        1. 使用填充值的算术方法
        2. DataFrame和Series间的操作
    5. 函数应用和映射
    6. 排序和排名
    7. 含有重复标签的轴索引
3. 描述性统计的概述与计算
4. 数据的输入与输出
    1. 处理***CSV、JSON文件***
    2. 《Python for Data Analysis(Second Edition)》
5. 数据清洗
    1. 删除空值
    2. 替换空值
    3. 清洗格式错误的数据
        1. 格式化日期
        2. 更改错误年龄
        3. 删除重复数据
6. 数据规整：连接、联合与重塑
    1. 分层索引
        1. 重排序和层级排序
        2. 按层级进行汇总统计
        3. 使用DataFrame的列进行索引
    2. 联合与合并数据集
        1. 数据库风格的DataFrame连接
        2. 根据索引合并
        3. 沿轴向连接
        4. 联合重叠数据
    3. 重塑和透视
        1. 使用多层索引进行重塑
        2. 将“长”透视为“宽”
        3. 将“宽”透视为“长” 
7. 数据聚合与分组操作
    - 《Python for Data Analysis(Second Edition)》
8. 绘图与可视化
    1. 图片与子图
    2. 使用pandas和seaborn绘图
    3. 直方图和密度图
    4. 散点图或点图
    5. 分面网络和分类数据
    6. 其他Python可视化工具
9. 时间序列
    - 《Python for Data Analysis(Second Edition)》
10. pandas高级应用
    - 《Python for Data Analysis(Second Edition)》

