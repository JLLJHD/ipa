# 优恩德 iOS 安装

在 iPhone 的 Safari 中打开 [优恩德安装页面](https://jlljhd.github.io/ipa/)，点击「安装优恩德」。需要 iOS 18.6 或更高版本。

- [安装清单](https://raw.githubusercontent.com/JLLJHD/ipa/main/manifest.plist)
- [下载 IPA](https://raw.githubusercontent.com/JLLJHD/ipa/main/youende-enterprise-1.0.ipa)
- Bundle ID：`guibai.youende`
- 版本：`1.0`（Build `1`）
- SHA-256：`a0af934e9ced541a7db45cc78eb4f17815ef929b188f71eee596927bd3d4ffca`

Safari 安装协议地址：

```text
itms-services://?action=download-manifest&url=https%3A%2F%2Fraw.githubusercontent.com%2FJLLJHD%2Fipa%2Fmain%2Fmanifest.plist
```

网站通过 `gh-pages` 分支发布。更新后同步发布：

```sh
git push origin main
git push origin main:gh-pages
```

IPA 保留上传者提供的原始签名；文件托管成功不代表真机签名验证通过。如果提示开发者不受信任，按 iOS 的指引在「设置 → 通用 → VPN 与设备管理」中验证对应开发者；如提示无法验证或完整性错误，应检查签名、证书和描述文件。
