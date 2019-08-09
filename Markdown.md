> HTML中有两个字符'<'和'&'需要特殊对待
>
> > 如果要使用他们的字面量在HTML中需要转义为字符实体，例如：`&lt`和`&amp`
> >
> > Markdown中在生成HTML时会将他们自动转码，不用自己来写这些麻烦的。但是也支持内联HTML，如果使用尖括号作为HTML标签定界符，Markdown将不会进行转义，也如&copy；版权符号。
> >
> > > 总之这两个符号，自由使用即可，Markdown会根据情况决定是否使用字面量
> > >
> > > 代码块中Markdown会将自动使用相应字符的字面量，也就是比如`&`会自动转换成它的字符实体`&lt`

1. Markdown中在生成HTML时会将他们自动转码，不用自己来写这些麻烦的。但是也支持内联HTML，如果使用尖括号作为HTML标签定界符，Markdown将不会进行转义，也如&copy；版权符号

2. ```python
   hello
   ```



> 内联型链接：[百度](www.baidu.com)

> 引用型链接：[an][baidu] 
>
> > [github][github]
>
> 语法：`[id]:url`在文章任意地方定义链接[id]

[baidu]: http://www.baidu.com
[github]: git@github.com

* 强调

> *你好*

>  **你好**

>  如果要使用字面量加`\*` :\*

so c is like `printf()`

![alt text](C:\Users\千百度\Pictures\Saved Pictures\2e2eb9389b504fc272875227e2dde71190ef6d3c.jpg)



> 自动生成链接：<http://www.baidu.com>

\*hello\*

---

----

![](C:\Users\千百度\Pictures\Saved Pictures\utro-pole-trava-1_1920x1200.jpg)



> 内联型：图片直接使用`![alt text](url)`

![RUNOOB 图标](http://static.runoob.com/images/runoob-logo.png)

> 引用型：图片引用`![alt text][id]   可以在文章末尾[id]:url "title(optional)"`

![alt 引用][id_]











[id_]:http://static.runoob.com/images/runoob-logo.png



[baidu]: 