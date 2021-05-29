# archlinux 真的适合我吗？

> ### 🍉 三思而后行
>
> 对于萌新（特别是对于 Linux 还是萌新的萌新）来说尝试安装 archlinux 之前，有必要了解 archlinux 是否真正适合 TA 们

> ### 🔖 这一节将会讨论：
>
> 1. 对于 Linux 萌新来说，archlinux 真的适合作为 TA 们的入门发行版吗？

> 这里，笔者自作主张的设立了 3 个判断标准，按照重要程度排列

## 判断标准之一：你是否具有一定的 Linux 基础？

不少 Linux 萌新可能从不同渠道听过一种说法，那就是选择 archlinux 作为 TA 们的入门发行版。理由包括但不限于：

1. 通过安装和使用 archlinux 我可以更好的了解 Linux 底层运作的原理
2. archlinux 的软件很多
3. 遇到问题好好看 [archWiki](<https://wiki.archlinux.org/title/Main_page_(%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87)>) 就好啦

这些理由所叙述的事实单独来看确实没有任何问题，但作为推荐 Linux 萌新选择 archlinux 作为入门发行版就显得不太合适了。理由有下：

1. 了解 Linux 底层运作的原理对于学习 Linux 的人来说无疑是一个进阶的话题了；脚踏实地，先从 Linux 基础甚至基本的计算机常识开始掌握才是正确的学习姿势。否则就知识体系就如同空中楼阁，摇摇欲坠
2. archlinux 的软件确实很多，甚至由于 arch 之道中实用性大于意识形态的原则，包含有不开源甚至非自由软件；但是对于其它发行版来说，日常使用的大部分软件也都在软件仓库中存在
3. [archWiki](<https://wiki.archlinux.org/title/Main_page_(%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87)>) 的内容的确包含面非常广，甚至非常细节的问题也有说明和解答。但也正是由于这种特性，导致其指引性较差，让用户容易迷失方向，更不用说对于 Linux 萌新了

对于这一部分同学，笔者的建议是先去阅读相关的书籍，在掌握了扎实的 Linux 基础之后，再来尝试 archlinux 吧！这里推荐一本由刘遄老师编写的 Linux 入门 📖 书籍[《Linux 就该这么学》](https://1drv.ms/b/s!AlPueKsomjVKyFcLj_2irwckcLnd?e=A90XOh)，并且作者本着开源精神让广大读者可以免费下载阅读，直接点击链接即可跳转下载（onedrive）。此外，掌握基础的英语阅读水平也是很有必要的，例如经常有一些同学在安装 archlinux 的时候由于看不懂英语的报错信息在已经发生错误的情况下继续执行下一步命令导致安装失败。

> #### 🍧 趣事
>
> 笔者曾经遇到过很多对于 Linux 毫无基础（包括曾经试用过“新手”发行版如 Ubuntu 但是依然不具备 Linux 基础知识）的人想要尝试 archlinux，却在安装时遇到“匪夷所思”的问题，对此略举一二（并没有）：
>
> 1. 小 H 同学在 win10 下经过一上午的努力，终于用 [DiskGenius](https://www.diskgenius.cn/)（win 下的磁盘分区工具）将 💾 磁盘分出了一部分空间以供安装 archlinux，但是却发现使用 `lsblk` 命令在安装环境无法看到分出来的空白空间！“问题”当然显而易见，因为没有分区的空白空间并不是块设备，自然无法用 `lsblk` 命令看到了
>
> 对于那些 `sudo` 命令输密码时看不到输出以为键盘坏了的，这些都是老生常谈了，就不多说了 QAQ

## 判断标准之二：你是否愿意花费时间在折腾系统上？

## 判断标准之三：在遇到难以解决的复杂问题时，能否冷静应对？