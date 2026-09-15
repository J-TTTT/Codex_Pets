# Miku

以用户确认的第二版 Q 版初音参考图制作。青绿色双马尾、半睁动漫眼睛、灰色上衣与黑色裙装，动作轻柔、安静。

## 使用

本地安装目录：`C:\Users\56180\.codex\pets\miku`。在 Codex 的智能拍档选择中选择 **Miku**。此交付安装为可选拍档；没有更改当前选择。

- `pet.json`：v2 拍档配置。
- `spritesheet.webp`：真正透明的 1536 × 2288 图集，8 列 × 11 行，每格 192 × 208。
- `preview.html`：所有动作的动画预览页。
- `previews/`：与安装图集相同帧的 GIF 预览。
- `qa/`：透明边缘、图集、方向盲测、连续性与独立视觉检查记录。
- `generation-prompts.md`：内置图像生成工具使用的提示词。

## 动画

| 状态 | 帧数 |
|---|---:|
| idle 待机 | 6 |
| running-right 向右移动 | 8 |
| running-left 向左移动 | 8 |
| waving 打招呼 | 4 |
| jumping 跳跃 | 5 |
| failed 失败 | 8 |
| waiting 等待用户 | 6 |
| running 工作思考 | 6 |
| review 检查结果 | 6 |

另含 16 个顺时针注视方向，从正上方开始，每 22.5° 一格。双手放松的待机与挥手打招呼分别制作。所有动作由内置图像生成工具基于角色参考生成，再由 hatch-pet 脚本提取、定位、装配并处理透明边缘。

完整验收结论、方向中的细微差异及安装文件校验值见 `qa/final-visual-qa.json`、`qa/blind-review-resolution.json` 与 `qa/run-summary.json`。
