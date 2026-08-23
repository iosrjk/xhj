# 自动更新下载链接

仓库已加入 `.github/workflows/update-releases.yml`。

- 每天自动运行一次，也可在 GitHub → Actions → `Update client release links` 手动运行。
- 检查以下仓库的 Latest Release：
  - `clash-verge-rev/clash-verge-rev`
  - `chen08209/FlClash`
  - `2dust/v2rayN`
  - `MetaCubeX/ClashMetaForAndroid`
- 自动匹配当前 `download.md` 使用的 Windows、macOS、Android 安装包。
- 检测到新版本才修改并提交 `download.md`。
- 主链接和 `gh-proxy.org/` 备用链接会同时更新。

如果 Actions 无法 push，请到仓库 Settings → Actions → General → Workflow permissions，允许 Read and write permissions。
