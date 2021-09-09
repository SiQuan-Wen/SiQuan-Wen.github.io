---
title: markdown语法
date: 2021-09-09 16:09:44
updated: 2021-09-09 17:25:00
tags:
  - 教程
  - markdown
  - 示例
categories: 技术文章
---


## 标题 
#数量代表 h1-h6 一级标题到六级标题

## 图片

![图片alt](图片地址 ''图片title'')

图片alt就是显示在图片下面的文字，相当于对图片内容的解释。
图片title是图片的标题，当鼠标移到图片上时显示的内容。title可加可不加

超链接🔗
[GitHub](https://github.com/ "Github同性交友网站")

## 文本样式
两个空格换行  
粗体、斜体、斜体加粗、删除线等
**这是加粗的文字**  
*这是倾斜的文字*  
***这是斜体加粗的文字***  
~~这是加删除线的文字~~

>这是引用的内容 >
>>这是引用的内容 >>

---
待办

- [x] 学习markdown语法
- [ ] 改掉拖延症

无序列表(-)
- 好好学习
- 天天向上
- 代码块(```)  

```
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello World");
    }
}
```


---

## 彩色标签引用

> Primary

<div class="success">

> Success

</div>

<div class="warning">

> Warning

</div>

<div class="danger">

> Danger

</div>

<div class="info">

> Info

</div>

<details>
<summary>使用方式</summary>
```markdown
> Primary

<div class="success">

> Success

</div>

<div class="warning">

> Warning

</div>

<div class="danger">

> Danger

</div>

<div class="info">

> Info

</div>
```
</details>


## Details 折叠

<details>
<summary>Summary</summary>

Content

</details>

```html
<details>
  <summary>Summary</summary>
  Content
</details>
```