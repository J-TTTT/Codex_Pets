# Codex 桌面智能拍档

让八重神子、初音未来和雷电将军陪你一起写代码。

本仓库收录三款日系 Q 版桌面拍档，使用 `hatch-pet` 制作。每款均包含透明动画图集、9 个标准动画状态，以及 16 个注视方向，可安装到支持自定义拍档的 Codex 桌面应用中。

## 认识你的拍档

| 八重神子 · 小神子 | 初音未来 · Miku | 雷电将军 · Raiden_Shogun |
| :---: | :---: | :---: |
| ![小神子待机](Yae_Miko/previews/idle.gif) | ![Miku 待机](miku/previews/idle.gif) | ![Raiden_Shogun 待机](raiden-shogun/previews/idle.gif) |
| 樱粉长发、狐耳与白红巫女服。温柔聪慧，带一点狡黠的笑意。 | 青绿色长双马尾与经典灰黑服装。安静乖巧，带一点天然呆。 | 深紫长辫、紫花金饰与和风服装。沉静端庄，动作温柔克制。 |
| [动画预览](Yae_Miko/previews/) · [下载素材包](Yae_Miko.zip) | [动画预览](miku/previews/) · [下载素材包](miku.zip) | [动画预览](raiden-shogun/previews/) · [下载素材包](raiden-shogun.zip) |

> 设置中的角色名称由 `pet.json` 的 `displayName` 决定。目前八重神子显示为 **小神子**，其余两款显示为 **Miku** 和 **Raiden_Shogun**。

## 特点

- **精致 Q 版风格**：柔和赛璐璐上色，保留角色的发型、服装与主要装饰。
- **轻柔的陪伴动作**：呼吸、眨眼、挥手、跑动、跳跃，以及等待、思考和检查结果时的不同表现。
- **16 个注视方向**：从正上方开始，按顺时针每隔 22.5° 排列。
- **真正透明背景**：安装图集使用带透明通道的 WebP，无背景场景、文字或水印。
- **下载即可安装**：使用现成素材不需要重新生成图片，也不需要安装 Python 或 hatch-pet。

## 快速开始

### 1. 下载并解压

下载上方任意一个角色的 ZIP 素材包，或使用 GitHub 的 **Code → Download ZIP** 下载整个仓库。

解压后，找到同时包含以下两个文件的角色文件夹：

```text
角色文件夹/
├── pet.json
└── spritesheet.webp
```

这两个文件是安装所必需的。`previews/`、`qa/` 和说明文档用于预览与查阅，可以留在下载目录中。

### 2. 放入本地拍档目录

**Windows**

在文件资源管理器地址栏输入：

```text
%USERPROFILE%\.codex\pets
```

如果 `pets` 文件夹不存在，手动创建即可。为每个角色创建一个独立子文件夹，并将对应的 `pet.json` 和 `spritesheet.webp` 放进去。

**macOS**

在 Finder 中选择 **前往 → 前往文件夹**，输入：

```text
~/.codex/pets
```

以安装三款角色为例，最终结构应为：

```text
.codex/
└── pets/
    ├── Yae_Miko/
    │   ├── pet.json
    │   └── spritesheet.webp
    ├── miku/
    │   ├── pet.json
    │   └── spritesheet.webp
    └── raiden-shogun/
        ├── pet.json
        └── spritesheet.webp
```

如果你自定义了 `CODEX_HOME`，请使用该目录下的 `pets/`。解压时留意文件夹层级，确保两个安装文件直接位于每个角色的子文件夹中。

### 3. 在应用中选择

1. 打开 Codex 桌面应用的 **设置 → 智能拍档 / Pets**，也可以从底部个人菜单进入 **Pets**。
2. 点击 **刷新 / Refresh**。
3. 选择 **小神子**、**Miku** 或 **Raiden_Shogun**。
4. 在输入框输入 `/pet`，或在命令菜单选择 **Show pet**，显示桌面拍档。

显示、隐藏和大小设置的入口可参考 [OpenAI 官方 Pets 使用说明](https://learn.chatgpt.com/docs/pets?surface=app)。不同应用版本的界面文字可能略有差异。

## 日常使用

- **移动位置**：拖动拍档，将她放在喜欢的桌面位置。
- **调整大小**：进入 **设置 → Pets → Customize → Pet size**。
- **隐藏拍档**：右键选择 **Hide**，或再次输入 `/pet`。
- **切换角色**：返回 **设置 → Pets**，选择另一款拍档。

拍档的任务状态由应用驱动。更换素材会改变角色外观与动画，不会改变模型能力或任务处理方式。[官方功能说明](https://learn.chatgpt.com/docs/pets?surface=app)

## 动画一览

| 状态 | 帧数 | 动作说明 |
| --- | ---: | --- |
| `idle` | 6 | 安静待机，轻微呼吸与眨眼 |
| `running-right` | 8 | 面向右方的小步跑动 |
| `running-left` | 8 | 面向左方的小步跑动 |
| `waving` | 4 | 抬手打招呼 |
| `jumping` | 5 | 蓄力、跳起与落地缓冲 |
| `failed` | 8 | 轻微失落或懊恼 |
| `waiting` | 6 | 安静等待用户回应 |
| `running` | 6 | 工作、思考与专注处理任务 |
| `review` | 6 | 仔细观察与检查结果 |

其中，`running` 是工作状态；左右跑动分别使用 `running-right` 和 `running-left`。此外，每款均包含 16 个注视方向。可在各角色的 `previews/` 文件夹中查看 GIF；如附有 `preview.html`，下载后用浏览器打开即可浏览动画合集。

## 素材结构与规格

| 文件或目录 | 用途 |
| --- | --- |
| `pet.json` | 拍档 ID、显示名称、图集路径及版本配置 |
| `spritesheet.webp` | 应用实际使用的透明动画图集 |
| `avatar.png` | 静态预览图 |
| `previews/` | 动画 GIF 预览 |
| `qa/` | 图集、透明背景、方向与视觉检查记录 |
| `generation-prompts.md` | 图片生成提示词记录 |

所有拍档使用 **v2 格式**：`spriteVersionNumber: 2`，图集尺寸为 **1536 × 2288**，按 **8 列 × 11 行** 排列，每格 **192 × 208**。

图像以角色参考图为依据，通过内置图像生成工具制作，再由 hatch-pet 完成帧提取、定位、透明背景处理、装配与检查。具体检查结论及已接受的细微差异见各角色的 `qa/` 记录。

## 常见问题

### 刷新后没有看到角色

检查 `pet.json` 和 `spritesheet.webp` 是否位于同一角色文件夹，且该文件夹直接位于正确的 `pets/` 目录下。保留原始文件名及配置中的图集路径，然后再次刷新；必要时重新启动应用。

### 设置里没有 Pets 入口

请确认使用的是提供拍档功能的桌面应用版本，并检查应用更新及工作区是否允许使用拍档。本仓库提供的是桌面 v2 素材包。

### 角色不动，只有静态画面

检查操作系统是否开启了“减少动态效果”。应用会遵循这一设置，以静态画面代替动画。[官方说明](https://learn.chatgpt.com/docs/pets?surface=app)

### 图片查看器里出现棋盘格

图片查看器可能使用棋盘格表示透明区域。实际安装时请使用原始 `spritesheet.webp`，不要用截图或 GIF 替换它，以免丢失透明通道或图集布局。

### 如何更新或移除

更新时，备份对应角色文件夹，再用新版 `pet.json` 和 `spritesheet.webp` 替换旧文件并刷新。移除时，先切换到其他拍档，再从本地 `pets/` 目录移走该角色文件夹并刷新即可。
