![image](https://www.kamailio.org/w/wp-content/uploads/2022/05/markdown-logo.jpeg)
<br>

作为打工人，学习Markdown只是方便自己做记录，所以我们只需要知道，在2004年就由约翰·格鲁伯(John Gruber)和亚伦·斯沃茨（Aaron Swartz）共同合作创建了Markdown语言。
Markdown 编写的文档后缀为.md,.markdown
有人推荐Markdown编辑器：Typora(https://typora.io/)
当然，打工人只需要与WPS和Office为伴就好，上学用的最多的就是Office，上班后发现大家用WPS，两个软件的文档有时候不兼容会导致格式错误，所以上班几乎大家都用WPS。这与上学用QQ，上班用微信一个道理。
Markdown支持插入图片、视频等
Markdown的基本用法[Markown官方中文教程](https://markdown.com.cn/basic-syntax/headings.html)
<br>

1. Markdown语法
   不同的 Markdown 应用程序处理 # 和标题之间的空格方式并不一致。为了兼容考虑，请用一个空格在 # 和标题之间进行分隔。  
   要创建标题，请在单词或短语前面添加井号 (#) 。（#） 的数量代表了标题的级别。例如，添加三个 （#） 表示创建一个三级标题 （例如：`### My Header`）
   <br>
   
   Markdown最多有6级标题  
   # 一级标题
   ## 二级标题
   ### 三级标题
   #### 四级标题
   ##### 五级标题
   ###### 六级标题
>注意：
>最后一个#字符与标题中间留一个空格
>标题应该置于行首，如果放入表格中可能无法正确解析
<br>

2. 字体
星号与下划线都可以，单是斜体，双是粗体，三是粗斜体
*这是斜体*	这是斜体
_这是斜体_	这是斜体
**这是粗体** 这是粗体
__这是粗体__ 这是粗体
***这是粗斜体*** 这是粗斜体
___这是粗斜体___ 这是粗斜体
<br>

3. 换行
Markdown换行的方式有很多种:  
直接在一句话后敲两个空格  
两句话之间加一个空行  
如果你在编辑的时候，想让一行文字在显示的时候换行，就在中间加`<br>`

4. 引用
Markdown 中引用通过符号 > 来实现。> 符号后的空格，可有可无。  
在引用的区块内，允许换行存在，换行并不会终止引用的区块。如果要结束引用，需要一行空白行，来结束引用的区块。  
此外，引用还可以嵌套使用  
>这是一个引用：
>>这是一个引用的引用
>>>这是一个引用的引用的引用

5. 链接
Markdown中插入链接的使用方式是：  
链接名称]("链接地址)` 或者 `<https://blog.csdn.net/qq_40818172?type=lately>`

6. 图片
可以直接Ctrl+v粘贴图片  
Markdown中插入图片的使用方式是：  
`![图片描述，可写可不写，但是中括号要有]"图片地址，本地链接或者URL地址#pic_center空格=长x宽)`  
也可以修改位置和图片大小：  
`![图片描述，可写可不写，但是中括号要有](图片地址，本地链接或者URL地址#pic_center空格=长x宽)`  

7. 列表
列表分为有序列表和无序列表  
无序列表，使用*、+、-，再加一个空格作为列表的标记  
有序列表，使用数字并加上.号，再加一个空格作为列表的标记  
代码：  
* 无序列表 1
+ 无序列表 2
- 无序列表 3

1. 有序列表 1
2. 有序列表 2
3. 有序列表 3
   
如果想要控制列表的层级，则需要在列表符号前使用Tab  
代码：  
+ 无序列表 1
+ 无序列表 2
	+ 无序列表 2.1
	+ 无序列表 2.2

1. 有序列表 1
	1.1 有序列表 1.1
2. 有序列表 2
	2.1 有序列表2.1

8. 分割线
Markdown中给出了多种分割线的样式，我们可以使用分割线让文章结构更加的清晰。  
分割线的使用，可以在一行中用三个-or*来建立一个分割线，但是注意：在分割线的上面空一行！！！  
代码：  
---
***
- - -
* * *
>注意：写分割线前，要空一行之后写，否则会导致前一行字体放大。

9. 删除线
删除线的的使用，可以在要添加删除线的文字前后添加两个~  
`~~这是要被删除的文字~~`  
~~这是要被删除的文字~~

11. 下划线
下划线的使用和html中类似，在需要添加下划线的文字首尾添加`<u>`文本`</u>`
代码：`<u>这行文字已被添加下划线</u>`  
<u>这行文字已被添加下划线</u>

13. 代码块
Markdown中代码块有两种：  
如果在一行内需要引用代码，只需要用反引号`引起来就好了。（反引号在英文输入法状态下ESC下面~建）  
代码：`Hello` World.  
如果是在一个块内需要引用代码，则在需要引用的代码块的前一行和后一行使用三个反引号，同时在前一个反引号后写入代码的语言。  
```python
print(Hellow,World!)
```
支持以下语言：
bash
c，clojure，cpp，cs，css
dart，dockerfile, diff
erlang
go，gradle，groovy
haskell
java，javascript，json，julia
kotlin
lisp，lua
makefile，markdown，matlab
objectivec
perl，php，python
r，ruby，rust
scala，shell，sql，swift
tex，typescript
verilog，vhdl
xml
yaml

12. 表格
表格使用|来分割不同的单元格，使用-来分隔表头和其他行  

:-：将表头及单元格内容左对齐
-:：将表头及单元格内容右对齐
:-:：将表头及单元格内容居中
<br>
| 项目        | 价格   |  数量  |
| --------   | -----:  | :----:  |
| 计算机     | \$1600 |   5     |
| 手机        |   \$12   |   12   |
| 管线        |    \$1    |  234  |

13. 脚注
脚注是对文本的备注，我们时长在论文中看到脚注，在Markdown中的使用方法  
代码：  
使用
```markdown
Markdown[^1]可以效率的书写文档, 直接转换成 HTML[^2], 你可以使用 Typora[^T] 编辑器进行书写。
[^1]:Markdown是一种纯文本标记语言
[^2]:HyperText Markup Language 超文本标记语言
[^T]:NEW WAY TO READ & WRITE MARKDOWN.
```
Markdown[^1]可以效率的书写文档, 直接转换成 HTML[^2], 你可以使用 Typora[^T] 编辑器进行书写。
[^1]:Markdown是一种纯文本标记语言
[^2]:HyperText Markup Language 超文本标记语言
[^T]:NEW WAY TO READ & WRITE MARKDOWN.

>使用 Markdown1可以效率的书写文档, 直接转换成 HTML2,
>注意：脚注自动被搬运到最后面，请到文章末尾查看，并且脚注后方的链接可以直接跳转回到加注的地方。

14. 特殊符号
对于Markdown中的语法符号，前面家反斜线\即可以显示符号本身。  
\\
\*
\_
\+
\.
等等

15. 高级用法
    更多请查阅：
    [菜鸟教程Markdown高级用法](https://www.runoob.com/markdown/md-advance.html)  
    [Cmd Markdown 简明语法手册](https://www.zybuluo.com/mdeditor?url=https://www.zybuluo.com/static/editor/md-help.markdown#cmd-markdown-%E9%AB%98%E9%98%B6%E8%AF%AD%E6%B3%95%E6%89%8B%E5%86%8C)
    15.1 可以实现对字体格式的改变  
    代码：  
    `<font face="楷体" color=#00ffff size=5>改变文字格式</font>`
    15.2 支持Html原生HTML语法
    15.3 制作待办事项
    我们可以使用Markdown来制作一个待办事项，格式为、-[] 表示未完成；-[x]表示已完成  
    代码：
    ```markdown
    - [ ] 支持以 PDF 格式导出文稿
    - [ ] - [ ] 改进 Cmd 渲染算法，使用局部渲染技术提高渲染效率
    - [ ] - [x] 新增 Todo 列表功能
    - [ ] - [x] 修复 LaTex 公式渲染问题
    - [ ] - [x] 新增 LaTex 公式编号功能
    ```
    - [ ] 支持以 PDF 格式导出文稿
    - [ ] - [ ] 改进 Cmd 渲染算法，使用局部渲染技术提高渲染效率
    - [ ] - [x] 新增 Todo 列表功能
    - [ ] - [x] 修复 LaTex 公式渲染问题
    - [ ] - [x] 新增 LaTex 公式编号功能
          
    15.4 书写公式
    Markdown支持书写公式，例如书写一个质能守恒公式。  
    `$$表示整行公式`  
    代码：`$$E=mc^2$$`
    $$E=mc^2$$

