# Raiden-Shogun

以用户确认的 Q 版Raiden-Shogun为唯一外观依据，保留紫色动漫眼睛、长辫、紫花金饰、和风服装及不对称设计。双手空着，动作沉静轻柔。左右跑动分别生成。

## 在 Codex 中选择

1. 按 **Ctrl+,** 打开设置，进入 **智能拍档 / Pets**。
2. 点击 **刷新 / Refresh**，选择 **Raiden-Shogun**。
3. 在输入框输入 **/pet**，或在命令菜单选择 **Show pet**，显示浮动拍档。

也可以从应用底部的个人菜单进入 Pets。官方操作说明：[Pets](https://learn.chatgpt.com/docs/pets?surface=app)。

本地安装目录：`Raiden-Shogun`。

## 素材

- `pet.json`：含 `spriteVersionNumber: 2` 的配置。
- `spritesheet.webp`：真正透明的 1536 × 2288 图集，8 × 11 格，每格 192 × 208。
- `preview.html` 与 `previews/`：动作预览。
- `qa/`：透明、帧表、三位独立方向盲测、连续性及最终视觉检查报告。
- `generation-prompts.md`：使用内置图像生成工具的提示词记录。

| 动作 | 帧数 |
|---|---:|
| idle 待机 | 6 |
| running-right 右移 | 8 |
| running-left 左移 | 8 |
| waving 招呼 | 4 |
| jumping 跳跃 | 5 |
| failed 失败 | 8 |
| waiting 等待 | 6 |
| running 工作思考 | 6 |
| review 检查 | 6 |

另含 16 个注视方向，从正上方开始，每隔 22.5° 顺时针排列。查看 `qa/final-visual-qa.json` 与 `qa/run-summary.json` 获取最终验收和安装文件校验结论；如有接受的细微差异，记录在 `qa/blind-review-resolution.json`。