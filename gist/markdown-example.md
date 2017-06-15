[TOC]

# 标题（一级标题）

## 标题（二级标题）

......

###### 标题（最小的六级标题）


# 列表

## 无序列表
- 这是无序列表项目
- 这是无序列表项目
- 这是无序列表项目
    - 嵌套列表项目
    - 嵌套列表项目
        - 嵌套列表项目
        - 嵌套列表项目
* 这是无序列表项目
* 这是无序列表项目
* 这是无序列表项目
+ 这是无序列表项目
+ 这是无序列表项目
+ 这是无序列表项目

## 有序列表
1. 这是有序列表项目
1. 这是有序列表项目
3. 这是有序列表项目
8. 这是有序列表项目


# 段落

## 换行
单个回车，这里->
视为空格。

连续回车

才能分段。

行尾加两个空格，这里->  
即可段内换行。

## 强调
*这些文字显示为斜体*

**这些文字显示为粗体**

__这些文字也显示为粗体__

~~删除这些字~~

## 分隔线
---
上面是一条分隔线

## 引用
使用 email 形式的区块引言

> ## This is a header.
> 
> 1.   This is the first list item.
> 2.   This is the second list item.
> 
> Here's some example code:
> 
>     return shell_exec("echo $input | $markdown_script");
> > This is nested blockquote.

# 代码

## 单行

`echo xx > /tmp/test.log`


## 代码段
使用 **```**开头和结束，或者行的开头空4个空格。

```go
package main

import "fmt"

func main() {
    fmt.Println("hello world")
}
```

    //这里显示一些代码，在正文显示中会自动识别语言，进行代码染色，这是一段C#代码
    public class Blog
    {
         public int Id { get; set; }
         public string Subject { get; set; }
    }


# 表格

## 基本表格

name | age
---- | ---
LearnShare | 12
Mike |  32


## 对齐

| left | center | right |
| :--- | :----: | ----: |
| aaaa | bbbbbb | ccccc |
| a    | b      | c     |

## 表格中插入其他行内标记

|     name     | age |             blog                |
| ------------ | --- | ------------------------------- |
| _LearnShare_ |  12 | [LearnShare](http://xianbai.me) |
| __Mike__     |  32 | [Mike](http://mike.me)          |


# 链接

## URL
<https://github.com/>  
[怎样使用Markdown](http://www.ituring.com.cn/article/23)  
[图灵社区][1]

## 图片
![这是一个Logo图像](http://www.turingbook.com/Content/img/Turing.Gif)  
![图灵社区Logo][2]

# 其他
* 转义字符。使用 `\`


# 分享点私货 —— git + markdown + 文本编辑器 搭建个人知识库

好记性不如烂笔头。

## 优点
* 全局搜索
* 版本管理
* 统一的编辑环境、语法。

## git 代码托管推荐
私库 gitlab.com，公开库 github.com。


# 参考
[怎样使用Markdown](http://www.ituring.com.cn/article/23)  
[Markdown: Basics （快速入门）](http://wowubuntu.com/markdown/basic.html)
[Markdown 语法说明 (简体中文版)](http://wowubuntu.com/markdown/index.html)


[1]:http://www.ituring.com.cn
[2]:http://www.ituring.com.cn/Content/img/Turing.Gif