# Proxyfree

代理客户端、公开订阅与网络工具索引

按设备找客户端，按用途找工具。这里收集项目与下载入口；公开订阅由第三方维护，可用性、安全性和更新频率会变化。使用前请核对来源，并遵守所在地法律与服务条款。

**快速导航：** [客户端](#代理客户端) · [公开订阅](#公开订阅与服务) · [Shadowrocket](#shadowrocket-配置与规则) · [OpenWrt](#openwrt-与软路由) · [Telegram](#telegram-相关资源) · [在线工具](#在线工具)

## 代理客户端

先按设备选软件，再到项目发布页下载适合系统和处理器的安装包。表格表示项目提供对应平台版本，不代表每个版本或设备都能正常运行。

| 客户端 | Windows | macOS | Linux | iOS | Android | 说明 |
| --- | :---: | :---: | :---: | :---: | :---: | --- |
| [Clash Verge Rev](https://github.com/clash-verge-rev/clash-verge-rev/releases) | ✅ | ✅ | ✅ | — | — | 桌面客户端 |
| [v2rayN](https://github.com/2dust/v2rayN/releases) | ✅ | ✅ | ✅ | — | — | 桌面客户端 |
| [Sparkle](https://github.com/xishang0128/sparkle/releases) | ✅ | ✅ | ✅ | — | — | 桌面客户端 |
| [Clash Party](https://github.com/mihomo-party-org/clash-party/releases) | ✅ | ✅ | ✅ | — | — | 桌面客户端 |
| [FlClash](https://github.com/chen08209/FlClash/releases) | ✅ | ✅ | ✅ | — | ✅ | 跨平台客户端 |
| [Karing](https://karing.app/quickstart/) | ✅ | ✅ | ✅ | ✅ | ✅ | 跨平台客户端 |
| [Hiddify](https://github.com/hiddify/hiddify-app/releases) | ✅ | ✅ | ✅ | ✅ | ✅ | 跨平台客户端 |
| [Shadowrocket](https://apps.apple.com/bo/app/shadowrocket/id932747118?l=en) | — | — | — | ✅ | — | App Store 地区与价格请以商店页面为准 |
| [ClashBar](https://github.com/Sitoi/ClashBar/releases) | — | ✅ | — | — | — | macOS 菜单栏客户端 |

还有一份[第三方软件汇总](https://huarun.win/)，下载前请优先核对项目官方页面。

> **关于 TUN：** 原文建议将栈模式设为 `System`。实际速度取决于系统、网络和节点，遇到问题时再对照客户端文档调整，不宜把它当成通用提速开关。

## 公开订阅与服务

这些链接来自不同维护者，本仓库没有验证节点质量或持续可用性。导入配置前请检查来源；不要在未知订阅中填写账号或敏感信息。

| 资源 | 类型 |
| --- | --- |
| [bsbb.cc](https://www.bsbb.cc/) | 第三方公开资源 |
| [OpenProxyList](https://openproxylist.com/) | 第三方公开资源 |
| [anaer/Sub 订阅](https://anaer.github.io/Sub/clash.yaml) | Clash 配置地址 |
| [anaer/Sub 镜像](https://cdn.jsdelivr.net/gh/anaer/Sub@main/clash.yaml) | 同一项目的镜像地址 |
| [OpenRung](https://openrung.org/zh/#top) · [源码](https://github.com/openrung/openrung) | 独立项目，使用方式以其官网为准 |
| [付费服务入口](https://77.dqtx.cc/) | 第三方付费服务 |

## Shadowrocket 配置与规则

### HTTPS 解密与广告过滤

以下是原作者的自用配置入口：[融合模块](https://9lnk.io/0ijs) · [视频广告模块](https://9lnk.io/d6O0) · [规则项目](https://github.com/Johnshall/Shadowrocket-ADBlock-Rules-Forever)。模块来自第三方，请先阅读内容及权限说明，再决定是否启用。

在 Shadowrocket 中，可从配置详情进入 HTTPS 解密设置，生成并安装 CA 证书，然后在系统设置中信任该证书。**启用 HTTPS 解密会扩大对设备流量的访问范围**；只在理解模块来源和用途时启用，不再需要时移除证书和对应模块。

## OpenWrt 与软路由

以下是 LuCI 主题项目，并非代理客户端：

- [luci-theme-aurora](https://github.com/eamonxg/luci-theme-aurora)
- [luci-theme-design](https://github.com/SAENE/luci-theme-design)

## Telegram 相关资源

- Android 客户端：[Telegram X](https://github.com/TGX-Android/Telegram-X/releases) · [Forkgram](https://github.com/forkgram/TelegramAndroid/releases)。安装第三方客户端前请核对维护者和权限。
- [Telegram 语言包](https://t.me/setlanguage/classic-zh-cn)
- 群组与机器人索引：[telegram-mop](https://telegram-mop.869hr.uk/) · [tmeseoi](https://github.com/tmeseoi/telegram.github.io) · [TelegramGroup](https://github.com/itgoyo/TelegramGroup) · [TelegramBot](https://github.com/itgoyo/TelegramBot)
- 可在 Telegram 的隐私与安全设置中查看是否提供 Passkey 登录；具体入口以当前客户端版本为准。

旧版 README 中关于短信收费绕过、强制重启跳过验证和替换浏览器关联文件的做法缺乏稳定性验证，也可能带来账号或设备风险，因此不作为操作指南保留。

## 在线工具

| 用途 | 链接 |
| --- | --- |
| IP 信息 | [IP 查询](https://iplark.com/) · [IP 类型与风险值](https://ping0.cc/) |
| 网络测速 | [Speedtest](https://www.speedtest.net/zh-Hans) |
| 临时邮箱 | [Temp Mail](https://temp-mail.org/zh/) |
| 密码生成 | [随机密码生成器](https://key.dqtx.cc/) |
| 地址样例 | [美国地址生成器](https://usaddressgen.com/) |
| 双因素验证 | [2FA 工具](https://2fa.run/) |
| 下载辅助 | [GitHub 下载加速](https://yishijie.gitlab.io/ziyuan/) |
| 短信接码 | [SMS Activate](https://sms-activate.guru/?ref=12307132)；不建议用于重要账号 |

第三方工具的可用性与隐私政策可能变化，请以各网站当前说明为准。
