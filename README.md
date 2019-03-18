# Android布局-LinearLayout，ConstraintLayout及TableLayout
   
      
   首先，我们将三种布局方式放入一个app通过更改MainActivity.java更改布局，源代码如下:


![在这里插入图片描述](https://img-blog.csdnimg.cn/20190318192115489.png?x-oss-proess=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQyMzA0MjY3,size_16,color_FFFFFF,t_70)


一.LinearLayout布局


主要源代码如下:


linearlayout.xml:


首先，我们先将总的布局设计为垂直划分，这样我们之后的每个小布局就可以分行显示


![在这里插入图片描述](https://img-blog.csdnimg.cn/20190318192538654.png)

其次，我们设计每一个小的布局为水平划分，并根据实现不同的要求划分他们的大小，如第一行，及第三行：


![在这里插入图片描述](https://img-blog.csdnimg.cn/20190318192702928.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQyMzA0MjY3,size_16,color_FFFFFF,t_70)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20190318192717252.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQyMzA0MjY3,size_16,color_FFFFFF,t_70)

运行结果如下:


![在这里插入图片描述](https://img-blog.csdnimg.cn/20190318192811279.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQyMzA0MjY3,size_16,color_FFFFFF,t_70)

二.ConstraintLayout布局

源代码如下:

constraintlayout.xml:

首先，设置总布局：

![在这里插入图片描述](https://img-blog.csdnimg.cn/20190318192940589.png)


其次，设计每一个分支布局，让他们根据内容分配大小，更改字体颜色等操作，最终达到实验要求效果，如红色及粉色：



![在这里插入图片描述](https://img-blog.csdnimg.cn/20190318193129829.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQyMzA0MjY3,size_16,color_FFFFFF,t_70)

![在这里插入图片描述](https://img-blog.csdnimg.cn/20190318193143179.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQyMzA0MjY3,size_16,color_FFFFFF,t_70)



运行结果如下:

![在这里插入图片描述](https://img-blog.csdnimg.cn/20190318193242515.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQyMzA0MjY3,size_16,color_FFFFFF,t_70)

三.TableLayout布局

源代码如下：

tablelayout.xml:

首先，设置总布局，背景颜色等使其符合实验要求标准：


![在这里插入图片描述](https://img-blog.csdnimg.cn/20190318193430178.png)


其次，实现表格中每个分支布局，如Open，下划线及Import：



![在这里插入图片描述](https://img-blog.csdnimg.cn/20190318193906849.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQyMzA0MjY3,size_16,color_FFFFFF,t_70)

![在这里插入图片描述](https://img-blog.csdnimg.cn/20190318193937410.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQyMzA0MjY3,size_16,color_FFFFFF,t_70)


运行结果如下:

![在这里插入图片描述](https://img-blog.csdnimg.cn/20190318194006534.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQyMzA0MjY3,size_16,color_FFFFFF,t_70)
