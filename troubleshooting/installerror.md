# 安装错误

本文仅收集常见的安装错误。

## 软件包签名与已安装应用程序的签名不一致

备份数据并完全卸载应用程序，然后重新安装新版应用程序。

> 卸载应用程序前请务必备份`/storage/emulated/0/.TGPhiEdit`目录。
>
> 如果有必要，甚至需要重新获取解密码。

## 安装包损坏

删掉刚才下载的安装包，去群里重新下载一个。

## “xxx”被禁止安装应用/已拒绝“xxx”安装应用

请检查你的手机是否允许外部来源应用，以下段落仅显示Color OS 15的解决方案。

“设置” > “密码与安全” > “系统安全” > “外部来源应用”

## 解析软件包时出现问题

> [!TIP]
>
> MixerWangDev个人偏见：
> 
> Godot引擎官方建议在Android 9（或者更新）设备上安装运行，如果遇到这个错误请直接查看你设备的Android版本。
>
> 不建议在HarmonyOS NEXT设备上使用卓易通（或者出境易）安装TPhi Editor，具体情况请参考Godot官方在GitHub的issues [#12734](https://github.com/godotengine/godot-proposals/issues/12734) [#10067](https://github.com/godotengine/godot-proposals/discussions/10067)
>
> 关于鸿蒙操作系统的问题请直接询问cmdysj（请勿询问TG铁锅炖大鹅）。
>
> 如果你正在使用HarmonyOS NEXT设备并且恰好没有安装卓易通（或者出境易）无法打开apk文件，则只能更换设备（华为和鸽游的原因没办法）。

带着你的手机型号直接反馈到群内以更新最低要求。

## 被要求实名验证/需要登录才能安装/需要联网才能安装（其他理由）

按报错信息的要求去做即可（情况比较复杂）。

华为用户遇到类似错误的请看[此处](https://consumer.huawei.com/cn/support/content/zh-cn15990893/)。

## 未退出谷歌账号导致无法安装TPhi Editor

参考这里的[解决方案](https://zhuanlan.zhihu.com/p/22363155451)。

> [!WARNING]
>
> 如果刚买来的手机遇到了类似的错误，不要继续，而是直接联系店家要求退货（不是登录谷歌账号）。任何尝试强制安装的行为都有可能导致不可逆的后果。

## 您的IT管理员禁止安装应用

没有针对这个错误的解决方法，建议更换设备。

> [!ATTENTION]
> 
> 请勿要求IT管理员为你的设备部署TPhi Editor，尽管TPhi Editor本身是专为移动设备写谱而设计的（如果是批量部署）。
>
> 如果你是IT管理员，请严格按照所在的企业规章制度。

感兴趣的在[这里](https://support.google.com/a/answer/9997133?hl=zh-Hans)了解。

## 打开apk文件时没有调出数据包安装程序

这种情况特定于一部分的华为手机（已安装HarmonyOS NEXT），这种情况只能更换设备。（参考“解析软件包时出现问题”）

然而一个例外是安装了ChromeOS的桌面电脑（不同于fydeOS），**ChromeOS Flex无法直接安装安卓应用**，如果你的电脑不小心安装了这个操作系统**建议设置Linux容器并使用Phichain**（以实现曲线救国）。
