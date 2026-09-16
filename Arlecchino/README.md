# Arlecchino

以已确认的《原神》Arlecchino Q 版参考图为唯一形象依据，保留银白与黑色相间的层次发型、红色叉形瞳孔、黑白灰礼服与深红点缀、黑色手部和红色指尖。动作冷静、克制、轻巧，双手空着，始终保持人形。

## 安装与选择

将 pet.json 和 spritesheet.webp 放在同一角色文件夹中：

~~~text
~/.codex/pets/Arlecchino/
├── pet.json
└── spritesheet.webp
~~~

Windows 默认目录为 %USERPROFILE%\.codex\pets\Arlecchino；设置了 CODEX_HOME 时，使用其下的 pets/Arlecchino。

打开 Codex **设置 → 智能拍档 / Pets → 刷新 / Refresh**，选择 **Arlecchino**。在输入框输入 /pet 或从命令菜单选择 **Show pet** 显示拍档。[官方操作说明](https://learn.chatgpt.com/docs/pets?surface=app)

## 动画与素材

| 状态 | 帧数 | 表现 |
| --- | ---: | --- |
| idle | 6 | 呼吸、眨眼，发梢与衣摆轻摆 |
| running-right | 8 | 向右小步移动 |
| running-left | 8 | 独立绘制的向左小步移动 |
| waving | 4 | 小幅挥手，安静回应 |
| jumping | 5 | 屈膝、轻跳、自然落地 |
| failed | 8 | 短暂困惑后恢复镇定 |
| waiting | 6 | 轻轻摊手，耐心等待 |
| running | 6 | 手靠下巴，认真思考 |
| review | 6 | 前倾观察，点头确认 |

另含 16 个顺时针注视方向，从正上方开始，每隔 22.5° 一格。左右移动分别绘制，保留头发黑白分区和服装的不对称设计。

- spritesheet.webp：透明的 1536 × 2288 图集，8 列 × 11 行，每格 192 × 208。
- pet.json：包含 spriteVersionNumber: 2 的拍档配置。
- preview.html 和 previews/：与安装素材对应的动画预览。
- qa/：格式、透明背景、方向、连续性和独立视觉检查记录。
- generation-prompts.md：内置图像生成工具所用提示词。

验收结果、已接受的细微差异及安装文件校验记录，见 qa/final-visual-qa.json、qa/blind-review-resolution.json 和 qa/run-summary.json。
