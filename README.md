# CardHub · 发布通道

本仓库只承载 **CardHub 桌面应用的发布产物**（GitHub Releases）：

- `CardHub-Setup-x.y.z.exe` — Windows 安装包
- `latest.yml` + `.blockmap` — 自动更新清单与差量更新索引

## 用户

到 [Releases 页面](https://github.com/TookuW/NamecardHub-Release/releases) 下载最新的 `CardHub-Setup-*.exe` 安装即可。
应用启动后会自动检查更新并后台下载，无需手动回来下载新版本。

## 开发者

源码在私有仓库 `TookuW/Namecardhub-private`。发布流程：打 tag `v*` → Actions 自动构建并上传到本仓库的 Release。
