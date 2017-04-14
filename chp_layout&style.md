\# 准备工作： Stylus & Flexbox



Quasar 提供了两款主题：mat & ios，mat能兼容PC端和移动端，用户可以任意定制和修改。

样式均由Stylus写就，戳\[这里\]\(http://www.zhangxinxu.com/jq/stylus/\)学习Stylus。



传统布局模型缺乏支持大型或复杂应用的弹性，特别是当应用涉及到方向变化、大小调整、拉伸、收缩等情形。弹性盒布局模型能很好的解决这些问题。



弹性盒布局模型\(Flexbox module\)是W3C当前的最新工作草案，旨在提供更有效的布局、对齐和给容器内元素分配空间的方法，甚至是元素的尺寸未知或者动态变化的情形，这就是所谓的‘弹性’。

弹性盒布局模型背后的主要思想是赋予容器改变它内部元素高、宽、排布的能力，以使其能最好的填充可用空间（主要是适配各种显示设备和屏幕尺寸）。

一个弹性容器能扩展其内部元素使其充满剩余可用空间或缩小其内部元素尺寸以防止其溢出。

弹性盒布局是方向无关的，这和传统的布局方式不同：block布局是垂直方向的，inline布局是水平方向的。

学习\[CSS弹性盒模型\]\(http://www.ruanyifeng.com/blog/2015/07/flex-grammar.html\)。



\# Quasar网格布局（Qusar Grid layout）



Quasar提供了很多CSS类帮助我们轻松实现布局。可以简单地把这种布局方式理解为table的行列布局。



\#\#\#\# 1. Qusar 定义的颜色：

!\[主要颜色\]\(/assets/pic\_colors\_1.png\)

根据颜色深浅，每种颜色分16级\(red, red-1, red-2, ..., red-15\);

每种颜色可用于颜色（text-red）和背景\(bg-red\);



\#\#\#\# 2. Qusar 定义了4种屏幕尺寸：

1. width &lt;= 600px : 小屏（sm）

2. width &gt; 601px && width &lt;= 920px : 中屏\(md\)

3. width &gt; 921px && width &lt;= 1280px : 大屏\(bg\)

4. width &gt; 1281px : 超大屏\(lg\)



\#\#\#\# 3. Qusar 定义了6种屏幕区间：

1. width &gt; 601px : gt-sm

2. width &lt; 600px : lt-sm

3. width &gt; 921px : gt-md

4. width &lt; 920px : lt-md

5. width &gt; 1281px: gt-lg

6. width &lt; 1280px: lt-lg



\#\#\#\# 4. Qusar 定义了4种槽（类似列间距）样式

1.





