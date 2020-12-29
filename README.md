# 开发人员面试大学

一个国外大神，每天8~12个小时，自学了几个月后，加入了Google。随后他公开了他的学习主题清单。在做完这份清单上的每个目标后，他成为了Google的软件开发工程师! 这份清单包含了几乎所有的成为优秀工程师的知识。

另外这里面还有他的经历“[我为了 Google 面试而自学了8个月](https://github.com/jiangmin42/Coding-Interview-University/blob/main/story/why-i-studied-full-time-for-8-months-for-a-google-interview.MD)”、“我是怎么加入亚马逊的”。  

在这份清单内的主题会让你拥有足够的知识去面对几乎每家软件公司的技术面试，包括科技巨头：Amazon、Facebook、Google，以及 Microsoft。

当然如果你在国内，腾讯、华为、阿里巴巴、字节跳动也不在话下了。

**本文是他完整清单的翻译版(目前正在翻译中)，可以看出这位大神的清单非常庞大，涉及说明、文档、资料、视频，我将尽我所能全部为其翻译成中文提供给大家，如果感兴趣想要一起翻译，请关注公众号：【深浅说道】找我**

# <a id="qianyan">前言</a>

清单只是一部分，完全学会并掌握它才是全部。

毕竟大神也需要每天8~12个小时的刻苦学习。

这是我为了从 web 开发者（自学、非计算机科学学位）蜕变至 Google 软件工程师所制定的计划，其内容历时数月。

这份清单适用于 **新手软件工程师**，或者想从软件/网站开发转向软件工程（需要计算机科学知识）的人员。如果你有多年的经验，并且声称拥有多年的软件工程经验，并且期待一次更艰难的面试。

如果你具有多年的软件/网页开发经验，请注意，大型软件公司（例如 Google，Amazon，Facebook 和 Microsoft）将软件工程视为不同于软件/网页开发，并且它们需要计算机科学知识。

如果你想成为可靠性工程师或运维工程师，请从可选列表（网络，安全）中学习更多。

# 目录
- [前沿](#qianyan)

- [为何要用到它？](#whyuseit)

- [如何使用它](#howuseit)

- [不要觉得自己不够聪明](#DonotEenyYourself)

- [相关视频资源](#RelatedVideos)

- [面试过程 & 通用的面试准备](#InterviewPreparation)

- [为你的面试选择一种语言](#ChooseAProgrammingLanguageForTheInterview)

- [书单](#书单)

- 在你开始之前

- 没有包含的内容

- 必备知识

- 日常计划

- 算法复杂度 / Big-O / 渐进分析法

- 数据结构

	- 数组（Arrays）

	- 链表（Linked Lists）

	- 堆栈（Stack）

	- 队列（Queue）

	- 哈希表（Hash table）

- 更多的知识

	- 二分查找（Binary search）

	- 按位运算（Bitwise operations）

- 树（Trees）

	- 树 —— 笔记 & 背景

	- 二叉查找树（Binary search trees）：BSTs

	- 堆（Heap） / 优先级队列（Priority Queue） / 二叉堆（Binary Heap）

	- 平衡查找树（Balanced search trees）（基本概念，非细节）

	- 遍历：前序、中序、后序、BFS、DFS

- 排序

	- 选择排序（selection）

	- 插入排序（insertion）

	- 堆排序（heapsort）

	- 快速排序（quicksort）

	- 归并排序（merge sort）

- 图（Graphs）

	- 有向图（directed）

	- 无向图（undirected）

	- 邻接矩阵（adjacency matrix）

	- 邻接表（adjacency list）

	- 遍历：广度优先(BFS), 深度优先(DFS)

- 更多知识

	- 递归

	- 动态规划

	- 面向对象编程

	- 设计模式

	- 组合 & 概率

	- NP, NP-完全和近似算法

	- 缓存

	- 进程和线程

	- 测试

	- 调度

	- 字符串搜索和操作

	- 字典树（Tries）

	- 浮点数

	- Unicode

	- 字节顺序

	- 网络

- 系统设计、可伸缩性、数据处理（如果你有4+年经验）

- 终面

- 编程问题练习

- 编程练习和挑战

- 当你临近面试时

- 你的简历

- 当面试来临的时候

- 问面试官的问题

- 当你获得了梦想的职位

-	---------------- 下面的内容是可选的	----------------

- 

- 额外书籍

- 附加学习

	- 编译器

	- Emacs and vi(m)

	- Unix 命令行工具

	- 信息论

	- 奇偶校验位 & 汉明码 (视频)

	- 系统熵值

	- 密码学

	- 压缩

	- 计算机安全

	- 垃圾回收

	- 并行编程

	- 消息传递，序列化和队列化的系统

	- A* 搜索算法

	- 快速傅里叶变换

	- 布隆过滤器

	- HyperLogLog

	- 局部敏感哈希

	- van Emde Boas 树

	- 增强数据结构

	- 平衡查找树

		- AVL 树

		- 伸缩树（Splay tree）

		- 红黑树

		- 2-3 查找树

		- 2-3-4 树(也称 2-4 树)

		- N-ary (K-ary, M-ary)树

		- B 树

	- k-D 树

	- 跳表

	- 网络流

	- 不相交集 & 联合查找

	- 快速处理的数学

	- 树堆 (Treap)

	- 线性规划

	- 几何：凸包（Geometry, Convex hull）

	- 离散数学

	- 机器学习

- 一些主题的额外内容

- 视频系列

- 计算机科学课程

- 论文


# <a id="whyuseit">为何要用到它？</a>

当我开始这个项目时，我不知道堆和栈的区别，不了解时间复杂度（Big-O）、树，或如何去遍历一个图。如果非要我去编写一个排序算法的话，我只能说我所写的肯定是很糟糕。一直以来，我所用的任何数据结构都是内建于编程语言当中。至于它们在背后是如何运作，对此我一概不清楚。此外，以前的我并不需要对内存进行管理，最多就只是在一个正在执行的进程抛出了“内存不足”的错误后，才会去找解决方法。在我的编程生涯中，虽然我有用过多维数组，也用过关联数组成千上万次，但我从来没有自己实现过数据结构。

这是一个漫长的计划，以至于花费了我数月的时间。若你早已熟悉大部分的知识，那么也许能节省大量的时间。

# <a id="howuseit">如何使用它</a>

下面所有的东西都只是一个概述。因此，你需要由上而下逐一地去处理它。

在学习过程中，我使用 GitHub 特殊语法的 markdown 去检查计划的进展，包括使用包含任务进度的任务列表。

**创建一个新的分支，以便你可以像这样去勾选计划的进展：直接往方括号中填写一个字符 x 即可：[x]。**

Fork一个分支，并跟随以下的指令
通过单击 Fork 按钮来 fork GitHub 仓库：jiangmin42/Coding-Interview-University

克隆项目到本地
git checkout -b progress

git remote add jwasham https://github.com/jiangmin42/Coding-Interview-University

git fetch --all

在你完成了一些修改后，在框框中打 x
git add .

git commit -m "Marked x"

git rebase jwasham/master

git push --set-upstream origin progress

git push --force

[更多关于 Github-flavored markdown 的详情](https://guides.github.com/features/mastering-markdown/#GitHub-flavored-markdown)

# <a id="DonotEenyYourself">不要觉得自己不够聪明</a>

- 大多数成功的软件工程师都非常聪明，但他们都有一种觉得自己不够聪明的不安全感。

- 天才程序员的神话 (视频，待翻译)

- 不要单打独斗：面对技术中的隐形怪物（视频，待翻译）

# <a id="RelatedVideos">相关视频资源</a>

译者语：这一部分全是国外的付费课程，我尽量找一些国内的类似的课程来替代。

# <a id="InterviewPreparation">面试过程 & 通用的面试准备</a>

- [ ] [ABC：不要停止编程（Always Be Coding）](https://github.com/jiangmin42/Coding-Interview-University/blob/main/tips/ABC-%E4%BF%9D%E6%8C%81%E7%BC%96%E7%A0%81.MD)
- [ ] [白板编程（Whiteboarding）](https://github.com/jiangmin42/Coding-Interview-University/blob/main/tips/%E7%99%BD%E6%9D%BF%E7%BC%96%E7%A8%8B.MD)
- [ ] 揭秘技术招聘 (译者语：youtube视频，等我搬到国内)
- [ ] 如何在科技四强企业中获得一份工作：
	- [ ] “如何在科技四强企业中获得一份工作 —— Amazon、Facebook、Google 和 Microsoft”（视频） (译者语：youtube视频，等我搬到国内)
- [ ] 解密开发类面试第一集：
	- [ ] Gayle L McDowell —— 解密开发类面试（视频）(译者语：youtube视频，等我搬到国内)
	- [ ] 解密开发类面试 —— 作者 Gayle Laakmann McDowell（视频）(译者语：youtube视频，等我搬到国内)
- [ ] 解密 Facebook 编码面试：
	- [ ]方法(译者语：youtube视频，等我搬到国内)
	- [ ]问题演练(译者语：youtube视频，等我搬到国内)
- [ ] 准备课程：
	- [ ] 软件工程师面试发布（收费课程）：(译者语：收费课程，等我找个类似免费的)
		- [ ]从前 Google 面试官身上学习如何准备自己，让自己能够应付软件工程师的面试。
	- [ ] Python 数据结构，算法和面试（收费课程）：(译者语：收费课程，等我找个类似免费的)
		- [ ]Python 面试准备课程，内容涉及数据结构，算法，模拟面试等。
	- [ ] Python 的数据结构和算法简介（Udacity 免费课程）：(译者语：收费课程，等我找个类似免费的)
		- [ ]免费的 Python 数据结构和算法课程。
	- [ ] 数据结构和算法纳米学位！（Udacity 收费纳米学位）：
		- [ ]获得超过100种数据结构和算法练习以及指导的动手练习，专门导师帮助你在面试和职场中做好准备。
	- [ ] 探究行为面试（Educative 免费课程）：(译者语：收费课程，等我找个类似免费的)
		- [ ]很多时候，不是你的技术能力会阻碍你获得理想的工作，而是你在行为面试中的表现。

# <a id="ChooseAProgrammingLanguageForTheInterview">为你的面试选择一种语言</a>

你可以在编程这一环节，使用一种自己用起来较为舒适的语言去完成编程，但对于大公司，你只有三种固定的选择：
- C++
- Java
- Python

你也可以使用下面两种编程语言，但可能会有某些限制，你需要实现查明：
- JavaScript
- Ruby

我之前写过一篇关于在面试时选择编程语言的文章：[为编程面试选择一种语言。](https://github.com/jiangmin42/Coding-Interview-University/blob/main/tips/%E4%B8%BA%E7%BC%96%E7%A8%8B%E9%9D%A2%E8%AF%95%E9%80%89%E6%8B%A9%E4%B8%80%E7%A7%8D%E8%AF%AD%E8%A8%80.MD

你需要对你所选择的语言感到非常舒适且足够了解。

由于我正在学习C、C++ 和 Python，因此在下面你会看到部分关于它们的学习资料。相关书籍请看文章的底部。

# <a id="书单">书单</a>

为了节省你的时间，以下是比我使用过的更缩减的书单。(译者语：关于书单，我另行提供)

