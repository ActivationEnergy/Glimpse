# 一瞥 · Glimpse

给闲暇，留一点诗意。闲置时作诗画屏保，或选择在解锁后停留片刻；想读时，打开一瞥。

[产品介绍、安装与完整设置指引](https://activationenergy.github.io/Glimpse/#guide)

## 1.1.1 公开测试版

[下载 Mac 通用安装包](https://github.com/ActivationEnergy/Glimpse/raw/refs/tags/v1.1.1/Releases/v1.1.1/Glimpse-1.1.1-macOS-universal.dmg) · [校验值](Releases/v1.1.1/SHA256SUMS)

适用于 macOS 14 及以上，Apple Silicon／Intel 通用。包含 1,105 篇目录作品、24 组离线核心配景；两组扩展默认不下载。

也可使用 Homebrew：

```sh
brew install --cask activationenergy/tap/glimpse
# 已安装时
brew update
brew upgrade --cask activationenergy/tap/glimpse
```

## 先选择一种展示方式

- **闲置时，作为屏保**：在 App 中安装／更新屏保，再到系统设置选择“一瞥诗词”。屏保启动应早于显示器关闭；退出 App 后仍可展示，解锁后直接回到工作界面。
- **解锁后，停留片刻**：先在系统设置改用其他屏保，返回 App 检查，确认一瞥屏保停用后才生效。默认离开至少 2 分钟，可选 5、10、30 分钟或 1 小时；解锁后主屏显示约 3 秒。点击诗句或署名阅读全文，其他点击、按键或滚动关闭。需要 App 运行，可关闭阅读窗口，也可按需允许登录后自动运行。
- **不自动显示**：只主动阅读和手动预览。系统仍选着一瞥屏保时，须另在系统设置停用，不能仅靠 App 内的选项关闭系统屏保。

普通打开 App 可回看最近实际展示的作品。解锁记录保存在 App 内；屏保回看与共享配景需用户允许数据访问。主 App、独立屏保须分别更新，Homebrew 只管理主 App。

macOS 14／15 的屏保入口在“系统设置 → 屏幕保护程序”；26 及以后在“系统设置 → 墙纸 → 屏幕保护程序”，也可搜索。入口以系统版本为准。

详细步骤、权限解释、升级卸载及排错见[网页使用指引](https://activationenergy.github.io/Glimpse/#guide)与[包内安装说明](Releases/v1.1.1/安装说明.txt)。

## 本版变化与测试边界

1.1 系列新增互斥展示模式、解锁三秒、可调离开时长和解锁作品回看；设置整理为三栏，并修正乾卦误分段。1.1.1 将篇名简化为“乾卦”，作者仍为“《周易》”；九篇明确题注以小字号楷体和次要墨色显示；屏保换诗可选 2／5／10／30 分钟，默认 2 分钟，下次屏保启动时生效。原文和既有展示资格不变。网页另补充了未公证屏保安装／更新的 Open Anyway 步骤。

本版采用临时签名，尚未完成 Apple 公证、完整 Gatekeeper 验证、Intel 与最低 macOS 14 真机验收。真实登录后启动与锁屏认证的系统事件时序仍需继续验证。请按系统安全提示自行决定是否允许运行，无需关闭全局安全保护。

安装包按固定版本标签保存，是仓库版本文件，并非 GitHub Release 附件。网站由 GitHub Pages 分发；源码、开发历史及编辑资料不公开。
