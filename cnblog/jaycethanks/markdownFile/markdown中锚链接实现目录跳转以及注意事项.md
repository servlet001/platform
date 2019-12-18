当文章有分类，需要快速阅读，通常会先在文首部写一个目录，点击可以跳转。
为文章写目录，特别在文章较长的时候，有助于对内容的整体把握，能提高阅读效率。

以下，将写一个基本的锚目录demo，然后特别说明需要注意的几点。

**Table Of Content**
* [1. Demo](#demo)
* [2. markdown 的锚使用中需要特别注意的几点](#markdown-的锚使用中需要特别注意的几点)

## Demo
---
### **Table Of Contents**
**[Installation Instructions](#installation-instructions)**</br>
**[Usage Instructions](#usage-instructions)**</br>
**[Troubleshooting](#troubleshooting)**</br>
**[Compatibility](#compatibility)** </br>
**[Notes and Miscellaneous](#notes-and-miscellaneous)** </br>
**[Building the Extension Bundles](#building-the-extension-bundles)**</br>
**[Next Steps, Credits, Feedback, License](#next-steps)**</br>
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

## markdown 的锚使用中需要特别注意的几点

**语法**
目录(Table Of Content)

```j

[链接的value值，任意名称](#*1 anchor-name)

```

锚

```j

#*n Anchor Name

//可以是一级标题、二级、三级····
```

<mark>注意：</mark>
在目录中：

* 链接的名称anchor-name必须全部是小写的，和锚中的名称不区分大小写匹配
* 对应的锚的名称中的空格要用`“-”`替换
* 不能含有`“:”`、`“()”`、`“.”`等字符，最好就不要有任何字符
* 目录的部分可以是多种样式，例如斜体，粗体，本身都是等级标题，甚至列表元素都行

在锚中：

* 不能含有`“:”`、`“()”`、`“.”`等字符
* 锚不能是列表元素，例如无序列表`*`
* 锚只要是标题就行，他可以是任意等级

![](https://img2018.cnblogs.com/blog/1735896/201912/1735896-20191218163649372-80753162.png)
