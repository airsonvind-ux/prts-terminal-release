# PRTS Terminal · Release Channel

这是 PRTS Terminal 的发布仓，只存安装包、更新清单、签名和校验和，不存源码。

- 源码：<https://github.com/airsonvind-ux/prts-terminal>
- 国内发布页：<https://gitee.com/airsonvind0/prts-terminal-release/releases>
- 当前版本：`0.1.0`

## 更新清单

GitHub 的更新清单 `latest.json` 位于最新 Release 的资产中：

```text
https://github.com/airsonvind-ux/prts-terminal-release/releases/latest/download/latest.json
```

Gitee 的更新清单位于仓库 `master` 根目录：

```text
https://gitee.com/airsonvind0/prts-terminal-release/raw/master/latest.json
```

## 验证

每个 Release 包含：

```text
PRTS Terminal_0.1.0_x64-setup.exe
PRTS Terminal_0.1.0_x64-setup.exe.sig
SHA256SUMS.txt
release-notes.md
latest.json
```

安装包使用 Tauri 更新签名；下载后请对照 `SHA256SUMS.txt`。MAA 本体不随本项目分发。
