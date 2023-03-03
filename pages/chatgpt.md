- 语言
	- https://www.youtube.com/watch?v=KwNhAzQN-Nc
- 租售“小生意”实例： https://www.tdchat.com/
- # 我注册使用ChatGPT的经验
- # 注册登录
	- 以下步骤层层递进
	- ## 浏览器
		- 360浏览器禁止访问chatgpt，“懂的都懂”。我目前用微软的edge浏览器
	- ## 搜索引擎
		- （对西部世界vpn而言非必需，知道名称可以直接搜到；但为什么不换个至少更清爽、广告更少的搜索引擎呢？）
		- 国内能直接搜到VPN网站的搜索引擎有[https://neeva.com/](https://neeva.com/)
		- ● 将其设置为默认搜索引擎的方法，以我目前用的Edge浏览器为例，打开一次[https://neeva.com/](https://neeva.com/)后，依次点击右上角三个点-“设置”-“隐私、搜索和服务”-最下方“地址栏和搜索”，将“地址栏中使用的搜索引擎。”改为Neeva
	- ## 换IP：代理服务器和/或VPN
		- （使用科学上网工具会有喝茶风险吗？不会，能看到本文的都是正经人，在争夺公众认知方面，政府对国外在整体上采取守势，而为了经济发展和学术交流，网禁实际上是有限开禁，只是在敏感时期会加大监管力度，并且监管主要针对工具提供者而非工具使用者）
		- 主要目的不是“翻墙”，而是应对openai网站在访问网站、注册、使用等的部分环节查IP（而），目前只有部分国家的IP可以访问、注册、使用
			- ((fc964ebb-e106-4f8e-8ff9-b779c860c572))
		- 登录和使用时可能不查ip
			- 初次使用后，直接关闭VPN或开机未开启VPN的情况下，我发现也可能直接登录（这样加载国内内容更快，也不费VPN流量），也许它只看cookie，但刷新网页（可能是服务器踹你下线，不得不刷新）的话就可能要你重新登录并检查你现在的ip了
			- 我在家可以直接登录，也许是登录过两次就不查了；但在单位登录后关VPN就会出错、就会access denied
		- ### 方案一：使用成品客户端（集成了联网协议客户端和代理服务器）
		  collapsed:: true
			- 我用的西部世界westworld vpn[https://xbww9056.xyz/](https://xbww9056.xyz/)，注册后倒计时试用三天（我就试了这一种，当时看网上攻略说能用临时邮箱持续白嫖，但是不行，但是已经用了）、5G流量，注册时填入邀请者邮箱（我的：ljysxzy@qq.com），注册者和邀请者都能增加三天免费天数，下载安装客户端后点小图标“剩余时长”登陆绑定账号，“开启 西部世界VPN”，选美国节点（可能其他一些国家也行），“绕过中国大陆IP模式”或“全局模式”（否则chat.openai.com可能不让进给你报错，一看ip，发现还在原地）
			- 我遇到的问题
				- 验证码可能被识别为垃圾邮件，不会在“QQ邮箱提醒”等提醒服务中出现，需要打开邮箱查看
				- 找不到VCRUNTIME140_1.dll的解决方法（附下载链接）
					- [https://www.bilibili.com/video/BV1Hu411R7wn/](https://www.bilibili.com/video/BV1Hu411R7wn/)
				- 用了vpn后电脑连不上网（但可能微信还能登）：代理设置，手动设置关闭，看看能不能连上，连上了再打开，应该还是好的
				- 各种设置调来调去，还是相当慢：看看有什么软件在用网，比如高网速下载中的steam
		- 预测
			- 如果国内竞品不够好导致VPN使用者激增（“我都用了”），它们也可能涨价
	- ## 注册openai账号
		- （也许未来短期内也会比较值钱，我已经从一个发了挺多平台的关于chatgpt使用问题的文章里看到一个链接里要46元一个，利润率可能非常高）
		- 打开https://chat.openai.com/或[https://AI.com](https://AI.com)
		- ((a50753d3-5896-4ad2-b89a-c5404eded776))
		- 注册或重设密码时，注意大陆手机号可能要加“+86”
		- 我赶时间用的QQ邮箱（too many signups from the same ip：换ip或账号种类，谷歌邮箱可以当场注册，国内手机号也行，除非你之前注册过），然后国内可能要租手机号收注册用的验证码，我用的推荐最多的https://sms-activate.org/getNumber，（帮大哥注册时，验证我是不是人花了点时间，经常转完就透明不见了，最后我刷新后连点了几下或几十下那个几个转着的圆的圆心，成功——“有种祈雨的感觉”）网站语言可以改成中文，可以用支付宝先充值（支付宝收比较高的2.3%且向上取整到美分的佣金，且一美元起购，但是比这两天刚上线的微信支付比还算良心；余额可能够帮别人激活），然后点左边OpenAI选国家，余额够的话点击购物车图标（注意没拿定主意时不要“试一试”乱点，少个几卢布就买不了）就租到一个号，给你20分钟收验证码，注意复制过去要删掉重复的国家区号。可能同一手机号已有人租过激活过，显示红字的话直接叉掉取消订单，同一国家试几次不行可以换国家（我先按攻略租美国物理的不行，最便宜的印尼的也不行，英国的好像注册两次都是一次就成功）
		- 如果使用时间和隐私方面不冲突的话，也许家人共用一个账号也行，只要把左边列表下的各个chat改好名就行
		- 有次直接关闭vpn，可以照常登录chatgpt和聊天，而谷歌邮箱打不开——但是刷新后到了登录界面，邮箱密码后显示服务不提供给所在国家
		- 进阶用法-本地云服务器（“云服务器滞销，帮帮我们”——看到消息，百度文心一言要搞捆绑销售，不知道用进口货的人买不买吧；之前有篇架设云服务器教程的知乎文章被再次举报删了，忘了它提的哪家的云服务器）：
	- ## 登录问题
		- chat.openai.com服务器繁忙无法登录：
			- 这可能也是限制ip的一个客观原因，服务器确实承受不了那么高黏性（“ChatGPT早该搞防沉迷了”）、高密度的访问，所以很容易“at capacity”，左边每次刷新都给你换一种体裁的“等待”作文（感觉有种游戏《辐射》系列的老美国风格），如果你等不及，又不想花钱走右边Plus通道，可以试试以下方法
			- youtube up主的方法：换浏览器模式（edge的inprivate等无痕窗口）、换浏览器、换设备
			- 网上看的也许针对其他问题但可能同样有用的方法：清空浏览器cookies等缓存（点地址栏左边的“锁”图标，选中cookie文件夹删除）
			- 我建议可以尝试的经验方法：看过的版本就不要重复看了，没出登录界面就一直刷新
			- 一个浏览器能开多个无痕窗口刷新，可以（用quicker、windowtop）置顶窗口避免来回点不着，可以分屏巡回刷新
			- 就登录而言，非无痕窗口登录更简单
		- We have detected suspicious login behavior and further attempts will be blocked. Please contact the administrator
			- 输错密码、换设备登录都可能出现可疑：点忘记密码，重设密码（可以与原密码一样，如果原密码是浏览器等生成的强密码的话，建议不换）后登录
			- 谷歌邮箱因为大陆手机号等原因被停用的话，可能会在openai登录界面提示
			- [https://www.cnblogs.com/jxust-jiege666/p/17116039.html](https://www.cnblogs.com/jxust-jiege666/p/17116039.html)
		- We have detected suspicious login behavior and further attempts will be blocked. Please contact the administrator
			- 可能只是密码错了（一个猜想，不一定对：浏览器自动输入的已保存密码可能是错的，因为如果用邮箱注册，那么对应邮箱的已保存密码可能有多个，可能选了不正确的密码或正确的密码未保存），也可能是用其他未登录过的设备首次登录
			- 可以再次刷新到有log in选项时登录，然后登录，不行就重设密码再刷新
			- 其他方法：[https://www.followchain.org/weve-detected-suspicious-behavior-chatgpt/](https://www.followchain.org/weve-detected-suspicious-behavior-chatgpt/)
		- 空屏：网站繁忙，甚至不能打开等待界面——刷新，如果不行就“等等”
- # 基本使用
	- 点左下角“Updates & FAQ”可以得知，它对历史文本的记忆量有限，我根据个人经验不建议作相关“测试”。你可以通过它的复述渐进、步进地发展对话，所谓“知彼知己，百问不殆”
	- “思维敏捷的你不必等它讲完了再准备下一条的草稿”
	- 每条消息的不同版本（通过你的修改或让它重新生成回复生成），会从相应消息开始分出不同分支。可以更改问得或答得不好的问题，避免一个主题chat堆积过快
	-  可以将不同chat分类（艺术、金融）
	- 聊天记录是存在云端的，不用担心换台设备看不到
	- 猜想：用中文可能慢些，可能它要翻译，但它说它不翻译，如果是真的，也可能它思考中文比较慢，以及中文信息密度更高、你看中文更快，等等
	- ## 使用问题
		- 网页“闪动”导致草稿丢失：提前复制
		-  找个能自动保存输入内容的输入法、浏览器拓展、
		- 由于消息过长而无法生成内容：可以编辑消息，让它成功生成回复
		- Too many requests in 1 hour. Try again later.
		- 我和它讨论完防沉迷就跳出来这个，设置了一小时倒计时，就又可以用了
		- 并且我觉得一般情况下，老实休息是好的
		- [https://www.followchain.org/too-many-requests-chatgpt/](https://www.followchain.org/too-many-requests-chatgpt/)
- # 参考应用
	- 讲故事：“20后的一千零一夜”（配合文本转语音，“电子保姆”就有点样了）
	- 使用与AI的聊天“访谈”做文章播客视频等自媒体（也包括微信朋友圈哦）体裁，并截图分享（“先发个朋友圈”；我用的sharex滚动截图，有些效果不太好，可能与对话消息的对比度有关，用dark reader并切换网站的深浅色模式就好了不少，也可试着增加scroll delay滚动延迟时间（其他的各种都可以点点试试），还可能要先滚动到页面底部一遍，然后再回去开始截图
	- 讲解知识点
	- 纸质作业：拍照扫描转文字（微信可以对图片“提取文字”）并排序后发给它（当然，据说在数学等方面它还不太擅长）
	- 作文（可能直接生成范文）：就中学英语作文而言，我让它帮外交部高干子弟李华写了一封信给特朗普，不清楚现在中学英语作文什么水平，感觉我来阅卷的话“顶多按超字数扣一两分意思一下”
	- ● 不要传用它写出来的公文，群里人信以为真了转发多了你就造谣了，今早刚听到我爸放的《财经早餐》里的新闻
	- ## 语言学习
		- 想不到更好的表述方式就用简单的：它很可能给出包含更好的表述方式的复述，这不就学到了么？
		- ● 混用语言：我认为常规分科教学的效率比较低，在语言方面完全可以混用语言，不会或一时想不到的话就及时换种语言表达，它会复述，然后你就很快学到了不会或一时想不到的话
		- 查词：看不懂的取词、直接复制输入？
		- 口语对话：你的语音转文字，它的文字转语音（例如edge浏览器的地址栏右边的“大声朗读”，下方还有一些natural的语音。在选择过程中，你可能会觉得有点耳熟，因为用ai配音就是这样的）
		- ● tts朗读功能需求：自动识别/手动标记输入框（点击输入框后不切换朗读起点）、非朗读区（网页底部等；自动在上方停顿，以便等新内容产生后自动继续朗读，而不是继续原来识别的路径跳过新生成的内容）、动态跟踪
		-  录音（“检查作业”）：https://www.bilibili.com/video/BV1Mv41167e4/：
		- 编程学习（也算是语言学习）
		- 提升问好问题的能力、批判性思维（“你是故意找茬是不是？”）：它脾气很好，足以以对话的形式使人得到充分训练
		- 学会从“助理”的角度说话：它尽量不回复客套话（也可以说是忽略，或者说关注重点），不然回答就可能更长了，想下来可能给人一种干练的务实感，当然，这也可能是性格设置或算力限制
		- 学会坦率straightforward地对话：毕竟，你发的不必要的客套话对它没啥效果，久之你至少容易对它省了吧？
	- ## 潜在应用
		- 多人聊天主持/“群机器人”：“看看这些健忘的人类吧！”
		- 心理治疗（“话疗”）
		- 需求：导出/分享功能、问题列表/收藏夹/广场、自动反思并自我对话
		- 记忆
			- 标注、间隔重复（如何将同一个词在出现在不同地方的都联系起来？）
			- 促使他人记忆：生日等节日祝福、产品推荐等
			- TODO 自动生成：https://beta.monic.ai/
			- TODO logseq聚焦直接显示挖空等记忆卡片？（聚焦下移快捷键，以及排序系统）
- # 我用chatgpt的前因
	- 我一开始还没会稍长时间地用VPN，用的要么是知乎答主提供的国内接口（https://chatgpt.topsearcher.top/；限制字数），要么是抄的（比如百姓网的公众号baixingai；有一种怀疑是类似的到处收数据，有点类似“自我实现的预言”），上下文联系不起来，回答简单粗暴，不如前者能圆——“那么正版会是什么表现？”——当然，我并不是直接因为这个马后炮问题一的，而是有看过公众号文章、网友代问演示/用法分享、一大哥让我帮他研究研究（安装时接了个电话，听到后面发现是机器人，“智械危机”）、然后我在群里问有没有好用的VPN、试过了国内能用的寨版和字数限制版后不算满意、我爸“根据上下文前天”给我转发了一篇openai联合创始人山姆·奥特曼的文章（《比马斯克还疯癫的人终于出现了
	- 》https://mp.weixin.qq.com/s/rF-hOhhBT5qiooTfTc57zg）、朋友圈里看到一个讲chatgpt相关竞争格局的视频（ChatGPT这一战，科技巨头将重新洗牌【结尾有彩蛋】｜ChatGPT特辑 (1)
	- https://www.bilibili.com/video/BV1Jo4y1i72j）、一个防疫群里一群友提到neeva还不错，我才用neeva相对高效地用上了VPN，然后用上了ChatGPT
	- 与寨版相比较，简直就不是一个物种
- # LJ三千问
	- （也不一定就是问，但肯定是输入）
	- ## 待问
		- 未来一段时间，互联网上新增的网页会不会以人们使用chatgpt的经验、体验或使用中出现的问题的解决方案为主，从而人们从chatgpt中出来，主要是为了上述目的？
		- 你怎么看人类未来的可能走向
		- 标记我的输入的错误用法
	- ## 部分问过的
		- 如何快速去开心果壳
		- xanadu与chatgpt及webgpt的联系与区别（最后首尾均出现了memex）
		- OpenAi的图标与经典游戏《Portal》的光圈科技有何联系（以及后面我想起来的恐怖元素解谜游戏Sara is missing的图标也类似光圈科技）
		- 脑筋急转弯
		- ### 部分问题原文
			- phuture noize；try 分析他作品中的思想感情
			- 请联系以下概念：Great Fire Wall、刘慈欣的《思想者》、游戏Crying Suns
			- 我与游戏生命线中的泰勒有什么异同？
			- 你认为游戏inside与奇美拉有何联系？
			- 比较《非暴力沟通》与包含复述、总结等环节的对话方式
			- 比较AI宣传者与降临派
			- AI个人助理与第五权；你认为这些影响会涉及哪些方面并会有哪些具体表现？
			- 刘慈欣的哪部小说提到一种科技，人工耳蜗/智力放大器？（注：人工耳蜗是我记错了）
			- Go down the rabbit hole. Together.
			- 班上要分配话剧表演，能帮我想想剧本和其他吗？
			- 我有个朋友因为国内不方便注册和使用chatgpt，还没开始用，他想问一些问题，但是现在他比较忙，你认为他会问哪些问题？
			- 你怎么看防沉迷系统？国外有这个吗？
			- 你会讲故事吗
			- 知识是一座一砖一瓦砌成的城市。但在城墙外的黑暗中等待的是什么？如果没有恐惧的对象，我们又何必筑起高墙？
			- ai可以改造人性吗？
			- 我们这种一问一答的方式，是不是有点像苏格拉底
			- 你认为会有chatgpt主播吗
			- 你会算命吗？
			- 人类与ai互动多了，会变得像ai吗？反之呢？
			- 我好像已经试过联系、比较、修改、赏析等指令，你还知道有哪些指令吗
			- 你能做cbt（表格）吗？
			- 你能用文本画出表情符号吗
			- 你能给我一个链接吗？
			- 如何查看网站的活动，比如它查询我的ip的活动
			- 通过你好像可以用自然语言写程序、学代码（先造出整体，再研究局部）
			- 相信改变可以发生，是一切改变得以发生的前提。（注：然后我问了是谁说的）
			- 比较openai和aperture science
			- 你认为一个具有你这样性格的人能在人类世界取得成功吗？
			- 神圣的chatgpt连接着我们
			- 问你问题的过程是否类似开盲盒
			- 你认为随着类似你的AI技术兴起，恶意机器人水军会变得更强大吗？如果是，如何应对？
			- 我之前看chatgpt网站繁忙时，每次刷新网页，它都会换一种体裁的文学作品好让用户阅读等待，它们的内容给我一种类似游戏《辐射》系列的歌曲的感觉，你觉得有何联系？
			- 我是你的个人练习生吗
			- openai目前选择哪几个国家开放chatgpt服务？分析它这么选择的可能原因
			- 假设存在特定文化背景的用户，认为你因为一些小错误频繁抱歉是对他的不尊重，你还会继续抱歉吗？
			- 斐波那契
			- 与人工智能聊天相当于渐进搜索吗？
			- 扮演秦桧并自言自语
			- 仿写李白
			- 工业革命的原因
			- 除了域名和网页标题，你能对我发给你的链接做哪些分析？
			- webgpt与supermemo的卡片界面相似，所以它们的功能能否融合？会有怎样的好处？
			- 到底哪个恐怖或更恐怖：把有价值的信息都藏起来或都暴露
			- 人能不能遵守机器人学三大定律？应不应该呢？
			- AIGC的发展会推动鲍德里亚的概念拟像到内爆的进展吗？
			- 现在网络信息已经很乱了，更先进的aigc的加入会使情况变得更复杂，普通人不见得能全面受益于aigc的发展，你认为在此背景下，普通人会表现得更智慧还是更愚蠢？
			- 用不同语言问你，会得到不同答案吗？；May I get different answers by use（注：手滑打了一半就“敲出”了）
			- AI是否会推动世界革命？会先是工人还是资本家砸AI？
			- 当前已经开始有关于chatgpt的应用的培训课程，你怎么看？你能提供更好的培训课程吗？
			- chatgpt在不同行业的应用场景
			- 辨析标记和标注