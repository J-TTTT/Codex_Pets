# La Signora

以用户确认的女士 Q 版参考图为唯一形象依据，保留浅金卷发、黑色华丽半面面具、灰蓝色可见眼睛、白色毛领与黑红礼服。动作从容、优雅、克制，双手空着，始终保持人形。

## 安装与选择

将 `pet.json` 和 `spritesheet.webp` 放在同一角色文件夹中：

```text
~/.codex/pets/la-signora/
├── pet.json
└── spritesheet.webp
```

Windows 默认对应 `%USERPROFILE%\.codex\pets\la-signora`；自定义 `CODEX_HOME` 时使用其下的 `pets/la-signora`。

打开 Codex **设置 → 智能拍档 / Pets → 刷新 / Refresh**，选择 **La Signora**。在输入框输入 `/pet` 或从命令菜单选择 **Show pet** 显示浮动拍档。[官方操作说明](https://learn.chatgpt.com/docs/pets?surface=app)

## 动画与素材

| 状态 | 帧数 | 表现 |
| --- | ---: | --- |
| idle | 6 | 呼吸、可见眼睛眨动、卷发与披风轻摆 |
| running-right | 8 | 向右小步移动 |
| running-left | 8 | 独立绘制的向左小步移动 |
| waving | 4 | 抬起戴手套的手，优雅招呼 |
| jumping | 5 | 蓄力、轻跳与柔和落地 |
| failed | 8 | 短暂失落后恢复镇定 |
| waiting | 6 | 轻轻摊手，等待回应 |
| running | 6 | 手靠下巴，认真思考 |
| review | 6 | 前倾观察，小幅点头确认 |

另含 16 个顺时针注视方向，从正上方开始，每隔 22.5° 一格。面具固定遮住角色自身左眼，正面对应画面右侧；左右动作不通过镜像生成。

- `spritesheet.webp`：真正透明的 1536 × 2288 图集，8 列 × 11 行，每格 192 × 208。
- `pet.json`：包含 `spriteVersionNumber: 2` 的拍档配置。
- `preview.html` 和 `previews/`：与安装素材对应的动画预览。
- `qa/`：图集、透明背景、方向、连续性和独立视觉检查记录。
- `generation-prompts.md`：内置图像生成工具所用提示词。

完整验收、已接受的细微差异及安装文件校验结果，见 `qa/final-visual-qa.json`、`qa/blind-review-resolution.json` 和 `qa/run-summary.json`。
