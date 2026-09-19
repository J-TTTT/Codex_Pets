# G.E.M. 文静婚纱版

安静陪伴用户的温柔歌者。保持已确认的白色舞台长裙、焦边孔洞、长头纱和金色麦克风，采用缓步、轻点头与细微眼神表达情绪。

![待机](previews/idle.gif)

**本地标识：`GEM-bridal_2`** · **Codex v2**

[交互预览](interactive.html) · [动画合集](preview.html) · [角色规范](制作规范.md) · [十六方向](qa/look-directions.png) · [验收记录](qa/README.md)

## 动作

| 系统状态 | 帧数 | 文静版表现 | 预览 |
| --- | ---: | --- | --- |
| `idle` | 6 | 安静待机 | [预览](previews/idle.gif) |
| `running-right` | 8 | 缓步向右 | [预览](previews/running-right.gif) |
| `running-left` | 8 | 缓步向左 | [预览](previews/running-left.gif) |
| `waving` | 4 | 轻柔招呼 | [预览](previews/waving.gif) |
| `jumping` | 5 | 着地喜悦 | [预览](previews/jumping.gif) |
| `failed` | 8 | 遗憾与恢复 | [预览](previews/failed.gif) |
| `waiting` | 6 | 耐心等待 | [预览](previews/waiting.gif) |
| `running` | 6 | 安静思考 | [预览](previews/running.gif) |
| `review` | 6 | 检查结果 | [预览](previews/review.gif) |

`jumping` 保留系统名称，视觉上为双脚着地的轻柔喜悦，没有跳跃或踮脚。左右移动使用独立生成的细小步伐，保留原有单肩方向和右手持麦。

## 外观与连接

棕色长卷发、明亮棕色动漫眼睛、圆润脸颊、浅腮红与金色耳饰保持参考图风格。单肩位于角色左肩，金色麦克风固定由角色右手握持。银白束腰保留竖向结构线和铜棕色做旧下缘；白色长裙及头纱保留有意设计的焦边、孔洞和内层布料。

头纱与发丝随头部轻柔跟随；注视变化主要由眼睛、头颈和少量上半身转动表达，下半身保持稳定。全部十六方向按屏幕坐标从上方开始顺时针排列。

## 选择拍档

安装状态见 [安装记录](qa/installation.json)。本机目录为 `C:/Users/56180/.codex/pets/GEM-bridal_2/`。

1. 打开 Codex **设置 → 智能拍档 / Pets**。
2. 点击 **刷新 / Refresh**，选择 **G.E.M. 文静婚纱版**。
3. 输入 `/pet`，或使用 **Show pet** 显示拍档。

其他拍档保持独立，旧版 `gem-bridal` 不受影响。参考 [官方 Pets 说明](https://learn.chatgpt.com/docs/pets?surface=app)。

## 素材与备份

图集为透明 WebP，1536 × 2288，8 列 × 11 行，每格 192 × 208。包含 57 帧标准动作、16 个注视方向及 v2 中性帧，`pet.json` 明确包含 `spriteVersionNumber: 2`。

完整 ZIP 包含此目录的说明、头像、图集、预览、提示词和验收记录。若在另一台电脑安装，将 `pet.json` 与 `spritesheet.webp` 放在同一个 `.codex/pets/GEM-bridal_2/` 子目录，然后在设置中刷新；已有同名目录时先备份。

实际生成提示词见 [generation-prompts.md](generation-prompts.md)，全部动作要求见 [pet_request.json](pet_request.json)。
