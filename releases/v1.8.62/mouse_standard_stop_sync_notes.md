# v1.8.62 mouse_standard_stop_sync

本次构建保持显示版本号 `1.8.62`，通过 build 标识区分为 `mouse_standard_stop_sync_20260611`。

## 更新内容

- 鼠标标准检测上方“异常观察”新增“按键异常”。
- 标准流程自动异常会立即同步到上方功能块、实时状态和检测明细。
- 按键、滚轮、移动、拖动异常按类型写入对应异常类，避免全部落到按键失灵。
- 标准流程不再强制捕获鼠标到测试区，测试过程中可以点击“中止检测”。

## 验证

- `dotnet build AKLPeripheralDiagnosticPlatform.csproj -c Release`
- `dotnet build AKLPeripheralDiagnosticPlatform.HidppWorker.csproj -c Release`
- `build_installer.ps1`