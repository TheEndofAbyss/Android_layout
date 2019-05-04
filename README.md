# Android布局-LinearLayout，ConstraintLayout及TableLayout
   
      
   首先，我们将三种布局方式放入一个app通过更改MainActivity.java更改布局，源代码如下:


![image](https://github.com/TheEndofAbyss/Android_layout/blob/master/image/2.1.png)


一.LinearLayout布局


主要源代码如下:


linearlayout.xml:


首先，我们先将总的布局设计为垂直划分，这样我们之后的每个小布局就可以分行显示

![image](https://github.com/TheEndofAbyss/Android_layout/blob/master/image/2.2.png)

其次，我们设计每一个小的布局为水平划分，并根据实现不同的要求划分他们的大小，如第一行，及第三行：

![image](https://github.com/TheEndofAbyss/Android_layout/blob/master/image/2.3.png)

![image](https://github.com/TheEndofAbyss/Android_layout/blob/master/image/2.4.png)

运行结果如下:

![image](https://github.com/TheEndofAbyss/Android_layout/blob/master/image/2.5.png)

二.ConstraintLayout布局

源代码如下:

constraintlayout.xml:

首先，设置总布局：

![image](https://github.com/TheEndofAbyss/Android_layout/blob/master/image/2.6.png)


其次，设计每一个分支布局，让他们根据内容分配大小，更改字体颜色等操作，最终达到实验要求效果，如红色及粉色：

![image](https://github.com/TheEndofAbyss/Android_layout/blob/master/image/2.7.png)

运行结果如下:

![image](https://github.com/TheEndofAbyss/Android_layout/blob/master/image/2.8.png)

三.TableLayout布局

源代码如下：

tablelayout.xml:

首先，设置总布局，背景颜色等使其符合实验要求标准：

![image](https://github.com/TheEndofAbyss/Android_layout/blob/master/image/2.9.png)

其次，实现表格中每个分支布局，如Open，下划线及Import：

![image](https://github.com/TheEndofAbyss/Android_layout/blob/master/image/2.10.png)

运行结果如下:

![image](https://github.com/TheEndofAbyss/Android_layout/blob/master/image/2.11.png)
