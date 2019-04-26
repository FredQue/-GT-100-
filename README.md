# -GT-100-
100天内快速分手GRE，Toefl

# 4.27一战GRE
阅读还是要大量积累的，听了微臣GRE的课，方法论记了不少。但是单词关没有过估计很难一战分手了。
不过明天考试还是会认真对待的。

9.1日前后二战GRE + toefl: 目标G：325+ 3.5 ； T：105 26，26，27，28:
会把每天的学习进度拉上来确认的。
首要是单词，单词，单词关。
其次是练习‘听力’和‘写作’。







附
====

git语法
————————
# 关于标题
规范的README文件开头都写上一个标题，这被称为大标题 。

大标题
====
在文本下面加上 等于号 = ，那么上方的文本就变成了大标题。等于号的个数无限制，但一定要大于0个哦。。

比大标题低一级的是中标题，也就是显示出来比大标题小点。

中标题
-------
在文本下面加上 下划线 - ，那么上方的文本就变成了中标题，同样的 下划线个数无限制。

除此以外，关于标题还有等级表示法，分为六个等级，显示的文本大小依次减小。不同等级之间是以井号  #  的个数来标识的。一级标题有一个 #，二级标题有两个# ，以此类推。 

#一级标题
##二级标题
###三级标题
####四级标题
#####五级标题
######六级标题
注意井号#和标题名称要并排写作一行，显示效果如图：

实际上，前文所述的大标题和中标题是分别和一级标题和二级标题对应的。即大标题大小和一级标题相同，中标题大小和二级标题相同。 

## 显示文本
普通文本 
直接输入的文字就是普通文本。需要注意的是要换行的时候不能直接通过回车来换行，需要使用<br>。也就是html里面的标签 。

这是一段普通的文本，
直接回车不能换行，<br>
要使用\<br>
注意第三行的<br>前加了反斜杠 \ 。目的就是像其他语言那样实现转义，也就是 <  的转义。 

此外，要显示一个 超链接 的话，就直接输入这个链接的URL就好了。显示出来会自动变成可链接的形式的。 

### 单行文本
使用两个Tab符实现单行文本。
        
        Hello,大家好，我是果冻虾仁。
注意前面有两个Tab。在GitHub上单行文本显示效果如图：

### 多行文本
多行文本和单行文本异曲同工，只要在每行行首加两个Tab

        欢迎到访
        很高兴见到您
        祝您，早上好，中午好，下午好，晚安


## 部分文字的高亮
如果你想使一段话中部分文字高亮显示，来起到突出强调的作用，那么可以把它用 `  ` 包围起来。注意这不是单引号，而是Tab上方，数字1左边的按键（注意使用英文输入法）。

Thank `You` . Please `Call` Me `Coder`

 文字超链接
给一段文字加入超链接的格式是这样的 [ 要显示的文字 ]( 链接的地址 )。比如：

[我的博客](http://blog.csdn.net/guodongxiaren)
显示效果： 
 
你还可以给他加上一个鼠标悬停显示的文本。

[我的博客](http://blog.csdn.net/guodongxiaren "悬停显示")
即在URL之后 用双引号括起来一个字符串。同样要注意这里是英文双引号。 

## 插入符号
圆点符
这是一个圆点符
这也是一个圆点符
上面这段的圆点是CSDN博客编辑器里面的符号列表。写文章在列出条目时经常用到。在GitHub的markdown语法里也支持使用圆点符。编辑的时候使用的是星号 *

* 昵称：果冻虾仁
* 别名：隔壁老王
* 英文名：Jelly
要注意的是星号* 后面要有一个空格。否则显示为普通星号。上文的显示效果如图： 

 
此外还有二级圆点和三级圆点。就是多加一个Tab。

* 编程语言
    * 脚本语言
        * Python
第二行一个Tab，第三行两个Tab。这样用来表示层级结构就更清晰了吧，看效果：


如果你觉得三级的结构还不够表达清楚的话，我们可以试着换一种形式，请看 字符包围

## 字符包围
我不知道称之为“字符包围”是否贴切。我也是看的网上有一篇博文是这样称呼的，我就姑且也这样称呼吧。囧。。

>数据结构
>>树
>>>二叉树
>>>>平衡二叉树
>>>>>满二叉树
 
具体这个“字符包围”的用法可能还有其他用法。大家自己摸索吧。 

## 插入图片
来源于网络的图片 
网上有很多README插入图片的教程了，经我自己多次测试呢，发现可以使用的最简单，最基本的语法是：

![](http://www.baidu.com/img/bdlogo.gif)
即 叹号! + 方括号[ ] + 括号( ) 其中叹号里是图片的URL。

如果不加叹号! ,就会变成普通文本baidu了。 

在方括号里可以加入一些 标识性的信息，比如

![baidu](http://www.baidu.com/img/bdlogo.gif)
这个方括号里的baidu并不会对图像显示造成任何改动，如果你想达到 鼠标悬停 显示提示信息，那么可以仿照前面介绍的文本中的方法，就是这样：

![baidu](http://www.baidu.com/img/bdlogo.gif "百度logo")
在URL后面，加一个双引号包围的字符串，显示效果如图： 



## GitHub仓库里的图片
有时候我们想显示一个GitHub仓库(或者说项目)里的图片而不是一张其他来源网络图片，因为其他来源的URL很可能会失效。那么如何显示一个GitHub项目里的图片呢？

其实与上面的格式基本一致的，所不同的就是括号里的URL该怎么写。

    https://github.com / 你的用户名 / 你的项目名 / raw / 分支名 / 存放图片的文件夹 / 该文件夹下的图片

这样一目了然了吧。比如：

![](https://github.com/XXX/XX/raw/master/Logo/foryou.gif)
我在GitHub上的用户名XXX；有一个项目XX；raw表示原数据的意思吧，不用管它；主分支master；项目里有一个文件夹Logo；Logo文件夹下有一张图片foryou.gif 

## 给图片加上超链接
如果你想使图片带有超链接的功能，即点击一个图片进入一个指定的网页。那么可以这样写：

[![baidu]](http://baidu.com)
[baidu]:http://www.baidu.com/img/bdlogo.gif "百度Logo"
这两句和前面的写法差异较大，但是也极易模仿着写出，就不过多介绍了。只需注意上下文中的 baidu 是你自己起的标识的名称，可以随意，但是一定要保证上下两行的 标识 是一致的。

这样就能实现 点击图片进入网页的功能了。 

## 插入代码片段
我们需要在代码的上一行和下一行用` `` 标记。``` 不是三个单引号，而是数字1左边，Tab键上面的键。要实现语法高亮那么只要在 ``` 之后加上你的编程语言即可（忽略大小写）。c++语言可以写成c++也可以是cpp。看代码：







