# 表演道具图标

- `source/{ID}.png`：60 件道具的高分辨率独立源图，可单独重绘或替换。
- `{ID}.webp`：验证器实际加载的占格比例图标。
- `manifest.json`：道具名称、类型、品质和宽高映射。
- `../../scripts/build-item-icons.mjs`：源图替换后重新导出 WebP。

重新导出：

```powershell
& "C:\Users\onemt\.cache\codex-runtimes\codex-primary-runtime\dependencies\node\bin\node.exe" scripts\build-item-icons.mjs
```

统一画风：活动 UE 背景对应的手游活动插画风，手绘卡通写实、简化几何、清晰色块、古典舞台金色装饰；背景为深蓝黑色。页面按 ID 读取，因此替换单件时只需保持文件名不变。

