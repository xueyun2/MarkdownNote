# 1. Markdown笔记

官方教程：<https://markdown.com.cn/extended-syntax/emoji.html>

- [1. Markdown笔记](#1-markdown笔记)
  - [1.1. 标题](#11-标题)
  - [1.2. 段落](#12-段落)
  - [1.3. 强调语句](#13-强调语句)
    - [1.3.1. 粗体（Bold）](#131-粗体bold)
    - [1.3.2. 斜体（Italic）](#132-斜体italic)
  - [1.4. 引用语法](#14-引用语法)
  - [1.5. 列表](#15-列表)
    - [1.5.1. 有序列表](#151-有序列表)
    - [1.5.2. 无序列表](#152-无序列表)
  - [1.6. 代码语法](#16-代码语法)
    - [1.6.1. 单个单词](#161-单个单词)
    - [1.6.2. 多行代码块](#162-多行代码块)
  - [1.7. 脚注](#17-脚注)
  - [1.8. 标题编号](#18-标题编号)
    - [1.8.1. 点击标题跳转到另一个文件](#181-点击标题跳转到另一个文件)
  - [1.9. 删除线](#19-删除线)
  - [1.10. 任务列表语法](#110-任务列表语法)
  - [1.11. 使用 Emoji 表情](#111-使用-emoji-表情)
  - [1.12. 使用图片](#112-使用图片)
  - [1.13. 在文档中添加链接跳转](#113-在文档中添加链接跳转)
  - [1.14. 表格](#114-表格)
    - [1.14.1. 对齐方式](#1141-对齐方式)

> 创建一个后缀为`.md`的文件。

## 1.1. 标题

已`#`号开头一个`#`号代表一级标题两个`#`号代表二级标题，以此类推1-6级标题

``` Markdown
# 标题1
## 标题2
### 标题3
#### 标题4
##### 标题5
###### 标题6
```

## 1.2. 段落

直接输入文字就是一个段落，输入回车则换行。
在一行的末尾添加两个或多个空格，然后按回车键,即可创建一个换行(`<br>`)

``` Markdown
我就是一个段落
换行段落
我就是一个段落段落段落
```

## 1.3. 强调语句

通过将文本设置为粗体或斜体来强调其重要性。

### 1.3.1. 粗体（Bold）

已4个星号包裹中间的的文字加粗。`**要加粗的文字**`。
在`vscode`中快捷是`ctrl+B`。

效果展示：
**我是加粗的**

``` Markdown
**我是加粗的**
```

### 1.3.2. 斜体（Italic）

两个星号包裹中间的文字为斜体。`*斜体*`。
在`vscode`中快捷是`ctrl+i`。

效果展示：
*我是倾斜的*

``` Markdown
*我是倾斜的*
```

## 1.4. 引用语法

要创建块引用，请在段落前添加一个 `>` 符号。

效果展示：
> 引用块样式

``` Markdown
> 引用块语法
```

## 1.5. 列表

### 1.5.1. 有序列表

在段落前面添加数字紧跟英文点好`1.我是有序列1`。

效果展示：
1.序列1
2.序列2
3.序列3

``` Markdown
1.序列1
2.序列2
3.序列3
```

### 1.5.2. 无序列表

无序列表有3种写法。

1.写法1：以横线开头加一个空格，`- 我是无序列表1`
2.写法2：以星号开头加一个空格，`* 我是序列表2`
3.写法3：以加号开头加一个空格，`+ 我是无序列表3`

效果展示：

- 无序1
  - 子列1

``` Markdown
- 无序1
  - 子列1

* 无序2

+ 无序3

```

## 1.6. 代码语法

### 1.6.1. 单个单词

如果要标记单个单词时可以使用反引号进行包裹。

效果展示：
语句中的单词`body`

``` Markdown
语句中的单词`body`
```

### 1.6.2. 多行代码块

如果要想显示多行代码块并且有高亮显示则可以使用六个反引号进行包裹在前三个中标识你要显示的语言代码即可。``` javavscript 后面再跟随三个反引号即可。

``` javascript
var obj = {}
```

## 1.7. 脚注

要创建脚注可以在方括号中编写脚注符号`[^1]`

效果展示：
[^1]这个是脚注的语法

```Markdown
[^1]这个是脚注的语法
```

## 1.8. 标题编号

一般在头部列出所有标题项然后可以点击跳转只对应的标题内容
语法：中括号是要显示跳转标题的名称，圆括号加`#`号则是要跳转对应的标题名称。

效果展示：
[列表](#列表)

```Markdown
[列表](#列表)
```

### 1.8.1. 点击标题跳转到另一个文件

在`A.md`文件中定义了一个跳转到JavaScript基础知识目录下的`README.md`文件

```Markdown
[JavaScript基础知识](./JavaScript基础知识/README.md)
```

## 1.9. 删除线

请在要增加删除线的前后使用两个波浪号~~

效果展示：
~~世界是平坦的。~~ 我们现在知道世界是圆的。

```Markdown
~~世界是平坦的。~~ 我们现在知道世界是圆的。
```

## 1.10. 任务列表语法

使用破折号和方括号组合 `- [ ] 带复选框的`。破折号与中括号之间由空格隔开，中括号中未选中留一个空格，选中状态加一个`X`即可,`- [x] 带复选框的`

效果展示：

- [ ] 选课

```Markdown
-[] 带复选框的
```

## 1.11. 使用 Emoji 表情

可以在 此网站上复制相关的表情包：<https://emojipedia.org/>

去露营了！⛺很快回来。

真好笑！😂

## 1.12. 使用图片

语法：`![商品列表](图片地址)`

## 1.13. 在文档中添加链接跳转

使用尖括号包裹要跳转的地址即可：<https://emojipedia.org/>

## 1.14. 表格

表格是由（`|`）符号与（`---`）符号组成（`---`）符号最少为3个以上，分割上方的内容为标题，下方内容为对应标题内容。

效果展示：
| 标题1 | 标题2 |
| ----- | ----- |
| 内容1 | 内容2 |

```Markdown
| 标题  | 描述  |
| ----- | ----- |
| 内容1 | 内容1 |
| 内容2 | 内容2 |
```

### 1.14.1. 对齐方式

在分割标题的（`---`）符号左右两侧增加冒号（`:`），加左边则左对齐，加右边则右对齐，两边都加则剧中对齐。

展示效果：

| 左对齐 | 剧中对齐 | 右对齐 |
| :----- | :------: | :----: |
| 1      |    2     |   3    |

```Markdown
| 左对齐 | 剧中对齐 | 右对齐 |
| :----- | :------: | :----: |
| 1      |    2     |   3    |
```