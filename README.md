不要fork! 不然下次GitHub还会继续封这个仓库
特别声明:
本仓库发布的Script项目中涉及的任何解锁和解密分析脚本，仅用于测试和学习研究，禁止用于商业用途，不能保证其合法性，准确性，完整性和有效性，请根据情况自行判断.

本项目内所有资源文件，禁止任何公众号、自媒体进行任何形式的转载、发布。

lxk0301对任何脚本问题概不负责，包括但不限于由任何脚本错误导致的任何损失或损害.

间接使用脚本的任何用户，包括但不限于建立VPS或在某些行为违反国家/地区法律或相关法规的情况下进行传播, lxk0301 对于由此引起的任何隐私泄漏或其他后果概不负责.

请勿将Script项目的任何内容用于商业或非法目的，否则后果自负.

如果任何单位或个人认为该项目的脚本可能涉嫌侵犯其权利，则应及时通知并提供身份证明，所有权证明，我们将在收到认证文件后删除相关脚本.

任何以任何方式查看此项目的人或直接或间接使用该Script项目的任何脚本的使用者都应仔细阅读此声明。lxk0301 保留随时更改或补充此免责声明的权利。一旦使用并复制了任何相关脚本或Script项目的规则，则视为您已接受此免责声明.

您必须在下载后的24小时内从计算机或手机中完全删除以上内容.

您使用或者复制了本仓库且本人制作的任何脚本，则视为已接受此声明，请仔细阅读

Script脚本列表
京东水果(jd_fruit.js)
东东萌宠(jd_pet.js)
种豆得豆(jd_plantBean.js)
天天加速(jd_speed.js)
摇钱树(jd_moneyTree.js)
宠汪汪(jd_joy.js)
宠汪汪偷好友狗粮与积分(jd_joy_steal.js)
宠汪汪单独喂食(jd_joy_feedPets.js)
宠汪汪兑换奖品(jd_joy_reward.js)
宠汪汪强制为好友助力(刷好友)(jd_joy_help.js)
宠汪汪赛跑助力(jd_joy_run.js)
宠汪汪聚宝盆辅助脚本(jd_petTreasureBox.js)
取关京东店铺和商品(jd_unsubscribe.js)
东东超市(jd_superMarket.js)
东东超市兑换奖品(jd_blueCoin.js)
进店领豆(jd_shop.js)
摇京豆(jd_club_lottery.js)
全名开红包(jd_redPacket.js)
京东多合一签到(jd_bean_sign.js) 【可N个京东账号，Node.js专用，核心脚本是JD_DailyBonus.js，iOS软件用户请使用NobyDa的 JD_DailyBonus.js 】
京豆变动通知(jd_bean_change.js)
京喜工厂(jd_dreamFactory.js)
东东小窝(jd_small_home.js)
东东工厂(jd_jdfactory.js)
点点券(jd_necklace.js)
十元街(jd_syj.js)
京东金融-天天提鹅(jd_daily_egg.js)
京东金融-养猪猪(jd_pigPet.js)
以及其他一部分在特定时间可用的薅京豆脚本：手机狂欢城 、星推官 、双十一活动领金币 、热8超级盲盒
Webhook触发Action(webhook.js)
搬运脚本

【@yangtingxiao】京东抽奖机(jd_lotteryMachine.js)
【@yangtingxiao】京东排行榜(jd_rankingList.js)
脚本兼容: QuantumultX, Surge, Loon, 小火箭, JSBox, Node.js

TODO

 东东工厂相互助力
 京喜工厂相互助力
食用方法
方法一：本地安装Node.js，下载本库脚本
教程请见：EvineDeng/jd-base，适用于以下系统：

Armbian/OpenWrt/Debian/Ubuntu/CentOS/Fedora/RedHat等Linux系统

Android

MacOS

方法二：云服务器、腾讯云函数等等
需自行有云服务器，云函数等
腾讯云云函数 快速部署教程（免费）
腾讯云云函数控制台使用 教程说明
腾讯云云函数 GitHub Action部署教程
方法三：Docker（NAS或VPS用户）
可以精确控制任务运行时间，有二种办法：docker办法一、docker办法二（和本地安装Node.js类似）
环境变量
注：以上三种运行机制都是Node.js，故您需仔细阅读下面几点
如果使用方法一与方法二，需自行提供京东cookie填写到 jdCookie.js 里面

获取京东cookie教程可参考 浏览器获取京东cookie教程 , 插件获取京东cookie教程

方法三Docker安装Cookie请见各自的说明。

方法四：iOS系统的代理软件（QuantumultX, Surge, Loon, 小火箭）
以下内容只针对iOS用户
ios使用多个京东账号，需要使用BoxJs保存多会话进行切换
BoxJs简单说明可看作者BoxJs仓库地址
使用box可以实现远程订阅助力好友(需订阅此 链接)

BoxJs使用教程

BoxJs教程视频

【用box订阅的好处】

1、脚本也可以远程挂载。京东活动助力功能的分享码只需在box里面填写。以后只需远程更新就行。

2、所有脚本的cookie都可以备份，方便你迁移到其他支持box的软件。

3、box可以支持多账号

赞赏码(开发维护不易,请赏杯茶水费)

特别感谢(排名不分先后)：
@NobyDa

@chavyleung

@liuxiaoyucc

@Zero-S1

@uniqueque

@nzw9314
