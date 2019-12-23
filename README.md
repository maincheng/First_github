# First_github
主题：鱼 运行地址：https://maincheng.github.io/First_github/login.html
## Fish
使用HTNL、CSS和js开发的一个个人网页，整个网页内容以鱼为主题来实现HTML的一些基础功能。
## 登录界面
登录页面使用了cookie功能可实现`记住我`的功能，另外使用了jquery来判断用户名和密码是否为空。
![](https://github.com/maincheng/First_github/raw/master/img/Screenshots_1.png)
* cookie设置了记住用户名和密码30天
* 调用jquery-3.4.1.min.js对用户名和密码进行判断
## 主页面
主页面的色调为暖色，渐变，使用了嵌套布局，内部多处使用弹性布局。主页面的内容包括：<br>
* 侧边栏：使用了纯CSS写了一个左侧边栏，包括块元素和内联块状盒子，以及固定定位、伪类。初始为-200px隐藏，点击后配合动画效果ease-out有渐变效果；鼠标悬停有颜色变化提示。<br>
![](https://github.com/maincheng/First_github/raw/master/img/Screenshots_2.png)<br><br>
* 页头：标题为英文Fish，下方为欢迎语，然后是一个传统的导航栏。同样在导航栏部分增添样式使其更为舒适：取消链接下划线，使用伪类设置鼠标划过链接颜色，`li`之间插入竖线图分割。并且使用图标字体。<br>
![](https://github.com/maincheng/First_github/raw/master/img/Screenshots_3.png)<br><br>
* 图片跑马灯：利用js代码对一组图片实现跑马灯效果，鼠标停留图片停止滚动，离开后继续滚动。<br>
![](https://github.com/maincheng/First_github/raw/master/img/Screenshots_4.png)<br><br>
* 文本内容：该部分使用了浮动布局和响应式设计。<br>
![](https://github.com/maincheng/First_github/raw/master/img/Screenshots_5.png)<br><br>
* Story：该部分为图片链接，链接后可查看有关的故事内容。<br>
![](https://github.com/maincheng/First_github/raw/master/img/Screenshots_6.png)<br><br><br>
## 图片页面
该页面向用户展示一下金鱼的照片，加入响应式设计。<br>
## 种类页面
该页面主要为文字内容，向用户介绍了鱼类的一些大致情况，以及金鱼的种类和相关介绍。<br>
## Story页面
该页面主要基于ajax实现了文件包含技术，减少了大量的重复，共享了站点头代码，并读取了故事的文本文件，降低了文本维护的成本。<br>
![](https://github.com/maincheng/First_github/raw/master/img/Screenshots_9.png)<br><br><br>
## 目录详解
```
├──login.html   登录页面
├──fish.html    项目的主页面
├──picture.html   图片页面，内含多组图片
├──kind.html    种类页面，文字较多
├──story_1.html   与鱼相关的故事或文章，下面几个同。
├──story_2.html ***
├──story_3.html ***
├──story_4.html ***
├──css    样式部分
    ├──login.css  登录页面样式部分
    ├──style.css  项目主要样式部分
    ├──cebianlan.css  侧边栏样式部分
    ├──paomadeng.css  跑马灯功能样式部分
├──font-awesome   图标字体库
├──js   js代码部分
    ├──jquery-3.4.1.min.js
    ├──paomadeng.js   实现跑马灯
├──img    项目图片
├──tpl
    ├──Untitled-1.tpl   站点头代码
    ├──story_1/2/3/4.tpl    故事文本文件
```
