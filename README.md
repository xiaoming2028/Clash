# Clash官网各个版本 Clash客户端下载地址指南2026，Windows、Mac、Android和iOS版本怎么选 

> 更新于 2026 年 9 月

找 Clash 客户端，先确认系统和芯片架构，再挑一款合适的软件。Windows可以从Clash Verge Rev开始，想在电脑和安卓上使用相近界面，可以看FlClash；iPhone、iPad则查看对应的App Store应用。新手先完成一次订阅导入，比反复比较软件名称更有用。

下面的链接来自各项目开发者的 GitHub 发布页和 App Store。安装客户端后，还需要导入可用的订阅或节点配置。**已有订阅可以直接下载并导入，没有订阅再看后面的机场选择。**

## 按设备快速找到Clash下载地址

| 你的设备                      | 可以先选                       | 下载入口                                                     |
| ----------------------------- | ------------------------------ | ------------------------------------------------------------ |
| Windows，Intel或AMD的64位电脑 | Clash Verge Rev 2.5.2          | [Windows x64安装包](https://github.com/clash-verge-rev/clash-verge-rev/releases/download/v2.5.2/Clash.Verge_2.5.2_x64-setup.exe) |
| Windows，ARM64电脑            | Clash Verge Rev 2.5.2          | [Windows ARM64安装包](https://github.com/clash-verge-rev/clash-verge-rev/releases/download/v2.5.2/Clash.Verge_2.5.2_arm64-setup.exe) |
| Mac，Apple M系列芯片          | FlClash 0.8.96                 | [Mac M系列芯片安装包](https://github.com/chen08209/FlClash/releases/download/v0.8.96/FlClash-0.8.96-macos-arm64.dmg) |
| Mac，Intel芯片                | FlClash 0.8.96                 | [Mac Intel安装包](https://github.com/chen08209/FlClash/releases/download/v0.8.96/FlClash-0.8.96-macos-amd64.dmg) |
| Android，64位ARM系统          | FlClash 0.8.96                 | [Android arm64-v8a安装包](https://github.com/chen08209/FlClash/releases/download/v0.8.96/FlClash-0.8.96-android-arm64-v8a.apk) |
| Android，不确定该选哪种架构   | Clash Meta for Android 2.11.33 | [Android通用安装包](https://github.com/MetaCubeX/ClashMetaForAndroid/releases/download/v2.11.33/cmfa-2.11.33-meta-universal-release.apk) |
| iPhone或iPad                  | Clash Mi                       | [Clash Mi美区App Store页面](https://apps.apple.com/us/app/clash-mi/id6744321968) |
| Linux桌面                     | FlClash或Clash Verge Rev       | [FlClash发布页](https://github.com/chen08209/FlClash/releases/latest) · [Clash Verge Rev发布页](https://github.com/clash-verge-rev/clash-verge-rev/releases/latest) |

不确定电脑架构时，Windows可以在系统设置的“关于”中查看“系统类型”；Mac在“关于本机”中查看芯片或处理器。Android通用包能减少选错架构的麻烦，但仍需满足应用的系统版本要求。

已有订阅，可以继续看[Clash订阅导入步骤](#clash下载后怎么导入订阅)。还没有可用节点，可以先了解[机场订阅怎么选](#还没有clash订阅机场怎么选)。

## Windows版Clash怎么选

**Clash Verge Rev适合希望按完整文档安装、导入和排错的人。** 它基于Tauri，内置Mihomo内核，提供订阅管理、规则编辑、系统代理和TUN模式等功能。这些功能不必第一天全部打开，先完成订阅导入和基本连接即可。

下载时看清文件名里的`x64`或`arm64`，首次安装通常选择以`setup.exe`结尾的文件。带`fixed_webview2`的包用于相应WebView2环境问题，不需要默认下载体积更大的这一版。Windows 7也不在现行版本的支持范围内。

**FlClash也是可选的Windows客户端。** 它覆盖Windows、macOS、Android和Linux，适合希望不同设备保持相近操作习惯的人。Windows版目前提供安装包和ZIP包，第一次使用更容易从安装包开始。

需要更新版本时，进入[Clash Verge Rev最新发布页](https://github.com/clash-verge-rev/clash-verge-rev/releases/latest)或[FlClash最新发布页](https://github.com/chen08209/FlClash/releases/latest)，展开`Assets`查找对应安装包。`Source code`是源码压缩包，普通安装不需要下载它。

## Mac版Clash要区分Intel和M系列芯片

上表给了FlClash的两种Mac安装包。Apple M系列选择`arm64`，Intel选择`amd64`。Clash Verge Rev也有Mac版本，其包名对应`aarch64`和`x64`，可以在[Mac与其他平台发布页](https://github.com/clash-verge-rev/clash-verge-rev/releases/latest)中选择。

喜欢菜单栏操作方式，还可以查看[ClashX.Meta发布页](https://github.com/MetaCubeX/ClashX.Meta/releases/latest)。本次核对的版本是1.4.44，下载文件名为`ClashX.Meta.zip`。注意核对完整项目名称，ClashX与ClashX.Meta不应混成同一个下载来源。

芯片架构匹配以后，还要确认客户端要求的最低macOS版本。尤其是旧系统，不要仅凭文件扩展名是DMG就认定能够安装。遇到安全提示，先核实来源和开发者说明，不要直接复制网上关闭系统安全检查的命令。

## Android版Clash下载，arm64还是通用包

安卓可以在FlClash和Clash Meta for Android之间选择，后者常简称CMFA。上表提供了FlClash的64位ARM包，以及CMFA的通用包。

如果需要其他架构，打开[FlClash Android发布页](https://github.com/chen08209/FlClash/releases/latest)或[CMFA发布页](https://github.com/MetaCubeX/ClashMetaForAndroid/releases/latest)。`armeabi-v7a`对应32位ARM，`arm64-v8a`对应64位ARM，`x86`或`x86_64`用于相应架构的设备或模拟器。文件名中的`universal`表示覆盖多种架构。

安装后，启动代理时可能出现系统VPN连接授权。先确认请求来自刚安装的客户端，再按系统提示操作。如果APK提示无法安装，优先核对系统版本、架构和是否与已安装版本存在签名冲突，不要反复下载来历不明的修改版。

## iPhone和iPad怎么下载Clash相关客户端

**Clash Mi基于Mihomo内核。** 本次核对时，美区商店标注免费下载，可以从上表的App Store入口查看。[Clash Mi应用说明](https://apps.apple.com/us/app/clash-mi/id6744321968)

**Shadowrocket是另一款独立代理客户端。** 如果订阅服务提供了Shadowrocket专用导入方式，可以考虑它。本次核对时，美区售价为US$2.99，购买应用与购买线路订阅是两笔费用。[Shadowrocket美区App Store页面](https://apps.apple.com/us/app/shadowrocket/id932747118)

这两个链接指向美区商店，能否获取及最终价格以你自己的商店地区和页面显示为准。不要把Apple账户密码交给代装人员，也不要默认把Clash格式的完整配置原样导入每一种iOS客户端，应选择服务商提供的对应格式。

## Linux下载DEB、RPM还是AppImage

Debian、Ubuntu等系统通常选择DEB包，Fedora等系统通常选择RPM包。还需要区分`amd64`、`x86_64`与`arm64`等架构标记。

本次核对的FlClash发布页包含amd64的DEB、RPM和AppImage，以及arm64的DEB。不同架构不一定拥有相同格式的安装包，下载前以实际文件列表为准。依赖安装可参考[FlClash使用说明](https://github.com/chen08209/FlClash/blob/main/README_zh_CN.md)；Clash Verge Rev用户可看[Linux安装说明](https://www.clashverge.dev/install.html)。

## Clash下载后怎么导入订阅

**客户端负责管理配置和使用节点，安装完成不会自动获得线路。** 如果你已经有可用的机场订阅或自建配置，不需要为了换客户端再买一份。

下面以Clash Verge Rev为例，其他客户端的按钮名称会有差别。

1. **取得兼容的订阅链接。** 在自己的服务后台选择Clash或Mihomo对应格式，复制完整订阅地址。不要复制账户登录页地址。
2. **导入并启用配置。** 在客户端的订阅管理处粘贴地址并导入，完成后应能看到一份订阅配置。选择并启用这份配置，再查看代理组和节点是否出现。
3. **选择节点和运行模式。** 先选一条准备使用的节点，普通浏览可以从规则模式开始。仅有节点列表，还不代表应用流量已经经过代理。
4. **开启系统代理并实际访问。** 在客户端打开系统代理，测试自己常用的网站。需要接管不遵循系统代理的程序时，再按文档了解TUN模式及权限要求。

界面操作可以对照开发者提供的[订阅导入说明](https://www.clashverge.dev/guide/profile.html)和[快速入门图解](https://www.clashverge.dev/guide/quickstart.html)。这部分按文档整理，不代表对每个平台都完成了实机测试。

订阅地址通常带有账户凭证。不要公开到评论区，不要提交给来源不明的在线订阅转换网站。需要截图求助时，遮住链接和账户信息。

## 还没有Clash订阅，机场怎么选

已经有可用订阅，按前面的步骤导入即可。**还没有节点的，可以先注册查看自己需要的地区和套餐，再决定是否购买。** 这里保留TAG和快雷GO两种选择，分别对应不同需求，不需要一起买。

### TAG，适合需要多个地区和不同出口的人

我把TAG留作主用选择，看重的是地区覆盖和不同出口的选择空间。日常使用常见地区，偶尔还需要冷门地区、家宽或原生IP，可以先看它。只用香港、日本等少数地区，预算又很紧，就不必为自己用不到的节点资源多花钱。

购买前确认需要的地区是否在所选套餐内，同时核对流量、节点倍率和客户端兼容性。我的选择方法是先买可接受的短周期，在自己的网络下测试常用网站和晚高峰，再决定是否续费。更多判断见[TAG长期使用与套餐评测](https://github.com/xiaoming2028/TAG-VPN)。

👉 <a href="https://570836.l49.net/#/auth/d2RtVGgb" rel="sponsored nofollow"><strong>点击进入TAG官网选购套餐（支持支付宝和微信）</strong></a>

### 快雷GO，适合电信晚高峰的人

快雷GO我从2024年底开始用。它的节点数量不算多，但常用地区能够覆盖我的日常需求，电信方向优化后的体验也有改善。如果你的用途主要集中在常见地区，又在意电信晚高峰表现，可以选它。需要大量冷门出口的人，选TAG会更合适。

选快雷GO套餐，我会先把设备数和流量放在一起看。个人日常使用先比较中包，多设备或视频、下载用量较大时再看大包；确实只有一两台设备、用量很少，小包也可以考虑。各档同时使用额度和节点倍率要在购买前核对，不能只按套餐名称或纸面流量决定。

👉 <a href="https://www.kuaileigo.top/register?code=tNhxxKq0" rel="sponsored nofollow"><strong>点击进入快雷GO官网选购套餐（支持支付宝和微信）</strong></a>

## Clash下载与使用常见问题

### Clash官网到底是哪一个

这份清单包含多个开发者维护的客户端，应该按完整项目名称找对应发布源。Clash Verge Rev、FlClash、ClashX.Meta和Clash Meta for Android各有自己的项目地址。下载时核对域名、项目维护者和文件名，不要仅凭网页标题写着“官网”就判断来源。

### Clash for Windows和旧版Clash Verge还能下载吗

搜索中仍可能出现历史安装包。原版[Clash Verge项目](https://github.com/zzzgydi/clash-verge)已经归档；Clash for Windows的[Flathub发行维护记录](https://github.com/flathub/io.github.Fndroid.clash_for_windows)也已标记EOL。历史文件还能找到，不等于仍在维护。

新用户可以先选择本文前面列出的客户端。需要保留旧版本处理已有配置时，单独核实来源、兼容性和迁移方式，不要把旧版镜像误认为当前开发者发布渠道。

### GitHub下载页打不开怎么办

先检查网络能否访问项目页面，也可以从项目文档寻找开发者明确列出的其他渠道。镜像属于另一份分发来源；使用前核对版本及官方校验信息，不能把“链接能打开”当成安全证明。

FlClash本次发布附有`SHA256SUMS`，可用于核对下载文件与发布方提供的哈希是否一致。校验一致能帮助检查文件完整性，但不等于完成软件安全审计。[FlClash发布文件列表](https://github.com/chen08209/FlClash/releases/tag/v0.8.96)

### 导入订阅后没有节点，是客户端坏了吗

先检查是否复制了完整订阅链接、格式是否兼容、配置是否已经启用，以及服务是否到期或流量耗尽。有明确错误提示时，保留错误文字，按客户端文档或服务商说明排查。证书报错时先核对地址、系统时间并联系服务方，不要把关闭证书验证当成默认解决办法。

### 换一个Clash客户端，速度会更快吗

客户端会影响协议兼容、路由和代理模式，但网速还受本地网络、线路负载及出口状态影响。先检查客户端是否正常工作，再在相同网络和时段比较节点。没有定位原因前，反复换软件或重复买订阅都可能白费工夫。

## 推荐阅读：

- [TAG 机场多年使用和套餐评测](https://github.com/xiaoming2028/TAG-VPN)
- [WgetCloud 两年使用和套餐评测](https://github.com/xiaoming2028/WgetCloud)
- [MESL 节点、家宽 IP 和流媒体评测](https://github.com/xiaoming2028/MESL)
- [红杏云套餐、多设备和客户端评测](https://github.com/xiaoming2028/hongxingyun)
- [狗狗加速怎么样？狗狗加速机场官网地址](https://github.com/xiaoming2028/DogDogGo)
