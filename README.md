# 百度网盘下载助手 | Online disk direct link download assistant

可以获取网盘文件真实下载地址。基于【网盘直链下载助手】修改，原作者：[油小猴](https://www.youxiaohou.com/) ，自用，去广告，甚至比原版还要好用！

## 说明

基于[【网盘直链下载助手】](https://www.baiduyun.wiki/install.html)修改
- 原作者：[油小猴](https://www.youxiaohou.com/)  
- 原脚本：[https://greasyfork.org/scripts/436446](https://greasyfork.org/scripts/436446)
- 原脚本仓库：[https://github.com/syhyz1990/baiduyun](https://github.com/syhyz1990/baiduyun)
- 本脚本发布至 GreasyFork：(https://greasyfork.org/zh-CN/scripts/484953-%E7%99%BE%E5%BA%A6%E7%BD%91%E7%9B%98%E4%B8%8B%E8%BD%BD%E5%8A%A9%E6%89%8B)
   
因网络环境，发布新脚本时 GreasyFork 是最快更新的，所以请在 GreasyFork [【直接安装本脚本】](https://greasyfork.org/zh-CN/scripts/484953-%E7%99%BE%E5%BA%A6%E7%BD%91%E7%9B%98%E4%B8%8B%E8%BD%BD%E5%8A%A9%E6%89%8B)。  

## 简介

现已支持百度、阿里、天翼、迅雷、夸克、移动六大网盘，可使用IDM等工具下载，完美适配Chrome，Edge等18种浏览器，可在无法安装客户端的环境下使用，助手免费开源。😎  
![TamperMonkeyBeta 篡改猴测试版](https://img.shields.io/badge/TamperMonkeyBeta_篡改猴测试版-v5.0.6190-red.svg)
![TamperMonkey 篡改猴](https://img.shields.io/badge/TamperMonkey_篡改猴-v4.19.0-brightgreen.svg)
![Violentmonkey 暴力猴](https://img.shields.io/badge/Violentmonkey_暴力猴-v2.15.0-brown.svg)  
![Google Chrome-≥76.0](https://img.shields.io/badge/Google_Chrome-≥76.0-yellow.svg)
![Microsoft Edge-≥88.0](https://img.shields.io/badge/Microsoft_Edge-≥88.0-blue.svg)
![支持平台](https://img.shields.io/badge/支持平台-Windows_|_Mac_|_Linux_|_Android-blueviolet.svg)


#### 卑微的小标题

这个脚本只有一个人在修改\~如果喜欢的话还请留个[好评](https://greasyfork.org/scripts/449291/feedback)和Star哦\~   
- 如有bug等问题请在这发[议题反馈](https://github.com/hmjz100/Online-disk-direct-link-download-assistant/issues)  
- 或者在[GreasyFork反馈](https://greasyfork.org/scripts/449291/feedback)，如果看到的话我会尽量修改。
- Greasy Fork 有人乱举报/(ㄒoㄒ)/~~

## 统计~

![Daily Installs](https://palerock.cn/node-service/images/greasyfork/stats/daily-installs/449291)
![Daily Updates](https://palerock.cn/node-service/images/greasyfork/stats/daily-updates/449291)
![Total Installs](https://palerock.cn/node-service/images/greasyfork/stats/total-installs/449291)
![Fan Score](https://palerock.cn/node-service/images/greasyfork/info/fan_score/449291?name=得分&rcolor=orange)
![Good Ratings](https://palerock.cn/node-service/images/greasyfork/info/good_ratings/449291?name=好评&rcolor=darkcyan)
![Views Info](https://palerock.cn/node-service/images/greasyfork/views-info/449291)
![License](https://palerock.cn/node-service/images/greasyfork/info/license/449291?name=许可证&rcolor=blueviolet)  

![Starchart](https://starchart.cc/hmjz100/Online-disk-direct-link-download-assistant.svg)

## 版本号
V. 1.2.2
- 如果 此处公布的脚本版本号 与 您获取到本脚本的网站 上公布的脚本版本号不一致，请不要安装，因为那可能是盗脚本的网站   
例如 MonkeyFork 就是盗用本脚本的网站之一，本脚本目前仅在 Github 与 Greas Fork 发布，如果您是在其他渠道获取到本脚本的，请不要安装。

## 公告

1. 要是连油猴菜单也没有加载出来的话，请检查网络环境能否打开[`unpkg.com`](https://unpkg.com)，  
我使用的DNS是微软推荐的`4.2.2.1`和`4.2.2.2`，可以正常访问[`unpkg.com`](https://unpkg.com)和[`api.youxiaohou.com`](https://api.youxiaohou.com)

**本脚本是 <a>网盘直链</a> 获取，而 <a>不提供</a> 会员链接解析功能，只是为了给会员用户免下载网盘客户端使用的。**  
###### (那些写着“查找内部隐藏优惠券”的脚本【大部分】都是搬运的现成脚本引用【不明来源】的查找优惠券脚本，装多了会影响你的购物体验(毕竟代码都不同，而且有可能收集你的隐私信息)，并且脚本作者能够盈利，所以各位还是要小心呀)

**如果遇到了只加载出油猴菜单，没有出现“下载助手”按钮的情况，请先打开任意网盘页面，进入脚本菜单中的`⚙ 设置`→在打开的`助手设置`弹窗找到`使用油小猴服务器`→选择`不使用 [用 jsdelivr 连接本项目 Github 仓库](更新可能不及时)`可能会暂时解决该情况。**   
![2](https://greasyfork.org/rails/active_storage/blobs/redirect/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaHBBd3pKQVE9PSIsImV4cCI6bnVsbCwicHVyIjoiYmxvYl9pZCJ9fQ==--9a082a73b5617faa71ad0ae5f048f27c87df4ff6/1.png)
--> 
