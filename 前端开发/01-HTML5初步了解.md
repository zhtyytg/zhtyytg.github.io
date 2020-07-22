# Web前端入门

## HTML5入门

## 网页的基本组成

文本、超链接、二进制文件(图片、音频、视频)等==元素==组成

## 什么是HTML

hyper text markup language 超文本标记语言  
用标记标签组成网页  
采用超文本方式将各个文件元素串联在一起

## 常用的浏览器(内核)

浏览器内核(渲染引擎)：负责读取网页内容，整理讯息，计算网页的显示方式并显示页面

chrome(Blink 是WebKit的分支)、firefox(Gecko)、IE(Trident)、Edege、Safari(WebKit)、Opera(Blink)、国产浏览器一般采用WebKit或Blink

## Web标准的三大组成部分~~HTML、CSS、JS~~

==Web标准==是W3C(万维网联盟)组织和其他标准化组织制定的一系列标准的集合，目的是统一不同浏览器的页面，降低软硬件限制

==Web标准==是由结构Structure、表现Presentation、行为Behavior组成的，结构>>HTML，表现>>CSS，行为>>javascript

## HTML标签

## 目标

1. 标签的书写注意规范
2. 写出HTML骨架标签
3. 写出超链接标签
4. 写出图片标签并说出alt和title的区别
5. 说出相对路径的三种形式

## 主要内容

### HTML语法规范：标签闭合

```html
<html>
    <br>
<html>
```

### HTML基本结构标签

```html
<html><!--	页面中最大的标签，称为root标签	-->
    <head><!--	文档的头部	-->
        <title>第一个页面</title><!--	文档的标签，页面标签名	-->
    </head>
    <body><!--	文档内容，存放页面基本内容	-->
        键盘敲烂，工资过万
    </body>
</html>
```

### 开发工具

dream wave、Hbuilder、VS code、Sublime Text。。。

### HTML常用标签

#### 标题标签\<h1> - \<h6>

1. 文字会变大
2. 标题独占一行

#### 段落标签和换行标签

- 段落标签\<p> - \</p>

  段落和段落中会有较大缝隙

- 换行标签\<br>

#### 文本格式化标签

1. 加粗\<strong>
2. 倾斜\<em>
3. 删除线\<del>
4. 下划线\<ins>

#### div和span标签：普通的盒子元素

#### 图像标签\<img>

1. src 引用路径
2. alt 加载失败时显示的文字
3. title 鼠标移动到图片上方时显示文字
4. height、width 宽高
5. border 边框设置

#### 链接标签\<a>

1. href URL地址
2. target URL打开方式，默认_self 在当前标签打开，\_blank 在新标签打开
3. 锚点链接 href = "#目标元素ID" 快速跳转到页面某个元素的位置

### HTML中的注释和特殊字符

## CSS3基础

## H5C3提高

## 项目-品优购电商网站
