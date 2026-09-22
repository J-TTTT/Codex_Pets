# G.E.M.

以已确认的黑色舞台装形象制作，明亮、自信、亲切，带一点俏皮。保留深棕长卷发、棕色动漫眼睛、银色耳饰、短款黑色外套、深色内搭、银色装饰、长裤与短靴。

![待机](previews/idle.gif)

**本地标识：`gem-stage`** · **Codex v2**

[交互预览](interactive.html) · [动画合集](preview.html) · [原始确认形象](approved-reference.png) · [十六方向](qa/look-directions.png) · [验收记录](qa/README.md)

## 动作

| 系统状态 | 帧数 | 表现 | 预览 |
| --- | ---: | --- | --- |
| `idle` | 6 | 安静待机 | [预览](previews/idle.gif) |
| `running-right` | 8 | 小步向右跑 | [预览](previews/running-right.gif) |
| `running-left` | 8 | 小步向左跑 | [预览](previews/running-left.gif) |
| `waving` | 4 | 轻柔招呼 | [预览](previews/waving.gif) |
| `jumping` | 5 | 开心小跳 | [预览](previews/jumping.gif) |
| `failed` | 8 | 失落与恢复 | [预览](previews/failed.gif) |
| `waiting` | 6 | 等待回应 | [预览](previews/waiting.gif) |
| `running` | 6 | 专注思考 | [预览](previews/running.gif) |
| `review` | 6 | 检查结果 | [预览](previews/review.gif) |

待机以呼吸、眨眼和微小卷发晃动为主。左右跑动分别绘制，双腿交替，小幅起伏；跳跃包含起跳、离地与柔和落地。工作是空手轻靠下巴的专注思考，检查结果则以观察、确认点头和小微笑区分。

## 外观与连接

附件为唯一外观依据，中性参考只调整站姿、麦克风高度和留白。保留脸型、眼睛结构、卷发分区、身体比例及日系二次元画风。黑色无线麦克风始终由角色右手握持，正面看位于画面左侧；空着的左手参与挥手、等待和思考动作。左右姿态没有通过镜像换手，服装非对称细节保持一致。

头发、耳饰、衣服配件与麦克风按原有连接关系跟随。注视时脚底稳定，眼睛先转向，头颈和上半身轻微跟随。无整个人物旋转、脸部拉伸、新道具、文字、水印、舞台背景或地面阴影。

## 在 Codex 中选择

安装记录见 [installation.json](qa/installation.json)，独立目录为 `C:/Users/56180/.codex/pets/gem-stage/`。

1. 打开 **设置 → 智能拍档 / Pets**。
2. 点击 **刷新 / Refresh**，选择 **G.E.M.**。
3. 使用 `/pet` 或 **Show pet** 显示拍档。

婚纱版和其他已有拍档不受影响。参考 [官方 Pets 说明](https://learn.chatgpt.com/docs/pets?surface=app)。

## 素材与备份

透明 WebP 图集为1536 × 2288，8列 × 11行，每格192 × 208。9种标准动作共57帧，加16个顺时针注视方向及中性帧；`pet.json` 包含 `spriteVersionNumber: 2`。

完整ZIP包含图集、角色定义、头像、原始确认图、动画预览、实际提示词和验收记录。复制到另一台电脑时，把 `pet.json` 与 `spritesheet.webp` 放在同一个 `.codex/pets/gem-stage/` 子目录，然后刷新；已有同名目录时先备份。

详细动作要求见 [pet_request.json](pet_request.json)，实际生成提示词见 [generation-prompts.md](generation-prompts.md)。
