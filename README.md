# 卷毛鼠公益项目之电视直播源

- [目录](#目录)
- [**JMSIPTV简介**](#jmsiptv仓库简介)
  - [有效性检测](#有效性检测)
  - [播放器推荐](#播放器推荐)
- [**直播源**](#直播源)
  - [**直播源目录导航**](#直播源目录导航)
  - [**卷毛鼠代理直播源**](#卷毛鼠代理直播源)
    - [M3U文件](#m3u文件)
    - [更新日志](#更新日志)
  - [**卷毛鼠代理直播平台源**](#卷毛鼠代理直播平台源)
    - [M3U文件](#m3u文件-1)
    - [更新日志](#更新日志-1)
  - [**卷毛鼠代理youtube源**](#卷毛鼠代理youtube源)
    - [M3U文件](#m3u文件-2)
    - [更新日志](#更新日志-2)
  - [**卷毛鼠自制轮播源**](#卷毛鼠自制轮播源)
    - [M3U文件](#m3u文件-3)
    - [更新日志](#更新日志-3)
  - [**互联网收集直播源**](#互联网收集直播源)
    - [M3U文件](#m3u文件-4)
    - [更新日志](#更新日志-4)
- [**鸣谢**](#鸣谢)  
---
---

# **JMSIPTV简介**


JMSIPTV是卷毛鼠公益项目之一，主要以分享全球IPTV直播源为主，所有电视直播源均收集于互联网并经过精挑细选而成。同时为方便各位观看，卷毛鼠代理了一些其他平台可开放观看的直播节目/频道。JMSIPTV/JMSRadio内含有世界各国电视直播广播频道，因各国文件差异及认知水平不同在收看节目时请理性思考，恪守爱国、敬业、诚信、友善社会主义核心价值观公民个人层面的价值准则。

卷毛鼠公益项目成立于2020年8月30日，已稳定运行将近两年，卷毛鼠公益项目包括：公益流媒体服务（Emby）、公益电视直播与广播服务（IPTV&Radio）您关注卷毛鼠，卷毛鼠关注世界，世界在您身边！

卷毛鼠公益流媒体 Telegram频道：https://t.me/CurlyMouse

卷毛鼠公益IPTV Telegram频道：https://t.me/CurlyMouseIPTV

卷毛鼠公益流媒体 Telegram交流群：https://t.me/Curly_Mouse

卷毛鼠公益IPTV Telegram交流群：https://t.me/Curly_MouseIPTV

---





## 有效性检测
> 有效性检测工具：IPTV Checker.exe
> 
> 卷毛鼠节目源检测Bot：@iptvcheck_bot
>   * Bot需要在卷毛鼠IPTV群中使用，频道有使用教程




---



## 播放工具推荐
> * Windows端：Potplayer、vlc
> 
> * 电视端：Kodi、TiviMate
> 
> * 手机端：Televizo
> 




---
---




# **直播源**
## **直播源目录导航**
* [卷毛鼠代理直播源](#卷毛鼠代理直播源)
* [卷毛鼠代理直播平台源](#卷毛鼠代理直播平台源)
* [卷毛鼠代理youtube源](#卷毛鼠代理youtube源)
* [卷毛鼠自制轮播源](#卷毛鼠自制轮播源)
* [互联网收集直播源](#互联网收集直播源)



---



## **卷毛鼠代理直播源**
卷毛鼠通过各种程序或项目代理的电视直播源。代理亦可理解为转发的含义，因部分公开的电视直播受限于固定的播放环境，通过代理即可重新定义直播源体现形式，将各种有验证的动态的链接固定为单一的静态链接，方便大家观看。


![](https://img.shields.io/badge/%E6%9B%B4%E6%96%B0%E6%97%A5%E6%9C%9F-2022.05.27-brightgreen?style=for-the-badge)


### M3U文件


通过cloudflare workers代理出的电视匣源，适用任何播放器，因基于cloudflare workers代理，每天只有10w请求，如发现不能播放，说明请求已用光，等待第二天恢复即可。

> https://raw.githubusercontent.com/JMSTV/iptv/main/JMSTV-CFW.m3u

通过vps代理出的电视匣源，适用任何播放器，无任何请求限制，随用随播！

> https://raw.githubusercontent.com/JMSTV/iptv/main/JMSTV-VPS.m3u
### 更新日志
> **2022.05.27**：电视匣官方源故障，此代理即将作废，正在咕咕代码写最新代理，敬请期待~~
> 
> **2022.05.26**：添加两套不同类型的代理源，节目源已套用CloudFlareCDN，如播放卡顿请挂代理观看。
> 


---



## **卷毛鼠代理直播平台源**

卷毛鼠基于Golang语言一套国内知名直播平台代理系统，实现重定向访问虎牙、斗鱼、Bilibili直播间M3U8/FLV直播流，将直播平台动态源转换为静态链接，方便在各种终端平台的播放器中直接播放。在原作者(原作者已跑路两年)代码基础上修复了部分错误，提高了代理的性能！更多直播平台将陆续添加。

![](https://img.shields.io/badge/%E6%9B%B4%E6%96%B0%E6%97%A5%E6%9C%9F-2022.05.27-brightgreen?style=for-the-badge)

### 使用教程

直播源表现格式：

> https://live.52sf.ga/平台/ID
>   * 虎牙=huya；斗鱼=douyu；B站=bilibili

完整直播源举例：

> https://live.52sf.ga/bilibili/23158556
> 如果主播下播将无法观看哦~

### 更新日志
> **2022.05.27**：先写好内容，服务稍后上线，上线后会更新此GitHub。
> 
---



## **卷毛鼠代理youtube源**
咕咕咕~

---



## **卷毛鼠自制轮播源**
咕咕咕~

---



## **互联网收集直播源**
咕咕咕~

---

## 鸣谢

