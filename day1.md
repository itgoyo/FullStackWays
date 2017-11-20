# Html基础
```
超链接: <a href=""> xxx </a>
xxx 可以是文字也可以是图片
```
超链接: <a href="">jump 01</a>

超链接: <a href="http://www.baidu.com"> <img src="1.jpg"> </a>

属性:
- title 设置鼠标悬停到超链接上的文字
- target :
 - _self 默认值在当前页面中打开新页面
 - _black 在新窗口中打开页面

全局在打开新窗口
```
<head>
<base target="_black">
</head>
```

锚链接:属于超链接的另外一种用法,实现的是本页面的跳转
<div id="xl"> (*^__^*)</div>

<a href="#xl"> 找笑脸去 </a>

&lt  : <

&gt  : >

![](http://omvbl46i3.bkt.clouddn.com/17-11-20/31703555.jpg)

Transitional 过度的  可包含所有的元素和属性

Strict 精确的  包含所有的元素和属性,但不包含被废弃的标签 如:

- font
- b
- i
- align

## html5

导航标签 :<nav> </nav>
区域 : <section> </section>
底部 : <footer> </footer>
侧边栏 : <aside> </aside>
文章 : <article> </aticle>
视频 : <video> </video>
```
<video src="movie.mp4" controls autoplay loop> </video>
```
- controls 显示控制面板
- autoplay 自动播放
- loop 循环
