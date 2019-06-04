##  CSS 指层叠样式表 (Cascading Style Sheets)
>  作用：美化页面  

#### 引入方式

1. html 标签上添加 style 属性(inline style 内联样式)  a
~~~
  <div style="color:red;text-align:center">
    <P>hello,world!</p>
  </div>
~~~

2. head 标签下添加 style 标签(Internal style sheet 内部样式)  b
~~~
   <style media="screen">
     #title{
       color：red !important;
       text-align: center
     }
   </style>
~~~

3. head 标签下引入 link 标签(External style sheet 外部样式)  c
~~~
   <link rel="stylesheet" href="/css/master.css">
~~~

>  优先级：!important > 内联样式 > 内部样式 > 外部样式
