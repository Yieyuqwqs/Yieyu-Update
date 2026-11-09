# Yieyu-Update

Yieyu Music 的**强更清单（公开只读）**。主源码仓库保持私有，这里只放客户端启动时拉取的 `update.json`。

## 文件

- `update.json` — 客户端启动 / 回前台时静默拉取；字段：
  - `minSupportedVersion` / `minVersionCode`：低于此版本的客户端会弹不可关闭的强更死锁弹窗
  - `latestVersion` / `versionCode`：当前最新版本
  - `downloadUrl`：强更按钮跳转的下载页
  - `message`：强更弹窗文案

## 下载

安装包放在本仓库的 [Releases](../../releases)。

> 客户端不读取本仓库源码；本仓库也不包含任何源码或密钥。
