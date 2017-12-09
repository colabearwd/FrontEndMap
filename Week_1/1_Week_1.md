---
date: 2017-11-04 14:24
status: public
title: 1_Week_1
---

#第一章 初级课程
##第1天 html

1、HTTP协议
####移步[HTTP协议详解](/HTTP协议.md)
2、html是纯文本
3、html骨架
6、body标签
7、html基本语法
>`<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>菜鸟教程(runoob.com)</title>
</head>
<body>
    <h1>我的第一个标题</h1>
    <p>我的第一个段落。</p>
</body>
</html>
`  

4、DTD文档类型
************未看懂
- - -
5、head标签
    http://101.132.155.48/wordpress/?p=48
####移步[Head标签](/head标签.md)
8、h系列的标签
9、p标签
	http://101.132.155.48/wordpress/?p=39
10、img标签
11、a标签
	http://101.132.155.48/wordpress/?p=50

12、div和span含义
	http://101.132.155.48/wordpress/?p=54
第2天 html

1、无序列表
2、有序列表
3、定义列表
	http://101.132.155.48/wordpress/?p=46
6、表格基础
7、合并单元格
	http://101.132.155.48/wordpress/?p=41
8、三个划分区域的语义标签
	http://101.132.155.48/wordpress/?p=94
10、input标签
	 http://101.132.155.48/wordpress/?p=74	 
9、form标签	 
11、单行文本框
13、密码框
14、单选框
15、多选框
16、文本域
18、按钮
17、下拉菜单
	 http://101.132.155.48/wordpress/?p=52
第3天 css

1、html注释
2、废弃标签
3、实体字符
	http://www.runoob.com/tags/ref-entities.html
4、css的概念
5、css的作用
6、css的样式
7、css的书写位置

8、基础选择
9、高级选择器
	选择器，速查
	http://www.w3school.com.cn/cssref/css_selectors.asp
	
	id选择器
		#para1  { text-align:center; color:red; } 
	class选择器	
		.center { text-align:center; } 
	属性选择器
		[title] { color:blue; }
		input[type="text"]  {	background-color:yellow;   }

10、css的继承性
11、css的层叠性
**************没看懂


第4天 css
1、color属性
	<style> 
		body {color:red;}
		h1 {color:#00ff00;}
		p.ex {color:rgb(0,0,255);}
	</style>
2、font-size属性
	h1 {font-size:250%}
	h2 {font-size:200%}
	p {font-size:100%} 
		元素的大小，默认值为medium
		xx-small
		x-small
		small
		medium
		large
		x-large
		xx-large
		比父元素
		smaller
		larger
	
3、font-family属性
	p{font-family:"Times New Roman",Georgia,Serif;} 
4、line-height属性
	大多数浏览器段落的行高是20px
	p.small	{ line-height: 10px}
5、font-weight属性
	p.normal {font-weight:normal;}
	
	normal 	默认值。定义标准的字符。
	bold 	定义粗体字符。
	bolder 	定义更粗的字符。
	lighter 定义更细的字符。
6、font-style属性
	p.normal {font-style:normal}
	
	normal 	默认值。浏览器显示一个标准的字体样式。
	italic 	浏览器会显示一个斜体的字体样式。
	oblique 	浏览器会显示一个倾斜的字体样式。
	inherit 	规定应该从父元素继承字体样式。
7、text-indent属性 段落的首行缩进
	p { text-indent:50px;} 
	
8、text-align属性
	h1 {text-align:center;}
	p.date {text-align:right;}
	p.main {text-align:justify;}
9、text-decoration属性
	h1 {text-decoration:overline;}
	h2 {text-decoration:line-through;}
	h3 {text-decoration:underline;}
	h4 {text-decoration:blink;}        定义闪烁的文本。
	

10、盒模型的初步认识
11、padding详解
12、margin详解
13、border详解
	 http://101.132.155.48/wordpress/?p=103

第5天 css

1、盒模型的拓展知识
	 http://101.132.155.48/wordpress/?p=103
2、清除默认样式
	 http://101.132.155.48/wordpress/?p=112
3、宽度剩余法
	 https://github.com/colabearwd/Blog_Wechat_Example/blob/master/width%20surplus%20method/01.html
4、height高度设置法
		
5、margin特性之垂直方向上的塌陷
	高度塌陷的情况只会存在于垂直方向
　　存在高度塌陷的情况：父与子之间存在高度塌陷、相邻子元素之间存在高度塌陷

　　在父元素没有给padding、border，或者父元素是非块状格式化的上下文元素、或者父和子元素之间没有inline元素分离，此时如果给子盒子加margin值，在界面上并不会显示出来，如果需要显示，只要破坏上述条件之一即可

　　相邻元素之间会存在高度塌陷情况：当两个元素有同正数的margin的时候，他们之间的距离是最大的margin值；当两个元素有一正一负的margin的时候，他们之间的距离是两数之和；当两个元素的margin都是负数的时候，则他们之间的距离，是绝对值较大的那个数值

　　技巧：我们在写列表的时候，一般会写间距的时候，只会给上间距或者下间距，其实我们可以利用高度塌陷这个特性，上下间距都写上，这样即使页面有一点变动，也不会影响整体的效果

6、margin特性之不能用儿子去踹父亲
	善于使用父亲的padding，而不是儿子的margin
	如果父亲没有border,那么儿子的margin实际上踹的是“流”，所以父亲也掉下来了。
	
7、父子盒模型的特性

8、居中的几种设置方法
	http://www.imooc.com/article/5199
9、认识标准文档流
10、标准文档流的特性

11、块级元素和行内元素的特性
	http://101.132.155.48/wordpress/?p=54



第6天 css
12、浮动的基础知识
	http://blog.csdn.net/helllochun/article/details/51615136
1、浮动的作用

2、浮动的特性之浮动的元素脱离标准文档流

3、浮动的特性之浮动的元素没 有margin塌陷

4、浮动的特性之浮动的元素依次贴边

5、浮动的特性之浮动的元素让出标准流的位置

6、浮动的特性之字围效果

7、浮动存在的问题


8、清除浮动的方法之给父盒子加高度
9、清除浮动的方法之加clear属性
10、清除浮动的方法之加隔墙法
11、清除浮动的方法之overflow法
	http://www.cnblogs.com/AnotherLife/p/5800751.html
	http://www.jianshu.com/p/09bd5873bed4
第7天 css

1、a标签的伪类
2、a标签伪类的顺序不能颠倒
http://101.132.155.48/wordpress/?p=114
3、a标签伪类的应用实例之按钮实例
https://github.com/colabearwd/Blog_Wechat_Example/blob/master/pseudo%20class/a%20pseudo%20class.html
4、a标签伪类的应用实例之导航栏实例
https://github.com/colabearwd/Blog_Wechat_Example/blob/master/pseudo%20class/nav.html
5、background-color背景色的详解
6、background-image背景图的详解
7、background-repeat背景重复的详解
8、background-position背景定位的详解
10、background-attachment背景固定的详解
	http://101.132.155.48/wordpress/?p=117
9、精灵图的使用方法及案例
	***********不知道什么意思
11、背景的应用之 文字换图片案例
	***********不知道什么意思
12、背景的应用之 padding设置背景图案例
	***********不知道什么意思
https://github.com/colabearwd/Blog_Wechat_Example/blob/master/background/bg%20padding.html