# G.E.M. 浅蓝版

**仓库目录：`GEM-Blue-Cargo/`** · [返回拍档列表](../README.md)。仓库目录由 `G.E.M.-Blue-Cargo/` 更名，本地安装 ID `G.E.M.-Blue-Cargo` 和设置中的显示名称 **G.E.M. 浅蓝版**保持不变。

以已确认的浅蓝工装造型为唯一外观依据，保留高马尾、细辫、棕色动漫眼睛与清爽的日系手绘画风。整体活泼、亲切、俏皮，适合安静陪伴。

![待机](previews/idle.gif)

**本地标识：`G.E.M.-Blue-Cargo`** · **Codex v2**

[交互预览](interactive.html) · [动画合集](preview.html) · [原始确认图](approved-reference.png) · [中性参考](canonical-reference.webp) · [十六方向](qa/look-directions.png) · [验收记录](qa/README.md)

## 造型与连接

保留棕色高马尾与暖金棕卷曲发梢、侧边细辫、银色发饰、脸侧发束、耳饰及耳返。白色宽松短款T恤、上下分开的两条银蓝腰带及矩形扣、浅蓝宽腿工装裤、大翻盖口袋、竖向拉链、主要水钻分布，以及银白厚底鞋和白色齿纹鞋底均作为外观特征保留。

胸前为稳定的浅蓝色 GLORIA / WORLD TOUR 印花；桌面小尺寸可表现为浅蓝图形，细小水钻简化为固定手绘亮点。金色麦克风带黑色环带及深色尾部，始终由角色右手握持，正面看位于画面左侧。左右跑动分别绘制，保持服装印花及配件方向。

## 动作

| 系统状态 | 帧数 | 表现 | 预览 |
| --- | ---: | --- | --- |
| `idle` | 6 | 安静呼吸与眨眼 | [预览](previews/idle.gif) |
| `running-right` | 8 | 向右小步跑 | [预览](previews/running-right.gif) |
| `running-left` | 8 | 向左小步跑 | [预览](previews/running-left.gif) |
| `waving` | 4 | 轻柔挥手 | [预览](previews/waving.gif) |
| `jumping` | 5 | 开心小跳 | [预览](previews/jumping.gif) |
| `failed` | 8 | 小懊恼后恢复 | [预览](previews/failed.gif) |
| `waiting` | 6 | 耐心等待回应 | [预览](previews/waiting.gif) |
| `running` | 6 | 托腮专注思考 | [预览](previews/running.gif) |
| `review` | 6 | 观察与确认 | [预览](previews/review.gif) |

待机轻呼吸与眨眼，不持续唱歌或挥手。小跑双腿交替，宽裤腿与厚底鞋随步伐运动；跳跃包括轻屈膝、双脚短暂离地和自然缓冲。工作以托腮、专注眼神及点头表现；检查结果通过观察、确认及小手势区分。注视时脚底稳定，眼神与头颈自然跟随，马尾根部和麦克风连接保持一致。

## 在 Codex 中选择

独立安装目录为 `C:/Users/56180/.codex/pets/G.E.M.-Blue-Cargo/`，记录见 [installation.json](qa/installation.json)。

1. 打开 **设置 → 智能拍档 / Pets**。
2. 点击 **刷新 / Refresh**，选择 **G.E.M. 浅蓝版**。
3. 使用 `/pet` 或 **Show pet** 显示拍档。

选择与刷新步骤参照 [Codex 官方拍档说明](https://learn.chatgpt.com/docs/pets)。自定义拍档保存在本机。

黑色舞台装版、婚纱版及其他已有拍档未被覆盖。

## 文件与检查

最终透明WebP图集为1536 × 2288，8列 × 11行，每格192 × 208。9种标准动作共57帧，另有16个顺时针注视方向和中性帧。`pet.json` 包含 `spriteVersionNumber: 2`。

完成结构、透明背景、轮廓、角色一致性、衣装及道具连接、动作预览、方向语义、三人独立盲审和连续性检查。接受的轻微差异及具体依据保留在验收记录中。

完整备份包包含定义、图集、头像、参考图、动画与交互预览、[制作规格](pet_request.json)、[提示词记录](generation-prompts.md)和验收资料。迁移时，将 `pet.json` 与 `spritesheet.webp` 放在同一个 `.codex/pets/G.E.M.-Blue-Cargo/` 文件夹，再刷新拍档列表；已有同名目录时先备份。
