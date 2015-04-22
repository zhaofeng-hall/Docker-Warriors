# 战报：4月21日

by 战地记者：[老肖](https://github.com/xiaods)

- 第一，Remove engine from * 已经差不多完了。docker项目的job机制发生了很大的改变。以前宏亮写的源码分析可能需要在更新一下。
－ 第二，—default-gateway的feature已经加上，可以自由的指定网关了。pipeworks的部分工作已经集成到docker里。

昨天还和马道长聊天到，让老马能多关注distribution，希望马道长能出手。

## docker/docker

Commits on Apr 21, 2015

- coolljt0725 - Remove redundant `\n` in daemon/daemon.go #12545
* coolljt0725 - Fix weird terminal output format #12471
* WeiZhang555 - change httpError logic #12539

- 点评：看出来了，他们的工作高峰期从我们这个时区来看Docker公司的开发者都是从星期二开始的。Merge pull的patch都刷屏了。 当然还是华为的战队在孤军奋战。昨天听说360、京东、微博开了docker的闭门会议，我就想说了，各位大佬能不能投点资源做做开发者社区，这样开会才能知己知彼，百战不殆。

 
## docker/libcontainer

- liubin - fix some typos in source code comments #546

>  点评：刘斌改错的patch。这两天libcontainer也没有人做patch了，可以考虑入里面做做。这个repo应该比较稳定了。 红帽的rhatdan是核心开发者，可以考虑与他保持联系。

## docker/libnetwork

无中国开发者


## docker/distribution

无中国开发者

> 点评：这个项目非常有可能成为我们中国战区的突破口。我估计没多少人会用这个distribution，请有心人做一个介绍教程吧。
 

## docker/machine

无中国开发者


> 点评：0.3版本开始开发了。


## docker/swarm

- sunyc - Clarify support for filtering with Node ID and Node Name #641
- jimmyxian - Add attach/diff/port/top integration test #649
- liubin - fix some typos in source code #648
- jimmyxian - Force refresh images when commit/tag/pull #650


> 孙雨聪，Coding的CTO，前Google的SRE。你懂的。闲暇之余才来关心swarm，赞。 jimmyxian是华为的Docker开发者，liubin是自动化检查语法错误工具的发起人。我都不用细说了。

## docker/compose

无中国开发者

## kitematic/kitematic

无中国开发者

> 这个工具是Mac专用的工具，考虑中国的开发者也没有关心这个的。明天起我不再翻这里的信息了。