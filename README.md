<!-- GreaseFork -->
<!-- <script charset="Shift_JIS" src="http://chabudai.sakura.ne.jp/blogparts/honehoneclock/honehone_clock_wh.js"></script> 时钟代码 -->
<!-- <h2>脚本区分</h2>
<ul><li>二合一(自动搜火力+自动发弹幕)脚本功能已经和原安全脚本功能合体了，旧的二合一脚本功能不再更新了，建议大家下载本页面的合体脚本即可，如仍需要旧的清爽版二和一脚本的朋友，请<a style="color:red;text-decoration:none;font-weight:bold;" href="https://greasyfork.org/zh-CN/scripts/390551" target="_blank">这里下载</a>；</li></ul>
<hr> -->
<h2><a style=" color:red; text-decoration:none; background-color:yellow">必知内容</a></h2>
<p><strong>本脚所包含的所有功能：自动搜索火力全开/福利社房间+随机发云端或AI弹幕(已整合二合一功能)+极速签到手速王+幻神弹幕特效(本机)+不绑定手机发弹幕+鱼吧收藏列表自动签到+车队页面签到领加油卡+一键打卡所有粉丝房间+鱼粮自动领取并抽奖+一键清空背包+房间自动签到(分为极速签到和普通签到)+房间在线人数+主播今日收益+房间今日弹幕数量+统计跳转次数+主播信用值+主播开播时间+自定义私有弹幕+跳转前自动取关(粉丝牌和特殊关注房间不取关)+新页面是否自动播放(记忆上次操作)+新页面是否开滚屏弹幕(记忆上次操作)+自动答谢礼物与感谢房管弹幕(隐藏功能)+自定义跳转次数(隐藏功能)+自定义结束等待时间(隐藏功能)+自定义跳转延迟(隐藏功能)+是否与AI弹幕混用(隐藏功能)+关闭幻神特效(隐藏功能)+匿名使用脚本(隐藏功能)</strong></p>
<ol>
    <li>如果是为了使用幻神弹幕特效和自动签到等功能，那将复选框点到⛔-火力停止状态,等待组件初始化就好了，其他的都不理会，按以往您斗鱼习惯操作就好。以下内容是抢丸子红包功能的详细介绍，<strong style="color: red">懒人只看看图片就好！</strong></li>
    <li>如果是为了抢丸子或红包，强力推荐大家用自动模式的二合一功能(火力搜寻+自动弹幕)，控制开关在菜单鱼吧的右侧，开启二合一开关+停留💥弹幕轰炸，会自动搜索火力全开+自动发送弹幕，默认每天跳转超过100次后，停止自动跳转；</li>
    <li>如果感觉跳转100次(适用账号低于Lv.10使用)鱼丸红包收益满足不了你，而且您的等级比较高(大于Lv.20)，那么可以<a href="https://popzoo.github.io/zoo/" style="text-decoration: none;" target="_blank"><strong style="color: red;">点击这里</strong></a>开启隐藏功能，自定义每日最大自动跳转次数，自定义每次火力全开停止后的等候时间等参数，满足您更长时间的火力需求；</li>
    <li>自动搜索火力全开房间的筛选条件包含：
        <ul><li>房间需要有火力全开/福利社抽奖活动才符合条件；</li>
            <li>房间人数大于4000的被过滤掉，中奖难度太高；</li>
            <li>奖品内容要为鱼丸、红包或现金，鱼丸份数>=2，数量>100；</li>
            <li>红包或现金过滤小于1元的红包；</li>
            <li>粉丝专属活动自动判断是否满足参与条件；</li>
            <li>过滤掉被房间禁言的直播间；</li>
        </ul>
    </li>
</ol>
<hr>
<h2>脚本说明</h2>
    <p><img src="https://rawcdn.githack.com/wolf-scream/FirePowerSeek/927b43f2c9229b3887416be52d9768c5c443f32b/pics/mainInstruction.jpg" width="100%"></p>
    <p>本脚本的使用方法特别简单，因为可供操作的区域都集中在房间标题附近，如上图所示；</p>
<ul>
</ul><table><tr>
    <td><img src = "https://rawcdn.githack.com/wolf-scream/FirePowerSeek/e53313d3faecc7aec41a53d6e1bae11ed8459352/pics/fnRadio.png" width="100%" ></td><td>&nbsp;&nbsp;</td>
    <td><img src = "https://rawcdn.githack.com/wolf-scream/FirePowerSeek/e53313d3faecc7aec41a53d6e1bae11ed8459352/pics/switchTip.png" width="100%" ></td>
</tr><tr>
    <td><img src = "https://rawcdn.githack.com/wolf-scream/FirePowerSeek/e53313d3faecc7aec41a53d6e1bae11ed8459352/pics/fnPeople.png" width="100%" ></td><td>&nbsp;&nbsp;</td>
    <td><img src = "https://rawcdn.githack.com/wolf-scream/FirePowerSeek/e53313d3faecc7aec41a53d6e1bae11ed8459352/pics/fnJump.png" width="100%" ></td>
</tr><tr>
    <td><img src="https://rawcdn.githack.com/wolf-scream/FirePowerSeek/e53313d3faecc7aec41a53d6e1bae11ed8459352/pics/redIncome.png" width="100%"></td><td>&nbsp;&nbsp;</td>
    <td><img src="https://rawcdn.githack.com/wolf-scream/FirePowerSeek/f5970bc8f236fbcb8c30a739e49f5b09e6c46166/pics/ballBenefit.png" width="100%"></td>
</tr><tr>
    <td><img src="https://rawcdn.githack.com/wolf-scream/FirePowerSeek/e53313d3faecc7aec41a53d6e1bae11ed8459352/pics/sendBack.png" width="100%"></td><td>&nbsp;&nbsp;</td>
    <td><img src="https://rawcdn.githack.com/wolf-scream/FirePowerSeek/e53313d3faecc7aec41a53d6e1bae11ed8459352/pics/huluStat.png" width="100%"></td>
</tr><tr>
    <td><img src="https://rawcdn.githack.com/wolf-scream/FirePowerSeek/e53313d3faecc7aec41a53d6e1bae11ed8459352/pics/donateBar.png" width="100%"></td><td>&nbsp;&nbsp;</td>
    <td><img src="https://rawcdn.githack.com/wolf-scream/FirePowerSeek/e53313d3faecc7aec41a53d6e1bae11ed8459352/pics/fishFood.png" width="100%"></td>    
</tr></table><ul>
   <li>各区域详细说明见上面小图，脚本在直播间执行后鼠标悬浮在对应的功能按钮上有相同的浮窗说明提示；</li></ul>
<ul>
<li>被斗鱼屏蔽发言的场景，一般满足频繁房间跳转+频繁发弹幕（二者兼备才行）则搜索跳转超过一定次数后就很有可能被斗鱼屏蔽弹幕（跳转上限与等级的对应规律请查看脚本的隐藏教程）。针对这个限制我们可以想办法规避，一是本脚本所做的，自动搜索限制每天跳转次数，而且自动搜索和自动发弹幕二者功能可以相互分离，可以设置跳转延迟等，这样很大程度上避免了被关小黑屋的可能性；二是针对自动跳转的延迟/等待时间间隔，每个新房间都停留个一两分钟以上再跳转，这样就不属于短时间频繁房间跳转，但坏处显而易见，太浪费时间了，所以这个方法不推荐大家使用；</li>    
<li>本脚本完全由原生的JS编写，用户可以先不装tampermokey或violentMonkey，直接复制需要的代码片段在控制台执行试用下效果，但有会有部分功能缺失,而且每次页面跳转都必须重新粘贴执行，完整使用建议去google商店(自备梯子)或<strong style="color: red"><a href="https://www.crx4chrome.com/">Crx4Chrome</a></strong>(国内可用)搜索安装tampermokey，使用完全版；</li>
<li>非油猴控制台的使用方式：
  <ul><li>打开房间，等待网页加载完毕</li>
    <li>拷贝代码，在浏览器（推荐chrome）中按F12打开控制台</li>
    <li>在console中粘贴代码，按回车执行脚本</li>
    <li>再按F12关闭控制台等待脚本加载</li>
  </ul></li>
<li>增加斗鱼部分广告的去除功能，主要是被斗鱼的广告恶心到了，而且遮挡了本大神的按钮模块功能，所以干掉了三个斗鱼没有的垃圾广告图标(点图标进入都是网页游戏的小图标)，但还最大程度上保留斗鱼的原味风格；</li></ul><hr>
<h2>新的功能</h2>
<ol>    
    <li>新增滚屏弹幕和自动播放开关记忆功能，如果用户关闭了视频播放，或关闭的滚屏弹幕，那么会记录在本地，下次刷新页面或跳转其他直播间会自动还原为记忆的状态，满足大家不同场景的需求撒~；</li>
   <li>新增极速签到功能，帮助大家抢签到手气王榜首，本方法是直接调用签到API接口，延迟为ms级别。在未开播房间循环检测到主播开播后极速签到，使用此功能记住一定要将主播加入特别关注，否则无法签到，由于此功能对服务器压力较大，建议最好在主播开播前几分钟使用，签到后会自动关闭。签到成功会自动弹窗提示；在此十分感谢斗鱼资深水友<strong style="color: red">PuddingPanda</strong>对本功能协同测试开发做出的突出贡献；</li>
    <table><tr>
        <td><img src="https://rawcdn.githack.com/wolf-scream/FirePowerSeek/636280339bfea5cde531b530aa797c3c1861a7b2/pics/fastAssign1.png" width="100%"></td><td>&nbsp;&nbsp;</td>
        <td><img src="https://rawcdn.githack.com/wolf-scream/FirePowerSeek/636280339bfea5cde531b530aa797c3c1861a7b2/pics/fastAssign2.png" width="100%"></td>
   </tr></table>   
    <li>新增<a href="https://popzoo.github.io/barrage" style=" color:red; text-decoration:none;font-weight:bold;" target="_blank">云弹幕词库</a>功能，大家可以从这里查看云弹幕的一些常用普通弹幕和部分精选弹幕，脚本自动从云端抽取符合房间类别的热门弹幕，不用再为发啥子弹幕而愁了，就是这么牛，奏是这么的方便，奏是这么滴憨憨~；</li>
    <table>
        <tr><td><a href="https://popzoo.github.io/barrage" target="_blank"><img src="https://coding.net/u/lvlanxing/p/popzoo/git/raw/master/pics/clouldBarrage.gif" width="100%"></a></td></tr>
   </table>    
    <li>幻神弹幕特效实现，含泪呀，拖了二个多月，别人家都做出来，博主一直懒得搞，这回好了，直接抓特效就好了，以后人人都是幻神了，有牌面，有气场，有神范，有木有……</li>
    <li>新增鱼吧自动签到，自动签到鱼吧收藏列表的所有鱼吧，没有签到数量的上限，只要是你收藏的鱼吧就都签到，每天执行一次，使用方法在任意直播间（非专题直播间）下拉加载鱼吧信息列表，后台静默签到(控制台日志显示签到信息)，若进入鱼吧页面签到，则有弹窗显示签到成功提示；</li>
    <li>新增车队一键签到，每天首次打开斗鱼页面，自动跳转车队页面签到，脚本自动签到并领取车队加油卡，领取完毕后推送到薅羊毛首页；</li>
    <table><tr>
        <td><img src="https://rawcdn.githack.com/wolf-scream/FirePowerSeek/a0e12c719c52b658eec8bf0c062446e283cad579/pics/yubaAssign.png" width="100%"></td><td>&nbsp;&nbsp;</td>
        <td><img src="https://rawcdn.githack.com/wolf-scream/FirePowerSeek/a0e12c719c52b658eec8bf0c062446e283cad579/pics/carAssign.png" width="100%"></td>
   </tr></table>    
    <li>重磅推出——人工智能AI聊天机器人-<strong style="color: red">小思</strong>，拥有亿级别的实体属性关系，机器人具备的功能有：中文分词、词性标注、命名实体识别、关键词提取、文本摘要、新词发现、情感分析等。已经过滤比较弱智的回答，在此特别感谢小思AI之父——<strong style="color: red">思裕大佬</strong>的大力相助与热情解惑；</li>
    <table><tr>
        <td><a href="https://www.ownthink.com/"><img src="https://rawcdn.githack.com/wolf-scream/FirePowerSeek/68bc788acec5c360bdd9a0bed2e39a66a185012c/pics/xiaosi.jpg" width="65%"></a></td><td>&nbsp;&nbsp;</td>
   </tr></table>    
    <li>新增一键打卡所有粉丝牌房间送荧光棒续牌子功能，每个有牌子的房间自动赠送一个荧光棒，防止亲密度下降,点击按钮在界面鱼丸的左侧，感谢斗鱼满牌水友<strong style="color: red">伯毅</strong>对此功能测试的大力帮助；</li>
    <li>新增跳转或刷新页面自动领取鱼粮，也可一键领取所有鱼粮功能，按键在鱼丸数量的左侧，并自动参与小礼物抽奖一次，领取成功后会自动弹窗提示框！这个功能是由斗鱼老牌水友<strong style="color: red">坑气十足</strong>提出的刚需；</li>
    <li>新增自定义私有弹幕的功能，用户可以在云弹幕页面去上传自己的专属弹幕，批量定制符合自己胃口的弹幕，再也不用烂大街的公用弹幕了，再也不使用AI沙雕萌新百科全书的弹幕了，奏事这样滴憨憨+牛批，<strong style="color: red"><a href="https://popzoo.github.io/barrage/" target="_blank">传送门</a></strong>；</li>
    <li>新增一键清空背包小礼物功能，可以点击清包后，可以自动将背包中的小礼物一股脑儿赠送给当前直播间，再也不用一个个点到手抽筋了，奏是一个字——“酷”；</li>    
</ol>
<hr>
<h2>常见问题</h2>
<ul>
    <li>问题No.1 当弹幕速度过快的时候(一般发送弹幕间隔时间小于2s)或网速延迟过高，会出现幻神弹幕特效出现在屏幕左侧移动缓慢的情况，这是个潜在的bug，还在探索解决中，但不影响脚本其他功能的使用;</li>
    <li>问题No.2 浏览器经常崩溃，这种情况是最为常见的，基本上是由于浏览器内存不足造成的，即用户打开的页面太多了，所以建议您用多个不同浏览器满足多个页面打开的需求，不建议用一个浏览器打开过多的页面，只要是chrome内核的浏览器就可以，如360、搜狗，不过非chrome内核浏览器，如FireFox没有适配;</li>
    <table><tr>
    <td><img src="https://rawcdn.githack.com/wolf-scream/FirePowerSeek/9fdabab520a3fd9143a015872a00208e7908ef23/pics/updateScript.jpg" width="100%"></td><td>&nbsp;&nbsp;</td>
    <td><a href="https://github.com/wolf-scream/FirePowerSeek/issues/2" target="_blank"><img src="https://rawcdn.githack.com/wolf-scream/FirePowerSeek/9fdabab520a3fd9143a015872a00208e7908ef23/pics/banSpeak.png" width="100%"></a></td>
    </tr></table>
    <li>问题No.3 如何快速更新脚本？ 由于tamperMonkey自带的脚本更新功能很low，所以建议大家抽空手动更新下脚本，方法特别简单，如下图，方法一，适用所有脚本更细，先勾选所有，然后选择触发一次更新，再点击开始即可；方法二适合单个脚本更新，即直接点击“最后更新”栏下对应脚本的时间,前提是此脚本在greaseFork发布过(即那个叉子图标)；当然还有方法三，直接来greaseFork重新安装脚本便可；</li>
    <li>问题No.4 被关‘小黑屋’。屏幕滚屏弹幕区和聊天弹幕区都不显示自己发送的弹幕，尝试用手机app端发送弹幕也没显示，这时可以用浏览器F12找console区域，然后发送一条弹幕出现右下图的报错，说明您已经触发了斗鱼的风控系统被自动屏蔽发言了，若出现这种情况，如果您是首次或您开了贵族，可以向客服反映，若是多次还请移步博主的github,参考如何解封账号异常状态，里面有详细的封禁场景和解封办法，<strong style="color: red;"><a style=";text-decoration:none;" href="https://github.com/wolf-scream/FirePowerSeek/issues/2" target="_blank">传送门</a></strong>；</li>
    <table><tr>
    <td><img src="https://rawcdn.githack.com/wolf-scream/FirePowerSeek/567152d5a660e937e786743748affd65fa537296/pics/thankAdmin.png" width="100%"></td><td>&nbsp;&nbsp;</td>
    <td><img src="https://rawcdn.githack.com/wolf-scream/FirePowerSeek/567152d5a660e937e786743748affd65fa537296/pics/thankDonator.png" width="100%"></td>
    </tr></table>
    <li>问题No.5 如何开启隐藏功能？ 目前隐藏功能包含的内容有：自动答谢礼物和房管弹幕+自定义跳转次数+关闭幻神特效+是否与AI弹幕混用+用户匿名使用+自定义延迟跳转时间+自定义结束等待时间。隐藏功能<a href="https://popzoo.github.io/zoo/" style="text-decoration: none;"><strong style="color: red;">传送门</strong></a>，来获取隐藏功能开启密码和使用方法，在此感谢斗鱼铁杆水友<strong>溜小溜丶</strong>对礼物答谢功能开发的大力协助；</li>
    <table><tr>
    <td><img src="https://rawcdn.githack.com/wolf-scream/FirePowerSeek/0f31a5cc6cd4de53fb0f306c25d0f80a3e88b013/pics/noemoji.png" width="100%"></td><td>&nbsp;&nbsp;</td>
    <td><img src="https://rawcdn.githack.com/wolf-scream/FirePowerSeek/0f31a5cc6cd4de53fb0f306c25d0f80a3e88b013/pics/containemoji.png" width="100%"></td>
    </tr></table>
    <li>问题No.6 为何我安装脚本后显示的图片为乱码或框框？ 因为作者大大本着好维护的原则直接采用的emoji原生会文字，目前iphone,android,win 10都已原生支持emoji小图标了，但是win7及以下用户可能不支持，见左上图，需要下载文字补丁包，虽然安装上也挺丑的，见右上图，win7的emoji补丁包<strong style="color: red;"><a href="https://support.microsoft.com/zh-cn/help/2729094/an-update-for-the-segoe-ui-symbol-font-in-windows-7-and-in-windows-ser" target="_blank">传送门</a></strong>；</li>
    <li>问题No.7 使用本脚本最好放不要隐藏tab标签页面(最好保持在前台)，否则可能页面元素无法加载，从而导致脚本无法运行，大家可以把需要执行脚本的页面单独从浏览器里拖拽出来，然后放到后面即可，但请别最小化窗口。如果感觉碍眼，可以用win10的多窗口功能，ctrl+win+D,创建一个新的窗口，然后再用ctrl+win+左右箭头，来切换窗口，非常方便，可以添加很多窗口来执行多账号多开页面需求，如果需要chrome浏览器多开账号功能的，请自行百度chorme多开账号功能；</li>
    <table><tr>
    <td><img src="https://rawcdn.githack.com/wolf-scream/FirePowerSeek/43d8b2f4a17b3583f2d26612841b7c2aca486f1f/pics/manyWindows.jpg" width="100%"></td>
    </tr></table>
</ul>
<hr>    
<h2><a href="https://popzoo.github.io/pop/giftshow.html" style=" color:red; text-decoration:none" target="_blank" >礼物车队</a></h2>
<ul>
   <li>开设了查看<strong style="color: red;"><a style="text-decoration:none;" href="https://popzoo.github.io/pop/giftshow.html" target="_blank">斗鱼礼物大全</a></strong>的图谱展示功能（包含动态礼物和静态礼物），大家可以涨涨见识撒，土豪的可以找找自己喜欢的礼物模板记住id，然后去斗鱼定制私人火箭，相当有牌面！用浏览器的搜索功能ctrl+F，能搜到自己熟悉的礼物图片，来个团团的“母猪冲撞”有木有撒；</li>
   <li>新设了<strong style="color: red;"><a style="text-decoration:none;" href="https://popzoo.github.io/pop/giftshow.html" target="_blank">斗鱼全部车队</a></strong>条件筛选功能，由于斗鱼官方车队搜索反穷人设计理念，以至于大家找个限制门槛低点的车队要鼠标来回点个几百次才能找到，只好自动动手丰衣足食，以方便大家进车队周转丸子或抢红包（注：现在抢丸子机器人太多，周转先试水哦）。这里涵盖的斗鱼的已建立的全部车队，包括车队标致，车队logo图片，车队号码，车队名称。车队筛选条件包括加入车队无限制(白嫖客的福音)、等级限制、贵族限制和粉丝限制；</li>
</ul><table><tr>
        <td><a href="https://popzoo.github.io/pop/giftshow.html" target="_blank"><img src="https://rawcdn.githack.com/popzoo/pop/1a207d2854edaf1a434a8dfe1402b936d4ce6239/images/giftShow.jpg" width="100%"></a></td><td>&nbsp;&nbsp;</td>
        <td><a href="https://popzoo.github.io/pop/motorcade.html" target="_blank"><img src="https://rawcdn.githack.com/popzoo/pop/1a207d2854edaf1a434a8dfe1402b936d4ce6239/images/motorcadeShow.jpg" width="100%"></a></td>
   </tr></table><hr>    
<h2><a style=" color:red; text-decoration:none; background-color:yellow">作者声明</a></h2>
<ol>
   <li><strong>本脚本仅供编程爱好者参考、学习和交流使用，请勿做商业用途或大规模恶意滥用，如有侵犯了您的权益，请立马联系作者进行处理；本脚本的二次分发代码需经作者同意，谢谢理解；</strong></li>
   <li><strong>关于本网页推荐的第三方网站的链接，比如透过本网页以及所著工具而得到的第三方链接及得到的资讯、产品、工具及服务等产生的纠纷，算到本站头上的概不认账撒(非要赖账也行，前提你是妹子，还要有能力养我的那种哈~)；</strong></li>
   <li><strong>本脚本历史版本的在线人数参考qianjiachun大佬的API接口(目前已经阵亡)，视频画质调整(功能已去除，如需要请下载其他脚本)参考wah0713大神的方法，切换账号的鱼吧签到Bug问题由胖头鱼大佬修复(在用)，在此竭诚拜谢三位大佬指引。除了这三处的参考，其他均为作者原创；</strong></li>
</ol>
<hr>
<h2><a style="color:red; text-decoration:none; background-color:yellow">用户隐私</a></h2>
<p><strong>本脚本从不恶意收集、窥探、分发、买卖（或其他不法商业行为）用户的个人信息或跑挖矿程序等，本着公开透明的原则，懂代码的大佬可以直接看源码注释，每个函数都有明确的功能说明；</strong></p>
<p><strong>对于小白用户我们也相当的友好，这里公开透明的例举了脚本使用或收集大家的哪些个人信息，下面是详细说明，如果您使用此脚本，则默认您同意下面的条款(不同意且会改代码的大佬，可以把此话当放屁~)；</strong></p>
<ul>
   <li>使用并收集了用户的昵称信息(收集昵称默认采用半匿名方式，如“大王***”，隐藏教程有全匿名的使用方法)，主要用途是区别自己已发弹幕的幻神图标去重，判断火力全开中奖列表是否含有自己，礼物致谢去重感谢自己的礼物，区分不同用户的每日跳转次数等；</li>
   <li>使用并收集了用户的UID信息(一串数字标识)，主要是通过用户的uid区别用户自定义的配置参数（隐藏功能可配置），以及通过uid获取用户的昵称；</li>
   <li>收集了火力/抽奖房间节点信息，方便寻找匹配的火力房间，并统计直播间的火力频率，然后再回馈大家，功能已经开发完毕，薅羊毛导航首页可进，快去尝鲜吧，少年！</li>
   <li>收集了用户的每日跳转次数和中奖增益，统计用户每日的跳转量，探索斗鱼对跳转规则的限制规律，希望能找到一种每天超量跳转(N次)还不被关小黑屋的方法，目前已有一定规律，想详细了解请参考隐藏教程；</li>
<!--    <li>使用了用户的手机绑定状态信息(非手机号码)，主要用途是如果用户没有绑定手机号，则实现非绑定手机发弹幕的功能(但不参与鱼粮领取)，如果绑定手机则直接参与鱼粮自动领取；</li>
   <li>使用了用户特别关注列表，用于查看主播是否开播，便于极速签到抢手速王；使用了用户的粉丝牌列表，用于一键打卡赠送荧光棒；使用前两者数据，用于排除自动取关房间；</li>
   <li>使用了用户的cookie中的acf_ccn，此cookie的用途是极速签到抢签到手速王需要发送的参数，火力全开房间跳转也用的此cookie作为参数向服务器发送；</li>
   <li>使用了用户的cookie中的post-csrfToken的值，此cookie的用途是用于车队自动签到，领取车队加油卡所需要发送的参数；</li> -->
   <li>使用了站长统计，主要统计云弹幕接口的访问频次（日均约10000+次），目前已经放弃了采用Github的接口(因为在特殊时期不稳定)，通过使用国外CDN加速+国内云盘存储加速访问，满足大家的对速度和稳定需求，主要靠捐助维持，希望大佬们多多抬手，在此小编大拜谢恩~；</li>
   <li>对着乔碧罗殿下发誓，真的木有了……；</li>
</ul>
<p><strong>本着职业道德和扫黑除恶的契约精神，本脚本从不恶意收集用户的敏感信息，诸如鱼翅数目、绑定手机号、绑定银行卡、账号登陆token等个人隐私，如一经发现作者侵犯了您的这些权益，请立马举报作者！或派遣一大波儿正义的美少女战士，把作者大大埋没在波涛胸涌的浪潮中吧😍！</strong></p>
<hr>
<h2>特别推荐</h2>
<ul>
    <li><strong style="color: red;"><a style="text-decoration:none;" href="https://greasyfork.org/zh-CN/scripts/380546">Greasy丶H2P</a></strong>群头的斗鱼房间清爽脚本(可自定义清爽模式，去除广告的或无用标题模块)配合本脚本的抢丸子功能，可以无缝清爽抢丸子，优化页面风格，提高舒适度；</li>
    <li><strong style="color: red;"><a style="text-decoration:none;" href ="https://www.obrua.com" target="_blank">胖头鱼的机器人</a></strong>，斗鱼机器人界的元老级大神，QQ群(158267839)很活跃，群内高人辈出，开发工具是谷歌浏览器插件，主要功能是自动抢宝箱和鱼吧自动签到灌水，一直在精心维护，这里特别推荐下，也感谢胖头鱼大佬对本脚本鱼吧签到bug的修复，做出的杰出贡献；</li>    
    <li><strong style="color: red;"><a style="text-decoration:none;" href ="https://github.com/nws0507/DYRoomCheckIn" target="_blank">小丑签到工具</a></strong>，斗鱼批量签到关注列表的phyton脚本工具，主要功能是自动批量签到关注列表的房间和抢占90%房间的签到手速王，这里特别推荐下，此外小丑大神的webSocket连接斗鱼弹幕系统进行收发弹幕功能脚本也已开发完毕，有需求的朋友可以github参考或加入Q群与之交流探讨；</li>    
    <li><strong style="color: red;"><a style="text-decoration:none;" href ="http://www.obsapp.com/apps/danmupro/" target="_blank">小葫芦弹幕助手</a></strong>，直播弹幕插件的开山大神，与许多直播平台有正规的合作，而且平台统计对小直播间也很友好(这点比播酱好)，想使用安全可靠的弹幕服务（一堆功能）的小伙伴，快去尝鲜吧；</li>
    <li><strong style="color: red;"><a style="text-decoration:none;" href="https://bojianger.com/" target="_blank">播酱</a></strong>这个斗鱼数据统计的平台是Github的liutianyu老兄向我推荐的，可以看到斗鱼特别详细的统计数据，包括真实活跃观众和历史所有的弹幕记录等，对用户数据抓取的很翔实，对数据感兴趣的童鞋可以去看看，每天幻神大大宠幸谁的直播间，什么时间发的啥子弹幕，送了啥子礼物都能一目了然，话说没有隐私了，牛批的一塌糊涂；</li>
    <li><strong style="color: red;"><a style="text-decoration:none;" href = "https://github.com/youbao88/douyuquiz">自动记录竞猜数据Python脚本</a></strong>是博主在Github看到的，已验证可用，包括竞猜封盘的赔率，竞猜标题，输赢，鱼丸数量等，数据保存到本地并可以浏览器列表形式展示数据。这个功能还挺棒的，喜欢梭哈的朋友可以试试，需要安装python环境；</li>
    <li>欢迎大家使用、研究和引用本脚本，但在引用脚本的时候，希望您能标注出处，这也是对作者付出的认可与尊重，也是对您自我修养的体现，如意见欢迎给博主<a href="mailto:lvlanxing@gmail.com?subject=邮件主题&body=邮件内容" rel="nofollow" style="color:red;text-decoration:none;font-weight:bold;">发送邮件</a>，或在博主的<strong style="color: red;"><a style="text-decoration:none;" href="https://github.com/wolf-scream/FirePowerSeek">GitHub</a></strong>上留言，或加入我们薅羊毛大军的QQ交流群：650178547 发留言；</li>
</ul>
