当文章有分类，需要快速阅读，通常会先在文首部写一个目录，点击可以跳转。
为文章写目录，特别在文章较长的时候，有助于对内容的整体把握，能提高阅读效率。

以下，将写一个基本的锚目录demo，然后特别说明需要注意的几点。

**Table Of Content**
* [1. Demo](#demo)
* [2. markdown 的锚使用中需要特别注意的几点](#markdown-的锚使用中需要特别注意的几点)

## Demo

---
### **Table Of Contents**
**[Installation Instructions](#installation-instructions)**
**[Usage Instructions](#usage-instructions)**
**[Troubleshooting](#troubleshooting)**
**[Compatibility](#compatibility)** 
**[Notes and Miscellaneous](#notes-and-miscellaneous)** 
**[Building the Extension Bundles](#building-the-extension-bundles)**
**[Next Steps, Credits, Feedback, License](#next-steps)**
<a href="#test">Something you should know</a> 

## Installation Instructions

blablablabla

## Usage Instructions

blablablabla

## Troubleshooting

blablablabla

## Compatibility

blablablabla

## Notes and Miscellaneous

blablablabla

## Building the Extension Bundles

blablablabla

## Next Steps

blablablabla

## Credits

blablablabla

## Feedback

blablablabla


<a name="test">用htmla标签实现的锚链接</a>
除了用markdown中的锚定义，我们还可以在需要的时候使用html中的a链接的name属性。实现传统的锚点。

```html
//点击：
<a href="#test">Something you should know</a>
//跳转至：
<a name="test">用htmla标签实现的锚链接</a>
````

---

## <mark>注意：</mark>markdown 的锚使用中需要特别注意的几点

### 语法
目录(Table Of Content)

```j

[链接的value值，任意名称](#*1 anchor-name)

```

锚

```j

#*n Anchor Name

//可以是一级标题、二级、三级····
```


### 1. 命名规则
#### 在目录中：

* 链接的名称anchor-name必须全部是小写的，和锚中的名称不区分大小写匹配
* anchor-name对应的锚的名称中的空格要用`“-”`替换
* anchor-name不能含有`“:”`、`“()”`、`“.”`、`%`、`$` 等等特殊字符，最好就不要有任何字符
* 目录的部分可以是多种样式，例如斜体，粗体，本身都是等级标题，甚至列表元素都行

#### 在锚中：
(指的是正文的标题)
* 不能含有`“:”`、`“()”`、`“.”`等字符
* 锚不能是列表元素，例如无序列表`*`
* 锚只要是标题就行，他可以是任意等级

![](https://img2018.cnblogs.com/blog/1735896/201912/1735896-20191218163649372-80753162.png)

### 2. 如果锚需要特殊符号该怎么办？

写url的时候anchor-name 直接跳过全部的特殊字符即可，如下示例：

![](https://img2018.cnblogs.com/blog/1735896/201912/1735896-20191219010907128-1461882156.png)
![](https://img2018.cnblogs.com/blog/1735896/201912/1735896-20191219010923098-1952167715.png)



<ud>==本文源markdown文档可以在这里查看:[Link](https://raw.githubusercontent.com/jaycethanks/platform/master/cnblog/jaycethanks/markdownFile/markdown%E4%B8%AD%E9%94%9A%E9%93%BE%E6%8E%A5%E5%AE%9E%E7%8E%B0%E7%9B%AE%E5%BD%95%E8%B7%B3%E8%BD%AC%E4%BB%A5%E5%8F%8A%E6%B3%A8%E6%84%8F%E4%BA%8B%E9%A1%B9.md)==</ud>
