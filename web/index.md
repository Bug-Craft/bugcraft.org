# 网页版服务器状态报告
> ㅤㅤ以下是网页版服务器的状态。需要刷新页面才可以看到最新的服务器状态。有时，需要等待一段时间才能够从服务器获取状态信息。
ㅤㅤ如果不能显示相关信息，则说明你的浏览器可能无法与网页版服务器正常地建立连接。这不一定是你的问题，当然也不一定是我们的问题。

ㅤㅤ如果你设备上的浏览器支持 `WebGL 2.0` ，那么你将可以使用网页版来连接这个服务器。推荐使用 [Google Chrome](https://www.google.cn/intl/zh-CN/chrome/) 来通过网页版加入。
ㅤㅤ此版本为 PBR 光影版本，默认语言为中文（简体），光影需要在 “选项” 中开启。关于语言支持，它支持 Minecraft Java 1.8 版本所支持的所有语言。 

### OpenFrp 通道（ws://cn-fz-plc-1.openfrp.top:18000/server）
<div id="openfrp"></div>
ㅤㅤ

ㅤㅤ点击下面的链接以通过 OpenFrp 加入我们的网页版服务器。

http://cn-fz-plc-1.openfrp.top:18000/client/?server=ws://cn-fz-plc-1.openfrp.top:18000/server
ㅤㅤ
### Kaifuxia 通道（ws://e2.kaifuxia.com:11273/）

<div id="kaifuxia"></div>
ㅤㅤ

ㅤㅤ点击下面的链接以通过 Kaifuxia 加入我们的网页版服务器。

http://cn-fz-plc-1.openfrp.top:18000/client/?server=ws://e2.kaifuxia.com:11273/

ㅤㅤ
ㅤㅤ上面的快捷链接将在你的浏览器中启动网页客户端，并在你填写好 BugID、设置好皮肤，然后点击 “完成” 后自动加入与上面的标题对应的服务器。目前，**这种加入方式仅支持使用鼠标和键盘来进行操作。**

ㅤㅤ想要在自己的网页上嵌入 BugCraft 的服务器状态？请参考[这个 GitHub 存储库](https://github.com/lax1dude/eaglercraft-HTML5_Ping_Embed)。注意：显示 BugCraft 服务器状态的网页必须运行在 HTTP 上或者直接存储在文件中，因为 HTTPS 只会允许 WSS 连接。 

ㅤㅤ网页版基于 EaglercraftX 1.8，所以你也可以使用其它版本加入我们的网页版服务器，即使并不是我们提供的 EaglercraftX 版本。当然，作弊客户端除外，无论是否为网页版本，我们都不建议你使用。

ㅤㅤ此页面由 Ygbs 于二〇二三年六月十九日编写。感谢你的阅读。

<script type="text/javascript" src="embed.js"></script>
<script>
	var embed = new ServerEmbed(document.getElementById("openfrp"), "100%");
	embed.ping("ws://cn-fz-plc-1.openfrp.top:18000/server");
	var embed = new ServerEmbed(document.getElementById("kaifuxia"), "100%");
	embed.ping("ws://e2.kaifuxia.com:11273/");
</script>
