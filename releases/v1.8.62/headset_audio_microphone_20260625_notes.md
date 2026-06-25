# v1.8.62 headset_audio_microphone_20260625

- 耳机播放素材从音量大小检查升级为低频 150Hz、中频 1000Hz、高频 4000Hz 的频段检查。
- 保留左右声道、双声道、左右轮播、左右脉冲播放，用于确认声道错位、单边无声和断续问题。
- 耳机独立检测窗口新增麦克风 5 秒录音回放确认，检测员可选择正常、观察或异常。
- 对外报告的耳机完整性判断同步更新为低中高频播放和麦克风录音回放。
- 本次不修改 HID++ 电量采样、设备识别合并、鼠标检测、键盘检测、接收器配对和在线更新传输逻辑。

Installer:

`AKLPeripheralDiagnosticPlatform_Setup_v1.8.62_headset_audio_microphone_20260625_103000.exe`

SHA256:

`D36B3DEC3B911110EBC2654B04EAC774953D0A9F95D331E8DE7442F5BB47E9BF`
