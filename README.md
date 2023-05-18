# Academic Research Guidelines

Academic Research Guidelines: 计算机小白科研入门快速教程

科研是一种充满挑战和探索的旅程，对于科研小白来说，刚开始踏入这个领域可能会感到无所适从和迷茫。但是，科研也是一项充满乐趣和成就感的工作，只要你具备正确的方法和态度，就能逐渐掌握科研的技巧和窍门，不断提升自己的能力。

本教程旨在为科研小白提供一个快速入门的指南，帮助你更好地开始你的科研之旅。无论你是大学生刚刚踏入科研领域，还是行业人士想要转行从事科研工作，本教程都将为你提供一些经验和实用的建议。

在本教程中，我们将分享一些科研中常用的工具，也会分享一些科研入门的基本知识和经验，希望能够帮助你更高效地进行科研工作。

我们相信，通过学习和掌握这些基本知识和技巧，你将能够在科研中更加自信和有效地前行。无论你的目标是进一步深造、开展创新研究还是为行业提供解决方案，本教程都将成为你迈出科研第一步的得力助手。

最后，希望你在科研的旅程中保持对知识的渴望和对探索的热情。科研是一项需要持之以恒的工作，但也是一项让人沉浸其中、乐在其中的工作。相信自己的能力，勇于尝试，不断学习和成长，你将会在科研的海洋中获得属于自己的宝贵经验和成果。祝你在科研之路上取得好的开端！

<div align="right">by: ChatGPT</div><div align="right">date: 2023.5.18</div>

## 目录

- [征稿通知（Call For Papers）](./Call-For-Papers.md)
- [投稿指南（Submission-Guidelines）](./Submission-Guidelines.md)
- [学术会议列表（Academic-Conferences）](./Academic-Conferences.md)
- [学术期刊列表（Academic-Journals）](./Academic-Journals.md)

---



**科研工具篇：**

- 熟练使用 [Google Scholar](https://scholar.google.com/)、[DBLP](https://dblp.org/)、[arXiv](https://arxiv.org/) 等文献检索检索工具。能够熟练使用关键词、作者姓名、发表日期、论文题目、会议名称、等进行文献的筛选。[[参考资料](https://www.bilibili.com/video/BV1Rj411u7kw)]
- 学会使用LaTeX作为论文撰写工具，**学术论文/学位论文均要求使用LaTeX进行撰写**。[[参考资料](https://blog.csdn.net/m0_38068876/category_10779337.html)]
- 使用 [Zotero](https://www.zotero.org/) + [坚果云](https://www.jianguoyun.com/) 部署多设备的文献管理环境，文献要按类别进行存放。
- 熟练使用 [LetPub](https://letpub.com.cn/) 或 [《中科院文献情报中心期刊分区表》](http://www.fenqubiao.com/Default.aspx) 等工具查询中科院SCI期刊分区表。[[参考资料](https://blog.csdn.net/m0_38068876/article/details/130719121)]
- 熟练使用《中国计算机学会推荐的国际学术会议、期刊》查询会议、期刊的A/B/C等级。[[参考资料](https://blog.csdn.net/m0_38068876/category_11820954.html)]
- 一律使用Anaconda-Navigator作为Python的开发工具。[[参考资料](https://blog.csdn.net/m0_38068876/article/details/128364154)]
- 掌握常用的科研工具，如：Anaconda-Navigator、Xmind、Zotero、DBLP、知云文献翻译等。[[参考资料](https://blog.csdn.net/m0_38068876/article/details/127873013)]

---

**项目协作篇：**

- 所有项目必须使用Git来进行代码版本管理，不限于gitee/github/gitlab等平台。
- 所有代码文件、类、函数必须要写注释，标记作者姓名、撰写时间和代码描述，如：
  ```shell
  @author: Allenpandas
  @date: 2023-5-17
  @desc: 本代码实现了XXX功能
  ```
- 公共的服务器的配置文件变更时，必须加注释，如：

  ```shell
  # author: Allenpandas
  # date: 2023-5-17
  # desc: 配置redis3.2时，新增环境变量。
  export PATH="/usr/local/opt/redis@3.2/bin:$PATH"
  ```

- Python撰写的项目要求：
  - 必须使用conda进行python项目的管理，一个项目使用一个conda环境。
  - 项目必须撰写README.md，介绍环境部署、运行步骤等信息。
  - 必须创建requirements.txt文件，将环境所需的包信息列入；同时，推荐使用`pip -r requirements.txt`命令部署开发环境。

---

**经验之谈篇：**
- 能够随口说出自己研究领域内知名的顶会顶刊名称，如：AAAI、IJCAI、ICML、ICLR、ICRA、AAMAS、NDSS、WWW、CCS、TITS等。
- 任意给你一篇文章，能够查询到文章的出处（发表在哪个期刊或会议上），并查询到这个期刊或会议的级别（期刊指：中科院SCI分区和CCF等级，会议指CCF等级）。


---

**校园生活篇：**
- 熟悉各个教学楼的位置及代号，如：思源西楼（SX）、思源楼（SY）、思源东楼（SD）等。
- 熟悉大学生活动中心（学活）、第九教学楼（九教）、9号楼（先进处）、8号楼（科技处/军工办）、思源楼校长办公室等与项目相关办公场所的具体位置，能够独自办理相关流程。


---

**习惯养成篇：**
- **明确任务：** 导师或师兄师姐布置完任务之后，需要重复任务内容进行确认，防止理解不一致导致返工。
- **及时反馈：** 论文撰写、项目执行时要定期、不定期的反馈进度。尤其是遇到新的问题可能导致执行方案与最初方案有所偏差时，当决定切换方案时务必开会重新讨论！禁止私自修改方案！
- **学会学习：** 不要抱着一门书从头到尾的翻页学习，也不用跟着一个视频从头到尾的学习。研究生阶段最高效的学习方法一定是**任务导向型/目标驱动型**的学习方式，即：先参与项目或者先阅读论文，遇到不会的地方再查阅文献对指定内容进行学习。
- **学会提问：** 提问前要明确问题是什么，遇到的问题是否尝试解决过？尝试了哪些方案，又遇到了什么问题？
- **学会交流：** 交流的前提一定要有积累，这个积累可以是阅读文献后做的笔记，可以是fellow某人工作突然有的idea，也可以是遇到问题的记录……总之交流之前不能空口而谈，什么都没有就来交流。

- **学会请教：** 
  - 及时请教：有问题及时提问，尽量不要隔夜、不要堆积问题。
  - 主动请教：有问题主动提问，不要等导师或师兄师姐问起时再汇报问题。要定期、不定期主动找导师汇报工作。
  - 找正确的人请教：优先导师，其次是导师推荐的师兄师姐。找不到正确的请教对象，花再多的时间也很难找到正确的答案。
- **学会复盘**： **要求每周六（周五晚24:00/周六0:00）之前需要提交本周的工作总结**，总结本周工作的内容、目前科研工作的进度、下周工作计划。
- **再三检查：** 撰写的申报书、需要盖章的材料、科研论文学术论文，一定再三检查关键信息。
- **事半功倍：** 熟练掌握科研工具，学会利用科研资源，保证在实验室的科研时间，提高科研效率。

---

**心态锻炼篇：**

- 沉心静气，严禁浮躁。
- 要锻炼自己的抗压能力和多任务并行能力，不要有玻璃心。
- “万事开头难”，畏难时要说服自己迈出第一步；“行百里者半九十”，做事情要有始有终。
