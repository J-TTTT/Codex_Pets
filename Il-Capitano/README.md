# Il-Capitano

以已确认的《原神》Il-Capitano Q 版参考图为唯一形象依据，保留全覆式深色头盔、金色几何装饰、黑色长发、厚实毛领、胸前链饰、深色披风与靴子。动作稳重、克制，通过头盔和肢体表达状态。面部始终隐藏，头盔内部保持不透明深色，双手空着。

## 安装与选择

将 pet.json 和 spritesheet.webp 放在同一角色目录：

~~~text
~/.codex/pets/Il-Capitano/
├── pet.json
└── spritesheet.webp
~~~

Windows 默认路径为 %USERPROFILE%\.codex\pets\Il-Capitano；设置了 CODEX_HOME 时，使用其下的 pets/Il-Capitano。

打开 Codex **设置 → 智能拍档 / Pets → 刷新 / Refresh**，选择 **Il-Capitano**。输入 /pet 或从命令菜单选择 **Show pet** 显示拍档。[官方操作说明](https://learn.chatgpt.com/docs/pets?surface=app)

## 动画与素材

| 状态 | 帧数 | 表现 |
| --- | ---: | --- |
| idle | 6 | 胸肩呼吸，头盔微调、长发与披风轻摆 |
| running-right | 8 | 向右稳健小步跑动 |
| running-left | 8 | 独立绘制的向左小步跑动 |
| waving | 4 | 抬起护手，小幅挥手与点头 |
| jumping | 5 | 屈膝、轻跳、自然落地缓冲 |
| failed | 8 | 低头沉肩，停顿后恢复站姿 |
| waiting | 6 | 头盔轻歪，摊手等待回应 |
| running | 6 | 手靠头盔下缘，认真思考 |
| review | 6 | 上身前倾，头盔转向观察 |

另含 16 个顺时针注视方向，从正上方开始，每隔 22.5° 一格。通过刚性头盔的转向、俯仰和遮挡关系表达注视，不添加五官或发光眼睛。

- spritesheet.webp：真正透明的 1536 × 2288 图集，8 列 × 11 行，每格 192 × 208。
- pet.json：包含 spriteVersionNumber: 2 的拍档配置。
- preview.html 和 previews/：与安装素材对应的动画预览。
- qa/：格式、透明背景、头盔内部不透明区域、方向和视觉检查记录。
- generation-prompts.md：内置图像生成工具所用提示词。

最终验收、已接受的细微差异和安装文件校验记录见 qa/final-visual-qa.json、qa/blind-review-resolution.json 和 qa/run-summary.json。

## 验收记录

最终格式与透明背景检查通过，四个主方向获得三位独立检查者一致确认。045°、202.5°、315° 的部分方向线索在无标签盲测中存在分歧，经原尺寸帧表及连续动画复核，保留为轻微差异。337.5° → 000° 的抬头幅度略大，身体与脚底保持稳定；详细记录见 qa/blind-review-resolution.json。此前未通过的版本及检查结果保留在 qa/candidate-1/，安装使用的是修正后的最终图集。
