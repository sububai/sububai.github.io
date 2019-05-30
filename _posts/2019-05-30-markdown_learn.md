1、使用html
 <div align="center" style="color:red">VS Code 使用 Markdown 编写文档</div>

2、标题
# h1
## h2

3、TOC  
[TOC]

4、引用
>hello world!  

> hello world!  输入完之后按两次空格键再按一次Enter键即可  
>> hello world!  输入完之后按两次空格键再按一次Enter键即可  
>>> hello world!  输入完之后按两次空格键再按一次Enter键即可  

5、行内标记
标记之外`hello world`标记之外

6、代码块  
1）用```代码```进行包裹
代码：  
    ```
    <div>  
        <div></div>  
        <div></div>
        <div></div>
    </div>
    ```  
2）自定义语法（根据不同的语言配置不同的代码着色）  
代码：  
    ```javascript
    var num = 0;
    for (var i = 0; i < 5; i++) {
        num+=i;
    }
    console.log(num);
    ```  

7、 插入链接
[百度 1](http://www.baidu.com/ '百度一下')  

8、插入图片  
[![](./01.jpg '描述')](http://www.baidu.com)  

9、插入视频（略）

10、序列  
1. one  
2. two  
3. three

* one
* two
* three

11、语义标记  
*斜体*、_斜体_  
**加粗**  
***加粗+斜体***、**_加粗+斜体_**  
~~删除线~~  
==背景色==  
$\underline{下划线}$   
Superscript - superscript  
^superscript^  
Subscript - subscript  
~subscript~  

12、语义标签
 <i>斜体</i>  
<b>加粗</b>  
<em>强调</em>  
<u>下划线</u>   
<del>删除</del>  
Z<sup>a</sup>  
Z<sub>a</sub>  
<kbd>Ctrl</kbd>

13、分隔符
---  
或者  
***

