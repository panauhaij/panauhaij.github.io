## Markdown语法
Markdown是一种轻量级标记语言，由约翰·格鲁伯（John Gruber）于2004年创建，其优点包括简洁易读、易于学习、可转换性强、便于协作以及可扩展性，如今已成为世界上最受欢迎的标记语言之一。

## 扩展语法速查
[Markdown扩展语法速查](https://blog.auhaijpan.top/post/Markdown-kuo-zhan-yu-fa-su-cha.html)

# 标题
使用 `#` 表示标题，数量表示标题级别；例如：
```
# 一级标题
## 二级标题
### 三级标题
```
也可以通过在标题下方添加等号 `=` 或连字符 `-` 来创建一级和二级标题；例如：

```
一级标题
=========

二级标题
----------
```

# 段落
段落之间需要通过一个或多个空行进行分隔；例如：
```
这是第一段。

这是第二段。
```
# 换行
如果想在同一段落中强制换行，可以在行尾加上两个或更多空格 `space` ，然后回车 `Enter` ；例如：
```
中国人的性情是总喜欢调和、折中的。譬如你说，  
这屋子太暗，须在这里开一个窗，大家一定不允许的。  
但如果你主张拆掉屋顶，他们就会来调和，愿意开窗了。  
没有更激烈的主张，他们总连平和的改革也不肯行。  
那时白话文之得以通行，就因为有废掉中国字而用罗马字母的议论的缘故。
```
# 强调
## _斜体_
使用单个星号 `*` 或下划线 `_` 包裹文本；例如：

`*这是斜体* 或 _这是斜体_`
## **粗体**
使用两个星号 `**` 或下划线 `__` 包裹文本；例如：

`**这是粗体** 或 __这是粗体__`
## **_粗斜体（两种都用）_**
使用三个星号 `***` 或下划线 `___` 包裹文本；例如：

`***粗体和斜体*** 或 ___粗斜体混用___`
# 引用
使用大于符号 `>` 来实现。每段引用都需要在行首加上 `>` ；例如：
```
>腾蛟起凤，孟学士之词宗；
>紫电青霜，王将军之武库。
```
>腾蛟起凤，孟学士之词宗；
>紫电青霜，王将军之武库。

同时也可以嵌套引用，只需在每一层都多添加一个 `>` ；例如：
```
>惜秦皇汉武，略输文采；
>唐宗宋祖，稍逊风骚。
>>一代天骄，成吉思汗，只识弯弓射大雕。
>>>俱往矣，数风流人物，
>>>还看今朝。
```
>惜秦皇汉武，略输文采；
>唐宗宋祖，稍逊风骚。
>>一代天骄，成吉思汗，只识弯弓射大雕。
>>>俱往矣，数风流人物，
>>>还看今朝。

# 列表
列表分为无序列表和有序列表；缩进（至少两个空格）可以用于创建嵌套列表。

## 无序列表
使用星号  `*` 、加号 `+` 或减号 `-` 来创建无序列表：

```
* 项目 1
* 项目 2
  * 子项目 2.1
  * 子项目 2.2
```
* 项目 1
* 项目 2
  * 子项目 2.1
  * 子项目 2.2

## 有序列表
使用数字加英文的句点 `.` 来创建有序列表：

```
1. 项目 1
2. 项目 2
   1. 子项目 2.1
   2. 子项目 2.2
```
1. 项目 1
2. 项目 2
   1. 子项目 2.1
   2. 子项目 2.2

# 代码
可以使用反引号 `` ` `` 来标记代码。（如果文本中包含反引号，可以使用多个反引号来包裹代码，以避免冲突）

## 行内代码
使用单个反引号包裹代码：

```这是 `行内代码` 示例。```

这是 `行内代码` 示例。
## 代码块
使用三个反引号来包裹多行代码块，也可以指定语言以启用语法高亮：

````
```
这是一个代码块。
```
````


```
这是一个代码块。
```
或者指定语言来启用代码高亮：

````
```python
def hello_world():
    print("Hello, world!")
```
````
```python
def hello_world():
    print("Hello, world!")
```
这样可以使代码更具可读性。

# 分隔线
在单独一行中使用三个或更多的短横线 `-` 、星号 `*` 或下划线 `_` 来分隔内容。例如：
```
---
***
___
```
---
***
___

# 链接
格式为`[链接文本](链接地址)`。例如：

`点击跳转[必应搜索](https://cn.bing.com/)`

点击跳转[必应搜索](https://cn.bing.com/)
# 图片
格式为`![替代文本](图片地址)`。（替代文本（alt text）用于描述图像内容。当图像无法加载时，就会显示替代文本）例如：

`![博客头像](https://avatars.githubusercontent.com/u/150444021?v=4)`

![博客头像](https://avatars.githubusercontent.com/u/150444021?v=4)
<br>
<br>
<br>
<br>
> 相关链接：
> - [Markdown 基本语法](https://markdown.com.cn/basic-syntax/)
> - [Basic Syntax | Markdown Guide](https://www.markdownguide.org/basic-syntax/)