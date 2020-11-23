---
title: Re:0从零开的WebGIS学习(一)《前言》
---

本次带大家了解一下前端开发。

## 《认识前端》

---

### 1. 什么是前端？

前端，一般分为前端设计和前端开发，我这里所说的前端，是前端开发。

在我的理解，前端就是用户能够看到并且可以与之互动的Web应用。（说白了，就是你能看到的，你能点的。）

既然有前段，那么相对的就有后端。后端（数据库、服务器）就是通过接口API向前端提供数据服务。

---

### 2. 什么是前端开发？

前端开发就是通过**HTML**、**CSS**、**JavaScript**这三种开发语言，完成的Web应用。


#### 2.1 HTML简单介绍
**HTML**(Hyper Text Markup Language)，称为**超文本标记语言**。HTML是用来描述Web的，它包括一系列标签的嵌套来完成。

现在，打开你的浏览器。按下F12或者右击空白处点击检查，你就能看到一大堆代码，选择Element，仔细看，下面是不是有一些用<>包含的着的东西。

```
{
    <head>...</head>
    <body>
        <div class="xxx">
        </div>
    </body> 
}
```
像这样的就是HTML。

[HTML入门教程](https://www.runoob.com/html/html-tutorial.html)

#### 2.2 CSS简单介绍
**CSS**(Cascading Style Sheets)，称为**层叠样式表**。  CSS是用来修饰Web的，也就是用来控制Web的外观。

现在，在刚才的附近找一找**Style**这个单词，它下面是不是有一些用{ }包含着的东西。

```
{
    html body {
        width: 1234px;
        height: 1234px;
    }
}
```

像这样的就是CSS。

[CSS入门教程](https://www.runoob.com/css/css-tutorial.html)

#### 2.3 JavaScript简单介绍
**JavaScript**是Web的编程语言，用来为网页添加各式各样的动态功能。

现在，打开浏览器，在之前的HTML下，找一找用<script></script>包裹着的东西。

```
{
    <script>
        function a() {
            let a = docuemnt.getElementById("xxx");
            a.innerHTML = "aaa";
        }
    </script>    
}
```

像这样的就是js。

[JavaScript入门教程](https://www.runoob.com/js/js-tutorial.html)

---

### 3. GIS与前端

GIS与前端的结合就是WebGIS(网络地理信息系统)，是指工作在Web网上的GIS,是传统的GIS在网络上的延伸和发展，具有传统GIS的特点，可以实现空间数据的检索、查询、制图输出、编辑等GIS基本功能，同时也是Internet上地理信息发布、共享和交流协作的基础。

### 4. 就业

#### 4.1 优势/劣势

第一，你要明确自己的专业：**地理信息科学 / 地理信息系统**(Geography Information science / Geography Information System)。

地信的特点就是**地理**与**信息**的结合。你们的老师应该和你们说过亦或者在网上了解到地信能够走两个方向，一个是**开发**，一个是**应用**。

优势：我们相较于专业前端来说，我们最大的优势就是有GIS基础。

劣势：我们相较于专业前端来说，我们的劣势就是计算机能力弱。

#### 4.2 薪资水平

这个大家可以自己去查找，南方的薪资相对来说高一些，至于北方的话，emmm...

互联网的整体薪资水平都还是很不错的。

## 《到此为止》

关于前端开发的事情先说这么多，到此为止，你对前段应该有了基础的了解。如果还是觉得一头雾水，没关系。如果你对前端开发有兴趣的话，不如收藏这个网址(因为只是部署到了github，所以公网上，无法搜索到)，或者可以分享给你身边的想要学习前端的同学们。先就这样，再见！