LinuxBashShellScriptForOps
================
Linux Bash Shell Scripts For Ops, some python scripts here also.

## 这是一个怎样的项目
此项目是对在Linux运维工作所能用到的Shell脚本和Python脚本的归纳和总结。
99%以上的源码均出自生产系统并经过比较严谨的测试。

## 为什么有Python的加入
不得不说Python是优秀的编程、脚本语言，用在运维上确实很方便，只需短短的几天时间就可以编写出有用的脚本。

Python不仅是一门高级的跨平台编程语言，而且能轻松实现很多Bash无法实现的功能。

作为运维人员不必排斥编程，编程是为了更好的运维。

至于其他的，如Bash、Git等，就不必多说了。

## 这个项目里有什么
此项目包含了常用的Shell脚本和Python脚本，主要拆分成两部分：functions和projects。

functions目录存放常用的、基本的脚本语句，用于编写一个完成某项具体事务的脚本。

projects目录存放比较完整的脚本文件，用于做成某件完整的事情。

## 如何使用该项目
使用Git工具克隆到本地。

```
git clone https://github.com/DingGuodong/LinuxBashShellScriptForOps.git
```

此项目只有master一个分支，也没有版本的概念，有bug则修复bug，在日后的使用过程中不断更新完善和优化。

如果是要使用functions，则需要自己翻阅functions下的所有目录以及各个文件，
或者使用“Find in Path”或者“search in this repository”功能按照关键字搜索。

如果是要使用projects，则可以根据项目的名字查看自己感兴趣或者需要的部分，
或者使用“Find in Path”或者“search in this repository”功能按照关键字搜索。

当前主要使用Python 2.7版本，日后会增加Python 3.x版本。

推荐使用JetBrains的PyCharm作为Bash Shell（需要安装插件“BashSupport”）和Python的开发工具。

## 此项目是如何进行的
此项目的所有内容均来自项目持有人本人的运维工作，因此全部与运维相关，遇到用脚本解决的问题就会写进此项目。

日后也会考虑添加一些文档或者有用的资源等，但通常不再创建新的repository，毕竟一个人在GitHub上维护多个repository并不轻松。

这个项目会持续完善，积累更多有用的Shell、Python编程和运维的相关知识和文件。

虽然直到现在这个项目一直由项目持有者本人独自进行，但期待每一个人的加入，欢迎fork和递交pull request。

此项目完全开源，允许自由复制和使用代码。

## 提交bugs和feature requests以及联系信息
可以使用 https://github.com/DingGuodong/LinuxBashShellScriptForOps/issues 页面进行issue提交。

也可以通过issue列出你想通过脚本实现的功能（help wanted，question，feature）、改进建议（enhancement，idea）等。（**推荐）

我在51CTO博客中写了大量的关于运维类的原创文章和总结。

blog: http://dgd2010.blog.51cto.com

Email: uberurey_ups#163.com

也可加入QQ群与其他人一起交流：

1. QQ群名称：[运维架构技术交流](https://jq.qq.com/?_wv=1027&k=52fjL0z) / 群号码：991904631

*欢迎提供其他QQ群，供交流参考，经营性或商业目的除外*


## 编程风格与编程规范 - Programing Style Guides

每个人都可以有自己的编程风格，但使用良好的编程规范可以帮助我们规范代码，也符合大多数人的阅读和使用习惯。

通常一些知名的大厂和团队都会有自己的编程规范，感谢分享！

NO1.从现有的产品或线上中学习，如参考系统中的脚本是如何写的，其他著名项目中的代码是怎样的。

1.[Shell风格指南](https://zh-google-styleguide.readthedocs.io/en/latest/google-shell-styleguide/contents/) - 中文

2.[Python 风格指南](https://zh-google-styleguide.readthedocs.io/en/latest/google-python-styleguide/contents/) - 中文

3.[Style guides for Google-originated open-source projects](https://github.com/google/styleguide)

4.[PEP 8](https://www.python.org/dev/peps/pep-0008/)

5.[Python best practices guidebook, written for humans.](https://docs.python-guide.org)

6.[Code Review Guidelines](https://docs.gitlab.com/ee/development/code_review.html#everyone)

当然还有更多优秀的指南或参考，不一一例举。

**最后，记住，规则有时就是用来打破的，做自己当然也是被允许的。**

## TODO List

1. 应该把文档的编写和完善作为一项长期任务，维护好，并保持可用

2. 整理和归纳代码体现的思想和方法，甚至可以让它们脱离代码，独立存在

3. ...
