# May 13th

by 战地记者[老肖](https://github.com/xiaods)

---

昨天听闻[喻勇@DaoCloud](mailto:frank.yu@daocloud.io)在DockerCon2015有一个[Topic](http://www.dockercon.com/speakers)，将给全世界介绍中国Docker社区的现状，真是为社区感到骄傲。中国Docker社区目前仍然还需要大家的共同努力，才能把大家吸引过来，加油。

对于中国的Docker开发者来说，目前的利好消息是Docker确实要进入中国了，它正在找一个Director来管理中国社区。如果有机会，我会当面去告诉他们，我们中国开发者有多优秀，他们缺不了我们。

但是，Docker的对手coreos/rkt也开始被巨头支持，竞争会更加激烈。请Docker的开发者把眼睛擦亮。从我战地记者的角度来看，这东西发展的速度还是很惊人的，它还吸收了k8s的Pod概念，并且还有华人在做Contribution（[xiang90](mailto:xiangli.cs@gmail.com)、[Yifan Gu](mailto:yifan.gu@coreos.com)）。目前我建议有时间的开发者已经可以入手，操起Rkt的代码了。

> *注意，CoreOS的Rkt仍然是一个企业支持的开源项目，和Apache基金会管理的项目是两码事，所以和Docker比，并不高明到那里去。并且Docker的特性现在是跑步式的前进。CoreOS/Rkt除了分裂社区，确实看不出有什么优点。(此处仅代表作者个人观点)*

好了，请允许我给大家继续介绍前方战况吧。


## docker/docker

- hqhq - Remove redundant warning 

> 点评：最近是在准备去DockerCon吗？国内战队的人已经很少在Commit里刷脸了。请大家到群里交流下。唯独黄强兄还在抗大旗。加油。


## docker/libcontainer

- hqhq - don't fail when subsystem not mounted

>  点评：目前libcontainer应该是进入稳定区，commit已经还少了。


## docker/libnetwork

- junxu(xujun@cmss.chinamobile.com) - Simplify the code in the RegisterSubnet method of ipallocator.

> 点评：这位新入的开发者是苏州的中国移动的开发者，嚓，我去联系下他。


## docker/distribution

- davidxia (David Xia <dxia@spotify.com>) - Fix broken ROADMAP link

> 点评：是个华人，看了它的Linkedin，应该是个会中文的外国人了。


## docker/machine

- 无中国开发者

> 点评：好歹是个顶级项目，就是没人参加。

## docker/swarm

- jimmyxian - add-support-images-save
- jimmyxian - fix var name and integration test 
- jimmyxian - update api README.md 

> 点评：Xian Chaobo <xianchaobo@huawei.com>，华为工程师。看来在关注这个项目。

## docker/compose

- 无中国开发者

## kitematic/kitematic 

- 暂时不关注了。