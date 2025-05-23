# idea：读者改写所看小说的剧情

## idea来源
JCF同事提过 ，读者期望对某段剧情改写，朝着读者期望的方向发展，如果质量高呢？那读者读的岂不更满意

## idea描述
「读者」，期望对某个剧情点 改变剧情走向，比如 希望某个角色不死掉 而是假装死了 后面继续作妖

于是「读者」向AI 输入改写剧情要求，AI 接着输出后面的一段，质量如果高的话 就好玩了，玩法如下：

- 【读的爽】改完 发现挺有意思的话，让你读者看的爽
我共鸣了这个需求。我们看电视剧/电影，对某段 上头时，恨不得某个角色立刻下地狱，对某个悲剧结尾非常不满 觉得明明可以以喜剧收场 恨透了编剧。 共鸣的人估计肯定不少，那么 在我们平台看小说，我们有AI帮你实现 岂不快哉！

- 【分享】改完 可以分享到评论区or社区，引起众人围观共鸣
我把「猫鼠游戏」中的马嘉祺 改为了 直男风格后，它也太直了，反而更撩我了，大家来看看吧

-【巨人肩膀上创作】甚至 「读者」在「作者」的允许下，改写后 持续用AI 开辟分支写下去，一起对 本书的广告、付费收入进行分成
如此低成本、快速，让用户改写剧情 持续输出 成为一个分支书籍，用户会很有参与欲望、成就感吧，分享意愿会很强吧

-【让社区嗨起来】改写分享、讨论，作者邀约读者来改写，读者邀约围观者问问怎么还可以怎么改


## 技术担忧
- 对于短篇而言，成本还可以，改写的质量高吗？
  - 待获知 每次成本
  - 待获知 质量高的概率
- 对于（3万字以上）长文而言，AI模型 token消耗 担心会大，成本高。需要探索在长文时 如果控制住 上下文成本合理的前提下 让AI输出 高质量的改写

## 作者合作意愿 担忧
- 作者 担心对自己原书 到底是收入是正影响、还是负影响呢？
  - 我们探索设计合理的合作分成模式，要不 从我们自己私有的作者账号 尝试？

## 验证期 How to verify
追求快速，如果不需要开发，就可以快速验证，就最好了

- 我们先使用人工方式
  - 对 一些好书，每天人工发现，可改写的地方，然后让AI去改，改到不错的程度，发到评论区，看看效果
  - 对于评论区的评论，AI能识别出 真实用户想要改写的评论吗？ 能的话，就减少了人工去找适合改写的地方了


