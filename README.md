# mu3-mods 发布镜像

本仓库向 OGKToolBox 提供已构建的 MU3 MonoMod 更新资产与更新清单。

## 来源与署名

`mu3-mods` 的源代码、Mod 实现、名称及相关文档来自
[akanyan/mu3-mods](https://gitea.tendokyu.moe/akanyan/mu3-mods)。

本仓库不宣称拥有这些 Mod 的著作权，仅分发与 OGKToolBox 更新流程兼容的上游构建产物。
功能说明、安装说明和问题反馈请优先参考上游仓库。

## 许可证

上游许可证以 `akanyan/mu3-mods` 仓库中的 LICENSE 文件为准。
发布或重新分发前，请保留上游 LICENSE、版权声明和必要的 NOTICE 文件。

## 更新

OGKToolBox 从 `manifest.json` 读取可用 Mod，并从 GitHub Release 下载对应 DLL。
每个文件均由 SHA-256 校验后安装到 `BepInEx/monomod`。
