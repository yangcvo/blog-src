title: "我在天堂当码农 —— 2014 年度回顾"
date: 2015-05-10 20:16:19
categories:
  - Life
  - Essay

cc: true
comments: true
thumbnail: http://ww2.sinaimg.cn/small/e724cbefgw1erzew6tmvlj21kw16ob29.jpg
---


4 月是 Alibaba 新财年的第一个月，照例在月底发放年终奖。据说每到这个时候，内网一片哀鸿，许多人高呼“万税万税万万税”，履行着公民义务的同时也让人肉痛不已。

我是 2014 年 3 月 7 日从天津来到杭州的，3 月 10 日开始实习。虽然我正式入职是在 7 月 7 日，但是我实习期间基本上全程投入生产，参与了一个底层系统的重构，所以对我来说，工作是从 3 月份开始的。

工作了一整年，也到了该做总结的时候。

<!-- more --><!-- indicate-the-source -->

# 实习 #

刚到杭州的时候，赶上了阴雨连绵的天气。我住在五常大道上的汉庭快捷酒店，距离西溪园区大约六七公里，每天骑着自行车往返。

报道前的那几天，我在屋子里处理邮件，寻找出租房源。就在那几天，我给自己想了个花名，简离，取自《凡人修仙传》的角色，人族大乘修士莫简离。这个花名，也算是纪念从高中到大学期间，那段追着更新看凡人的日子。

我在酒店住了 11 天，然后搬进了一个漂亮的住宅区。我和几个阿里的同事合住，异地实习的住房补贴除了 Cover 房租，还有剩余。

![绿城・翡翠城](http://ww2.sinaimg.cn/mw1024/e724cbefgw1erzew6tmvlj21kw16ob29.jpg)

## 报道 ##

入职那天，我早上 8 点多就到了园区，9 点找 HR 办了实习入职手续，实习单位是菜鸟。就在那天，HR 系统出了点小问题，我迟迟没能出现在内网，所以一直没法领用电脑，只好在工位上等着，翻看师兄给我的《MySQL 核心内幕》。那是天猫技术部的工位，我所在团队那时还在天猫的工位办公。就在那天，我认识了我的师兄北岩，还有当时的主管大通。

到了下午，HR 系统终于好了，师兄带着我去 IT 部门领取电脑。按照规则，实习生只能领取台式机。师兄跟 IT 的同事说我是带着校招 offer 来实习的，他们才给我发了一台笔记本，ThinkPad x230。

虽然这台电脑没比我当时自己那台二手的 ThinkPad t400 好到哪里，但是也比台式机方便了许多。我也就没折腾系统，按部就班的给电脑装上 JDK、Eclipse 等等，搭建开发环境，然后照着师兄给的一份新人文档开始尝试使用 WebX、HSF 等内部框架。

## 页面狗 ##

开始的一周，我都在工位上自己看文档写 Demo。许多年没用 Java，用起来也是满腹的怨念，对于 Web 框架我倒是没什么感觉，反正我也没用过别的框架。那时候师兄和两三个同事在项目室里，做着一个新应用。

有一天我跟师兄说文档里面的东西我看完了，有没有其他的事情可以做。师兄想了想，带着我到了另一个项目室里，让我跟着另一个同事做项目。那是一个重构项目，重构一个支撑着菜鸟各种物流业务的系统。师兄正在做的应用对这个底层的系统有着比较强的依赖。当然，这个底层的系统由多个应用组成，我参与重构的应用只是其中一个。从那天开始，我在那个项目组混了两个月，跟着李元、心动两位前辈，学了不少东西。

那两个月，我们的任务就是写页面，写页面，修小强，修小强。4 月中旬的时候请了 3 天假回学校中期答辩，然后回来接着干活。

坐在我旁边的是恪明，一个刚从北航毕业的硕士学长。我们都对 Java 满腹怨念，一起吐槽招聘的时候仿佛找的是计算机科学家，结果进来了之后干的却是写页面的活。

那两个月，虽然工作上没有啥挑战性，却让我的代码的气质完全变了。在学校的时候，我们写的是程序，写的是算法，追求的是简洁，追求的是酷；在公司里，我们写的是软件，每行代码都是为了在生产环境中创造价值，注重的是逻辑清晰、可维护，以及健壮性。我也从一个 Coder，渐渐变成了 Developer。

那段时间，经常和师兄还有同事们一起吃饭，有一次师兄跟我说，新人都是从简单的工作开始做起的，只有把简单的事情做好了，才会接到有挑战性的任务。

虽然我不甘于每天写着页面，指尖流出的代码一行行都是各种业务逻辑，但是想到师兄的教诲，我还是坚持把手头的事情做好，然后在业余，自己找时间做喜欢的事情。

那段时间的周会，轮到我汇报工作的时候，我能说的都是，我在写页面。实际上，下班之后我回家还要做我的毕业设计。两次小长假，清明和五一，我都我在房间里写毕设的代码。那段时间里，用 Python 写毕设，成了我寻找乐趣的一种途径。

后来，5 月 21 日，项目发布。第二天我就回学校，写论文，答辩。

## 自我投资 ##

大概在 4 月中旬，我实在无法忍受在 Windows 系统上做开发了。原本打算用信用卡分期付款买一台 MBP，结果被招行放了鸽子。申请信用卡的时候说的是阿里员工都有一万到两万的额度，结果拿到的信用卡只有 8000 信用额，而且还是普卡。当时我就怒了，直接重新申请了一张金卡，然后动用父亲之前给我的一笔资金购买了 15 寸的 MBP。

在我拿到阿里的 offer 之后，父亲往我的卡里打了一笔钱，让我定期存着。父亲说，手中有钱心中不慌，的确如此。哪怕 7 天的报销期过了，我依然住在酒店里，直到我找到满意的房子；我可以在短短几个月接连购买最好的电子产品，让我从此不再浪费时间去和手机电脑较劲。

现在想来，如果我能够更早拥有这些设备，该多好。

我的父亲是一个有见识的人，但是在电子产品上，却异乎寻常的古板。直到现在，无论我如何说明解释，他都难以理解，最好的电脑，最好的手机，对一个开发者意味着什么。在移动互联网大大提高了我们获取知识和信息的效率的今天，他还经常跟我说，手机就是用来打电话和发短信的。当他知道我买了 MBP 之后，居然问我是不是下一步要买小型机。也许他没有亲身经历那种在廉价设备上工作的效率和心情，没法理解一个好的设备能够给开发者的生产力带来怎样翻天覆地的解放。

# 毕业 #

我的毕设和机器学习有些关系，确切的说，是排序学习，Learning to Rank。那时候我估算了一下，在我的笔记本上，需要一个月不间断的满负荷计算，才能把结果跑出来。如果我回学校用实验室的服务器跑，时间可以缩短到一周。因为实验室的服务器有 32 核，我的笔记本才 8 核。

回到学校后，我一头扎进实验室，把数据和程序放到服务器上，火力全开跑数据。恐怕我是第一个把实验室的服务器全负荷跑起来的人，据说之前这台 Linux 服务器除了我别人都没怎么用过。

一边跑数据一边写论文。我和蔡育琛一起，以学长留下的 LaTeX 模板为基础，做了大量修改以适配新的论文模板。比较欣慰的是，除了我们两个，还有其他几个同学也用我们修改之后的模板。

事实证明，LaTeX 帮我们节省了大量时间，一个人对模板的修正，可以直接分享给其他人。而且大家一起找问题，我和蔡育琛修问题，很快就把 LaTeX 模板中不符合最新论文模板的地方修正了。用 Word 写论文的同学则没有这么幸运了，在调格式这一最没价值的环节各自为战，花了大量精力调格式还是被那些只看格式的老师喷成狗。

毕业季，有人欢喜有人愁。我们这些有了去处的家伙自然是逍遥自在，不是在宿舍玩电脑就是单独约上朋友吃离别饭。那时候，南开东门外的一家叫味好家的牛排店，成了我请同学朋友吃饭的固定场所。

大学四年，我一直以学渣的身份，混迹在莘莘学子的最底层，一切的奖学金、荣誉都和我无关。亲人的失望和不解如影随形，他们没法理解一个学霸为何“堕落”成了学渣，以为是我不努力，不争气。如果不是发自内心喜欢计算机，喜欢编程，恐怕我早已放弃。其实我明白，不要指望别人理解你，哪怕是亲人也不见得能理解你，他们甚至认为你在技术上的追求只是为了掩盖成绩上的差强人意。

人生在世，只求无愧天地。要对自己负责，才能有自由。

## 师者 ##

虽然这四年远远谈不上不快乐，但是我还是认识了一些让我发自内心去尊重的老师。

王建荣，副教授，我的第一位导师，讲授《计算机科学导论》，《C++ 程序设计》。大一时候我两次参与校 ACM 队选拔落榜，然后加入了他主持的 RoboCup 实验室。虽然我因为成绩很差，一直没怎么参与实验室的事务，现在实验室的页面上也看不到我曾经存在的痕迹，我还是很感谢王老师当初对我的关心。

张钢，教授。第一次上张老师的课是《计算机体系结构》，后来大四上学期又修了他讲授的《用户界面设计》。张教授是一位让人肃然起敬的老先生，头发花白却神采奕奕，讲授的课程让学生舍不得翘课。在用户界面设计这门课上，张教授说我是这届学生中，唯一见到他会主动打招呼的学生，他也因此记得我的名字。

杜朴风，副教授。我们是在他讲授的《开源技术及应用》上认识的。那时候是大三，虽然那时候我已经用 Linux 许久了，还是在这门课上学到了一些有趣的东西。杜老师喜欢用一些小奖品去奖励积极回答问题的同学，我手边的罗技鼠标，就是这门课上得到的奖品。大四的时候他去香港当交流学者了，我拿到 offer 之后没几天刚好碰到回到天大的他，第二天我们聊了聊我的选择和未来的发展之类的。感谢杜老师给我的鼓励，让我能够更加坚定的在旁人甚至亲友的不解中坚持走下去。

廖士中，教授，讲授《人工智能》。这门课是我整个大三学得最认真的课，虽然廖老师和学生没有太多的互动，我却能感受到他骨子里作为一个真学者的坚守。

冯志勇，教授。冯教授是计算机学院的副院长，也是我一个同学的父亲。上过冯教授讲授的《知识工程》和《数值计算》。

冯伟，副教授，讲授《图像处理》。他说，如果一个学者，如果连自己的研究领域都不能讲的生动有趣，估计研究出来的东西，嘿嘿嘿。

## 别津门 ##

7 月 6 日毕业典礼，我 7 月 5 日又返回天津。我没有参加毕业典礼，典礼结束后我和好友刘典一起吃了火锅，他那段时间一直在帝都，自己租了一间房子，准备考北大法律的研究生。

7 月 7 日，我带着毕业证搭乘动车赶回杭州，办理正式入职。终于可以离开这个压抑了我整整四年的地方，到一个或许更加适合我的地方，继续我的奋斗。离开那天，心里有着说不出的激动。

# 工作 #

工作就这么开始了。一个一个的日常，一个一个的项目，交互改造，电子面单二期，双 11，双 12，电子面单三期。

有些时候我也不知道自己这么努力的工作是为了什么。为了成长？为了成为更优秀的开发者？为了自由？我只知道，我不是为了钱，也不是为了 KPI。

入职之后不久，师兄成了我的直接主管，前主管成了我主管的主管，俗称大老板。

其实我一直很感谢师兄北岩，还有大老板大通对我的培养，这是一种以身作则，潜移默化的培养。他们是我敬佩的开发者，这一点比他们是我的主管更重要。希望有一天，我能成为不输他们的开发者和团队领袖。

## 成长 ##

我本不擅长的 Java 以及 Java 技术栈，现在成了我最擅长的开发工具。我原本擅长的开源技术和脚本语言，帮助我成为了更加高效的开发者。

双 11 期间，我用 Linux 和 Python 让全链路压测中，最痛苦的造数据这件事情，变得几乎易如反掌。开始有多年坚守 Windows 的同事在台式机上安装 Linux，学习命令行。

我现在似乎成了技术团队中最擅长用 Mac 的人之一，也成了苹果的义务推销员和技术支持。

有一段时间我以为自己是菜鸟的技术团队中最擅长用 Linux 的人，直到双 11 的时候，一个叫杜琨的技术专家小小露了一手，把我折服。杜琨是菜鸟这边双 11 的技术负责人。

后来，我开始写博客。一开始写一些不痛不痒的东西。后来开始阅读 Guava 源码，写 Guava 系列博客。比较惭愧的是，我有一段时间没写 Guava 系列文章了。

## 年终 ##

<!-- 前些日子，财年结束，开始评定绩效。我原本认为自己做的不够好，只给了自己一个中庸的分数。没想到师兄和大老板最后给了我超出期望的评价，然后我就迎来了人生第一次加薪，还有超出期望的年终奖。阿里一直有这么一个说法，今天的最佳表现，就是明天的最低要求。今年我该如何努力才好？ -->

前些日子，见到恪明的时候，是他在菜鸟的最后一天。那天他带着蚂蚁的工牌，正在和菜鸟的同事交接工作。我们坐下来聊了一会，互道珍重。当年我们一起做项目，一年之后，他转岗去蚂蚁写中间件了，我继续在留菜鸟写业务系统。他羡慕我所在的团队，也羡慕我的绩效。无论如何，他终于能够不写业务系统了，不用再跟 if else 较劲。有本事的人，不怕没工作，不怕换工作，不是吗？

{% blockquote @蔡学镛 http://weibo.com/1614282004/Ch4tlgO5w %}
能力好 => 不怕找不到工作 => 不怕失去现在的工作 => 不怕工作上犯错 => 愿意担负责任 => 拥有更多锻炼的机会 => 能力变更好 ... 这就是职场的正向循环

通过两个入口，可进入此正向循环：1. 很努力学习，让自己能力提升 2. 主动承担更多责任
{% endblockquote %}

其实我不喜欢写业务系统，我渴望更有挑战的事情。我刚入职的时候，师兄跟我说，现在的系统流量还没起来，所以技术上没什么挑战，我们把系统做起来，把流量做起来，有意思的事情就来了。我们就这样一点一点做着，流量也一点一点起来，系统也渐渐在我们手中变得完善起来，我也在跟着系统一起成长。

## 加班讨论 ##

今年发生了不少事情，一些同行因为加班过度先走一步，然后业界开始了关于加班、KPI 等等一系列东西的论战。

![左耳朵耗子的微博](http://ww1.sinaimg.cn/large/e724cbefgw1erze80mknqj20gm04rq45.jpg)

同事问我是站哪边的。我说我站在耗子这边，他们笑了，说我口嫌体正直，因为我是团队里面加班加得最凶的人。

仔细想想，我主动加班已经到了没有生活的程度，除了睡觉之外，基本上其他时间都泡在公司，连周末也是。

耗子说，位置不能带来自由，能力才能让人自由[^1]。显然，耗子已经有了自由的能力，而我还在提升能力的路上。之前大老板跟我说，希望我在编程之外还有其他爱好，恐怕这个比较难以实现，我从今年给生活多留一些时间开始吧。

[^1]: [http://weibo.com/1401880315/CdYHLg7C4](http://weibo.com/1401880315/CdYHLg7C4)

共勉。
