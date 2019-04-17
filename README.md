# 本项目暂停更新，有缘再见

# release
release官方说明

# 使用方法

[模块激活方法](https://github.com/liuzhushaonian/release/blob/master/Instructions.md)

# 声明

## 强调一下，本模块并没有看H漫的操作，本模块仅仅用于显示大妈之家那些因版权而屏蔽掉的漫画，如果你想看H漫而使用本模块，不好意思你走错地方了。本模块谢绝智友论坛"一个人的冬季"搬运，请你就此打住，不要再玷污我和我的模块！

## 我做这个模块不是为了断大妈的财路，仅仅是为了能看到被隐藏的漫画，毕竟在个人订阅里都看不到了，想看还挺麻烦的，而且一不小心换个手机后，基本上找不到被隐藏的漫画了。也希望大妈能够坚挺下去，多赚点钱，然后多买几个土豆吧。

## 本模块完全免费，也不允许任何的收费行为，包括但不限于捐助，赞助，打赏，购买以及商业用途，本人也不会因为本模块以任何名义收取任何人一分钱，有钱给我还不如捐给山区里的孩子。

# release

隐藏在大妈土豆服务器里的神秘漫画啊，请在我面前显示你真正的力量，与你定下约定的模块命令你——release！


# 更新记录

## 0.1-ζ （戴塔）

- 修复若干bug
- 增加漫画本数提示
- 未完待续

## 0.1-ε （伊普西龙）

- 支持太极
- 修改首页指向

## 0.1-δ （德尔塔）

- 固定搜索框位置，修复搜索框消失bug
- 更改漫画源，做到秒刷新。另外，旧源并未放弃，旧版本依旧可以使用，只是速度不尽人意。
- 退出APP后自动隐藏图标
- 没了，祝玩得开心，不对，看得开心。

## 0.1-γ （伽马）

- 添加漫画许愿功能
- 恢复游戏图标，恢复首页广告（我也提到过了不想断大妈财路，之前的版本去掉了首页上的游戏图标以及进入大妈时的广告，现在都恢复了，因为大妈能活到现在不容易，我个人心里还是非常希望大妈能够一直走下去的。之前做这个功能主要是因为调试的时候一直要看这5秒的广告，很浪费时间，才写了个去除的操作，之后上架也忘了去掉这个功能了。）
- 修复搜索框消失bug
## 关于漫画许愿：

入口在"我的"页面，底部有"点击许愿漫画"字样。
此功能仅仅用于请求某些找不到的漫画，如果你找不到某一本漫画了，又没有阅读记录，则可以通过此功能查找该漫画是否存在，如果存在，则下次的周期更新将会更新该漫画，如果不存在，则表示大妈的土豆里已经删除了该漫画的数据库信息，我也无能为力了。



## 0.1-β （贝塔）
- 添加搜索功能
- 更换默认封面

## 0.1-α （阿尔法）
- 完成隐藏漫画的显示

# 原理

没什么好说的，感谢大妈。

目前大妈隐藏漫画的方式大概有四种。

- 浅度隐藏

此为最常见也是最多的方式，一般来说就是订阅了也无法在订阅中心看得到，也无法在APP内搜索到，但是却可以在大妈的官网上搜索到，只是会提示已下架。

- 深度隐藏

这种隐藏方式较为独特，是大妈有意隐藏的漫画，或是一些被大头买走版权的漫画，此类漫画哪怕是在官网上也搜索不到，直接出错并返回首页。但是可以通过个人评论来找到，这也是大多数人为什么喜欢在漫画评论下Mark。

- 拒绝访问

这种隐藏方式无解。大妈封死了访问方式，无法获取其详细信息，使用id访问也只是返回一个locked字符串。<S>这种漫画少见，目前为止也就发现两本。</S>
昨天，也就是2019年4月16日，大妈突然锁死大部分被B站买走版权的漫画，说实话我打算放弃这个项目了，也放弃大妈了。

- 直接删除

这种方式跟第三种有些相似，一样是无解。但不同的是，大妈删除了其id，导致使用id访问时返回的是空的信息，我在下方列出来的大多数是这种直接被删除id的漫画。这种漫画一般是那种限制级别的漫画，不，甚至可以称之为本子了。

以上四种隐藏漫画的方式，第1、2种隐藏的漫画很多。第3种说实话我并不清楚大妈的用意，因为发现的两本漫画都不是什么限制级别的漫画，反而是很正常的欢乐向狗粮型的，所以搞不懂。第4种嘛，限制级隐藏就隐藏吧，反正放出来也是厚码。



# 共享计划

本模块仅仅收录了一小部分被隐藏的漫画，尚且有一些大头漫画没被收录。不过没关系，我在模块内置了上传功能，如果你发现了某一本被隐藏的漫画，请你在漫画页面点击它的封面，就可以向服务器上传该漫画的一些信息，之后这些漫画就可以在封印页面看到了。
我称之为共享计划，意在让更多被隐藏的漫画被发掘出来，让更多人看到。也不需要那么辛苦地去寻找它们。当然，本功能并没有任何依据可以判断漫画是否被隐藏，所以还请不要随意上传没被隐藏的漫画，一来会对隐藏漫画的筛选带来一定困扰，二来也会影响个人阅览。

# 无法收录的隐藏漫画

- 恋姐倾心
- 源君物语
- 监狱学园
- 出包王女Darkness
- 魔物娘的(相伴)日常
- 女子中学生×人妻
- 漫画家与助手们
- 你是我的荡漾女王
- 放学后的游戏
- 猛兽性少年少女
- 偷窥小孔
- 出包王女
- <S>魔王勇者女魔法使外传</S>
- 天真无邪的乐园
- 修女与吸血鬼	15991
- 异世界精灵的日常喜剧
- 异界魔王与召唤少女的隶属魔术
- <S>恶魔人</S>
- <S>坏孩子也可以吗</S>
- <S>Lost -It’s My Life-</S>
- <S>母娘</S>


以上漫画由于各种原因现已无法在大妈上查看，也无法通过漫画许愿功能找到，或许会有遗漏，或许也有出错，如果有人有幸看到了他们，那就说明是我统计出错了。

# 更新时间

目前改为日更，更新时间是半夜3点。

## 给个窍门，找到喜欢的漫画后请尽量下载观看，毕竟大妈的土豆你懂的~


最后补两张图

![](https://ws1.sinaimg.cn/large/c13993a9ly1g1jst2g16xj20u01o0e14.jpg)
![](https://ws1.sinaimg.cn/large/c13993a9ly1g1jstmro1hj20u01o0x1e.jpg)
