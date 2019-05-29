# 百度前端技术学院练习作业 #


## day5-6 三种简历 ##
保证resume.html中引用的css文件，无论是style_1.css 还是 style_2.css 或是 style_3.css，都可以保证页面按照设计稿的要求呈现。也就是说同一份HTML，可以在改变CSS代码的情况下，实现不同样式，达到HTML结构内容和CSS样式的解耦。

**style_1.css**

![](https://b.bdstatic.com/searchbox/icms/searchbox/img/resume1.png)

**style_2.css**

![](https://b.bdstatic.com/searchbox/icms/searchbox/img/resume2.png)

**style_3.css**

![](https://b.bdstatic.com/searchbox/icms/searchbox/img/resume3.png)

## day6-7 学习布局 ##

参考如下设计稿实现HTML页面及CSS样式：链接: https://pan.baidu.com/s/1IndqG9nanVhKxwysibZZRg 密码: vfs6

设计稿描述：

1.设计稿分为头部，中间的Banner，主导航，内容区域，底部

2.头部区域为100%宽的一个深色背景，头部中间有一块960px的定宽居中区域，里面包括了左边的Logo和右上角导航

3.Banner为100%宽的区块，中间右下方有banner轮显的当前图片数字的示例，其中正在显示的图片对应的数字有特殊样式（注意不需要实现轮显banner的业务逻辑，只是按照设计稿做静态样式）

4.主导航区域，有一个100%宽的灰色线条，线条之上，在中间960px区域是导航菜单，当前正在浏览页对应的菜单有特殊样式

5.主要内容区域，宽度为960px，里面每个内容都有至少80px的padding，每一个内容的宽度均为自适应，可以使用flex布局

