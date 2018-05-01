# **markdown语法**  
什么是Markdown？Markdown是一种轻量级的「标记语言」，通常为程序员群体所用，目前它已是全球最大的技术分享网站 GitHub 和技术问答网站 StackOverFlow 的御用书写格式。  
就是这十个不到的标记符号，却能让人优雅地沉浸式记录，专注内容而不是纠结排版，达到「心中无尘，码字入神」的境界。  
今天我决定熟悉一下markdown的语法,以后可以用它来记日记,写文章.  
2018年4月22日 天气:绵绵细雨
# 空行的写法
如果上下两行格式相同,回车不会在预览模式另起一行,两个回车会空一行.通用性不知道.需要换行的话,句尾加两个空格再回车.
# 来自官方的教程
可以建议的使用**粗体**和*斜体*.亦可以连接到[github markdown](https://guides.github.com/features/mastering-markdown/)!  ~~此处包含超链接~~  
是不是很简单?  
## 列表
1.优点:提高效率,可读性  
2.缺点:通用性有差异,造成不同平台差异  
### 缩进
- 学习编程
  - 像python
    - 三重缩进
      - 四重缩进!!!

### 图像
引用网络图像  
![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png =100x100)  
标题
> 这是什么  
> 引用某人  

代码  
单行
`print('Hello World!')`  
代码块
```
print('Hello World!')
```  
代码高亮
``` python
print('Hello World!')
```
## 制作待办事项To-do List  
- [x] This is a complete item
- [ ] This is an incomplete item

## github表情  
显示不出来  哈哈  
emoji 表情!  
:sparkles:  
:camel:  
:boom:
## 流程图 平台不兼容
```
graph TD
  A[51劳动节] --> B(放假)
  B --> C{let me think}
```
## 甘特图 平台不兼容
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
## 分割线
***
# 基本语法
强调  
*This text will be italic*  
_This will also be italic_  

**This text will be bold**  
__This will also be bold__

_You **can** combine them_

1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b  

## Inline code
   I think you should use an
   `<addr>` element here instead.
## Strikethrough删除线
<del>**你好**</del>

姓名 | 年龄
---- | ----
whve | 25
