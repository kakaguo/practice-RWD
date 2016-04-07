# practice-RWD
a practice of responsible website design

<!-- 总体思路 
1.采用Mobile First原则，创建grid-based形式的layout.css。
2.背景图采用自适应缩放。
3.采用Media queries实现在不同尺寸的设备中，显示对应的页面。


具体介绍：
1.采用Mobile First原则，创建grid-based形式的layout.css。
页面布局：1)先设置outer rows(将页面垂直划分为不同的部分);
	  2)设置rows中container，宽度按需求分为wide/medium/narrow,同时实现页面居中;
 	  3)设置container中col,宽度按需求分为wide/medium/narrow。

2.背景图采用自适应缩放。
通过background-size：container可实现图片包含在该container里自适应。

3.采用Media queries实现在不同尺寸的设备中，显示对应的页面。
@media：1)不同的屏幕尺寸对应不同的背景图;
	2)不同的屏幕尺寸对应不同的字体大小;
	3)不同的margin和padding值;
	4)结合在HTML中添加的相应的类，在layout.css和modules.css中对不同的屏幕尺寸进行分别设置。
	
-->
