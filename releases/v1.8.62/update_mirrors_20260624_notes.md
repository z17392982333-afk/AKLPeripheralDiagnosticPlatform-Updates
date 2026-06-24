# v1.8.62 update_mirrors_20260624

- 新增 `downloadUrl` / `installerMirrors` 多下载源清单能力。
- 客户端下载失败时会自动尝试下一个下载源。
- 所有下载源仍统一执行 SHA256 校验。
- GitHub Release 保留为兜底源；正式提速需要把安装包同步到可信的国内或私有 HTTPS 下载源后写入 `downloadUrl`。
