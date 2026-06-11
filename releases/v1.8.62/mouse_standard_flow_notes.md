# v1.8.62 mouse_standard_flow

本次构建保持显示版本号 `1.8.62`，通过 build 标识区分为 `mouse_standard_flow_20260611`。

## 更新内容

- 新增鼠标标准化检测流程。
- 标准项包括左键、右键、中键、侧键 1、侧键 2、滚轮上滚、滚轮下滚。
- 每项目标为 100 次/格，达到目标后弹出确认窗口。
- 确认结果支持正常、观察、异常、重测。
- 标准化流程与自由独立检测、RawInput 异常复测互斥，避免同一次动作被重复记录。
- 标准化流程 UI 更新做节流处理，降低长时间测试时的界面刷新压力。

## 验证

- `dotnet build AKLPeripheralDiagnosticPlatform.csproj -c Release`
- `dotnet build AKLPeripheralDiagnosticPlatform.HidppWorker.csproj -c Release`
- `build_installer.ps1`