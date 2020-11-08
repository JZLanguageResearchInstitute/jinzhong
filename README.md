## 关于jinzhong

jinzhong，是我本人与几个好友在高中时期建立的一个名为“缙云中学校园语言研究所”的项目的托管仓库。该仓库收集了我们收集的有关我们当时就读的学校<u>浙江省缙云中学</u>的特色词汇（多是些带有调侃意味的东西），并通过Github Pages使得他人能够访问查阅这些资料。

由于高中时间紧张，我们设计了一条低成本的实现路径：利用Markdown进行网页排版，通过如Typora等第三方工具转Markdown为Html（内嵌CSS），而后通过超链接进行各个部分的连接。

它的流程是这样的：

<img src="https://gitee.com/leewendao/jinzhong/raw/master/db/pic/Map1.jpg" alt="map1" style="zoom:50%;" />

为了方便用户访问，我们为其绑定了域名并再次借助第三方工具Fusion App制作了安卓端的APP,我们命名之为“ChinaRed”。因而它的完整人机交互过程是这样的：

<img src="https://gitee.com/leewendao/jinzhong/raw/master/db/pic/Map2.jpg" alt="Map2" style="zoom:50%;" />

有几件事是毫无疑问的：

1. Jinzhong是一个**低技术力**的产物，在*自创性*上也非常不突出。
2. 它的维护较为繁琐，每一次更新都要更迭整个文档（虽然通过Markdown节省了不少精力）。
3. 它就像是一个小孩子的玩具，幼稚无比。

不过尽管它如此贻笑大方，唯几尚令人安慰的是它实现了自己要实现的目标，在我们搭建的过程中在可以的部分通过相对URL减少了“握手”的消耗，考虑到了用户与损耗。这是令人非常高兴的事情。

凡为过去之事，皆为来日之基石。希望负责这个项目的我和叶姐都能在未来不断提高自己的水平直至顶峰，在那时回首这个项目时依然心里能有一种半好笑半欣慰的情感。

***

#### 如何查看Jinzhong里的内容

jinzhong的一切内容基于GithubPages为用户访问查阅。

您可以通过在浏览器内输入官网地址了解一些**基本信息**：

`https://jzlanguageresearchinstitute.github.io/jinzhong/Index.html`

当然，由于我们绑定了域名，我们更推荐您使用域名地址访问：

`https://www.otterdaily.cn/Index.html`

***

绝大部分词汇都存放于`./db/word`文件夹下，您可以通过该链接访问您想要查看的词汇或页面：

`https://jzlanguageresearchinstitute.github.io/jinzhong/db/words/$$.html`

或：

`https://www.otterdaily.cn/db/words/$$.html`

`$$`即您需要查阅的条目名称，在输入时将`$$`换成您想要查阅的条目名称即可。

例如我要查阅*“月下散步”*一词，输入：

`https://www.otterdaily.cn/db/words/月下散步.html`

即可。

***

若您不知道有哪些内容可以查阅，我们预先编写了检索目录供您查询，您可以通过

`https://www.otterdaily.cn/db/words/检索.html`

查看有哪些条目可以查阅。
