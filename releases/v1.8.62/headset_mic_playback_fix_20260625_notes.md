# v1.8.62 headset_mic_playback_fix_20260625

- 修复耳机独立检测中麦克风录音回放听不清的问题。
- 录音回放会进行有界增益和直流偏置处理，低音量录音更容易听到。
- 软件会等待录音回放结束后再弹出确认框，避免检测员还没听完就进行判断。
- 本次不修改 HID++ 电量采样、设备识别合并、鼠标检测、键盘检测、接收器配对和在线更新传输逻辑。

Installer:

`AKLPeripheralDiagnosticPlatform_Setup_v1.8.62_headset_mic_playback_fix_20260625_111500.exe`

SHA256:

`890E31DC14E00259281C05C5F43BF518880D4CD1549146852A99BA98E4D20C3B`
