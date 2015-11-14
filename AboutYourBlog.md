##搭建个人博客##

我们可以依托github的pages服务搭建一个自己的专属静态博客。

如果纯手写或者用github官网的模板生成器的话，会比较麻烦，也不容易出效果。

[这是我用官网的生成器生成的页面](http://danceiny.github.io/spring)

我尝试过两种博客生成器，一个是github推荐的[jekyll](http://jekyllcn.com/)

**重提一遍，在github上搭建可以直接访问的个人博客、主页或者组织、项目网站，[最好的参考文档在这里](https://pages.github.com/)

一个就是Hexo。

[Hexo的主页](https://hexo.io/zh-cn/)

Hexo是台湾人搞的，所以还有中文版，相比jekyll都没有官方支持windows系统，又是纯英文，相比更简单。

搭建Hexo站点需要先[安装Node.js](https://nodejs.org/)，并且接触到一些命令行的东西,以及模板和生成器的概念。
我认为对理解网页的构成很有帮助。因为我的前端知识也是非常少的。通过自己去配置一些东西，有了更深入的了解。

按照官网的说明搭建好站点后，我推荐大家试试一个叫[NexT（知乎有个回答说这个主题是最受欢迎的）]
(http://www.zhihu.com/question/24422335)**theme**。

总的来说，换主题很简单，把主题下载过来，一个文件夹，放到Hexo的那个themes文件夹下，
然后到Hexo文件夹下的_config.yml文件修改主题那一栏（默认是landscape)，就okay。

我用Hexo创建的站点[在此](http://danceiny.github.io/blog/)

[欢迎直接来看源代码:My Hexo Repository](http://github.com/Danceiny/blog)

新手在搭建过程中难免会走些弯路，我也接触才几天，也遇到了不少问题。如果遇到bug等问题，最好先百度一下，
因为很可能有人跟你遇到了同样的问题。

如果有需要帮助的,直接问我就ok。

BTW，使用NexT等其他主题可能会遇到意外的问题，原因是在主题文件中也有一个_config.yml文件，可能与主文件夹冲突。
我认为是以主题中的config优先（堆栈的覆盖式，所以优先吧）。**关于这方面的问题，可能比较难百度到**。
**因为我几乎都百度过，没有找到多少高质量的结果**

So，如果有需要帮助的,直接问我就ok。能帮就帮，一起调bug。
