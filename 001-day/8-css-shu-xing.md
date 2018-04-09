####CSS 属性的继承 和 不可继承

####一、可继承属性

- 父标签的属性值会传递给子标签
- 一般是**文字控制**属性

如下： 因为 div 是 p标签和span 标签的父标签，因此p标签和span继承了div的文字属性，颜色都为红色

```objc
 <style>

    div{
       color: red;
    }

</style>
    
<div>

    <p> 我是段落</p>
    <span>我是行内同期</span>

</div>
    
```
