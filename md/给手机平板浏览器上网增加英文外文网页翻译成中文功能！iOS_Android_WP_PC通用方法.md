> 本文由 [简悦 SimpRead](http://ksria.com/simpread/) 转码， 原文地址 [www.iplaysoft.com](https://www.iplaysoft.com/translate-bookmarklet.html) 

最近由于买 [X-Box](https://www.iplaysoft.com/go/xboxone)、[PS4](https://www.iplaysoft.com/go/ps4) 等迷上了海淘而经常要在不同国家的[亚马逊](https://www.iplaysoft.com/go/amazonus)网站挑选商品，英语还好，而日语、法语、德语等各种外语网页都得靠翻译，因此特别希望能在**电脑和手机上都能方便地将网页[翻译](https://www.iplaysoft.com/tag/翻译)成中文。**

由于 [Chrome 浏览器](https://www.iplaysoft.com/google-chrome.html)翻译功能经常会受到网络的干扰出现 “由于[服务器](https://www.iplaysoft.com/tag/服务器)出错，翻译失败” 错误且 iOS 版没有，因此我特意找来更多的替代方案如**必应翻译和有道翻译的 Bookmarklet (书签工具)**，重点在于，它们不仅可在电脑上各种不同浏览器使用，而且还能让手机、平板浏览器都能加上[网页翻译](https://www.iplaysoft.com/translate-bookmarklet.html)的功能！真心实用……

### 先说说什么是 Bookmarklet (收藏夹 / 书签工具)：


说到 Bookmarklet (书签工具)，其实就是一段保存在书签里的 [Javascript](https://www.iplaysoft.com/tag/javascript) 代码，平时我们打开一个网页时，点击收藏夹里的某个书签的话（譬如你之前收藏了[异次元](https://www.iplaysoft.com)），那么这个页面就会跳转到异次元的网站去了，而 Bookmarklet 则是直接在当前的网页中执行书签里保存的那段 JS 代码。我们网站之前就发布过一个[可以解除网页右键复制文字限制的书签小工具](https://www.iplaysoft.com/po-jie-fu-zhi-bookmarklet.html)，我们一般将这些带有功能性的书签叫做 Bookmarklet 或者书签小工具。

[![](https://img.iplaysoft.com/wp-content/uploads/2013/translate-bookmarklet/translate-web-pages-on-mobile-phone.png)](https://www.iplaysoft.com/go/amazonus)  
「使用网页翻译书签小工具在手机浏览器上也能很方便地将网页翻译成中文了！」

虽然像 [iOS](https://www.iplaysoft.com/tag/ios) 上的 Safari、Chrome 或 [Android](https://www.iplaysoft.com/tag/android) 等手机平台上的各种浏览器目前基本上都没多少能像电脑的一样可以支持扩展或[插件](https://www.iplaysoft.com/tag/插件)的，然而幸运的是，我发现他们大多都可以使用 Bookmarklet！虽然 Bookmarklet 的功能并没有扩展那么强大和丰富，但终究可以让手机的浏览器做上更多的事情，譬如今天介绍的**给手机浏览器增加网页[翻译](https://www.iplaysoft.com/tag/翻译)功能**，如上图。

### 怎样安装使用：

下面的 Bookmarklet 在电脑、[手机](https://www.iplaysoft.com/tag/手机)、平板等各种浏览器上一般都能支持，所以如果大家需要在任何地方使用网页翻译功能，那么都可以试试。要安装它们，可以有很多种方法，一般在电脑的浏览器上，直接将它们的链接拖放到浏览器的书签栏即可 (Chrome 使用快捷键 Ctrl+Shift+B 可显示书签栏)。

在手机或平板上，你可以先随便收藏一个网页 (加一个[书签](https://www.iplaysoft.com/tag/书签))，然后再去修改该书签的名称与网址，将其中网址替换成下面对应的[代码](https://www.iplaysoft.com/tag/代码)即可。个人建议，可以使用 Chrome 或者 Safari 的书签[同步](https://www.iplaysoft.com/tag/同步)功能，在电脑上弄好，直接就能再移动平台上使用了。

下面的[网页翻译书签工具](https://www.iplaysoft.com/translate-bookmarklet.html)都能支持多国语言的翻译，譬如[英文](https://www.iplaysoft.com/tag/英语)、法文、日文、德文、韩文、西班牙文等等，从此手机上网可以通行全天下了，哈哈！

### 网页翻译 Bookmarklet 代码：

**必应翻译 Bookmarklet （任何语言翻译成简体中文、繁体中文、英文）：**

> 必应翻译 (中文) << 拖放到浏览器收藏夹或工具栏即可，或将下面代码作为网址保存成书签  
> javascript:(function(){var s = document.createElement('script'); s.type = 'text/javascript'; s.src = 'http://labs.microsofttranslator.com/bookmarklet/default.aspx?f=js&to=zh-chs'; document.body.insertBefore(s, document.body.firstChild);})()
> 
> 必应翻译 (繁中)  
> javascript:(function(){var s = document.createElement('script'); s.type = 'text/javascript'; s.src = 'http://labs.microsofttranslator.com/bookmarklet/default.aspx?f=js&to=zh-cht'; document.body.insertBefore(s, document.body.firstChild);})()
> 
> 必应翻译 (英文)  
> javascript:(function(){var s = document.createElement('script'); s.type = 'text/javascript'; s.src = 'http://labs.microsofttranslator.com/bookmarklet/default.aspx?f=js&to=en'; document.body.insertBefore(s, document.body.firstChild);})()

**有道翻译 Bookmarklet (任何语言翻译成简体中文)：**

> 有道翻译
> 
> javascript: void((function() {var element = document.createElement('script');element.id = 'outfox_seed_js';element.charset = 'utf-8',element.setAttribute('src', 'http://fanyi.youdao.com/web2/seed.js?' + Date.parse(new Date()));document.body.appendChild(element);})())

**Google 谷歌翻译 Bookmarklet （任何语言翻译成简体中文）：**

> 这个可以让非 Chrome 浏览器也拥有谷歌翻译功能了，呵呵。不过网络偶尔还是个问题。
> 
> 谷歌翻译 (中文)
> 
> javascript:var t=((window.getSelection&&window.getSelection())||(document.getSelection&&document.getSelection())||(document.selection&&document.selection.createRange&&document.selection.createRange().text));var e=(document.charset||document.characterSet);if(t!=''){location.href='http://translate.google.com/?text='+t+'&hl=zh-CN&langpair=auto|zh-CN&tbb=1&ie='+e;}else{location.href='http://translate.google.com/translate?u='+encodeURIComponent(location.href)+'&hl=zh-CN&langpair=auto|zh-CN&tbb=1&ie='+e;};

**Google 谷歌翻译 Bookmarklet （任何语言翻译成繁体中文）：**

> 谷歌翻译 (繁中)
> 
> javascript:var t=((window.getSelection&&window.getSelection())||(document.getSelection&&document.getSelection())||(document.selection&&document.selection.createRange&&document.selection.createRange().text));var e=(document.charset||document.characterSet);if(t!=''){location.href='http://translate.google.com/?text='+t+'&hl=zh-CN&langpair=auto|zh-TW&tbb=1&ie='+e;}else{location.href='http://translate.google.com/translate?u='+encodeURIComponent(location.href)+'&hl=zh-CN&langpair=auto|zh-TW&tbb=1&ie='+e;};

**Google 谷歌翻译 Bookmarklet (任何语言翻译成英文)：**

> 谷歌翻译 (英文)
> 
> javascript:var t=((window.getSelection&&window.getSelection())||(document.getSelection&&document.getSelection())||(document.selection&&document.selection.createRange&&document.selection.createRange().text));var e=(document.charset||document.characterSet);if(t!=''){location.href='http://translate.google.com/?text='+t+'&hl=zh-CN&langpair=auto|en&tbb=1&ie='+e;}else{location.href='http://translate.google.com/translate?u='+encodeURIComponent(location.href)+'&hl=zh-CN&langpair=auto|en&tbb=1&ie='+e;};

### 手机版 Chrome 浏览器怎样使用 Bookmarklet 的方法：

由于[手机版的 Chrome 浏览器](https://www.iplaysoft.com/chrome-mobile.html)在点击书签后会打开新的网页而不能正确执行其中的代码，我尝试了一番终于找到可行的办法了！因为 Chrome 的地址栏是带有搜索书签功能的，譬如我们的想使用名为 “必应翻译” 的 Bookmarklet，那么只需在地址栏中输入必应，然后找到地址是 javascript: 开头的那个书签点击即可成功调用了！为方便使用，大家可以将书签改成英文如 Bing2Cn 或 Bing2En，输入时只需输入部分字符即可匹配出来。此方法在 [iPhone](https://www.iplaysoft.com/go/iphone)/[iPad](https://www.iplaysoft.com/go/ipad) 版的 Chrome 实测可行，Android 未测。

![](https://img.iplaysoft.com/wp-content/uploads/2013/translate-bookmarklet/chrome-bookmarklet.png)

而其他浏览器如 iOS 中的 Safari，一般只需像平常那样打开书签栏，点击书签即可。更多的浏览器大家自行测试一下吧，我就不花时间一一测试了。

### 最后：

OK，基本上就是这样了，当你弄好这些书签之后，在上网时需要[翻译网页](https://www.iplaysoft.com/translate-bookmarklet.html)时，不管你用的是什么平台什么设备，只要打开你的浏览器收藏夹，点击对应的翻译书签工具即可。如果这篇文章对你有帮助，希望你多多推荐本站给您的朋友认识哦！

如果你还有一些好用或够酷的 [Bookmarklet](https://www.iplaysoft.com/tag/bookmarklet)，欢迎推荐分享出来给我们收录方便更多人！
