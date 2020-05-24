---
id: doc4
title: 样式指南
sidebar_label: 样式指南
---

---
## 标题
`#` `标题内容`

`##` `标题内容`

`###` `标题内容`

`####` `标题内容`

`#####` `标题内容`

`######` `标题内容`

演示如下：
# H1

## H2

### H3

#### H4

##### H5

###### H6

:::note提示
只有h2与h3标签能在导航栏显示分级
:::

---

## 标记
### 斜体
用2个`_`包含需要斜体的地方

例如：`_斜体_`  _斜体_
### 加粗
用2个`**`包含需要斜体的地方

例如：`**加粗**`  **加粗**
### 删除线
用2个`~~`包含需要删除的地方

例如：`~~删除~~`  ~~删除~~

:::note提示
可以同时使用加粗或斜体或删除线

例如：`**_~~加粗斜体删除线~~**_`  **_~~加粗斜体删除线~~_**
:::

---

## 列表
### 有序列表
在若干行开头输入`1.`和空格，即可生成有序序列
```md
1. 演示1
1. 演示2
1. 演示3
1. 演示4
```
1. 演示1
1. 演示2
1. 演示3
1. 演示4
### 无序列表
在若干行开头输入`-`**或**`*`**或**`+`**和**空格，即可生成无序序列
```md
- 演示1
* 演示2
+ 演示3
* 演示4
```
- 演示1
* 演示2
+ 演示3
* 演示4

---

## 链接
[我是内联式链接](https://github.com/xjz3103)

[我是一个内联式链接与标题](https://github.com/xjz3103 "github")

[我是参考样式的链接][arbitrary case-insensitive reference text]

[我是存储库文件的相对引用](../blob/master/LICENSE)

[您可以将数字用于参考样式的链接定义][1]

或者将其留空并使用[链接文本本身]。

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[链接文本本身]: http://www.reddit.com

```md
[我是内联式链接](https://github.com/xjz3103)

[我是一个内联式链接与标题](https://github.com/xjz3103 "github")

[我是参考样式的链接][arbitrary case-insensitive reference text]

[我是存储库文件的相对引用](../blob/master/LICENSE)

[您可以将数字用于参考样式的链接定义][1]

或者将其留空并使用[链接文本本身]。

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[链接文本本身]: http://www.reddit.com
```
:::caution注意
`参考样式的链接`、`参考样式的链接定义`、`链接文本本身`必须要对其赋值
:::

---

## 图像