---
title: 幻灯片测试
separator: <!--s-->
verticalSeparator: <!--v-->
theme: simple
highlightTheme: github
css: custom.css
revealOptions:
    transition: 'slide'
    transitionSpeed: fast
    center: false
    slideNumber: "c/t"
    width: 1000
---

<div class="middle center">
<div style="width: 100%">

# 幻灯片测试

<hr/>

改自 [@TonyCrane](https://github.com/TonyCrane) 的 [模板](https://github.com/TonyCrane/slide-template)

</div>
</div>

<!--v-->


## 说明


修改了部分字体，以及框线，，，

<!--s-->

<div class="middle center">
<div style="width: 100%">

# Part.1 大标题

一些 markdown

</div>
</div>


<!--v-->

## 标题

> 这是引用 

<hr/>

```python [1|2-3]
# 这是代码块
print("HELLO!")
print("BYE!")
```

**加粗**，*倾斜*，***加粗倾斜***，~删除~， <u>划线</u>，<mark>高亮</mark>，，，

数学公式显示：
$$
\prod_{p} \frac{1}{1-p^{-s}}= \sum _{n=1}^{\infty} \frac{1}{n^s}
$$


<!--v-->

## 标题

<div class="three-line">

|  表头 a  |  表头 b  | 表头 c |
| :------: | :------: | :----: |
| 这是一个 | 一些内容 |  ...   |
|  三线表  |   ...    |  ...   |

</div>

|  表头 a  |  表头 b  | 表头 c |
| :------: | :------: | :----: |
| 这是一个 | 一些内容 |  ...   |
| 普通表格 |   ...    |  ...   |

<!--s-->

<div class="middle center">
<div style="width: 100%">

# Part.2 布局

</div>
</div>

<!--v-->

## 多列布局

<div class="mul-cols">
<div class="col">

第一列

- list
- list

</div>
<div class="col">

第二列

```python
class MyClass:
    def __init__(self, ...):
        ...
    def method(self, ...):
        ...
```

</div>
</div>

<div class="mul-cols">
<div class="col">

第一列

- list
- list

</div>
<div class="col">

第二列

1. list 
2. list 
    - list

</div>
<div class="col">

第三列

```python
class MyClass:
    def __init__(self, ...):
        ...
    def method(self, ...):
        ...
```

</div>
</div>