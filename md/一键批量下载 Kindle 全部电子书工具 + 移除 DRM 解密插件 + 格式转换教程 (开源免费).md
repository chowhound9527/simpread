> 本文由 [简悦 SimpRead](http://ksria.com/simpread/) 转码， 原文地址 [www.iplaysoft.com](https://www.iplaysoft.com/kindle-download-dedrm.html) [哔哩大会员限时 98 元 / 年](https://www.iplaysoft.com/p/bilibili-vip)  |   [PD18 虚拟机](https://www.iplaysoft.com/go/pdpost)  |   [爱奇艺 + 京东 Plus=123 元](https://www.iplaysoft.com/news/4313)  |   [腾讯云](https://www.iplaysoft.com/go/qcloud)  |   [Win11 激活码](https://www.iplaysoft.com/windows11.html)

最近「[亚马逊](https://www.iplaysoft.com/go/amazon)」官方宣布了旗下的 [Kindle 电子书店](https://www.iplaysoft.com/go/kindlestore)将会正式退出中国市场，2024 年 6 月 30 日后正式关闭中国区的电子书下载功能，这对于一部分喜欢看电子书的朋友真的是噩耗。

如果你之前购买过不少 Kindle [电子书](https://www.iplaysoft.com/tag/电子书)，那么建议大家将已购的电子书全部下载到本地永久保存[备份](https://www.iplaysoft.com/tag/备份)，以免停止服务后无法再下载图书资源。那要怎样才能**批量下载到 Kindle 帐号的全部电子书**呢？下面异次元就送上教程，用[开源](https://www.iplaysoft.com/tag/开源)的「**Kindle 下载助手 + DeDRM 插件**」轻松搞定……

[推荐：电纸书阅读器](https://www.iplaysoft.com/go/ebookreader)

[传送门：热门畅销图书榜](https://www.iplaysoft.com/go/book)

### 批量下载 Kindle 全部电子书永久保存

<iframe>

「**Kindle 下载助手**」(**Kindle download helper)** 是一个免费[开源](https://www.iplaysoft.com/tag/开源)的小工具，可以帮助用户一键批量下载亚马逊 Kindle 帐号里全部已购买的电子书以及个人文档，下载到本地[硬盘](https://www.iplaysoft.com/tag/硬盘)，以便永久保存这些已购买的电子图书，避免停服后造成损失。

![](https://img.iplaysoft.com/wp-content/uploads/2022/kindle-download-helper/kindle.jpg!0x0.webp)

该工具目前已支持[中国区 (amazon.cn)](https://www.iplaysoft.com/go/amazon)、[美国区 (amazon.com)](https://www.iplaysoft.com/go/amazonus) 和日本区 (amazon.co.jp) 三大区的帐号。最初它也只是一个[命令行](https://www.iplaysoft.com/tag/命令行)工具，但随着大佬们的合作，现在的 Kindle 下载助手已经拥有了简单易用的图形界面了，在使用上基本没有难度！

#### 打开 Kindle 电子书提示受 DRM 保护错误？

不过，下载其实并不难，最大的问题是，“[批量](https://www.iplaysoft.com/tag/批量)下载回来的 Kindle 的正版电子书文件都是带有 DRM 加密保护的”，尽管是花钱购买的正版内容，但你并不能随意使用它们。比如直接使用第三方阅读软件如 [Calibre](https://www.iplaysoft.com/calibre.html) 来打开它们时会提示 DRM 错误，并无法[阅读](https://www.iplaysoft.com/tag/阅读)。

![](https://img.iplaysoft.com/wp-content/uploads/2022/kindle-download-helper/kindle_drm_error.jpg!0x0.webp)

所以异次元这次的[教程](https://www.iplaysoft.com/tag/教程)将一起教会大家如何 “**搞定 Kindle 电子书批量下载 + 移除 DRM 保护 + 转换格式**” (让电子书能在任意设备阅读 / 转换[格式](https://www.iplaysoft.com/tag/格式)等) ，方便大家永久保存和收藏自己购买过的电子书。废话不多说，我们这就开始吧。

### 第一步：设置帐号的默认设备

在开始之前，我们需要首先做一个 “设置默认设备” 的操作，并以此**获得正确的 16 位的序列号或对应的 Key 密钥文件**。这一步是必要的！后面要用到它们来破解移除电子书的 DRM 保护，后面有详解。

#### 情况 1：你拥有 Kindle 设备，只需记下 16 位序列号

如果你拥有[实体的 Kindle 阅读器](https://www.iplaysoft.com/go/kindle)设备，可以前往「[这里查看帐号绑定的默认设备](https://www.amazon.cn/hz/mycd/digital-console/alldevices)」，如果已是此设备，那么就记录下它的 16 位序列号（不是 32 位的）即可。否则，你需要在该设备上登录亚马逊帐号，然后回到网页上将其 “设置为默认设备”，再记录下它的序列号。

#### 情况 2：你「没有」Kindle 设备，那就要安装桌面版 Kindle 应用程序

如果你没有 Kindle 设备，平常使用的是电脑或手机的 APP，那么就需要多做下面几步了。

1、下载 “旧版” 的 **Kindle 桌面版程序** (Windows v1.24 / Mac v1.31)，注意官网最新的版本是不行的，用手机版也不行，下载地址在本文末尾有提供。  
2、修改系统的 [hosts](https://www.iplaysoft.com/switchhosts.html) 防止软件自动更新，添加下面两行：

> 127.0.0.1 kindleformac.s3.amazonaws.com  
> 127.0.0.1 kindleforpc.s3.amazonaws.com

3、安装并运行 Kindle 应用，优先进入选项里禁用 “自动更新”，然后再登录你的帐号。  
4、[前往这里](https://www.amazon.cn/hz/mycd/digital-console/alldevices)将你的这个 Kindle 应用程序 “设置为默认设备”。

### 第二步：使用 Kindle 下载助手批量下载电子书

下载并打开 「**Kindle 下载助手**」(本文结尾处绿色框内有提供) ，你可以通过点击 “登录” 按钮打开浏览器来尝试自动获取 Cookie。但如果你无法成功获取，那么可以参考下面手动输入 Cookies 的方法。

![](https://img.iplaysoft.com/wp-content/uploads/2022/kindle-download-helper/kindle_download_helpder.png!0x0.webp)

#### 手动输入 Cookies 和 CSRF Token 方法：

本文以 Windows 版的 [Edge 浏览器](https://www.iplaysoft.com/microsoft-edge.html)为例子 ([Chrome 浏览器](https://www.iplaysoft.com/google-chrome.html)的操作基本类似)，首先在浏览器上打开亚马逊 [Kindle 网站上的「我的内容」](https://www.amazon.cn/gp/digital/fiona/manage/?ie=UTF8&tag=personalass3898-23)并登录上你的帐号。

登录成功后可以看到全部的已购图书列表，在网页空白处点击鼠标右键，然后选择「检查」，或者按下键盘快捷键 `Ctrl`+`Shift`+`i` (注意：不同浏览器 / 不同系统的热键并不一样) 来呼出「开发人员工具」。

##### 第一步：获取 Cookies 的值

依次进入 “网络”(Network) 面板，然后点击 “Fetch/XHR”，然后在列表中点击任意一个 ajax 请求（若列表为空可以刷新下页面），就可以看到请求的数据了。

![](https://img.iplaysoft.com/wp-content/uploads/2022/kindle-download-helper/cookies.png!0x0.webp)

然后在「标头」一栏里面找到「请求标头」(不是响应标头)，就能找到名为 Cookie 的数据了，拷贝它的全部内容值 (注意不要包含 `Cookie:` 字眼，前后无空格)

##### 第二步：获取 csrfToken 的值

![](https://img.iplaysoft.com/wp-content/uploads/2022/kindle-download-helper/csrftoken.png!0x0.webp)

在同一个地方点击 「负载」(Payload) 面板，在里面的「表单数据」一项里就能找到 csrfToken 的值了。同样是要拷贝 “值”，不要包含 `csrfToken:` 本身，前后也不含空格。注意的是，csrfToken 的值是有时效性的，取出来太久过期了的话后面是无法下载到图书的。

#### 批量下载全部 Kindle 电子书：

成功获取到了 **Cookie** 和 **csrfToken** (CSRF Token) 的值之后，我们就能在 [Kindle 下载助手](https://www.iplaysoft.com/kindle-download-dedrm.html)的界面上面一一对应填写了，然后点击「获取下载列表」按钮，该工具就能帮列出全部已购买的图书和个人文档内容了。

![](https://img.iplaysoft.com/wp-content/uploads/2022/kindle-download-helper/kindle_dl_helpder_download.png!0x0.webp)

设置好本地保存的目标文件夹后，点击「下载全部」按钮就可以批量下载你的亚马逊账号里全部已购的电子书了！到此，我们已经完成了图书下载的步骤了。不过先不要鸡冻，因为后面我们还有一些事情要处理。

### 第二步：移除亚马逊 azw 电子书的 DRM 保护 + 转换格式

因为，通过 Kindle download helper 工具下载，或直接在[亚马逊网站](https://www.iplaysoft.com/go/amazon)里下载得到的电子书都「**带有 DRM 版权[加密](https://www.iplaysoft.com/tag/加密)保护**」，虽然你可以传输到已绑定的 Kindle 设备里阅读，但你是无法随意在其他的设备上使用这些电子书的，也无法直接进行格式转换。所以为收藏方便日后使用，我们还必须要**移除电子书的 DRM 保护限制**。

#### 什么是 DRM 保护？为什么要删除它

Kindle 采取了数字 **DRM 保护**为了防止用户非法拷贝、阅读或分享其电子书，DRM 全称 (Digital rights management) 即「数字版权管理」。我们无需了解 DRM 是如何保护版权的，只需知道正版的 Kindle 电子书存在各种限制 (如无法在任意设备上打开 / 阅读 / 转格式)，打开时提示 “This book is locked by DRM” 之类的错误，只有在删除 DRM 后才能解除这些限制。

![](https://img.iplaysoft.com/wp-content/uploads/2022/kindle-download-helper/kindle_drm_to_pdf_epub.png!0x0.webp)

既然亚马逊官宣了要关闭 Kindle 服务了，那就意味着在 2024 年 6 月 30 日关停之后，我们将无法再下载或使用自己购买过的内容。而如果我们想让这些电子书日后还能用，那么除了下载，还必须想办法[破解](https://www.iplaysoft.com/tag/破解)并移除它们的 DRM 保护，**并转换成没有任何限制的 ePUB、[PDF](https://www.iplaysoft.com/tag/pdf) 等通用格式，才能算是「永久保存好这些电子书」**。

事实上，只要我们不去分享[电子书](https://www.iplaysoft.com/tag/电子书) (不经允许的分发属于盗版 / 侵犯版权行为)，移除自己合法购买的数字内容 DRM 并在自己的设备上合理自用的行为其实并不算违法。下面，我们就给大家说说怎样移除 Kindle 的 DRM 保护吧。

### 使用 Calibre + DeDrm 插件移除 DRM

异次元曾经推荐过的「[跨平台电子书管理神器——Calibre](https://www.iplaysoft.com/calibre.html)」可以让我们阅读和转换电子书的[格式](https://www.iplaysoft.com/tag/格式)，而它最大的特点是[开源](https://www.iplaysoft.com/tag/开源)同时还支持插件扩展。这里我们使用了一款开源的「**DeDRM 插件**」，能帮助我们在 Calibre 里删除 Kindle 电子书的 DRM 保护，之后就能随意转换格式了。

#### 1、安装 Calibre + DeDRM 插件

根据你的系统，[下载安装对应版本的 Calibre](https://www.iplaysoft.com/calibre.html)，然后在本文的结尾处**下载 DeDRM 插件**（异次元实测 Calibre v5.44.0 + DeDRM v10.0.2 插件可以成功，其他版本未做尝试）。启动 Calibre 后，在顶部的工具栏里，选择「首选项」并找到「插件」。

![](https://img.iplaysoft.com/wp-content/uploads/2022/kindle-download-helper/calibre_plugins.png!0x0.webp)

下载异次元所提供的 DeDRM 插件压缩包，解压得到里面的 `DeDRM_plugin.zip` 文件 (此文件无需再解压)，然后点击下图中的「从文件加载插件」，选择路径即可成功安装插件。

![](https://img.iplaysoft.com/wp-content/uploads/2022/kindle-download-helper/calibre_plugins_loadfromfile.png!0x0.webp)

成功加载之后，在「插件」页列表里应该就能搜索到 DeDRM 插件，这就表示安装成功了。

#### 2、填写 Kindle 序列号或生成 Key 密钥

这里根据前面第一步说到的两种情况有所区别。

##### 情况 1：如果你拥有 Kindle 设备：

![](https://img.iplaysoft.com/wp-content/uploads/2022/kindle-download-helper/calibre_plugins_dedrm_sn.png!0x0.webp)

如上图的步骤，点击 “插件”→“文件类型”→“DeDRM (双击)”→“eInk Kindle ebooks”→ `+`，在 “EInk Kindle Serial Number” 一栏里输入前面记录下来的 16 位序列号并保存即可。

另外，在 Kindle 下载助手的下载目录里也保存有 `key.txt` 的文件应该也记录着序列号，可做参考。

##### 情况 2：如果你没有 Kindle 设备 (安装桌面应用程序)

按照前面的步骤，你应该已经**安装好了 Windows 或 Mac 版的 Kindle 阅读器 APP 应用程序**并登录上自己的帐号了，这时启动 [Calibre](https://www.iplaysoft.com/calibre.html) 软件并进入插件页。

![](https://img.iplaysoft.com/wp-content/uploads/2022/kindle-download-helper/calibre_plugins_dedrm_key.png!0x0.webp)

进入 “插件”→“文件类型”→“DeDRM (双击)”→“Kindle for Mac/PC ebooks”，正常情况下 Calibre 的 DeDrm 插件已能自动找到“default_key” 的密钥了，如上图这样就 OK 了！无需做其他操作。（如果这里列表是空的，可试试用 Kindle 应用随意下载一本书让其生成密钥）

#### 3、转换格式并导出无 DRM 的电子书

**在确保你填入了正确的序列号或者拥有 key 密钥之后**，[Calibre](https://www.iplaysoft.com/calibre.html) 即可以直接打开阅读任意由 Kindle 下载助手批量下载的或直接在亚马逊官网上下载回来的 azw 格式电子书了。(否则会提示 “本书由 DRM 加密保护”/ This book is locked by DRM 的错误)

![](https://img.iplaysoft.com/wp-content/uploads/2022/kindle-download-helper/calibre_convert_books.png!0x0.webp)

如果你能在 Calibre 里成功打开阅读这些 .azw 电子书就表示 DeDRM 解密是成功的了！之后就能 “为所欲为” 啦！将所有下载回来的 azw 文件全部拖放进或导入到 Calibre 里面，点击菜单栏的「转换书籍」或「批量转换」，即可将这些电子书全部**转换为没有 DRM 限制的 EPUB 或 PDF，或是任何其他你喜欢格式**了。

至此，你已成功移除亚马逊 Kindle 电子书的 DRM 保护并转换成通用的格式了！你可以试试用另外的阅读器如 [SumatraPDF](https://www.iplaysoft.com/sumatra-pdf.html) 测试打开是否成功。之后你是将它们导出上传到[网盘](https://www.iplaysoft.com/tag/网盘)或是 [NAS](https://www.iplaysoft.com/go/nas) 上永久保存备份，还是传到[手机](https://www.iplaysoft.com/go/shouji)、iPad 或是放到其他品牌的[电纸书阅读器](https://www.iplaysoft.com/go/ebookreader)上慢慢阅读就看阁下意愿了。

### 总结：

[亚马逊](https://www.iplaysoft.com/go/amazon) Kindle 退出中国对于喜欢[读书](https://www.iplaysoft.com/go/book)又喜欢[电纸书设备](https://www.iplaysoft.com/go/ebookreader)的人来说确实是一大 遗憾，毕竟好的正版电子书商城并不多，但既然这已是事实，我们也只好想办法保存好自己买过的图书了。

使用 **Kindle 下载助手**工具，我们可以很方便地批量一键下载保存到本地。但为了日后能随意使用这些电子书，还必须要移除 DRM 保护。跟着异次元的[教程](https://www.iplaysoft.com/tag/教程)其实操作也并不难。而做了这些之后，至少我们可以永久收藏保存好自己买过的这些[电子书](https://www.iplaysoft.com/tag/电子书)，避免自己的损失了。

### 相关文件下载地址

官方网站：[访问](https://www.iplaysoft.com/go/amazon)  
软件性质：免费 + 开源  
解压密码：www.iplaysoft.com

旧版本 Kindle 桌面应用：[Windows v1.24](https://dl.iplaysoft.com/files/5729.html)  |  [macOS v1.31](https://dl.iplaysoft.com/files/5730.html)  
[Kindle 下载助手 Win](https://dl.iplaysoft.com/files/5732.html)、[Mac](https://dl.iplaysoft.com/files/5733.html)  |  [Calibre 电子书管理器](https://www.iplaysoft.com/calibre.html)  |  [DeDRM 插件](https://dl.iplaysoft.com/files/5731.html)  |  [更多阅读相关](https://www.iplaysoft.com/tag/阅读)