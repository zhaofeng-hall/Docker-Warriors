# 战报：4月20日

by [战地记者老肖](https://github.com/xiaods)

23、24、25日Qcon大会就要开始了，又一批大咖专家来给大家洗脑了。请大家一定要保持清晰的头脑，自己做判断。

刘斌使用语法工具，正在横扫所有Docker相关项目，大家的typo patch的机会基本快没了。跪了。

这次出现新的华为开发者，zhang wei，欢迎新战队成员。

有些compose/kitematic/machine，这些直接开发者用的项目，基本上吸引不了我们中国开发者。


## docker/docker

Commits on Apr 20, 2015

- coolljt0725 - Add support cpu cfs quota
- coolljt0725 - Remove redundant '\n' in daemon.go and correct the warning messages f… 
- HuKeping - Remove Job from Info API
- Mashimiao - clenaup: delete unused function getEnv
- hqhq  - remove unused function in server_unit_test.go
- WeiZhang555（Zhang Wei <zhangwei555@huawei.com>） change httpError logic

> 点评：除了zhang wei是新上来的华为开发者。其他选手也都是华为的主力选手了。当然我们不能忽略Mashimiao，富士通的开发者。

## docker/libcontainer

Commits on Apr 20, 2015

- liubin - fix some typos in source code comments

> 点评：刘斌的工具有可能直接导致华为KPI积分的丢失（玩笑，勿当真），还请刘斌手下留情，做一些高级一些的Patch吧。


## docker/libnetwork

Commits on Apr 20, 2015

- liubin(bin liu <liubin0329@gmail.com>) fix some typos

> 点评：刘斌的工具非常有效果，可以帮检查出语法错误。很棒。这个项目目前有数名Docker自己的工程在维护。应该是一个不错的子项目。
 

## docker/distribution

Commits on Apr 20, 2015

> 点评：连个patch都没有，老外这天都在偷懒。我非常希望马道长能直接参加这个项目的指导工作。这个项目基本无人参与。


## docker/machine

Commits on Apr 20, 2015

> 点评：老外休假中，无Patch

## docker/swarm

Commits on Apr 20, 2015
- liubin - fix some typos in source code
- jimmyxian((Xian Chaobo <xianchaobo@huawei.com>)) - add force-refresh when commit/tag/pull

> 点评：jimmyxian是昨天和我联系上的Docker中国区开发者，对swarm感兴趣，可能之后有什么swarm问题，就可以向他请教了。


## docker/compose

>  点评：崩溃，从18号到20，连续3天没有patch。这个compose项目是不是快死了。。。不对，原来1.2版本发布，1.3版本刚立项。

## kitematic/kitematic



> 点评：目前这个项目由jeffdm一人维护。如果有中国开发者能去帮帮忙，我估计很快可以成为这个项目的maintainer。技术栈有点特别，是nodejs项目。