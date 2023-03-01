# 常见问题

## TuneFlow 在哪里使用/下载?

TuneFlow 网页版地址: [https://www.tuneflow.com](https://www.tuneflow.com)

桌面版下载也在首页。

## TuneFlow 打不开/打开很慢/无法下载/桌面版卡在初始界面

如果在网页版出现这种问题，可能是浏览器兼容性导致的。你可以尝试使用兼容性更高的浏览器，推荐使用谷歌 Chrome 来打开网站。

如果是桌面版出现该问题，可能是第一次打开时网速较慢导致的，可以尝试关闭后重开一遍。

## 安装遇到问题

### Windows Defender 阻止我安装/运行 TuneFlow

如果你在安装 TuneFlow 时看到如下信息，请点击 "更多信息" 并选择 "仍要运行"。

![Windows Defender](../images/windows_defender_example.png)

出现这个提示信息是因为我们刚刚重新续签了代码签名证书，Windows Defender 需要足够多的运行次数来对新的证书建立信任。

## 我在 TuneFlow 上生成的曲子可以商用吗？需要注明出处吗？

请参见 [版权与许可](https://help.tuneflow.com/zh/terms-of-service/license.html)。

## 我发现生成的曲子跟某一首曲子很相似

TuneFlow 的 AI 模型是从大量现有的音乐作品学习而来，尽管我们已经采用了大量可能是业界最先进的查重措施，但仍然不能完全避免漏网之鱼。据我们所知，这仍是一个 AI 生成方向无法完全避免的问题。

如果你发现了疑似与已有歌曲相似的生成曲目，请点击帮助菜单中的`报告歌曲问题`，或者直接与我们取得联系。

## 桌面版没有扫描出我的 VST2 插件

TuneFlow 默认只扫描最优先的插件类型，如果没有发现某种类型的插件，可以点击“主菜单->设置->管理音频插件->扫描 XXX 插件”扫描需要的插件类型。

## macOS 版本扫描插件时卡在了 `DLSMusicDevice`

有可能是因为同时开启了其他 DAW 造成的，可以关闭其他 DAW 之后重试。

## 在哪里可以给你们提建议？

可以发邮件至我们的[邮箱](mailto:contact@info.tuneflow.com)，或者给我们的[B 站账号](https://space.bilibili.com/512426691)发站内信。
