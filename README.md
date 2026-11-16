# SnowLuma 安装包镜像

> **状态**：上游 `github.com/SnowLuma/SnowLuma` 已于 **2026-11-09** 转为 private（社区称因律师函），所有官方下载链接失效。
> 本仓库只做**发行包存档**，方便已经用 qq-bridge 的人重装环境。

## 下载

| 文件 | 版本 | 大小 | SHA256 |
| --- | --- | --- | --- |
| `SnowLuma-v2.4.2-win-x64.zip` | v2.4.2 | 41.4 MB | `0912926c5e73260f35b000278a8658493fc9452f36782c32fa86f0e825bad81a` |
| `checksums.sha256` | v2.4.2 | — | 上游原始校验清单 |

直链：

```
https://github.com/juju114514/snowluma-mirror/releases/download/v2.4.2/SnowLuma-v2.4.2-win-x64.zip
```

## 一键安装（配合 qq-bridge）

```powershell
powershell -ExecutionPolicy Bypass -File scripts\fetch-gateway.ps1 -Kind snowluma -To D:\QQBot\snowluma
```

或手动指定本镜像：

```powershell
powershell -ExecutionPolicy Bypass -File scripts\fetch-gateway.ps1 -Kind snowluma `
  -Mirror https://github.com/juju114514/snowluma-mirror/releases/download/v2.4.2/SnowLuma-v2.4.2-win-x64.zip `
  -To D:\QQBot\snowluma
```

## 说明

- 本仓库**不修改、不反编译、不再分发源码树**，只保存官方发布的原始压缩包；
- 版权与许可归 SnowLuma 原作者，使用前请遵守其非商业许可（见压缩包内 LICENSE）；
- 若有权利人认为不妥，请提 issue，我会立即删除对应文件。

## 其他镜像（备用）

- `TomyJan/SnowLuma`（483★）
- `zhx57/SnowLuma`（存档）
- `venti1112/snowluma`（备份）
- `XingYunStar/snowluma`（含 Docker 镜像）