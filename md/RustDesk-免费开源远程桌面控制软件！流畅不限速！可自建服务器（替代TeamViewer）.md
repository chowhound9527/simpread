> 本文由 [简悦 SimpRead](http://ksria.com/simpread/) 转码， 原文地址 [www.iplaysoft.com](https://www.iplaysoft.com/rustdesk.html) [哔哩大会员限时 98 元 / 年](https://www.iplaysoft.com/p/bilibili-vip)  |   [PD18 虚拟机](https://www.iplaysoft.com/go/pdpost)  |   [爱奇艺 + 京东 Plus=123 元](https://www.iplaysoft.com/news/4313)  |   [腾讯云](https://www.iplaysoft.com/go/qcloud)  |   [Win11 激活码](https://www.iplaysoft.com/windows11.html)

远程操控类软件并不少，比如推荐过的 [ToDesk](https://www.iplaysoft.com/todesk.html)，还有老牌的 [TeamViewer](https://www.iplaysoft.com/teamviewer.html)、[向日葵](https://www.iplaysoft.com/sunlogin.html)、[微软远程桌面](https://www.iplaysoft.com/microsoft-remote-desktop.html)、[AnyDesk](https://www.iplaysoft.com/anydesk.html) 等，但这些工具大多数商业化、免费限制多，或服务器在国外连接卡顿不流畅。

但如果你还是想找一款 “**免费开源**” 的[远程](https://www.iplaysoft.com/tag/远程)控制软件来替代这些商业软件，**RustDesk** 正是一个好选择！它完全免费可商用、跨平台、功能丰富不限速，甚至你还能**自建中继服务器**，不必担心安全和网速问题！可以说是解决了大家对远控软件的很多痛点……

「[Office 办公软件](https://www.iplaysoft.com/go/officepost) / [VPS 服务器推荐](https://www.iplaysoft.com/go/vps)」

### 好用！开源免费的 ToDesk / Teamviewer 有力替代品

<iframe>

**RustDesk** 是一款小巧轻量好用、[开源](https://www.iplaysoft.com/tag/开源)且完全免费的**远程桌面控制软件**！它跟 [ToDesk](https://www.iplaysoft.com/todesk.html)、[TeamViewer](https://www.iplaysoft.com/teamviewer.html)、[AnyDesk](https://www.iplaysoft.com/anydesk.html) 等软件一样简单易用，无需任何配置，也不必像[微软远程桌面](https://www.iplaysoft.com/microsoft-remote-desktop.html)那样考虑[内网穿透](https://www.iplaysoft.com/tag/穿透)的情况，能轻松实现各种远程[办公](https://www.iplaysoft.com/tag/办公)、远程教学 / 演示，或者是远程协助 / 技术支持等工作。

![](https://img.iplaysoft.com/wp-content/uploads/2022/rustdesk/rustdesk.jpg)

RustDesk 软件轻量小巧，界面清爽，跨平台支持 Windows、[Mac](https://www.iplaysoft.com/os/mac-platform)、[Linux](https://www.iplaysoft.com/os/linux-platform) 和 [iOS](https://www.iplaysoft.com/os/ios-platform)、[Android](https://www.iplaysoft.com/os/android-platform) 系统，也提供**网页版**客户端，支持文件传输、可调整画面质量、端到端加密、支持[局域网](https://www.iplaysoft.com/tag/局域网)发现、支持 IP 白名单、剪贴板互通 (复制粘贴文件)、收发文本消息等功能。

![](https://img.iplaysoft.com/wp-content/uploads/2022/rustdesk/rustdesk_connect.png)

软件的使用方式非常简单，只需输入受控机的 ID 和密码即可连接！RustDesk 的 Windows 版还可以纯绿色运行，临时用用很方便。如果需要长期 “受控” 的话，则可以选择安装。

但最大的特色还不是上面这些，而是 RustDesk 还支持用户搭建私有的中继服务器，你可以完全掌控自己的流量和数据，不必担心[安全](https://www.iplaysoft.com/tag/安全)问题！因为 RustDesk 不仅提供客户端软件，同时也还提供了「服务器端程序」。

### 支持自建中继服务器

如果个人或轻度使用的话，你可以直接使用 RustDesk 官方公共免费的中继服务器，无需任何配置。而如果你比较注重安全性和稳定性，那么你还能**用[自己的云服务器](https://www.iplaysoft.com/go/vps)、NAS (比如[群晖](https://www.iplaysoft.com/go/synology)、QNAP 等) 等设备来搭建专属的 RustDesk 中继服务器**，来保证远程连接的安全和网速的可控。

![](https://img.iplaysoft.com/wp-content/uploads/2022/rustdesk/rustdesk_win11.jpg)

特别是[公司](https://www.iplaysoft.com/tag/公司)、团队有[服务器](https://www.iplaysoft.com/go/vps)资源的，完全可以借助 RustDesk 自建一套私有可靠的远控系统，可以应用在商业化用途，还不必为此付费！这一点是其他同类软件无法提供的。([参考文档](https://rustdesk.com/docs/zh-cn/self-host/?utm_source=iplaysoft.com&hmsr=iplaysoft.com))

### 为什么 RustDesk 有时流畅有时卡顿？

为了提高远控的流畅性，RustDesk 会首先尝试建立 TCP 隧道，俗称 “打洞直连”，尝试让两台设备直接「点对点」穿透，如果能成功连接，这种方式速度是最快的，完全取决于自家的网速带宽，用户会感觉到很流畅；但如果失败的话，它才会再通过「中继服务器」来中转两者流量。

#### 先尝试 “打洞” 直连，失败再走服务器中转

打洞失败的话，远程控制的流畅性就基本全部取决于中继[服务器](https://www.iplaysoft.com/go/vps)的线路快慢和稳定了。虽然说 RustDesk 本身并无限速、也无功能限制，但由于官方的 “免费公共中继服务器” 出于成本考虑都部署在海外，因此国内直接用起来还是会比 「[ToDesk](https://www.iplaysoft.com/todesk.html)」等本土服务要慢一些。

毕竟 RustDesk 只是一个开源项目，没收费也无广告，官方纯粹是用爱在发电，所以你能 “白嫖” 的这些公共服在国内访问的速度只能说将就，就当做是功能演示来看吧。

![](https://img.iplaysoft.com/wp-content/uploads/2022/rustdesk/rustdesk_relay.png)

如果你想舒舒服服地使用 RustDesk，真正实用的场景还是「**自建中继服务器**」！修改方法如上图，只要你有一点动手能力，同时也有[国内服务器](https://www.iplaysoft.com/go/vps)的话，就能获得 “丝般顺滑” 的体验。否则，可能 [ToDesk](https://www.iplaysoft.com/todesk.html) 会更合适轻度用户或懒人们使用。所以，其实 RustDesk 和 ToDesk 实际上是面向两种不同人群需求的。

### 更多 RustDesk 的特性：

#### 多平台互相控制，支持文件传输：

说回远控软件本身，RustDesk 可以支持多端互相控制，只需输入远程设备的 ID 和[密码](https://www.iplaysoft.com/tag/密码)即可连接。除了常规的 Win、[Mac](https://www.iplaysoft.com/go/mac)、Linux 等不同平台的电脑互相远程控制外，还支持使用手机 / 平板 APP (iPhone、iPad、Android 等) 来控制电脑。

[RustDesk 远程桌面 iPhone 版截图]<table cellpadding="0" cellspacing="0"><tbody><tr align="center"><td><a rel="colorbox1" target="_blank" href="https://is3-ssl.mzstatic.com/image/thumb/PurpleSource115/v4/50/ef/a5/50efa545-526e-1d3a-1dab-8d41d0b61072/78d505f6-10e2-480b-8d5b-c26fd4f1fa62_Simulator_Screen_Shot_-_iPhone_11_Pro_Max_-_2021-08-20_at_02.12.31.png/600x0w.jpg"><img class="" src="https://is3-ssl.mzstatic.com/image/thumb/PurpleSource115/v4/50/ef/a5/50efa545-526e-1d3a-1dab-8d41d0b61072/78d505f6-10e2-480b-8d5b-c26fd4f1fa62_Simulator_Screen_Shot_-_iPhone_11_Pro_Max_-_2021-08-20_at_02.12.31.png/300x0w.jpg"></a></td><td><a rel="colorbox1" target="_blank" href="https://is1-ssl.mzstatic.com/image/thumb/PurpleSource125/v4/af/bd/4d/afbd4d43-0857-ba93-4296-54f644b819b5/d32f5816-66bd-42a1-b91b-12404983bfcf_Simulator_Screen_Shot_-_iPhone_11_Pro_Max_-_2021-08-20_at_02.52.15.png/600x0w.jpg"><img class="" src="https://is1-ssl.mzstatic.com/image/thumb/PurpleSource125/v4/af/bd/4d/afbd4d43-0857-ba93-4296-54f644b819b5/d32f5816-66bd-42a1-b91b-12404983bfcf_Simulator_Screen_Shot_-_iPhone_11_Pro_Max_-_2021-08-20_at_02.52.15.png/300x0w.jpg" style="width: auto;"></a></td><td><a rel="colorbox1" target="_blank" href="https://is1-ssl.mzstatic.com/image/thumb/PurpleSource125/v4/6c/d1/ed/6cd1edd0-eaf5-b726-8738-f7d7cbff1f3e/c78fc2f2-0590-4db8-86db-706d0847f854_Simulator_Screen_Shot_-_iPhone_11_Pro_Max_-_2021-08-20_at_02.52.52.png/600x0w.jpg"><img class="" src="https://is1-ssl.mzstatic.com/image/thumb/PurpleSource125/v4/6c/d1/ed/6cd1edd0-eaf5-b726-8738-f7d7cbff1f3e/c78fc2f2-0590-4db8-86db-706d0847f854_Simulator_Screen_Shot_-_iPhone_11_Pro_Max_-_2021-08-20_at_02.52.52.png/300x0w.jpg" style="width: auto;"></a></td><td><a rel="colorbox1" target="_blank" href="https://is2-ssl.mzstatic.com/image/thumb/PurpleSource115/v4/b5/5e/17/b55e1789-4d03-ef43-7c4d-04b899aa6f0d/41ce5dbc-ec85-4f83-adce-824689e245f4_Simulator_Screen_Shot_-_iPhone_11_Pro_Max_-_2021-08-20_at_02.51.10.png/600x0w.jpg"><img class="" src="https://is2-ssl.mzstatic.com/image/thumb/PurpleSource115/v4/b5/5e/17/b55e1789-4d03-ef43-7c4d-04b899aa6f0d/41ce5dbc-ec85-4f83-adce-824689e245f4_Simulator_Screen_Shot_-_iPhone_11_Pro_Max_-_2021-08-20_at_02.51.10.png/300x0w.jpg" style="width: auto;"></a></td></tr></tbody></table>

#### 支持远程文件传输：

除了远程桌面，我们经常还需要在不同电脑之间传输文件，RustDesk 提供了一个非常实用的文件传输管理器，可以方便地发送和接收文件。另外，[剪贴板](https://www.iplaysoft.com/tag/剪贴板)也能开启复制 / 粘贴文件的功能。

![](https://img.iplaysoft.com/wp-content/uploads/2022/rustdesk/rustdesk_transfer.png)

#### 支持安卓手机端受控

RustDesk 还有个比较特色的功能就是支持 Android 端受控，也就是说你可以在电脑上远程操作安卓手机了。所以除了用于办公之外，有时你还能借助它远程帮助父母长辈解决[手机](https://www.iplaysoft.com/tag/手机)问题。

![](https://img.iplaysoft.com/wp-content/uploads/2022/rustdesk/rustdesk_android_control.png)

#### TeamViewer 等商业软件的优秀代替品

另外，RustDesk 免费可商用，能轻松替代 [TeamViewer](https://www.iplaysoft.com/teamviewer.html)、[AnyDesk](https://www.iplaysoft.com/anydesk.html) 等各种老牌昂贵的商业软件，加上开源以及能自建中转服务器，对需要控制成本或注重可控性安全性的个人、中小公司和团队都非常友好！也非常适合需要维护大量主机的[运维](https://www.iplaysoft.com/tag/运维)人员使用。

*   开源免费！个人、公司均可用于商业用途
*   支持多平台 Windows、macOS、Linux、iOS、Android 客户端 APP 齐全
*   支持 Android 安卓受控
*   提供网页版，可以在[浏览器](https://www.iplaysoft.com/tag/浏览器)上进行远程控制
*   轻量小巧，Windows 上甚至是 “绿色” 软件，不必安装就能运行
*   界面清爽简洁，上手简单，无需[学习](https://www.iplaysoft.com/tag/学习)成本
*   支持自行搭建中继服务器，保证网络速度稳定性和安全性
*   支持远程文件传输 (互传)、剪贴板互通等功能
*   可调整画面质量，可以设置 IP 白名单，支持代理连接等
*   支持端到端加密，以及基于角色的访问权限控制，数据传输足够安全
*   不区分控制端和受控端，可以控制别人，也能允许被控。

### 总结：

**RustDesk** 最大的亮点在于开源并支持自建中继服务器，可保证网络安全和网速稳定。大家可以根据需求自行搭建，而且有[开发](https://www.iplaysoft.com/tag/开发)能力的朋友还能基于它的源代码进行二次开发。

功能上，远程控制软件该有的功能 RustDesk 基本都齐全，软件小巧轻量，跨平台支持丰富，可以很好满足各种远控[办公](https://www.iplaysoft.com/tag/办公)的需求了。如果你一直在寻找免费可商用、低成本的远程控制软件方案，特别是有能力自建中继，那么 RustDesk 绝对是你个人或公司团队的极佳远程方案。

### 相关文件下载地址

官方网站：[访问](https://rustdesk.com/zh/?utm_source=iplaysoft.com&hmsr=iplaysoft.com)  
软件性质：免费开源  
同类软件：[ToDesk](https://www.iplaysoft.com/todesk.html)  |  [TeamViewer](https://www.iplaysoft.com/teamviewer.html)  |  [微软远程桌面](https://www.iplaysoft.com/microsoft-remote-desktop.html)  |  [向日葵](https://www.iplaysoft.com/sunlogin.html)  
相关链接：[更多远程相关](https://www.iplaysoft.com/tag/远程)  |  [服务器相关](https://www.iplaysoft.com/tag/服务器)  |  [更多开源](https://www.iplaysoft.com/tag/开源)  |  [运维相关](https://www.iplaysoft.com/tag/运维)  
解压密码：www.iplaysoft.com

[下载 RustDesk 官方绿色便携版 (Windows)](https://dl.iplaysoft.com/files/5741.html)  |  [Mac](https://dl.iplaysoft.com/files/5742.html)  |  [Linux](https://dl.iplaysoft.com/files/5743.html)  |  [iOS](https://dl.iplaysoft.com/files/5744.html)  |  [Android](https://dl.iplaysoft.com/files/5745.html)
