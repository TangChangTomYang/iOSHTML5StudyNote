

###常见HTML 标签

####一、HTML 的主要结构

```objc
<!--根标签-->
<html>

    <!--头部 （head）一般用来存放一些资源 配置信息 引用信息-->
    <head>
        
        <title>hello world</title>

        <!--设置页面的编码,否则页面可能出现乱码，一般设置UTF-8 和国标GB2312-->
        <meta charset="UTF-8">

    </head>

    <!--主要内容-->
    <body>
        <!--body 主要用来放一些内容和结构的    -->

    </body>

</html>

```

####二、常用的html标签
**主要有：**
标题标签： h1 h2 h3 h4 h5 h6
段落标签： p
换行标签：br
容器标签：div  span (用来容纳其他标签)
表格标签： table  tr   td  现在已经完全用div 取代了
列表标签： ul  ol  li   相当于ios 中的tableView ,ul 是无序的，ol 是有序的
表单标签：input 

- **input 标签**

```objc
<!--表单标签-->
<input> <!--默认类型type 是text 文本标签-->
<input type="text">
<!--包含默认值的表单-->
<input value="我是默认值">
<!--日期选择表单-->
<input type="date">
<!--颜色选择表单-->
<input type="color">
<!--文件选择表单-->
<input type="file">
<!--按钮表单-->
<input type="button">
<input type="button" value="我是按钮">
<!--复选表单-->
<input type="checkbox" >
<!--单选表单-->
<input type="radio">
<input type="radio">
```

![](/assets/input.png)

- **ul ol  li 列表标签**

```objc
<!--列表-->
        <!--无序列表-->
        <ul>
            <li>我是无序列表</li>
            <li>我是无序列表</li>
            <li>我是无序列表</li>
            <li>我是无序列表</li>
            <li>我是无序列表</li>
        </ul>
        <!--有序列表-->
        <ol>
            <li>我是有序列表</li>
            <li>我是有序列表</li>
            <li>我是有序列表</li>
            <li>我是有序列表</li>
        </ol>

         <!--指定有序列表的序号-->
        <ol type="A">
            <li>我是有序列表</li>
            <li>我是有序列表</li>
            <li>我是有序列表</li>
            <li>我是有序列表</li>
        </ol>
```

![](/assets/ulolli.png)


**说明： 只要是双标签就是容器**




  
    
      
          