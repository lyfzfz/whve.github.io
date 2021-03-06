# **markdown简介**  
什么是Markdown？Markdown是一种轻量级的「标记语言」，通常为程序员群体所用，目前它已是全球最大的技术分享网站 GitHub 和技术问答网站 StackOverFlow 的御用书写格式。  
就是这十个不到的标记符号，却能让人优雅地沉浸式记录，专注内容而不是纠结排版，达到「心中无尘，码字入神」的境界。  
今天我有必要熟悉一下markdown的语法,以后可以用它来记日记,写文章.  
2018年4月22日 天气:绵绵细雨
# **语法**
[本文地址](https://github.com/whve/whve.github.io/tree/master/a/markdown)
# 空行的写法-经验之谈
1. 如果上下两行格式相同,回车不会在预览模式另起一行,两个回车会空一行.
1. 需要换行的话,句尾加两个空格再回车.
1. 以上可以自己演示.

# 来自官方的教程[github markdown](https://guides.github.com/features/mastering-markdown/)
`**粗体**`-->**粗体**  
`*斜体*`-->*斜体*.  
 or  
 `__粗体__`-->__粗体__  
 `_斜体_`--> _斜 体_ .  
or  
 `_You **can** combine them_`-->
 _You **can** combine them_
## 列表
```
1. 优点:提高效率,可读性  
1. 缺点:通用性有差异,造成不同平台差异  
```

1. 优点:提高效率,可读性  
1. 缺点:通用性有差异,造成不同平台差异  

```
1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b  
```

1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b  

### 缩进

```
- 学习编程
  - 像python
    - 三重缩进
      - 四重缩进!!!
```
- 学习编程
  - 像python
    - 三重缩进
      - 四重缩进!!!

### 图像
**引用网络图像**  

```
![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)  
```

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)  

**引用本地图像**  
`![](images/han.jpg)`注:images文件夹与该.md文件同目录
![Image of Yaktocat](images/yaktocat.png)  

#### 调整图片大小在GitHub上显示
``` html
<img src="https://octodex.github.com/images/yaktocat.png" width = "300" height = "" alt="yaktocat"  align=center />
```
效果: 本地在线效果相同  
<img src="https://octodex.github.com/images/yaktocat.png" width = "300" height = "" alt="yaktocat"  align=center />
<img src="images/yaktocat.png" width = "300" height = "" alt="yaktocat"  align=center />
## 引用

```
> 这是什么  
> 引用某人  
```
> 这是什么  
> 引用某人

代码单行==Inline code  

```
`print('Hello World!')`  
```
效果  
`print('Hello World!')`  

代码块展现源代码


```
print('Hello World!')
```  
代码高亮+空格+python

``` python
print('Hello World!')
```
## 制作待办事项To-do List  
```
- [x] This is a complete item
- [ ] This is an incomplete item
```

- [x] This is a complete item
- [ ] This is an incomplete item

## github表情  
在github上显示:   
:sparkles:  
:camel:  
:boom:

## 分割线
```
---
***
```
---
***


## Strikethrough删除线
```
~~妳好~~
<del>你好</del>
```
~~妳好~~  
<del>你好</del>
## 表格
```
姓名 | 年龄
---- | ----
whve | 25
```

姓名 | 年龄
---- | ----
whve | 25

# 特殊用法
## 有道云笔记-流程图 平台不兼容
```
graph TD
  A[51劳动节] --> B(放假)
  B --> C{let me think}
```

## 有道云笔记-甘特图 平台不兼容
```
gantt
dateFormat YYYY-MM-DD
title 就这样毁了自己的一生
section 初期
无忧童年:1993-10-14,3650d
section 中期
回忆过往:2003-10-14,3650d
section 晚期
无尽凉凉:2013-10-14,3650d
```
