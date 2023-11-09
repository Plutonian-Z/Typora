# JSbase



JavaScrpit主要负责网页交互

容器默认值 undefined

DOM 文档项目模型

BOM 浏览器项目模型

### 元素获取方式  

document.queryselector(all) 

item.textContent = ""  内容替换

item.previousElementSibling.textContent = ""

item.nextElementSibling.textContent = ""

item.parentNode

item.children

### 样式处理

 

### 文本处理

 textContent只能设置纯文本

innerHTML可以进行标签的生成

### 事件处理

block.onclick = function () {

​	alert('surprise!')

}  会被覆盖

block.addEventListener('click', function () {

​	alert('surprise!')

} )

block.addEventListener('click', function () {

​	alert('surprise again!')

} )

### 定时器

setTimeout(function () {

​	alert('surprise!')

}, 2000)

setInterval(function () {

​	alert('surprise!')

}, 2000)



# React

react脚手架创建应用

src目录下  index.js  app.js

将JavaScript与Html语句书写在一起，称为JSX

