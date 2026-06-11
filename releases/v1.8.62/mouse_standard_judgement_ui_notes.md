# v1.8.62 mouse_standard_judgement_ui

本次构建保持显示版本号 `1.8.62`，通过 build 标识区分为 `mouse_standard_judgement_ui_20260611`。

## 更新内容

- 鼠标标准化流程增加总状态、当前项目、项目结果列表和异常明细展示。
- 标准流程扩展为 9 项：左键、右键、中键、侧键 1、侧键 2、滚轮上滚、滚轮下滚、移动、左键拖动。
- 加入自动异常判定：疑似双击/抖动、重复按下未释放、卡键/释放延迟、非当前项目误触、滚轮反向、移动轨迹突变、拖动中断。
- 每项完成弹窗会显示自动检测结论；如果自动检测发现异常，即使人工确认正常也会落为观察，避免异常被直接覆盖。
- 中止检测会同步停止标准流程、鼠标检测会话和 UI 状态。

## 验证

- `dotnet build AKLPeripheralDiagnosticPlatform.csproj -c Release`
- `dotnet build AKLPeripheralDiagnosticPlatform.HidppWorker.csproj -c Release`
- `build_installer.ps1`