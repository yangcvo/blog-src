title: "关于可扩展性和迁移成本——以Hexo为例"
date: 2015-04-28 23:12:24
tags:
  - Blogging
  - Software
categories:
  - Life
  - Essay
cc: true
comments: true
thumbnail: http://ww2.sinaimg.cn/small/e724cbefgw1erloakbg0hj20hs08ymxu.jpg
---

这周六晚上我对博客动了个大手术，把博客的主题从 Pacman 换成了现在的 icarus。

大约从深夜十一点开始折腾，当我终于满意，感觉可以发布的时候，已经五点多，看看窗外天都亮了。

页面布局从之前的两栏变成了三栏，左边是个人资料和站点信息，让我可以在博客的各个页面强刷存在感。放在个人资料里面的微信二维码也不会在平板上响应式的时候把页面弄的不和谐，招聘小广告还是照样打打。

<!-- more --><!-- indicate-the-source -->

页面右侧的挂件有一个最近文章列表，如果文章有配图的话效果想必会很不错。分类挂件终于支持层级分类，之前用 Pacman 的时候我折腾了老半天才发现是主题把这个功能阉割了。总之，切换主题之后的效果我还是比较满意的。

切换的过程中，我一边修改代码调试页面效果，一边思考着为什么我切换一个主题要做这么多事情，是什么东西把博客主题的迁移成本弄的这么高？

![](http://ww2.sinaimg.cn/large/e724cbefgw1erloakbg0hj20hs08ymxu.jpg)

# 学习 #

是不是一个软件需要被用户学习之后才能够正常使用，就会产生较高的迁移成本？

乍一看似乎是这么回事，花了大把的精力才学会用这么个破软件，怎么能说换就换呢？再一想，我感觉这种说法根本站不住脚，学习成本和迁移成本完全是不沾边的两回事。

当初用了许多年的 Windows，大一的时候为了技术进步，一咬牙一跺脚就把 Windows 删了只用 Linux。工作之后为了更高的工作效率买了 Mac，一个下午就把工作流从 Linux 上迁移了过来。曾经吭哧吭哧学 Vim 学了好久都没能登堂入室，大三的时候拜读了 SICP 就直接转投 Emacs。

可见，无论你在原先的软件上花了多少功夫去学习和钻研，只要别的软件更好学好用，基本上切换过去的迁移成本会很小。学习成本和迁移成本之间关系并不明显。

# 扩展 #

我又在想，会不会是软件的可扩展性给软件带来了迁移成本？

Hexo 是一个可扩展性很好的静态博客系统，在 2.x 版本中支持有大量的插件，升级到了 3.x 版本之后虽然插件数量减少不少，但还是瘦死的骆驼比马大。

因为并没有切换到其他的博客系统，仅仅是在 Hexo 下切换一个主题，跟插件的多少并没有关系。

如果我是切换了博客系统，然后 Hexo 能够提供目标系统不能提供的功能，目标系统在功能上的缺失就会给我带来很高的迁移成本，要么我忍忍接着迁移，要么我想办法在新系统中实现类似的功能。

之前有好长一段时间我没用 Emacs，后来还是用回去了。原因不在别的，就是有一个功能让我难以释怀，Highlight Tail。其他的编辑器没有插件或者现成方案能够实现类似效果，然而对我来说这种 eye candy 能够极大的刺激我的创作欲望，所以我最终还是回到了 Emacs 的怀抱。

虽然在这里，Hexo 的可扩展性不是造成我在切换主题时候有着有如此高的成本的原因，但是它可能称为我日后切换到其他博客系统时候的阻力。之前博客的 Timeline 页面是使用 iframe 来实现的，为了在写时间轴的时候不用手写 HTML，我在前些日子写了一个 Hexo Plugin 来处理我自定义的一个 Tag，把 Hexo Tag 语法的文本转换为我想要的 HTML 代码。

当我迁移到别的博客系统的时候，我就不得不去把这个插件用那个博客系统的方式实现一遍，甚至没法比较轻易的实现。

似乎当用户仅仅是使用别人提供的扩展的时候，只要迁移目标提供了类似的功能，其实用户的迁移成本是很低的。一旦用户为了满足自己的小众需求去创作了扩展，这时候迁移成本瞬间就上去了。

# 定制 #

仔细想了想，其实创作扩展还不是导致迁移成本最高的点。一旦用户去修改了软件的源码，增加功能来满足自身的需求，用户基本上就很难迁移到其他软件上面了。

修改源码增添功能其实是一件比较费时费力的事情，而且需要用户亲自动手去做，这种需求一般来就不是普遍存在的，属于小众中的小众。软件的其他同类替代做得再好，也不太可能实现这种功能。于是，用户即使硬着头皮迁移过去了，还是面临着需求重新造轮子的悲剧。除非新的软件有着十足的吸引力，让用户不惜在一个陌生的代码中摸索，也要迁移到新的软件上。

我之前就是对 Pacman 主题做了很多很多的修改，为了尽可能的保持切换前后的一致性，我需要把这些小修改迁移到 icarus 上，同时要让这些修改和 icarus 和谐相处，因此不是简单的把代码迁移过来了事，我需要弄清楚 icarus 的代码结构页面结构等各种东西，然后在合适的地方做恰如其分的修改。

幸好 icarus 和 Pacman 的都用的 ejs 文件作为渲染页面的模板，省去了我学习新模板语言的成本。除了迁移之前的定制之外，我还把新主题中我看不顺眼的地方通通调整了一遍，可能导致访问缓慢的地方通通修改掉，于是博客终于可以拉出来见人了。

# 总结 #

切换一个主题尚且如此辛苦，更不用说切换博客系统了。

但愿 icarus 这个主题能够让我用更长的时间，之前的主题，估计不会切换回去了。

