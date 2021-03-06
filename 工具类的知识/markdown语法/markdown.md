# Markdown 语法的使用

## 标题

使用几个#就是几级标题

## 段落

**段落的换行是使用两个以上空格加上回车。**  
当然也可以在段落后面使用一个空行来表示重新开始一个段落。

## 字体

**文字两边左右分别两个`*`号是加粗**  
*文字两边左右分别一个`*`号是斜体*  
***文字两边左右分别三个`*`号是斜体加粗***  
~~文字两边左右分别两个`~`号就是删除线~~

## 分割线

- - -
----------
***
* * *
*****

# 下划线

下划线可以通过 HTML 的 `<u>` 标签来实现：

<u>带下划线文本</u>

# 脚注

[^要注明的文本两侧分别使用[]，中间添加^和要添加的内容]：我到底什么时候能初步掌握前端所需要的技能

## 列表嵌套

* 无序列表
* 使用星号（`*`）、加号(`+`)或是减号(`-`)作为列表标记
* 这些标记后面要添加一个空格，然后再填写内容

1. 有序列表
2. 使用数字
3. 并加上`.`号来表示

1. 列表嵌套
    - 只需在子列表中的选项前面
    - 添加四个空格

## 区块引用

> 在要引用的文字面前加上>就是引用

> 区块可以嵌套
>> 一个`>`符号是最外层
>>> 两个`>`符号是第一层嵌套 

## 代码

`代码可以用反引号把它包起来（```)`

    代码区块
    使用 4 个空格
    或者一个制表符（Tab 键）
    
 ## 图片

![图片的替代文字](图片的地址 "Google")

## 链接

[百度](http://www.baidu.com)

## 表格

Markdown 制作表格使用`|`来分隔不同的单元格，使用`-`来分隔表头和其他行。

|  表头   | 表头  |
|  ----  | ----  |
| 单元格  | 单元格 |
| 单元格  | 单元格 |

**我们可以设置表格的对齐方式：**

* `-:`设置内容和标题栏居右对齐。
* `:-`设置内容和标题栏居左对齐。
* `:-:`设置内容和标题栏居中对齐。

| 左对齐 | 右对齐 | 居中对齐 |
| :----| ----: | :----: |
| 单元格 | 单元格 | 单元格 |
| 单元格 | 单元格 | 单元格 |
